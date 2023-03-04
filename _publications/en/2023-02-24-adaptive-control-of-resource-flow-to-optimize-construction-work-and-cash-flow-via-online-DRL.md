---
title: "Adaptive Control of Resource Flow to Optimize Construction Work and Cash Flow via Online Deep Reinforcement Learning"
lang: en
ref: publications/2023-02-24-adaptive-control-of-resource-flow-to-optimize-construction-work-and-cash-flow-via-online-DRL
collection: publications
permalink: /en/publications/2023-02-24-adaptive-control-of-resource-flow-to-optimize-construction-work-and-cash-flow-via-online-DRL
excerpt: 'This paper introducess a model and method to adaptive control the resource flows to optimize the work and cash flows of construction projects, which could save 7% total with impact on duration'
date: 2023-02-24
venue: 'Automation in Construction'
doi: '10.1016/j.autcon.2023.104817'
paperurl: 'http://doi.org/10.1016/j.autcon.2023.104817'
citation: 'Jiang, C., Li, X., Lin, J.R.*, Liu, M., Ma, Z. (2023). Adaptive Control of Resource Flow to Optimize Construction Work and Cash Flow via Online Deep Reinforcement Learning. <i>Automation in Construction</i>, 150, 104817. doi: 10.1016/j.autcon.2023.104817'

comment: true
category: journal

tags: 
  - inforcement learning
  - resource planning
  - construction optimization
  - proximal policy optimization
  - adaptive control
  - SCI

grants:
  - K20210032
---


{{site.data.ui-text[page.lang].abstract}}
====

Due to complexity and dynamics of construction work, resource, and cash flows, poor management of them usually leads to time and cost overruns, bankruptcy, even project failure. Existing approaches in construction failed to achieve optimal control of resource flow in a dynamic environment with uncertainty. Therefore, this paper introducess a model and method to adaptive control the resource flows to optimize the work and cash flows of construction projects. First, a mathematical model based on a partially observable Markov decision process is established to formulate the complex interactions of construction work, resource, and cash flows as well as uncertainty and variability of diverse influence factors. Meanwhile, to efficiently find the optimal solutions, a deep reinforcement learning (DRL) based method is introduced to realize the continuous adaptive optimal control of labor and material flows, thereby optimizing the work and cash flows. To assist the training process of DRL, a simulator based on discrete event simulation is also developed to mimic the dynamic features and external environments of a project. Experiments in simulated scenarios illustrate that our method outperforms the vanilla empirical method and genetic algorithm, possesses remarkable capability in diverse projects and external environments, and a hybrid agent of DRL and empirical method leads to the best result. This paper contributes to adaptive control and optimization of coupled work, resource, and cash flows, and may serve as a step stone for adopting DRL technology in construction project management.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2023-02-24-adaptive-control-of-resource-flow-to-optimize-construction-work-and-cash-flow-via-online-DRL.pdf)

This study was supported by a grant from Glodon Company Limited and the Research Development Project of the Ministry of Housing and Urban-Rural Development of the People’s Republic of China (K20210032).