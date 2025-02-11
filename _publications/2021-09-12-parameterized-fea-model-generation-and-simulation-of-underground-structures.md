---
title: "Parameterized FEA Model Generation and Simulation of Underground Structures Based on BIM: A Case Study"
lang: zh
ref: publications/2021-09-12-parameterized-fea-model-generation-and-simulation-of-underground-structures
collection: publications
permalink: /publications/2021-09-12-parameterized-fea-model-generation-and-simulation-of-underground-structures
excerpt: '论文将可视化编程与OpenSees相结合，提出一种基于参数化的地下结构有限元模型参数化生成与仿真方法，可自动生成施工过程不同时间点的仿真模型并自动分析结构受力情况，有关成果对地铁结构施工安全风险识别与管控具有重要意义'
date: 2021-09-12
venue: 'Proceedings of the ASCE 2021 International Conference on Computing in Civil Engineering (i3CE 2021)'
doi: '10.1061/9780784483893.051'
paperurl: 'https://doi.org/10.1061/9780784483893.051'
citation: 'Song, S.Y., Lin, J.R.*, Zhou, Y.C., Ding, W.Q. (2021). Parameterized FEA Model Generation and Simulation of Underground Structures Based on BIM: A Case Study. <i>Proceedings of the ASCE 2021 International Conference on Computing in Civil Engineering (i3CE 2021)</i>, 408-416. Orlando, Florida, USA.'

comment: true
category: conference

tags: 
  - BIM
  - visual programming
  - finite element
  - construction
  - parametric modeling
  - generative design

grants:
  - 51908323
  - 72091512
  - RCBIM
---


{{site.data.ui-text[page.lang].abstract}}
====

论文将可视化编程与OpenSees相结合，提出一种基于参数化的地下结构有限元模型参数化生成与仿真方法，可自动生成施工过程不同时间点的仿真模型并自动分析结构受力情况，有关成果对地铁结构施工安全风险识别与管控具有重要意义。

Building information modeling (BIM) and finite element analysis (FEA) are widely used technologies for underground structure design; however, they failed to coordinate work well. Currently, existing BIM-to-FEA model conversion methods have a coarse conversion effect and a narrow scope of application. They do not consider the variational working conditions in the construction of underground structures, and thus can hardly be used in the simulations. To address this problem, this research proposes a semi-automatic BIM-to-FEA conversion method for construction simulation of underground structures based on Revit Dynamo and OpenSees software. The method is realized in three steps. Firstly, typical subway stations are selected as the research objects, and the parameterized BIM models are established. Secondly, based on Dynamo visual programming and tool command language (TCL) scripts, a BIM-to-FEA semi-automatic conversion method is formed to carry out FEA calculation. Finally, the method is extended for construction simulation. Based on the BIM model of the station’s enveloping structure, an FEA model of diaphragm wall with multiple working conditions is automatically generated, and the structural simulation of the open-cut excavation process is conducted. This method provides an automatic BIM-to-FEA conversion way that can efficiently generate FEA construction simulation models with various working conditions, and realizes a time-saving construction simulation framework based on BIM technology.

<video poster="/images/2021-09-12-parameterized-fea-model-generation-and-simulation-of-underground-structures.jpg" controls preload>
    <source src="/videos/2021-09-12-parameterized-fea-model-generation-and-simulation-of-underground-structures.mp4" media="only screen and (min-device-width: 568px)"></source> 
</video>

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2021-09-12-parameterized-fea-model-generation-and-simulation-of-underground-structures.pdf)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

The authors are grateful for the financial support received from the National Natural Science Foundation of China (No. 51908323, No. 72091512), and the Tsinghua University-Glodon Joint Research Center for Building Information Model (RCBIM).