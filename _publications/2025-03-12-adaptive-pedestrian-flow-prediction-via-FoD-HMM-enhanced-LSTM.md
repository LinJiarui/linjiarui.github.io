---
title: "An Adaptive Pedestrian Flow Prediction Model Based on First-Order Differential Error Adjustment and Hidden Markov Model"
lang: zh
ref: publications/2025-03-12-adaptive-pedestrian-flow-prediction-via-FoD-HMM-enhanced-LSTM
collection: publications
permalink: /publications/2025-03-12-adaptive-pedestrian-flow-prediction-via-FoD-HMM-enhanced-LSTM
excerpt: '本研究针对人流量预测数据变异性大、质量不稳定带来的预测失真问题，提出了一种具备两阶段误差补偿机制的LSTM人流预测模型，通过集成一阶微分级马尔科夫模型实现了预测精度与大幅提升'
date: 2025-03-12
venue: 'Buildings'
doi: '10.3390/buildings15060902'
paperurl: 'http://doi.org/10.3390/buildings15060902'
citation: 'Zhang, H., Deng, J., Xu Y., Deng, Y.*, Lin, J.R. (2025). An Adaptive Pedestrian Flow Prediction Model Based on First-Order Differential Error Adjustment and Hidden Markov Model. <i>Buildings</i>, 15(6), 902. doi: 10.3390/buildings15060902'

comment: true
category: journal

tags: 
  - digital twin
  - LSTM
  - adaptive prediction
  - hidden markov model
  - pedestrian flow
  - video surveillance
  - SCI

grants:
  - 52308314
  - 2023A1515030169
---

{{site.data.ui-text[page.lang].abstract}}
====

行人流量预测是一个典型的时间序列预测问题，广泛应用于室内导航和应急响应等领域。然而，现有的预测模型对异常数据很敏感，在适应动态和不断变化的环境方面面临重大挑战。为了应对这些挑战，本文提出了一个综合的行人流量预测框架。核心架构采用长短期记忆 (LSTM) 网络来捕捉行人运动模式中复杂的时间依赖性。为了提高预测精度，我们引入了一种两阶段误差补偿机制，基于一阶微分 (FoD) 模块分析实时误差梯度并不断调整预测偏差，同时利用隐马尔可夫模型 (HMM) 的自适应控制器根据不断变化的人群动态动态优化模型参数。该模型有效地缓解了数据不一致和与高比例零值相关的挑战。它旨在提供自适应反馈并根据行人流量的实时变化调整预测。对于调整后的时间节点预测序列准确率提升了2.45%，F-crowded指标则实现了从0到60.29%的突破。对于全预测序列准确率提升了1.9%，从76.14%提升到了77.87%，F-crowded从85.18%提升到了86.62%。这些结果凸显了HMM-FoD-LSTM模型在处理动态环境中数据变异性方面的有效性。

Pedestrian flow prediction is a quintessential time series forecasting problem with widespread applications in domains such as indoor navigation and emergency response. However, existing prediction models exhibit sensitivity to anomalous data and face significant challenges in adapting to dynamic and evolving environments. To address these challenges, this paper proposes an integrated pedestrian flow prediction framework. The core architecture employs a Long Short-Term Memory (LSTM) network to capture complex temporal dependencies in pedestrian movement patterns. To improve prediction accuracy, we introduce a two-stage error compensation mechanism. A first-order differential (FoD) module continuously adjusts prediction deviations by analyzing real-time error gradients, while a Hidden Markov Model (HMM)-based adaptive controller dynamically optimizes model parameters in response to changing crowd dynamics. This model effectively mitigates data inconsistency and the challenges associated with a high proportion of zero values. It is designed to provide adaptive feedback and adjust predictions in response to real-time variations in pedestrian flow. For the adjusted time node prediction sequence, accuracy improved by 2.45%, while F-crowded made a significant breakthrough, increasing from 0 to 60.29%. For the full prediction sequence, accuracy increased by 1.9%, from 76.14% to 77.87%, and F-crowded increased by 1.7%, from 85.18% to 86.62%. These results highlight the effectiveness of the HMM-FoD-LSTM model in dealing with data variability in dynamic environments.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-03-12-adaptive-pedestrian-flow-prediction-via-FoD-HMM-enhanced-LSTM.pdf)

The authors would like to acknowledge the support of the National Science Foundation of China (52308314), and the support of the Guangdong Basic and Applied Basic Research Foundation (2023A1515030169).