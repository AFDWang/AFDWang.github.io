---
title:          "Graph Neural Network Training Acceleration for Multi-GPUs"
selected:       false
pub:            "<strong>[JOS 2022 | Second Author]</strong>Journal of Software"
pub_date:       "2022"

abstract: >-
  Graph neural network has attracted a lot of research interests recently due to its powerful and flexible representation ability. Considering the increasing scale of graph data and the limitation of GPU device memory, it becomes more challenging to train the graph neural networks with traditional general deep learning systems. How to perform efficient large graph neural network training over GPUs is one of the important research issues in this field. Traditional approaches are built on top of sparse matrix multiplication. When the device memory capacity is limited, it distributes the computation tasks to each device by distributed matrix multiplication. Their shortcomings mainly include: (1) They ignore the sparse distribution of the graph data, resulting in low computation efficiency; (2) These methods ignore the GPU computation and memory characteristics and fail to utilize the hardware resource. To improve the training efficiency, some studies propose to reduce the costs of each iteration through graph sampling techniques, which are also flexible and scalable. But due to the stochastics and variance, these methods are often harmful to the model quality. In this paper, we propose a high-performance graph neural network training framework over multi-GPUs. We have explored different GNN partition strategies over GPUs, studied the influence of different graph ordering patterns on the training efficiency, and proposed the block-sparse-aware optimization methods. We implemented our system using C++ and CuDNN, the experiments over four large graphs demonstrate that: (1) the graph re-ordering method improves around 40% cache hit rate and 2 times computation speedup; (2) compared to existing system DGL, our system achieves 5.8x total speedup.
cover:          /assets/images/covers/GNN.png
authors:
  - Xupeng Miao
  - <strong>Yujie Wang</strong>
  - Jia Shen
  - Yingxia Shao
  - Bin Cui
links:
  Paper: https://jos.org.cn/jos/article/abstract/Lh006
---
