---
layout:     post
title:      "TASKGALAXY"
subtitle:   "SCALING MULTI-MODAL INSTRUCTION FINE-TUNING WITH TENS OF THOUSANDS VISION TASK TYPES"
date:       2025-02-14
author:     "Jiankang Chen, Tianke Zhang, Changyi Liu, Haojie Ding, Yaya Shi, Feng Cheng, Huihui Xiao, Bin Wen, Fan Yang, Tingting Gao, Di Zhang"
img: "img/TASKGALAXY.jpg"
---

Multimodal visual language models are advancing in open-world applications but face limitations due to insufficient task-specific data, causing poor generalization and biased outputs. While increasing task diversity in fine-tuning datasets is crucial, manual task labeling is labor-intensive and typically yields only a few hundred task types. To overcome this, we propose **TaskGalaxy**, a large-scale multimodal instruction fine-tuning dataset with **19,227 hierarchical task types** and **413,648 samples**. TaskGalaxy uses **GPT-4o** to expand task diversity from a small set of manually defined tasks, employs **CLIP and GPT-4o** to filter tasks best matching open-source images, generates relevant question-answer pairs, and leverages multiple models to ensure sample quality. This automated approach enhances task diversity and data quality while minimizing manual effort. Integrating TaskGalaxy into models like **LLaVA-v1.5** and **InternVL-Chat-v1.0** demonstrates substantial performance gains across **16 benchmarks**, highlighting the critical role of task diversity. TaskGalaxy is publicly available at [https://github.com/Kwai-YuanQi/TaskGalaxy](https://github.com/Kwai-YuanQi/TaskGalaxy).
