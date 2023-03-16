---
title: "Random Normalization Aggregation for Adversarial Defense"
authors: "<i><b>Minjing Dong</b></i>, Xinghao Chen, Yunhe Wang, Chang Xu"
collection: publications
permalink: /publication/rna_nips_2022
date: 2022-11-28
venue: '2022 Advances in Neural Information Processing Systems. NeurIPS 2022.'
paperurl: 'https://openreview.net/pdf?id=K4W92FUXSF9'
abstract: "The vulnerability of deep neural networks has been widely found in various models as well as tasks where slight perturbations on the inputs could lead to incorrect predictions. These perturbed inputs are known as adversarial examples and one of the intriguing properties of them is Adversarial Transfersability, i.e. the capability of adversarial examples to fool other models. Traditionally, this transferability is always regarded as a critical threat to the defense against adversarial attacks,
however, we argue that the network robustness can be significantly boosted by
utilizing adversarial transferability from a new perspective. In this work, we first
discuss the influence of different popular normalization layers on the adversarial
transferability, and then provide both empirical evidence and theoretical analysis to shed light on the relationship between normalization types and transferability. Based on our theoretical analysis, we propose a simple yet effective module named Random Normalization Aggregation (RNA) which replaces the batch normalization layers in the networks and aggregates different selected normalization types to form a huge random space. Specifically, a random path is sampled during each inference procedure so that the network itself can be treated as an ensemble of a wide range of different models. Since the entire random space is designed with low adversarial transferability, it is difficult to perform effective attacks even when the network parameters are accessible. We conduct extensive experiments on various models and datasets, and demonstrate the strong superiority of proposed algorithm. The PyTorch code is available at https://github.com/UniSerj/Random-Norm-Aggregation and the MindSpore code is available at https://gitee.com/mindspore/models/tree/master/research/cv/RNA."
---