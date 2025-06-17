---
layout:     post
title:      "Libra-Merging"
subtitle:   "Importance-redundancy and Pruning-merging Trade-off for Acceleration Plug-in in Large Vision-Language Model"
arxiv:      "https://openaccess.thecvf.com/content/CVPR2025/supplemental/Yang_Libra-Merging_Importance-redundancy_and_CVPR_2025_supplemental.pdf"
date:       2025-02-11
author:     "Longrong Yang, Dong Shen, Chaoxiang Cai, Kaibing Chen, Fan Yang, Tingting Gao, Di Zhang, Xi Li"
img: "img/Libra-Merging.jpg"
---

Large Vision-Language Models (LVLMs) have achieved significant progress, but expensive inference costs limit realistic deployment. While existing works compress visual tokens by identifying important non-redundant tokens as targets (pruning/merging others), they face two dilemmas: 1) the **token importance-redundancy dilemma** in target token identification, and 2) the conflict between disrupting target token information and losing non-target token information during merging/pruning. To solve these, we propose **Libra-Merging**—a novel visual token compression scheme. For target token identification, it selects the most important tokens from **spatially discrete intervals**, achieving more robust importance-redundancy trade-offs than hyper-parameter-dependent methods. During token compression, it avoids merging non-target tokens dissimilar to targets (preventing target information disruption) while condensing them into an **information compensation token** to retain critical non-target information. Serving as a plug-in for diverse LVLMs, extensive experiments demonstrate its effectiveness, with code available at [https://github.com/longrongyang/Libra-Merging](https://github.com/longrongyang/Libra-Merging).
