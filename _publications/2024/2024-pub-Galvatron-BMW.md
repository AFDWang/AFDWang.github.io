---
title:          "Improving Automatic Parallel Training via Balanced Memory Workload Optimization"
# date:           2024-05-12 00:01:00 +0800
selected:       true
pub:            "IEEE Transactions on Knowledge and Data Engineering (TKDE) 2024"
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
Transformer models have emerged as the leading approach for achieving state-of-the-art performance across various application domains, serving as the foundation for advanced large-scale deep learning (DL) models. However, efficiently training these models across multiple GPUs remains a complex challenge due to the abundance of parallelism options. Existing DL systems either require manual efforts to design distributed training plans or limit parallelism combinations to a constrained search space. In this paper, we present Galvatron-BMW, a novel system framework that integrates multiple prevalent parallelism dimensions and automatically identifies the most efficient hybrid parallelism strategy. To effectively navigate this vast search space, we employ a decision tree approach for decomposition and pruning based on intuitive insights. We further utilize a dynamic programming search algorithm to derive the optimal plan. Moreover, to improve resource utilization and enhance system efficiency, we propose a bi-objective optimization workflow that focuses on workload balance. Our evaluations on different Transformer models demonstrate the capabilities of Galvatron-BMW in automating distributed training under varying GPU memory constraints. Across all tested scenarios, Galvatron-BMW consistently achieves superior system throughput, surpassing previous approaches that rely on limited parallelism strategies.
cover:          /assets/images/covers/Galvatron-BMW.jpg
authors:
  - <strong>Yujie Wang</strong>
  - Youhe Jiang
  - Xupeng Miao
  - Fangcheng Fu
  - Shenhan Zhu
  - Xiaonan Nie
  - Yaofeng Tu
  - Bin Cui
links:
  Paper: https://dl.acm.org/doi/10.1109/TKDE.2024.3370614
  Arxiv: https://arxiv.org/abs/2307.02031
  Code: https://github.com/PKU-DAIR/Hetu-Galvatron
---
