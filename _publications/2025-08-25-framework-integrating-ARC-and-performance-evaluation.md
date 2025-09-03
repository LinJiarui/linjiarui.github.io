---
title: "Integrated Framework for Compliance Checking and Performance Evaluation in Building Design"
lang: zh
ref: publications/2025-08-25-framework-integrating-ARC-and-performance-evaluation
collection: publications
permalink: /publications/2025-08-25-framework-integrating-ARC-and-performance-evaluation
excerpt: '提出一种集成自动化合规性检查、疏散性能模拟及 BIM 设计软件模块的框架，实现了合规检查、模拟分析、设计修改全流程的高效迭代循环，案例表明其可显著提升设计质量且具有广泛应用潜力'
date: 2025-08-25
venue: 'Proceedings of the 6th ICCBEI'
doi: '10.29007/5797'
paperurl: 'http://doi.org/10.29007/5797'
citation: 'Han, J., Zheng, Z., Xu, Z., Lu, X.Z., Lin, J.R.* (2025). Integrated Framework for Compliance Checking and Performance Evaluation in Building Design. <i>Proceedings of The Sixth International Conference on Civil and Building Engineering Informatics</i>, 22, 804-816. Hong Kong. doi: 10.29007/5797'

comment: true
category: conference

tags: 
  - BIM
  - ACC
  - ARC
  - evacuation
  - building design
  - performance
  - simulation
  - generative design

grants:
  - 52238011
  - 52378306
---

{{site.data.ui-text[page.lang].abstract}}
====

合规性检查与性能评估是迭代式设计及审查流程的核心组成部分。然而，传统的人工审查与精细化模拟往往存在主观性强、耗时费力的问题，且需输入大量参数。因此，自动化规则检查（ARC）与基于代理模型的性能模拟受到了日益广泛的关注。尽管如此，现有研究大多侧重于其中单一领域，未能实现两者的有效融合，导致其在实际应用中存在可靠性与效率不足的问题。为此，本研究提出一种集成框架，将自动化合规性检查与基于代理模型的高效性能评估相结合，以实现设计审查的快速迭代。该框架由三个相互关联的模块构成：基于工业基础类（IFC）与语义对齐的规则检查模块（NLP-AutoChecking）、基于扩散模型的疏散性能模拟模块（DiffEvac），以及通过统一数据交互方式连接上述两个模块并实现设计修改的 BIM 设计软件模块。具体而言，可将 BIM 设计转换为 IFC 格式进行规则检查，识别不合规元素并明确其违反的规范要求；设计人员随后可在 BIM 软件中据此调整设计方案。需注意的是，多种方案可能均符合规范要求，但并非所有方案在科学或实际应用层面均为最优 —— 部分方案可能会牺牲安全性或增加成本。因此，经修改的 BIM 设计需导出为平面图，在经过数据清洗与标注后输入至代理模型进行性能模拟，进而从备选方案中评估并筛选出最优解。这一 "合规性检查 - 模拟 - 设计修改" 的迭代循环将持续进行，直至设计方案同时满足所有规范标准并实现性能最优。案例研究表明，该框架可在设计与审查全流程中实现快速迭代与调整，显著提升设计质量，具有广泛的实际应用潜力。

Compliance checking and performance evaluation are crucial components of the iterative design and review process. However, traditional manual reviews and refined simulations are often subjective, time-consuming, and require a large number of input parameters. Therefore, automated rule checking (ARC) and performance simulation based on surrogate models have gained increasing attention. Despite this, most existing research focuses on one aspect or the other, without effectively integrating both, leading to gaps in reliability and efficiency when applied in practice. Therefore, this study proposes an integrated framework that combines automated compliance checking and efficient performance evaluation based on surrogate models, enabling rapid design review iterations. The framework comprises three interconnected modules: the NLP-AutoChecking module for rule checking based on IFC (Industry Foundation Classes) and semantic alignment; the DiffEvac module for evacuation performance simulation based on diffusion models; and a BIM design software module that connects both through a unified data interaction approach to modify design. Specifically, the BIM design can be converted into IFC format for rule checking to identify non-compliant elements and specify the violated regulations. Designers can then modify the design within the BIM software accordingly. It is important to note that multiple solutions may meet regulatory requirements, but not all are scientifically or practically optimal, as some may compromise safety or increase costs. Therefore, the modified BIM designs are exported as floor plans, cleaned and annotated, and then fed into the surrogate model for performance simulation, which evaluates and selects the optimal solution from the available options. This iterative cycle of compliance checking, simulation, and design modification continues until the design meets all regulatory standards and achieves optimal performance. Case studies demonstrate that this framework enables quick iterations and adjustments throughout both the design and review stages, significantly improving design quality and offering strong potential for widespread practical adoption.

![graphical abstract](/images/2025-08-25-framework-integrating-ARC-and-performance-evaluation-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-08-25-framework-integrating-ARC-and-performance-evaluation.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (Nos. 52238011, 52378306)