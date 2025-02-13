---
title:          "Spindle: Efficient Distributed Training of Multi-Task Large Models via Wavefront Scheduling"
selected:       true
pub:            "[<strong>ASPLOS 2025</strong>] ACM International Conference on Architectural Support for Programming Languages and Operating Systems"
pub_date:       "2025"

abstract: >-
  Recent foundation models are capable of handling multiple tasks and multiple data modalities with the unified base model structure and several specialized model components. However, efficient training of such multi-task (MT) multi-modal (MM) models poses significant system challenges due to the sophisticated model architecture and the heterogeneous workloads of different tasks and modalities.
  In this paper, we propose Spindle, a brand new training system tailored for resource-efficient and high-performance training of MT MM models via wavefront scheduling. The key idea of Spindle is to decompose the model execution into waves and address the joint optimization problem sequentially, including both heterogeneity-aware workload parallelization and dependency-driven execution scheduling. We build our system and evaluate it on various MT MM models. Experiments demonstrate the superior performance and efficiency of Spindle, with speedup ratio up to 71% compared to state-of-the-art training systems.
cover:          /assets/images/covers/Spindle.png
authors:
  - <strong>Yujie Wang</strong>
  - Shenhan Zhu
  - Fangcheng Fu
  - Xupeng Miao
  - Jie Zhang
  - Juan Zhu
  - Fan Hong
  - Yong Li
  - Bin Cui
links:
  Arxiv: https://arxiv.org/abs/2409.03365
---
