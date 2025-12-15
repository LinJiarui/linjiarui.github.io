---
title: "A Multi-object Detection Method for Building Fire Warnings through Artificial Intelligence Generated Content"
lang: en
ref: publications/2025-06-06-multi-object-detection-for-building-fire-warnings-through-genAI
collection: publications
permalink: /en/publications/2025-06-06-multi-object-detection-for-building-fire-warnings-through-genAI
excerpt: 'This paper proposes an AIGC-based multi-object detection method for building fires, which achieves 95.7% detection accuracy for flames and smoke, detects fires within 2 seconds (6.5× faster than traditional alarms), and provides timely warnings for evacuation and rescue.'
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

Timely fire warnings are crucial for minimizing casualties during building fires. In this paper, a multi-object detection method through artificial intelligence generated content (AIGC) is proposed to improve building fire warning capability. First, an AIGC workflow of dataset construction on building fire images is designed, to overcome the limitation due to a serious lack of real building fire images. Validation experiments demonstrate that the detection accuracy of the model trained on the AIGC dataset is only 1.6% lower than that of the model trained on the real image dataset. Subsequently, a multi-object detection model is developed to enhance its feature capture capability, by incorporating the MLCA mechanism into its backbone and replacing the feature fusion layer in its neck. The developed model can detect the flame and smoke of building fires with an accuracy of 95.7%. Finally, the case study involving three real fire incidents demonstrates that the proposed method can detect fires within 2s since the fire starting, which achieves an improvement of at least 6.5 times in the fire warning efficiency compared to the traditional fire alarms. Therefore, the proposed method can deliver timely fire warnings for the evacuation and rescue efforts during building fires.

![graphical abstract](/images/2025-06-06-multi-object-detection-for-building-fire-warnings-through-genAI-ga.webp)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-06-06-multi-object-detection-for-building-fire-warnings-through-genAI.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (52238011, 52208456), and Shenzhen Major Science and Technology Program (KJZD20230923114310021).