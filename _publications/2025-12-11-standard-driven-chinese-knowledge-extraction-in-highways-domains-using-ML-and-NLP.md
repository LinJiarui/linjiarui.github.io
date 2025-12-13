---
title: "Standard-Driven Chinese Knowledge Extraction in Highway Domains Using Machine Learning and NLP Approach"
lang: zh
ref: publications/2025-12-11-standard-driven-chinese-knowledge-extraction-in-highways-domains-using-ML-and-NLP
collection: publications
permalink: /publications/2025-12-11-standard-driven-chinese-knowledge-extraction-in-highways-domains-using-ML-and-NLP
excerpt: '本研究提出了一种公路工程相关标准知识的自动提取方法，利用多种模型实现知识图谱生成，实现关键公路工程概念的关联'
date: 2025-12-11
venue: '2024 Proceedings of the ASCE International Conference on Computing in Civil Engineering (i3CE 2024)'
doi: '10.1061/9780784486115.010'
paperurl: 'http://doi.org/10.1061/9780784486115.010'
citation: 'Ching, W.L., Zhang, X.B., Lin, J.R., Hu, Z.Z.* (2025). Standard-Driven Chinese Knowledge Extraction in Highway Domains Using Machine Learning and NLP Approach. <i>Proceedings of the ASCE International Conference on Computing in Civil Engineering (i3CE 2024)</i>, 96-106. Pittsburgh, PA, USA. doi: 10.1061/9780784486115.010'

comment: true
category: conference

tags: 
  - standard
  - knowledge
  - knowledge extraction
  - machine learning
  - ML
  - NLP
  - entity recognition
  - NER
  - TextCNN
  - BERT

grants:
  - 2022YFC3801100
---

{{site.data.ui-text[page.lang].abstract}}
====

信息技术的发展催生了众多提升交通效率的数据驱动策略，但交通系统间的数据交换常受限于数据复杂、定义模糊及格式各异等问题。为此，本文提出一种公路标准知识自动提取模型的构建方法：以 ISO 12006-3 为上层本体，在小规模训练集上采用 BiLSTM-CRF、TextCNN-BiLSTM-CRF、BERT 及 BERT-CRF 等机器学习模型，完成命名实体识别与关系分类任务；通过预测后处理与人工修正优化训练数据集，用于模型迭代学习，并将最优结果整理为图谱并存储为 OWL 本体。该方法从中文标准中生成 158 个图谱，通过 ISO 12006-3 参考类实现关联，串联公路领域概念，为数据管理和项目协作提供支持。该方法为公路项目优化数据管理、促进跨学科协作提供了可行路径，助力该领域数据驱动发展。

Advancements in informatics have led to numerous data-driven strategies for improving transportation efficiency. However, data exchange between transportation systems is often hindered by complexity, ambiguous definitions, and varied data sets. To tackle these issues, this article introduces a method for creating an automatic knowledge extraction model for highway standards. Machine learning models like BiLSTM-CRF, TextCNN-BiLSTM-CRF, BERT, and BERT-CRF are utilized on small training sets for tasks such as Named Entity Recognition using ISO 12006-3 as upper-level ontology and relationship classification. Additionally, post-prediction and manual corrections refine training data sets for iterative learning. The best results are formatted into graphs and saved as OWL ontologies. This approach yielded 158 graphs from Chinese standards, linked via ISO 12006-3 referenced classes, and the outcome links highway domain concepts, enhancing data management and project collaboration. This method shows promise for better data management and interdisciplinary collaboration in highway projects, furthering data-driven progress in the field.

![graphical abstract](/images/2025-12-11-standard-driven-chinese-knowledge-extraction-in-highways-domains-using-ML-and-NLP-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-12-11-standard-driven-chinese-knowledge-extraction-in-highways-domains-using-ML-and-NLP.pdf)

The authors are grateful for the financial support received from the National Key R&D Program of China (No. 2022YFC3801100).