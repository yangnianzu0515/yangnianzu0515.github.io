---
title: "Learning Self-Modulating Attention in Continuous Time Space with Applications to Sequential Recommendation"
collection: publications
permalink: /publication/paper4-moleood
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
# date: 2009-10-01
venue: 'ICML 2021'
preprint:
authors: 'Chao Chen, Haoyu Geng, <b>Nianzu Yang</b>, Junchi Yan, Daiyue Xue, Jianping Yu, Xiaokang Yang'
paperurl: 'http://yangnianzu0515.github.io/files/paper2-self-modulating_attention.pdf'
citation: # 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
poster: "http://yangnianzu0515.github.io/poster/paper2-poster-self-modulating_attention.pdf"
slides: "http://yangnianzu0515.github.io/slides/paper2-slides-self-modulating_attention.pdf"
code: "https://github.com/cchao0116/SMACTREC-ICML21"
---
In this paper, we propose a novel **self-modulating attention** and apply it to sequential recommendation.

**Abstract:** Molecule representation learning (MRL) has been extensively studied and current methods have shown promising power for various tasks, e.g., molecular property prediction and target  identification. However, a common hypothesis of existing methods is that either the model development or experimental evaluation is mostly based on i.i.d. data across training and testing. Such a hypothesis can be violated in real-world applications where testing molecules could come from new environments, bringing about serious performance degradation or unexpected prediction. We propose a new representation learning framework entitled MoleOOD to enhance the robustness of MRL models against such distribution shifts, motivated by an observation that the (bio)chemical properties of molecules are usually invariantly associated with certain privileged molecular substructures across different environments (e.g., scaffolds, sizes, etc.). Specifically, We introduce an environment inference model to identify the latent factors that impact data generation from different distributions in a fully data-driven manner. We also propose a new learning objective to guide the molecule encoder to leverage environment-invariant substructures that more stably relate with the labels across environments. Extensive experiments on ten real-world datasets demonstrate that our model has a stronger generalization ability than existing methods under various out-of-distribution (OOD) settings, despite the absence of manual specifications of environments. Particularly, our method achieves up to 5.9\% and 3.9\% improvement over the strongest baselines on OGB and DrugOOD benchmarks in terms of ROC-AUC, respectively. Our source code is publicly available at [https://github.com/yangnianzu0515/MoleOOD](https://github.com/yangnianzu0515/MoleOOD).

[PDF](http://yangnianzu0515.github.io/files/paper4-moleood.pdf)
[Poster](http://yangnianzu0515.github.io/poster/paper2-poster-self-modulating_attention.pdf)
[Slides](http://yangnianzu0515.github.io/slides/paper2-slides-self-modulating_attention.pdf)
[Code](https://github.com/cchao0116/SMACTREC-ICML21)