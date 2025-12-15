---
title: "SMALLM: a Local Small Model Augmented a Cloud-based Large Language Model for Chinese Named Entity Recognition in Low-resource Industries"
lang: en
ref: publications/2025-09-16-SMALLM-local-small-model-augmented-LLM-for-chinese-NER-in-low-resourse-industries
collection: publications
permalink: /en/publications/2025-09-16-SMALLM-local-small-model-augmented-LLM-for-chinese-NER-in-low-resourse-industries
excerpt: 'Cloud LLMs lag in NER, especially in data- or resource-scarce industries. This study proposes SMALLM (BERT + ChatGPT), which boosts ChatGPT’s CNER performance by up to 48.37% with low cost.'
date: 2025-09-16
venue: 'Complex & Intelligent Systems'
doi: '10.1007/s40747-025-02074-6'
paperurl: 'http://doi.org/10.1007/s40747-025-02074-6'
citation: 'Yang, J., Yang, Z.*, Wu, C.*, Guo, Y., Li, X., Lin, J. (2025). SMALLM: a Local Small Model Augmented a Cloud-based Large Language Model for Chinese Named Entity Recognition in Low-resource Industries. <i>Complex & Intelligent Systems</i>, 11, 460. doi: 10.1007/s40747-025-02074-6'

comment: true
category: journal

tags: 
  - LLM
  - large language model
  - NER
  - named entity recognition
  - ChatGPT
  - NLP
  - natural language processing
  - small model
  - BERT
  - SCI

grants:
  - 
---

{{site.data.ui-text[page.lang].abstract}}
====

Although the cloud-based commercial Large Language Models (LLMs) have achieved state-of-the-art (SOTA) performances and cutting-edge zero-shot learning abilities on a variety of Natural Language Processing (NLP) tasks, their performance on Named Entity Recognition (NER) is still significantly below supervised baselines. While NER in the universal domain has achieved remarkable success, NER in specialized industries continues to face challenges due to the scarcity of data and computational resource. To address these issues, this study proposes "SMALLM", a novel NER framework that integrates a local BERT-based model to augment the performance of the state-of-the-art LLM, ChatGPT, in an end-to-end manner. By leveraging both the strengths of the small model and the LLM, SMALLM acts as a domain expert through few-shot learning. SMALLM updates only hundreds of thousands of parameters in the local BERT-based model with minimal training data. This significantly reduces computational demands, enables fast training and minimizes reliance on data. Additionally, our framework provides a solution to the constraints posed by closed-source LLMs like ChatGPT converting their responses into one-hot vectors for subsequent optimization and integration. Through experiments on three industrial Chinese NER (CNER) datasets—Construction, CCKS2019- Military, and CCKS2020-Clinic—SMALLM enhances the performance of ChatGPT, achieving improvements of 28.80%, 13.48%, and 48.37%, respectively. Additionally, SMALLM consistently surpasses mainstream models in low-resource settings.

![graphical abstract](/images/2025-09-16-SMALLM-local-small-model-augmented-LLM-for-chinese-NER-in-low-resourse-industries-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-09-16-SMALLM-local-small-model-augmented-LLM-for-chinese-NER-in-low-resourse-industries.pdf)

 The work described in this paper is supported by grants from Shenzhen Science Fund for Excellent Young Scholars (Grant No. RCYX20221008093036022), Chinese Academy of Sciences President’s International Fellowship Initiative Grant (No.2025PVA0112), Guangdong Special Support Plan Science and Technology Innovation Young Top-notch Talents (No.2023TQ07L745), Shenzhen-Hong Kong joint funding project (A)(No. SGDX20230116092053005), the Science and Technology Project of Shenzhen (No.CJGJZD20220517141405012), the Youth Innovation Promotion Association CAS (Grant No. 2021358), Shenzhen Excellent Innovative Talents (RCYX20221008093036022), and the Guangdong Special Support Plan Science and Technology Innovation Young Topnotch Talents (No.2023TQ07L745).