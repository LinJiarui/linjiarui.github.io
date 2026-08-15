---
title: "BIM Design Assistant Driven by LLM Agents"
lang: en
ref: publications/2026-06-22-BIM-design-assistant-driven-by-LLM-agents
collection: publications
permalink: /en/publications/2026-06-22-BIM-design-assistant-driven-by-LLM-agents
excerpt: 'This paper presents a BIM design assistant driven by LLM agents, enabling natural-language-based assistance for BIM design and visualization tasks through reliable tool invocation.'
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

BIM design workflows involve complex, multi-step interactions with professional software, which limit the direct applicability of large language models (LLMs). This paper presents a BIM design assistant driven by LLM agents, enabling natural-language-based assistance for BIM design and visualization tasks through reliable tool invocation. First, a two-layer Revit interface function library is designed to bridge LLM agents and BIM software, providing secure, extensible, and fine-grained model manipulation capabilities. Based on the ReAct paradigm, an agent framework is developed that integrates dialogue history management, structured prompt engineering, and step-by-step reasoning to support long-horizon and multi-turn BIM tasks. To evaluate the proposed system, an agent-oriented BIM task benchmark is constructed, covering information querying, model visualization, component modification, and deletion, with tasks further categorized by difficulty. Experimental results with three representative LLMs show that high-performance general-purpose models can reliably act as BIM design assistants within the proposed framework, achieving up to 90% task accuracy. These results demonstrate the feasibility and reliability of LLM-agent-driven BIM design assistance in practical scenarios.

![graphical abstract](/images/2026-06-22-BIM-design-assistant-driven-by-LLM-agents-ga.jpg)

[{{site.data.ui-text[page.lang].download_paper}}]({{page.paperurl}})

[{{site.data.ui-text[page.lang].download_preprint}}]({{ site.baseurl }}/files/2026-06-22-BIM-design-assistant-driven-by-LLM-agents.pdf)

The authors are grateful for the financial support received from the National Natural Science Foundation of China (No. 52378306). 