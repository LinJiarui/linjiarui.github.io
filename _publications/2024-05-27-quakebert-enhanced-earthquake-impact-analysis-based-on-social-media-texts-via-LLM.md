---
title: "Enhanced Earthquake Impact Analysis based on Social Media Texts via Large Language Model"
lang: zh
ref: publications/2024-05-27-quakebert-enhanced-earthquake-impact-analysis-based-on-social-media-texts-via-LLM
collection: publications
permalink: /publications/2024-05-27-quakebert-enhanced-earthquake-impact-analysis-based-on-social-media-texts-via-LLM
excerpt: '本研究研发了首个地震领域大模型，并通过该模型实现了社交媒体文本震害信息的高效提取与地震影响快速评估，可有效去除大量噪声信息、提升灾后决策效率'
date: 2024-05-27
venue: 'International Journal of Disaster Risk Reduction'
doi: '10.1016/j.ijdrr.2024.104574'
paperurl: 'http://doi.org/10.1016/j.ijdrr.2024.104574'
citation: 'Han, J., Zheng, Z., Lu, X.Z., Chen, K.Y., Lin, J.R.* (2024). Enhanced Earthquake Impact Analysis based on Social Media Texts via Large Language Model. <i>International Journal of Disaster Risk Reduction</i>, 109, 104574. doi: 10.1016/j.ijdrr.2024.104574'

comment: true
category: journal

tags: 
  - LLM
  - earthquake
  - impact assessment
  - text mining
  - social media
  - BERT
  - social impact
  - large language model
  - SCI

grants:
  - 52238011
  - 52378306
  - 72091512
  - xplorize
---


{{site.data.ui-text[page.lang].abstract}}
====

在地震灾害发生后，迅速获取和分析相关信息对于应急响应至关重要。在互联网时代，社交媒体上是重要的信息来源，目前已有很多学者利用社交媒体上的海量数据辅助灾难后响应。但微博上存在大量的不专业的描述（“我婆娘说她的脑壳都晃昏咯”），还有各种噪音或干扰信息（比如“美国政坛地震，特朗普被判有罪！”）。那么，如何高效地从包含大量噪声的社交媒体数据中提取灾害损失数据呢？

针对以上问题，本研究提出了一种大语言模型增强的社交媒体文本地震信息提取与影响分析方法，用于地震损失的快速评估。我们开发并微调了第一个地震领域的大语言模型 QuakeBERT，显著提高了地震损失信息的提取精度和效率。通过结合舆情趋势分析、情绪分析和基于关键词的物理影响量化，实现对地震物理和社会影响的快速评估。实验结果表明，QuakeBERT 的性能优于传统模型，能够有效过滤嘈杂的微博并辅助后续的地震影响评估过程，从而实现有效的灾后应急响应，创建更具韧性的城市。



![graphical abstract](/images/2024-05-27-quakebert-enhanced-earthquake-impact-analysis-based-on-social-media-texts-via-LLM-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2024-05-27-quakebert-enhanced-earthquake-impact-analysis-based-on-social-media-texts-via-LLM.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (No. 52238011, 52378306, 72091512) and the Tencent Foundation through the XPLORER PRIZE.