---
title:          "Malleus: Straggler-Resilient Hybrid Parallel Training of Large-scale Models via Malleable Data and Model Parallelization"
date:           2025-01-10 00:00:00 +0800
selected:       false
pub:            "<strong>[SIGMOD 2025]</strong> ACM International Conference on Management of Data"
pub_date:       "2025"

abstract: >-
  As the scale of models and training data continues to grow, there is an expanding reliance on more GPUs to train large-scale models, which inevitably increases the likelihood of encountering dynamic stragglers that some devices lag behind in performance occasionally. However, hybrid parallel training, one of the de facto paradigms to train large models, is typically sensitive to the stragglers.
  This paper presents Malleus, a straggler-resilient hybrid parallel training framework for large-scale models. Malleus captures the dynamic straggler issues at the nuanced, per-GPU granularity during training. Once a shift in the GPU ability is detected, Malleus adaptively adjusts the parallelization of GPU devices, pipeline stages, model layers, and training data through a novel planning algorithm, accommodating the dynamic stragglers in real time. In addition, Malleus seamlessly and efficiently migrates the model states to fulfill the adjusted parallelization plan on the fly, without sacrificing the stability of the training tasks. Empirical results on large language models with up to 110B parameters show that Malleus consistently outperforms existing parallel training frameworks under various straggler situations, delivering on average 2.63-5.28 times of efficiency improvement.
cover:          /assets/images/covers/Malleus.png
authors:
  - Haoyang Li
  - Fangcheng Fu
  - Hao Ge
  - Sheng Lin
  - Xuanyu Wang
  - Jiawen Niu
  - <strong>Yujie Wang</strong>
  - Hailin Zhang
  - Xiaonan Nie
  - Bin Cui
links:
  Arxiv: https://arxiv.org/abs/2410.13333
  Code: https://github.com/PKU-DAIR/Hetu
---
