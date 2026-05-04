---
title: "Graph-Based Rule Representation for Automated Design Checking"
lang: zh
ref: publications/2026-02-21-graph-based-rule-representation-for-automated-design-checking
collection: publications
permalink: /publications/2026-02-21-graph-based-rule-representation-for-automated-design-checking
excerpt: '研究提出一种面向智能审图的图结构规则表达方法，实现了高效的审图规则表征与代码生成'
date: 2026-02-21
venue: 'Architectural Engineering and Design Management'
doi: '10.1080/17452007.2026.2632098'
paperurl: 'http://doi.org/10.1080/17452007.2026.2632098'
citation: 'Zhang, S., Chen, K.Y., Lin, J.R.*, Pan, P.* (2026). Graph-Based Rule Representation for Automated Design Checking. <i>Architectural Engineering and Design Management</i>, 1-27. doi: 10.1080/17452007.2026.2632098'

comment: true
category: journal

tags: 
  - ACC
  - design checking
  - rule representation
  - rule interpretation
  - knowledge graph
  - code generation
  - computational logic
  - atomic function
  - SCI

grants:
  - 2024YFF0619303
---

{{site.data.ui-text[page.lang].abstract}}
====

自动化规则检查（即：智能审图）旨在通过计算机可处理规则实现设计审查自动化，相关研究已开展多年。现有规则解析方法难以表达隐含的复杂计算逻辑，且复杂逻辑表示与规则解析结果的融合不足。本文提出一种面向自动化设计审查的图结构知识规则表示方法，其图结构表示过程主要分为两步：首先通过语义映射将规则表示为三类图分支的语义组合；其次通过基元函数映射，从可计算逻辑层面为图添加基元函数节点，形成完整的知识图谱表示。本文进一步给出了从知识图谱结构自动生成规则推理程序代码的方法，可结合基元函数库实现自动化规则审查。该方法在可解释性与直观易懂方面表现出显著优势，为全自动规则检查系统研发提供了新思路。

Automated rule checking aims to automate design checking via computer-processible rules and has been extensively studied for years. Existing methods for rule interpretation are often limited in their ability to represent implicit complex computational logic, and the integration between complex logic representation methods and rule interpretation outcomes remains insufficient. In this paper, we propose a graph-based method for representing knowledge rules for automated design checking. The graph representing procedure consists of two main steps. Firstly, semantic mapping is employed, whereby the rules are represented as a semantic combination of three corresponding graph branches. Secondly, atomic function mapping is utilized, which adds atomic function nodes to the graph from the level of computable logic to form a complete graph representation, thereby forming a complete graph representation. We then provide a method for automatically generating programming code from the graphs, which, combined with the development of atomic functions, can be used for checking. This approach demonstrates considerable potential in terms of its interpretability and comprehensibility, and it provides novel ideas for the development of fully automated rule checking systems.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2026-02-21-graph-based-rule-representation-for-automated-design-checking.pdf)

The authors are grateful for the financial support received from the National Key Research and Development Program of China (No. 2023YFC3804600) and National Natural Science Foundation of China (No. 52378306) .