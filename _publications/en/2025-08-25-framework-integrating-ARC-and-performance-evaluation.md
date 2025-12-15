---
title: "Integrated Framework for Compliance Checking and Performance Evaluation in Building Design"
lang: en
ref: publications/2025-08-25-framework-integrating-ARC-and-performance-evaluation
collection: publications
permalink: /en/publications/2025-08-25-framework-integrating-ARC-and-performance-evaluation
excerpt: 'This study proposes an integrated framework combining NLP-AutoChecking, DiffEvac, and BIM design software, which enables rapid design iterations via a check-simulate-modify cycle, significantly improving deisng quality with broad practical potential'
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

Compliance checking and performance evaluation are crucial components of the iterative design and review process. However, traditional manual reviews and refined simulations are often subjective, time-consuming, and require a large number of input parameters. Therefore, automated rule checking (ARC) and performance simulation based on surrogate models have gained increasing attention. Despite this, most existing research focuses on one aspect or the other, without effectively integrating both, leading to gaps in reliability and efficiency when applied in practice. Therefore, this study proposes an integrated framework that combines automated compliance checking and efficient performance evaluation based on surrogate models, enabling rapid design review iterations. The framework comprises three interconnected modules: the NLP-AutoChecking module for rule checking based on IFC (Industry Foundation Classes) and semantic alignment; the DiffEvac module for evacuation performance simulation based on diffusion models; and a BIM design software module that connects both through a unified data interaction approach to modify design. Specifically, the BIM design can be converted into IFC format for rule checking to identify non-compliant elements and specify the violated regulations. Designers can then modify the design within the BIM software accordingly. It is important to note that multiple solutions may meet regulatory requirements, but not all are scientifically or practically optimal, as some may compromise safety or increase costs. Therefore, the modified BIM designs are exported as floor plans, cleaned and annotated, and then fed into the surrogate model for performance simulation, which evaluates and selects the optimal solution from the available options. This iterative cycle of compliance checking, simulation, and design modification continues until the design meets all regulatory standards and achieves optimal performance. Case studies demonstrate that this framework enables quick iterations and adjustments throughout both the design and review stages, significantly improving design quality and offering strong potential for widespread practical adoption.

![graphical abstract](/images/2025-08-25-framework-integrating-ARC-and-performance-evaluation-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-08-25-framework-integrating-ARC-and-performance-evaluation.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (Nos. 52238011, 52378306)