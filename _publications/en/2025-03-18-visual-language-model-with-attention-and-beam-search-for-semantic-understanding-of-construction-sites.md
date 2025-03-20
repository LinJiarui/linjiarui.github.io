---
title: "Enabling High-Level Worker-Centric Semantic Understanding of Onsite Images Using Visual Language Models with Attention Mechanism and Beam Search Strategy"
lang: en
ref: publications/2025-03-18-visual-language-model-with-attention-and-beam-search-for-semantic-understanding-of-construction-sites
collection: publications
permalink: /en/publications/2025-03-18-visual-language-model-with-attention-and-beam-search-for-semantic-understanding-of-construction-sites
excerpt: 'Aiming at the semantic understanding of construction scenes, this study constructed an open image-text dataset SODA-ktsh including 16 common scenes, and developed a large visual language model that integrates the attention mechanism and the beam search strategy. BLEU-4 score, CIDEr score and ROUGE_L score of the develop VLM are 0.7464, 5.0255 and 0.8106 respectively, showing strong generalization, perception and recognition capabilities, which is very suitable for explaining and analyzing complex construction scenes.'
date: 2025-03-18
venue: 'Buildings'
doi: '10.3390/buildings15060959'
paperurl: 'http://doi.org/10.3390/buildings15060959'
citation: 'Deng, H., Fu, K., Yu B., Li, H., Duan, R., Deng, Y.*, Lin, J.R. (2025). Enabling High-Level Worker-Centric Semantic Understanding of Onsite Images Using Visual Language Models with Attention Mechanism and Beam Search Strategy. <i>Buildings</i>, 15(6), 959. doi: 10.3390/buildings15060959'

comment: true
category: journal

tags: 
  - visual language model
  - construction
  - scene understanding
  - image captioning
  - attention mechanism
  - LLM
  - CV
  - computer vision
  - SCI

grants:
  - 52308314
  - 2023A1515030169
---

{{site.data.ui-text[page.lang].abstract}}
====

Visual information is becoming increasingly essential in construction management. However, a significant portion of this information remains underutilized by construction managers due to the limitations of existing image processing algorithms. These algorithms primarily rely on low-level visual features and struggle to capture high-order semantic information, leading to a gap between computer-generated image semantics and human interpretation. However, current research lacks a comprehensive justification for the necessity of employing scene understanding algorithms to address this issue. Moreover, the absence of large-scale, high-quality open-source datasets remains a major obstacle, hindering further research progress and algorithmic optimization in this field. To address this issue, this paper proposes a construction scene visual language model based on attention mechanism and encoder–decoder architecture, with the encoder built using ResNet101 and the decoder built using LSTM (long short-term memory). The addition of the attention mechanism and beam search strategy improves the model, making it more accurate and generalizable. To verify the effectiveness of the proposed method, a publicly available construction scene visual-language dataset containing 16 common construction scenes, SODA-ktsh, is built and verified. The experimental results demonstrate that the proposed model achieves a BLEU-4 score of 0.7464, a CIDEr score of 5.0255, and a ROUGE_L score of 0.8106 on the validation set. These results indicate that the model effectively captures and accurately describes the complex semantic information present in construction images. Moreover, the model exhibits strong generalization, perceptual, and recognition capabilities, making it well suited for interpreting and analyzing intricate construction scenes.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-03-18-visual-language-model-with-attention-and-beam-search-for-semantic-understanding-of-construction-sites.pdf)

The authors would like to acknowledge the support by the National Science Foundation of China (52308314) and the support by Guangdong Basic and Applied Basic Research Foundation (2023A1515030169).