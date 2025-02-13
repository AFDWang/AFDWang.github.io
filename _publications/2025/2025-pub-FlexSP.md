---
title:          "FlexSP: Accelerating Large Language Model Training via Flexible Sequence Parallelism"
date:           2025-01-30 00:00:00 +0800
selected:       true
pub:            "<strong>[ASPLOS 2025 | First Author]</strong> ACM International Conference on Architectural Support for Programming Languages and Operating Systems"
pub_date:       "2025"

abstract: >-
  Sequence parallelism has been popular for training long-context LLMs. Existing methods assume homogeneous sequence lengths and leverages a single, static strategy. However, real-world training corpora exhibit variability in sequence lengths, leading to workload heterogeneity. We show that current methods suffers from inefficiency, and propose a heterogeneity-adaptive sequence parallelism method, which captures the variability in sequence lengths and assigns the optimal combination of scattering strategies based on workload characteristics.
cover:          /assets/images/covers/FlexSP.png
authors:
  - <strong><u>Yujie Wang</u></strong>
  - Shiju Wang
  - Shenhan Zhu
  - Fangcheng Fu
  - Xinyi Liu
  - Xuefeng Xiao
  - Huixia Li
  - Jiashi Li
  - Faming Wu
  - Bin Cui
links:
  Arxiv: https://arxiv.org/abs/2412.01523
  Code: https://github.com/PKU-DAIR/Hetu-Galvatron
---
