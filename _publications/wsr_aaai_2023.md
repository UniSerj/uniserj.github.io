---
title: "Neural Architecture Search for Wide Spectrum Adversarial Robustness"
authors: "Zhi Cheng, Yanxi Li, <i><b>Minjing Dong</b></i>, Xiu Su, Shan You, Chang Xu"
collection: publications
permalink: /publication/wsr_aaai_2023
date: 2023-06-26
venue: '2023 AAAI Conference on Artificial Intelligence. AAAI 2023.'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/25118/24890'
abstract: "One major limitation of CNNs is that they are vulnerable to adversarial attacks. Currently, adversarial robustness in neural networks is commonly optimized with respect to a small pre-selected adversarial noise strength, causing them to have potentially limited performance when under attack by larger adversarial noises in real-world scenarios. In this research, we aim to find Neural Architectures that have improved robustness on a wide range of adversarial noise strengths through Neural Architecture Search. In detail, we propose a lightweight Adversarial Noise Estimator to reduce the high cost of generating adversarial noise with respect to different strengths. Besides, we construct an Efficient Wide Spectrum Searcher to reduce the cost of adjusting network architecture with the large adversarial validation set during the search. With the two components proposed, the number of adversarial noise strengths searched can be increased significantly while having a limited increase in search time. Extensive experiments on benchmark datasets such as CIFAR and ImageNet demonstrate that with a significantly richer search signal in robustness, our method can find architectures with improved overall robustness while having a limited impact on natural accuracy and around 40% reduction in search time compared with the naive approach of searching. Codes available at: https://github.com/zhicheng2T0/Wsr-NAS."
---
