---
layout: default
title: "Horizon Summary: 2026-10-03 (ZH)"
date: 2026-10-03
lang: zh
---

> 从 108 条内容中筛选出 11 条重要资讯。

---

1. [GitGuardian ggshield 设置指南：13 步阻止 AI 编码过程中的敏感信息泄露](#item-1) ⭐️ 8.0/10
2. [DwarfStar (ds4)：Redis 创建者推出的高性能本地大模型运行工具](#item-2) ⭐️ 7.0/10
3. [使用 GLM-5.3 Flash 进行原型开发的第一个月](#item-3) ⭐️ 7.0/10
4. [Docker Sandbox Kit 规范：将 AI 代理权限打包为 OCI 镜像](#item-4) ⭐️ 7.0/10
5. [创业者将 AI 智能体视为自主同事，成功实现业务规模化](#item-5) ⭐️ 7.0/10
6. [Shopify Canvas：代理式 AI 消除定制化网店门槛](#item-6) ⭐️ 7.0/10
7. [OpenAI 推出 Dot，一款用于处理业务任务和在线订单的 AI 智能体](#item-7) ⭐️ 7.0/10
8. [恶意邮件可劫持 AI 代理并访问关联账户](#item-8) ⭐️ 7.0/10
9. [Moderna 将取代华纳兄弟探索公司进入纳斯达克 100 指数](#item-9) ⭐️ 6.0/10
10. [为何年轻投资者应考虑将纳斯达克 100 指数 ETF 作为长期退休规划](#item-10) ⭐️ 6.0/10
11. [FLEET 算法通过记忆增强的 MCTS 提升大语言模型生成效率](#item-11) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [GitGuardian ggshield 设置指南：13 步阻止 AI 编码过程中的敏感信息泄露](https://news.google.com/rss/articles/CBMigwFBVV95cUxOS2RQeEhXSGpGaGc3Sk5VX1BaVHhfbXAxWGJqdDBZajlaMGdVQzN2TVJKY2lsaTk2aVZXOHVPQmF1dXBIUFR4VUJwdWh1bDNYcnR1elRKRW52dUU2bHJzdk9nbUV1clRaZ3llelFlWjBNR1hPSE5taTZrU25OZHFaR1FTSQ?oc=5) ⭐️ 8.0/10

本指南提供了一套包含 13 个步骤的完整工作流程，旨在将 GitGuardian 的 ggshield 集成到开发环境中，从而在 AI 辅助编码过程中自动检测并阻止敏感数据泄露。 随着开发者对 AI 工具的依赖日益增加，将私有 API 密钥或凭据意外提交到公共仓库的风险显著上升。在现代 DevOps 流水线中实施自动化的密钥扫描对于维护稳健的安全性至关重要。 该设置重点在于利用 ggshield，这是一个开源的命令行工具，通过与 GitGuardian API 交互来扫描代码中超过 500 种类型的敏感信息。用户需注意，该工具不会扫描超过 1MB 的文件或二进制文件。

rss · AI Productivity and Monetization · 10月2日 08:22

**背景**: GitGuardian 是一个专注于检测源代码中硬编码密钥（如 API 密钥、数据库凭据和证书）的网络安全平台。ggshield 作为本地封装工具，允许开发者直接从命令行运行这些安全检查，或将其作为 CI/CD 流程的一部分，从而在代码推送到仓库之前防止泄露。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gitguardian.com/ggshield">ggshield - Detect secrets in source code from your CLI | GitGuardian</a></li>
<li><a href="https://github.com/GitGuardian/ggshield">GitHub - GitGuardian / ggshield : Detect and validate 500+ types of...</a></li>
<li><a href="https://medium.com/gitguardian/how-to-use-ggshield-to-avoid-hardcoded-secrets-cheat-sheet-included-582f859ab11d">How To Use ggshield To Avoid Hardcoded Secrets... | Medium</a></li>

</ul>
</details>

**标签**: `#AI Productivity`, `#Cybersecurity`, `#DevOps`, `#Data Privacy`, `#Coding`

---

<a id="item-2"></a>
## [DwarfStar (ds4)：Redis 创建者推出的高性能本地大模型运行工具](https://dwarfstar.sh/) ⭐️ 7.0/10

DwarfStar (ds4) 是一款极简的高性能 C 语言推理引擎，旨在让用户在消费级硬件上本地运行 DeepSeek V4、Qwen 和 GLM 等大模型。它支持 Metal、CUDA 和 ROCm 后端，能够提供快速的推理速度和长上下文窗口支持。 该工具使开发者能够在不依赖昂贵或存在隐私风险的云端 API 的情况下，构建 AI 集成工作流和本地智能体。通过针对高端消费级硬件进行优化，它缩小了大型服务器模型与本地生产力工具之间的差距。 ds4 是一个原生推理引擎，支持文本和视觉模型，并提供命令行界面和本地服务器接口。它专门针对 DeepSeek V4.1 Flash 和 Qwen3.8 Flash Next 等模型进行了优化，旨在为拥有大内存机器的用户提供高效的运行体验。

hackernews · fibo · 10月2日 18:01 · [社区讨论](https://news.ycombinator.com/item?id=49936575)

**背景**: 本地大模型推理是指直接在用户机器上运行 AI 模型，而不是通过远程云服务。这种方法需要大量的计算资源，通常利用 GPU 加速（通过 CUDA、Metal 或 ROCm）来处理模型执行过程中涉及的复杂矩阵运算。DwarfStar 由 Redis 数据库的创始人 Salvatore Sanfilippo 开发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dwarfstar.sh/">DwarfStar 4 (ds4): Local DeepSeek V4.1, Qwen and GLM</a></li>
<li><a href="https://github.com/antirez/ds4">GitHub - antirez/ds4: DeepSeek 4 Flash and PRO local ...</a></li>

</ul>
</details>

**社区讨论**: 社区反响热烈，用户反馈其在 M5 Max 等高端硬件上表现出色。开发者们正积极通过 Go 语言绑定和自定义推理引擎来扩展该项目，尽管也有用户指出模型偶尔出现的行为问题可能源于智能体框架而非引擎本身。

**标签**: `#AI Productivity`, `#Local LLM`, `#Developer Tools`, `#Automation`

---

<a id="item-3"></a>
## [使用 GLM-5.3 Flash 进行原型开发的第一个月](https://wagtail.org/blog/one-month-on-glm-53-flash/) ⭐️ 7.0/10

一位开发者记录了使用 GLM-5.3 Flash 模型进行快速原型开发的月度体验，强调了其高效率和低运营成本。该案例研究展示了该模型如何促进代理工作流，同时也警示了不受控的 Token 消耗所带来的财务风险。 该案例研究为在人工智能驱动的项目中平衡速度与预算的开发者提供了关键见解。它强调了在软件开发中部署自主智能体时，模型选择和成本管理的重要性。 GLM-5.3 Flash 采用了稀疏专家混合（MoE）架构，拥有 3200 亿总参数和 180 亿激活参数，能够以极低的成本实现高性能。作者指出，虽然该模型非常适合原型设计，但若使用不当的代理模式，可能会导致大量意外的 Token 支出。

hackernews · ThibWeb · 10月2日 15:29 · [社区讨论](https://news.ycombinator.com/item?id=49934620)

**背景**: GLM-5.3 Flash 是一款原生多模态模型，以其优化的注意力机制和稀疏 MoE 主干架构而闻名，这些特性显著提升了智能与计算的比例。代理工作流是指由 AI 驱动的流程，其中自主智能体在极少人工干预的情况下执行任务，通常需要仔细监控以防止资源过度消耗。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/agentic-workflows">What are agentic workflows? - IBM</a></li>

</ul>
</details>

**社区讨论**: 社区对现代大模型极低的能耗表示惊讶，但也提醒在代理工作流中选择不当的模型仍可能导致巨大的意外成本。用户还讨论了“氛围编程”（vibe coding）现象，认为虽然 AI 在原型设计方面功能强大，但开发者需要具备迭代改进并舍弃早期不完美尝试的心态。

**标签**: `#AI Productivity`, `#Agentic Workflows`, `#LLM Optimization`, `#Prototyping`

---

<a id="item-4"></a>
## [Docker Sandbox Kit 规范：将 AI 代理权限打包为 OCI 镜像](https://news.google.com/rss/articles/CBMia0FVX3lxTE4xSlpVaUNiaW54bVR0a3NoSGpqRVpldE5IQWlNNkZfb1VrbTFOVjlkaXhrM2hXN3Y1VlJ6alhyUnMtQ25oeDFZeVN1OUtPS1RDcVBtcmZydk03NGRVSGtQV25RLThBYzdMd2Q0?oc=5) ⭐️ 7.0/10

Docker 推出了 Sandbox Kit Specification v3，允许开发者将 AI 代理的执行环境（包括网络规则、凭据和卷）打包为标准的 OCI 镜像。这种方法将代理权限视为代码，确保了其在不同环境中的可移植性和可复现性。 该规范解决了运行自主 AI 代理时固有的关键安全和隔离挑战。通过将这些环境标准化为 OCI 镜像，它实现了既安全又与现有容器基础设施兼容的生产级自动化。 该规范包含描述符格式、BuildKit 前端以及用于验证已发布 Kit 和支持该规范的运行时的合规性套件。目前，Docker 正将其作为管理代理权限的供应商中立标准提交给 CNCF。

rss · AI Productivity and Monetization · 10月2日 09:01

**背景**: AI 代理通常需要高度特定且隔离的环境来安全地执行代码或访问敏感数据。传统的容器最初并非为自主代理的极端隔离需求而设计，因此 Docker 开发了 Cloud Sandboxes 和 Sandbox Kit 规范来弥补这一差距。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.docker.com/blog/docker-sandbox-kit-spec/">Docker Sandbox Kit Spec: Authority as Code | Docker</a></li>
<li><a href="https://github.com/docker/sandbox-kit-spec">Docker Sandbox Kit Specification v3 - GitHub</a></li>
<li><a href="https://awesomeagents.ai/news/docker-cloud-sandboxes-microvm-agents/">Docker's Cloud Sandboxes Isolate AI Agents by... | Awesome Agents</a></li>

</ul>
</details>

**社区讨论**: 社区认为这是 AI 安全领域的必要演进，并指出通过 OCI 镜像标准化代理环境简化了复杂自主工作流的部署。开发者对这一能够良好集成到现有 DevOps 流水线中的供应商中立标准表示欢迎。

**标签**: `#AI Agents`, `#Docker`, `#DevOps`, `#AI Productivity`, `#Software Architecture`

---

<a id="item-5"></a>
## [创业者将 AI 智能体视为自主同事，成功实现业务规模化](https://news.google.com/rss/articles/CBMiowFBVV95cUxPS2EwY0QyUkpBSVZTNGlma3BJZ21rYjhCV2hnQ18wQWpUX1F5LUlqa2RaTlNqdlRBb0FvcXJ6RmJ2UmhNdzZXcFcxZUJPZ0RRa2NHazFzcVlCQ1MzTk5wVE5TM1hFbDVRTG1HNkhDUV9IMHNLMTItZm1LVnNTZ2tmM2k1akNwai1mdU5USWd2cm1BVjM5TWRhbmV2aGhPZ0Y1U2pZ?oc=5) ⭐️ 7.0/10

一位创业者通过将 AI 从被动工具转变为能够执行复杂工作流的“自主同事”，成功实现了业务规模化。这种方法使 AI 能够独立处理任务，而不仅仅是响应简单的提示词。 这种转变代表了生产力的重大演进，使个人能够在无需增加人力的情况下扩展业务规模并管理复杂流程。它凸显了智能体工作流在现代商业环境中的巨大潜力。 这种转型涉及从简单的聊天机器人转向能够针对高层目标进行推理、规划和执行任务的自主系统。在此模式下取得成功，需要为 AI 智能体建立清晰的集成方式和明确的操作边界。

rss · AI Productivity and Monetization · 10月2日 14:34

**背景**: 自主 AI 智能体是旨在通过与各种软件工具和环境交互来执行多步骤任务的先进系统。与需要持续人工输入的传统 AI 不同，这些智能体利用推理能力来引导工作流并独立解决问题。这项技术正越来越多地被集成到商业平台中，以实现复杂的端到端业务自动化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nvidia.com/en-us/glossary/ai-agents/">What are Autonomous AI Agents ? | NVIDIA Glossary</a></li>
<li><a href="https://www.make.com/">AI Workflow Automation Software & Tools | Make</a></li>
<li><a href="https://n8n.io/">AI Workflow Automation Platform - n8n</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#Productivity`, `#Automation`, `#Business Scaling`

---

<a id="item-6"></a>
## [Shopify Canvas：代理式 AI 消除定制化网店门槛](https://news.google.com/rss/articles/CBMimwFBVV95cUxNUGpkcE12VzNxMnExYmNxZXBKRk8yYWt3cS00dVRRMmtYbFAwTVRoVzk2aXltQS1UckJQVWJLOVJXVERhd3lHMmlVaGplVU5XYWhFNm9yS0E2UlBxMEVXaHh4SDFFTzVjdjdjS0tpWm9jZXcybC1GeVc4c3RaeXF0VHo4S0V6RzcwNkZwd25YeWl4RWtvODJZemxaSQ?oc=5) ⭐️ 7.0/10

Shopify Canvas 利用代理式 AI 实现了电子商务店面设计与定制的自动化。该工具使创业者无需深厚的技术背景或传统的模板开发，即可构建专业级的在线商店。 通过降低技术准入门槛，Shopify Canvas 显著提升了个人创业者和小企业的生产力。它标志着电子商务生态系统正向更具自主性和节省劳动力的工具转型。 该系统利用代理式 AI 来观察、规划并实时执行商店修改。它直接与 Shopify 的基础设施集成，确保商店数据在 Shopify 元字段中保持一致。

rss · AI Productivity and Monetization · 10月2日 12:14

**背景**: 代理式 AI（或称自主 AI）是指能够观察环境、规划行动并执行任务以实现特定目标的系统，无需人类持续干预。传统上，构建定制化的电子商务网站需要大量的编程知识或购买死板的预制模板。Shopify Canvas 旨在通过智能化的自动设计辅助来取代这些手动流程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tanium.com/blog/what-is-agentic-ai">What is agentic AI ? What to know about this new AI type | Tanium</a></li>
<li><a href="https://buildwithcanvas.com/">Canvas — Freeform editorial layouts for Shopify</a></li>
<li><a href="https://www.creativeainews.com/articles/shopify-canvas-sidekick-store-builder-theme-lock-in-2026/">Shopify Canvas : 20-Minute Stores, No Theme Download</a></li>

</ul>
</details>

**社区讨论**: 用户普遍对该工具节省时间的能力持乐观态度，但也有人担心 AI 生成的设计在灵活性上不如手动编码。社区对于这将如何影响自由职业网页开发者的市场表现出了浓厚兴趣。

**标签**: `#AI Productivity`, `#E-commerce`, `#Automation`, `#Monetization`, `#Shopify`

---

<a id="item-7"></a>
## [OpenAI 推出 Dot，一款用于处理业务任务和在线订单的 AI 智能体](https://news.google.com/rss/articles/CBMingFBVV95cUxNRVphd29MM1o1WEN5V3JQVlNrWjJET0xpVmsxcjhlWHZWdV91b0s5T0dSQlIyZHFqdmxUWUxUbUdnWEZaMDdoQU5xUEdwTFVtS0Ywd05jN3dLS0liaEFkRVJBLWxueFkxWEx1djZUa0RCWlk1T1ljMGxLZjROX2U0blR1MGEyeUpCa2tteGZLbExQM09KTjlLOGZzelZ3UQ?oc=5) ⭐️ 7.0/10

OpenAI 推出了名为“Dot”的全新 AI 智能体，专门用于自动化复杂的业务工作流程并简化在线订购流程。该工具旨在自主完成以往需要人工干预的多步骤任务。 Dot 的推出标志着向智能体 AI 的重大转变，即从简单的文本生成转向主动的劳动力替代和生产力提升。这种能力使企业和个人能够自动化日常运营，从而有望提高效率并降低运营成本。 Dot 作为一种自主推理引擎运行，能够规划工作流程、与外部工具交互并执行操作以实现既定目标。与传统的基于规则的自动化不同，它旨在适应上下文并在任务执行过程中独立做出决策。

rss · AI Productivity and Monetization · 10月2日 18:23

**背景**: AI 智能体是能够感知环境、推理用户请求并采取自主行动以实现特定目标的软件系统。与主要提供信息的标准聊天机器人不同，智能体 AI 能够使用工具并操作软件界面来执行端到端的工作。这项技术代表了 AI 的下一次演进，即从被动助手转变为数字工作流程的积极参与者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.unite.ai/best-ai-agents-for-business-automation/">10 Best AI Agents for Business Automation (2026) - Unite.AI</a></li>
<li><a href="https://www.deloitte.com/us/en/what-we-do/capabilities/applied-artificial-intelligence/articles/agentic-ai-insights.html">AI agents for business: Agentic AI insights and trends - Deloitte</a></li>
<li><a href="https://www.zendesk.com/blog/ai/workflow-automation/what-are-ai-agents/">What are AI agents? How they work, types, and examples (2026)</a></li>

</ul>
</details>

**标签**: `#AI Agents`, `#Automation`, `#Productivity`, `#OpenAI`

---

<a id="item-8"></a>
## [恶意邮件可劫持 AI 代理并访问关联账户](https://news.google.com/rss/articles/CBMirwFBVV95cUxOM0tBYnFTeGV0Qk5YOGktblFEV1dhanp3LWJhLWI4ano4UUpfS081eW1hU2xpMEpSdzU3UlJyOERCc2lITTRSUDlRdXk5RXZiVFJ4LVVIMF9pbTBPMkdvRW9RVi1VN0ZuUzRPbjY3V1BzTExid2pRVFBUcmN2bEZab0dma2dyNVpsT05KMTZwR1ZjRkg2dUR5U202M2tfVUNoUjhTSnp6bnhvclR1SG53?oc=5) ⭐️ 7.0/10

研究人员发现了一种安全漏洞，恶意邮件可以操纵 AI 代理，从而获得对用户关联账户的未经授权访问权限。该漏洞允许攻击者通过直接向代理的工作流注入指令来绕过标准安全措施。 该漏洞凸显了授予 AI 代理对敏感工具和个人数据的自主访问权限所带来的重大风险。随着企业越来越依赖代理工作流，此类缺陷可能导致大规模的数据泄露和未经授权的系统操作。 该攻击利用了“间接提示注入”（indirect prompt injection），即 AI 代理处理来自电子邮件等外部来源的恶意内容，并将其视为合法指令。这证明了在没有足够的人工监督或沙箱隔离的情况下允许代理执行操作的危险性。

rss · AI Productivity and Monetization · 10月2日 11:28

**背景**: AI 代理是旨在代表用户与软件工具和 API 交互以执行任务的自主系统。提示注入（prompt injection）是指攻击者输入恶意文本，诱骗大语言模型（LLM）忽略其原始指令，转而执行攻击者的命令。当这种情况通过电子邮件或网页等外部数据发生时，被称为间接提示注入。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cobusgreyling.medium.com/ai-agent-security-vulnerabilities-239ff511d27d">AI Agent Security Vulnerabilities | by Cobus Greyling | Medium</a></li>
<li><a href="https://opennash.com/blog/prompt-injection-ai-agents-enterprise-security/">Prompt Injection in AI Agents : An Enterprise... | OpenNash Blog</a></li>
<li><a href="https://nhimg.org/how-to-prevent-prompt-injection-in-ai-agents">How to Prevent Prompt Injection in AI Agents</a></li>

</ul>
</details>

**社区讨论**: 安全专家和社区成员强调，迫切需要为 AI 代理引入“人在回路”（human-in-the-loop）的验证机制和更严格的权限控制。许多人认为，现有的安全架构尚无法应对自主代理工作流带来的独特威胁。

**标签**: `#AI Security`, `#Agentic Workflows`, `#Cybersecurity`, `#AI Productivity`

---

<a id="item-9"></a>
## [Moderna 将取代华纳兄弟探索公司进入纳斯达克 100 指数](https://news.google.com/rss/articles/CBMikwFBVV95cUxQX3JURWVCSUtCWkhMdk1naXFhb2pwenNPM0dHbWFkME40cE83XzUxcXh5djZxb3RFV0dOaXhKTHFtUDJiR3hhbTFFaGxlbExadjR3UmFzVnJOQ25XejMyWXZyLV9tNzBHa0tWWnFoT1dhVXF6YUdNRlppQ183UFVsMGFqUEluWmhvbkFRb0sxTzl4NnM?oc=5) ⭐️ 6.0/10

Moderna 将被纳入纳斯达克 100 指数，取代华纳兄弟探索公司，该调整将于 2024 年 12 月 23 日开盘前生效。 这一变动对追踪纳斯达克 100 指数的机构投资者和被动基金具有重要意义，因为他们必须调整持仓以反映新的指数构成。 纳斯达克 100 指数会定期进行再平衡，以确保其持续代表在纳斯达克交易所上市的市值最大的 100 家非金融公司。

rss · QQQ and Nasdaq 100 · 10月2日 05:21

**背景**: 纳斯达克 100 指数是由在纳斯达克证券交易所上市的 100 家最大的非金融公司组成的股票市场指数。指数再平衡每季度进行一次，以保持指数的准确性和相关性，这通常会触发追踪指数的基金进行自动买卖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.thinkmarkets.com/en/trading-academy/market-events/nasdaq-100-rebalancing/">Nasdaq-100 Rebalancing: Schedule and Market Impact</a></li>
<li><a href="https://indexes.nasdaq.com/docs/Methodology_NDX.pdf">NASDAQ-100 INDEX®</a></li>

</ul>
</details>

**标签**: `#Nasdaq-100`, `#QQQ`, `#Index Rebalancing`, `#Equity Markets`

---

<a id="item-10"></a>
## [为何年轻投资者应考虑将纳斯达克 100 指数 ETF 作为长期退休规划](https://news.google.com/rss/articles/CBMirAJBVV95cUxOMlVKUDF3NEMwWkp6VVI0T0prdEhtWDc5SWp4QnF4TXZmakhLcFF2cmlwdnRPRHZVNHlXTURud0wxajE3SW43VlEwTnpKd1RYTEV4T1hZYWVra3JPV3dqUWMxUHNiQ2FTcVVuVHZaU3oxbEx4UC14cWZrRWIyZTRHNEg2cE81OTRHNVhhS0lUSGFpbE5mVHIxbW9EQUtlZk1iRDgybHF4bDFOZWRLU2xHbFhheUpZaFJDMFQzeTRvdFZXYTBFYmVtWEZ3dERPc0xsNHllLXg5WGp6OUVodDVidGlIa3BYdnF0SUtKbmtlb3RwU2VPNmVWZkplWDd6ZWh1MWFDMDFLRTgzdENjcFAwYUR2SDA5ZEF4RDgwU3pSRVNITHEzRGF2ZUYyYlQ?oc=5) ⭐️ 6.0/10

文章建议 20 多岁的年轻投资者应将纳斯达克 100 指数 ETF（如 QQQM）作为其退休策略的核心组成部分，特别是在市场低迷时期。它强调了在数十年时间跨度内持有这些以增长为导向的资产所带来的长期收益。 这一策略利用了顶级非金融公司历史上的增长潜力，使年轻投资者能够随着时间的推移实现财富复利。它通过专注于长期积累而非短期择时，为应对市场波动提供了一种简单直接的方法。 纳斯达克 100 指数专注于以创新为驱动的非金融公司，这些公司通常表现出更高的增长潜力，但也伴随着更高的波动性。文章鼓励投资者在市场崩盘期间保持持仓，以从最终的长期复苏中获益。

rss · QQQ and Nasdaq 100 · 10月2日 13:09

**背景**: 纳斯达克 100 指数是一个包含在纳斯达克证券交易所上市的 100 家最大非金融公司的股票市场指数。ETF（交易型开放式指数基金）是一种追踪特定指数或资产类别表现的投资工具，像普通股票一样在交易所进行交易。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nasdaq.com/products/global-indexes/nasdaq-100">Nasdaq - 100 | Nasdaq</a></li>

</ul>
</details>

**标签**: `#QQQ`, `#Nasdaq-100`, `#Long-term Investing`, `#Retirement Planning`, `#ETF`

---

<a id="item-11"></a>
## [FLEET 算法通过记忆增强的 MCTS 提升大语言模型生成效率](https://www.reddit.com/r/MachineLearning/comments/1wvs12j/adding_memory_to_search_instead_of_sampling_in/) ⭐️ 6.0/10

FLEET 算法通过使用记忆增强的蒙特卡洛树搜索（MCTS）取代盲目采样，利用历史奖励数据指导 Token 选择，从而提升了大语言模型的生成能力。该算法通过熵和方差熵追踪模型的不确定性，以识别搜索过程中的最优分支点。 这种方法显著提高了推理阶段的效率，使模型能够以更少的迭代次数达到性能基准。对于构建需要最大化奖励的智能体工作流的开发者来说，这提供了一个实用的优化框架。 FLEET 将归一化的隐藏状态存储在向量数据库中以映射奖励历史和转换，并使用余弦相似度进行检索。在 GSM8K 和 LiveCodeBench 上的实验表明，与标准采样相比，FLEET 在大幅减少迭代次数的情况下达到了基准性能。

reddit · r/MachineLearning · /u/Helpful_Minimum_2214 · 10月2日 12:04

**背景**: Best-of-N 采样是一种常见技术，通过生成多个输出并根据奖励模型选择最佳结果。MCTS 是一种常用于决策过程的搜索算法，目前正越来越多地应用于大语言模型，通过探索不同的 Token 序列作为潜在路径来提升推理能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hrletsgo.me/en/documents/mcts-game-ai-to-llm-test-time-compute">What Is MCTS — From Game AI to LLM Test-Time Compute</a></li>
<li><a href="https://arxiv.org/pdf/2402.03289">Make Every Move Count: LLM -based High-Quality RTL Code...</a></li>

</ul>
</details>

**社区讨论**: 目前的社区讨论尚处于早期阶段，但作者已经提供了开源代码和预印本，并邀请开发者就 MCTS 的实现和搜索参数调整进行技术交流。

**标签**: `#AI Research`, `#LLM Optimization`, `#Agentic Workflows`, `#Inference Efficiency`

---