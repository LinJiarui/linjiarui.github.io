---
title: "Linking Data Model and Formula to Automate KPI Calculation for Building Performance Benchmarking"
lang: zh
ref: publications/2021-02-17-link-data-model-and-formula-to-automate-performance-benchmarking
collection: publications
permalink: /publications/2021-02-17-link-data-model-and-formula-to-automate-performance-benchmarking
excerpt: '针对建筑能效对比，提出一种链接数据模型及KPI公式的自动计算方法，可基于不同粒度的数据对比同类建筑的能效'
date: 2021-02-17
venue: 'Energy Reports'
doi: '10.​1016/​j.​egyr.​2021.​02.​044'
paperurl: 'http://doi.org/10.​1016/​j.​egyr.​2021.​02.​044'
citation: 'Zhang, Y.Y., Hu, Z.Z., Lin, J.R.*, Zhang J.P. (2021). Linking Data Model and Formula to Automate KPI Calculation for Building Performance Benchmarking. <i>Energy Reports</i>, 7, 1326-1337. doi: 10.​1016/​j.​egyr.​2021.​02.​044'

comment: true
category: journal

tags: 
  - 
  - building performance
  - data model
  - linked data
  - sensor network
  - formula
  - KP1
  - semantic web
  - knowledge graph
  - SCI

grants:
  - 2017YFC0704200
  - 51908323
  - 2019Z02UOT
---


{{site.data.ui-text[page.lang].abstract}}
====

建筑是全球一次能源的主要消耗者之一，对其能耗的分析、管理离不开大量的监测数据。关键绩效指标（KPI）可以克服数据异构带来的挑战，实现不同建筑物的能效对比。但是，当前建筑能耗监测系统和数据仍是典型的“数据孤岛”，相互割裂，且数据及KPI计算公式之间存在明显的语义鸿沟。针对该问题，本研究提出一种基于本体的建筑能耗KPI自动计算方法。该方法首先实现了BIM模型建筑信息、传感网络感知的能耗及环境信息的语义链接，实现了建筑运维阶段静态、动态数据的集成；同时，基于本体建立了KPI公式各参数与数据模型的语义映射关系，从而可直接基于SPARQL实现数据查询和自动计算。案例应用验证表明，本文方法可自动根据所选择的KPI进行数据查询提取并计算特定空间及时间内的能效指标，并支持基于不同粒度的数据计算同一KPI，从而可基于不同LOD的数据实现同类建筑物的能效对比。有关研究可为管理者发现建筑能效表现的差异，优化建筑用能效率提供决策依据。研究同时也为数据模型及其计算模型（如KPI公式）的语义链接与映射提供了一种新方法，可支撑其他有关多源异构数据融合、计算的研究。

![Graph Abstract]({{ site.baseurl }}/images/2021-02-17-link-data-model-and-formula-to-automate-performance-benchmarking.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2021-02-17-link-data-model-and-formula-to-automate-performance-benchmarking.pdf)

This work was funded by the National Key R&D Program of China (Grant No. 2017YFC0704200). Dr. Lin was also supported by the National Science Foundation of China (No. 51908323) and the Tsinghua University Initiative Scientific Research Program (No. 2019Z02UOT).
This work emerged from the IBPSA Project 1, an international project conducted under the umbrella of the International Building Performance Simulation Association (IBPSA). Project 1 will develop and demonstrate a BIM/GIS and Modelica Framework for building and community energy system design and operation.



