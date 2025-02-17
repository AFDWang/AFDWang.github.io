---
show: true
width: 10
date: 2024-02-13 00:00:00 +0800
---

<div class="p-4">
    <h2>Hetu</h2>
    <hr />
    <div class="text-center">
        <img src="{{ 'assets/images/badges/hetu.png' | relative_url }}" class="img-fluid" style="max-width: 18%;">
    </div>
    <p>
    </p>
    <p>
        I am a core developer of <a href="https://github.com/PKU-DAIR/Hetu" target="_blank">Hetu</a>.
        Hetu is a high-performance distributed deep learning system targeting trillions of parameters DL model training, developed and open-sourced by DAIR Lab at Peking University. 
        It takes account of both high availability in industry and innovation in academia, which has a number of advanced characteristics:
    </p>
    <p>
        <ol>
            <li>
                <strong>Applicability</strong><br/>
                DL model definition with standard dataflow graph; many basic CPU and GPU operators; efficient implementation of more than plenty of DL models and at least popular 10 ML algorithms.
            </li>
            <li>
                <strong>Efficiency</strong><br/> 
                Achieve at least 30% speedup compared to TensorFlow on DNN, CNN, RNN benchmarks.
            </li>
            <li>
                <strong>Flexibility</strong><br/>
                Supporting various parallel training protocols and distributed communication architectures, such as Data/Model/Pipeline parallel; Parameter server & AllReduce.
            </li>
            <li>
                <strong>Scalability</strong><br/>
                Deployment on more than 100 computation nodes; Training giant models with trillions of model parameters, e.g., Criteo Kaggle, Open Graph Benchmark.
            </li>
            <li>
                <strong>Agility</strong><br/>
                Automatically ML pipeline: feature engineering, model selection, hyperparameter search.
            </li> 
        </ol>       
    </p>
    <p>
        We welcome everyone interested in machine learning or graph computing to contribute codes, create issues or pull requests. Please refer to <a href="https://github.com/PKU-DAIR/Hetu/blob/main/CONTRIBUTING.md" target="_blank">Hetu Contribution Guide</a> for more details.
    </p>
    <!-- <img data-src="https://api.star-history.com/svg?repos=PKU-DAIR/Hetu&type=Date" class="lazy w-100 rounded-top" src="{{ '/assets/images/empty_300x200.png' | relative_url }}"> -->
    <p class="card-text text-right"><a href="https://github.com/PKU-DAIR/Hetu" target="_blank">Give a star!</a></p>
</div>