---
layout: default
title: "Horizon Summary: 2026-08-25 (ZH)"
date: 2026-08-25
lang: zh
---

> 从 122 条内容中筛选出 11 条重要资讯。

---

1. [使用 PostgreSQL、pgvector 和 Qwen3 构建最先进的混合搜索引擎](#item-1) ⭐️ 8.0/10
2. [Oxylabs 将代理基础设施定位为 Agentic AI 的核心要素](#item-2) ⭐️ 7.0/10
3. [Perplexity 发布用于计算机界面自动化的本地 AI 智能体](#item-3) ⭐️ 7.0/10
4. [如何自托管部署您自己的 AI 智能体指南](#item-4) ⭐️ 7.0/10
5. [Perplexity and NVIDIA team up to release a local AI agent - How-To Geek](#item-5) ⭐️ 7.0/10
6. [英伟达与 SpaceX 合作开发先进的智能体 AI 基础设施](#item-6) ⭐️ 7.0/10
7. [遥测管道如何控制 AI 代理的运营成本](#item-7) ⭐️ 7.0/10
8. [PPFAS GIFT 将标普 500 和纳斯达克 100 基金的最低投资额降至 500 美元](#item-8) ⭐️ 7.0/10
9. [面向主权 AI 的前沿模型持续学习技术报告](#item-9) ⭐️ 7.0/10
10. [苹果发布 M6 和 M5 Ultra 芯片，大幅提升人工智能计算性能](#item-10) ⭐️ 6.0/10
11. [日本将于十月起上调永久居留权申请费用](#item-11) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [使用 PostgreSQL、pgvector 和 Qwen3 构建最先进的混合搜索引擎](https://www.reddit.com/r/MachineLearning/comments/1vxyrsr/how_we_built_a_sota_search_engine_using/) ⭐️ 8.0/10

Papers with Code 团队实现了一个混合搜索系统，结合了传统的关键词搜索与使用 Qwen3-Embedding-0.6B 模型的语义向量搜索。该架构利用 PostgreSQL 的 pgvector 扩展，并结合 Hugging Face 的生态系统进行批量处理和推理。 这种方法为开发者提供了一个经济高效且可投入生产的蓝图，使其无需依赖昂贵的专有向量数据库服务即可实现高性能检索。它展示了如何有效集成开源工具，以提升技术内容平台中的搜索相关性。 该系统使用 NVIDIA L4 GPU 进行批量嵌入生成，并利用 Hugging Face 推理端点进行实时查询处理。通过结合词法和语义方法，该引擎实现了比单独使用任何一种方法更优越的检索性能。

reddit · r/MachineLearning · /u/NielsRogge · 8月25日 12:42

**背景**: 混合搜索是一种结合了基于关键词的搜索和语义向量搜索的信息检索技术，旨在提高整体相关性。PostgreSQL 是一款强大的关系型数据库，而 pgvector 是一个开源扩展，使其能够存储和查询高维向量嵌入，从而实现语义相似度搜索。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pgvector">Pgvector</a></li>
<li><a href="https://grokipedia.com/page/Hybrid_search">Hybrid search</a></li>
<li><a href="https://en.wikipedia.org/wiki/Text_embeddings">Text embeddings</a></li>

</ul>
</details>

**社区讨论**: 社区对这些实际的架构选择表现出了浓厚兴趣，特别是将轻量级的 Qwen3-Embedding-0.6B 模型用于生产环境搜索。讨论重点在于技术文档检索中模型大小与检索准确性之间的权衡。

**标签**: `#AI Productivity`, `#Vector Databases`, `#PostgreSQL`, `#Search Infrastructure`, `#Hybrid Search`

---

<a id="item-2"></a>
## [Oxylabs 将代理基础设施定位为 Agentic AI 的核心要素](https://news.google.com/rss/articles/CBMipAFBVV95cUxPUElYSVVsT19lanRUb2tJZy0wY1VjMzdSS3E4VTRoaVpjQTRQd1hmN0k5M0wtSGp6RUdOOWVqX3M4WldjYnJGV3paaURDVGFSNTRYaHdDVWNzN1NYVWJ1a2syTmdZVXQ0ekFPNVZPbWFmZG1tNUM1bndqR3RoR1RKSVBRZzdTUnhuRFVlSFpsc2tQMDhOd283bkQzZVYtbEJySFFQZA?oc=5) ⭐️ 7.0/10

Oxylabs 强调其网页抓取和代理基础设施是为自主 AI Agent 提供实时、可靠数据的关键层。这一整合旨在解决阻碍 AI Agent 有效执行研究或市场情报任务的数据获取瓶颈问题。 可靠的数据访问是 AI 系统进行自主决策的基础。通过提供稳定的代理基础设施，Oxylabs 使 AI Agent 能够绕过反爬虫限制并获取全球网络数据，从而显著提升 Agent 工作流的生产力和实用性。 该服务专注于大规模数据采集，提供代理管理功能，使 AI Agent 能够模拟人类浏览行为并避免 IP 被封禁。这确保了 Agent 能够在无需人工干预的情况下持续访问动态网页内容。

rss · AI Productivity and Monetization · 8月25日 21:09

**背景**: Agentic AI 指的是能够感知环境、进行推理并在无需持续人工监督的情况下执行复杂任务的自主系统。这些 Agent 通常需要从互联网获取海量的实时数据才能有效运作，因此强大的网页抓取和代理服务对其运行至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://mitsloan.mit.edu/ideas-made-to-matter/agentic-ai-explained">Agentic AI, explained | MIT Sloan</a></li>
<li><a href="https://www.ibm.com/think/topics/agentic-ai">What is Agentic AI? - IBM</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#Data Infrastructure`, `#Automation`, `#Web Scraping`

---

<a id="item-3"></a>
## [Perplexity 发布用于计算机界面自动化的本地 AI 智能体](https://news.google.com/rss/articles/CBMif0FVX3lxTE9pdExYeUM1ako3bXhhRjl1YU96dlJUb21Ea0ExX2JuQ3FUeTFkN3UzZFp3c3dKMUFSWE1hczk3amo5UlBGV3huTmhpck9aR1Z3LUNRWVVPcXpvRmxQS0ptSmUwUFBmdWZhTFZEQ282NnY0UVFxXzc5b0d4UUZ2ZUE?oc=5) ⭐️ 7.0/10

Perplexity 推出了一款全新的本地 AI 智能体，能够直接控制计算机界面以自动执行复杂的浏览器任务。该工具允许 AI 像人类一样与网页元素进行交互，从而简化了重复性的数字工作流程。 这一进展标志着 AI 从文本生成向主动任务执行的代理式工作流迈出了重要一步。通过自动化以往需要手动操作的多步骤流程，它为用户带来了显著的生产力提升。 该智能体在本地运行，通过减少向外部服务器传输敏感数据的需求，增强了隐私和安全性。用户在执行过程中应监控系统，以确保其在复杂浏览器环境下的稳定性和准确性。

rss · AI Productivity and Monetization · 8月25日 13:00

**背景**: 网页浏览器是一种通过从 Web 服务器检索文件来访问和查看网站的应用程序。AI 智能体是一类旨在通过感知环境并采取行动来实现特定目标的自主软件程序。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Web_browser">Web browser - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#Productivity`, `#Automation`, `#Perplexity`

---

<a id="item-4"></a>
## [如何自托管部署您自己的 AI 智能体指南](https://news.google.com/rss/articles/CBMickFVX3lxTFBoSEE2anphb2FOWVZZdm9lQ2hha0x2a2UzMlRZaWdhemhFejVVUnpWN0poNldBX1lzWE5sQkVWODg1NHN3YXNPVERfS2pyMm1aLVUxZkRxY3FhWjREM01xVUZWVXkwYVZYbFE0UTAyaU9LUQ?oc=5) ⭐️ 7.0/10

TechRadar 发布了一份详尽的指南，详细介绍了自托管 AI 智能体的流程、技术要求及优势。这种方法允许用户在自己的基础设施上运行 AI 工作流，而无需依赖第三方云服务。 自托管 AI 智能体能让用户更好地掌控数据隐私，消除对外部 API 速率限制的依赖，并规避潜在的内容审查。对于希望构建安全、长期且具有成本效益的自动化工作流的开发者和企业来说，这一点尤为重要。 该指南强调了对充足硬件资源（如高性能 GPU）的需求，以及选择合适的开源模型的重要性。它还指出了托管云 AI 服务的便利性与维护本地环境的技术复杂性之间的权衡。

rss · AI Productivity and Monetization · 8月25日 14:24

**背景**: AI 智能体是旨在感知环境、进行推理并自主执行多步任务以实现特定目标的软件系统。自托管是指在本地服务器或私有云基础设施上运行这些 AI 模型和智能体框架，从而使用户能够完全掌控软件栈和数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent - Wikipedia</a></li>
<li><a href="https://cloud.google.com/discover/what-are-ai-agents">What are AI agents ? Definition, examples, and types</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#Self-hosting`, `#Automation`, `#Productivity`, `#Privacy`

---

<a id="item-5"></a>
## [Perplexity and NVIDIA team up to release a local AI agent - How-To Geek](https://news.google.com/rss/articles/CBMihwFBVV95cUxNVW42SEZFMWNEdC1XZElHVXhaTkZiamhzQ2V6bUY3SkJEcG5pUllzQlNjNk9Zd0lnZm5qc2FNYnpBYUVuamRRRk5NdkxrZENzUEFKMHYxOEhjN0g5OXlQWTVySDRsM2NvM2tKVElYMzBUZ25Penl3b3MxMnhCaEpNNnBoemZINUk?oc=5) ⭐️ 7.0/10

Perplexity and NVIDIA have collaborated to release a local AI agent, enabling advanced AI capabilities to run directly on user hardware.

rss · AI Productivity and Monetization · 8月25日 18:50

**标签**: `#AI Agents`, `#NVIDIA`, `#Perplexity`, `#Local AI`, `#Productivity`

---

<a id="item-6"></a>
## [英伟达与 SpaceX 合作开发先进的智能体 AI 基础设施](https://news.google.com/rss/articles/CBMilgFBVV95cUxOc2hQRWwtSHkwSUxrNFQ1UGNXWlgtcm1BdU5SZG9KOENldnctT0c1VGJnRjlwXzkwOGo0QVhYY3pmUEhjMFBjV0RwY3NSSm5JdXI1d2E2NmRYWk5CZklsZ3JBSEpyU0hLTUpSa0NWajZXOHFZM3Z2TXc1SzMxaVJ2Q3AtVllhVFV1RkZEUldYcy1FSnBGcFE?oc=5) ⭐️ 7.0/10

英伟达与 SpaceX 宣布合作构建先进的智能体 AI 基础设施，重点在于扩展自主系统和工业 AI 能力。此次合作旨在将高性能计算与复杂的、以目标为导向的 AI 智能体进行深度集成。 此次合作标志着向大规模工业自动化迈出了重要一步，AI 系统不再局限于简单的聊天机器人，而是能够主动管理复杂的现实任务。它凸显了为高风险行业中的自主操作构建专用硬件和软件栈的重要性。 该计划专注于创建能够让 AI 智能体自主规划步骤、与现实工具交互并调整行动的基础设施。预计这一进展将通过减少对人工持续监督的需求，从而提高工业环境的效率。

rss · AI Productivity and Monetization · 8月25日 11:04

**背景**: 智能体 AI（Agentic AI）是指能够自主追求目标并采取行动的系统，这与仅生成响应的传统 AI 形成对比。AI 基础设施涵盖了在大规模环境下训练和部署这些复杂的、以目标为导向的系统所需的基础硬件和软件框架。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent - Wikipedia</a></li>
<li><a href="https://agentic.ai/what-is-agentic-ai">What Is Agentic AI? Definition, 6 Levels & Examples (2026)</a></li>
<li><a href="https://www.ibm.com/think/topics/agentic-ai">What is agentic AI ? - IBM</a></li>

</ul>
</details>

**标签**: `#AI Infrastructure`, `#Agentic AI`, `#NVIDIA`, `#SpaceX`, `#Industrial Automation`

---

<a id="item-7"></a>
## [遥测管道如何控制 AI 代理的运营成本](https://news.google.com/rss/articles/CBMiX0FVX3lxTE9zRFoxdWY0ZDN6RE5lbldzSUVTRHU3Vk41X01NYlZBbWZWRFh0OGo5cEU0NWFKenZLQXQ0MFZ4NHRUUGYxYWRiMVEyZ19aMUJNbm96WjlSaW96eWlxbDdj?oc=5) ⭐️ 7.0/10

遥测管道正被用于监控和管理与 AI 代理工作流相关的高额运营开支。通过部署这些管道，开发人员可以实时跟踪 Token 使用量和代理性能，从而优化成本。 随着 AI 代理变得越来越复杂，其不可预测的 Token 消耗可能导致不可持续的成本。通过遥测实现有效的可观测性，对于企业在保持性能的同时实现 AI 产品盈利化扩展至关重要。 遥测管道从代理交互中收集指标、日志和追踪信息，从而实现对工具使用和 LLM 调用的细粒度分析。这些数据使开发人员能够识别低效的工作流并实施成本优化措施。

rss · AI Productivity and Monetization · 8月25日 19:02

**背景**: 遥测是从分布式系统收集和传输数据以进行监控和分析的自动化过程。在 AI 背景下，可观测性帮助开发人员理解代理的非确定性行为，这些行为通常涉及多个工具调用和复杂的推理步骤，使用传统软件方法很难进行调试。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/telemetry">What is telemetry ? - IBM</a></li>
<li><a href="https://www.ibm.com/think/insights/ai-agent-observability">Why observability is essential for AI agents | IBM</a></li>
<li><a href="https://www.langchain.com/resources/agent-observability">AI Agent Observability: Tracing, Testing, and Improving Agents</a></li>

</ul>
</details>

**标签**: `#AI Productivity`, `#Agentic Workflows`, `#Cost Optimization`, `#AI Infrastructure`

---

<a id="item-8"></a>
## [PPFAS GIFT 将标普 500 和纳斯达克 100 基金的最低投资额降至 500 美元](https://news.google.com/rss/articles/CBMi3AFBVV95cUxQLTRRSWRQay04X0wyME50T2ZJVXN0bkVWdWF2UldLM040Qmdwc3JmY0hwX05pT2FZWmdXSUNicG8wQVprejM1SDV5QkJFV3pab0dOcUhxSURRMTdoc3VmNlRzLVhJWDBBdHM4a01NNDBwMHV5UmZwN2tIeENwMU5tMW9LVEJUZXBXd2hKRFk3U0liNnZsbE5WVk41WVlVUnpQajVrQkRhcFA3X3o3YXNpMzU2bXFZRHRkMUtKdUNYaGhxcF9aR2RGbzVUQjdueExqWVJzMXhITU5Yc0NE?oc=5) ⭐️ 7.0/10

PPFAS GIFT 已正式将其标普 500 和纳斯达克 100 指数基金的最低投资门槛从 5000 美元下调至 500 美元。这一调整使得散户投资者通过 GIFT City 平台参与国际指数基金变得更加容易。 此次下调将资本门槛降低了 90%，使印度投资者能够更广泛地接触全球股票市场。这符合散户投资者对多元化国际资产配置日益增长的需求。 较低的门槛专门适用于通过 GIFT City 国际金融服务中心提供的基金。投资者应注意，此举旨在吸引小额资金，同时保持对美国主要指数的投资敞口。

rss · QQQ and Nasdaq 100 · 8月25日 19:35

**背景**: GIFT City（古吉拉特国际金融科技城）是印度的一个国际金融服务中心，允许国内和外国投资者在国际市场进行交易。国际指数基金使投资者能够在无需直接购买个股的情况下，获得对外国股市表现（如美国的标普 500 和纳斯达克 100 指数）的投资敞口。

**标签**: `#Nasdaq-100`, `#Investment`, `#GIFT City`, `#Asset Allocation`, `#ETF`

---

<a id="item-9"></a>
## [面向主权 AI 的前沿模型持续学习技术报告](https://www.reddit.com/r/MachineLearning/comments/1vxvzju/continual_learning_of_frontier_models_for/) ⭐️ 7.0/10

Thomson 1.0 技术报告提出了一种方法论，使机构能够通过对开源权重模型进行持续学习，实现前沿水平的 AI 性能。这种方法使组织能够构建并维护强大的 AI 能力，而无需依赖中心化的闭源提供商。 该框架通过使更多参与者能够掌控其 AI 基础设施、数据隐私和价值观，从而推动了主权 AI 的发展。它通过降低前沿模型通常所需的高额计算和人力成本，显著降低了高风险专业 AI 应用的准入门槛。 Thomson 模型展示了一种“π型”性能模式，在多个领域实现了广泛的能力提升，同时有效缓解了灾难性遗忘问题。该方法论侧重于对参数进行高影响力的干预，以在训练过程中保持模型的稳定性和可塑性。

reddit · r/MachineLearning · /u/Forsaken_Scientist · 8月25日 10:30

**背景**: 主权 AI 是指组织独立开发、部署和管理其 AI 系统的能力，以避免对外部提供商的依赖。持续学习是一种使模型能够按顺序适应新数据或任务，同时不丢失先前习得知识的范式，旨在解决静态预训练的局限性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2603.12658">[2603.12658] Beyond Static Models: An Evolving Framework for Continual Learning in Large Language Models across Training Stages</a></li>
<li><a href="https://dl.acm.org/doi/10.1145/3735633">Continual Learning of Large Language Models: A Comprehensive Survey | ACM Computing Surveys</a></li>
<li><a href="https://www.solarwinds.com/blog/open-source-llms-vs-open-weight-llms-vs-proprietary-llms">Open Source LLMs vs Open Weight LLMs vs Proprietary LLMs - SolarWinds Blog</a></li>

</ul>
</details>

**标签**: `#SovereignAI`, `#OpenWeights`, `#ContinualLearning`, `#AIInfrastructure`, `#Productivity`

---

<a id="item-10"></a>
## [苹果发布 M6 和 M5 Ultra 芯片，大幅提升人工智能计算性能](https://www.apple.com/newsroom/2026/08/apple-introduces-m6-and-m5-ultra-for-a-big-leap-in-performance-and-ai-compute/) ⭐️ 6.0/10

苹果正式推出了 M6 和 M5 Ultra 芯片，旨在为人工智能密集型任务提供显著的性能提升。这些新处理器是苹果自研芯片系列的最新迭代，重点强化了高端计算能力。 这些芯片为个人电脑上的本地人工智能处理树立了新标杆，使专业用户能够处理复杂的工作负载，而无需完全依赖云端基础设施。此次发布巩固了苹果在高性能硬件市场保持竞争优势的决心。 M5 Ultra 支持海量内存配置，高端机型内存可达 256GB，并有望在未来支持 512GB。然而，这些大内存配置的价格非常昂贵，完全配置的工作站价格往往超过 18,000 美元。

hackernews · interpol_p · 8月25日 13:01 · [社区讨论](https://news.ycombinator.com/item?id=49433292)

**背景**: Apple Silicon 是一系列基于 ARM 架构的片上系统（SoC）设计，将 CPU、GPU 和神经网络引擎集成在单一封装中。其中的“Ultra”版本通常利用苹果的 UltraFusion 技术将两块高端芯片互联，从而为要求苛刻的专业工作负载实现性能翻倍。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Apple_silicon">Apple silicon - Wikipedia</a></li>
<li><a href="https://www.apple.com/newsroom/2022/03/apple-unveils-m1-ultra-the-worlds-most-powerful-chip-for-a-personal-computer/">Apple unveils M1 Ultra, the world’s most powerful chip for a personal computer - Apple</a></li>

</ul>
</details>

**社区讨论**: 社区用户对性能提升印象深刻，但对高内存配置的高昂价格表示担忧。一些用户还对未来的产品路线图进行了猜测，包括有传言称苹果可能会跳过某些 M6 变体，以优先开发 M7 芯片。

**标签**: `#Apple`, `#Hardware`, `#AI Compute`, `#Productivity`, `#Semiconductors`

---

<a id="item-11"></a>
## [日本将于十月起上调永久居留权申请费用](https://news.google.com/rss/articles/CBMiX0FVX3lxTE5qamxSQzIyNjYzUURVZkh0VFZYU29RVnNpMUtjNC1aRE1tRGV0Z3NFd1N3VVVKVkFheTIxd3FjZWVuQ3hfMzljSzd3OVFQdjVlSF8yM2lfUDlaQ1NvS3A0?oc=5) ⭐️ 6.0/10

日本政府宣布将从十月起上调永久居留权申请费用。此次调整是日本移民服务相关行政费用整体更新的一部分。 这一变化直接影响了计划在日本长期定居的外国公民，申请人需要据此调整申请过程的财务预算。这也反映了日本政府在管理移民系统行政成本方面的持续举措。 申请人应在十月提交材料前做好应对新收费标准的准备，以避免处理延迟。具体的费用金额将根据新的政府法规进行更新。

rss · Global Mobility and Residency · 8月25日 14:47

**背景**: 日本永久居留权允许外国公民无限期在日本居住和工作，无需续签签证。申请过程非常严格，要求申请人在居住时长、财务稳定性和法律合规性方面满足特定标准。

**标签**: `#Japan`, `#Permanent Residency`, `#Global Mobility`, `#Immigration Policy`

---