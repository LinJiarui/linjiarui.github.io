---
title: "Visualization of Indoor Thermal Environment on Mobile Devices based on Augmented Reality and Computational Fluid Dynamics"
lang: zh
ref: publications/2019-03-12-ar-based-cfd-visualization-for-indoor-thermal-environment
collection: publications
permalink: /publications/2019-03-12-ar-based-cfd-visualization-for-indoor-thermal-environment
excerpt: '本研究提出一种用于在移动终端上基于AR实现室内气流CFD仿真可视化的方法，相比vtk格式数据压缩比高达63.4%，数据加载时间最高节约89.3%，有关源代码和测试数据已在GitHub上传'
date: 2019-03-12
venue: 'Automation in Construction'
doi: '10.1016/j.autcon.2019.02.007'
paperurl: 'https://doi.org/10.1016/j.autcon.2019.02.007'
citation: 'Lin, J.*, Cao, J., Zhang, J., van Treeck, C., Frisch, J. (2019). Visualization of Indoor Thermal Environment on Mobile Devices based on Augmented Reality and Computational Fluid Dynamics. <i>Automation in Construction</i>, 103, 26-40. doi: 10.1016/j.autcon.2019.02.007'

comment: true
category: journal

tags: 
  - CFD
  - SCI
  - AR
  - visualization
  - indoor thermal environment

grants:
  - 2017YFC0704200
  - 8194067
  - QNRC2016001
  - RCBIM
---


{{site.data.ui-text[page.lang].abstract}}
====

Augmented reality (AR) based visualization of computational fluid dynamics (CFD) simulation on mobile devices is important for the understanding and discussion of indoor thermal environments in the design process. However, utilizing AR-based mobile device for indoor thermal environment understanding still encounters problems due to limited computational power and lack of efficient interaction methods. To improve the performance of AR-based CFD visualization on a mobile device and provide the users with intuitive interaction with indoor environment, an integrated approach based on client-server framework is established. Within the approach, a new mobile friendly data format (cfd4a) with low computational complexity is proposed for CFD simulation results representation. Server-side data pre-processing method is also introduced to reduce the computational power and time needed on the client side. Furthermore , interactive section view selection and time-step animation methods are proposed for intuitive interaction with the AR environment. Then, a prototype system is developed with Unity3D engine and Tango Tablet. Demonstration in * Corresponding author some typical scenarios shows that the proposed method and prototype system provide an intuitive and fluent AR-based environment for interactive indoor thermal environment visualization. Comparing to the widely used vtk format, a data compression ratio of 63.4% and a loading time saving ratio of 89.3% are achieved in the performance test with the proposed method. The proposed approach also shows good flexibility and extensibility in supporting different AR devices through exposing standard web services and utilizing the widely used Unity3D engine. Source code of the developed prototype and relevant testing data are also shared through github, enabling other researchers to compare our work with theirs. It is also suggested that stability of AR-based mobile devices, new interaction methods and integration with cloud computing still need further investigation and improvement.

[{{site.data.ui-text[page.lang].download_paper}}](https://doi.org/10.1016/j.autcon.2019.02.007)

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2019-03-12-ar-based-cfd-visualization-for-indoor-thermal-environment.pdf)

[源代码和测试数据](https://github.com/LinJiarui/ARvis-CFD/)

有关[学术报告1]({{ site.baseurl }}/talks/2019-05-26-AR-based-CFD-visualization)和[学术报告2]({{ site.baseurl }}/talks/2019-04-04-connecting-virtual-and-physical-world-for-aec-projects)

This work was funded by the National Key R&D Program of China (Grant No. 2017YFC0704200) as well as by the Excellence Initiative of the German Federal and State Governments, the Beijing Natural Science Foundation (No. 8194067), the Young Elite Scientists Sponsorship Program by China Association for Science and Technology (No. QNRC2016001) and the Tsinghua University-Glodon Joint Research Centre for Building Information Model (RCBIM).

Accession Number: WOS:000466828500003

ISSN: 0926-5805

eISSN: 1872-7891

IDS Number: HW6VJ