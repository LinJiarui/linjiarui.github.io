---
title: "An Adaptive Pedestrian Flow Prediction Model Based on First-Order Differential Error Adjustment and Hidden Markov Model"
lang: en
ref: publications/2025-03-12-adaptive-pedestrian-flow-prediction-via-FoD-HMM-enhanced-LSTM
collection: publications
permalink: /en/publications/2025-03-12-adaptive-pedestrian-flow-prediction-via-FoD-HMM-enhanced-LSTM
excerpt: 'This paper proposes an integrated pedestrian flow prediction framework, employing a Long Short-Term Memory (LSTM) network to capture complex temporal dependencies in pedestrian movement patterns. This model effectively mitigates data inconsistency and the challenges associated with a high proportion of zero values.'
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

Pedestrian flow prediction is a quintessential time series forecasting problem with widespread applications in domains such as indoor navigation and emergency response. However, existing prediction models exhibit sensitivity to anomalous data and face significant challenges in adapting to dynamic and evolving environments. To address these challenges, this paper proposes an integrated pedestrian flow prediction framework. The core architecture employs a Long Short-Term Memory (LSTM) network to capture complex temporal dependencies in pedestrian movement patterns. To improve prediction accuracy, we introduce a two-stage error compensation mechanism. A first-order differential (FoD) module continuously adjusts prediction deviations by analyzing real-time error gradients, while a Hidden Markov Model (HMM)-based adaptive controller dynamically optimizes model parameters in response to changing crowd dynamics. This model effectively mitigates data inconsistency and the challenges associated with a high proportion of zero values. It is designed to provide adaptive feedback and adjust predictions in response to real-time variations in pedestrian flow. For the adjusted time node prediction sequence, accuracy improved by 2.45%, while F-crowded made a significant breakthrough, increasing from 0 to 60.29%. For the full prediction sequence, accuracy increased by 1.9%, from 76.14% to 77.87%, and F-crowded increased by 1.7%, from 85.18% to 86.62%. These results highlight the effectiveness of the HMM-FoD-LSTM model in dealing with data variability in dynamic environments.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-03-12-adaptive-pedestrian-flow-prediction-via-FoD-HMM-enhanced-LSTM.pdf)

The authors would like to acknowledge the support of the National Science Foundation of China (52308314), and the support of the Guangdong Basic and Applied Basic Research Foundation (2023A1515030169).