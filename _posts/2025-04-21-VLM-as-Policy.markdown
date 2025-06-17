---
layout:     post
title:      "VLM as Policy"
subtitle:   "Common-Law Content Moderation Framework for Short Video Platform"
arxiv:      "https://arxiv.org/pdf/2504.14904"
date:       2025-04-21
author:     "Xingyu Lu, Tianke Zhang, Chang Meng, Xiaobei Wang, Jinpeng Wang, Yi-Fan Zhang, Shisong Tang, Changyi Liu, Haojie Ding, Kaiyu Jiang, Kaiyu Tang, Bin Wen, Hai-Tao Zheng, Fan Yang, Tingting Gao, Di Zhang, Kun Gai"
header-img: "img/VLM-as-Policy.jpg"
---

Exponentially growing short video platforms (SVPs) face significant challenges in moderating content detrimental to users' mental health, especially for minors, where dissemination risks catastrophic societal consequences. Existing methods suffer three critical limitations: 1) **Manual review** incurs high costs and human bias; 2) **Automated methods** lack nuanced understanding, reducing accuracy; and 3) **Industrial regulations** adapt slowly to evolving trends due to long update cycles. To address these, we: 1) annotate the **first SVP content moderation benchmark** with authentic user/reviewer feedback; 2) verify limitations through benchmark evaluation; and 3) propose **KuaiMod**—a common-law framework with three components: training data construction, offline adaptation, and online deployment & refinement. Leveraging **VLM and Chain-of-Thought reasoning**, KuaiMod dynamically models video toxicity from sparse feedback, achieving rapid updates and high accuracy. Offline experiments and large-scale A/B tests show KuaiMod achieves **best benchmark performance**, **reduces user reporting by 20%**, and **increases DAU/AUT** on Kuaishou platforms. Benchmark open-sourced at [KuaiMod.github.io](https://github.com/KuaiMod/KuaiMod.github.io).
