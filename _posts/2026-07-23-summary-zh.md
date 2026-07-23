---
layout: default
title: "Horizon Summary: 2026-07-23 (ZH)"
date: 2026-07-23
lang: zh
---

> 从 125 条内容中筛选出 9 条重要资讯。

---

1. [真实大模型任务成本分析显示：隐藏推理 Token 导致 10.6 倍费用差异](#item-1) ⭐️ 9.0/10
2. [Cactus Hybrid：通过置信度评分实现智能大模型路由的 Gemma 4 模型](#item-2) ⭐️ 8.0/10
3. [大型科技公司财报前瞻：人工智能变现能否跟上资本支出步伐？](#item-3) ⭐️ 8.0/10
4. [Perplexity 发布 macOS 智能体 AI，实现桌面任务自动化](#item-4) ⭐️ 8.0/10
5. [OmniRoute：用于统一模型访问和成本优化的开源 AI 网关](#item-5) ⭐️ 8.0/10
6. [Arm MCP 服务器的采用凸显了向代理式 AI 工作流的转变](#item-6) ⭐️ 7.0/10
7. [Napster 的 AI 智能体将 F1 门票结账点击率提升了 70%](#item-7) ⭐️ 7.0/10
8. [Anaconda 收购 Kilo Code 以推进企业级可验证 AI 编程](#item-8) ⭐️ 7.0/10
9. [OpenAI 发布 ChatGPT Work，转型为自主工作场所 AI 智能体](#item-9) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [真实大模型任务成本分析显示：隐藏推理 Token 导致 10.6 倍费用差异](https://www.reddit.com/r/MachineLearning/comments/1v450o3/real_task_cost_across_gpt_claude_gemini_and_kimi/) ⭐️ 9.0/10

一项针对主流大模型提供商的 10 项真实任务基准测试发现，实际 API 成本差异高达 10.6 倍，远超官方定价 2 倍的差距。这种差异主要源于“隐藏”的推理 Token，它们按输出费率计费，但对用户不可见。 这一发现揭示了人工智能成本管理中的一个关键盲点，表明官方定价表无法反映智能体工作流的真实运营开销。开发者在扩展人工智能应用时，必须考虑这些隐藏的 Token 成本，以避免严重的预算超支。 研究观察到，模型即使在处理简单的分类任务时也会生成数百个不可见的推理 Token。该研究还引用了 CostBench 的发现，指出领先模型往往无法选择最具成本效益的执行方案。

reddit · r/MachineLearning · /u/pixelo2323 · 7月23日 05:51

**背景**: 现代大模型通常使用“推理轨迹”（即内部思维链）来提高复杂任务的准确性，但这些 Token 通常被计入输出费用。智能体工作流涉及自主代理来规划和执行多步任务，如果代理失败或采取低效路径，可能会导致不可预测的 Token 消耗。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2601.03066">Do LLMs Encode Functional Importance of Reasoning Tokens? Do LLMs Encode Functional Importance of Reasoning Tokens ? Thinking to recall: How reasoning unlocks parametric ... Input vs Output vs Reasoning Tokens Cost - LLM Pricing ... Reasoning models | OpenAI API Reasoning Tokens vs Knowledge Tokens: How LLMs Actually Think Diverse reasoning traces teach LLMs to make better decisions</a></li>
<li><a href="https://www.ibm.com/think/topics/agentic-workflows">What are agentic workflows? - IBM</a></li>
<li><a href="https://github.com/ClickHouse/CostBench">GitHub - ClickHouse/CostBench: Open benchmark for comparing ...</a></li>

</ul>
</details>

**社区讨论**: 社区对该方法论表现出浓厚兴趣，指出推理的“隐藏”成本是生产级人工智能的主要担忧。许多用户强调，API 计费在推理 Token 与生成 Token 的区分上需要更高的透明度。

**标签**: `#AI Productivity`, `#LLM Optimization`, `#Cost Management`, `#Agentic Workflows`, `#API Economics`

---

<a id="item-2"></a>
## [Cactus Hybrid：通过置信度评分实现智能大模型路由的 Gemma 4 模型](https://github.com/cactus-compute/cactus-hybrid) ⭐️ 8.0/10

Cactus Hybrid 推出了一款经过后训练的 Gemma 4 模型，该模型能为输出结果提供置信度评分，使开发者能够智能地在本地模型和云端大模型之间分配查询任务。这种方法通过仅将不确定的查询发送给昂贵的云端模型，显著降低了 API 使用成本。 该架构通过提供一种可靠且基于数据的混合推理机制，解决了人工智能应用中高成本与延迟之间的权衡问题。它使开发者能够在保持高性能的同时，将大部分流量保留在经济高效且私密的本地设备上。 该模型使用一个 68k 参数的探测层在解码过程中分析隐藏状态，在预测正确性方面达到了平均 0.814 的 AUROC 值。它兼容 Transformers、MLX 和 Llama.cpp 等主流框架，并以 MIT 许可证发布。

hackernews · HenryNdubuaku · 7月22日 17:56 · [社区讨论](https://news.ycombinator.com/item?id=49010782)

**背景**: 大模型路由是一种通过动态选择最适合特定查询的模型来优化性能和成本的技术。机械可解释性是一个研究领域，旨在通过分析神经网络的隐藏状态和激活值来理解其内部工作原理，而不是将其视为黑盒。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2404.14618">Hybrid LLM: Cost-Efficient and Quality-Aware Query Routing GitHub - microsoft/best-route-llm: Efficient LLM query ... LLMRouter: An Open-Source Library for LLM Routing LLM Routing – Intuitively and Exhaustively Explained Query Routing for Retrieval-Augmented Language Models LLM routing for quality, low-cost responses - IBM Research</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mechanistic_interpretability">Mechanistic interpretability - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员对这种基于机械可解释性的自我意识信号方法表现出了浓厚兴趣，同时也就“知道自己错了”与“不确定性”之间的术语差异进行了讨论。其他人分享了各自的集成实验，并要求提供更多关于探测层训练方法的细节。

**标签**: `#AI Productivity`, `#LLM Optimization`, `#Cost Reduction`, `#Edge AI`, `#Agentic Workflows`

---

<a id="item-3"></a>
## [大型科技公司财报前瞻：人工智能变现能否跟上资本支出步伐？](https://news.google.com/rss/articles/CBMitAFBVV95cUxPWHNZSzNjUkhUeUk2SjdINDRGTmh0ZmxHNDlxYVB3MERRV1Y1X3hJaEkweXYtNVFmMEQ0SmV5cWVuM0FBRHZrVnpOQzJfWjROdnBjR3hBd3hvTmxIclJVZy1veGhkLVhlVUVoZFdCOENjQkJ3VmRGM2Nod1BQNElCQVcwMGw3Ny1ZUG9hdUZUVmNYZ3V0SnIxYVBoTlloNjNsOENNOXF1QVdkRVE5WnE4b1JFdGc?oc=5) ⭐️ 8.0/10

本文分析了大型科技公司投入到人工智能基础设施中的巨额资本支出（CapEx），是否开始在即将发布的季度财报中转化为实际的收入增长。文章重点关注了从基础设施投资向盈利性人工智能产品变现的关键转型。 这一点至关重要，因为当前美国股市估值的可持续性，取决于大型科技公司能否证明其数十亿美元的人工智能投资正在产生实质性回报。投资者正日益审视巨额支出与实际创收之间的差距。 该分析强调了“人工智能基础设施冲刺”与企业采用人工智能的缓慢步伐之间的紧张关系，前者支出已达数千亿美元。文章指出，市场信心取决于最新财务业绩中人工智能驱动收入流的明确证据。

rss · AI Productivity and Monetization · 7月22日 21:04

**背景**: 大型科技公司正处于前所未有的资本支出周期中，投入巨资建设数据中心、GPU 和云基础设施以支持人工智能发展。虽然这些投资对于构建基础模型至关重要，但投资者现在要求证明这些成本将通过人工智能驱动的服务带来长期盈利能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://futurumgroup.com/insights/ai-capex-2026-the-690b-infrastructure-sprint/">AI Capex 2026: The $690B Infrastructure Sprint - Futurum</a></li>
<li><a href="https://www.forbes.com/sites/jasonkirsch/2026/07/03/the-ai-capital-expenditure-cycle-has-not-peaked---and-that-changes-the-investment-calculus/">The AI Capital Expenditure Cycle Has Not Peaked — And That Changes The Investment Calculus</a></li>
<li><a href="https://fortune.com/2026/06/29/ai-spending-boom-accelerates-big-tech-trillion-infrastructure-qualcomm-cfo/">AI spending boom accelerates as Big Tech pours trillions into infrastructure | Fortune</a></li>

</ul>
</details>

**标签**: `#Nasdaq-100`, `#AI Monetization`, `#Capital Expenditure`, `#US Equities`, `#Big Tech`

---

<a id="item-4"></a>
## [Perplexity 发布 macOS 智能体 AI，实现桌面任务自动化](https://news.google.com/rss/articles/CBMilgFBVV95cUxOM1I4N1QwcF9KZW5IZnpEM1p4WjE0bTdpMjFDNmRJVDVUdlRVNnVOd3BGa0ZQeHBQdWw4ZlphSUhuWDdveE40MXlBUFdDOFdHYmVJdUpXblU3MEl2MjJXT05WMXQycXBWVmpJNnBaNUhobzhod2Foem9sTEVOMUFDQ1VRbjFZNXVDczJpN281WExGM05hM3c?oc=5) ⭐️ 8.0/10

Perplexity 推出了适用于 macOS 的智能体 AI 功能，允许模型直接在用户的电脑上自主执行多步骤任务。该功能使 AI 能够与桌面应用程序和浏览器工作流进行交互，从而在极少的人工干预下完成复杂的工作。 这一进展标志着“计算机使用”类 AI 的重大转变，将 AI 从被动聊天机器人转变为能够处理行政和研究工作流的主动助手。通过自动化以往需要手动操作的重复性任务，它为用户提供了直接的生产力提升。 该智能体利用 macOS 系统级集成来感知并与用户界面元素交互，使其能够执行点击、输入和在不同应用程序间导航等操作。用户需要注意，这些智能体功能旨在处理超出简单文本生成的复杂多步骤序列。

rss · AI Productivity and Monetization · 7月22日 18:29

**背景**: 智能体 AI（Agentic AI）是指能够感知环境、推理问题并采取行动以实现特定目标的自主系统，无需持续的人工干预。在 macOS 上，此类智能体通常利用辅助功能 API（Accessibility APIs）和 ScreenCaptureKit 等原生框架来“观察”屏幕并安全地与软件界面进行交互。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://mitsloan.mit.edu/ideas-made-to-matter/agentic-ai-explained">Agentic AI, explained | MIT Sloan</a></li>
<li><a href="https://fazm.ai/blog/macos-ai-agent">macOS AI Agent: How Desktop Agents Work on Mac in 2026 - Fazm Blog</a></li>
<li><a href="https://www.ibm.com/think/topics/agentic-ai">What is Agentic AI? - IBM</a></li>

</ul>
</details>

**社区讨论**: 早期用户和科技评论员对该功能带来的巨大时间节省潜力表示兴奋，但也有讨论强调在处理敏感工作流时，需要对安全性和自主操作的可靠性保持谨慎。

**标签**: `#AI Productivity`, `#Automation`, `#Agentic AI`, `#Workflow Optimization`

---

<a id="item-5"></a>
## [OmniRoute：用于统一模型访问和成本优化的开源 AI 网关](https://github.com/diegosouzapw/OmniRoute) ⭐️ 8.0/10

OmniRoute 是一个开源 AI 网关，为 160 多种 AI 模型提供统一的访问端点，并具备内置的 Token 压缩和自动故障转移功能。它允许开发人员将 Claude Code、Cursor 和 Copilot 等工具与各种 AI 提供商集成，同时显著降低 Token 使用量。 通过将多个 AI 提供商聚合到一个接口中并实现 Token 压缩，OmniRoute 帮助开发人员降低了运营成本并简化了基础设施管理。对于希望在不牺牲性能的情况下优化 AI 工作流的团队来说，这具有极高的价值。 该平台支持 RTK 和 Caveman 压缩技术，声称可节省 15-95% 的 Token，并包含对 MCP（模型上下文协议）和多模态 API 的支持。它使用 TypeScript 构建，并提供桌面端和 PWA 部署选项。

ossinsight · diegosouzapw · 7月23日 07:44

**背景**: AI 网关充当中间件层，用于管理、保护和路由应用程序与各种大语言模型（LLM）之间的流量。模型上下文协议（MCP）是一种开放标准，允许 AI 助手安全地连接到外部数据源和工具，而 Token 压缩技术则用于减少发送给 LLM 的数据量，从而降低成本并提高效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://modelcontextprotocol.io/docs/getting-started/intro">What is the Model Context Protocol (MCP)?</a></li>
<li><a href="https://www.supercompress.dev/token-compression">Token Compression for LLMs: The Complete Guide (2026)</a></li>

</ul>
</details>

**标签**: `#AI-Gateway`, `#Productivity`, `#Cost-Optimization`, `#TypeScript`, `#LLM-Infrastructure`

---

<a id="item-6"></a>
## [Arm MCP 服务器的采用凸显了向代理式 AI 工作流的转变](https://news.google.com/rss/articles/CBMigAFBVV95cUxOR2k2NkUzMVdVdmN0Z043NUFUUmRCQlU1OHZ6THMxa0lfMHY3aGhxUi13a1d6LUhmWkI2dGQ5cmUwX1g2Vmo5UWVpMVlVZTFRRmZYUWxpczhvcjBtc2NqdHUxU2tndHRqbmxUOF9CY0ZyR0tRZkh6YXA3VWV4cXJvWg?oc=5) ⭐️ 7.0/10

Arm 推出了对模型上下文协议 (MCP) 服务器的支持，使 AI 代理能够更高效地与开发人员工具和数据环境进行交互。这种集成允许开发人员使用标准化接口将 AI 系统连接到本地和远程数据源。 MCP 的采用是实现 AI 互操作性的关键一步，因为它用通用标准取代了碎片化的定制集成。这一转变显著减少了手动数据集成任务，并加速了自主代理式 AI 工作流的开发。 由 Anthropic 最初推出的 MCP 标准为将 AI 应用程序连接到数据库和文件系统等外部系统提供了通用框架。通过利用 Arm MCP 服务器，开发人员可以确保其 AI 代理能够可靠且安全地访问复杂编码任务所需的上下文。

rss · AI Productivity and Monetization · 7月22日 19:06

**背景**: 代理式 AI 是指能够以不同程度的自主性追求目标、使用工具并采取行动的智能系统。模型上下文协议 (MCP) 是一项开源标准，旨在通过允许 AI 模型安全且一致地访问来自各种开发人员工具和环境的数据，从而解决“上下文”问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://modelcontextprotocol.io/">What is the Model Context Protocol ( MCP )? - Model Context Protocol</a></li>
<li><a href="https://www.anthropic.com/news/model-context-protocol">Introducing the Model Context Protocol \ Anthropic</a></li>

</ul>
</details>

**社区讨论**: 社区普遍认为 AI 与工具通信的标准化是提高生产力的重要举措，它降低了构建自定义 AI 代理的门槛。开发人员对相比维护专有 API 集成所带来的维护开销减少的前景感到特别兴奋。

**标签**: `#AI Agents`, `#Developer Productivity`, `#MCP`, `#Automation`, `#Software Engineering`

---

<a id="item-7"></a>
## [Napster 的 AI 智能体将 F1 门票结账点击率提升了 70%](https://news.google.com/rss/articles/CBMi-AFBVV95cUxPNkt4UThTSmNFZmZWZjdWNlQ5Y1lCUlh6bTR5dTgycWU4UGR6eUR1a0hUUFhwTUJhbm00MUFDSUNTZ1djNzZUeFZKRVFfMURiOXNsNHdMdjItNDhCWVFqaUdwME1jZUt2ZVhGSFFwUGhMb0JLaHAyZGJOcld5NnI2TENWcHdMLUd4YXZCWHRuWDQ4LUJyOGdGQ0o4NEVfY19tOGZRaWJHMXp3VzIzRzcxRHhPbmtzYW5JU19JWV9Ud0JfWk5hN1M3Rnc3bWZqc1RpWUktT2FOSjA5dkQtSU8yMVZLaUdQWGZIZEI2Q3Q4NDdiTk5aVzJLdQ?oc=5) ⭐️ 7.0/10

Napster 成功部署了一个 AI 智能体，在 F1 门票购买过程中为用户提供引导，使结账点击率提升了 70%。该智能体通过实时交互帮助将浏览者转化为购买者。 这一案例研究展示了 AI 智能体在电子商务中的实际影响，证明了个性化的实时辅助可以显著减少交易阻力并提高转化指标。它为寻求优化变现流程的企业提供了一个可扩展的参考模型。 此次部署专注于引导用户完成复杂的门票购买流程，有效地将被动的浏览行为转化为主动的结账参与。这凸显了 AI 在管理高意向、时效性强的销售活动中的有效性。

rss · AI Productivity and Monetization · 7月22日 17:00

**背景**: 电子商务中的 AI 智能体是旨在充当虚拟购物助手的自动化软件程序，帮助用户浏览产品目录、回答问题并完成交易。通过利用行为数据，这些智能体可以提供传统静态客服队列无法比拟的个性化支持。这项技术正越来越多地被用于减少购物车放弃率并简化购买路径。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://controlhippo.com/ai-agents/ecommerce/">AI Agents for Ecommerce : Automate Support & Drive Sales</a></li>
<li><a href="https://www.index.dev/blog/ai-agents-ecommerce-workflow-automation">7 Best AI Agents for E - commerce Automation 2026</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#E-commerce`, `#Conversion Optimization`, `#Monetization`, `#AI Productivity`

---

<a id="item-8"></a>
## [Anaconda 收购 Kilo Code 以推进企业级可验证 AI 编程](https://news.google.com/rss/articles/CBMilwFBVV95cUxORUtBTzlYZDRGSmhMemZzb1RmYkt0RlNfYnJrd3N2X0xnUFJNXzlpWFV6UWZ0ajBCNXFMYkhSNTVHTmFzcTV1Si1WMDNNYzYzWENMOVE5NDJ4OU9qcGxpamtjWDFCaURGMS14VkRFLU9iLXNsOVNCbkJndHJLVVFLVWxYMHVYbWZqYmxhdEtPS2FOWGdDdU1z?oc=5) ⭐️ 7.0/10

Anaconda 收购了 Kilo Code，旨在将其技术整合到现有平台中，重点在于为企业环境生成可验证、安全且可复现的代码。此举旨在超越简单的 AI 代码生成，转向更可靠、可投入生产的软件开发工作流。 此次收购解决了企业在自动化流水线中减少 AI 幻觉并确保代码质量的关键需求。通过优先考虑可验证性，Anaconda 正致力于帮助企业将 AI 安全地集成到关键任务的软件开发中。 该合作强调了生成可复现代码的重要性，这对调试和维护复杂的软件系统至关重要。它将重点从单纯的代码片段生成转向构建可验证的端到端开发流水线。

rss · AI Productivity and Monetization · 7月22日 11:10

**背景**: Anaconda 以其用于数据科学和机器学习的 Python 及 R 发行版而闻名，提供管理复杂软件依赖关系的工具。“可验证代码生成”是指 AI 系统不仅能生成代码，还能提供证明或测试，以确保代码按预期运行，从而降低生产环境中的错误风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://stackoverflow.com/help/minimal-reproducible-example">How to create a Minimal, Reproducible Example - Help Center - Stack Overflow</a></li>
<li><a href="https://arxiv.org/html/2505.23135">Verina: Benchmarking Verifiable Code Generation</a></li>

</ul>
</details>

**标签**: `#AI Coding`, `#Software Development`, `#Enterprise AI`, `#Productivity Tools`, `#Automation`

---

<a id="item-9"></a>
## [OpenAI 发布 ChatGPT Work，转型为自主工作场所 AI 智能体](https://news.google.com/rss/articles/CBMikgFBVV95cUxQNWdjcGhfbkpzQ2UzRE1zbTNPWDNGU24wVzR4bXZtMlRXUEFBcWJ0d0tfRjEyNHZLaVZpa0tDcExSMUdvRzVHYmtuMzdmWDQyaEstY1NTUlFoTGl0ZXFHUmd6TThpRFpfY2xpTm92aWtwRnhvUkhjcnVCUXVmQVRXbG91VExYSU45UjFIdkxRSUdEdw?oc=5) ⭐️ 7.0/10

OpenAI 推出了 ChatGPT Work，这是一个旨在作为自主智能体运行的新平台版本，能够执行复杂的工作场所工作流。这一转变标志着该工具从简单的对话回复向主动完成任务的模式演进。 这一发展代表了 AI 生产力的重大演进，使个人和团队能够自动化处理复杂流程，而不仅仅是检索信息。它标志着行业向能够独立规划和执行任务的“智能体 AI”迈进的更广泛趋势。 与依赖用户每一步提示的传统聊天机器人不同，ChatGPT Work 旨在管理多步骤任务并与企业工具集成，以提高运营效率。它专注于通过处理端到端的工作流来减少人工干预。

rss · AI Productivity and Monetization · 7月22日 17:08

**背景**: 传统的聊天机器人主要是基于规则或依赖输入的工具，仅用于响应特定查询。相比之下，AI 智能体是能够进行规划、决策并在各种应用程序中执行操作以实现特定目标的智能系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/enterprise-transformation-through-agentic-ai-from-dinesh-rivankar-fvuzc">Enterprise Transformation through Agentic AI : From Automation to...</a></li>
<li><a href="https://www.microsoft.com/en-us/microsoft-copilot/for-individuals/do-more-with-ai/general-ai/understanding-ai-agents-vs-chatbots">Understanding AI Agents vs. Chatbots | Microsoft Copilot</a></li>
<li><a href="https://www.cognigy.com/ai-agents/chatbot-vs-ai-agent">Chatbots vs AI Agents: What Is the Difference?</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#Productivity`, `#Automation`, `#ChatGPT`, `#Workflow Optimization`

---