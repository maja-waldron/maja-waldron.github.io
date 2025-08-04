---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile. I have previously been publishing under my maiden name Rudolph.</a>.</div>
{% endif %}

{% include base_path %}

{% for pub in site.publications reversed %}
  <div class="pub-entry">
    <strong>{{ pub.title }}</strong><br>
    {% if pub.authors %}{{ pub.authors }}.<br>{% endif %}
    {% if pub.venue %}<em>{{ pub.venue }}</em>, {% endif %}
    {% if pub.date %}{{ pub.date | date: "%Y" }}{% endif %}
  </div>
  <br>
{% endfor %}

<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}



