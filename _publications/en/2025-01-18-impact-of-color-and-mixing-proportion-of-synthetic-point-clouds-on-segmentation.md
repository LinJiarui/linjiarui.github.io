---
title: "Impact of Color and Mixing Proportion of Synthetic Point Clouds on Semantic Segmentation"
lang: en
ref: publications/2025-01-18-impact-of-color-and-mixing-proportion-of-synthetic-point-clouds-on-segmentation
collection: publications
permalink: /en/publications/2025-01-18-impact-of-color-and-mixing-proportion-of-synthetic-point-clouds-on-segmentation
excerpt: 'This paper unveils the performance-improving mechanism of synthetic point clouds (SPC) by introducing: 1) method to generate SPC with real colors and uniform colors from BIM, and 2) enhanced benchmarks for better performance evaluation.'
date: 2025-01-18
venue: 'Automation in Construction'
doi: '10.1016/j.autcon.2025.105963'
paperurl: 'http://doi.org/10.1016/j.autcon.2025.105963'
citation: 'Zhou, S., Lin, J.R.*, Pan, P., Pan, Y., Brilakis, I. (2025). Impact of Color and Mixing Proportion of Synthetic Point Clouds on Semantic Segmentation. <i>Automation in Construction</i>, 171, 105963. doi: 10.1016/j.autcon.2025.105963'

comment: true
category: journal

tags: 
  - point cloud
  - synthetic point cloud
  - semantic segmentation
  - built environment
  - construction site
  - deep learning
  - intelligent construction
  - digital twin
  - SCI

grants:
  - 2023YFC3805800
  - 5200-202311481A-3-2-ZN
---

{{site.data.ui-text[page.lang].abstract}}
====

Deep learning (DL)-based point cloud segmentation is essential for understanding built environment. Despite synthetic point clouds (SPC) having the potential to compensate for data shortage, how synthetic color and mixing proportion impact DL-based segmentation remains a long-standing question. Therefore, this paper addresses this question with extensive experiments by introducing: 1) method to generate SPC with real colors and uniform colors from BIM, and 2) enhanced benchmarks for better performance evaluation. Experiments on DL models including PointNet, PointNet++, and DGCNN show that model performance on SPC with real colors outperforms that on SPC with uniform colors by 8.2 % + on both OA and mIoU. Furthermore, a higher than 70 % mixing proportion of SPC usually leads to better performance. And SPC can replace real ones to train a DL model for detecting large and flat building elements. Overall, this paper unveils the performance-improving mechanism of SPC and brings new insights to boost SPC's value(for building large models for point clouds).

SOTA results of this study could be accessed via [github](https://github.com/smartaec/Synthetic-Point-Clouds-for-semantic-segmentation)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-01-18-impact-of-color-and-mixing-proportion-of-synthetic-point-clouds-on-segmentation.pdf)

This research was conducted with the supports of the “National Key R&D Program of China” (Project No. 2023YFC3805800) and the project “Research on Key Technologies for Mechanized Construction of Substation Civil Engineering” of “Technology project funding from State Grid Corporation of China” (Project No. 5200-202311481A-3-2-ZN).