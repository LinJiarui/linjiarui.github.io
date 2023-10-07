---
title: "A Multilayer Perceptron-based Fast Sunlight Assessment for the Conceptual Design of Residential Neighborhoods under Chinese Policy"
lang: en
ref: publications/2023-08-14-MLP-based-sunlight-assessment-for-conceptual-design
collection: publications
permalink: /en/publications/2023-08-14-MLP-based-sunlight-assessment-for-conceptual-design
excerpt: 'To achieve realtim sunlight, this study proposes a one-stage sunlight prediction approach based on multilayer perceptron, which reduces the computation time to 1/84~1/50 with 96+% accuracy'
date: 2023-08-14
venue: 'Building and Environment'
doi: '10.1016/j.buildenv.2023.110739'
paperurl: 'http://doi.org/10.1016/j.buildenv.2023.110739'
citation: 'Jiang, C., Liang, X., Zhou, Y.C., Tian, Y., Xu, S, Lin, J.R.*, Ma, Z., Yang S., Zhou, H. (2023). A Multilayer Perceptron-based Fast Sunlight Assessment for the Conceptual Design of Residential Neighborhoods under Chinese Policy. <i>Building and Environment</i>, 244, 110739. doi: 10.1016/j.buildenv.2023.110739'

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


In Chinese building codes, it is required that residential buildings receive a minimum number of hours of natural, direct sunlight on a specified winter day, which represents the worst sunlight condition in a year. This requirement is a prerequisite for obtaining a building permit during the conceptual design of a residential project. Thus, officially sanctioned software is usually used to assess the sunlight performance of buildings. These software programs predict sunlight hours based on repeated shading calculations, which is time-consuming. This paper proposed a multilayer perceptron-based method, a one-stage prediction approach, which outputs a shading time interval caused by the inputted cuboid-form building. The sunlight hours of a site can be obtained by calculating the union of the sunlight time intervals (complement of shading time interval) of all the buildings. Three numerical experiments, i.e., horizontal level and slope analysis, and simulation-based optimization are carried out; the results show that the method reduces the computation time to 1/84~1/50 with 96.5%~98% accuracies. A residential neighborhood layout planning plug-in for Rhino 7/Grasshopper is also developed based on the proposed model. This paper indicates that deep learning techniques can be adopted to accelerate sunlight hour simulations at the conceptual design phase.

![graphical abstract](/images/2023-08-14-MLP-based-sunlight-assessment-for-conceptual-design-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2023-08-14-MLP-based-sunlight-assessment-for-conceptual-design.pdf)

This study was supported by the Research Project of Beijing Municipal Science & Technology Commission, Administrative Commission of Zhongguancun Science Park (20220468132) and the Research Development Project of the Ministry of Housing and Urban‒Rural Development of the People's Republic of China (K20210032). We would also like to sincerely express our appreciation to Prof. Lin Borong of Tsinghua University, China, for providing the MOOSAS simulator.