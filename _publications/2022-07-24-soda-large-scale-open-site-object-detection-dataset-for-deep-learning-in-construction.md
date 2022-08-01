---
title: "SODA: A Large-scale Open Site Object Detection Dataset for Deep Learning in Construction"
lang: zh
ref: publications/2022-07-24-soda-large-scale-open-site-object-detection-dataset-for-deep-learning-in-construction
collection: publications
permalink: /publications/2022-07-24-soda-large-scale-open-site-object-detection-dataset-for-deep-learning-in-construction
excerpt: '研究构建了面向施工现场物体识别的大规模图像数据集SODA（Site Object Detection dAtaset）,包括不同拍摄视角、光照条件的照片2万余张，覆盖施工现场工人、机械、材料、环境等多类实体。研究表明，本数据集训练的YOLO模型可实现81.47%的mAP，大幅提升有关算法在施工领域的表现，对未来施工多场景算法测试及应用具有重要意义'
date: 2022-07-24
venue: 'Automation in Construction'
doi: '10.1016/j.autcon.2022.104499'
paperurl: 'http://doi.org/10.1016/j.autcon.2022.104499'
citation: 'Duan, R., Deng, H., Tian, M. Deng, Y.C., Lin, J.R. (2022). SODA: A Large-scale Open Site Object Detection Dataset for Deep Learning in Construction. <i>Automation in Construction</i>, 142, 104499. doi: 10.1016/j.autcon.2022.104499'

comment: true
category: journal

tags: 
  - open dataset
  - deep learning
  - object detection
  - construction site
  - computer vision
  - transfer learning
  - pretrained model
  - YOLO
  - image processing
  - SCI

grants:
  - 72091512
  - 51908323
---


{{site.data.ui-text[page.lang].abstract}}
====

大规模图像数据集对建筑及施工行业构建深度学习对象识别模型及算法测试具有重要意义。但有关数据集构建过程复杂，需要大量专业人员精力、知识投入。为此，本研究开发并公布了专门面向施工现场的大型对象识别图像数据集SODA（Site Object Detection dAtaset）。数据集包含施工现场工人、材料、机器和环境等15类实体对象，覆盖了不同拍摄视角、天气条件和施工阶段，共计20000余张照片。实验分析表明，该数据集在多样性和数据规模方面具有显著优势；基于YOLO深度学习目标识别算法的训练和测试进一步表明了该数据集的优越性，最大mAP可达81.47%。总之，本研究为建筑业及施工场景构建了一个大规模开放图像数据集，为相关算法研发、测试及应用奠定了重要基础。


Comprehensive image datasets can benefit the construction industry in terms of serving as the basis for generating deep-learning-based object detection models and testing the performance of object detection algorithms, but building such datasets is complex and requires vast professional knowledge. This paper develops and publicly releases a new large-scale image dataset specifically collected and annotated for the construction site, called Site Object Detection dAtaset (SODA), which contains 15 object classes categorized by the worker, material, machine, and layout. More than 20,000 images were collected from multiple construction sites in different situations, weather conditions, and construction phases, covering different angles and perspectives. Statistical analysis shows that the dataset is well developed in terms of diversity and volume. Further evaluation with two widely adopted deep learning-based object detection algorithms also illustrates the feasibility
of the dataset, achieving a maximum mAP of 81.47%. This research contributes a large-scale open image dataset for the construction industry and sets up a performance benchmark for further evaluation of relevant algorithms. 

![Graph Abstract]({{ site.baseurl }}/images/2022-07-24-soda-graph-abstract.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2022-07-24-soda-large-scale-open-site-object-detection-dataset-for-deep-learning-in-construction.pdf)

[数据集下载链接]({{ site.baseurl }}/portfolio/2022-02-22-SODA-site-object-detection-dataset-for-deep-learning-in-construction)

The authors would like to acknowledge the support by Guangdong Science Foundation (Grant No. 2022A1515010174); the support by the State Key Lab of Subtropical Building Science, South China University of Technology (No. 2022ZB19); the support by the Guangzhou Science and Technology Program (No. 202201010338); and the National Natural Science Foundation of China (Grant No. 72091512, 51908323). 