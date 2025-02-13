---
title:          "Malleus: Straggler-Resilient Hybrid Parallel Training of Large-scale Models via Malleable Data and Model Parallelization"
date:           2025-01-10 00:00:00 +0800
selected:       false
pub:            "<strong>[SIGMOD 2025 (CCF-A)]</strong> ACM International Conference on Management of Data"
pub_date:       "2025"

abstract: >-
  As model size and training data grow, the reliance on GPUs increases, raising the risk of dynamic stragglers that some devices lag behind in performance occasionally. We propose Malleus, a straggler-resilient hybrid parallel training framework for large-scale models. Malleus captures the dynamic straggler issues at the nuanced, per-GPU granularity during training, and adapts in real-time to stragglers by adjusting GPU parallelization, pipeline stages, model layers, and data. Besides, it efficiently migrates model states without disrupting training stability. 
cover:          /assets/images/covers/Malleus.png
authors:
  - Haoyang Li
  - Fangcheng Fu
  - Hao Ge
  - Sheng Lin
  - Xuanyu Wang
  - Jiawen Niu
  - <strong><u>Yujie Wang</u></strong>
  - Hailin Zhang
  - Xiaonan Nie
  - Bin Cui
links:
  Arxiv: https://arxiv.org/abs/2410.13333
  Code: https://github.com/PKU-DAIR/Hetu
---
