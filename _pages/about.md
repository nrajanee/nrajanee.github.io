---
permalink: /
title: #"About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



Hi! My name is Nikita Rajaneesh. I am completing the Advanced Master’s Research Program at Columbia University focused in AI/ML, advised by [Prof. Richard Zemel](https://scholar.google.com/citations?user=iBeDoRAAAAAJ&hl=en). 

I am broadly interested in responsible, robust, and safe AI. My research focuses on AI robustness and safety, particularly in multimodal large language models and their applications, including in healthcare. Additionally, I have been actively participating in Prof Zemel's Continual Learning working group. 

After graduation, (in May 2025), I want to contribute to building more trustworthy and resilient AI systems. I am open to opportunities in applied AI research and engineering.

Here's my [CV](/files/Nikita_Rajaneesh_CV.pdf).

I've highlighted a few research projects and some work experience below. 

# Research 

### Towards effective discrimination testing for generative AI
Thomas P Zollo, **Nikita Rajaneesh**, Richard Zemel, Talia B. Gillis, and Emily Black. Towards effective
discrimination testing for generative AI. In ICLR 2025 Workshop on Building Trust in Language Models
and Applications, 2025. 

Full Paper: [arXiv:2412.21052](https://arxiv.org/abs/2412.21052)

[Github repository](https://github.com/thomaspzollo/dhacking)

Generative AI (GenAI) models present new challenges in regulating against discriminatory behavior. In this paper, we argue that GenAI fairness research still has not met these challenges; instead, a significant gap remains between existing bias assessment methods and regulatory goals. Through four case studies, we demonstrate how this misalignment between fairness testing techniques and regulatory goals can result in discriminatory outcomes in real-world deployments, especially in adaptive or complex environments. We offer practical recommendations for improving discrimination testing to better align with regulatory goals and enhance the reliability of fairness assessments in future deployments.

### Unsupervised Domain Adaptation for Multimodal Large Language Models. 

**As part of my masters thesis**, in collaboration with Thomas Zollo and under the supervision of Prof. Richard Zemel. 

[Paper:] Coming soon

[Github] Coming soon

We propose a novel unsupervised domain adaptation approach for
improving generalization in Multimodal large language models. Instead of relying on extensive labeled datasets, our method leverages a weakly supervised auxiliary task to guide adaptation, allowing the model to refine its representations in new domains
without requiring large amounts of high-quality annotations. Our algorithm aims to preserve the model’s rich pre-training knowledge while enhancing its ability to generalize to diverse, real-world tasks. 

**Results so far**: Our method has shown a 5.62% relative improvement in accuracy in [GQA](https://cs.stanford.edu/people/dorarad/gqa/about.html) (QA on image scene graphs) dataset and a 2.6% relative improvement in accuracy in a medical dataset [VQA-Rad](https://paperswithcode.com/dataset/vqa-rad).


# Work Experience 

### Software Engineer, (AI/ML), Determined AI 
February 2022 - June 2023

· Developed software to enable users to customize hyperparameter-tuning with Determined’s Deep Learning platform. Designed the software to ensure fault tolerance and distributed computation. ([github commit](https://github.com/determined-ai/determined/commit/60e5fe145a6e4be9539b792535579f15340639ac))

· Developed a framework for an adversarial library toolkit that is integrable with deep learning platform.

· Wrote Python SDK and Go API for user management and authentication for model registry. ([github commit 1](https://github.com/determined-ai/determined/commit/9a7c8b9ec7e8340352ca07e36f9e81b5132ee7c8), [github commit 2](https://github.com/determined-ai/determined/commit/52d1111b82e9e6667bb8f37cd3c966e4b0cec3fc), [github commit 3](https://github.com/determined-ai/determined/commit/1ae77fd5d6642f8a7837513f2688418222c4fc44), [github commit 4](https://github.com/determined-ai/determined/commit/b279bb5b0e81336ff0be03a3307133fe52a1450b))

· Built functionality to delete checkpoints saved during model training. ([github commit](https://github.com/determined-ai/determined/commit/42615b4b1730e40e2702d9ead5b2d31d88e31c0a))

· Built a tool to enable easy debugging of trials in model experiments. ([github commit](https://github.com/determined-ai/determined/commit/9032f67c1b9922e011d2104248f02a534733ccd6))


### Software Engineer, Morningstar 
August 2020 - Feb 2022

· Developed software (using vaderSentiment and spaCy) to perform Sentiment Analysis on fund reviews.

· Developed an audit process (with AWS architecture) which collects metadata of tables in the Datalake.

· Worked with AWS lambda, AWS Glue jobs and Spark to parse and write AWS s3 access and cloudtrail
logs to parquet files.