---
title: "Intelligent BIM Searching via Deep Embedding of Geometric, Semantic, and Topological Features"
lang: zh
ref: publications/2025-03-20-intelligent-BIM-searching-via-deep-embedding-of-GST-features
collection: publications
permalink: /publications/2025-03-20-intelligent-BIM-searching-via-deep-embedding-of-GST-features
excerpt: '本研究提出了一种BIM模型智能搜索方法，可通过深度学习融合几何、语义、拓扑多维特征，实现更加精准的搜索，相比传统方法提升4-6%'
date: 2025-03-20
venue: 'Buildings'
doi: '10.3390/buildings15060951'
paperurl: 'http://doi.org/10.3390/buildings15060951'
citation: 'Huang, P.H., Song, S.Y., Xu, Z., Hu, Z.Z., Lin, J.R.* (2025). Intelligent BIM Searching via Deep Embedding of Geometric, Semantic, and Topological Features. <i>Buildings</i>, 15(6), 951. doi: 10.3390/buildings15060951'

comment: true
category: journal

tags: 
  - BIM
  - model search
  - feature extraction
  - deep learning
  - similarity
  - feature embedding
  - intelligent design
  - SCI

grants:
  - 2022YFC3801100
  - 2023YFC3804600
  - 52378306
---

{{site.data.ui-text[page.lang].abstract}}
====

作为建筑物的完整数字化表达，建筑信息模型 (BIM) 封装了几何、语义和拓扑特征 (GSTF)，以表达建筑组件及其连接的几何、视觉及功能特征，从而表征建筑系统。然而，既有BIM模型检索方法非常注重语义特征，而忽略了几何和拓扑特征，因此很难充分复用BIM模型中的丰富知识。因此，本研究提出了一种通过深度学习 (DL) 嵌入 GSTF 的智能 BIM 搜索新方法。首先，开发了从 BIM 中提取 GSTF 并从搜索查询中识别所需 GSTF 的算法。然后，通过 DL 模型嵌入不同的 GSTF，创建基于向量的 BIM 或搜索查询表示。最后，采用基于相似性的排名来查找与查询高度相关的 BIM。实验表明，所提出的方法比手动检索方法效率高 780 倍，比传统方法效率高 4-6%。本研究提供了一种更全面、准确、高效的方法来查找和重用 BIM 中的丰富知识，从而推动了 BIM 搜索领域的发展，最终有助于更好地进行建筑设计和知识管理。

As a digital representation of buildings, building information models (BIMs) encapsulate geometric, semantic, and topological features (GSTFs), to express the visual and functional characteristics of building components and their connections to create building systems. However, searching for BIMs pays much attention to semantic features, while overlooking geometric and topological features, making it difficult to find and reuse rich knowledge in BIMs. Thus, this study proposes a novel approach to intelligent BIM searching by embedding GSTFs via deep learning (DL). First, algorithms for extracting GSTFs from BIMs and identifying required GSTFs from search queries are developed. Then, different GSTFs are embedded via DL models, creating vector-based representations of BIMs or search queries. Finally, similarity-based ranking is adopted to find BIMs highly related to the queries. Experiments show that the proposed approach demonstrates an efficiency of 780 times greater than manual retrieval methods and 4–6% more efficient than traditional methods. This study advances the field of BIM searching by providing a more comprehensive, accurate, and efficient method for finding and reusing rich knowledge in BIMs, ultimately contributing to better building design and knowledge management.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-03-20-intelligent-BIM-searching-via-deep-embedding-of-GST-features.pdf)

The authors are grateful for the financial support received from the National Key R&D Program of China (No. 2022YFC3801100, No. 2023YFC3804600) and the National Natural Science Foundation of China (No. 52378306).