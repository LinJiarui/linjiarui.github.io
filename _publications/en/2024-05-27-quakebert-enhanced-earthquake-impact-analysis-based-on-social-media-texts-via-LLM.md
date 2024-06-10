---
title: "Enhanced Earthquake Impact Analysis based on Social Media Texts via Large Language Model"
lang: en
ref: publications/2024-05-27-quakebert-enhanced-earthquake-impact-analysis-based-on-social-media-texts-via-LLM
collection: publications
permalink: /en/publications/2024-05-27-quakebert-enhanced-earthquake-impact-analysis-based-on-social-media-texts-via-LLM
excerpt: 'This study proposes the first domain-specific LLM model and an integrated method for rapid earthquake impact assessment, which can effectively enhance the impact assessment process by accurate detection of noisy microblogs, therefore enabling effective post-disaster emergency responses.'
date: 2024-05-27
venue: 'International Journal of Disaster Risk Reduction'
doi: '10.1016/j.ijdrr.2024.104574'
paperurl: 'http://doi.org/10.1016/j.ijdrr.2024.104574'
citation: 'Han, J., Zheng, Z., Lu, X.Z., Chen, K.Y., Lin, J.R.* (2024). Enhanced Earthquake Impact Analysis based on Social Media Texts via Large Language Model. <i>International Journal of Disaster Risk Reduction</i>, 109, 104574. doi: 10.1016/j.ijdrr.2024.104574'

comment: true
category: journal

tags: 
  - LLM
  - earthquake
  - impact assessment
  - text mining
  - social media
  - BERT
  - social impact
  - large language model
  - SCI

grants:
  - 52238011
  - 52378306
  - 72091512
  - xplorize
---


{{site.data.ui-text[page.lang].abstract}}
====

Social media aids disaster response but suffers from noise, hindering accurate impact assessment and decision making for resilient cities, which few studies considered. To address the problem, this study proposes the first domain-specific LLM model and an integrated method for rapid earthquake impact assessment. First, a few categories are introduced to classify and filter microblogs considering their relationship to the physical and social impacts of earthquakes, and a dataset comprising 7282 earthquake-related microblogs from twenty earthquakes in different locations is developed as well. Then, with a systematic analysis of various influential factors, QuakeBERT, a domain-specific large language model (LLM), is developed and fine-tuned for accurate classification and filtering of microblogs. Meanwhile, an integrated method integrating public opinion trend analysis, sentiment analysis, and keyword-based physical impact quantification is introduced to assess both the physical and social impacts of earthquakes based on social media texts. Experiments show that data diversity and data volume dominate the performance of QuakeBERT and increase the macro average F1 score by 27%, while the best classification model QuakeBERT outperforms the CNN- or RNN-based models by improving the macro average F1 score from 60.87% to 84.33%. Finally, the proposed approach is applied to assess two earthquakes with the same magnitude and focal depth. Results show that the proposed approach can effectively enhance the impact assessment process by accurate detection of noisy microblogs, which enables effective post-disaster emergency responses to create more resilient cities.


![graphical abstract](/images/2024-05-27-quakebert-enhanced-earthquake-impact-analysis-based-on-social-media-texts-via-LLM-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2024-05-27-quakebert-enhanced-earthquake-impact-analysis-based-on-social-media-texts-via-LLM.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (No. 52238011, 52378306, 72091512) and the Tencent Foundation through the XPLORER PRIZE.