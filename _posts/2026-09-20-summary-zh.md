---
layout: default
title: "Horizon Summary: 2026-09-20 (ZH)"
date: 2026-09-20
lang: zh
---

> 从 52 条内容中筛选出 10 条重要资讯。

---

1. [ProgramAsWeights：将英语描述编译为本地可执行的神经程序](#item-1) ⭐️ 8.0/10
2. [Atlassian 将 Jira 升级为 AI 驱动的编码指挥中心](#item-2) ⭐️ 7.0/10
3. [代理式 AI 迎来关键缺失层：市场准入](#item-3) ⭐️ 7.0/10
4. [Meta 发布 Muse for Mac：一款用于本地生产力的个人 AI 智能体](#item-4) ⭐️ 7.0/10
5. [为何 2 倍杠杆的 QLD 在市场崩盘时表现优于 3 倍杠杆的 TQQQ](#item-5) ⭐️ 7.0/10
6. [开发者分享了为期五个月的全面机器学习学习路线图](#item-6) ⭐️ 7.0/10
7. [PlanetScale 推出用于 Postgres 全文搜索的 'Tin'](#item-7) ⭐️ 6.0/10
8. [评估人工智能代理的自主权与决策权限](#item-8) ⭐️ 6.0/10
9. [AI 智能体技能成为关键的供应链攻击载体](#item-9) ⭐️ 6.0/10
10. [AMD EPYC 处理器现已针对全周期智能体 AI 工作流进行优化](#item-10) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [ProgramAsWeights：将英语描述编译为本地可执行的神经程序](https://www.reddit.com/r/MachineLearning/comments/1wl13eu/programasweights_compile_english_function/) ⭐️ 8.0/10

ProgramAsWeights (PAW) 是一个开源工具，它通过为小型冻结解释器模型生成特定任务的 LoRA 适配器，将自然语言规范编译为可重用的神经程序。这使用户能够在 CPU 等硬件上本地运行 AI 定义的功能，而无需调用外部 API。 这种方法通过将一次性的编译成本与重复的本地推理分离，实现了高效、私密且经济的 AI 集成。它使开发人员能够部署 AI 驱动的任务，而无需承担持续的云服务费用或担心数据隐私问题。 该系统使用微调后的 Qwen3-4B 编译器为 0.6B 参数的解释器生成适配器，在 FuzzyBench 数据集上达到了 73.4% 的准确率。用户还可以通过“编译即训练”（Compile by Training）功能，对生成的适配器进行 100 步微调，从而进一步提升性能。

reddit · r/MachineLearning · /u/yuntiandeng · 9月19日 23:35

**背景**: 神经程序合成通常涉及根据自然语言指令生成执行特定任务的代码或模型。LoRA（低秩自适应）是一种通过在模型层中注入小型、可训练的秩分解矩阵，同时保持基础权重冻结，从而高效微调大型语言模型的技术。这使得模型能够在无需全量微调的高计算成本下，快速针对特定任务进行专业化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://programasweights.readthedocs.io/">ProgramAsWeights Documentation</a></li>
<li><a href="https://github.com/programasweights/compile-by-training">GitHub - programasweights / compile -by-training: Compile ...</a></li>
<li><a href="https://pypi.org/project/programasweights/">Compile natural language specifications into neural programs that run...</a></li>

</ul>
</details>

**社区讨论**: 社区对该项目在无需 API 依赖的情况下在本地运行 AI 任务的能力表现出了浓厚兴趣，用户强调了其在节省成本和处理隐私敏感应用方面的潜力。

**标签**: `#AI Productivity`, `#Local LLM`, `#Automation`, `#Software Development`, `#Cost Optimization`

---

<a id="item-2"></a>
## [Atlassian 将 Jira 升级为 AI 驱动的编码指挥中心](https://news.google.com/rss/articles/CBMimwFBVV95cUxPR094ZlVsdU5YUHpMUTZyMWc5WmZLQmlMeVN4c2hnOXlORmI3M1d1a2JpRl8tNHFwNGU4WFRQeWNXMndoUFNiLUNLeTBxTFlNV3ozRFk3dkVsTHd6NDg5aWV1Qnl4UTBPNWswSFY2S0ZWZ2VIb1VOZVdEdS1kcWVSMHRFdEx2Z0sxZkd2ZklvX1JFZEo4aHFicTNyZw?oc=5) ⭐️ 7.0/10

Atlassian 已将 AI 智能体直接集成到 Jira 中，使开发人员能够通过智能、自主的交互来自动化复杂的软件开发工作流并管理任务。此更新有效地将该项目管理平台转变为 AI 辅助编码操作的中心枢纽。 此次集成通过减少任务跟踪和工作流管理的手动开销，显著提高了开发人员的生产力。这标志着一个更广泛的行业趋势，即企业软件平台正在演变为能够积极参与开发生命周期的智能体系统。 新功能允许将 AI 智能体连接到工作流转换、看板列和自动化规则中。这使团队能够将诸如问题分配、状态更新和任务升级等重复性工作委托给自主智能体处理。

rss · AI Productivity and Monetization · 9月19日 19:04

**背景**: Jira 是一款广泛使用的项目管理工具，旨在帮助软件开发团队跟踪问题并管理敏捷工作流。AI 智能体是能够根据实时反馈做出决策并独立执行任务的自主程序。通过将两者结合，Atlassian 旨在弥合高层项目管理与底层代码执行之间的鸿沟。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.atlassian.com/software/jira/guides/workflows/overview">What are Jira workflows? Editor, rules, and AI agents</a></li>
<li><a href="https://www.atlassian.com/software/jira/guides/automation/overview">What is Jira Automation? Common Use Cases</a></li>
<li><a href="https://github.com/resources/articles/what-are-ai-agents">What are AI agents? · GitHub</a></li>

</ul>
</details>

**标签**: `#AI Productivity`, `#Software Development`, `#Workflow Automation`, `#Atlassian`, `#Enterprise SaaS`

---

<a id="item-3"></a>
## [代理式 AI 迎来关键缺失层：市场准入](https://news.google.com/rss/articles/CBMie0FVX3lxTE96OUY1VzVFR1R4d0hvd0l1TFF0ZEJVb25OdjMzMHNTX0d3R0xoTzZOR05sUHZXdEVxeEU2elI4Rnl4UmVIbWNJRE5ka09uU1FXX25zRVFqREdXbnAySVdRX0luNFhnbHZ2a3R5UkE3ZTBiUWVfNVV1bm1waw?oc=5) ⭐️ 7.0/10

文章指出市场准入是代理式 AI 当前缺失的关键层，并提出了一种框架，使自主智能体能够执行现实世界的交易和创造价值的任务。文章建议通过集成专用子账户和安全的结算协议，使智能体能够在自主经济中运行。 这一进展意义重大，因为它将 AI 智能体从单纯的任务执行者转变为能够进行自主交易的经济参与者。这种演变对于提升 AI 生产力规模以及构建机器原生商业的新生态系统至关重要。 所提议的架构涉及让智能体在具有特定市场数据、交易和内部转账权限的专用子账户中运行，同时严格限制提现权限。这种设计确保了自动化交易的安全性和法律效力。

rss · AI Productivity and Monetization · 9月19日 20:50

**背景**: 代理式 AI 是指无需持续人工干预即可发起任务、进行推理并适应环境以实现目标的自主系统。与主要用于生成内容的传统生成式 AI 不同，代理式 AI 旨在与外部环境和软件工具交互，以完成复杂的工作流程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hackernoon.com/agentic-ai-meets-its-missing-layer-market-access">Agentic AI Meets Its Missing Layer: Market Access | HackerNoon</a></li>
<li><a href="https://medium.com/@gwrx2005/building-an-ai-agent-oriented-market-institutional-design-protocol-economics-and-governance-for-ebeb2f103555">Building an AI Agent-Oriented Market: Institutional Design, Protocol Economics, and Governance for Machine-Native Trade | by Jung-Hua Liu | Medium</a></li>
<li><a href="https://github.com/BlockRunAI/polymarket-agent">GitHub - BlockRunAI/polymarket-agent: Autonomous AI-powered prediction market trading agent using x402 micropayments · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区讨论强调了一个日益增长的共识，即 AI 的未来在于自主经济代理，许多人强调需要基于协议的安全结算层来实现机器对机器的交易。

**标签**: `#Agentic AI`, `#AI Monetization`, `#Automation`, `#Productivity`

---

<a id="item-4"></a>
## [Meta 发布 Muse for Mac：一款用于本地生产力的个人 AI 智能体](https://news.google.com/rss/articles/CBMidkFVX3lxTE5xa3hiaWFfYzZLOFRRVlBHOXZ6VkdZRkpUZXhONjdCenBEV1RWMzhERzhOcnZ2d1RLYTYyNnI2a3QtRjl0VVQwR1NtTjJTU3dPS2FzbXV4UHpCZ0tzTWJmbG9FdUxPcGhZSzlIZzl2TmVZc3MxcEHSAXtBVV95cUxOVXlBR195ZDJfUExRZnR5QjR6dWduMjI4enBmRHVOVm91aHhiOE9oYnk5bTJYWU9BNlY1VDZDT3g5dGRhXzM4VWh1UkV5OTBIVmFvb0oxdWZrcUE5TmRpTW9JTTJTT2tEaHFMTnR6V19KYmZVZlA2X3lVSzA?oc=5) ⭐️ 7.0/10

Meta 发布了 Muse for Mac，这是一款旨在与用户的本地文件、电子邮件、信息、日历和笔记直接集成的个人 AI 智能体。该工具旨在通过作为 macOS 平台上的集中式助手来简化日常行政任务。 此次发布标志着向“本地优先”AI 生产力的重大转变，允许用户在保持敏感个人数据留在本地设备上的同时实现工作流自动化。它满足了用户对能够情境化理解并管理其私人数字环境的 AI 工具日益增长的需求。 Muse for Mac 专注于与原生 macOS 应用程序的深度集成，以提供情境感知的辅助功能。通过在本地运行，它最大限度地减少了将私人信息上传到云服务器的需求，从而增强了数据隐私和安全性。

rss · AI Productivity and Monetization · 9月19日 07:22

**背景**: “本地优先”AI 架构是一种设计方法，其数据处理和存储主要在用户的设备上而非云端进行。这种架构在 AI 智能体中越来越受欢迎，因为它通过将上下文文件保留在本地，降低了隐私风险并减少了延迟。个人 AI 智能体是旨在通过与用户特定的数字生态系统交互来执行任务、检索信息和管理工作流的软件程序。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aifirstsearch.com/solution-awareness/local-first-ai-architecture">Local - First AI Architecture | AI First Search</a></li>
<li><a href="https://hackernoon.com/the-architecture-of-local-first-ai-memory-no-cloud-no-keys-no-read-time-llms">hackernoon.com/the- architecture -of- local - first - ai -memory-no-cloud...</a></li>

</ul>
</details>

**标签**: `#AI Productivity`, `#Automation`, `#Local-first AI`, `#Workflow Optimization`

---

<a id="item-5"></a>
## [为何 2 倍杠杆的 QLD 在市场崩盘时表现优于 3 倍杠杆的 TQQQ](https://news.google.com/rss/articles/CBMi7wFBVV95cUxNeHNROTdUMEFUNWFCQUR5bW9Ca013VlJrNjMtZVJMQXVybDJUSDB2ZUlHT2h1b1J3OGNLaHQ4OFZTN3VrOXN6eFJtRUdFLUVXNGlYRkZQYjN4RjF6ekdFZUxIdVpZZGZRMGc4eFRPR2JURzkwVjllbmM5czJIY1hLaXRZU2MxcG55RVVHSkRxdUFuY2Jtc3NPSTV5bWRlUnhwejZxekdqQzBUTFJiNW53a3U0eFFoR0NQVDRzVTBlQXpLNVNVUkxTYUMwSFZYc3poa3BqVi1RTUpUVHNIX0Y5STR2ZUtieWRMOEFzV3FFaw?oc=5) ⭐️ 7.0/10

该分析指出，与提供 3 倍杠杆的 TQQQ 相比，提供纳斯达克 100 指数 2 倍日杠杆的 QLD 提供了更具可持续性的风险回报配置。这种适中的杠杆水平有助于投资者在市场低迷期间减轻波动率衰减带来的严重影响。 理解 2 倍杠杆与 3 倍杠杆之间的差异对长期投资者至关重要，因为更高的杠杆率会显著增加在市场持续波动期间永久性资本损失的风险。选择合适的杠杆倍数可能决定了投资者是能从崩盘中恢复，还是面临投资组合的彻底枯竭。 杠杆 ETF 每日重置其敞口，这意味着波动率衰减（即贝塔滑点）会随时间累积，并对 TQQQ 这类杠杆倍数更高的基金造成不成比例的损害。QLD 的 2 倍结构提供了一个缓冲，使其在标的指数大幅下跌时具有更好的恢复潜力。

rss · QQQ and Nasdaq 100 · 9月19日 10:55

**背景**: 杠杆 ETF 利用金融衍生品和债务来放大标的指数的每日回报。由于这些基金每日重置杠杆，它们被设计用于短期交易而非长期持有。波动率衰减的发生是因为杠杆基金需要更大的百分比涨幅才能从百分比损失中恢复，这种现象会随着杠杆倍数的增加而加剧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://leverageshares.com/us/insights/leveraged-etfs-explained-how-they-work-risks-and-benefits/">Leveraged ETFs Explained: How They Work, Risks, and Benefits</a></li>
<li><a href="https://www.investopedia.com/terms/l/leveraged-etf.asp">Leveraged ETFs: The Potential for Big Gains—and Bigger Losses</a></li>
<li><a href="https://www.leveraged-etfs.com/education/decay">Volatility Decay in Leveraged ETFs : Formula and Calculator</a></li>

</ul>
</details>

**标签**: `#Nasdaq-100`, `#Leveraged ETFs`, `#Risk Management`, `#Investment Strategy`, `#QQQ`

---

<a id="item-6"></a>
## [开发者分享了为期五个月的全面机器学习学习路线图](https://www.reddit.com/r/MachineLearning/comments/1wklia8/sharing_my_ml_learning_repo_numpy_to_transformers/) ⭐️ 7.0/10

一位开发者开源了一个 GitHub 仓库，记录了他为期五个月的每日学习历程，涵盖了从 NumPy 和经典算法到 Transformers 的完整机器学习技术栈。该仓库包含公开的 Jupyter Notebook，详细介绍了 scikit-learn、XGBoost、TensorFlow 以及自然语言处理（NLP）基础等内容。 该资源为自学者提供了一条结构化、免费且实用的路线图，帮助他们掌握现代人工智能开发技能。通过展示透明的每日技术进阶过程，它有效地弥合了理论知识与实际应用之间的鸿沟。 该课程涵盖了经典机器学习、卷积神经网络（CNN）和长短期记忆网络（LSTM）等深度学习架构、数据可视化、统计学以及 SQL。它专为那些希望通过持续的实践练习在数据科学和人工智能领域建立扎实基础的学习者而设计。

reddit · r/MachineLearning · /u/oGauRav · 9月19日 12:54

**背景**: 机器学习是人工智能的一个领域，使系统能够从数据中学习并随时间提升性能。2017 年引入的 Transformers 等现代架构彻底改变了自然语言处理领域，而 XGBoost 等算法仍然是处理结构化数据任务的行业标准。LSTM 是一种特殊的循环神经网络，旨在通过解决梯度消失问题来处理序列数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Transformer_(deep_learning)">Transformer (deep learning) - Wikipedia</a></li>
<li><a href="https://www.geeksforgeeks.org/machine-learning/lstm-networks/">LSTM Networks - GeeksforGeeks</a></li>
<li><a href="https://datatalksclub.github.io/podwiki/course-wiki/mlz-m06-gradient-boosting-and-xgboost/">Gradient boosting and XGBoost — Machine Learning Zoomcamp...</a></li>

</ul>
</details>

**社区讨论**: 社区对该仓库给予了积极回应，赞赏作者每日坚持学习的透明度，以及为初学者提供的结构化课程内容。

**标签**: `#Machine Learning`, `#AI Education`, `#Self-Learning`, `#Data Science`, `#Open Source`

---

<a id="item-7"></a>
## [PlanetScale 推出用于 Postgres 全文搜索的 'Tin'](https://planetscale.com/blog/introducing-tin) ⭐️ 6.0/10

PlanetScale 推出了名为 'Tin' 的 Postgres 全文搜索功能，旨在简化数据库生态系统内的搜索实现。该功能目前作为其云服务的一部分提供，以实现集成的搜索能力。 此次发布反映了行业内的一个广泛趋势，即数据库提供商正将专门的搜索功能直接集成到其平台中，以与独立的搜索引擎竞争。它通过减少为数据密集型应用维护独立搜索基础设施的需求，为开发人员提供了更精简的工作流程。 Tin 目前仅限于 PlanetScale 的云服务，其本地版本主要用于语法测试，而非生产环境性能测试。它加入了诸如 pg_search 和 pg_textsearch 等日益增长的 Postgres 搜索扩展行列。

hackernews · ksec · 9月19日 13:52 · [社区讨论](https://news.ycombinator.com/item?id=49766611)

**背景**: Postgres 长期以来一直包含使用 tsvector 和 tsquery 的内置全文搜索功能，支持复杂的文本匹配和排名。然而，许多开发人员发现这些原生工具配置复杂，或者在处理大数据集时性能开销较大，这促使了各种专用扩展的兴起。与标准的 Postgres 实现相比，这些扩展通常旨在提供更友好的用户界面或更好的性能优化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.postgresql.org/docs/current/textsearch.html">PostgreSQL: Documentation: 18: Chapter 12. Full Text Search</a></li>
<li><a href="https://iniakunhuda.medium.com/postgresql-full-text-search-a-powerful-alternative-to-elasticsearch-for-small-to-medium-d9524e001fe0">PostgreSQL Full-Text Search: A Powerful Alternative to Elasticsearch for Small to Medium Applications | by Miftahul Huda | Medium</a></li>

</ul>
</details>

**社区讨论**: 社区对此持不同意见；一些用户称赞集成搜索的趋势是 AI 驱动生产力的体现，而另一些用户则质疑在 Postgres 已经具备强大原生搜索功能的情况下，是否有必要引入新工具。此外，人们还担心与开源替代方案相比，这种仅限云端的实现方式具有封闭性。

**标签**: `#Postgres`, `#Database`, `#Infrastructure`, `#AI-Productivity`, `#Search-Engine`

---

<a id="item-8"></a>
## [评估人工智能代理的自主权与决策权限](https://news.google.com/rss/articles/CBMirgFBVV95cUxQd2cwX095Ul90cVBNQk9iWnZSakotX1pwdkpEcERPdlh4ZUdSd1BEc3NBdUxZbkNZaVJiWi1yRi1RSkZ2WXF3dFZRX2J3LXlQS1VBSzBHeTRFcldGdjVEdjJQX0lDYURXWkY4VnRmQ2k2MXVLazE4N3pfVW4zX0xYSU1OeFAxaHJEa1R4VUkxazZ1eHA3YmQ5YkhnVUl0ckZSRmx3dkh4b2JJOHlBSkE?oc=5) ⭐️ 6.0/10

本文探讨了从利用人工智能代理执行简单任务，到在专业环境中赋予其更高自主权和决策权限的战略转变。文章强调，随着组织扩展这些代理工作流，必须进行谨慎的风险管理。 随着人工智能代理能力不断增强，确定适当的人工监管水平对于平衡运营效率与组织安全至关重要。对于旨在将自主系统集成到复杂、高风险业务流程中的公司而言，这种转变至关重要。 讨论强调，增加代理权限需要健全的治理框架，以减轻潜在错误或意外后果。文章建议，组织必须超越简单的自动化，为自主决策实施结构化的监督。

rss · AI Productivity and Monetization · 9月19日 21:25

**背景**: 自主人工智能代理是一种能够感知环境、进行推理并执行操作以实现特定目标的软件系统，无需人类持续干预。现代代理架构通常利用分层设计或如 LangGraph 之类的编排框架来管理复杂任务。针对这些系统的有效风险管理通常遵循既定标准，例如 NIST 人工智能风险管理框架，以确保责任制和安全性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.langchain.com/langgraph">LangGraph: Agent Orchestration Framework for Reliable AI Agents</a></li>
<li><a href="https://cltc.berkeley.edu/publication/agentic-ai-risk-profile/">Agentic AI Risk-Management Standards Profile - CLTC Berkeley</a></li>
<li><a href="https://www.linkedin.com/pulse/emerging-architecture-autonomous-ai-agents-rohan-pinto-c7i6e">The Emerging Architecture of Autonomous AI Agents</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#Productivity`, `#Automation`, `#Workflow Optimization`

---

<a id="item-9"></a>
## [AI 智能体技能成为关键的供应链攻击载体](https://news.google.com/rss/articles/CBMirAFBVV95cUxNeTVyLW14Z0o4V3RXamVXTm11dExtRUcyelJyLWdfaS1UQVAyWU5lM2Vtc3dtRWNKb2lNQVhMTm1iTkZSbXJwbHdjSFlHRS14blR5YkE2NDRLZUVyeHpOSWFMS2JKVXdZRlAtU0tmR1Y5Rm41SS02djI2enBlU0pIbDJaUXBuYWdmWGR6R1dFTm9jMG93LWhiMmNyMjJLN2xyYUJNb01CS2VfYTBa?oc=5) ⭐️ 6.0/10

第三方 AI 智能体技能在未经审查的情况下被集成，产生了一个新的安全漏洞，使攻击者能够利用自主智能体的执行层。这些赋予智能体执行现实世界任务能力的技能，目前在部署时缺乏足够的安全审查。 随着企业日益依赖 AI 智能体进行自动化工作流，这些未经审查的技能带来了未经授权的数据访问和系统受损的重大风险。这一转变凸显了在 AI 智能体生态系统中建立标准化安全协议的必要性。 智能体技能作为编排多步工作流的执行层，已成为恶意代码注入的主要目标。与已经受到广泛安全关注的 LLM 不同，这些技能的中间行为层目前仍处于很大程度上的无保护状态。

rss · AI Productivity and Monetization · 9月19日 18:09

**背景**: AI 智能体是通过与外部工具和 API 交互来执行任务的自主系统。“技能”是指允许这些智能体执行操作（如访问数据库或发送电子邮件）的具体能力或功能。在此背景下，供应链指的是开发者集成到其 AI 应用中的第三方库和预构建模块的生态系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://owasp.org/projects/agentic-skills-top-10">OWASP Agentic Skills Top 10</a></li>
<li><a href="https://neuraltrust.ai/blog/ai-driven-supply-chain-attacks">AI-Driven Supply Chain Attacks: The New Cyber Risk in 2026 | NeuralTrust</a></li>

</ul>
</details>

**标签**: `#AI Security`, `#AI Agents`, `#Cybersecurity`, `#Automation Risk`

---

<a id="item-10"></a>
## [AMD EPYC 处理器现已针对全周期智能体 AI 工作流进行优化](https://news.google.com/rss/articles/CBMia0FVX3lxTE5MSm5USmNJcXFjTFYwVVdNdXhoTjlwMlFJaTFGVzYxd3Q4eUtzdVE2ZHFBak15NUxKd1Q2TENqV1NzUHgxOU5jNzZoQ0VScUNTOUlrWk9hVjBqTkVSTnlFTU9jMVl4ODlTUHVR?oc=5) ⭐️ 6.0/10

AMD 更新了其 EPYC 处理器的功能，使其能够处理智能体 AI 工作流的各个阶段，从而更高效地执行复杂的多步骤 AI 任务。这一优化使数据中心能够在单一 CPU 架构上管理 AI 智能体的整个生命周期。 通过使 CPU 能够处理智能体 AI，企业可以降低将任务卸载到专用硬件所带来的成本和延迟。这一转变使企业能够更轻松地扩展用于日常企业自动化的自主 AI 智能体。 此次优化重点在于第五代 AMD EPYC CPU 的灵活性，旨在适应 AI 工作流不断变化的需求。这些处理器提供了必要的处理密度，以支持迭代式、多步骤的 AI 流程，而无需频繁进行硬件重配置。

rss · AI Productivity and Monetization · 9月19日 09:29

**背景**: 智能体 AI 工作流是指 AI 智能体能够自主将复杂问题分解为多步骤、迭代式任务以实现特定目标的系统。与提供单一响应的标准 AI 模型不同，这些工作流利用工具、记忆和推理能力来适应实时数据和不断变化的条件。AMD EPYC 处理器是数据中心常用的服务器级 CPU，旨在为这些高要求的企业应用提供所需的计算能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.amd.com/en/products/processors/server/epyc/ai.html">AMD EPYC ™ Servers are the Foundation for Data Center AI</a></li>
<li><a href="https://www.ibm.com/think/topics/agentic-workflows">What are Agentic Workflows? | IBM</a></li>
<li><a href="https://www.techpowerup.com/334004/amd-recommends-epyc-processors-for-everyday-ai-server-tasks">AMD Recommends EPYC Processors for Everyday AI ... | TechPowerUp</a></li>

</ul>
</details>

**标签**: `#AI Infrastructure`, `#Agentic AI`, `#AMD`, `#Enterprise AI`, `#Automation`

---