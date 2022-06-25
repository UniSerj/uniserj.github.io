---
title: "Adversarially Robust Neural Architectures"
authors: "<i><b>Minjing Dong</b></i>, Yanxi Li, Yunhe Wang, Chang Xu"
collection: publications
permalink: /publication/racl_arxiv_2020
date: 2020-09-02
venue: 'arXiv preprint. arXiv 2020.'
paperurl: 'https://arxiv.org/pdf/2009.00902'
abstract: "Deep Neural Network (DNN) are vulnerable to adversarial attack. Existing methods are devoted to developing various robust training strategies or regularizations to update the weights of the neural network. But beyond the weights, the overall structure and information flow in the network are explicitly determined by the neural architecture, which remains unexplored. This paper thus aims to improve the adversarial robustness of the network from the architecture perspective with NAS framework. We explore the relationship among adversarial robustness, Lipschitz constant, and architecture parameters and show that an appropriate constraint on architecture parameters could reduce the Lipschitz constant to further improve the robustness. For NAS framework, all the architecture parameters are equally treated when the discrete architecture is sampled from supernet. However, the importance of architecture parameters could vary from operation to operation or connection to connection, which is not explored and might reduce the confidence of robust architecture sampling. Thus, we propose to sample architecture parameters from trainable multivariate log-normal distributions, with which the Lipschitz constant of entire network can be approximated using a univariate log-normal distribution with mean and variance related to architecture parameters. Compared with adversarially trained neural architectures searched by various NAS algorithms as well as efficient human-designed models, our algorithm empirically achieves the best performance among all the models under various attacks on different datasets."
---
