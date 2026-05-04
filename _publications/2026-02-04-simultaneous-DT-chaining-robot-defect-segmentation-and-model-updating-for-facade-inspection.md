---
title: "Simultaneous Digital Twin: Chaining Climbing-Robot, Defect Segmentation, and Model Updating for Building Facade Inspection"
lang: zh
ref: publications/2026-02-04-simultaneous-DT-chaining-robot-defect-segmentation-and-model-updating-for-facade-inspection
collection: publications
permalink: /publications/2026-02-04-simultaneous-DT-chaining-robot-defect-segmentation-and-model-updating-for-facade-inspection
excerpt: '论文提出了一种面向建筑外墙检测的实时数字孪生框架，实现了爬壁机器人、缺陷分割算法与数字孪生平台的端到端集成，实现外墙缺陷的秒级识别、更新与可视化'
date: 2026-02-04
venue: 'Buildings'
doi: '10.3390/buildings16030646'
paperurl: 'http://doi.org/10.3390/buildings16030646'
citation: 'Song, C.*, Lu, C., Shi, Y., He, A., Lin, J.R.*, Ma, Z. (2026). Simultaneous Digital Twin: Chaining Climbing-Robot, Defect Segmentation, and Model Updating for Building Facade Inspection. <i>Buildings</i>, 16(3), 646. doi: 10.3390/buildings16030646'

comment: true
category: journal

tags: 
  - wall-climbing robot
  - facade inspection
  - defect segmentation
  - digital twin
  - robotics
  - CV
  - computer vision
  - SCI

grants:
  - 2024YFF0619303
---

{{site.data.ui-text[page.lang].abstract}}
====

建筑外立面老化加速给城市带来重大安全隐患，亟需先进的自动化检测方案。计算机视觉（CV）与深度学习（DL）技术虽在缺陷分析中展现潜力，但在实现适配机器人部署的实时、定量、通用化损伤评估方面仍存关键短板。现有方法往往缺乏精准的指标量化能力，难以适配多样的材料外观，且现场处理的计算成本较高。为此，本文提出一套集成爬壁机器人、视觉实时分析系统与数字孪生管理平台的全自动端到端检测框架。本文核心贡献有三：（1）设计新型全集成机器人框架，实现自主导航、多传感器数据采集与实时分析；（2）构建轻量型、融合合成数据增强的深度学习模型，完成缺陷实时分割与指标量化，模型分割平均精度（mAP）达 0.775，缺陷长度平均误差 1.140 cm、中心位置平均误差 0.826 cm；（3）搭建云端数字孪生平台，支持缺陷定量可视化、时空溯源与数据驱动的项目管理，现场检测的响应延迟仅为 2.8~4.8 s。经实验室测试与实际建筑工程验证，该框架相较传统方法，在检测效率、定量精度与决策支持能力上均实现显著提升。

The rapid deterioration of building facades presents substantial safety hazards in urban environments, necessitating advanced, automated inspection solutions. While computer vision (CV) and deep learning (DL) techniques have shown promise for defect analysis, critical gaps remain in achieving real-time, quantitative, and generalizable damage assessment suitable for robotic deployment. Current methods often lack precise metric quantification, struggle with diverse material appearances, and are computationally intensive for on-site processing. To address these limitations, this paper introduces a fully automated, end-to-end inspection framework integrating a wall-climbing robot, a real-time vision-based analysis system, and a digital twin management platform. The primary contributions are threefold: (1) a novel, fully integrated robotic framework for autonomous navigation, multi-sensor data collection, and real-time analysis; (2) a lightweight, synthetic data-augmented DL model for real-time defect segmentation and metric quantification, achieving a mean Average Precision (mAP) of 0.775 for segmentation, an average defect length error of 1.140 cm, and an average center position error of 0.826 cm; (3) a cloud-based digital twin platform enabling quantitative defect visualization, spatiotemporal traceability, and data-driven project management, with the on-site inspection cycle demonstrating a responsive latency of 2.8–4.8 s. Validated through laboratory tests and real building projects, the framework demonstrates significant improvements in inspection efficiency, quantitative accuracy, and decision support over conventional methods.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2026-02-04-simultaneous-DT-chaining-robot-defect-segmentation-and-model-updating-for-facade-inspection.pdf)

This research was funded by National Key Research and Development Program of China, grant number 2024YFF0619303.