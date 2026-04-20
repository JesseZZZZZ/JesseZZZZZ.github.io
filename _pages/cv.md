---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* MPhil in Computer Science, Peking University, 2025 – 2028
  * School of Computer Science / Institute of Computational Linguistics
  * Advisor: Prof. Yunfang Wu
  * Research: Natural Language Processing, Large Language Models, Reinforcement Learning

* B.S. in Computer Science, Beijing Institute of Technology, 2021 – 2025
  * Xu Teli Honors Program
  * GPA: 3.8 / 4.0 &nbsp;|&nbsp; Rank: 1 / 68

Publications
======
1. **Zhaoxi Zhang**, Sanwoo Lee, Zhixiang Wang, Yunfang Wu. *3DM: Distill, Dynamic Drop, and Merge for Debiasing Multi-modal Large Language Models.* **ACL 2025.**

2. Yihan Lin\*, **Zhaoxi Zhang**\*, Taoyi Wang, Yuguo Chen, Rong Zhao. *CSVO: Complementary-Pathway Spatial-Enhanced Visual Odometry for Extreme Environments with Brain-inspired Vision Sensors.* **IROS 2025.** (Co-first author)

3. Yanzhi Zhang\*, **Zhaoxi Zhang**\*, Haoxiang Guan, Yilin Cheng, Yitong Duan, Chen Wang, Yue Wang, Yunfang Wu, Shuxin Zheng, Jiyan He. *No Free Lunch: Rethinking Internal Feedback for LLM Reasoning.* (Co-first author, under review)

4. **Zhaoxi Zhang**, Yitong Duan, Yunfang Wu. *One Tool Is Enough: Reinforcement Learning of LLM Agents for Repository-level Code Navigation.* (Under review)

5. *(For a full list, see [Google Scholar](https://scholar.google.com/citations?user=ssesMYEAAAAJ&hl=en).)*

Research & Internship Experience
======
* **Reinforcement Learning for LLM Agents**, Baidu Research &nbsp;|&nbsp; Jan 2026 – Present
  * Researching end-to-end RL training and evaluation of LLM agents.
  * **Agentic Learning with Skills**: Designed a two-agent system (Skill Generator + Solver). The Solver is trained with GRPO; the Generator receives reward based on the performance gain the skills provide and is updated with REINFORCE. Achieved improvements on multiple single-hop and multi-hop QA benchmarks. Targeting NeurIPS / EMNLP.
  * **Repository-level Code Generation Benchmark**: Designing a cross-language benchmark for evaluating LLMs' repo-level code generation capability. Successfully constructed 400 samples and scaling up. Targeting NeurIPS / EMNLP.
  * **Mixture of Experts as Multi-Agents**: Exploring sparse MoE architectures to design novel MARL algorithms where each agent role activates distinct experts, aiming to resolve capability conflicts in multi-agent systems.

* **Reinforcement Learning for LLM Agents**, Zhongguancun Institute of Artificial Intelligence (ZIAI) &nbsp;|&nbsp; Apr 2025 – Jan 2026
  * Studied whether RL teaches LLMs genuinely new skills in the agentic setting, where tools are newly designed to avoid data leakage.
  * **Zoom-R1**: Proposed a visual reasoning method where the model invokes a zoom tool to insert magnified sub-images into its chain-of-thought, enabling fine-grained spatial reasoning over images.
  * **CodeBase QA (One Tool Is Enough)**: Redefined SWE-Bench as a code localization task. Trained an agent via multi-turn tool-call RL using the VeRL framework, allowing the model to browse source code during rollouts. Submitted in January 2026.

* **Model Merging for Debiasing Multimodal LLMs**, Peking University &nbsp;|&nbsp; Nov 2024 – Feb 2025
  * Investigated debiasing multimodal LLMs via model merging. Used knowledge distillation to unify heterogeneous model architectures, then designed a novel merging strategy that preserves capability-enhancing parameters while discarding bias-inducing ones. Published at **ACL 2025**.

* **Multimodal Visual Odometry**, Tsinghua University &nbsp;|&nbsp; Nov 2023 – Mar 2025
  * Addressed the failure of RGB-only VO under extreme conditions (HDR, high speed) using the Tianmouc neuromorphic sensor, which outputs Time-Difference (TD) and Space-Difference (SD) streams. Designed an asynchronous multimodal fusion network combining SD and RGB channels. Achieved state-of-the-art results on standard benchmarks and real Tianmouc recordings. Published at **IROS 2025**.

Awards & Honors
======
* Excellence Scholarship (First Prize), Beijing Institute of Technology
* National English Competition for College Students — First Prize, Beijing
* "FLTRP·ETIC Cup" English Speaking Contest — First Prize, Beijing; 1st Place, Beijing Institute of Technology
