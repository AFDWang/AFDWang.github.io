---
title:          "Enabling Parallelism Hot Switching for Efficient Training of Large Language Models"
date:           2024-07-30 00:00:00 +0800
selected:       false
pub:            "<strong>[SOSP 2024]</strong> Proceedings of the ACM SIGOPS 30th Symposium on Operating Systems Principles"
pub_date:       "2024"

abstract: >-
  Training large-scale deep learning models requires parallelizing across multiple devices. Current systems assume uniform workloads and adopt a static parallelism strategy throughout one training process, but this fails for sequence inputs with varying lengths, leading to sub-optimal performance. This paper introduces HotSPa, a system that uses multiple parallelism strategies within a mini-batch. HotSPa partitions sequences into multiple groups, applies different strategies to each group, and enables dynamic switching between strategies by transferring model parameters and gradients in real-time. 
cover:          /assets/images/covers/HotSpa.png
authors:
  - Hao Ge
  - Fangcheng Fu
  - Haoyang Li
  - Xuanyu Wang
  - Sheng Lin
  - <strong><u>Yujie Wang</u></strong>
  - Xiaonan Nie
  - Hailin Zhang
  - Xupeng Miao
  - Bin Cui
links:
  Paper: https://dl.acm.org/doi/10.1145/3694715.3695969
  Code: https://github.com/PKU-DAIR/Hetu
---
