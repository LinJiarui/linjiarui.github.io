---
title: "Integrating NLP and Context-Free Grammar for Complex Rule Interpretation towards Automated Compliance Checking"
lang: en
ref: publications/2022-07-12-integrating-NLP-and-CFG-for-rule-interpretation-towards-ACC
collection: publications
permalink: /en/publications/2022-07-12-integrating-NLP-and-CFG-for-rule-interpretation-towards-ACC
excerpt: 'This research integrates natural language processing (NLP) and context-free grammar (CFG) to propose a novel generalized rule interpretation approach, which outperforms the state-of-the-art methods and achieves 99.6% and 91.0% accuracies for parsing single- and multi-requirement sentences. This research also publishes the first regulation dataset for future exploration, validation, and benchmarking in the ARC area'
date: 2022-07-12
venue: 'Computers in Industry'
doi: '10.1016/j.compind.2022.103746'
paperurl: 'http://doi.org/10.1016/j.compind.2022.103746'
citation: 'Zhou, Y.C., Zheng, Z., Lin, J.R.*, Lu, X.Z. (2022). Integrating NLP and Context-Free Grammar for Complex Rule Interpretation towards Automated Compliance Checking. <i>Computers in Industry</i>, 142, 103746. doi: 10.1016/j.compind.2022.103746'

comment: true
category: journal

tags: 
  - rule interpretation
  - deep learning
  - context-free grammar
  - automated compliance checking
  - automated rule checking
  - semantic labeling
  - syntax parsing
  - smart design
  - BIM
  - NLP
  - SCI

grants:
  - 51908323
  - 72091512
  - 2018YFD1100900
  - 2019Z02UOT
---


{{site.data.ui-text[page.lang].abstract}}
====

Automated rule checking (ARC) is expected to significantly promote the efficiency and compliance of design in the construction industry. The most vital and complex stage of ARC is interpreting the regulatory text into a computer-processable format. However, existing systems and studies of rule interpretation either require considerable time-consuming manual effort or are based on exhaustive enumerations of matching patterns with a limited scope of application. To address this problem, this research integrates natural language processing (NLP) and context-free grammar (CFG) to propose a novel generalized rule interpretation framework, which can parse regulatory text like a domain-specific language. First, a syntax tree structure with several semantic elements is proposed to represent the roles and relations of concepts in regulatory text. Second, a deep learning model with the transfer learning technique is utilized to label the semantic elements in a sentence. Finally, a set of CFGs is built to parse a labeled sentence into the language-independent tree structure, from which computable checking rules can be generated. Experimental results demonstrate our method outperforms the state-of-the-art methods: it achieves 99.6% and 91.0% accuracies for parsing single- and multi-requirement sentences, respectively, where the multi-requirement sentences are more complex and common but difficult for existing methods to deal with. This research contributes a method and framework for rule interpretation with both a high level of automation and wide scope of application, which can create computable rules from various textual regulatory documents. This research also publishes the first regulation dataset for future exploration, validation, and benchmarking in the ARC area. 

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2022-07-12-integrating-NLP-and-CFG-for-rule-interpretation-towards-ACC.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (No. 51908323, No. 72091512), the National Key R&D Program of China (No. 2018YFD1100900), and the Tsinghua University Initiative Scientific Research Program (No. 2019Z02UOT).