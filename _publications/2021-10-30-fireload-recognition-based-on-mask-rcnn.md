---
title: "Deep Learning-based Instance Segmentation for Indoor Fire Load Recognition"
lang: zh
ref: publications/2021-10-30-fireload-recognition-based-on-mask-rcnn
collection: publications
permalink: /publications/2021-10-30-fireload-recognition-based-on-mask-rcnn
excerpt: '本研究构建了首个室内场景火荷载标注图像数据集，并基于深度实例分割实现了室内火荷载的识别，为未来室内火荷载自动估计、风险与韧性评估奠定了基础。'
date: 2021-10-30
venue: 'IEEE Access'
doi: '10.1109/ACCESS.2021.3124831'
paperurl: 'http://doi.org/10.1109/ACCESS.2021.3124831'
citation: 'Zhou, Y.C., Hu, Z.Z., Yan, K.X., Lin, J.R.* (2021). Deep Learning-based Instance Segmentation for Indoor Fire Load Recognition. <i>IEEE Access</i>, 9, xxx-xxx. doi: 10.1109/ACCESS.2021.3124831'

comment: true
category: journal

tags: 
  - building resilience
  - deep learning
  - fire load recognition
  - fire safety
  - indoor scene
  - instance segmentation
  - performance-based design
  - SCI

grants:
  - 72091512
  - 51778336
  - 51908323
---


{{site.data.ui-text[page.lang].abstract}}
====

准确的可燃物或火荷载信息对于建筑物的安全设计和韧性评估至关重要。传统的火灾荷载采集方法，如火灾荷载调查，存在耗时、繁琐、易出错等问题，无法适应室内场景动态变化的特征需求景。为实现室内火荷载的自动估计，首先需实现室内火荷载的快速识别。因此，本研究提出了一种基于计算机视觉火荷载识别的方法，通过基于深度学习的实例分割来自动识别室内火荷载。研究首先根据材料组成将室内元素进行分类并构建了室内场景的火荷载图像标注数据集。在此基础上，研究以Mask-RCNN为基础，通过迁移学习构建了火荷载识别模型和算法。实验结果表明，我们的模型可达到令人满意的准确率，在数据集上的实例分割平均精度 (AP)可达40.5%，AP50可达59.2%，均为领域内精度最高水平。相比人工火荷载识别，自动方法可提升效率近1200倍。本研究主要贡献包括：1)提出 基于实例分割的室内环境火荷载高效自动识别的新方法；2）评估了小样本复杂室内场景微小实例识别效率提升和模型优化和训练策略；3) 构建了首个室内火荷载标注的图像数据集。尽管图像实例分割的研究已非常多，但本研究开创性将其用于室内火荷载识别场景，为建成环境的火荷载估计和韧性评估带来了新方法和新思路。 

Accurate fire load (combustible objects) information is crucial for safety design and resilience assessment of buildings. Traditional fire load acquisition methods, such as fire load survey, which are time-consuming, tedious, and error-prone, failed to adapt to dynamic changed indoor scenes. As a starting point of automatic fire load estimation, fast recognition and detection of indoor fire load are important. Thus, this research proposes a computer vision-based method to automatically detect indoor fire loads using deep learning-based instance segmentation. First, indoor elements are classified into different categories according to their material composition. Next, an image dataset of indoor scenes with instance annotations is developed. Finally, a deep learning model, based on Mask R-CNN, is developed and trained using transfer learning to detect fire loads in images. Experimental results show that our model achieves promising accuracy, as measured by an average precision (AP) of 40.5% and AP50 of 59.2%, for instance segmentation on the dataset. A comparison with manual detection demonstrates the method’s high efficiency as it can detect fire load 1200 times faster than humans. This research contributes to the body of knowledge 1) a novel method of high accuracy and efficiency for automated fire load recognition in indoor environments based on instance segmentation; 2) training techniques for a deep learning model in a relatively small dataset of indoor images which includes complex scenes and a variety of instances; and 3) an image dataset with annotations of indoor fire loads. Although instance segmentation has been applied for several years, this is a pioneering research on using it for automated indoor fire load recognition, which paves the foundation for automatic fire load estimation and resilience assessment for the built environment.

![Graph Abstract]({{ site.baseurl }}/images/2021-10-30-fireload-recognition-based-on-mask-rcnn-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2021-10-30-fireload-recognition-based-on-mask-rcnn.pdf)

This work was supported in part by the National Natural Science Foundation of China under Grant 72091512, 51778336 and 51908323.