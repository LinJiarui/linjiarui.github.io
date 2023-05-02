---
title: "Adaptive Control of Resource Flow to Optimize Construction Work and Cash Flow via Online Deep Reinforcement Learning"
lang: zh
ref: publications/2023-02-24-adaptive-control-of-resource-flow-to-optimize-construction-work-and-cash-flow-via-online-DRL
collection: publications
permalink: /publications/2023-02-24-adaptive-control-of-resource-flow-to-optimize-construction-work-and-cash-flow-via-online-DRL
excerpt: '本研究针对施工过程现金流与工序调度提出一种基于在线深度强化学习（DRL）的自适应资源调控方法，相比经典方法可以在工期不变的情况节约7%的成本'
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
  - 20220468132
  - K20210032
---


{{site.data.ui-text[page.lang].abstract}}
====

建造过程工序、资源和现金流具有高度的复杂性和动态性，一旦管理不当往往会导致时间和成本超支、破产，甚至项目失败。现有的施工管控方法尚不能有效的实现不确定性动态环境中的资源高效调度和控制。因此，本文引入一种施工过程资源流自适应调度的模型和方法，以实现施工工序和现金流的优化。首先，研究将施工过程的工序、资源和现金流的复杂相互作用以及各类不确定因素的影响形式化为一个基于部分可观察的马尔可夫决策过程的数学模型；同时，研究引入基于深度强化学习（DRL）的方法实现了该模型的高效求解，以实现对人员、材料的连续自适应优化控制并优化工序及现金流。此外，为了辅助DRL的训练过程，研究同时建立了基于离散事件模拟的模拟器来模拟项目的动态特征和外部环境。实验表明，我们的方法优于朴素经验方法和遗传算法，在不同的项目和外部环境中具有显著优势，并且混合DRL和经验方法训练的决策代理可以产生最优方案。本研究贡献了耦合“工序-资源-现金”多要素的自适应控制和优化，并为工程施工过程利用DRL技术奠定了基础。

Due to complexity and dynamics of construction work, resource, and cash flows, poor management of them usually leads to time and cost overruns, bankruptcy, even project failure. Existing approaches in construction failed to achieve optimal control of resource flow in a dynamic environment with uncertainty. Therefore, this paper introducess a model and method to adaptive control the resource flows to optimize the work and cash flows of construction projects. First, a mathematical model based on a partially observable Markov decision process is established to formulate the complex interactions of construction work, resource, and cash flows as well as uncertainty and variability of diverse influence factors. Meanwhile, to efficiently find the optimal solutions, a deep reinforcement learning (DRL) based method is introduced to realize the continuous adaptive optimal control of labor and material flows, thereby optimizing the work and cash flows. To assist the training process of DRL, a simulator based on discrete event simulation is also developed to mimic the dynamic features and external environments of a project. Experiments in simulated scenarios illustrate that our method outperforms the vanilla empirical method and genetic algorithm, possesses remarkable capability in diverse projects and external environments, and a hybrid agent of DRL and empirical method leads to the best result. This paper contributes to adaptive control and optimization of coupled work, resource, and cash flows, and may serve as a step stone for adopting DRL technology in construction project management.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2023-02-24-adaptive-control-of-resource-flow-to-optimize-construction-work-and-cash-flow-via-online-DRL.pdf)

This study was supported by Research Project of Beijing Municipal Science & Technology Commission, Administrative Commission of Zhongguancun Science Park (20220468132) and the Research Development Project of the Ministry of Housing and Urban-Rural Development of the People's Republic of China (K20210032).