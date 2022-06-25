---
title: "Adversarial recurrent time series imputation"
authors: "Shuo Yang, <i><b>Minjing Dong</b></i>, Yunhe Wang, Chang Xu"
collection: publications
permalink: /publication/time_tnnls_2020
date: 2020-08-04
venue: '2020 IEEE Transactions on Neural Networks and Learning Systems. TNNLS 2020.'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9158560'
---

## Abstract
For the real-world time series analysis, data missing is a ubiquitously existing problem due to anomalies during data collecting and storage. If not treated properly, this problem will seriously hinder the classification, regression, or related tasks. Existing methods for time series imputation either impose too strong assumptions on the distribution of missing data or cannot fully exploit, even simply ignore, the informative temporal dependencies and feature correlations across different time steps. In this article, inspired by the idea of conditional generative adversarial networks, we propose a generative adversarial learning framework for time series imputation under the condition of observed data (as well as the labels, if possible). In our model, we employ a modified bidirectional RNN structure as the generator G, which is aimed at generating the missing values by taking advantage of the temporal and nontemporal information extracted from the observed time series. The discriminator D is designed to distinguish whether each value in a time series is generated or not so that it can help the generator to make an adjustment toward a more authentic imputation result. For an empirical verification of our model, we conduct imputation and classification experiments on several real-world time series data sets. The experimental results show an eminent improvement compared with state-of-the-art baseline models.
