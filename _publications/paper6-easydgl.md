---
title: "EasyDGL: Encode, Train and Interpret for Continuous-time Dynamic Graph Learning"
collection: publications
permalink: /publication/paper6-easydgl
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
# date: 2009-10-01
venue: 'arXiv'
preprint:
authors: 'Chao Chen, Haoyu Geng, <b>Nianzu Yang</b>, Xiaokang Yang, Junchi Yan'
paperurl: 'http://yangnianzu0515.github.io/files/paper6-easydgl.pdf'
citation: # 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
poster: 
slides: 
code: "https://github.com/cchao0116/EasyDGL"
blod:
chinese_blog: 
---
Authors: Chao Chen, Haoyu Geng, **Nianzu Yang**, Xiaokang Yang, Junchi Yan



**Abstract:** Dynamic graphs arise in various real-world applications, and it is often welcomed to model the dynamics directly in continuous time domain for its flexibility. This paper aims to design an easy-to-use pipeline (termed as EasyDGL which is also due to its implementation by DGL toolkit) composed of three key modules with both strong fitting ability and interpretability. Specifically the proposed pipeline which involves encoding, training and interpreting: i) a temporal point process (TPP) modulated attention architecture to endow the continuous-time resolution with the coupled spatiotemporal dynamics of the observed graph with edge-addition events; ii) a principled loss composed of task-agnostic TPP posterior maximization based on observed events on the graph, and a task-aware loss with a masking strategy over dynamic graph, where the covered tasks include dynamic link prediction, dynamic node classification and node traffic forecasting; iii) interpretation of the model outputs (e.g., representations and predictions) with scalable perturbation-based quantitative analysis in the graph Fourier domain, which could more comprehensively reflect the behavior of the learned model. Extensive experimental results on public benchmarks show the superior performance of our EasyDGL for time-conditioned predictive tasks, and in particular demonstrate that EasyDGL can effectively quantify the predictive power of frequency content that a model learn from the evolving graph data.

[[PDF]](http://yangnianzu0515.github.io/files/paper6-easydgl.pdf)
[[Code]](https://github.com/cchao0116/EasyDGL)
