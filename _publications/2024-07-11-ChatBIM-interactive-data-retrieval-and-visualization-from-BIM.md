---
title: "ChatBIM: Interactive Data Retrieval and Visualization from BIM"
lang: zh
ref: publications/2024-07-11-ChatBIM-interactive-data-retrieval-and-visualization-from-BIM
collection: publications
permalink: /publications/2024-07-11-ChatBIM-interactive-data-retrieval-and-visualization-from-BIM
excerpt: '本论文简要介绍了作者团队引入LLM等自然语言处理技术提出的BIM数据智能提取与可视化方法，可自动理解用户文本或语音输入，实现BIM数据自动提资、施工状态对话式获取等功能，实现了更加自然的人机交互对话'
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

建筑信息模型 (BIM) 已成为建筑行业数字化转型的基础支撑技术，促进了整个建筑生命周期中的多专业数据集成和共享。然而，BIM 系统和用户界面日益复杂，导致学习成本增加，设计和决策效率降低。为了应对这一挑战，团队将有关研究成果整合为了一个交互式人工智能助手 ChatBIM，它支持通过语音或基于文本的交互进行智能数据检索和可视化。这里我们介绍了我们基于传统自然语言处理 (NLP) 技术的早期探索，以及基于深度学习和大型语言模型 (LLM) 的改进方案。

作者团队最早于2013年开始探索基于NLP的BIM数据提取与可视化方案。为了理解文本用户输入，我们利用包括分词、标记和句法分析在内的 NLP 技术，通过检测名词短语及其与依存关系解析的关系来识别关键对象（例如，梁、墙等）。然后，使用国际词典框架 (IFD)（它将不同 CAD 系统中的概念联系起来）将识别的对象映射到工业基础类 (IFC) 中的数据实体。IFD 还进一步扩展为包括同义词、别名、同一概念的缩写，以提高映射精度。之后，基于 IFC 数据方案中的图形路径搜索生成数据库查询。最后，执行查询会产生用户所需的数据，并预定义一些规则模板以可视化检索到的数据，例如，数据系列应以表格或图表的形式可视化，建筑元素应以 3D 视图的形式可视化并根据其类别着色。将所有步骤集成在一起，创建了一个 AI 助手，它可以过滤用户关注的 BIM 对象并汇总检索到的 BIM 对象的属性（例如数量、成本、施工进度等），以便做出更好的决策。


随着 LLM 的最新发展，我们基于领域特定 LLM (DS-LLM) 重建了 AI 助手。首先，我们通过收集大量领域文档和进一步微调开源基础 LLM 进一步对 DS-LLM 进行预训练。之后，通过开发的 DS-LLM，可以比以前更准确地理解用户以文本或语音形式输入的内容。即使用户采用口语、不专业术语等表述方式，本方法也可以准确识别用户所关系的关键对象并将其与数据模型中的概念联系起来。此外，还采用了检索增强生成 (RAG) 来为用户创建更自然的系统响应。

通过上述方法，笔者团队开发了一个原型软件系统以及名为潮汐屏的硬件产品，并在多个工程中进行了应用验证。结果表明，所提出的方法易于学习，并为施工经理和决策者提供了一种直观的方法。这也将是未来在人工智能和元宇宙的新时代开发未来人机界面的一种有前途的方法。

Building Information Modeling (BIM) has become a cornerstone technology for the digital transformation of the construction industry, facilitating multi-disciplinary data integration and sharing throughout the building life cycle. However, the increasing complexity of BIM systems and user interfaces has resulted in increased learning costs and reduced design and decision-making efficiency. To address this challenge, we propose to integrate our previous works as an interactive AI assistant, ChatBIM, which supports intelligent data retrieval and visualization through voice- or text-based interactions. Here we introduce our early attempt based on traditional Natural Language Processing (NLP) techniques and its improvement based on deep learning and Large Language Models (LLMs). 

Our first attempt is developed a decade ago based on NLP. To understanding textual user input, NLP techniques including word segmentation, tagging, and syntactic analysis are utilized, to recognize key objects (e.g., beams, walls, etc.) by detecting noun phrases and their relations with dependency parsing. Then, International Framework for Dictionaries (IFD), which links concepts in different CAD systems are used to map recognized objects to data entities in Industry Foundations Classes (IFC). IFD is also further extended to include synonyms, alias, abbreviations of the same concept for better mapping accuracy. After that, database queries are generated based on graph pathing searching in IFC data scheme. Finally, executing the queries produces the required data of the users, and a few rule templates are predefined for the visualization of the retrieved data, for example, data series should be visualized in tables or charts, and building elements should be visualized in 3D view and colored according to their categories. Integrating all the steps together creates an AI assistant that could filter user concerned BIM objects and aggregates the properties (e.g., quantities, costs, construction progresses, etc.) of retrieved BIM objects for better decision-making. 

With recent development of LLMs, we rebuilt the AI assistant based on a Domain-Specific LLM (DS-LLM). First of all, we further pretrained the DS-LLM by collecting plenty of domain documents and further fine-tuning an open-sourced foundation LLM. After that, user inputs in texts or voices could be understood via the developed DS-LLM with a higher accuracy than before. The key objects expressed in various words could be detected and linked with concepts in the data model, even if they are not in a standard form. Also, Retrieval Augmented Generation (RAG) is adopted to create a more natural response to the users. 

With the above-mentioned approaches, a prototype software system as well as a prototype hardware called ChaoXi Screen are developed and verified in a few cases. Results show that the proposed method is easy to learn, and provides an intuitive way for the construction managers and decision makers. It would also be a promising way for future developing future human-computer interface in a new era for AI and metaverse. 

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2024-07-11-ChatBIM-interactive-data-retrieval-and-visualization-from-BIM.pdf)

The authors are grateful for the financial support of the National Key R&D Program of China (Grant No. 2023YFC3804600).