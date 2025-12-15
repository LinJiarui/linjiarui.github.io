---
title: "Knowledge-Informed Semantic Alignment and Rule Interpretation for Automated Compliance Checking"
lang: zh
ref: publications/2022-08-03-knowledge-informed-semantic-alignment-and-rule-interpretation-for-ACC
collection: publications
permalink: /publications/2022-08-03-knowledge-informed-semantic-alignment-and-rule-interpretation-for-ACC
excerpt: '面向智能审图需求，提出一种知识增强的语义对齐及规则解译方法，解决了设计模型与规范文本直接的语义不一致问题，有效提升了规则解译准确度及审图效率'
date: 2022-08-03
venue: 'Automation in Construction'
doi: '10.1016/j.autcon.2022.104524'
paperurl: 'http://doi.org/10.1016/j.autcon.2022.104524'
citation: 'Zheng, Z., Zhou, Y.C., Lu, X.Z., Lin, J.R.* (2022). Knowledge-Informed Semantic Alignment and Rule Interpretation for Automated Compliance Checking. <i>Automation in Construction</i>, 142, 104524. doi: 10.1016/j.autcon.2022.104524'

comment: true
category: journal

tags: 
  - semantic alignment
  - rule interpretation
  - compliance checking
  - NLP
  - construction industry
  - knowledge modeling
  - SCI

grants:
  - 51908323
  - 72091512
  - 2019YFE0112800
  - XPLORER
---


{{site.data.ui-text[page.lang].abstract}}
====

作为提高建筑设计质量的关键环节，设计自动审查（即智能审图）的关键是实现规范文本的智能解释并实现不同来源的领域概念的精准对齐。然而，当前设计模型/图纸及规范文本之间仍然存在明显的语义鸿沟，极大地阻碍了智能审图方法的研发和应用。因此，基于自然语言处理，本研究提出一种知识增强的智能审图方法。首先，研究建立了一套领域本体以描述概念、同义词、关系、约束等各类领域知识；同时，研究提出了语义对齐和冲突消解方法，基于领域先验知识和无监督学习技术改进了自动规则解释过程。最后，研发了一种自动将审查规则转换为SPARQL查询的算法，通过自动匹配SPARQL函数实现了复杂规则解译和隐含属性的自动推理。实验表明，所提出的框架和方法通过引入领域知识有效解决了设计模型和规范文本之间的语义鸿沟，语义对齐准确率高达 90.1%，显著优于常用的关键词匹配方法。同时，所提出的规则解译方法相比领域专家人工解译提效5倍以上。本研究为智能审图贡献了一套知识增强的新方法，实现了领域知识的引入与高效利用。

As an essential prodecure to improve design quality in the construction industry, automated rule checking (ARC) requires intelligent rule interpretation from regulatory texts and precise alignment of concepts from different sources. However, there still exists semantic gaps between design models and regulatory texts, hindering the exploitation of ARC. Thus, a knowledge-informed framework for improved ARC is proposed based on natural language processing. Within the framework, an ontology is first established to represent domain knowledge, including concepts, synonyms, relationships, constraints, etc. Then, semantic alignment and conflict resolution are introduced to enhance the rule interpretation process based on predefined domain knowledge and unsupervised learning techniques. Finally, an algorithm is developed to identify the proper SPARQL function for each rule, and then to generate SPARQL-based queries for model checking purposes, thereby making it possible to interpret complex rules where extra implicit data needs to be inferred. Experiments show that the proposed framework and methods successfully filled the semantic gaps between design models and regulatory texts with domain knowledge, which achieves a 90.1% accuracy and substantially outperforms the commonly used keyword matching method. In addition, the proposed rule interpretation method proves to be 5 times faster than the manual interpretation by domain experts. This research contributes to the body of knowledge of a novel framework and the corresponding methods to enhance automated rule checking with domain knowledge. 

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2022-08-03-knowledge-informed-semantic-alignment-and-rule-interpretation-for-ACC.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (No. 51908323, No. 72091512), the National Key R&D Program (No. 2019YFE0112800), and the Tencent Foundation through the XPLORER PRIZE.