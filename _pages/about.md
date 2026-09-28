---
permalink: /
title: #"About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



Hi! My name is Nikita Rajaneesh. 
I'm a machine learning researcher and engineer with experience in agent and model evaluation, multimodal
models, test-time adaptation and ML infrastructure (4+ years in industry and 3+ years in academia).
{: .intro-lead}

I completed (May 2025) the Advanced Master’s Research Program at Columbia University focused in AI/ML, advised by [Prof. Richard Zemel](https://scholar.google.com/citations?user=iBeDoRAAAAAJ&hl=en). 

Here's my [CV](/files/Nikita_Rajaneesh_CV.pdf).

I've highlighted a few research projects below — my full [experience](/experience/) is on its own page.

# Research 

### Test-Time Warmup for Multimodal Large Language Models
**Nikita Rajaneesh**, Thomas P Zollo, and Richard Zemel.

**As part of my masters thesis**, in collaboration with Thomas Zollo and under the supervision of Prof. Richard Zemel.

Full paper: [arXiv:2509.10641](https://arxiv.org/abs/2509.10641)

[Github repository](https://github.com/nrajanee/test-time-warmup-mllms)

Multimodal Large Language Models (MLLMs) hold great promise for advanced reasoning at the intersection of text and images, yet they have not fully realized this potential. MLLMs typically integrate an LLM, a vision encoder, and a connector that maps the vision encoder's embeddings into the LLM's text embedding space. Although each component is pretrained on massive datasets with billions of samples, the entire multimodal model is typically trained on only thousands (or a few million) samples, which can result in weak performance on complex reasoning tasks. To address these shortcomings, instead of relying on extensive labeled datasets for fine-tuning, we propose a Test-Time Warmup method that adapts the MLLM per test instance by leveraging data from weakly supervised auxiliary tasks. With our approach, we observe a relative performance improvement of 4.03% on MMMU, 5.28% on VQA-Rad, and 1.63% on GQA on the Llama-Vision-Instruct model. Our method demonstrates that 'warming up' before inference can enhance MLLMs' robustness across diverse reasoning tasks.

### Towards effective discrimination testing for generative AI
Thomas P Zollo, **Nikita Rajaneesh**, Richard Zemel, Talia B. Gillis, and Emily Black. Towards effective
discrimination testing for generative AI. In Fairness, Accountability and Transparency (FAccT), 2025. 

Full Paper: [https://arxiv.org/abs/2412.21052](https://arxiv.org/abs/2412.21052)

[Github repository](https://github.com/thomaspzollo/dhacking)

Generative AI (GenAI) models present new challenges in regulating against discriminatory behavior. In this paper, we argue that GenAI fairness research still has not met these challenges; instead, a significant gap remains between existing bias assessment methods and regulatory goals. Through four case studies, we demonstrate how this misalignment between fairness testing techniques and regulatory goals can result in discriminatory outcomes in real-world deployments, especially in adaptive or complex environments. We offer practical recommendations for improving discrimination testing to better align with regulatory goals and enhance the reliability of fairness assessments in future deployments.

### On Equalized Odds in Supervised Learning, for the Special Case of Non-Decreasing Conditional Event Probabilities
Kent Quanrud and **Nikita Rajaneesh**.

Manuscript: [On Equalized Odds in Supervised Learning](/files/equalizedodds_ced.pdf)

Algorithmic fairness is an increasingly important aspect of algorithm design as algorithms play an increasing role in society. There are many competing notions of algorithmic fairness and here we consider a well studied notion called equalized odds. For a given classification problem, equalized odds requires the amount of false positive error to be equal across demographics and the amount of true positive error to be equal across demographics. Foundational work by Hardt, Price, and Srebro considers the problem of taking an existing classifier or a rating system as a black box and deriving another classifier satisfying equalized odds and otherwise minimizing the error. They gave a polynomial time algorithm that produces a fairly simple classifier that is optimal (in a particular sense, with respect to a given loss function) among those that satisfy equalized odds. In this work, we further the research direction of Hardt, Price, and Srebro and in particular we consider the same problem for the special and canonical case of algorithmic scoring systems that exhibit non-decreasing conditional event probabilities. Non-decreasing conditional event probabilities is a natural property inherent to reasonable scoring systems. We show that for scoring systems with non-decreasing event probabilities the optimal derived classifier can always be obtained by an extremely simple, randomized one-threshold classifier, which involves only a single threshold for each demographic. Moreover, the optimal randomized one-threshold classifier can be computed efficiently. Given the ubiquity of non-decreasing conditional event probabilities, constructing such a radically simple mechanism to achieve equalized odds, that is also optimal among those that achieve equalized odds, is valuable from the perspective of transparency. It gives interesting structural insight into equalized odds in general, which we also discuss.


# Work Experience

I'm a Founding Research Engineer at Odva AI. Before that I was a Machine Learning Research
Engineer at Arklex.AI, working on automated agent evaluation, and a machine learning researcher in Prof. Richard
Zemel's group at Columbia, and a software engineer at Determined AI (HPE) and Morningstar.

The full history — roles, education and skills — is on my [experience page](/experience/),
and the condensed version is in my [CV](/files/Nikita_Rajaneesh_CV.pdf).
