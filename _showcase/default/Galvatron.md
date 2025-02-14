---
show: true
width: 10
date: 2024-02-14 00:00:00 +0800
---

<div class="p-4">
    <h2>Hetu-Galvatron</h2>
    <hr />
    <p> 
        <a href="https://github.com/PKU-DAIR/Hetu-Galvatron" target="_blank">Hetu-Galvatron</a> is an automatic distributed training system designed for Transformer models, including Large Language Models (LLMs). It leverages advanced automatic parallelism techniques to deliver exceptional training efficiency. 
        <strong>Key Features</strong>
        (1) Enhanced Efficiency via Automatic Parallelism
        - Enlarged Parallelism Search Space
        Incorporate multiple popular parallelism dimensions of distributed training, including DP (Data Parallelism), SDP (Sharded Data Parallelism, support both ZeRO-2 & ZeRO-3), PP (Pipeline Parallelism, support both GPipe & Pipedream-flush / 1F1B-flush), TP (Tensor Parallelism). Also incorporate CKPT (Activation Checkpointing) as a special parallelism dimension.
        - Fine-grained Hybrid Parallelism
        For each Transformer layer, support flexible and fine-grained hybrid parallelism strategies, contributing to the enhanced training efficiency.
        - Efficient Automatic Parallelism Optimization
        For any given Transformer model, automatically and efficiently search for the optimal parallelism strategies, which provides the optimal training efficiency.
        (2) Versatility
        Suitable for a wide range of Transformer architectures, including language models, LLMs, vision models, multi-modality models, etc.
        (3) User-Friendly Interface
        Easy to use, even for those new to distributed training.
    </p>
    <p>
        We welcome everyone interested in efficient distributed training techniques and parallelism optimization to use Hetu-Galvatron, and contribute codes, create issues or pull requests to Hetu-Galvatron.
        Read the <a href="https://github.com/PKU-DAIR/Hetu-Galvatron/blob/main/README.md" target="_blank">README</a> and the <a href="https://hetu-galvatron.readthedocs.io/en/latest/" target="_blank">Document</a> of Hetu-Galvatron for detailed usage guidance.
    </p>
    <!-- <img data-src="https://api.star-history.com/svg?repos=PKU-DAIR/Hetu-Galvatron&type=Date" class="lazy w-100 rounded-top" src="{{ '/assets/images/empty_300x200.png' | relative_url }}"> -->
    <p class="card-text"><small><a href="https://github.com/PKU-DAIR/Hetu-Galvatron" target="_blank">Give a star!</a></small></p>
</div>