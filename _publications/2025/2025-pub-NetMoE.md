---
title:          "NetMoE: Accelerating MoE Training through Dynamic Sample Placement"
date:           2025-01-22 00:00:00 +0800
selected:       true
pub:            "<strong>[ICLR 2025 Spotlight 5.1% | Second Author]</strong> International Conference on Learning Representations"
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  During the training of Mixture of Experts (MoE) models, All-to-All communication has become a notable challenge to training efficiency. In this paper, we find that tokens in the same training sample have certain levels of locality in expert routing. Motivated by this, we develop NetMoE, which takes such locality into account and dynamically rearranges the placement of training samples to minimize All-to-All communication costs. Experiments show the superior efficiency of NetMoE over state-of-the-art MoE training frameworks.
cover:          /assets/images/covers/NetMoE.png
authors:
  - Xinyi Liu
  - <strong><u>Yujie Wang</u></strong>
  - Fangcheng Fu
  - Xupeng Miao
  - Shenhan Zhu
  - Xiaonan Nie
  - Bin Cui
links:
  OpenReview: https://openreview.net/forum?id=1qP3lsatCR
---
