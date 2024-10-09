---
layout: page
title: Benchmarking ChatGPT for Persian
description: Natural Language Processing Lab, University of Tehran
img: assets/img/BenchmarkingChatGPTForPersian.jpg
importance: 1
category: Reseach Projects
related_publications: false
---

I was part of the Natural Language Processing lab in the ECE department, where I co-authored a published article titled **“Benchmarking Large Language Models for Persian: A Preliminary Study Focusing on ChatGPT”** under the supervision of [Prof. Y. Yaghoobzadeh](https://scholar.google.com/citations?user=TvGqaqAAAAAJ&hl=en).

This paper, accepted at the [LREC-COLING 2024](https://lrec-coling-2024.org/) conference, evaluates the performance of popular large language models (LLMs) on the Persian language, highlighting the absence of a comprehensive benchmark and analyzing state-of-the-art LLMs to identify areas for improvement. The study covers various NLP tasks in classical, reasoning, and knowledge-based domains. My specific contributions were focused on sentiment analysis and emotion recognition using the ParsiNLU and ArmanEmo datasets, respectively.

I explored how multilingual LLMs perform in the Persian language when given only instructions and few-shot examples for these tasks. Our experiments revealed several interesting findings, such as the better performance of English task descriptions over Persian in both tasks. Additionally, while increasing the number of shots did not significantly enhance GPT-3.5’s performance, it dramatically improved GPT-4’s results. Ultimately, the fine-tuned mT5 model using LoRA achieved state-of-the-art performance on both tasks.

You can find the research paper in [publication section](https://hadi-loo.github.io/publications/). Also, the code and other material are available on the [GitHub repository](https://github.com/Hadi-loo/Benchmarking_ChatGPT_for_Persian).
