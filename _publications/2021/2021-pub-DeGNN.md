---
title:          "DeGNN: Improving Graph Neural Networks with Graph Decomposition"
date:           2021-01-30 00:00:00 +0800
selected:       false
pub:            "<strong>[SIGKDD 2021]</strong>Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining"
pub_date:       "2021"

abstract: >-
  Mining from graph-structured data is an integral component of graph data management. A recent trending technique, graph convolutional network (GCN), has gained momentum in the graph mining field, and plays an essential part in numerous graph-related tasks. Although the emerging GCN optimization techniques bring improvements to specific scenarios, they perform diversely in different applications and introduce many trial-and-error costs for practitioners. Moreover, existing GCN models often suffer from oversmoothing problem. Besides, the entanglement of various graph patterns could lead to non-robustness and harm the final performance of GCNs. In this work, we propose a simple yet efficient graph decomposition approach to improve the performance of general graph neural networks. We first empirically study existing graph decomposition methods and propose an automatic connectivity-ware graph decomposition algorithm, DeGNN. To provide a theoretical explanation, we then characterize GCN from the information-theoretic perspective and show that under certain conditions, the mutual information between the output after l layers and the input of GCN converges to 0 exponentially with respect to l. On the other hand, we show that graph decomposition can potentially weaken the condition of such convergence rate, alleviating the information loss when GCN becomes deeper. Extensive experiments on various academic benchmarks and real-world production datasets demonstrate that graph decomposition generally boosts the performance of GNN models. Moreover, our proposed solution DeGNN achieves state-of-the-art performances on almost all these tasks.
cover:          /assets/images/covers/DeGNN.png
authors:
  - Xupeng Miao
  - Nezihe Merve Gürel
  - Wentao Zhang
  - Zhichao Han
  - Bo Li
  - Wei Min
  - Susie Xi Rao
  - Hansheng Ren
  - Yinan Shan
  - Yingxia Shao
  - Yujie Wang
  - Fan Wu
  - Hui Xue
  - Yaming Yang
  - Zitao Zhang
  - Yang Zhao
  - Shuai Zhang
  - Yujing Wang
  - Bin Cui
  - Ce Zhang
links:
  Paper: https://dl.acm.org/doi/10.1145/3447548.3467312
  Arxiv: https://arxiv.org/abs/1910.04499
---
