---
title:          "Enabling Parallelism Hot Switching for Efficient Training of Large Language Models"
selected:       false
pub:            "Proceedings of the ACM SIGOPS 30th Symposium on Operating Systems Principles (<strong>SOSP</strong>)"
pub_date:       "2024"

abstract: >-
  Training of large-scale deep learning models necessitates parallelizing the model and data across numerous devices, and the choice of parallelism strategy substantially depends on the training workloads such as memory consumption, computation cost, and communication cost. Current approaches generally assume uniform training workloads across samples in a given task. Thus, existing systems are designed to adopt a static parallelism strategy throughout one training process. Nevertheless, when training models with sequence inputs, this assumption fails due to the sequence length variation across samples. Consequently, training with a static parallelism strategy would result in sub-optimal performance.
  In this paper, we first reveal the under-explored fact that the optimal parallelism strategy varies even for the sequences within a single mini-batch. Motivated by this, we present HotSPa, a novel system that adopts multiple parallelism strategies for efficient training with sequence inputs. To be specific, given a mini-batch of training sequences, HotSPa partitions them into multiple groups and applies different parallelism strategies to process each group individually. To enable the hot switching between strategies, HotSPa transfers model parameters and accumulated gradients among the devices on the fly. Significant solutions are proposed with the hope of seamless and rapid parallelism hot switching. Firstly, we design a graph compiler, which generates distributed computation graphs for different parallelism strategies simultaneously, and orchestrates them to share a single model storage backbone. Secondly, we develop a simple yet effective hot switch planner, which heuristically deduces communication plans to accelerate the transition of model partitioning given any pairs of strategies. Extensive experiments on large language model training demonstrate that HotSPa can be up to 2.99× faster than Megatron-LM and DeepSpeed that utilize static parallelism strategies.
cover:          /assets/images/covers/HotSpa.png
authors:
  - Hao Ge
  - Fangcheng Fu
  - Haoyang Li
  - Xuanyu Wang
  - Sheng Lin
  - <strong>Yujie Wang</strong>
  - Xiaonan Nie
  - Hailin Zhang
  - Xupeng Miao
  - Bin Cui
links:
  Paper: https://dl.acm.org/doi/10.1145/3694715.3695969
  Code: https://github.com/PKU-DAIR/Hetu
---
