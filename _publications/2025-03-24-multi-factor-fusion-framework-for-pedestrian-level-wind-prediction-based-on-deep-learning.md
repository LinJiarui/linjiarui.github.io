---
title: "A Multi-Factor-Fusion Framework for Efficient Prediction of Pedestrian-level Wind Environment Based on Deep Learning"
lang: zh
ref: publications/2025-03-24-multi-factor-fusion-framework-for-pedestrian-level-wind-prediction-based-on-deep-learning
collection: publications
permalink: /publications/2025-03-24-multi-factor-fusion-framework-for-pedestrian-level-wind-prediction-based-on-deep-learning
excerpt: '论文提出了一种基于深度学习的多因素融合（MFF）框架，通过图卷积网络（GCN）和注意力长短期记忆网络（ALSTM）融合历史风速、障碍物分布和气象数据，端到端直接预测行人级风场，避免了传统 CFD 模拟的网格划分和迭代计算，效率提升显著。研究利用多尺度模拟数据（WRF+CFD）训练模型并校准预测结果，在案例中实现了10 分钟预测误差 3.52%、1 小时误差 10.23%，为城市风环境分析提供了高效解决方案。'
date: 2025-03-24
venue: 'IEEE Access'
doi: '10.1109/ACCESS.2025.3553490'
paperurl: 'http://doi.org/10.1109/ACCESS.2025.3553490'
citation: 'Hu, Z.Z.*, Min, Y.T., Leng, S., Li, S., Lin, J.R. (2025). A Multi-Factor-Fusion Framework for Efficient Prediction of Pedestrian-level Wind Environment Based on Deep Learning. <i>IEEE Access</i>, 13, 52912-52924. doi: 10.1109/ACCESS.2025.3553490'

comment: true
category: journal

tags: 
  - wind environment
  - deep learning
  - numerical simulation
  - green building
  - intelligent design
  - graph convolutional network
  - GCN
  - LSTM
  - SCI

grants:
  - 2022YFC3801100
  - 52378306
  - 2022B1515130006
---

{{site.data.ui-text[page.lang].abstract}}
====

高效准确地评估行人级风环境对于维护健康安全的城市居住环境至关重要。计算流体力学（CFD）和多尺度建模技术等数值模拟方法常用于风环境分析，但这些方法计算量大且耗时，尤其在处理复杂城市景观时效率低下。本研究提出了一种基于深度学习的新型多因素融合（MFF）框架，该框架集成图卷积网络（GCN）和长短时记忆网络（LSTM），通过提取和融合多维度影响因素，构建了可直接预测风场的端到端神经网络模型。通过避免网格划分和迭代计算的需求，该框架显著提升了风环境分析效率。此外，研究采用多尺度模拟数据对模型进行训练和预测结果修正，确保了预测结果的准确性。这种创新方法通过实现效率与精度的平衡，有望彻底革新行人级风环境预测技术。

Efficient and accurate assessment of the Pedestrian-Level Wind Environment is essential to maintain a healthy and safe urban living environment. Numerical simulations, such as computational fluid dynamics and multi-scale modeling techniques, are commonly used for wind environment analysis. However, they are computationally intensive and time-consuming, particularly when dealing with the complexities of urban landscapes. This study proposes a novel Multi-Factor-Fusion (MFF) framework that leverages deep learning techniques. This framework integrates Graph Convolutional Networks and Long Short-Term Memory networks to extract and fuse multiple factors and create an end-to-end neural network model capable of directly predicting wind fields. By avoiding the need for grid division and iterative calculations, the framework significantly enhances the efficiency of wind environment analysis. Furthermore, multi-scale simulation data is used to train the model and correct the predictive results, ensuring the accuracy of the final results. This innovative approach has the potential to revolutionize the Pedestrian-Level Wind Environment prediction by achieving a trade-off between efficiency and accuracy.

![graphical abstract](/images/2025-03-24-multi-factor-fusion-framework-for-pedestrian-level-wind-prediction-based-on-deep-learning-ga.jpg)

![graphical abstract](/images/2025-03-24-multi-factor-fusion-framework-for-pedestrian-level-wind-prediction-based-on-deep-learning.png)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-03-24-multi-factor-fusion-framework-for-pedestrian-level-wind-prediction-based-on-deep-learning.pdf)

This work was supported in part by the National Key Research and Development Program of China under Grant 2022YFC3801100, in part by the Natural Science Foundation of China under Grant 52378306, and in part by Guangdong Basic and Applied Basic Research Foundation under Grant 2022B1515130006.