---
title: "Automatic Construction of Building Code Graph for Regulation Intelligence"
lang: zh
ref: publications/2021-10-16-automatic-construction-of-building-code-graph-for-regulation-intelligence
collection: publications
permalink: /publications/2021-10-16-automatic-construction-of-building-code-graph-for-regulation-intelligence
excerpt: '本研究面向建筑行业法规智能场景，提出一种建筑规范结构化处理及法规图谱自动构建方法，可将规范文本自动转换为XML格式及neo4j图数据库形式，并可基于图数据库检索支撑规范引用关系查询、潜在冲突识别与设计审查，对实现行业法规智能具有启发意义'
date: 2021-10-16
venue: 'Proceedings of the 2021 International Conference on Construction and Real Estate Management (ICCREM 2021)'
doi: '10.1061/9780784483848.028'
paperurl: 'https://doi.org/10.1061/9780784483848.028'
citation: 'Zhou, Y.C., Lin, J.R.*,  She, Z.T. (2021). Automatic Construction of Building Code Graph for Regulation Intelligence. <i>Proceedings of the 2021 International Conference on Construction and Real Estate Management (ICCREM 2021)</i>, 248-254. Beijing, China.'

comment: true
category: conference

tags: 
  - NLP
  - code graph
  - text mining
  - construction
  - neo4j
  - database
  - building
  - regulation intelligence
  - regulatory intelligence

grants:
  - 51908323
  - 72091512
  - 2019Z02UOT
---


{{site.data.ui-text[page.lang].abstract}}
====

本研究面向建筑行业法规智能场景，提出一种建筑规范结构化处理及法规图谱自动构建方法，可将规范文本自动转换为XML格式及neo4j图数据库形式，并可基于图数据库检索支撑规范引用关系查询、潜在冲突识别与设计审查，对实现行业法规智能具有启发意义。

Building codes are composed of a set of requirements that govern the design, construction, and maintenance of buildings and structures. Currently, most building codes are stored in unstructured text-based documents. However, with the advance of artificial intelligence, these unstructured building codes are no longer meet the requirements toward regulation intelligence scenarios such as design compliance review, relation analysis, and so on. To address this problem, this research proposes a method to automatically collect and formalize building codes and transform them into a knowledge graph representation. The method mainly consists of three steps: 1) data collection, which automatically collects building codes by crawling data in the web; 2) data structuring, which automatically transforms text-based building codes (e.g., HTML and PDF) into XML structure; and 3) graph generation, which transforms XML-based building codes into Neo4j graph database. The proposed method is implemented and tested in a case study. The result demonstrates the feasibility of the method and shows that the generated knowledge graph can support multiple regulation intelligence scenarios such as regulation relation retrieval, regulation conflict analysis, design compliance review, and so forth. 

论文第一作者周育丞于2021年10月16日下午在2021年建设与房地产国际学术研讨会（ICCREM 2021）做了口头报告，论文同时获得ICCREM 2021国际会议优秀论文奖。

![优秀论文奖]({{ site.baseurl }}/images/2021-10-16-best-paper-award-iccrem2021.jpg)

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2021-10-16-automatic-construction-of-building-code-graph-for-regulation-intelligence.pdf)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

The authors are grateful for the financial support received from the National Natural Science Foundation of China (No. 51908323, No. 72091512), and the Tsinghua University Initiative Scientific Research Program (No. 2019Z02UOT). 