---
title:          "FlexSP: Accelerating Large Language Model Training via Flexible Sequence Parallelism"
# date:           2024-05-12 00:01:00 +0800
selected:       true
pub:            "ACM International Conference on Architectural Support for Programming Languages and Operating Systems (<strong>ASPLOS</strong>)"
pub_date:       "2025"

abstract: >-
  Extending the context length (i.e., the maximum supported sequence length) of LLMs is of paramount significance. To facilitate long context training of LLMs, sequence parallelism has emerged as an essential technique, which scatters each input sequence across multiple devices and necessitates communication to process the sequence. In essence, existing sequence parallelism methods assume homogeneous sequence lengths (i.e., all input sequences are equal in length) and therefore leverages a single, static scattering strategy for all input sequences. However, in reality, the sequence lengths in LLM training corpora exhibit substantial variability, often following a long-tail distribution, which leads to workload heterogeneity.
  In this paper, we show that employing a single, static strategy results in inefficiency and resource under-utilization, highlighting the need for adaptive approaches to handle the heterogeneous workloads across sequences. To address this, we propose a heterogeneity-adaptive sequence parallelism method. For each training step, our approach captures the variability in sequence lengths and assigns the optimal combination of scattering strategies based on workload characteristics. We model this problem as a linear programming optimization and design an efficient and effective solver to find the optimal solution. Furthermore, we implement our method in a high-performance system that supports adaptive parallelization in distributed LLM training. Experimental results demonstrate that our system outperforms state-of-the-art training frameworks by up to 1.98x.
cover:          /assets/images/covers/FlexSP.png
authors:
  - <strong>Yujie Wang</strong>
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
