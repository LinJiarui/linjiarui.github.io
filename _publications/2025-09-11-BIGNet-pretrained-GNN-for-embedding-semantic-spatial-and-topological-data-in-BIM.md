---
title: "Pretrained Graph Neural Network for Embedding Semantic, Spatial, and Topological Data in Building Information Models"
lang: zh
ref: publications/2025-09-11-BIGNet-pretrained-GNN-for-embedding-semantic-spatial-and-topological-data-in-BIM
collection: publications
permalink: /publications/2025-09-11-BIGNet-pretrained-GNN-for-embedding-semantic-spatial-and-topological-data-in-BIM
excerpt: '针对当前大模型难以有效处理BIM模型中语义、空间及拓扑特征的问题，本研究首先构建了面向BIM的大规模图神经网络 BIGNet，经设计缺陷识别等多任务验证表明BIGNet性能优异，可有效利用BIM模型中丰富的设计特征'
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

大型基础模型在土木工程领域展现出显著优势，但目前其研究多聚焦于文本与视觉数据，忽略了建筑信息模型（BIM）中丰富的语义、空间及拓扑特征。为此，本研究构建首个大规模图神经网络 BIGNet，旨在学习并复用 BIM 模型中蕴含的多维设计特征。首先，提出可扩展的图表示方法，对 BIM 构件的 “语义 - 空间 - 拓扑” 特征进行编码，并构建含近 100 万个节点、350 万条边的数据集；其次，在 GraphMAE2 基础上引入新型消息传递机制构建 BIGNet，并采用节点掩码策略对其进行预训练；最后，在多个基于 BIM 的设计审查迁移学习任务中对 BIGNet 开展评估。结果表明：（1）同构图表示在学习设计特征方面优于异构图；（2）考虑 30 厘米半径内的局部空间关系可提升模型性能；（3）结合图注意力网络特征提取的 BIGNet 迁移学习效果最佳。该创新使模型平均 F1 分数较非预训练模型提升 72.7%，证实其在学习与迁移 BIM 设计特征方面的有效性，为未来设计及全生命周期管理中设计特征的自动化应用提供支撑。

Large foundation models have demonstrated significant advantages in civil engineering, but they primarily focus on textual and visual data, overlooking the rich semantic, spatial, and topological features in building information modeling (BIM) models. Therefore, this study develops the first large-scale graph neural network, BIGNet, to learn and reuse multidimensional design features embedded in BIM models. First, a scalable graph representation is introduced to encode the “semantic-spatial-topological” features of BIM components, and a dataset with nearly 1 million nodes and 3.5 million edges is created. Subsequently, BIGNet is proposed by introducing a new message-passing mechanism to GraphMAE2 and further pretrained with a node masking strategy. Finally, BIGNet is evaluated in various transfer learning tasks for BIM-based design checking. Results show that: (1) homogeneous graph representation outperforms heterogeneous graph in learning design features, (2) considering local spatial relationships in a 30 cm radius enhances performance, and (3) BIGNet with graph attention network-based feature extraction achieves the best transfer learning results. This innovation leads to a 72.7% improvement in average F1-score over non-pretrained models, demonstrating its effectiveness in learning and transferring BIM design features and facilitating their automated application in future design and lifecycle management.

![graphical abstract](/images/2025-09-11-BIGNet-pretrained-GNN-for-embedding-semantic-spatial-and-topological-data-in-BIM-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-09-11-BIGNet-pretrained-GNN-for-embedding-semantic-spatial-and-topological-data-in-BIM.pdf)

This project is funded by the National Natural Science Foundation of China under Grant No. 52378306 and No. 52238011.