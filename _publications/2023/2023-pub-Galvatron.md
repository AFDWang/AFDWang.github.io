---
title:          "Galvatron: Efficient Transformer Training over Multiple GPUs Using Automatic Parallelism"
selected:       true
pub:            "<strong>[VLDB 2023 | Co-First Author]</strong> Proceedings of the VLDB Endowment"
pub_date:       "2023"

abstract: >-
  Transformer models have achieved state-of-the-art performance on various domains of applications and gradually becomes the foundations of the advanced large deep learning (DL) models. However, how to train these models over multiple GPUs efficiently is still challenging due to a large number of parallelism choices. Existing DL systems either rely on manual efforts to make distributed training plans or apply parallelism combinations within a very limited search space. In this approach, we propose Galvatron, a new system framework that incorporates multiple popular parallelism dimensions and automatically finds the most efficient hybrid parallelism strategy. To better explore such a rarely huge search space, we 1) involve a decision tree to make decomposition and pruning based on some reasonable intuitions, and then 2) design a dynamic programming search algorithm to generate the optimal plan. Evaluations on four representative Transformer workloads show that Galvatron could perform automatically distributed training with different GPU memory budgets. Among all evluated scenarios, Galvatron always achieves superior system throughput compared to previous work with limited parallelism.
cover:          /assets/images/covers/Galvatron.png
authors:
  - Xupeng Miao*
  - <strong>Yujie Wang*</strong>
  - Youhe Jiang
  - Chunan Shi
  - Xiaonan Nie
  - Hailin Zhang
  - Bin Cui
links:
  Paper: https://dl.acm.org/doi/10.14778/3570690.3570697
  Arxiv: https://arxiv.org/abs/2211.13878
  Code: https://github.com/PKU-DAIR/Hetu/tree/main/tools/Galvatron
---
