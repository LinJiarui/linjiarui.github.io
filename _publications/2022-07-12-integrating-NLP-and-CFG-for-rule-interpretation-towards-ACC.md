---
title: "Integrating NLP and Context-Free Grammar for Complex Rule Interpretation towards Automated Compliance Checking"
lang: zh
ref: publications/2022-07-12-integrating-NLP-and-CFG-for-rule-interpretation-towards-ACC
collection: publications
permalink: /publications/2022-07-12-integrating-NLP-and-CFG-for-rule-interpretation-towards-ACC
excerpt: '研究建立了首个面向建筑业智能审图（设计自动审查）规则解译的规范条文数据集并提出了基于深度NLP和上下文无关文法（CFG）的智能规则解译方法，实验表明，相较已有方法本文方法具有显著优势，对简单句和复杂句的解译准确率分别达到99.6%和91%，突破了既有方法不能处理复杂句的难题。研究同时公开了有关数据集和算法，可为行业相关算法开发、测试提供参考'
date: 2022-07-12
venue: 'Computers in Industry'
doi: '10.1016/j.compind.2022.103746'
paperurl: 'http://doi.org/10.1016/j.compind.2022.103746'
citation: 'Zhou, Y.C., Zheng, Z., Lin, J.R.*, Lu, X.Z. (2022). Integrating NLP and Context-Free Grammar for Complex Rule Interpretation towards Automated Compliance Checking. <i>Computers in Industry</i>, 142, 103746. doi: 10.1016/j.compind.2022.103746'

comment: true
category: journal

tags: 
  - rule interpretation
  - deep learning
  - context-free grammar
  - automated compliance checking
  - automated rule checking
  - semantic labeling
  - syntax parsing
  - smart design
  - BIM
  - NLP
  - SCI

grants:
  - 51908323
  - 72091512
  - 2018YFD1100900
  - 2019Z02UOT
---


{{site.data.ui-text[page.lang].abstract}}
====

智能审图或自动规则检查 (ARC) 可显著提升建筑行业设计的效率和合规性，其关键环节之一是将规范、标准等文本自动解译为计算机可处理的格式。然而，现有的规则方法以人工解译和正则表达式模式匹配为主，耗时长、适用范围有限。因此，本研究提出一种集成自然语言处理（NLP）和上下文无关语法（CFG）的规则自动解译新方法，可将规范条文视为特定领域语言实现高效解析。研究首先提出一种包含多种语义元素的句法树结构来表示规范文本有关概念的角色和相互关系；同时，基于深度学习和迁移学习实现了规范条文语义元素的自动标注；最后，提出了面向规则解译的CFG文法结构，实现了规范条文向语言无关逻辑树的自动转换，支持可计算逻辑自动生成。实验显示，本文方法相较既有方法优势显著，简单约束句和复杂约束句的解析准确度分别达到了 99.6% 和 91.0% 突破了既有方法不能处理规范中普遍存在的复杂条文的问题。本研究为规范条文自动解译提供了一种自动、通用的方法框架，可以从规范、标准、合同等各类文本中提取可计算逻辑规则；同时，研究开放了首个规范条文解译数据集，为领域算法开发、测试以及应用提供了重要支撑。


Automated rule checking (ARC) is expected to significantly promote the efficiency and compliance of design in the construction industry. The most vital and complex stage of ARC is interpreting the regulatory text into a computer-processable format. However, existing systems and studies of rule interpretation either require considerable time-consuming manual effort or are based on exhaustive enumerations of matching patterns with a limited scope of application. To address this problem, this research integrates natural language processing (NLP) and context-free grammar (CFG) to propose a novel generalized rule interpretation framework, which can parse regulatory text like a domain-specific language. First, a syntax tree structure with several semantic elements is proposed to represent the roles and relations of concepts in regulatory text. Second, a deep learning model with the transfer learning technique is utilized to label the semantic elements in a sentence. Finally, a set of CFGs is built to parse a labeled sentence into the language-independent tree structure, from which computable checking rules can be generated. Experimental results demonstrate our method outperforms the state-of-the-art methods: it achieves 99.6% and 91.0% accuracies for parsing single- and multi-requirement sentences, respectively, where the multi-requirement sentences are more complex and common but difficult for existing methods to deal with. This research contributes a method and framework for rule interpretation with both a high level of automation and wide scope of application, which can create computable rules from various textual regulatory documents. This research also publishes the first regulation dataset for future exploration, validation, and benchmarking in the ARC area. 

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2022-07-12-integrating-NLP-and-CFG-for-rule-interpretation-towards-ACC.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (No. 51908323, No. 72091512), the National Key R&D Program of China (No. 2018YFD1100900), and the Tsinghua University Initiative Scientific Research Program (No. 2019Z02UOT).