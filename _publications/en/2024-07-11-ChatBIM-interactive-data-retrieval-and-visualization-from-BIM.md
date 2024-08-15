---
title: "ChatBIM: Interactive Data Retrieval and Visualization from BIM"
lang: en
ref: publications/2024-07-11-ChatBIM-interactive-data-retrieval-and-visualization-from-BIM
collection: publications
permalink: /en/publications/2024-07-11-ChatBIM-interactive-data-retrieval-and-visualization-from-BIM
excerpt: 'This paper briefly introduces the BIM data intelligent extraction and visualization method proposed by the authors, which can automatically understand user text or voice input via LLM, achieving automatic BIM data extraction and acquisition of construction status.'
date: 2024-07-11
venue: 'the 10th International Conference on Innovative Production and Construction 
(IPC 2024)'
doi: 10.13140/RG.2.2.31563.20006
paperurl: 'https://doi.org/10.13140/RG.2.2.31563.20006'
citation: 'Lin, J.R.*, Chen, K.Y., Pang, P., Wu, D.P., Zhang, J.P. (2024). ChatBIM: Interactive Data Retrieval and Visualization from BIM. <i> the 10th International Conference on Innovative Production and Construction (IPC 2024)</i>, 265-266. Perth, Australia.'

comment: true
category: conference

tags: 
  - LLM
  - large language model
  - BIM
  - human-computer interaction
  - data retrieval
  - NLP
  - natural language processing

grants:
  - 2023YFC3804600
---


{{site.data.ui-text[page.lang].abstract}}
====

Building Information Modeling (BIM) has become a cornerstone technology for the digital transformation of the construction industry, facilitating multi-disciplinary data integration and sharing throughout the building life cycle. However, the increasing complexity of BIM systems and user interfaces has resulted in increased learning costs and reduced design and decision-making efficiency. To address this challenge, we propose to integrate our previous works as an interactive AI assistant, ChatBIM, which supports intelligent data retrieval and visualization through voice- or text-based interactions. Here we introduce our early attempt based on traditional Natural Language Processing (NLP) techniques and its improvement based on deep learning and Large Language Models (LLMs). 

Our first attempt is developed a decade ago based on NLP. To understanding textual user input, NLP techniques including word segmentation, tagging, and syntactic analysis are utilized, to recognize key objects (e.g., beams, walls, etc.) by detecting noun phrases and their relations with dependency parsing. Then, International Framework for Dictionaries (IFD), which links concepts in different CAD systems are used to map recognized objects to data entities in Industry Foundations Classes (IFC). IFD is also further extended to include synonyms, alias, abbreviations of the same concept for better mapping accuracy. After that, database queries are generated based on graph pathing searching in IFC data scheme. Finally, executing the queries produces the required data of the users, and a few rule templates are predefined for the visualization of the retrieved data, for example, data series should be visualized in tables or charts, and building elements should be visualized in 3D view and colored according to their categories. Integrating all the steps together creates an AI assistant that could filter user concerned BIM objects and aggregates the properties (e.g., quantities, costs, construction progresses, etc.) of retrieved BIM objects for better decision-making. 

With recent development of LLMs, we rebuilt the AI assistant based on a Domain-Specific LLM (DS-LLM). First of all, we further pretrained the DS-LLM by collecting plenty of domain documents and further fine-tuning an open-sourced foundation LLM. After that, user inputs in texts or voices could be understood via the developed DS-LLM with a higher accuracy than before. The key objects expressed in various words could be detected and linked with concepts in the data model, even if they are not in a standard form. Also, Retrieval Augmented Generation (RAG) is adopted to create a more natural response to the users. 

With the above-mentioned approaches, a prototype software system as well as a prototype hardware called ChaoXi Screen are developed and verified in a few cases. Results show that the proposed method is easy to learn, and provides an intuitive way for the construction managers and decision makers. It would also be a promising way for future developing future human-computer interface in a new era for AI and metaverse. 

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2024-07-11-ChatBIM-interactive-data-retrieval-and-visualization-from-BIM.pdf)

The authors are grateful for the financial support of the National Key R&D Program of China (Grant No. 2023YFC3804600).