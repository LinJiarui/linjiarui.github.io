---
title: "Automatic Design Method of Building Pipeline Layout Based on Deep Reinforcement Learning"
lang: zh
ref: publications/2023-07-04-automatic-design-of-building-pipeline-layout-based-on-deep-reinforcement-learning
collection: publications
permalink: /publications/2023-07-04-automatic-design-of-building-pipeline-layout-based-on-deep-reinforcement-learning
excerpt: '本研究提出一种基于深度强化学习（DRL）的建筑管线系统自动设计方法，并初步验证了DRL在复杂管线系统设计中的巨大潜力'
date: 2023-07-04
venue: '30th International Conference on Intelligent Computing in Engineering (EG-ICE 2023)'
doi: 10.48550/arXiv.2305.10760
paperurl: 'https://doi.org/10.48550/arXiv.2305.10760'
citation: 'Yang, C., Zheng, Z., Lin, J.R.* (2023). Automatic Design Method of Building Pipeline Layout Based on Deep Reinforcement Learning. <i>30th International Conference on Intelligent Computing in Engineering (EG-ICE 2023)</i>, 42-51. London, UK.'

comment: true
category: conference

tags: 
  - automatic design
  - pipeline layout
  - BIM
  - reinforcement learning
  - deep learning

grants:
  - 
---


{{site.data.ui-text[page.lang].abstract}}
====

管线布局设计是建筑工程设计关键任务之一。当然，管线布局仍以工程师手工设计为主，费时费力。引入自动化方法对简化管线设计流程、降低设计师工作负荷、节约时间具有重要意义。本研究提出了一种基于深度强化学习（DRL）的管线三维布局生成方法。首先，本研究通过抽象三维空间几何特征构建了训练环境，并基于管道长度、弯头和安装距离三个约束定义勒奖励函数。从而，建立了通过智能体和训练环境相互交互实现了DRL模型的训练。最后，我们选择训练效果最好的DRL模型在单根管道设计中做了验证。结果表明，相比传统算法，DRL模型可以在更短的时间内完成完成管道布设任务，且设计质量更高，并在复杂管线设计中体现出巨大潜力。

The layout design of pipelines is a critical task in the construction industry. Currently, pipeline layout is designed manually by engineers, which is time-consuming and laborious. Automating and streamlining this process can reduce the burden on engineers and save time. In this 
paper, we propose a method for generating three-dimensional layout of pipelines based on deep reinforcement learning (DRL). Firstly, we abstract the geometric features of space to establish a training environment and define reward functions based on three constraints: pipeline length, elbow, and installation distance. Next, we collect data through interactions between the agent and the environment and train the DRL model. Finally, we use the well-trained DRL model to automatically design a single pipeline. Our results demonstrate that DRL models can complete the pipeline layout 
task in space in a much shorter time than traditional algorithms while ensuring high-quality layout outcomes.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2023-07-04-automatic-design-of-building-pipeline-layout-based-on-deep-reinforcement-learning.pdf)

you can find the whole proceedings [here](https://liveuclac-my.sharepoint.com/:b:/g/personal/ucqbtt2_ucl_ac_uk/EcNZcIcR_odFvWgISiaonDQBIBlAyjGBqtEGY-fe_b8nRw?e=Tv39Xs).

The authors are grateful for the support of potential financial support.