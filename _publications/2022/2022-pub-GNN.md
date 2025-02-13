---
title:          "Graph Neural Network Training Acceleration for Multi-GPUs"
date:           2022-01-30 00:00:00 +0800
selected:       false
pub:            "<strong>[JOS 2022 | Second Author]</strong>Journal of Software"
pub_date:       "2022"

abstract: >-
  Graph neural networks (GNNs) are gaining attention, but performing efficient large GNN training over GPUs remains a challenge. Traditional methods rely on sparse matrix multiplication, which ignores the sparse distribution of the graph data and ignores the GPU computation and memory characteristics, leading to resource underutilization. Some approaches use graph sampling to reduce iteration costs but sacrifice model quality due to variance. This paper presents a high-performance multi-GPU GNN training framework, exploring GNN partition strategies, graph ordering patterns, and block-sparse-aware optimization methods. 
cover:          /assets/images/covers/GNN.png
authors:
  - Xupeng Miao
  - <strong><u>Yujie Wang</u></strong>
  - Jia Shen
  - Yingxia Shao
  - Bin Cui
links:
  Paper: https://jos.org.cn/jos/article/abstract/Lh006
---
