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

I'm actively looking for new roles focused on safe, robust and human-compatible AI. I am open to opportunities in applied AI research and engineering.

I completed (May 2025) the Advanced Master’s Research Program at Columbia University focused in AI/ML, advised by [Prof. Richard Zemel](https://scholar.google.com/citations?user=iBeDoRAAAAAJ&hl=en). 

Here's my [CV](/files/Nikita_Rajaneesh_CV.pdf).

I've highlighted a few research projects and some work experience below. 

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

### Machine Learning Research Engineer, Arklex.AI 
July 2025 - Present, New York, NY

· Own the end-to-end agent evaluation component of the flagship product, covering scenario design, conversation simulation, and automated agent evaluation, turning ad-hoc agent testing into a systematic, repeatable evaluation framework.

· Built a taxonomy of agent-behavior failure modes plus tooling to surface unique, high-signal errors and trace each back to targeted code-level fixes, tightening the debug loop for agent building.

· Developed a novel NLP framework to adaptively generate scenarios from real conversations, increasing coverage of real errors by 15% for a leading education company.

· Implemented an ML algorithm that improves alignment of LLM judges to domain experts by 20%.


### Software Engineer, (AI/ML), Determined AI (HPE company) 
February 2022 - June 2023, Chicago, IL

· Developed software to enable users to customize hyperparameter-tuning with Determined’s Deep Learning platform. Designed the software to ensure fault tolerance and distributed computation. ([github commit](https://github.com/determined-ai/determined/commit/60e5fe145a6e4be9539b792535579f15340639ac))

· Developed a framework for an adversarial library toolkit that is integrable with deep learning platform.

· Wrote Python SDK and Go API for user management and authentication for model registry. ([github commit 1](https://github.com/determined-ai/determined/commit/9a7c8b9ec7e8340352ca07e36f9e81b5132ee7c8), [github commit 2](https://github.com/determined-ai/determined/commit/52d1111b82e9e6667bb8f37cd3c966e4b0cec3fc), [github commit 3](https://github.com/determined-ai/determined/commit/1ae77fd5d6642f8a7837513f2688418222c4fc44), [github commit 4](https://github.com/determined-ai/determined/commit/b279bb5b0e81336ff0be03a3307133fe52a1450b))

· Built functionality to delete checkpoints saved during model training. ([github commit](https://github.com/determined-ai/determined/commit/42615b4b1730e40e2702d9ead5b2d31d88e31c0a))

· Built a tool to enable easy debugging of trials in model experiments. ([github commit](https://github.com/determined-ai/determined/commit/9032f67c1b9922e011d2104248f02a534733ccd6))


### Software Engineer, Morningstar 
August 2020 - Feb 2022, Chicago, IL

· Developed software (using vaderSentiment and spaCy) to perform Sentiment Analysis on fund reviews.

· Developed an audit process (with AWS architecture) which collects metadata of tables in the Datalake.

· Worked with AWS lambda, AWS Glue jobs and Spark to parse and write AWS s3 access and cloudtrail
logs to parquet files.


### Software Engineering Intern, Morningstar 
June 2019 - August 2019, Chicago, IL

· Developed software that allows users to do analytics on the usage data of the Datalake.

· Developed software that helps users get access to the glue catalog in the Datalake by using AWS Glue API and Apache Airflow.


### Software Engineering Intern, Jobcase 
June 2018 - August 2018, Boston, MA

· Developed a "view history" functionality using Java Hibernate in an AngularJS web app called "Scheduler" to allow a user to record changes to a scheduled process.

· Developed a regular expressions based approach to automatically populate job requirements' fields to reduce job search time for a user. Used ElasticSearch and developed a parsing tool in Java to test and analyze the proposed approach.