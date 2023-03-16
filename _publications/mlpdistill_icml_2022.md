---
title: "Spatial-Channel Token Distillation for Vision MLPs"
authors: "Yanxi Li, Xinghao Chen,<i><b>Minjing Dong</b></i>, Yehui Tang, Yunhe Wang, Chang Xu"
collection: publications
permalink: /publication/mlpdistill_icml_2022
date: 2022/6/28
venue: '2022 International Conference on Machine Learning. ICML 2022.'
paperurl: 'https://proceedings.mlr.press/v162/li22c/li22c.pdf'
abstract: "Recently, neural architectures with all Multi-layer Perceptrons (MLPs) have attracted great research interest from the computer vision community. However, the inefficient mixing of spatial-channel information causes MLP-like vision models to demand tremendous pre-training on large-scale datasets. This work solves the problem from a novel knowledge distillation perspective. We propose a novel Spatial-channel Token Distillation (STD) method, which improves the information mixing in the two dimensions by introducing distillation tokens to each of them. A mutual information regularization is further introduced to let distillation tokens focus on their specific dimensions and maximize the performance gain. Extensive experiments on ImageNet for several MLP-like architectures demonstrate that the proposed token distillation mechanism can efficiently improve the accuracy. For example, the proposed STD boosts the top-1 accuracy of Mixer-S16 on ImageNet from 73.8% to 75.7% without any costly pre-training on JFT-300M. When applied to stronger architectures, eg CycleMLP-B1 and CycleMLP-B2, STD can still harvest about 1.1% and 0.5% accuracy gains, respectively."
---
