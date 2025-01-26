---
title: "Enhancing LLM’s Coding Ability by Tree-Based Searching Methods"
excerpt: "We implement MCTS and Tree of Thought to guide code synthesis based on execution feedback.<br/><img src='/xiangyu_zhang.github.io/images/projects/tree-search.png'>"
collection: projects
---

Code generation is a key challenge in machine learning, requiring models to produce accurate code based on problem descriptions. This study examines reinforcement learning methods for code generation using a dataset of 76 programming problems with test cases. Four approaches are explored: Best-of-N (Vanilla), MCTS-Append, MCTS-Modify, and Tree of Thought (ToT).

Results show that Tree of Thought excels in simpler problems, achieving the highest pass rate and lowest computational cost when full test case feedback is available, but its performance declines on complex tasks. MCTS-based methods offer limited improvements over the baseline due to suboptimal early reasoning paths and "prompt poisoning," where prior generated code negatively affects outputs. With partial test case feedback, MCTS-Append and Tree of Thought perform better on validation sets, demonstrating their potential in scenarios with incomplete feedback.

These findings highlight the challenges of applying tree-based reasoning to code generation and the importance of robust prompt design. Future work should refine initial reasoning strategies, address prompt poisoning, and explore hybrid methods to improve code generation in large language models.

Report: [Enhancing LLM’s Coding Ability by Tree-Based Searching Methods](/xiangyu_zhang.github.io/files/projects/Reinforced_Learning_Project_Report.pdf)

Link: [GitHub Repository](https://github.com/Painkillerzzz/code_contest)