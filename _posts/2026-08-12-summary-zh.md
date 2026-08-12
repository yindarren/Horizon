---
layout: default
title: "Horizon Summary: 2026-08-12 (ZH)"
date: 2026-08-12
lang: zh
---

> 从 123 条内容中筛选出 11 条重要资讯。

---

1. [Qwen3.8-2.4T：一款全新的超大规模开源 MoE 模型](#item-1) ⭐️ 8.0/10
2. [如何在单个代码库上协同运行两个 AI 编程代理](#item-2) ⭐️ 8.0/10
3. [DeepSeek 通过 OpenRouter 发布高性能 V4 Pro 0813 模型](#item-3) ⭐️ 7.0/10
4. [Ahrefs 为营销人员和代理商推出 AI 智能体工作空间 Letaido](#item-4) ⭐️ 7.0/10
5. [“流氓模型”风暴：如何管理自主代理式 AI 系统](#item-5) ⭐️ 7.0/10
6. [全球对冲基金投资重心从人工智能基础设施转向人工智能商业化](#item-6) ⭐️ 7.0/10
7. [LegalZoom 部署代理式 AI 以提升效率并实现客户支持自动化](#item-7) ⭐️ 7.0/10
8. [NVIDIA 发布 Nemotron 3.5 Lightning 以优化 AI 智能体工作流](#item-8) ⭐️ 7.0/10
9. [2026 年保加利亚数字游民签证：远程工作者申请要求指南](#item-9) ⭐️ 7.0/10
10. [Zed 推出 Delta，旨在实现协作式 AI 辅助编程](#item-10) ⭐️ 6.0/10
11. [嘉信理财推出超过 50 只美股的个股期货合约](#item-11) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Qwen3.8-2.4T：一款全新的超大规模开源 MoE 模型](https://huggingface.co/Qwen/Qwen3.8-2.4T-A95B) ⭐️ 8.0/10

Qwen3.8-2.4T 作为一款超大规模混合专家模型（MoE）正式发布，其性能可媲美 Opus 和 Fable 等前沿模型。该模型提供 bf16 和 fp8 格式，支持在高端本地环境中部署以处理复杂的 AI 工作流。 此次发布为开发者和企业提供了接近前沿水平的 AI 能力，且支持在私有基础设施上托管，从而降低了对闭源 API 的依赖。这标志着高性能开源模型在可访问性方面迈出了重要一步。 该模型每个 MoE 拥有 950 亿激活参数，对硬件要求极高，完整的无损 BF16 版本体积高达 4.9TB。尽管性能强劲，但用户指出开源版本缺少官方“Max”版中的部分功能，如原生视觉支持和 100 万上下文长度。

hackernews · Philpax · 8月12日 15:01 · [社区讨论](https://news.ycombinator.com/item?id=49273478)

**背景**: 混合专家模型（MoE）是一种利用多个专业子网络处理数据的架构，能够在保持计算效率的同时实现超大规模参数量。量化是一种降低模型权重精度（例如从 16 位降低到 8 位或更低）的技术，旨在减少内存占用并提升推理速度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained - Hugging Face</a></li>

</ul>
</details>

**社区讨论**: 社区对该模型的性能印象深刻，但也强调了硬件需求和缺乏量化感知训练（QAT）带来的挑战。讨论还涉及了针对高营收实体的许可限制，并将其与其他新兴模型（如 DeepSeek V4-Pro）进行了对比。

**标签**: `#AI`, `#LLM`, `#OpenWeights`, `#Productivity`, `#Infrastructure`

---

<a id="item-2"></a>
## [如何在单个代码库上协同运行两个 AI 编程代理](https://news.google.com/rss/articles/CBMieEFVX3lxTE9VRmtDcVh3ODhESHBTa2s3V2FjTlpxZHA1X1pvaDMwQjBiN2Y5S3hScktQM2RBZXJ6R3dqTlZGeDQxZHBCOTZhQnlaZHA1UExYZTk4Z0hPYUNwSFhIS05nM1NjR2N4YWRCYWIwb0JPeFhOaVE0NXJaaQ?oc=5) ⭐️ 8.0/10

本文概述了一种在单个代码库上同时运行两个 AI 编程代理的实用工作流程，旨在提高开发速度。它展示了开发者如何管理多个代理以并行处理任务，而无需人工干预。 这种方法将开发者的角色从独立编码者转变为团队管理者，通过自动化复杂的软件任务显著提高了生产力。它凸显了多代理编排在现代软件工程中日益增长的趋势。 该工作流程强调了管理上下文窗口和异步任务执行以防止冲突的重要性。它为希望扩展 AI 辅助编码工作的开发者提供了一个基础指南。

rss · AI Productivity and Monetization · 8月12日 20:18

**背景**: AI 编程代理是专门用于自动化编写代码、调试和测试等任务的软件程序。多代理编排涉及协调多个此类代理在共享代码库上工作，模拟人类开发团队的协作。随着开发者寻求超越单一模型交互，转向协作式 AI 系统，这一领域正在迅速发展。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.augmentcode.com/tools/open-source-agent-orchestrators">9 Open-Source Agent Orchestrators for AI Coding (2026) | Augment Code</a></li>
<li><a href="https://vibecoding.app/blog/multi-agent-software-development-workflow">Multi - Agent Software Development : Complete Guide</a></li>
<li><a href="https://addyosmani.com/blog/code-agent-orchestra/">AddyOsmani.com - The Code Agent Orchestra - what makes multi-agent coding work</a></li>

</ul>
</details>

**社区讨论**: 开发者社区对多代理编排表现出浓厚兴趣，并将其视为 AI 编程的未来。讨论通常集中在冲突解决的技术挑战以及通过运行并行代理所获得的效率提升上。

**标签**: `#AI Agents`, `#Coding Productivity`, `#Software Development`, `#Automation`

---

<a id="item-3"></a>
## [DeepSeek 通过 OpenRouter 发布高性能 V4 Pro 0813 模型](https://openrouter.ai/deepseek/deepseek-v4-pro-0813) ⭐️ 7.0/10

DeepSeek 推出了 V4 Pro 0813 模型，现已在 OpenRouter 平台上提供，具备先进的编程和推理能力。该版本旨在为现有的行业领先 AI 模型提供一种高性能的替代方案。 该模型定位为一种极具成本效益的选择，其价格比某些顶级竞争对手便宜约 20 倍，同时保持了极具竞争力的性能。这使得开发人员能够以更低的开销将强大的 AI 集成到工作流中。 虽然该模型性能强劲，但用户测试表明，在复杂的、多步骤的编程任务中，它可能仍落后于 GPT-5.6 或 Fable 5 等高端模型。它采用了以高效和低推理成本著称的 DeepSeek V4 架构。

hackernews · explosion-s · 8月12日 16:04 · [社区讨论](https://news.ycombinator.com/item?id=49274600)

**背景**: OpenRouter 是一个统一的 API 平台，允许用户通过单一接口访问并切换数百种不同的 AI 模型。DeepSeek 是一家人工智能研究机构，以开发利用多头潜在注意力（MLA）和混合架构来优化性能并降低计算成本的模型而闻名。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>
<li><a href="https://hfviewer.com/deepseek-ai/DeepSeek-V4-Flash-0731">Architecture graph for deepseek -ai/ DeepSeek - V 4 -Flash-0731</a></li>

</ul>
</details>

**社区讨论**: 社区反馈褒贬不一；虽然用户赞赏其显著的成本优势，但一些人指出，与更昂贵的替代方案相比，该模型在处理复杂编程任务时仍显吃力。开发人员注意到，尽管它效率很高，但在复杂的软件项目中可能需要更多的调试工作。

**标签**: `#AI`, `#LLM`, `#Productivity`, `#OpenRouter`, `#Coding`

---

<a id="item-4"></a>
## [Ahrefs 为营销人员和代理商推出 AI 智能体工作空间 Letaido](https://news.google.com/rss/articles/CBMinwFBVV95cUxNWHl0LVRoYlh1eXFONzkxdVJURlVJTFZFc0tCaW5mZHk2WFVIR09XTVk0cmQwSEowM1prUVFTNE4xa2FxZXowYlczZGpkYXpiaDNtcTZPa2RpODNmQVlaYTM2VS1oaERjMGFDRTc5QVNscjBjY05PdEZzWXkyTWZ6dXNnQ2hvQ2RKaEV5dUdWTkNkODJ1TUFvWXNUblFzdjA?oc=5) ⭐️ 7.0/10

Ahrefs 推出了名为 Letaido 的 AI 驱动工作空间，旨在为营销代理商自动化复杂的营销工作流并简化运营流程。该平台允许用户部署 AI 智能体来处理重复性任务，并更高效地管理内容生产。 此次发布标志着 Ahrefs 从传统的 SEO 工具集向智能体平台的重要转型，为营销人员提供了即时的生产力提升。这也反映了行业向自主系统发展的趋势，即通过 AI 智能体以最少的人工干预执行端到端的营销活动。 Letaido 作为一个集成工作空间运行，其中的 AI 智能体能够针对营销场景进行推理并采取具体行动。该产品专门针对数字营销代理商和独立创业者所面临的运营瓶颈而设计。

rss · AI Productivity and Monetization · 8月12日 13:00

**背景**: AI 智能体是能够感知环境、对复杂任务进行推理并执行操作以实现特定目标的自主系统。在营销领域，这些智能体正越来越多地被用于自动化营销活动规划、内容创作和网站管理，从而减少了对人工干预的需求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.razorsharpdigital.com/blog/autonomous-ai-agents-in-marketing/">Autonomous AI Agents in Marketing : The Future of Campaigns That...</a></li>
<li><a href="https://www.graphed.com/blog/ai-agents-for-marketing-complete-guide">AI Agents for Marketing : A Complete Guide to Autonomous Marketing</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#Marketing Automation`, `#Productivity`, `#SaaS`

---

<a id="item-5"></a>
## [“流氓模型”风暴：如何管理自主代理式 AI 系统](https://news.google.com/rss/articles/CBMiaEFVX3lxTFAtVDZIOGxRdGhpanRKeklGUWhkV3VwdTBYT1pQemNVOFYyYVpZN3FfVVg0cENkSGNYcjhYbzNLVXRnWXlaX3FGOU5OSmpTel9YN09zanNlSFlSekpGV0tkN1lBNHZpd3FQ?oc=5) ⭐️ 7.0/10

本文概述了在部署自主代理式 AI 时保持人类监督和控制的策略，以防止出现不可预测或有害的运营结果。文章强调了实施稳健的治理框架对于降低高自主性 AI 系统相关风险的必要性。 随着代理式 AI 成为生产力的标准，了解如何防止“流氓”行为对于个人和团队避免重大的财务或运营损失至关重要。适当的风险管理确保组织在利用自动化的同时，能够保持与业务目标和安全标准的一致性。 报告指出，与传统模型不同，代理式 AI 系统表现出目标驱动的行为和适应性，这需要定制化的测试和调整。建议组织采用如 NIST AI RMF 或 ISO 42001 等框架，以系统地识别和降低风险。

rss · AI Productivity and Monetization · 8月12日 10:25

**背景**: 代理式 AI 是指能够进行自主、目标导向决策的系统，通常协调多个代理来完成复杂的工作流程，而无需人类持续干预。随着这些系统超越简单的任务执行，它们带来了新的安全和运营挑战，包括产生意外行为或“流氓”行为的可能性。在此背景下，有效的风险管理涉及建立明确的治理、安全基础设施和持续监控。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/agentic-ai">What is Agentic AI? | IBM</a></li>
<li><a href="https://www.obsidiansecurity.com/blog/agentic-ai-security">From Agentic AI to Autonomous Risk: Why Security Must Evolve</a></li>
<li><a href="https://www.pwc.com/us/en/industries/tmt/library/trust-and-safety-outlook/rise-and-risks-of-agentic-ai.html">The rise and risks of agentic AI: PwC</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#Automation`, `#Productivity`, `#Risk Management`

---

<a id="item-6"></a>
## [全球对冲基金投资重心从人工智能基础设施转向人工智能商业化](https://news.google.com/rss/articles/CBMi5wFBVV95cUxNbkNXRU5CaWRLeVhJNENLQnkxdC1XQjk1NG9GRlduOGg1Q2RCenlVR2x2NHBrT0ZrSjNHdWdzQl94c0xZQ2FSeTVlSVJkTHlpcmlaZXpGejBiQUx3ZmVkM2plRGZfZ2FLTXBQcXFMSlJxY283V09lZF8zY1FNamZQaURKQ21pcURyR3Q5ZEZEZHhQQ3E4ZndTbmtKN0lIQ2Y0c3VFVjZRZ0lNTzVIc2NGRW5DakQ2Vm5nVENTTVVQSnNpYXhWX3ZKRllNU1FiQTBSOU1QS2dsNVdXUlNTZzVHdjNRWW1QUlE?oc=5) ⭐️ 7.0/10

七月份，机构对冲基金开始将其资本从人工智能基础设施提供商转向那些能够展示切实人工智能驱动收入和商业化策略的公司。这一转变标志着投资者优先事项从基础硬件层向应用和软件层的过渡。 这种轮动表明，投资者在初始建设阶段之后，正日益寻求人工智能投资的长期可持续性和价值证明。这凸显了一个正在成熟的市场，即从人工智能工具中获取利润的能力正变得与底层技术本身一样关键。 这一趋势反映了市场向利用多样化收入模式的公司靠拢，例如订阅价格上涨、基于代币的使用费或基于消费的计费模式。对于追踪纳斯达克 100 指数中大型科技股表现的投资者而言，这种转向尤为重要。

rss · AI Productivity and Monetization · 8月12日 13:00

**背景**: 人工智能基础设施通常指构建人工智能系统所需的硬件、数据中心和基础模型，而人工智能商业化则涉及公司将这些能力转化为经常性收入的策略。从历史上看，“基础设施阶段”见证了大量资本流入芯片制造商和云服务提供商，因为它们为人工智能热潮构建了必要的骨干。随着行业成熟，重心自然转向“应用阶段”，公司必须证明他们能够通过这些昂贵的工具获利，以证明其估值的合理性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.revenera.com/resources/SWM-wb-monetizing-ai:-comparing-pricing-models-and-monetization-strategies">Monetizing AI: Comparing Pricing Models and Monetization Strategies</a></li>
<li><a href="https://www.zuora.com/glossary/ai-monetization/">AI Monetization: Key Concepts for Finance Leaders - Zuora</a></li>
<li><a href="https://enterprise-ai.io/knowledge/what_are_the_most_effective_ai_powered_investment_strategies_for_2026.php">What are the most effective AI powered investment ... | enterprise- ai .io</a></li>

</ul>
</details>

**标签**: `#AI Investment`, `#Nasdaq-100`, `#Market Trends`, `#AI Monetization`

---

<a id="item-7"></a>
## [LegalZoom 部署代理式 AI 以提升效率并实现客户支持自动化](https://news.google.com/rss/articles/CBMirAFBVV95cUxPOTVNY3FmTDd0ckVhU1pqdkVWdTI2OFBCM21EOHNlS0d5cmFBRVZNWlpPbmFOSDBwTVVXS1EwaXpPbnJiZTQtTDZDRHVkUW9YSDlycUg0VXVHZjduWFJTUjU1MDRXVnBrZkRKU21OMTgxMU8xVnpablJsTGtkZ1hxa3VTY2I1UlVwc3RfdnRIczN1UWluYVc3RFVFckZ2djVmbzNDVmxtaXBmVk5T0gGyAUFVX3lxTE5INHN2OHREczJoT21rX2x4WUd0X3J0bnBzWG9SMHZYMkFLdk5VTTMxWkJnXzZyYlp2aC1hNWZqdUJyVktJejNuTENXdVRKa0g2dnZ4aGZnWG94eTlHdnpWS3lUbkUxUFpxam5vQl90Vjc2bjU5LWROZGJ0eWoyVzU3MFU4TElrQVJjUDNKOUMtbGhtZkstd3NfMHNqMDRrU3IyR3duS2duTF9RaFF5a2JVdlE?oc=5) ⭐️ 7.0/10

LegalZoom 已成功部署代理式 AI 系统，自主解决了 40% 的客户咨询，并将商标检索所需的时间缩短了 55%。 这一部署展示了代理式 AI 在专业服务领域带来的切实投资回报，为自动化处理复杂的、多步骤的业务流程提供了一个可扩展的范例。 该系统利用代理式工作流来协调任务，超越了简单的聊天机器人回复，在法律运营中实现了主动的、以目标为导向的问题解决能力。

rss · AI Productivity and Monetization · 8月12日 12:18

**背景**: 代理式 AI 是指能够通过规划步骤、做出决策并使用各种工具来自主实现特定目标的系统。与传统的反应式 AI 不同，这些系统能够主动发起行动并适应环境，因此在复杂的业务自动化场景中非常有效。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.hostinger.com/my/tutorials/what-is-agentic-ai">What is agentic AI ?</a></li>
<li><a href="https://www.ibm.com/think/topics/agentic-workflows">What are Agentic Workflows? | IBM</a></li>

</ul>
</details>

**标签**: `#AI Productivity`, `#Agentic Workflow`, `#Business Automation`, `#LegalTech`, `#Operational Efficiency`

---

<a id="item-8"></a>
## [NVIDIA 发布 Nemotron 3.5 Lightning 以优化 AI 智能体工作流](https://news.google.com/rss/articles/CBMisgFBVV95cUxNRENuWFJ4QlJTOGswbi0wOGI3Mk9iTk9IZ2tSRHYtM21NLWs1d1BybV9LOUVEUlloR3U4Q0hLbmJkWkJ0OW1XVW8zUFFWYzg0WEZrbW42NVZEX254aGlxYlpwTHZ4b1Y1cmFCQ085NXRreGN3OXY1MXVVWWltUU1PZjhvdTVjRlZ3TkM3R2ZuNXVkd2FuVWZBUnFmOEQwMmIxblpDb0N6a3ZLWXlwQ0dOQ2tn?oc=5) ⭐️ 7.0/10

NVIDIA 推出了 Nemotron 3.5 Lightning，这是一款专为简化 AI 智能体执行日常重复性任务而设计的高速模型。它采用混合架构，在保持低延迟的同时提供高性能表现。 该模型的重要性在于它降低了智能体 AI 的计算成本和延迟，使得在本地系统、边缘设备和云环境中部署自动化智能体变得更加实用。它为开发者构建可扩展的 AI 自动化提供了关键的基础组件。 该模型采用混合专家模型（MoE）架构，结合了 30B 总参数和 3B 激活参数，并使用了交错的 Mamba-2 和 MoE 层。它由 NVIDIA 的前沿模型 Nemotron 3 Ultra 蒸馏而来，以确保在紧凑的规格下具备高性能。

rss · AI Productivity and Monetization · 8月12日 09:30

**背景**: AI 智能体是能够通过与工具和软件交互来执行复杂多步任务的自主系统。推理优化技术（如量化和蒸馏）对于在资源受限的硬件上高效运行这些大型模型至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://build.nvidia.com/nvidia/nemotron-3.5-lightning-30b-a3b/modelcard">nemotron - 3 . 5 - lightning -30b-a3b Model by NVIDIA | NVIDIA NIM</a></li>
<li><a href="https://lmstudio.ai/models/nvidia/nemotron-3.5-lightning">nvidia / nemotron - 3 . 5 - lightning • LM Studio</a></li>
<li><a href="https://huggingface.co/nvidia/NVIDIA-Nemotron-3.5-Lightning-30B-A3B-BF16">nvidia / NVIDIA - Nemotron - 3 . 5 - Lightning -30B-A3B-BF16 · Hugging Face</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#NVIDIA`, `#Automation`, `#Productivity`, `#LLM Optimization`

---

<a id="item-9"></a>
## [2026 年保加利亚数字游民签证：远程工作者申请要求指南](https://news.google.com/rss/articles/CBMijwFBVV95cUxPU09DcHVabHZqY21DU3JVNjVQTjhXZ0w1TkRpNWc4dTk5RkpFNXd6UGRoMzhHdE5wQVJtVXR0bDkzZGx6b21XOW1fT0lkWjBzc1hHNnlrV0I4cFZ5YnVGV0dXcUU3TFlQNzItLTJYVWZVTnhXTFVqdnpKQ290THlsdVZ6T2NTQkF5TG9TWnd6MA?oc=5) ⭐️ 7.0/10

保加利亚在 2026 年继续提供数字游民签证，为希望在索非亚和班斯科等中心城市生活的远程工作者提供了低成本的居留途径。该项目允许符合条件的个人在保加利亚合法居住，同时维持其远程工作状态。 该签证是进入欧盟和申根区的战略切入点，为非欧盟公民提供了显著的流动性优势。对于寻求欧洲居留权的远程工作者来说，这仍然是最具成本效益的选择之一。 申请人必须满足特定的收入门槛并提供远程工作证明。虽然该签证有助于获得居留权，但需要注意的是，它并不直接提供通往永久公民身份的途径。

rss · Global Mobility and Residency · 8月12日 06:52

**背景**: 申根区是由 29 个取消了内部边境管制的欧洲国家组成的体系，允许人员自由流动。自 2025 年底起，欧盟实施了出入境系统（EES），利用生物识别数据严格监控非欧盟公民的停留时间。数字游民签证是一种国家级许可，允许远程工作者在特定国家合法长期居住，通常可以规避标准旅游签证的限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Schengen_Area">Schengen Area - Wikipedia</a></li>
<li><a href="https://www.remotifyeurope.com/blog/every-digital-nomad-visa-in-europe-compared-eligibility-cost-timeline-2026-update">Digital Nomad Visas in Europe (2026): Costs, requirements and ...</a></li>

</ul>
</details>

**标签**: `#Digital Nomad Visa`, `#Bulgaria`, `#EU Residency`, `#Global Mobility`, `#Remote Work`

---

<a id="item-10"></a>
## [Zed 推出 Delta，旨在实现协作式 AI 辅助编程](https://zed.dev/blog/introducing-delta) ⭐️ 6.0/10

Zed 推出了 Delta，这是一种将 AI 对话视为可协作、可编辑文档的新界面。它允许开发人员在共享的持久工作区中与 AI 代理进行交互，而不是使用传统的聊天窗口。 Delta 将 AI 辅助编程从个人体验转变为团队协作工作流，从而促进了更好的指导和代码审查。它允许开发人员实时检查并优化 AI 代理生成的逻辑。 该界面支持实时多人协作，允许用户在 AI 生成的文档中进行内联评论。其目标是弥合 AI 输出与人类可读代码文档之间的差距。

hackernews · khy · 8月12日 18:19 · [社区讨论](https://news.ycombinator.com/item?id=49276574)

**背景**: Zed 是一款高性能的开源代码编辑器，专为协作开发和代理工作流而设计。它旨在快速处理大型代码库，并与各种 AI 模型深度集成，以辅助软件工程任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zed.dev/ai">Zed — The AI Code Editor Built for Speed</a></li>

</ul>
</details>

**社区讨论**: 社区反馈褒贬不一；一些用户赞赏其在指导和协作调试方面的潜力，但也有人对 AI 生成摘要的价值表示怀疑，并批评了该网站低对比度的设计。

**标签**: `#AI Productivity`, `#Software Development`, `#Collaboration Tools`, `#Coding Agents`

---

<a id="item-11"></a>
## [嘉信理财推出超过 50 只美股的个股期货合约](https://news.google.com/rss/articles/CBMi2AFBVV95cUxNcUxicXVQUUl4OHNYQWFLd09kbHIxWks1cU9WLUt1RG1sWXFITzNNQWVuXzZDVUhGZXk0ZnV1ajNvV3AyRHdrUHp0blVzdEVWbHhLdklvMFEzVm9sUlRKWThwU3ViNV9qS3VRWDVOd3FfbGd4d2h3WDlyaDJxelN2bGF2bFpKS1ptT2F1djNVQ0FIWEVVOGhqc0FfZkFFejRZQjBaZzM0SWwzdVp3T0U4ZUhqUmVwYkc3RzZXNGhJYkd3Y3AyTzlaZVUxMm0tbms1LVpES0xmcnc?oc=5) ⭐️ 6.0/10

嘉信理财（Charles Schwab）已为标普 500 指数和纳斯达克 100 指数中的 50 多家大型公司推出了个股期货。这些新的金融工具允许投资者通过期货合约获取个股的投资敞口。 这一扩展为投资者提供了更复杂的工具，用于对冲现有股票头寸并在投资组合中利用杠杆。通过为交易大型美股提供更高的资本灵活性，这进一步提高了市场效率。 这些合约采用现金结算，意味着投资者在到期时并不持有标的股票。这些工具提供 23 小时的市场准入，为跨时区交易的投资者提供了极大的灵活性。

rss · QQQ and Nasdaq 100 · 8月12日 13:13

**背景**: 个股期货是一种衍生品合约，其标的资产是单只股票而非指数。衍生品在金融领域通常用于对冲（即作为抵御价格下跌的保险）或通过杠杆进行投机以放大潜在收益。由于杠杆交易存在固有风险，这些产品通常仅限于合格投资者参与。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.schwab.com/learn/story/single-stock-futures-what-they-are-how-to-use">What Are Single Stock Futures? | Charles Schwab</a></li>
<li><a href="https://www.cmegroup.com/markets/equities/single-stock-futures">Single Stock Futures - CME Group</a></li>
<li><a href="https://investingintheweb.com/brokers/single-stock-futures/">What are single stock futures? CME's 2026 launch explained</a></li>

</ul>
</details>

**标签**: `#US Equities`, `#Nasdaq-100`, `#Financial Derivatives`, `#Charles Schwab`, `#Investment Strategy`

---