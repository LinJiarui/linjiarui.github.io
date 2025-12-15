---
title: "Enabling High-Level Worker-Centric Semantic Understanding of Onsite Images Using Visual Language Models with Attention Mechanism and Beam Search Strategy"
lang: zh
ref: publications/2025-03-18-visual-language-model-with-attention-and-beam-search-for-semantic-understanding-of-construction-sites
collection: publications
permalink: /publications/2025-03-18-visual-language-model-with-attention-and-beam-search-for-semantic-understanding-of-construction-sites
excerpt: '本研究针对建设场景语义理解，构建了包括16个常见场景的开放图像-文本数据集SODA-ktsh，研发了融合注意力机制与集束搜索策略的视觉语言大模型，其BLEU-4 得分、CIDEr得分及ROUGE_L得分分别为0.7464、5.0255和0.8106，表现出强大的泛化、感知和识别能力，非常适合解释和分析复杂的建筑场景'
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

视觉信息在建设管理中的重要性日益凸显，然而，受制于现有图像处理算法的局限性，很大一部分视觉信息未被工程管理者充分利用。这些算法主要依赖低级视觉特征，难以捕捉高阶语义信息，导致计算机生成的图像语义与人类理解之间存在差距。然而，目前的研究缺乏使用场景理解算法解决这一问题的全面论证。此外，缺乏大规模、高质量的开源数据集仍然是阻碍该领域进一步研究进展和算法优化的主要障碍。针对这一问题，本文提出了一种基于注意力机制和编码器-解码器架构的建设场景视觉语言模型，编码器采用ResNet101，解码器采用LSTM（长短期记忆）构建。注意力机制和集束搜索策略的加入改进了模型，使其更加准确和具有泛化能力。为了验证所提方法的有效性，构建并验证了一个包含16个常见建筑场景的公开建筑场景视觉语言数据集SODA-ktsh。实验结果表明，所提出的模型在验证集上的 BLEU-4 得分为 0.7464、CIDEr 得分为 5.0255、ROUGE_L 得分为 0.8106。这些结果表明，该模型能够有效捕捉并准确描述建筑图像中存在的复杂语义信息。此外，该模型表现出强大的泛化、感知和识别能力，非常适合解释和分析复杂的建筑场景。

Visual information is becoming increasingly essential in construction management. However, a significant portion of this information remains underutilized by construction managers due to the limitations of existing image processing algorithms. These algorithms primarily rely on low-level visual features and struggle to capture high-order semantic information, leading to a gap between computer-generated image semantics and human interpretation. However, current research lacks a comprehensive justification for the necessity of employing scene understanding algorithms to address this issue. Moreover, the absence of large-scale, high-quality open-source datasets remains a major obstacle, hindering further research progress and algorithmic optimization in this field. To address this issue, this paper proposes a construction scene visual language model based on attention mechanism and encoder–decoder architecture, with the encoder built using ResNet101 and the decoder built using LSTM (long short-term memory). The addition of the attention mechanism and beam search strategy improves the model, making it more accurate and generalizable. To verify the effectiveness of the proposed method, a publicly available construction scene visual-language dataset containing 16 common construction scenes, SODA-ktsh, is built and verified. The experimental results demonstrate that the proposed model achieves a BLEU-4 score of 0.7464, a CIDEr score of 5.0255, and a ROUGE_L score of 0.8106 on the validation set. These results indicate that the model effectively captures and accurately describes the complex semantic information present in construction images. Moreover, the model exhibits strong generalization, perceptual, and recognition capabilities, making it well suited for interpreting and analyzing intricate construction scenes.

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2025-03-18-visual-language-model-with-attention-and-beam-search-for-semantic-understanding-of-construction-sites.pdf)

The authors would like to acknowledge the support by the National Science Foundation of China (52308314) and the support by Guangdong Basic and Applied Basic Research Foundation (2023A1515030169).