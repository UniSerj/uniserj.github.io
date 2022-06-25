---
title: "An Empirical Study of Adder Neural Networks for Object Detection"
authors: "Xinghao Chen, Chang Xu, <i><b>Minjing Dong</b></i>, Chunjing Xu, Yunhe Wang"
collection: publications
permalink: /publication/adderdet_nips_2021
date: 2021-12-06
venue: '2021 Advances in Neural Information Processing Systems. NeurIPS 2021.'
paperurl: 'https://proceedings.neurips.cc/paper/2021/file/37693cfc748049e45d87b8c7d8b9aacd-Paper.pdf'
abstract: "Adder neural networks (AdderNets) have shown impressive performance on image classification with only addition operations, which are more energy efficient than traditional convolutional neural networks built with multiplications. Compared with classification, there is a strong demand on reducing the energy consumption of modern object detectors via AdderNets for real-world applications such as autonomous driving and face detection. In this paper, we present an empirical study of AdderNets for object detection. We first reveal that the batch normalization statistics in the pre-trained adder backbone should not be frozen, since the relatively large feature variance of AdderNets. Moreover, we insert more shortcut connections in the neck part and design a new feature fusion architecture for avoiding the sparse features of adder layers. We present extensive ablation studies to explore several design choices of adder detectors. Comparisons with state-of-the-arts are conducted on COCO and PASCAL VOC benchmarks. Specifically, the proposed Adder FCOS achieves a 37.8% AP on the COCO val set, demonstrating comparable performance to that of the convolutional counterpart with an about 1.4x energy reduction."
---
