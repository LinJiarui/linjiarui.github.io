---
title: "A Text Classification-based Approach for Evaluating and Enhancing the Machine Interpretability of Building Codes"
lang: en
ref: publications/2023-09-24-text-classification-for-evaluating-and-enhancing-machine-interpretability-of-building-codes
collection: publications
permalink: /en/publications/2023-09-24-text-classification-for-evaluating-and-enhancing-machine-interpretability-of-building-codes
excerpt: 'This study proposes a text classification approach based on a pretrained large language model, to identify computer-processible clauses and to evaluate the machine interpretability of building codes. Result show that the proposed algorithm outperforms SOTA methods with an F1-score of 93.6%, and could further improve downstream rule interpretation algorithm by 4%. It is also revealed that the overall interpretability of building codes is only 34.4%.'
date: 2023-09-24
venue: 'Engineering Applications of Artificial Intelligence'
doi: '10.1016/j.engappai.2023.107207'
paperurl: 'http://doi.org/10.1016/j.engappai.2023.107207'
citation: 'Zheng, Z., Zhou, Y.C., Chen, K.Y., Lu, X.Z., She, Z.T., Lin, J.R.* (2024). A Text Classification-based Approach for Evaluating and Enhancing the Machine Interpretability of Building Codes. <i>Engineering Applications of Artificial Intelligence</i>, 127PA, 107207. doi: 10.1016/j.engappai.2023.107207'

comment: true
category: journal

tags: 
  - rule interpretation
  - NLP
  - ARC
  - pretrained model
  - intelligent design
  - text classification
  - human-machine intelligence
  - SCI

grants:
  - 52378306
  - 51908323
---


{{site.data.ui-text[page.lang].abstract}}
====

Interpreting regulatory documents or building codes into computer-processable formats is essential for the intelligent design and construction of buildings and infrastructures. Although automated rule interpretation (ARI) methods have been investigated for years, most of them are highly dependent on the early and manual filtering of interpretable clauses from a building code. While few of them considered machine interpretability, which represents the potential to be transformed into a computer-processable format, from both clause- and document-level. Therefore, this research aims to propose a novel approach to automatically evaluate and enhance the machine interpretability of single clauses and building codes. First, a few categories are introduced to classify each clause in a building code considering the requirements for rule interpretation, and a dataset is developed for model training. Then, an efficient text classification model is developed based on a pretrained domain-specific language model and transfer learning techniques. Finally, a quantitative evaluation method is proposed to assess the overall interpretability of building codes. Experiments show that the proposed text classification algorithm outperforms the existing CNN- or RNN-based methods, by improving the F1-score from 72.16% to 93.60%. It is also illustrated that the proposed classification method can enhance downstream ARI methods with an improvement of 4%. Furthermore, analysis of more than 150 building codes in China showed that their average interpretability is only 34.40%, which implies that it is still difficult to fully transform an entire regulatory documents into computer-processable formats. It is also argued that the interpretability of building codes should be further improved both from the human side (considering certain constraints when writing building codes) and the machine side (developing more powerful algorithms, tools, etc.).

![graphical abstract](/images/2023-09-24-text-classification-for-machine-interpretability-of-building-codes-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2023-09-24-text-classification-for-evaluating-and-enhancing-machine-interpretability-of-building-codes.pdf)

The authors are grateful for the financial support received from the 2023 Open Selection Project of Tsinghua University-Tsingshang Joint Institute for Smart Scene Innovation Design and the National Natural Science Foundation of China (no. 52378306 and no. 51908323).