---
title: "Middle Layer Based Scalable Learned Index Scheme"
collection: publications
permalink: /publication/paper1-learned_index
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
# date: 2009-10-01
preprint:
venue: 'Journal of Software'
authors: 'Yuanning Gao, Jinbiao Ye, <b>Nianzu Yang</b>, Xiaofeng Gao, Guihai Chen'
paperurl: 'http://yangnianzu0515.github.io/files/paper1.pdf'
citation: # 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
paperpdf: /file/paper1-learned_index.pdf
poster: 
slides: 
code: 
---
This paper is about learned index. sdsd s

**Abstract:** In the era of big data and cloud computing, efficient data access is an important metric to measure the performance of a large-scale storage system. Therefore, design a lightweight and efficient index structure, which can meet the system's demand for high throughput and low memory footprint, is one of the research hotspots in the current database field. Recently, Kraska, et al proposed to use the machine learning models instead of traditional B-tree indexes, and remarkable results are achieved on real data sets. However, the proposed model assumes that the workload is static and read-only, failing to handle the index update problem. This study proposes Dabble, a middle layer based scalable learning index model, which is used to mitigate the index update problem. Dabble first uses K-means algorithm to divide the data set into K regions, and trains K neural networks to learn the data distribution of different regions. During the training phase, it innovatively integrates the data access patterns into the neural network, which can improve the prediction accuracy of the model for hotspot data. For data insertion, it borrows the idea of LSM tree, i.e., delay update mechanism, which greatly improved the data writing speed. In the index update phase, a middle layer based mechanism is proposed for model decoupling, thus easing the problem of index updating cost. Dabble model is evaluated on two datasets, the Lognormal distribution dataset and the real-world Weblogs dataset. The experiment results demonstrate the effectiveness and efficiency of the proposed model compared with the state-of-the-art methods.

[PDF](http://yangnianzu0515.github.io/files/paper1-learned_index.pdf)


<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->