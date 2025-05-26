---
title: "Self-Certainty Guided Test-Time Scaling for Web Agents"
excerpt: "We implemented a self-certainty guided R-MCTS method for web agents.<br/><img src='/xiangyu_zhang.github.io/images/projects/SCATS.png'>"
collection: projects
---

Large language models (LLMs) are increasingly deployed in real-world interactive environments where response quality and decision efficiency are both critical. We propose a adaptive test-time scaling strategy facing response selection based on self-certainty, a confidence measure computed from the model’s own token-level log-probabilities to adaptively control branching and inference cost. 

Evaluated on the VisualWebArena and WebArena benchmark, our method consistently outperforms the baselines, achieving a +3.6% improvement in average success rate while reducing prompt token usage by over 80%. These results highlight the utility of internal confidence estimation in balancing exploration and efficiency, paving the way for more selective and scalable test-time inference in LLM based agents.

Video Presentation: [Video URL](https://drive.google.com/file/d/190pQZZ86I8k8q5mrGcUH2Isqd5wSNMV_/view?usp=drive_link)

Slides: [SC-ATS Project Overview](/xiangyu_zhang.github.io/files/projects/SCATS.pdf)

Link: [GitHub Repository](https://github.com/Painkillerzzz/SC-ATS)