---
title: "Intelligent Monitoring System for Deep Foundation Pit Based on Digital Twin"
lang: zh
ref: publications/2025-01-25-DT-based-monitoring-of-deep-foundation-pit
collection: publications
permalink: /publications/2025-01-25-DT-based-monitoring-of-deep-foundation-pit
excerpt: '本研究提出了基坑数字孪生监测方法、模型及系统，并通过典型工程应用验证了所提出方法的有效性'
date: 2025-01-25
venue: 'Buildings'
doi: '10.3390/buildings15030366'
paperurl: 'http://doi.org/10.3390/buildings15030366'
citation: 'Pan, P., Sun, S.H., Feng, J.X., Wen, J.T.*, Lin, J.R., Wang, H.S. (2025). Intelligent Monitoring System for Deep Foundation Pit Based on Digital Twin. <i>Buildings</i>, 15(3), 366. doi: 10.3390/buildings15030366'

comment: true
category: journal

tags: 
  - digital twin
  - intelligent monitoring
  - deep foundation pit
  - data integration
  - inverse analysis
  - SCI

grants:
  - 2023YFC3805800
---

{{site.data.ui-text[page.lang].abstract}}
====

地下空间开发使基坑工程的深度、规模和复杂程度显著增加，但既有基坑监测系统缺乏必要的力学模型支撑，无法有效预测和控制施工风险，且基坑模型无法根据现场观测数据进行更新，导致预测不准确。本研究提出了一种基坑数字孪生（DT）建模框架，用于模拟、预测和控制整个开挖过程的风险。随后，基于该框架，通过建模和更新算法建立了基坑数字孪生模型（DTFPM）。本研究通过总结并确定了基坑建模的关键参数，并开发了基于ABAQUS（v2020）的参数化建模算法，在秒级内驱动基坑开挖过程机理建模。此外，采用基于遗传算法（GA）和实时观测变形的反分析优化算法来更新土体的弹性模量，该算法支持并行计算、可在10代内收敛。通过反分析，可将模型的预测误差降低到10％以内。最后，应用DTFPM建立了基坑智能监测系统，重点研究了基于当前施工阶段监测变形和更新模型的实时性和预测性预警。本研究通过北京某项目案例分析，验证了系统的有效性，展示了所提方法的实际应用。结果表明，DTFPM能够准确模拟基坑变形行为，系统能够提供更及时、更准确的安全预警。所提方法在理论和实践上都对未来基坑智能化建设具有潜在的贡献。

Underground space development has significantly increased the depth, scale, and complexity of foundation pit engineering. However, monitoring systems lack mechanical analysis models and fail to predict and control construction risks. Additionally, the foundation pit model could not be updated based on on-site observed data, leading to inaccurate predictions. This study proposes a DT modeling framework for foundation pits, which is used to simulate, predict, and control the risks associated with the entire excavation process. Consequently, based on the DT modeling framework, a DT foundation pit model (DTFPM) was established using modeling and updating algorithms. This study summarizes and identifies the key modeling parameters of foundation pits. A parametric modeling algorithm based on ABAQUS (v2020) was developed to drive the excavation pit modeling process within seconds. Furthermore, an inverse analysis optimization algorithm based on genetic algorithms (GA) and real-time observed deformation was employed to update the elastic modulus of the soil. The algorithm supports parallel computing and can converge within 10 generations. The prediction error of the model after inverse analysis can be reduced to within 10%. Finally, the authors applied DTFPM to establish an intelligent monitoring system. The focus is on real-time and predictive warnings based on the monitoring deformation of the current construction step and the updated model. This study analyzes a Beijing project case to verify the effectiveness of the system, demonstrating the practical application of the proposed method. The results showed that the DTFPM could accurately simulate the deformation behavior of the foundation pit. The system could provide more timely and accurate safety warnings. The proposed method can potentially contribute to the intelligent construction of foundation pits in the future, both theoretically and practically.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-01-25-DT-based-monitoring-of-deep-foundation-pit.pdf)

This research was supported by the National Key R&D Program of China (Project No. 2023YFC3805800). This research was also supported by the project “Constructing a theoretical system for sustainable development strategy of construction enterprises with digital platforms as the core”, which was funded by CHINA CONSTRUCTION THIRD ENGINEERING BUREAU BEIJING CO., LTD. The authors also acknowledge the support from Tsinghua University-China Construction Third Engineering Bureau Group Co., Ltd. Joint Research Center for New Technology in Civil Engineering.