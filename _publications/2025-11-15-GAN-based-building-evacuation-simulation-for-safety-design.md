---
title: "Generative Model-Based Building Evacuation Simulation for Safety Design"
lang: zh
ref: publications/2025-11-15-GAN-based-building-evacuation-simulation-for-safety-design
collection: publications
permalink: /publications/2025-11-15-GAN-based-building-evacuation-simulation-for-safety-design
excerpt: '
本研究提出 DiffEvac 方法，用于高效疏散模拟与安全设计优化，其结构相似性指数（SSIM）最高提升 37.6%，模拟速度加快 16 倍'
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

疏散模拟是建筑安全设计的关键，可保障疏散路线规划合理性。但传统疏散模拟依赖精细化建模与大量参数，难以适配早期快速设计迭代。为此，本研究提出基于生成模型（GMs）的 DiffEvac 方法，通过学习建筑疏散模式实现高效模拟，助力安全设计优化。首先，构建含 399 个多样功能布局及对应疏散热力图的数据集；其次，提出解耦特征表示方法，嵌入布局、人员密度等物理特征供生成模型使用；最后，设计基于图像提示词的扩散模型，从模拟疏散热力图中学习疏散模式。与采用 RGB 表示的条件生成对抗网络（Conditional GANs）相关研究相比，DiffEvac 的结构相似性指数（SSIM）最高提升 37.6%，峰值信噪比（PSNR）提升 142%，模拟速度加快 16 倍，耗时缩短至 2 分钟。案例研究表明，该方法通过高效疏散模拟显著助力快速设计迭代调整，为智能建筑设计的安全优化提供新思路与技术路径，其研究价值在于降低建模成本、支持大规模假设分析，并可与多目标设计工具耦合使用。

Evacuation simulation is essential for building safety design, ensuring properly planned evacuation routes. However, traditional evacuation simulation relies heavily on refined modeling with extensive parameters, making it challenging to adopt such methods in a rapid design iteration process in the early stages. Thus, this study proposes DiffEvac, a novel method to learn building evacuation patterns based on Generative Models (GMs), for efficient evacuation simulation and enhanced safety design. Initially, a dataset of 399 diverse functional layouts and corresponding evacuation heatmaps of buildings was established. Then, a decoupled feature representation is proposed to embed physical features like layouts and occupant density for GMs. Finally, a diffusion model based on image prompts is proposed to learn evacuation patterns from simulated evacuation heatmaps. Compared to existing research using Conditional GANs with RGB representation, DiffEvac achieves up to a 37.6 % improvement in SSIM, 142 % in PSNR, and delivers results 16 times faster—cutting simulation time to 2 min. Case studies further demonstrate that the proposed method not only significantly enhances the rapid design iteration and adjustment process with efficient evacuation simulation but also offers new insights and technical pathways for future safety optimization in intelligent building design. The research implication is that the approach lowers the modeling burden, enables large-scale what-if exploration, and facilitates coupling with multi-objective design tools.


![graphical abstract](/images/2025-11-15-GAN-based-building-evacuation-simulation-for-safety-design-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-11-15-GAN-based-building-evacuation-simulation-for-safety-design.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (Nos. 52238011, 52378306).