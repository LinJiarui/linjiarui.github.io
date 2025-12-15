---
title: "Rule-based Information Extraction for Mechanical-Electrical-Plumbing-Specific Semantic Web"
lang: en
ref: publications/2022-01-03-rule-based-information-retrieval-for-MEP-specific-semantic-web
collection: publications
permalink: /en/publications/2022-01-03-rule-based-information-retrieval-for-MEP-specific-semantic-web
excerpt: 'We proposed a rule-based approach for automatic construction of semantic web or knowledge graph related to the MEP domain, both snowball strategy for large-scale corpora collection and methods for named entity recognition and relationship extraction are introduced. The proposed method outperforms existing methods with 40% improvement.'
date: 2022-01-03
venue: 'Automation in Construction'
doi: '10.1016/j.autcon.2021.104108'
paperurl: 'http://doi.org/10.1016/j.autcon.2021.104108'
citation: 'Wu, L.T, Lin, J.R., Leng, S., Li, J.L., Hu, Z.Z. (2022). Rule-based Information Extraction for Mechanical-Electrical-Plumbing-Specific Semantic Web. <i>Automation in Construction</i>, 135, 104108. doi: 10.1016/j.autcon.2021.104108'

comment: true
category: journal

tags: 
  - information extraction
  - MEP
  - rule match
  - named entity recognition
  - relation extraction
  - natural language processing
  - NLP
  - natural language understanding
  - semantic web
  - knowledge graph
  - SCI

grants:
  - 51778336
  - 72091512
  - RCBIM
---


{{site.data.ui-text[page.lang].abstract}}
====

Information extraction (IE), which aims to retrieve meaningful information from plain text, has been widely studied in general and professional domains to support downstream applications. However, due to the lack of labeled data and the complexity of professional mechanical, electrical and plumbing (MEP) information, it is challenging to apply current common deep learning IE methods to the MEP domain. To solve this problem, this paper proposes a rule-based approach for MEP IE task, including a “snowball” strategy to collect large-scale MEP corpora, a suffix-based matching algorithm on text segments for named entity recognition (NER), and a dependency-path-based matching algorithm on dependency tree for relationship extraction (RE). 2 ideas called “meta linking” and “path filtering” for RE are proposed as well, to discover the out-of-pattern entities/relationships as many as possible. To verify the feasibility of the proposed approach, 65 MB MEP corpora have been collected as input of the proposed approach and an MEP semantic web which consists of 15,978 entities and 65,110 relationship triples established, with an accuracy of 81% to entities and 75% to relationship triples, respectively. A comparison experiment between classical deep learning models and the proposed rule-based approach was carried out, illustrating that the performance of our method is 37% and 49% better than the selected deep learning NER and RE models, respectively, in the aspect of extraction precision.


[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2022-01-03-rule-based-information-retrieval-for-MEP-specific-semantic-web.pdf)

This research was supported by the National Natural Science Foundation of China (No. 51778336, No. 72091512), and the Tsinghua University – Glodon Joint Research Center for Building Information Modeling. 


