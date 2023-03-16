---
title: "Adversarial Robustness via Random Projection Filters"
authors: "<i><b>Minjing Dong</b></i>, Chang Xu"
collection: publications
permalink: /publication/rpf_cvpr_2023
date: 2023-06-23
venue: '2023 Conference on Computer Vision and Pattern Recognition. CVPR 2023.'
paperurl: 'https://openreview.net/pdf?id=5_DyEmGyOe'
abstract: "Deep Neural Networks show superior performance in various tasks but are vulnerable to adversarial attacks. Most defense techniques are devoted to the adversarial training strategies, however, it is difficult to achieve satisfactory robust performance only with traditional adversarial training. We mainly attribute it to that aggressive perturbations which lead to the loss increment can always be found via gradient ascent in white-box setting. Although some noises can be involved to prevent attacks from deriving precise gradients on inputs, there exist trade-offs between the defense capability and natural generalization. Taking advantage of the properties of random projection, we propose to replace part of convolutional filters with random projection filters, and theoretically explore the geometric representation preservation of proposed synthesized filters via Johnson-Lindenstrauss lemma. We conduct sufficient evaluation on multiple networks and datasets. The experimental results showcase the superiority of proposed random projection filters to state-of-the-art baselines. The code is available on https://github.com/UniSerj/Random-Projection-Filters."
---