---
title: "Deep Learning-based Instance Segmentation for Indoor Fire Load Recognition"
lang: en
ref: publications/2021-10-30-fireload-recognition-based-on-mask-rcnn
collection: publications
permalink: /en/publications/2021-10-30-fireload-recognition-based-on-mask-rcnn
excerpt: 'This research proposes a computer vision-based method to automatically detect indoor fire loads using deep learning-based instance segmentation; an image dataset of indoor scenes with various fire load instances annotated is also developed. Although instance segmentation has been applied for several years, this is a pioneering research on using it for automated indoor fire load recognition, which paves the foundation to automatic fire load estimation and resilience assessment for the built environment.'
date: 2021-10-30
venue: 'IEEE Access'
doi: '10.1109/ACCESS.2021.3124831'
paperurl: 'http://doi.org/10.1109/ACCESS.2021.3124831'
citation: 'Zhou, Y.C., Hu, Z.Z., Yan, K.X., Lin, J.R.* (2021). Deep Learning-based Instance Segmentation for Indoor Fire Load Recognition. <i>IEEE Access</i>, 9, 148771-148782. doi: 10.1109/ACCESS.2021.3124831'

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

header:
  overlay_image: 2021-10-30-fireload-recognition-based-on-mask-rcnn.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  caption: "Fire Load Recognition"
  #cta_url: "full url here"
---


{{site.data.ui-text[page.lang].abstract}}
====

Accurate fire load (combustible objects) information is crucial for safety design and resilience assessment of buildings. Traditional fire load acquisition methods, such as fire load survey, which are time-consuming, tedious, and error-prone, failed to adapt to dynamic changed indoor scenes. As a starting point of automatic fire load estimation, fast recognition and detection of indoor fire load are important. Thus, this research proposes a computer vision-based method to automatically detect indoor fire loads using deep learning-based instance segmentation. First, indoor elements are classified into different categories according to their material composition. Next, an image dataset of indoor scenes with instance annotations is developed. Finally, a deep learning model, based on Mask R-CNN, is developed and trained using transfer learning to detect fire loads in images. Experimental results show that our model achieves promising accuracy, as measured by an average precision (AP) of 40.5% and AP50 of 59.2%, for instance segmentation on the dataset. A comparison with manual detection demonstrates the method’s high efficiency as it can detect fire load 1200 times faster than humans. This research contributes to the body of knowledge 1) a novel method of high accuracy and efficiency for automated fire load recognition in indoor environments based on instance segmentation; 2) training techniques for a deep learning model in a relatively small dataset of indoor images which includes complex scenes and a variety of instances; and 3) an image dataset with annotations of indoor fire loads. Although instance segmentation has been applied for several years, this is a pioneering research on using it for automated indoor fire load recognition, which paves the foundation for automatic fire load estimation and resilience assessment for the built environment.

![Graph Abstract]({{ site.baseurl }}/images/2021-10-30-fireload-recognition-based-on-mask-rcnn-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2021-10-30-fireload-recognition-based-on-mask-rcnn.pdf)

This work was supported in part by the National Natural Science Foundation of China under Grant 72091512, 51778336 and 51908323.


Accession Number: WOS:000716673600001

ISSN: 2169-3536

IDS Number: WU6SR