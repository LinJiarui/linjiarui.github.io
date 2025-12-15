---
title: "A Multi-object Detection Method for Building Fire Warnings through Artificial Intelligence Generated Content"
lang: zh
ref: publications/2025-06-06-multi-object-detection-for-building-fire-warnings-through-genAI
collection: publications
permalink: /publications/2025-06-06-multi-object-detection-for-building-fire-warnings-through-genAI
excerpt: '本研究提出基于 AIGC 的建筑火灾多目标检测方法，通过构建 AIGC 数据集解决真实样本匮乏问题，改进模型后实现 95.7% 的火焰与烟雾检测精度，能在火灾发生 2 秒内完成预警，效率较传统报警器提升 6.5 倍以上，为人员疏散和救援提供及时预警支持。'
date: 2025-06-06
venue: 'Scientific Reports'
doi: '10.1038/s41598-025-02865-4'
paperurl: 'http://doi.org/10.1038/s41598-025-02865-4'
citation: 'Fu, J., Xu, Z.*, Yue, Q., Lin, J., Zhang, N., Zhao, Y., Gu, D. (2025). A Multi-object Detection Method for Building Fire Warnings through Artificial Intelligence Generated Content. <i>Scientific Reports</i>, 15, 18434. doi: 10.1038/s41598-025-02865-4'

comment: true
category: journal

tags: 
  - fire warning
  - fire safety
  - object detection
  - computer vision
  - dataset
  - synthetic images
  - AIGC
  - genAI
  - fire alarm
  - evacuation
  - SCI

grants:
  - 52238011
  - 52208456
  - KJZD20230923114310021
---

{{site.data.ui-text[page.lang].abstract}}
====

及时的火灾预警对于最大限度减少建筑火灾中的伤亡至关重要。本文提出一种基于人工智能生成内容（AIGC）的多目标检测方法，以提升建筑火灾预警能力。首先，设计了针对建筑火灾图像的 AIGC 数据集构建工作流程，有效克服了真实建筑火灾图像严重匮乏的限制。验证实验表明，基于 AIGC 数据集训练的模型检测精度仅比真实图像数据集训练的模型低 1.6%。随后，通过在主干网络中融入 MLCA 机制并替换颈部的特征融合层，开发了增强特征捕捉能力的多目标检测模型，该模型对建筑火灾火焰和烟雾的检测精度达到 95.7%。最后，针对三起真实火灾事件的案例研究表明，所提方法可在火灾发生后 2 秒内完成火情检测，相比传统火灾报警器，预警效率提升至少 6.5 倍。因此，该方法能够为建筑火灾中的人员疏散和救援工作提供及时的火灾预警。

Timely fire warnings are crucial for minimizing casualties during building fires. In this paper, a multi-object detection method through artificial intelligence generated content (AIGC) is proposed to improve building fire warning capability. First, an AIGC workflow of dataset construction on building fire images is designed, to overcome the limitation due to a serious lack of real building fire images. Validation experiments demonstrate that the detection accuracy of the model trained on the AIGC dataset is only 1.6% lower than that of the model trained on the real image dataset. Subsequently, a multi-object detection model is developed to enhance its feature capture capability, by incorporating the MLCA mechanism into its backbone and replacing the feature fusion layer in its neck. The developed model can detect the flame and smoke of building fires with an accuracy of 95.7%. Finally, the case study involving three real fire incidents demonstrates that the proposed method can detect fires within 2s since the fire starting, which achieves an improvement of at least 6.5 times in the fire warning efficiency compared to the traditional fire alarms. Therefore, the proposed method can deliver timely fire warnings for the evacuation and rescue efforts during building fires.

![graphical abstract](/images/2025-06-06-multi-object-detection-for-building-fire-warnings-through-genAI-ga.webp)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-06-06-multi-object-detection-for-building-fire-warnings-through-genAI.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (52238011, 52208456), and Shenzhen Major Science and Technology Program (KJZD20230923114310021).