---
layout: single
title: "Experience"
permalink: /experience/
author_profile: true
---

Machine learning researcher and engineer with 4+ years in industry and 3+ years in academia, working on agent and model evaluation, multimodal models, test-time adaptation, and ML infrastructure.

The short version is in my [CV](/files/Nikita_Rajaneesh_CV.pdf).

# Work

### Machine Learning Research Engineer, Arklex.AI
July 2025 - Present, New York, NY

· Own automated agent evaluation within the flagship product's end-to-end pipeline (scenario design → conversation simulation → evaluation), turning ad-hoc agent testing into a repeatable framework.

· Built a taxonomy of agent-behavior failure modes plus tooling to surface unique, high-signal errors and trace each back to targeted code-level fixes, tightening the debug loop for agent building.

· Developed a novel NLP framework to adaptively generate scenarios from real conversations, increasing coverage of real errors by 15% for a leading education company.

· Implemented an ML algorithm that improves alignment of LLM judges to domain experts by 20%.

### Machine Learning Researcher, Zgroup (Columbia University)
September 2023 - May 2025, New York, NY

· Developed an unsupervised test-time adaptation method for multimodal LLMs that fine-tunes on a weakly supervised auxiliary task to boost generalization in label-scarce domains like medicine, yielding relative gains of 4.03% on MMMU, 5.28% on VQA-Rad (medical), and 1.63% on GQA.

· Demonstrated how variability in bias-testing methods (e.g., red-teaming) can let unfair models appear compliant, and how single-turn evaluations miss biases emerging in multi-turn interactions.

· Benchmarked state-of-the-art LLM uncertainty-quantification techniques (semantic uncertainty, eigenscore) in the multimodal setting, extending their evaluation beyond text-only models.

· Designed a computationally efficient UQ method leveraging image-informed priors that matches existing LLM-based UQ baselines while cutting computational overhead.

· Built an algorithm to reconstruct the weights of black-box CNNs.

### Software Engineer (AI/ML), Determined AI (HPE company)
February 2022 - June 2023, Chicago, IL

· Developed software to enable users to customize hyperparameter tuning with Determined's deep learning platform. Designed the software to ensure fault tolerance and distributed computation. ([github commit](https://github.com/determined-ai/determined/commit/60e5fe145a6e4be9539b792535579f15340639ac))

· Developed a framework for an adversarial library toolkit that is integrable with the deep learning platform.

· Wrote Python SDK and Go API for user management and authentication for model registry. ([github commit 1](https://github.com/determined-ai/determined/commit/9a7c8b9ec7e8340352ca07e36f9e81b5132ee7c8), [github commit 2](https://github.com/determined-ai/determined/commit/52d1111b82e9e6667bb8f37cd3c966e4b0cec3fc), [github commit 3](https://github.com/determined-ai/determined/commit/1ae77fd5d6642f8a7837513f2688418222c4fc44), [github commit 4](https://github.com/determined-ai/determined/commit/b279bb5b0e81336ff0be03a3307133fe52a1450b))

· Built functionality to delete checkpoints saved during model training. ([github commit](https://github.com/determined-ai/determined/commit/42615b4b1730e40e2702d9ead5b2d31d88e31c0a))

· Built a tool to enable easy debugging of trials in model experiments. ([github commit](https://github.com/determined-ai/determined/commit/9032f67c1b9922e011d2104248f02a534733ccd6))

### Software Engineer, Morningstar, Inc.
August 2020 - February 2022, Chicago, IL

· Developed software (using vaderSentiment and spaCy) to perform sentiment analysis on fund reviews.

· Developed an audit process (with AWS architecture) which collects metadata of tables in the Datalake.

· Worked with AWS Lambda, AWS Glue jobs and Spark to parse and write AWS S3 access and CloudTrail logs to parquet files.

### Machine Learning Researcher, Purdue University
January 2020 - August 2020, West Lafayette, IN

· Extended the Hardt–Price–Srebro equalized-odds framework to the special case of scoring systems with non-decreasing conditional event probabilities, proving that a universally optimal fair classifier exists in this setting.

· Showed this optimal classifier reduces to a single randomized threshold per demographic group, making it simple, explainable to policymakers, and computable in polynomial time.

· Co-authored the resulting paper, [On Equalized Odds in Supervised Learning, for the Special Case of Non-Decreasing Conditional Event Probabilities](/files/equalizedodds_ced.pdf), with Prof. Kent Quanrud.

### Software Engineering Intern, Morningstar, Inc.
June 2019 - August 2019, Chicago, IL

· Developed software that allows users to do analytics on the usage data of the Datalake.

· Developed software that helps users get access to the Glue catalog in the Datalake by using the AWS Glue API and Apache Airflow.

### Software Engineering Intern, Jobcase, Inc.
June 2018 - August 2018, Boston, MA

· Developed a "view history" functionality using Java Hibernate in an AngularJS web app called "Scheduler" to allow a user to record changes to a scheduled process.

· Developed a regular expressions based approach to automatically populate job requirements' fields to reduce job search time for a user. Used ElasticSearch and developed a parsing tool in Java to test and analyze the proposed approach.

# Education

### Columbia University
September 2023 - May 2025, New York, NY

Advanced Master's Research program, advised by [Prof. Richard Zemel](https://scholar.google.com/citations?user=iBeDoRAAAAAJ&hl=en). GPA: 3.91/4.0.

Selected coursework: deep learning, computational learning theory, continual learning, datasets in ML, computational aspects of robotics.

### Purdue University
August 2016 - May 2020, West Lafayette, IN

BS in Computer Science (Honors) and a minor in Mathematics. GPA: 3.82/4.0. Dean's List and Semester Honors every semester.

Selected coursework: randomized algorithms (graduate-level), natural language processing (graduate-level), machine learning, artificial intelligence, analysis of algorithms, compilers, linear algebra.

# Skills

**Languages:** Python, Go, C/C++, Java, TypeScript, Scala, SQL, R, MATLAB

**Tools:** PyTorch, Hugging Face, vLLM, TensorFlow, AWS, Docker, Pandas, Spark, NumPy

**Research areas:** agent and model evaluation, multimodal LLMs, test-time adaptation, fairness and discrimination testing, uncertainty quantification, distributed deep learning
