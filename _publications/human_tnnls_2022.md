---
title: "Skeleton-Based Human Motion Prediction With Privileged Supervision"
authors: "<i><b>Minjing Dong</b></i>, Chang Xu"
collection: publications
permalink: /publication/human_tnnls_2022
date: 2022-04-21
venue: '2022 IEEE Transactions on Neural Networks and Learning Systems. TNNLS 2022.'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9761789'
abstract: "Existing supervised methods have achieved impressive performance in forecasting skeleton-based human motion. However, they often rely on action class labels in both training and inference phases. In practice, it could be a burden to request action class labels in the inference phase, and even for the training phase, the collected labels could be incomplete for sequences with a mixture of multiple actions. In this article, we take action class labels as a kind of privileged supervision that only exists in the training phase. We design a new architecture that includes a motion classification as an auxiliary task with motion prediction. To deal with potential missing labels of motion sequence, we propose a new classification loss function to exploit their relationships with those observed labels and a perceptual loss to measure the difference between ground truth sequence and generated sequence in the classification task. Experimental results on the most challenging Human 3.6M dataset and the Carnegie Mellon University (CMU) dataset demonstrate the effectiveness of the proposed algorithm to exploit action class labels for improved modeling of human dynamics."
---
