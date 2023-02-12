---
title: "MoleRec: Combinatorial Drug Recommendation with Substructure-Aware Molecular Representation Learning"
collection: publications
permalink: /publication/paper5-molerec
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
# date: 2009-10-01
venue: 'TheWebConf (a.k.a. WWW) 2023'
preprint:
authors: '<b>Nianzu Yang</b>, Kaipeng Zeng, Qitian Wu, Junchi Yan'
paperurl: 'http://yangnianzu0515.github.io/files/paper5-molerec.pdf'
citation: # 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
poster: 
slides: 
code: "https://github.com/yangnianzu0515/MoleRec"
blod:
chinese_blog: 
---
Authors: **Nianzu Yang**, Kaipeng Zeng, Qitian Wu, Junchi Yan

We propose a novel molecular substructure-aware encoding method called **MoleRec** for combinatorial drug recommendation.

**Abstract:** Combinatorial drug recommendation involves recommending a personalized combination of medication (drugs) to a patient over his/her longitudinal history, which essentially aims at solving a combinatorial optimization problem that pursues high accuracy under the safety constraint. Among existing learning-based approaches, the association between drug substructures (i.e., a sub-graph of the molecule that contributes to certain chemical effect) and the target disease is largely overlooked, though the function of drugs in fact exhibits strong relevance with particular substructures. To address this issue, we propose a molecular substructure-aware encoding method entitled MoleRec that entails a hierarchical architecture aimed at modeling inter-substructure interactions and individual substructures' impact on patient's health condition, in order to identify those substructures that really contribute to healing patients. Specifically, MoleRec learns to attentively pooling over substructure representations which will be element-wisely re-scaled by the model's inferred relevancy with a patient's health condition to obtain a prior-knowledge-informed drug representation. We further design a weight annealing strategy for drug-drug-interaction (DDI) objective to adaptively control the balance between accuracy and safety criteria throughout training. Experiments on the MIMIC-III dataset demonstrate that our approach achieves new state-of-the-art performance w.r.t. four accuracy and safety metrics. Our source code is publicly available at [https://github.com/yangnianzu0515/MoleRec](https://github.com/yangnianzu0515/MoleRec).

[[PDF]](http://yangnianzu0515.github.io/files/paper5-molerec.pdf)
[[Code]](https://github.com/yangnianzu0515/MoleRec)
