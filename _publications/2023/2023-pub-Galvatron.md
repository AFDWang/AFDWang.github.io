---
title:          "Galvatron: Efficient Transformer Training over Multiple GPUs Using Automatic Parallelism"
date:           2023-08-30 00:00:00 +0800
selected:       true
pub:            "<strong>[VLDB 2023 | Co-First Author]</strong> Proceedings of the VLDB Endowment"
pub_date:       "2023"

abstract: >-
  To train large Transformer models over multiple GPUs efficiently, we propose Galvatron, a new automatic parallelism system that incorporates multiple popular parallelism dimensions and automatically finds the most efficient hybrid parallelism strategy. To better explore such a rarely huge search space, we 1) involve a decision tree to make decomposition and pruning based on some reasonable intuitions, and then 2) design a dynamic programming search algorithm to generate the optimal plan. Experiments show the effectiveness and efficiency of Galvatron.
cover:          /assets/images/covers/Galvatron.png
authors:
  - Xupeng Miao*
  - <strong><u>Yujie Wang*</u></strong>
  - Youhe Jiang*
  - Chunan Shi
  - Xiaonan Nie
  - Hailin Zhang
  - Bin Cui
links:
  Paper: https://dl.acm.org/doi/10.14778/3570690.3570697
  Arxiv: https://arxiv.org/abs/2211.13878
  Code: https://github.com/PKU-DAIR/Hetu/tree/main/tools/Galvatron
---
