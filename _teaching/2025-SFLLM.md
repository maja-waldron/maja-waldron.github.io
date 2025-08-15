---
title: "Statistical Frontiers in Foundation Models and LLMs"
collection: teaching
type: "STAT 992"
permalink: /teaching/2025-SFLLM
venue: "UW - Madison, Department of Statistics"
date: 2025-09-05
location: "Madison, WI"
---
In this graduate seminar we will explore statistical frontiers in foundation models and large language models (LLMs).

Course Description
======
*Statistical Frontiers in Foundation Models and LLMs* explores the emerging intersection between modern statistical thinking and the capabilities of large-scale foundation models such as large language models (LLMs), vision-language models (VLMs), and diffusion models. While foundation models have achieved remarkable empirical success, they raise foundational questions about uncertainty, reliability, generalization, and inference—core concerns of the statistical sciences. This course examines how statistical tools and perspectives can help us rigorously evaluate, understand, and extend the capabilities of these models, and how in turn, foundation models may offer new tools for statisticians.

We begin by introducing foundation models from a statistical viewpoint, emphasizing why concepts such as calibration, entropy, and generalization remain central in the age of large-scale deep learning. Students will critically examine techniques for evaluating model reliability, including calibration accuracy, posterior consistency, and other statistical quantities. The seminar then turns to modern approaches for uncertainty quantification in generative models and LLMs, such as conformal prediction and deep ensembles, highlighting both the theoretical underpinnings and practical challenges of deploying these systems in safety-critical domains. Finally, we explore how foundation models can be used to perform statistical tasks themselves—such as assisting in Bayesian inference, simulation-based inference, and prediction-powered inference—marking a shift from models as objects of analysis to models as computational subroutines in statistical tasks.

Throughout the course, students will engage deeply with contemporary research papers at the frontier of statistics and machine learning, with an emphasis on developing the tools to evaluate and innovate in this rapidly evolving landscape.

Topics
======
### **Topic 1: What are Foundation Models and Why Should Statisticians Care?**

**Title:** *Should Statisticians Care About Foundation Models?*

We set the stage for the seminar by defining what foundation models are (e.g., LLMs, VLMs, diffusion models), how they differ from traditional statistical models, and why their empirical power raises new theoretical and practical questions. We also discuss the role of statistical thinking in evaluating and repurposing these models for scientific inference, decision-making, and societal impact.

- [An Overview of Large Language Models for Statisticians](https://arxiv.org/abs/2502.17814)
- [Do Large Language Models (Really) Need Statistical Foundations?](https://arxiv.org/abs/2505.19145)
- [Position: Bayesian Deep Learning is Needed in the Age of Large-Scale AI](https://arxiv.org/abs/2402.00809)


### **Topic 2: Statistical Evaluation of Foundation Models**

**Title:** *Measuring What Matters: Statistical Lenses on Model Behavior*

Foundation models are often evaluated in terms of benchmarks or task accuracy—but what does it mean for them to be statistically *reliable* or *trustworthy*? This module explores evaluation through the lens of calibration, entropy, consistency, and statistical diagnostics. We treat models as black boxes and use classical statistical tools to probe the quality of their predictions and generations.

We might also read papers about watermarking. Watermarking straddles the line between statistical evaluation of foundation models and intervention: Statistical signals can be embedded into model outputs—intentionally or inadvertently. Such signals can be detected, analyzed, and potentially used for provenance, accountability, and robustness. 

https://aclanthology.org/2020.emnlp-main.21/

https://arxiv.org/abs/2207.07411

https://arxiv.org/html/2312.04021v1

https://aclanthology.org/2023.mmnlg-1.1/

https://arxiv.org/abs/2306.13063

https://arxiv.org/abs/2307.10236

https://arxiv.org/abs/2402.14418

https://arxiv.org/abs/2506.13831

https://arxiv.org/abs/2405.02917

https://arxiv.org/abs/1906.05664

https://arxiv.org/abs/2312.15576v1

https://arxiv.org/abs/2411.02603

https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00410/107384/Measuring-and-Improving-Consistency-in-Pretrained

https://arxiv.org/abs/2310.03957

https://proceedings.mlr.press/v202/kirchenbauer23a.html

https://arxiv.org/abs/2404.01245

---

### **Topic 3: Statistical Methods for Uncertainty Quantification**

**Title:** *What Do You (Think You) Know? Quantifying Uncertainty in Foundation Models*

When foundation models are deployed in high-stakes settings, uncertainty is as important as accuracy. This module focuses on statistical techniques for quantifying predictive uncertainty—including conformal prediction, deep ensembles, Laplace approximations, and attention-based uncertainty metrics. We discuss both theoretical guarantees and empirical behavior under distribution shift.

https://arxiv.org/abs/2107.07511

https://arxiv.org/abs/1612.01474

https://proceedings.neurips.cc/paper/2021/hash/a7c9585703d275249f30a088cebba0ad-Abstract.html

https://aclanthology.org/2024.acl-long.276/

https://arxiv.org/abs/2310.00035

https://arxiv.org/abs/2308.13111

https://proceedings.neurips.cc/paper_files/paper/2024/hash/7d53575463291ea6b5a23cf6e571f59b-Abstract-Conference.html

https://openreview.net/forum?id=512IkGDqA8

https://arxiv.org/abs/2502.20946

https://arxiv.org/abs/2305.18404

https://arxiv.org/abs/2305.02633

https://openreview.net/forum?id=gENDUvkytD

https://arxiv.org/abs/2312.17162

https://arxiv.org/abs/2403.09869

https://openreview.net/forum?id=37fM2QEBSE

---

### **Topic 4: Foundation Models for Statistical Inference**

**Title:** *From Model to Oracle: Using Foundation Models in the Service of Inference*

Beyond being objects of analysis, foundation models can act as tools in statistical workflows. This module explores how LLMs and generative models can assist in Bayesian inference, simulation-based inference (SBI), and prediction-powered inference. We consider the opportunities and pitfalls of using models as simulators, priors, or query engines in structured inference problems.

https://arxiv.org/abs/2311.01453

https://arxiv.org/abs/2301.09633

https://arxiv.org/abs/2304.07438

https://arxiv.org/abs/2112.10510

https://proceedings.mlr.press/v202/nagler23a

https://arxiv.org/abs/2501.16825

https://arxiv.org/abs/2505.11325

https://arxiv.org/abs/2404.09636

