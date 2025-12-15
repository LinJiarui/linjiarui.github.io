---
title: "Generative Model-Based Building Evacuation Simulation for Safety Design"
lang: en
ref: publications/2025-11-15-GAN-based-building-evacuation-simulation-for-safety-design
collection: publications
permalink: /en/publications/2025-11-15-GAN-based-building-evacuation-simulation-for-safety-design
excerpt: '
This study proposes DiffEvac for efficient evacuation simulation and enhanced safety design, achieving up to a 37.6% improvement in SSIM,and delivering results 16 times faster'
date: 2025-11-15
venue: 'Journal of Building Engineering'
doi: '10.1016/j.jobe.2025.114644'
paperurl: 'http://doi.org/10.1016/j.jobe.2025.114644'
citation: 'Han, J., Zheng, Z., Gu, Y., Lin, J.R.*, Lu, X.Z. (2025). Generative Model-Based Building Evacuation Simulation for Safety Design. <i>Journal of Building Engineering</i>, 116, 114644. doi: 10.1016/j.jobe.2025.114644'

comment: true
category: journal

tags: 
  - GAN
  - evacuation
  - surrogate model
  - generative design
  - safety design
  - intelligent design
  - SCI

grants:
  - 52238011
  - 52378306
  
---


{{site.data.ui-text[page.lang].abstract}}
====


Evacuation simulation is essential for building safety design, ensuring properly planned evacuation routes. However, traditional evacuation simulation relies heavily on refined modeling with extensive parameters, making it challenging to adopt such methods in a rapid design iteration process in the early stages. Thus, this study proposes DiffEvac, a novel method to learn building evacuation patterns based on Generative Models (GMs), for efficient evacuation simulation and enhanced safety design. Initially, a dataset of 399 diverse functional layouts and corresponding evacuation heatmaps of buildings was established. Then, a decoupled feature representation is proposed to embed physical features like layouts and occupant density for GMs. Finally, a diffusion model based on image prompts is proposed to learn evacuation patterns from simulated evacuation heatmaps. Compared to existing research using Conditional GANs with RGB representation, DiffEvac achieves up to a 37.6 % improvement in SSIM, 142 % in PSNR, and delivers results 16 times faster—cutting simulation time to 2 min. Case studies further demonstrate that the proposed method not only significantly enhances the rapid design iteration and adjustment process with efficient evacuation simulation but also offers new insights and technical pathways for future safety optimization in intelligent building design. The research implication is that the approach lowers the modeling burden, enables large-scale what-if exploration, and facilitates coupling with multi-objective design tools.


![graphical abstract](/images/2025-11-15-GAN-based-building-evacuation-simulation-for-safety-design-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-11-15-GAN-based-building-evacuation-simulation-for-safety-design.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (Nos. 52238011, 52378306).