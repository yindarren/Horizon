---
layout: default
title: "Horizon Summary: 2026-09-06 (ZH)"
date: 2026-09-06
lang: zh
---

> 从 43 条内容中筛选出 8 条重要资讯。

---

1. [麦肯锡：AI 编程代理促使企业从购买软件转向自主开发](#item-1) ⭐️ 8.0/10
2. [llama.cpp 新实现支持在推理阶段扩展 MoE 模型专家数量](#item-2) ⭐️ 8.0/10
3. [在推理阶段为预训练大模型应用滑动窗口注意力机制](#item-3) ⭐️ 8.0/10
4. [赋予 AI 智能体专属电子邮箱地址成为新兴产品类别](#item-4) ⭐️ 7.0/10
5. [微软推出基于人工智能的 WinUI 3 应用快速开发工作流](#item-5) ⭐️ 7.0/10
6. [PINNStudio：用于物理信息神经网络的免费开源无代码图形界面](#item-6) ⭐️ 7.0/10
7. [比特币矿工转向人工智能，基础设施收入激增 52%](#item-7) ⭐️ 6.0/10
8. [将金融交易委托给 AI 代理的风险与潜力探讨](#item-8) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [麦肯锡：AI 编程代理促使企业从购买软件转向自主开发](https://news.google.com/rss/articles/CBMi5wFBVV95cUxOUnRQX0U1dUZWMlFtRUVwQ0NURk5mWHhDdGotMGFQRDU0OUhqeWRpX1d2dmZRZG9kY0NuZ3U0YjF1cFphTGpKbGIycXQ2QVFRa0xwVTR3MWh6djJFVjFLemJIRVVjZU9FbUN4cjVUamtvcGFMOXdoVXVvY1VHVVQ0QXA2S2hHX3A5RWsxekpKYm1RSUFZUmRRT0dVZGpnWW51c0k3VUxHN3I1a3YxVTRrQUxWTDI2OHhteVZtRmFZYVplTXlwdlFSa251aV81TUhPSG1SQ2pPejdYeWZoSlFESXhnVTYxa2_SAesBQVVfeXFMTUw3T0p1U3lKbENFTGlld3F5Q1pNVFIzVHlaMXhaN285LW03aWFkRGVubC1nWnJGcmVyUC1rbWRXYmp6SDlIRURseGQyMnZ6YTl0a1YxZ0cxR2VwX3FJQTlNVlVpUk1DTlBhcEE3MlBFVEdxWDVwMUFxWkFqUlN5TWNqanp5cUFjRWZ5MlVxanlZN05FMzg0UFQ4LWwtY3ZxaGtWVHFLTGgxMUxuaThkMm1naGNiV3VmNWp0LWotTktrY2dNbm1wV0ZweGZWLXp0amlYTDRIQ3E1WVR6TTllV2trS0U5aUdyUXVoUQ?oc=5) ⭐️ 8.0/10

麦肯锡报告指出，AI 编程代理的兴起使企业能够优先考虑定制化内部软件开发，而非购买现成的 SaaS 产品。这一趋势表明企业在 IT 预算分配方式上正在发生根本性转变。 这一趋势可能会通过降低定制化解决方案的门槛，从而颠覆传统的 SaaS 商业模式。企业可能会发现，构建符合自身特定需求的定制工具，比支付死板的订阅制软件更具成本效益和效率。 AI 编程代理能够自动化软件开发生命周期中的大部分环节，包括代码生成、测试和调试。通过减少编码所需的时间和人力，这些工具使得小型团队维护定制化软件栈变得切实可行。

rss · AI Productivity and Monetization · 9月6日 15:37

**背景**: “自研还是购买”是企业面临的经典战略难题，即权衡开发专有软件与购买成熟第三方解决方案的成本与风险。AI 编程代理是利用大语言模型在整个软件开发过程中辅助开发者的先进 AI 系统。这些代理近期已从简单的代码补全工具演变为能够处理复杂开发任务的自主系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.netsolutions.com/insights/build-vs-buy/">A Guide to Making a Build vs . Buy Software Decision</a></li>
<li><a href="https://gainhq.com/blog/build-vs-buy-software/">Build Vs Buy Software : Complete Decision Guide For... - GainHQ</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_coding_agent">AI coding agent</a></li>

</ul>
</details>

**社区讨论**: 社区讨论通常集中在 AI 是否真的能取代专业软件工程师，还是仅仅能提高现有团队的生产力。一些观察人士对 AI 生成的定制代码在长期维护和安全性方面是否能与专业企业级软件相媲美表示担忧。

**标签**: `#AI Productivity`, `#Software Development`, `#SaaS`, `#Business Strategy`, `#Automation`

---

<a id="item-2"></a>
## [llama.cpp 新实现支持在推理阶段扩展 MoE 模型专家数量](https://www.reddit.com/r/MachineLearning/comments/1w94dtn/proposed_architecture_for_inferencing_sparse_moe/) ⭐️ 8.0/10

llama.cpp 的一项新实现允许用户在运行时增加稀疏专家混合（MoE）模型中的活跃专家数量，且无需进行模型重训练或微调。该功能支持自适应阈值和影响衰减，从而在现有硬件上提升模型性能。 这一进展为本地 AI 部署提供了一种零成本的方法，能够显著提升 MoE 模型的有效参数量和性能。它允许用户绕过原生 top-K 路由限制，从而从现有硬件中挖掘出更强的模型能力。 该实现引入了仅在运行时生效的调整，包括自适应阈值、99% 到 50% 的影响衰减以及可配置的层范围。该方案已在 Qwen 3.6 35B A4B+ 模型上针对所有支持的后端进行了成功测试。

reddit · r/MachineLearning · /u/Specific-Tax-6700 · 9月6日 18:41

**背景**: 稀疏专家混合（MoE）模型使用路由机制，仅为每个输入 token 激活一部分参数（专家），从而提高计算效率。通常，这些模型使用“top-K”路由，即仅选择最相关的 K 个专家来处理 token。这种新方法允许用户覆盖这些默认设置，从而激活比模型架构最初设计更多的专家。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hal.science/hal-05113196v1/document">A Survey of Mixture of Experts Models : Architectures and...</a></li>
<li><a href="https://sesen.ai/blog/mixture-of-experts-llms-sparse-routing">Mixture of Experts in LLMs: From Switch to DeepSeek-V3</a></li>
<li><a href="https://dkaarthick.medium.com/unlocking-efficiency-and-scale-the-mixture-of-experts-moe-and-sparse-moe-smoe-architectures-676fffaac2db">Unlocking Efficiency and Scale: The Mixture of Experts ( MoE ) and...</a></li>

</ul>
</details>

**社区讨论**: 社区对该实现表现出了浓厚兴趣，认为这对于希望最大化硬件利用率的本地大模型用户来说是一种非常实用的优化方案。讨论强调了在无需复杂模型微调的情况下，该方案能带来立竿见影的生产力提升。

**标签**: `#AI Productivity`, `#LLM Optimization`, `#llama.cpp`, `#MoE Models`, `#Local Inference`

---

<a id="item-3"></a>
## [在推理阶段为预训练大模型应用滑动窗口注意力机制](https://www.reddit.com/r/MachineLearning/comments/1w8repz/applying_sliding_window_attention_to_pretrained/) ⭐️ 8.0/10

一项新的可重用推理层实现允许开发者在无需重新训练模型的情况下，将滑动窗口注意力机制（SWA）应用于现有的 Hugging Face 因果大模型。它通过结合注意力汇聚点（attention sinks）的有限 KV 缓存来维持性能，同时显著降低了内存占用。 该实现大幅降低了长上下文任务的显存需求，使得在消费级硬件上运行大上下文窗口成为可能。它为本地大模型部署提供了一种实用且低成本的优化路径，避免了微调带来的高昂开销。 该实现采用了用于 KV 存储的循环环形缓冲区和分块注意力掩码，在 Qwen2.5-7B 模型 16K 上下文的测试中，将 KV 缓存大小从约 923 MB 降低至约 3.5 MB。用户需注意，对于需要窗口外信息的任务，模型性能可能会出现下降。

reddit · r/MachineLearning · /u/ahsaor8 · 9月6日 09:23

**背景**: KV 缓存是 Transformer 模型中占用内存的主要组件，它存储了过去 token 的表示，以避免在生成过程中进行重复计算。滑动窗口注意力（SWA）通过将注意力机制限制在最近 token 的固定窗口内来优化这一过程，而“注意力汇聚点”（attention sinks）则是模型往往会不成比例地关注的特定初始 token，保留它们有助于维持模型稳定性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2502.18845">[2502.18845] Sliding Window Attention Training for Efficient Large Language Models</a></li>
<li><a href="https://huggingface.co/blog/tomaarsen/attention-sinks">🕳️ Attention Sinks in LLMs for endless fluency</a></li>
<li><a href="https://cyrilzakka.github.io/llm-playbook/nested/swa.html">Sliding-Window Attention (SWA) - The Large Language Model Playbook</a></li>

</ul>
</details>

**社区讨论**: 社区成员正积极与开发者互动，就可验证的模型架构提供反馈，并讨论了内存效率与长距离依赖信息丢失之间的权衡问题。

**标签**: `#AI Productivity`, `#LLM Optimization`, `#Inference Efficiency`, `#VRAM Management`

---

<a id="item-4"></a>
## [赋予 AI 智能体专属电子邮箱地址成为新兴产品类别](https://news.google.com/rss/articles/CBMinAFBVV95cUxPVHhDZDlGaHZaX2xJWThVRkVoS1RRMWZrb19NWVA5Uk9QUWMyZzZtb3YtTHd2RmxPU0ZHbFZoQ3FNa1ljNjZ2bTlNcEEySU9SN3pfUU5INE9jeFVKa1NnMk5ieHpXc1hJbU9oOEw2eWdpbm5CSFR3NGUxQzNLNFRkVmFhNGZ2NWNPdlBVVU1EQzdKVlNpLW9FaHNLUV8?oc=5) ⭐️ 7.0/10

将电子邮件功能集成到 AI 智能体中已演变为一个独特的产品类别，使这些智能体能够自主管理通信并执行复杂的工作流。这些智能体现在无需人工干预即可处理收到的邮件、起草回复并触发后续操作。 这一转变使企业能够大规模自动化处理诸如潜在客户资质审核和客户支持等高频通信任务。通过将 AI 智能体视为具备邮件功能的实体，企业可以显著提高生产力并简化跨平台流程自动化。 现代实现方案通常利用 n8n 等平台或专用 API，将 GPT-4 或 Claude 等大语言模型连接到 Gmail 或 IMAP 触发器。与传统的静态邮件自动化不同，这些智能体利用推理能力来处理动态且非确定性的邮件内容。

rss · AI Productivity and Monetization · 9月6日 04:05

**背景**: 传统的电子邮件自动化依赖于静态的、基于规则的触发器，即特定的输入会导致预定义的模板回复。相比之下，自主电子邮件工作流使用 AI 智能体来理解上下文、提取数据并执行多步骤操作，例如更新 CRM 记录或安排会议。这种转变标志着从简单的“如果-那么”逻辑向智能化的智能体交互迈进。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/posts/muhammad-omar-46665a209_ai-aiagent-automation-activity-7427304386852192256-SiyP">AI Agent Architecture : Intelligent Assistant with Calendar... | LinkedIn</a></li>
<li><a href="https://www.betterclaw.io/blog/ai-agent-gmail-safe-setup">Connect AI Agent to Gmail Safely (2026 Guide)</a></li>
<li><a href="https://resources.mailertogo.com/glossary/autonomous-email-workflow">Autonomous Email Workflows : Definition & Infrastructure Guide</a></li>

</ul>
</details>

**社区讨论**: 社区讨论强调了智能体自主性与安全性之间的平衡，用户特别指出需要安全设置协议以防止未经授权的操作。许多开发者正在积极探索如何利用低代码工具将这些智能体集成到现有的技术栈中。

**标签**: `#AI Agents`, `#Automation`, `#Productivity`, `#SaaS`, `#Workflow Optimization`

---

<a id="item-5"></a>
## [微软推出基于人工智能的 WinUI 3 应用快速开发工作流](https://news.google.com/rss/articles/CBMia0FVX3lxTFBfTlJGNU9idlY5ek1fa0JrT19mbzJWQjlBaU5yck1oUFlMX3lKRmpFZ3J3QjROZUZ3aHlNSy00V2FWV0pxaGI0eGgzc3A1eUNRTi1WODhvcW05M2RXaFhmcHVaUFNhQmotdTVB?oc=5) ⭐️ 7.0/10

微软推出了一套全新的 AI 驱动工作流，使开发者能够利用 VS Code 和命令行工具在约 30 分钟内完成 WinUI 3 应用程序的构建与发布。 该工作流通过自动化复杂的部署流程，显著降低了软件开发和商业化的门槛，使个人能够以极低的编码成本快速原型化并发布商业软件工具。 该流程将 AI 自动化直接集成到开发周期中，简化了从初始代码编写到最终应用程序部署在 Windows App SDK 生态系统中的转换过程。

rss · AI Productivity and Monetization · 9月6日 23:22

**背景**: WinUI 3 是 Windows App SDK 的一部分，是一个现代化的原生用户界面框架，旨在将 UI 组件与操作系统解耦，从而实现更快的更新。它允许开发者使用 XAML 和 C# 为 Windows 10 和 11 构建一致且现代化的桌面应用程序。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WinUI_3">WinUI 3</a></li>
<li><a href="https://grokipedia.com/page/WinUI_3">WinUI 3</a></li>

</ul>
</details>

**标签**: `#AI Productivity`, `#Software Development`, `#Monetization`, `#Automation`, `#Microsoft`

---

<a id="item-6"></a>
## [PINNStudio：用于物理信息神经网络的免费开源无代码图形界面](https://www.reddit.com/r/MachineLearning/comments/1w9a2i7/pinnstudio_a_free_opensource_nocode_gui_for/) ⭐️ 7.0/10

PINNStudio 是一个全新的开源无代码图形用户界面，旨在自动化物理信息神经网络（PINN）的设置、训练和可视化过程。用户可以通过该界面定义偏微分方程（PDE）、边界条件和网络架构，而无需编写繁琐的样板代码。 该工具通过抽象化复杂的编码任务，显著降低了科学机器学习的入门门槛，使研究人员能够专注于物理本身而非软件实现。它简化了科学研究中正向和反向问题的求解流程。 PINNStudio 基于 DeepXDE 库构建，支持一维和二维域以及耦合的多输出 PDE 系统，并提供损失曲线和解图的实时监控。它还内置了诸如热方程、Allen-Cahn 方程和 Cahn-Hilliard 方程等经典方程的模板。

reddit · r/MachineLearning · /u/Impossible-Jello2749 · 9月6日 22:19

**背景**: 物理信息神经网络（PINN）是一类深度学习模型，旨在通过在训练过程中将物理定律作为约束条件来求解微分方程。在科学计算中，正向问题涉及根据已知参数预测系统行为，而反向问题则涉及从观测数据中估计未知的物理参数。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@keerthi9706/physics-informed-neural-networks-explained-c458b3deeab9">Physics - Informed Neural Networks Explained | by Keerthi... | Medium</a></li>
<li><a href="https://kks32-courses.github.io/sciml/01-pinns/inverse-heat.html">Inverse analysis - Scientific Machine Learning (SciML)</a></li>

</ul>
</details>

**社区讨论**: 社区对该项目表现出了浓厚兴趣，特别是对这种能够简化那些更侧重于物理而非软件工程的研究人员工作流程的努力表示赞赏。

**标签**: `#AI Productivity`, `#Scientific Machine Learning`, `#No-Code`, `#Automation`, `#Research Tools`

---

<a id="item-7"></a>
## [比特币矿工转向人工智能，基础设施收入激增 52%](https://news.google.com/rss/articles/CBMiV0FVX3lxTE1rQ2cybUdQYmtKUW5GaTRsRWJXZDg1M3V0cF90NEhpU0Z4VFdOOFJkUXo3WDNyUmJRanZubG9oNUUzX3lhODRUb1NORGxRbHJ6eGlFeGMzVQ?oc=5) ⭐️ 6.0/10

比特币矿工已将其挖矿业务削减了 23%，同时将来自人工智能相关基础设施服务的收入提高了 52%。这一转变反映了他们将现有的数据中心电力和设施重新用于高性能计算的战略举措。 这一趋势凸显了计算经济的重大结构性转变，矿工们正在放弃波动剧烈的加密货币挖矿周期，转而追求人工智能基础设施更稳定、更丰厚的利润。这表明电力采购和场地就绪性正成为人工智能供应链中最宝贵的资产。 虽然专门的比特币挖矿芯片（ASIC）无法用于人工智能训练，但其物理基础设施（如大容量电网和冷却系统）与人工智能数据中心的需求高度兼容。这种转型使矿工能够在供应受限的市场中将其现有的能源合同和房地产变现。

rss · AI Productivity and Monetization · 9月6日 20:14

**背景**: 比特币挖矿需要大量的电力和专用硬件来解决复杂的加密难题。随着人工智能行业在寻找具有足够电力容量的数据中心方面面临全球性瓶颈，比特币矿工凭借其在能源丰富地区已建立的设施，成为了关键参与者。这种转型通常被称为“计算经济”，即提供可靠电力和 GPU 集群空间的能力与软件本身一样至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/posts/alchematician_investmentmanagement-assetmanagement-artificialintelligence-activity-7467937594241236993-5KyT">Bitcoin Miners Repurpose Infrastructure for AI Cloud... | LinkedIn</a></li>
<li><a href="https://holder.io/news/bitcoin-miners-repurpose-for-ai-demand/">Bitcoin Miners Repurpose Infrastructure for AI ’s Growing Demand</a></li>
<li><a href="https://www.okx.com/en-ae/learn/cipher-mining-ai-infrastructure-pivot">Cipher Mining AI : How This Bitcoin Miner is Transforming... | OKX UAE</a></li>

</ul>
</details>

**社区讨论**: 社区普遍认为这是一种务实的生存策略，并指出人工智能公司提供的长期合同比不可预测的比特币挖矿奖励提供了更好的财务稳定性。一些观察人士提醒说，人工智能数据中心的技术要求比简单的挖矿更为复杂，可能会给矿工带来运营挑战。

**标签**: `#AI Infrastructure`, `#Data Centers`, `#Compute Economics`, `#Market Trends`

---

<a id="item-8"></a>
## [将金融交易委托给 AI 代理的风险与潜力探讨](https://news.google.com/rss/articles/CBMilAFBVV95cUxOdWJVYTRVcmNxWUUxN0VzM2xMa3VwcUk0cW5ucUl4SWlEdjVBeFJRajJDRnEtUy1nUkpIWHZUQm1XV1ZjV2NKUjBlZG5XaW5fNkt5SkZIcU5WSVU1UmZEVGJzdV9fRjhtOV9lN0Jsb25sSEZmYkZmLXZNUFRqcTdKcnNyRUc4M1lXT0FxZlVmeHpUVHBm0gGQAUFVX3lxTE1QVUhmaVNkVGkybmlJMGJzak95VFdHSzJrT2JGWGh4RXBzRFAwUkF5dzlPczNQVUZZQlpYUGVRdDBBYjhJYnJHbjRqSUR3Tjg5SWgwNHBsWUZXUWdTRm52cFdtVTdnajd6Y3MwQUluXzZwWkFpd2FIbm1wa19wYWpWNTYteVpyVlRFVGJuM2FhXw?oc=5) ⭐️ 6.0/10

近期的讨论强调了使用自主 AI 代理执行金融交易的增长趋势，并对这些系统的安全性和可靠性提出了关键质疑。讨论的核心在于这些系统是否已经准备好在无需人工干预的情况下管理现实世界的资金。 随着 AI 代理能力的增强，它们在金融领域的整合可能会彻底改变交易效率，但也带来了灾难性财务损失的重大风险。对于在金融科技未来中探索的投资者和开发者来说，理解这些权衡至关重要。 自主交易系统面临技术故障、模型错误以及过度拟合历史数据的风险。有效的部署需要强大的基础设施、严格的治理机制以及持续的人工监督，以减轻潜在的故障影响。

rss · AI Productivity and Monetization · 9月6日 13:12

**背景**: 算法交易涉及使用计算机程序根据预定义的标准执行交易，现已演变为能够自主决策的更复杂的“代理式”AI。传统的算法遵循严格的规则，而现代 AI 代理利用机器学习实时适应市场状况。这种转变代表了从简单的自动化向更复杂、自我管理的金融工具的演进。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/from-wall-street-analysts-autonomous-financial-agents-ai-ready-hub-4eqqc">From Wall Street Analysts to Autonomous Financial Agents</a></li>
<li><a href="https://zitaplus.com/blog/expert-advisors/risks-in-algorithmic-trading/">Risks in Algorithmic Trading | ZitaPlus</a></li>
<li><a href="https://groww.in/blog/hft-vs-algorithmic-trading">High-Frequency Trading vs. Algorithmic Trading : Overview, Key...</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#Algorithmic Trading`, `#Fintech`, `#Automation`

---