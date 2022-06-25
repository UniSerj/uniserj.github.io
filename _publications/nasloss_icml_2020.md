---
title: "Neural architecture search in a proxy validation loss landscape"
authors: "Yanxi Li, <i><b>Minjing Dong</b></i>, Yunhe Wang, Chang Xu"
collection: publications
permalink: /publication/nasloss_icml_2020
date: 2020-11-21
venue: '2020 International Conference on Machine Learning. ICML 2020.'
paperurl: 'http://proceedings.mlr.press/v119/li20c/li20c.pdf'
abstract: "This paper searches for the optimal neural architecture by minimizing a proxy of validation loss. Existing neural architecture search (NAS) methods used to discover the optimal neural architecture that best fits the validation examples given the up-to-date network weights. However, back propagation with a number of validation examples could be time consuming, especially when it needs to be repeated many times in NAS. Though these intermediate validation results are invaluable, they would be wasted if we cannot use them to predict the future from the past. In this paper, we propose to approximate the validation loss landscape by learning a mapping from neural architectures to their corresponding validate losses. The optimal neural architecture thus can be easily identified as the minimum of this proxy validation loss landscape. A novel sampling strategy is further developed for an efficient approximation of the loss landscape. Theoretical analysis indicates that the validation loss estimator learnt with our sampling strategy can reach a lower error rate and a lower label complexity compared with a uniform sampling. Experimental results on benchmarks demonstrate that the architecture searched by the proposed algorithm can achieve a satisfactory accuracy with less time cost."
---
