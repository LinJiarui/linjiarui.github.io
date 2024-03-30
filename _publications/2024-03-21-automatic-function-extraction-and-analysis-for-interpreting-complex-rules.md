---
title: "支持复杂规范条文解译的基元函数提取与分析"
lang: zh
ref: publications/2024-03-21-automatic-function-extraction-and-analysis-for-interpreting-complex-rules
collection: publications
permalink: /publications/2024-03-21-automatic-function-extraction-and-analysis-for-interpreting-complex-rules
excerpt: '本研究针对复杂规范条文的计算机解析与推理需求，引入基元函数概念，并提出了相应的基元函数识别与提取方法，研究分析表明所提出的基元函数可更好表征复杂规范条文的计算与推理逻辑，大幅提升复杂条文的解译范围与推理能力。'
date: 2024-03-21
venue: '工程力学'
doi: '10.6052/j.issn.1000-4750.2023.11.0850'
paperurl: 'https://link.cnki.net/urlid/11.2595.O3.20240321.1458.008'
citation: '逯静洲, 曹心瑜, 郑哲, 陆新征, 林佳瑞*. (2024). 支持复杂规范条文解译的基元函数提取与分析. <i>工程力学</i>, xx(x), xx-xx. doi: 10.6052/j.issn.1000-4750.2023.11.0850 (在线发表)'

comment: true
category: journal

tags: 
  - building code
  - ARC
  - rule interpretation
  - atomic function
  - rule checking
  - intelligent design
  - text analysis
  - EI

grants:
  - 72091512
  - 52378306
  - 51978596
---


{{site.data.ui-text[page.lang].abstract}}
====

规则条文解译(Rule interpretation)是智能审图(Automated rule checking, ARC)面临的关键挑战之一，目前依赖领域专家完成规则解译，耗时耗力。其根本原因是规范条文包含大量复杂逻辑与领域隐含知识，计算机缺乏相应的基本常识与逻辑规则，因此难以有效理解和解译复杂设计规范条文。因此，本研究以《建筑设计防火规范》关键内容为例，通过系统整理、分析与拆解有关规范条文，首次提出了基元函数概念，以表征不同规范条文规则推理与逻辑计算过程共用的基础算法单元；并面向复杂规范条文解析，建立了有关基元函数的识别与提取方法，识别、定义了存在性检查、数量检查、几何检查、距离检查、面积检查、空间位置检查、窗墙比检查、属性检查共 8 类 66 个基元函数，构建了首个针对我国建筑结构设计审查的基元函数库。同时，研究从审查对象以及基元函数复杂度、使用频次、共现特征与复杂条文表示能力等方面进行了详细分析，结果表明：基元函数使用频率呈长尾分布；属性类函数与其他各类函数都有较高的共现次数；所建立的基元函数具有强大的复杂逻辑表示能力，可大幅提升复杂条文解译范围与推理能力。

![研究方案](/images/2024-03-21-automatic-function-extraction-and-analysis-for-interpreting-complex-rules-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2024-03-21-automatic-function-extraction-and-analysis-for-interpreting-complex-rules.pdf)

基金资助: 国家自然科学基金项目(72091512，52378306，51978596)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (No. 72091512, No. 52378306, No. 51978596). 