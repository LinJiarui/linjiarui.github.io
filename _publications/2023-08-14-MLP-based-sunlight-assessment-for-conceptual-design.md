---
title: "A Multilayer Perceptron-based Fast Sunlight Assessment for the Conceptual Design of Residential Neighborhoods under Chinese Policy "
lang: zh
ref: publications/2023-08-14-MLP-based-sunlight-assessment-for-conceptual-design
collection: publications
permalink: /publications/2023-08-14-MLP-based-sunlight-assessment-for-conceptual-design
excerpt: 'To achieve realtim sunlight, this study proposes a one-stage sunlight prediction approach based on multilayer perceptron, which reduces the computation time to 1/84~1/50 with 96+% accuracy'
date: 2023-08-14
venue: 'Building and Environment'
doi: '10.1016/j.buildenv.2023.110739'
paperurl: 'http://doi.org/10.1016/j.buildenv.2023.110739'
citation: 'Jiang, C., Liang, X., Zhou, Y.C., Tian, Y., Xu, S, Lin, J.R.*, Ma, Z., Yang S., Zhou, H. (2023). A Multilayer Perceptron-based Fast Sunlight Assessment for the Conceptual Design of Residential Neighborhoods under Chinese Policy . <i>Building and Environment</i>, 243, 110739. doi: 10.1016/j.buildenv.2023.110739'

comment: true
category: journal

tags: 
  - conceptual design
  - sunlight analysis
  - neural network
  - shading calculation
  - simulation optimization
  - SCI

grants:
  - 20220468132
  - K20210032
---


{{site.data.ui-text[page.lang].abstract}}
====

中国建筑设计规范通常要求住宅建筑在冬至日时接受的自然直射阳光最低时数应满足特定要求，这是在住宅项目概念设计过程必须满足的规范要求。 因此，使用官方认可的软件评估建筑物的日照情况是设计过程的关键步骤之一，然而该过程往往需要大量计算不同时间点的日照情况来预测最低日照时间，因此非常耗时。针对该问题，本研究提出了一种基于多层感知机的单阶段预测方法，可快速计算立方体建筑的日照时间间隔。并可通过计算所有建筑物日照时间间隔（遮阳时间间隔的补集）的并集，以快速计算整个小区的日照时数。研究通过平面、坡面等不同数值试验对所提出的方法进行了验证，结果表明，本文方法可将计算时间减少到既有方法的1/84∼1/50，且准确率保持在96.5%∼98%。研究同时基于所提出的模型，开发了适用于 Rhino 7/Grasshopper 的住宅小区布局规划插件。相关研究为在概念设计阶段利用深度学习技术加速日照分析，提升设计效率带来了新方法。

![graphical abstract](/images/2023-08-14-MLP-based-sunlight-assessment-for-conceptual-design-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2023-08-14-MLP-based-sunlight-assessment-for-conceptual-design.pdf)

This study was supported by the Research Project of Beijing Municipal Science & Technology Commission, Administrative Commission of Zhongguancun Science Park (20220468132) and the Research Development Project of the Ministry of Housing and Urban‒Rural Development of the People's Republic of China (K20210032). We would also like to sincerely express our appreciation to Prof. Lin Borong of Tsinghua University, China, for providing the MOOSAS simulator.