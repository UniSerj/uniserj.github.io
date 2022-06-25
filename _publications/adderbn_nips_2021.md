---
title: "Towards Stable and Robust Addernets"
authors: "<i><b>Minjing Dong</b></i>, Yunhe Wang, Xinghao Chen, Chang Xu"
collection: publications
permalink: /publication/adderbn_nips_2021
date: 2021-12-06
venue: '2021 Advances in Neural Information Processing Systems. NeurIPS 2021.'
paperurl: 'https://proceedings.neurips.cc/paper/2021/file/6e3197aae95c2ff8fcab35cb730f6a86-Paper.pdf'
abstract: "Adder neural network (AdderNet) replaces the original convolutions with massive multiplications by cheap additions while achieving comparable performance thus yields a series of energy-efficient neural networks. Compared with convolutional neural networks (CNNs), the training of AdderNets is much more sophisticated including several techniques for adjusting gradient and batch normalization. In addition, variances of both weights and activations in resulting adder networks are very enormous which limits its performance and the potential for applying to other tasks. To enhance the stability and robustness of AdderNets, we first thoroughly analyze the variance estimation of weight parameters and output features of an arbitrary adder layer. Then, we develop a weight normalization scheme for adaptively optimizing the weight distribution of AdderNets during the training procedure, which can reduce the perturbation on running mean and variance in batch normalization layers. Meanwhile, the proposed weight normalization can also be utilized to enhance the adversarial robustness of resulting networks. Experiments conducted on several benchmarks demonstrate the superiority of the proposed approach for generating AdderNets with higher performance."
---
