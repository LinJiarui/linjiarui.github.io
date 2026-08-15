---
title: "BIM Design Assistant Driven by LLM Agents"
lang: zh
ref: publications/2026-06-22-BIM-design-assistant-driven-by-LLM-agents
collection: publications
permalink: /publications/2026-06-22-BIM-design-assistant-driven-by-LLM-agents
excerpt: '本研究基于大模型智能体框架，研发了BIM智能设计助手及其任务评测基准，支持BIM数据查询、可视化、构件编辑等多场景任务'
date: 2026-06-22
venue: '2026 Proceedings of the 43rd ISARC'
doi: '10.22260/ISARC2026/0227'
paperurl: 'http://doi.org/10.22260/ISARC2026/0227'
citation: 'Han, J., Zhou, B.S.N., Lu, X.Z., Hu, Z.Z., Ma, J., Lin, J.R.* (2026). BIM Design Assistant Driven by LLM Agents. <i>2026 Proceedings of the 43rd ISARC</i>, 1777-1784. Singapore. doi: 10.22260/ISARC2026/0227'

comment: true
category: conference

tags: 
  - BIM
  - LLM
  - Agent
  - Intelligent Design
  - Design Assistant
  - ReAct
  - Revit

grants:
  - 52378306
---

{{site.data.ui-text[page.lang].abstract}}
====

BIM 设计流程需与专业软件开展复杂多步交互，限制了大语言模型（LLM）的直接应用。本文提出基于大语言模型智能体的 BIM 设计助手，通过可靠的工具调用实现 BIM 设计与可视化任务的自然语言辅助。首先构建双层 Revit 接口函数库，打通大模型智能体与 BIM 软件，提供安全、可扩展、细粒度的模型操作能力。基于 ReAct 范式搭建智能体框架，融合对话历史管理、结构化提示工程与分步推理，支持长周期、多轮 BIM 任务。为评估该系统，构建面向智能体的 BIM 任务基准数据集，涵盖信息查询、模型可视化、构件修改与删除，并按难度划分任务等级。基于三类主流大语言模型开展实验，结果表明高性能通用大模型可在本框架下胜任 BIM 设计助手，任务准确率最高可达 90%，验证了大模型智能体驱动 BIM 设计辅助在实际场景中的可行性与可靠性。（AI自动翻译）

BIM design workflows involve complex, multi-step interactions with professional software, which limit the direct applicability of large language models (LLMs). This paper presents a BIM design assistant driven by LLM agents, enabling natural-language-based assistance for BIM design and visualization tasks through reliable tool invocation. First, a two-layer Revit interface function library is designed to bridge LLM agents and BIM software, providing secure, extensible, and fine-grained model manipulation capabilities. Based on the ReAct paradigm, an agent framework is developed that integrates dialogue history management, structured prompt engineering, and step-by-step reasoning to support long-horizon and multi-turn BIM tasks. To evaluate the proposed system, an agent-oriented BIM task benchmark is constructed, covering information querying, model visualization, component modification, and deletion, with tasks further categorized by difficulty. Experimental results with three representative LLMs show that high-performance general-purpose models can reliably act as BIM design assistants within the proposed framework, achieving up to 90% task accuracy. These results demonstrate the feasibility and reliability of LLM-agent-driven BIM design assistance in practical scenarios.

报告视频可在[这里](https://www.youtube.com/watch?v=N1OH62XSPYA)观看。

![graphical abstract](/images/2026-06-22-BIM-design-assistant-driven-by-LLM-agents-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2026-06-22-BIM-design-assistant-driven-by-LLM-agents.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (No. 52378306). 