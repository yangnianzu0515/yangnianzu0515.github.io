---
title: "Learning Self-Modulating Attention in Continuous Time Space with Applications to Sequential Recommendation"
collection: publications
permalink: /publication/paper2-self-modulating_attention
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
blod:
chinese_blog: 
---
Authors: Chao Chen, Haoyu Geng, **Nianzu Yang**, Junchi Yan, Daiyue Xue, Jianping Yu, Xiaokang Yang

In this paper, we propose a novel **self-modulating attention** and apply it to sequential recommendation.

**Abstract:** User interests are usually dynamic in the real world, which poses both theoretical and practical challenges for learning accurate preferences from rich behavior data. Among existing user behavior modeling solutions, attention networks are widely adopted for its effectiveness and relative simplicity. Despite being extensively studied, existing attentions still suffer from two limitations: i) conventional attentions mainly take into account the spatial correlation between user behaviors, regardless the distance between those behaviors in the continuous time space; and ii) these attentions mostly provide a dense and undistinguished distribution over all past behaviors then attentively encode them into the output latent representations. This is however not suitable in practical scenarios where a user’s future actions are relevant to a small subset of her/his historical behaviors. In this paper, we propose a novel attention network, named *self-modulating attention*, that models the complex and non-linearly evolving dynamic user preferences. We empirically demonstrate the effectiveness of our method on top-N sequential recommendation tasks, and the results on three largescale real-world datasets show that our model can achieve state-of-the-art performance.

[[PDF]](http://yangnianzu0515.github.io/files/paper2-self-modulating_attention.pdf)
[[Poster]](http://yangnianzu0515.github.io/poster/paper2-poster-self-modulating_attention.pdf)
[[Slides]](http://yangnianzu0515.github.io/slides/paper2-slides-self-modulating_attention.pdf)
[[Code]](https://github.com/cchao0116/SMACTREC-ICML21)