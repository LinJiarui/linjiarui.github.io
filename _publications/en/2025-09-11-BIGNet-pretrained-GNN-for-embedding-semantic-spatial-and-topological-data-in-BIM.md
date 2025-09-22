---
title: "Pretrained Graph Neural Network for Embedding Semantic, Spatial, and Topological Data in Building Information Models"
lang: en
ref: publications/2025-09-11-BIGNet-pretrained-GNN-for-embedding-semantic-spatial-and-topological-data-in-BIM
collection: publications
permalink: /en/publications/2025-09-11-BIGNet-pretrained-GNN-for-embedding-semantic-spatial-and-topological-data-in-BIM
excerpt: 'Current large foundation models struggle to effectively process the semantic, spatial, and topological features in BIM models, thus, this study first proposes BIGNet, a large-scale pretrained graph neural network for BIM. Verification through multiple tasks such as design defect identification shows that BIGNet has excellent performance and can effectively utilize the rich design features embedded in BIM models'
date: 2025-09-11
venue: 'Computer-Aided Civil and Infrastructure Engineering'
doi: '10.1111/mice.70073'
paperurl: 'http://doi.org/10.1111/mice.70073'
citation: 'Han, J., Lu, X.Z., Lin, J.R.* (2025). Pretrained Graph Neural Network for Embedding Semantic, Spatial, and Topological Data in Building Information Models. <i>Computer-Aided Civil and Infrastructure Engineering</i>, 1-25. doi: 10.1111/mice.70073'

comment: true
category: journal

tags: 
  - graph neural network
  - large foundation model
  - GNN
  - BIM
  - pretrain
  - intelligent design
  - design checking
  - transfer learning
  - design feature
  - SCI

grants:
  - 52378306
  - 52238011
---

{{site.data.ui-text[page.lang].abstract}}
====

Large foundation models have demonstrated significant advantages in civil engineering, but they primarily focus on textual and visual data, overlooking the rich semantic, spatial, and topological features in building information modeling (BIM) models. Therefore, this study develops the first large-scale graph neural network, BIGNet, to learn and reuse multidimensional design features embedded in BIM models. First, a scalable graph representation is introduced to encode the “semantic-spatial-topological” features of BIM components, and a dataset with nearly 1 million nodes and 3.5 million edges is created. Subsequently, BIGNet is proposed by introducing a new message-passing mechanism to GraphMAE2 and further pretrained with a node masking strategy. Finally, BIGNet is evaluated in various transfer learning tasks for BIM-based design checking. Results show that: (1) homogeneous graph representation outperforms heterogeneous graph in learning design features, (2) considering local spatial relationships in a 30 cm radius enhances performance, and (3) BIGNet with graph attention network-based feature extraction achieves the best transfer learning results. This innovation leads to a 72.7% improvement in average F1-score over non-pretrained models, demonstrating its effectiveness in learning and transferring BIM design features and facilitating their automated application in future design and lifecycle management.

![graphical abstract](/images/2025-09-11-BIGNet-pretrained-GNN-for-embedding-semantic-spatial-and-topological-data-in-BIM-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-09-11-BIGNet-pretrained-GNN-for-embedding-semantic-spatial-and-topological-data-in-BIM.pdf)

This project is funded by the National Natural Science Foundation of China under Grant No. 52378306 and No. 52238011.