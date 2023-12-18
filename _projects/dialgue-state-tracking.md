---
title: "Dialogue State Tracking Using Large Language Models"
excerpt: Data Science Capstone Research <br/><img src='/images/rl-sac-project.png'>
collection: projects
---

*Data Science Capstone Research at NYU Shanghai by Bale Chen, Peiyang Wu, and Xiaocheng Yang, supervised by [Prof. Wilson Tam](https://shanghai.nyu.edu/academics/faculty/directory/yik-cheung-wilson-tam). *

This project explores the task of Dialogue State Tracking (DST) in task-oriented dialogue systems. DST involves understanding and tracking user intentions in multi-turn dialogues, typically represented as slot-value pairs. The study reviews various DST methods, highlighting limitations in classification-based and span extraction-based approaches. The paper adopts a generative approach, leveraging large language models (LLMs) to improve performance. Experimenting with different formulations, model scaling, and data scaling, the study demonstrates the feasibility of using LLMs for DST, achieving a new state-of-the-art on MultiWOZ 2.2 and 2.4 benchmarks. The slot-level question-answering formulation is shown to enhance LLM performance, reducing hallucination. Additionally, the paper provides insights into the influence of model scaling and data scaling on DST performance, contributing to a comprehensive understanding of the subject.

[[Code](https://github.com/BaleChen/dst-capstone)] [[Report](https://github.com/BaleChen/dst-capstone/blob/main/Final_Report.pdf)]