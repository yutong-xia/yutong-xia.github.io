---
title: "LargeST: A Benchmark Dataset for Large-Scale Traffic Forecasting"
collection: publications
permalink: /publication/2023-NeurIPS-LargeST
excerpt: 'We introduce the LargeST benchmark dataset, which encompasses a total number of 8,600 sensors with a 5-year time coverage and includes comprehensive metadata.'
date: 2023-09-26
venue: 'NeurIPS-23'
paperurl: 'https://arxiv.org/pdf/2306.08259.pdf'
---

Traffic forecasting plays a critical role in smart city initiatives and has experienced significant advancements thanks to the power of deep learning in capturing non-linear patterns of traffic data. However, the promising results achieved on current public datasets may not be applicable to practical scenarios due to limitations within these datasets. First, the limited sizes of them may not reflect the real-world scale of traffic networks. Second, the temporal coverage of these datasets is typically short, posing hurdles in studying long-term patterns and acquiring sufficient samples for training deep models. Third, these datasets often lack adequate metadata for sensors, which compromises the reliability and interpretability of the data. To mitigate these limitations, we introduce the LargeST benchmark dataset. It encompasses a total number of 8,600 sensors with a 5-year time coverage and includes comprehensive metadata. Using LargeST, we perform in-depth data analysis to extract data insights, benchmark well-known baselines in terms of their performance and efficiency, and identify challenges as well as opportunities for future research.

[Paper](https://arxiv.org/pdf/2306.08259.pdf), [Code](https://github.com/liuxu77/LargeST)

Citation: 
```
@article{liu2023largest,
  title={LargeST: A Benchmark Dataset for Large-Scale Traffic Forecasting},
  author={Liu, Xu and Xia, Yutong and Liang, Yuxuan and Hu, Junfeng and Wang, Yiwei and Bai, Lei and Huang, Chao and Liu, Zhenguang and Hooi, Bryan and Zimmermann, Roger},
  journal={arXiv preprint arXiv:2306.08259},
  year={2023}
}
```