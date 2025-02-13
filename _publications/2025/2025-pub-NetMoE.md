---
title:          "NetMoE: Accelerating MoE Training through Dynamic Sample Placement"
selected:       true
pub:            "<strong>[ICLR 2025 Spotlight 5.1%]</strong> International Conference on Learning Representations"
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  Mixture of Experts (MoE) is a widely used technique to expand model sizes for better model quality while maintaining the computation cost constant. In a nutshell, an MoE model consists of multiple experts in each model layer and routes the training tokens to only a fixed number of experts rather than all. In distributed training, as experts are distributed among different GPUs, All-to-All communication is necessary to exchange the training tokens among the GPUs after each time of expert routing. Due to the frequent and voluminous data exchanges, All-to-All communication has become a notable challenge to training efficiency.
  In this paper, we manage to accelerate All-to-All communication in MoE models from the training sample perspective, which is unexplored so far. In particular, we put forward the observation that tokens in the same training sample have certain levels of locality in expert routing. Motivated by this, we develop \name, which takes such locality into account and dynamically rearranges the placement of training samples to minimize All-to-All communication costs. Specifically, we model the All-to-All communication given the sample placement and formulate an integer programming problem to deduce the optimal placement in polynomial time. Experiments with 32 GPUs show that NetMoE achieves a maximum efficiency improvement of 1.67x compared with state-of-the-art MoE training frameworks.
cover:          /assets/images/covers/NetMoE.png
authors:
  - Xinyi Liu
  - <strong>Yujie Wang</strong>
  - Fangcheng Fu
  - Xupeng Miao
  - Shenhan Zhu
  - Xiaonan Nie
  - Bin Cui
links:
  OpenReview: https://openreview.net/forum?id=1qP3lsatCR
---
