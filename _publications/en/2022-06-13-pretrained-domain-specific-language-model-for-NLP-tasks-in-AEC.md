---
title: "Pretrained Domain-Specific Language Model for Natural Language Processing Tasks in the AEC Domain"
lang: en
ref: publications/2022-06-13-pretrained-domain-specific-language-model-for-NLP-tasks-in-AEC
collection: publications
permalink: /en/publications/2022-06-13-pretrained-domain-specific-language-model-for-NLP-tasks-in-AEC
excerpt: 'This research develops the first domain corpora and proposes the first domain-specific pretrained language model for AEC, experiments showed that the proposed model outperforms existing methods in all typical NLP tasks, with maximum improvements of 8.1% in the F1-score.'
date: 2022-06-13
venue: 'Computers in Industry'
doi: '10.1016/j.compind.2022.103733'
paperurl: 'http://doi.org/10.1016/j.compind.2022.103733'
citation: 'Zheng, Z., Lu, X.Z., Chen, K.Y., Zhou, Y.C., Lin, J.R.* (2022). Pretrained Domain-Specific Language Model for Natural Language Processing Tasks in the AEC Domain. <i>Computers in Industry</i>, 142, 103733. doi: 10.1016/j.compind.2022.103733'

comment: true
category: journal

tags: 
  - domain corpus
  - deep learning
  - BERT
  - pretrained language model
  - transfer learning
  - NLP
  - construction
  - AEC
  - SCI

grants:
  - 51908323
  - 72091512
  - 2019YFE0112800
  - XPLORER_PRIZE
---


{{site.data.ui-text[page.lang].abstract}}
====

As an essential task for the architecture, engineering, and construction (AEC) industry, information processing and acquiring from unstructured textual data based on natural language processing (NLP) are gaining increasing attention. Although deep learning (DL) models for NLP tasks have been investigated for years, domain-specific pretrained DL models and their advantages are seldomly investigated in the AEC domain. Therefore, this work developed a large scale domain corpora and pretrained domain-specific language models for the AEC domain, and then systematically explores various transfer learning and fine-tuning techniques to explore the performance of pretrained DL models for various NLP tasks. First, both in-domain and close-domain Chinese corpora are developed. Then, two types of pretrained models, including static word embedding models and contextual word embedding models, are pretrained based on various domain corpora. Finally, several widely used DL models for NLP tasks are further trained and tested based on various pretrained models. The result shows that domain corpora can further improve the performance of static word embedding-based DL models and contextual word embedding-based DL models in text classification (TC) and named entity recognition (NER) tasks. Meanwhile, contextual word embedding-based DL models significantly outperform the static word embedding-based DL methods in TC and NER tasks, with maximum improvements of 8.1% and 3.8% in the F1 score, respectively. This research contributes to the body of knowledge in two ways: (1) demonstrating the advantages of domain corpora and pretrained DL models, and (2) opening the first domain-specific dataset and pretrained language models named ARCBERT for the AEC domain. Thus, this work sheds light on the adoption and application of pretrained models in the AEC domain.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2022-06-13-pretrained-domain-specific-language-model-for-NLP-tasks-in-AEC.pdf)

The  authors  are  grateful  for  the  financial  support  received  from  the  National  Natural  Science Foundation  of  China  (No.  51908323,  No.  72091512),  the  National  Key  R&D  Program  (No. 2019YFE0112800), and the Tencent Foundation through the XPLORER PRIZE. 


