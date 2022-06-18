---
title: "Pretrained Domain-Specific Language Model for Natural Language Processing Tasks in the AEC Domain"
lang: zh
ref: publications/2022-06-13-pretrained-domain-specific-language-model-for-NLP-tasks-in-AEC
collection: publications
permalink: /publications/2022-06-13-pretrained-domain-specific-language-model-for-NLP-tasks-in-AEC
excerpt: '研究建立了首个面向建筑业的大规模领域语料库及深度学习预训练模型，试验表明所提出的预训练模型在文本分类、命名实体识别等多个领域任务中表现优异，F2最高提升8.1%，为行业知识图谱研究及应用提供了重要支撑'
date: 2022-06-13
venue: 'Computers in Industry'
doi: '10.1016/j.compind.2022.103733'
paperurl: 'http://doi.org/10.1016/j.compind.2022.103733'
citation: 'Zheng, Z., Lu, X.Z., Chen, K.Y., Zhou, Y.C., Lin, J.R.*. (2022). Pretrained Domain-Specific Language Model for Natural Language Processing Tasks in the AEC Domain. <i>Computers in Industry</i>, 142, 103733. doi: 10.1016/j.compind.2022.103733'

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

作为建筑业 (AEC)的信息获取（IR）的重要任务，自然语言处理 (NLP)得到了越来越多的关注。尽管深度学习模型已在NLP任务中得到广泛应用并被引入到建筑业相关研究中，但目前仍缺乏面向建筑业的大规模领域语料库及预训练模型。因此，本研究面向建筑业NLP应用，构建了首个一个大规模领域语料库和领域预训练模型，并系统地分析了不同迁移学习策略及微调技术对各类NLP任务的性能影响。最后，在各种预训练模型的基础上，进一步训练和构建了面向多任务的预训练模型。结果表明，在文本分类和命名实体识别任务中，领域语料库对传统词嵌入模型具有相反的效果，但可有效提高 BERT 深度学习模型在所有任务中的性能。同时，研究显示，BERT领域预训练模型在所有IR任务中的表现都显著优于传统方法，F1最大提升分别为可达5.4%和 10.1%。因此，本研究一方面有效展示了领域语料库和预训练深度学习模型在领域NLP任务中的巨大优势，另一方面所提出的首个领域语料库和预训练模型也为建筑业NLP应用提供了重要的支撑。


As an essential task for the architecture, engineering, and construction (AEC) industry, information retrieval (IR) from unstructured textual data based on natural language processing (NLP) is gaining increasing attention. Although deep learning (DL) models for IR tasks have been investigated for years, domain-specific pretrained DL models and their advantages are seldomly investigated in the AEC domain. Therefore, this work developed a large scale domain corpora and a pretrained domain-specific language model for the AEC domain, and systematically explores various transfer learning and fine-tuning techniques to explode the performance of pretrained DL models for various IR tasks. First, both in-domain and close-domain corpora are developed. Then, two types of pretrained models, including traditional word embedding models and BERT-based models, are pretrained based on various domain corpora. Finally, several widely used DL models for IR tasks are further trained and tested based on various pretrained models. The result shows that domain corpora have opposite effects on traditional word embedding models for text classification and named entity recognition tasks but can further improve the performance of BERT-based models in all tasks. Meanwhile, BERT-based models significantly outperform traditional methods in all IR tasks, with maximum improvements of 5.4% and 10.1% in the F1 score, respectively. This research contributes to the body of knowledge in two ways: 1) demonstrating the advantages of domain corpora and pretrained DL models and 2) opening the first domain-specific dataset and pretrained language model for the AEC domain. Thus, this work sheds light on the adoption and application of pretrained models in the AEC domain.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2022-06-13-pretrained-domain-specific-language-model-for-NLP-tasks-in-AEC.pdf)

The  authors  are  grateful  for  the  financial  support  received  from  the  National  Natural  Science Foundation  of  China  (No.  51908323,  No.  72091512),  the  National  Key  R&D  Program  (No. 2019YFE0112800), and the Tencent Foundation through the XPLORER PRIZE. 


