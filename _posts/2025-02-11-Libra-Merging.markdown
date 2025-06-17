---
layout:     post
title:      "Libra-Merging"
subtitle:   "Importance-redundancy and Pruning-merging Trade-off for Acceleration Plug-in in Large Vision-Language Model"
date:       2025-02-11
author:     "Longrong Yang, Dong Shen, Chaoxiang Cai, Kaibing Chen, Fan Yang, Tingting Gao, Di Zhang, Xi Li"
header-img: "img/post-bg-js-module.jpg"
---

Large Vision-Language Models (LVLMs) have achieved significant progress in recent years. However, the expensive inference cost limits the realistic deployment of LVLMs.
Some works find that visual tokens are redundant and compress tokens to reduce the inference cost. These works identify important non-redundant tokens as target tokens, then prune the remaining tokens (non-target tokens) or merge them into target tokens. However, target token identification faces the token importance-redundancy dilemma. Besides, token merging and pruning face a dilemma between disrupting target token information and losing non-target token information. To solve these problems, we propose a novel visual token compression scheme, named LibraMerging. In target token identification, Libra-Merging selects the most important tokens from spatially discrete intervals, achieving a more robust token importance-redundancy trade-off than relying on a hyper-parameter. In token compression, when non-target tokens are dissimilar to target tokens, Libra-Merging does not merge them into the target tokens, thus avoiding disrupting target token information. Meanwhile, Libra-Merging condenses these non-target tokens into an information compensation token to prevent losing important non-target token information. Our method
can serve as a plug-in for diverse LVLMs, and extensive experimental results demonstrate its effectiveness. The code will be publicly available at https://github.com/longrongyang/Libra-Merging.
