---
title: "A Text Classification-based Approach for Evaluating and Enhancing the Machine Interpretability of Building Codes"
lang: zh
ref: publications/2023-09-24-text-classification-for-evaluating-and-enhancing-machine-interpretability-of-building-codes
collection: publications
permalink: /publications/2023-09-24-text-classification-for-evaluating-and-enhancing-machine-interpretability-of-building-codes
excerpt: '本研究基于团队领域大语言模型成果，提出一种高效的规范条文分类及规范可解译性评价方法；结果表明所提出的算法F1指标为93.6%、显著优于既有方法，且可进一步将升下游规则自动解译算法提升4%；研究同时表明现有规范的整体机器可解译性仅有34.4%，亟需从人-机双方角度改进规范编写方法及规则解译算法，实现完全自动化的规范解析'
date: 2023-09-24
venue: 'Engineering Applications of Artificial Intelligence'
doi: '10.1016/j.engappai.2023.107207'
paperurl: 'http://doi.org/10.1016/j.engappai.2023.107207'
citation: 'Zheng, Z., Zhou, Y.C., Chen, K.Y., Lu, X.Z., She, Z.T., Lin, J.R.* (2024). A Text Classification-based Approach for Evaluating and Enhancing the Machine Interpretability of Building Codes. <i>Engineering Applications of Artificial Intelligence</i>, 127, 107207. doi: 10.1016/j.engappai.2023.107207'

comment: true
category: journal

tags: 
  - rule interpretation
  - NLP
  - ARC
  - pretrained model
  - intelligent design
  - text classification
  - human-machine intelligence
  - SCI

grants:
  - 52378306
  - 51908323
---


{{site.data.ui-text[page.lang].abstract}}
====

将建筑工程规范及标准文档自动解析为计算机可处理的格式对于建筑物和基础设施的智能设计、建造至关重要。尽管自动规则解释 (ARI) 方法已被研究多年，但大多数方法仍高度依赖人工筛选可计算机解译的规范条文。且基本无人关注规范条文以及规范文档整体的机器可解译性，以评估单个规范条文或规范文档整体转换为计算机可处理格式的潜力。因此，本研究基于领域大模型，提出一种自动评估和增强单个条文及整体规范文档机器可解译性的新方法。 首先，考虑条文规则解译要求，研究建立了规范条文的分类规则并建立了有关模型训练数据集。 进而，基于团队领域预训练大模型和迁移学习算法，构建了规范条文高效分类算法。以此为基础，本研究首次提出了定量评估规范文本可解译性的新方法。 研究表明，所提出的文本分类算法优于现有基于CNN或 RNN的方法，可将F1指标从72.16%提升到93.60%，且所提出的分类方法可以有效增强下游ARI算法，准确度可提升4%。同时，对中国150多部建筑工程规范文本的分析表明，规范文档整体的平均可解释性仅为34.40%，这意味着将整个规范性文件完全转换为计算机可处理的格式仍然面临巨大挑战。当前，亟需从人（在编写建筑规范时考虑某些约束）-机（开发更强大的算法、工具等）两个角度综合创新，以进一步推动计算机可完全解译推理的规范数字化技术发展。


![graphical abstract](/images/2023-09-24-text-classification-for-machine-interpretability-of-building-codes-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2023-09-24-text-classification-for-evaluating-and-enhancing-machine-interpretability-of-building-codes.pdf)

The authors are grateful for the financial support received from the 2023 Open Selection Project of Tsinghua University-Tsingshang Joint Institute for Smart Scene Innovation Design and the National Natural Science Foundation of China (no. 52378306 and no. 51908323).