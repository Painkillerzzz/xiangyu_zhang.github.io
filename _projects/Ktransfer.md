---
title: "Ktransfer: Exploring Knowledge-Agnostic Prompt Domains for Cross-Domain Question Answering"
excerpt: "We build and trained retrievers across knowledge-agnostic domains for multi-choice question answering."
collection: projects
---

Knowledge transfer across domains has become a challenge in retrieve augmented generation (RAG), especially in scenarios where data from the target domain is scarce or unavailable. This project, Ktransfer, investigates whether knowledge-agnostic prompt domains (shot domains) can aid multi-choice question answering in a target domain (test domain). The study is conducted in two phases:

1. Baseline Validation: Using cosine similarity as a naive retriever, we examine the effectiveness of few-shot examples from the shot domain in improving the target domain's performance. The results reveal negligible impact, highlighting the limitations of cosine similarity in knowledge-agnostic scenarios.

2. Enhanced Retrieval Model: By randomly selecting few-shot examples, we construct positive and negative pairs for pairwise learning. A Transformer-based retrieval model is then trained on these pairs to better align shot and test domains. Evaluation shows that the retrieval model outperforms random selection and naive similarity-based methods, demonstrating its potential to bridge the gap between domains.

This work sheds light on the importance of carefully designed retrievers for cross-domain knowledge transfer. It paves the way for more advanced retrieval strategies, such as incorporating domain-specific embeddings and contextual hints. Future directions include analyzing the retrieval model's performance across diverse domains and refining its architecture for improved scalability and efficiency.

Slides: [Ktransfer Project Overview](/files/projects/Ktransfer_Project_Presentation.pdf)

Link: Coming Soon
[GitHub Repository](https://github.com/ljr040929/jittor-I_do_not_play_Honkai_StarRail-2)