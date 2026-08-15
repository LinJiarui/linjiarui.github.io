---
title: "Precise Longitudinal Crack Detection via Continuous Texture Reconstruction and Deep Segmentation"
lang: en
ref: publications/2026-06-15-precise-longitudinal-crack-detection-via-continuous-texture-reconstruction-and-deep-segmentation
collection: publications
permalink: /en/publications/2026-06-15-precise-longitudinal-crack-detection-via-continuous-texture-reconstruction-and-deep-segmentation
excerpt: 'This paper introduces a dual-channel crack detection model that integrates continuous pavement texture reconstruction with deep segmentation and high-precision boundary refinement algorithms, enabling on-site implementation and accuracy enhancement for longitudinal crack detection'
date: 2026-06-15
venue: 'Advanced Engineering Informatics'
doi: '10.1016/j.aei.2026.104919'
paperurl: 'http://doi.org/10.1016/j.aei.2026.104919'
citation: 'An, P., Ren, Z.R., Liu, L.X., Lin, J.R., Yu, Y., Guo, Y.T., Hou, C., Hu, Z.Z.* (2026). Precise Longitudinal Crack Detection via Continuous Texture Reconstruction and Deep Segmentation. <i>Advanced Engineering Informatics</i>, 76, 104919. doi: 10.1016/j.aei.2026.104919'

comment: true
category: journal

tags: 
  - crack detection
  - texture
  - segmentation
  - road
  - infrastructure
  - localization
  - image segmentation
  - maintenance
  - pavement
  - inspection
  - SCI

grants:
  - 2022YFC3801100
  - SGDX20240115110503006
---

{{site.data.ui-text[page.lang].abstract}}
====

Pavement cracks are a major form of road infrastructure degradation, necessitating efficient and accurate detection for timely maintenance. Existing inspection methods rely either on labor-intensive manual surveys or automated systems constrained by high hardware costs and GPS dependency, limiting their flexibility for continuous surface assessment. This paper introduces a dual-channel crack detection model that integrates continuous pavement texture reconstruction with deep segmentation and high-precision boundary refinement algorithms, enabling on-site implementation and accuracy enhancement for longitudinal crack detection. A feature-based image stitching algorithm is developed to reconstruct continuous pavement textures from high-resolution images, enabling GPS-free crack localization. The proposed method further combines the YOLOv8-seg model with adaptive morphological operations to achieve pixel-level crack reconstruction. Comparative experiments reveal that the hybrid approach achieves superior segmentation performance with finer boundary delineation and improved branch recovery compared to the baseline model. The paper provides a practical solution for automated inspection and high-fidelity reconstruction of longitudinal cracks, effectively supporting pavement maintenance planning.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2026-06-15-precise-longitudinal-crack-detection-via-continuous-texture-reconstruction-and-deep-segmentation.pdf)

elopment Program of China (grant number 2022YFC3801100); and Shenzhen Science and Technology Program (grant number SGDX 20240115110503006).