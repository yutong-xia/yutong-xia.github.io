---
title: "Deciphering Spatio-Temporal Graph Forecasting: A Causal Lens and Treatment"
collection: publications
permalink: /publication/2023-NeurIPS-CaST
excerpt: 'In this study, through a causal lens, we propose a novel framework called CaST to tackle temporal OoD and dynamic spatial causation in STG forecasting.'
date: 2023-09-26
venue: 'NeurIPS-23'
paperurl: 'https://arxiv.org/pdf/2309.13378.pdf'
---

Spatio-Temporal Graph Neural Networks often struggle with temporal out-of-distribution (OoD) issues and dynamic spatial causation. In this paper, we propose a novel framework called CaST to tackle these two challenges via causal treatments. Concretely, leveraging a causal lens, we first build a structural causal model to decipher the data generation process of STGs. To handle the temporal OoD issue, we employ the back-door adjustment by a novel disentanglement block to separate invariant parts and temporal environments from input data. Moreover, we utilize the front-door adjustment and adopt the Hodge-Laplacian operator for edge-level convolution to model the ripple effect of causation. 

[Paper](https://arxiv.org/pdf/2309.13378.pdf), [Code](https://github.com/yutong-xia/CaST)

Citation: 
```
@article{xia2023deciphering,
  title={Deciphering Spatio-Temporal Graph Forecasting: A Causal Lens and Treatment},
  author={Xia, Yutong and Liang, Yuxuan and Wen, Haomin and Liu, Xu and Wang, Kun and Zhou, Zhengyang and Zimmermann, Roger},
  journal={arXiv preprint arXiv:2309.13378},
  year={2023}
}
```