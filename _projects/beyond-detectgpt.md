---
title: "Beyond DetectGPT: Towards AI-generated Text Detection in a Black-box Setting"
excerpt: Course Research Project <br/><img src='/images/detectgpt.jpg'>
collection: projects
---

*Final project for DS-GA 1012 Natural Language Understanding and Computational Semantics (graduate-level), supervised by Dr. Sophie Hao. The project is done collaboratively by Bale Chen, Corey Chen, Richen Du, and Manli Zhao.*

Recently, we have witnessed many releases of highly capable large natural language generation (NLG) models, which elicits potential issues like plagiarism. It is essential to develop a reliable detector to distinguish between human and machine-generated text. Our paper builds upon the [DetectGPT](https://arxiv.org/abs/2301.11305) framework and generalizes it to a more challenging black-box setting where we cannot access the model that generates the content. We proposed a fine-tuned OPT approach that consistently outperforms other methods in the black-box setting but fails to match up with the white-box DetectGPT. We also analyzed potential reasons for the poor performance of the ensemble method and noising perturbation. Lastly, accuracy under false positive control (AFC) is shown to be a better metric than AUROC score in the context of AI-generated text detection. Our findings show that the fine-tuned OPT method is an efficient approach to the black-box AI-generated text detection task and has the potential to generalize DetectGPT to a black-box setting.


[[Code](https://github.com/BaleChen/nlu-final-project/tree/main)] [[Report](https://github.com/BaleChen/nlu-final-project/blob/main/NLU-final-paper.pdf)]
