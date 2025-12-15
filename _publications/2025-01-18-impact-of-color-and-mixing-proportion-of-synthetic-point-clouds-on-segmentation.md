---
title: "Impact of Color and Mixing Proportion of Synthetic Point Clouds on Semantic Segmentation"
lang: zh
ref: publications/2025-01-18-impact-of-color-and-mixing-proportion-of-synthetic-point-clouds-on-segmentation
collection: publications
permalink: /publications/2025-01-18-impact-of-color-and-mixing-proportion-of-synthetic-point-clouds-on-segmentation
excerpt: '本研究提出了高保真合成点云的生成方法，以及点云分割模型的性能评测基准实验，揭示了合成点云对点云分割等任务的性能提升机理。结果表明，高保真合成点云对OA及mIoU的提升不低于8.2%，且与真实点云的比例高于7:3时对性能具有显著提升'
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

基于深度学习 (DL) 的点云语义分割对于理解建筑或工地环境至关重要。尽管合成点云 (SPC) 有可能弥补数据短缺问题，但合成点云的颜色和混合比例如何影响点云分割的深度谢谢模型仍然悬而未决。因此，本文通过引入：1）新颖的高保真彩色点云与一致颜色点云合成方法，以及2）增强的语义分割模型评测基准实验，解决了上述问题。基于PointNet、PointNet++、DGCNN、Point Transformer等DL模型的实验表明，相较一致颜色点云，高保真彩色合成点云对OA和mIoU的提升不低于8.2%。此外，高于70%的合成点云混合比例通常会带来显著的性能提升。研究同时表明，在识别墙、板等大而扁平的建筑构件是，合成点云可以完全替代真实点云来训练语义分割模型。总体而言，研究深入揭示了合成点云对语义分割模型的性能提升机理，为进一步释放合成点云的价值、乃至点云大模型的构建带来了新的启示。

Deep learning (DL)-based point cloud segmentation is essential for understanding built environment. Despite synthetic point clouds (SPC) having the potential to compensate for data shortage, how synthetic color and mixing proportion impact DL-based segmentation remains a long-standing question. Therefore, this paper addresses this question with extensive experiments by introducing: 1) method to generate SPC with real colors and uniform colors from BIM, and 2) enhanced benchmarks for better performance evaluation. Experiments on DL models including PointNet, PointNet++, and DGCNN show that model performance on SPC with real colors outperforms that on SPC with uniform colors by 8.2 % + on both OA and mIoU. Furthermore, a higher than 70 % mixing proportion of SPC usually leads to better performance. And SPC can replace real ones to train a DL model for detecting large and flat building elements. Overall, this paper unveils the performance-improving mechanism of SPC and brings new insights to boost SPC's value(for building large models for point clouds).


本研究的最新实验结果可通过[github](https://github.com/smartaec/Synthetic-Point-Clouds-for-semantic-segmentation)查看。

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-01-18-impact-of-color-and-mixing-proportion-of-synthetic-point-clouds-on-segmentation.pdf)

This research was conducted with the supports of the “National Key R&D Program of China” (Project No. 2023YFC3805800) and the project “Research on Key Technologies for Mechanized Construction of Substation Civil Engineering” of “Technology project funding from State Grid Corporation of China” (Project No. 5200-202311481A-3-2-ZN).