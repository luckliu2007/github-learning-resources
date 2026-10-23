# AI、机器学习和数据科学

从机器学习基础到大模型应用、智能体（Agent）和 MCP 工具生态的完整学习路线（2026-10 更新：新增一站式 AI 工程课程；2026-09 新增推理模型、MCP、Agent Skills 相关资源。入选项目均已核实仍在活跃维护）。按阶段学，每个阶段选一两个资源学透，不要一次打开太多。

> 本页偏**模型 / 工程师路线**。如果你的目标是**把 AI 用进产品和工作流**，或者是**管理者要制定 AI 战略**，请看独立仓库 [ai-ml-data-roadmap](https://github.com/luckliu2007/ai-ml-data-roadmap)：含能力模型、分周学习计划、评估与战略模板。

## 一站式路线：AI Engineering from Scratch

如果你想要一条从数学基础一路走到智能体上线的完整主线，而不是在下面多个资源之间拼凑，可以直接选它，再用各阶段的资源做专题加深。

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [AI Engineering from Scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | 会写代码、想系统转 AI 工程的人 | 2026 年 3 月开源、增长最快的 AI 工程课程之一（约 7 万星，MIT 许可）：20 个阶段 500+ 节课，覆盖数学与 ML 基础、深度学习、Transformer、从零实现 LLM、RAG、MCP 与 Agent Skills、多智能体和生产部署，每节课都有代码和运行命令 |

## 第一阶段：机器学习和数据科学基础

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [ML For Beginners](https://github.com/microsoft/ML-For-Beginners) | 机器学习新手 | 传统机器学习基础、课程式练习 |
| [AI For Beginners](https://github.com/microsoft/AI-For-Beginners) | AI 新手 | AI 基础概念、神经网络、计算机视觉、NLP |
| [Machine Learning Zoomcamp](https://github.com/DataTalksClub/machine-learning-zoomcamp) | 想边学边做项目的人 | 免费实战课程，从回归分类一直做到模型部署 |
| [OSSU Data Science](https://github.com/ossu/data-science) | 想系统学数据科学的人 | 数学、统计、机器学习、数据工程 |

## 第二阶段：深度学习和大模型原理

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero) | 想真正搞懂神经网络的人 | Karpathy 视频课，从反向传播一路手写到 GPT |
| [LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch) | 想搞懂大模型内部原理的人 | 用 PyTorch 从零实现一个 GPT，配套书籍代码 |
| [fastbook](https://github.com/fastai/fastbook) | 想快速上手深度学习的人 | fast.ai 实战式深度学习教材，先跑通再深究 |
| [nanochat](https://github.com/karpathy/nanochat) | 学完 nn-zero-to-hero 想看完整流程的人 | Karpathy 出品，约 100 美元算力从分词、预训练、微调到聊天界面完整训练一个小型 ChatGPT |
| [reasoning-from-scratch](https://github.com/rasbt/reasoning-from-scratch) | 想搞懂推理模型的人 | LLMs-from-scratch 续作，从零实现推理（reasoning）能力：推理时扩展、强化学习训练 |
| [tiny-llm](https://github.com/skyzh/tiny-llm) | 想搞懂大模型推理服务的系统工程师 | mini-lsm 作者 skyzh 出品，在 Apple Silicon 上用 MLX 从矩阵运算手写 Qwen3 推理，再加 KV Cache、量化、批处理，搭一个迷你 vLLM（需 Mac） |

## 第三阶段：大模型应用开发

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [Generative AI For Beginners](https://github.com/microsoft/generative-ai-for-beginners) | 想学生成式 AI 的人 | 大模型应用、提示工程、RAG、微调 |
| [llm-course](https://github.com/mlabonne/llm-course) | 想走 LLM 工程方向的人 | LLM 科学家和工程师两条路线图，附大量 notebook |
| [RAG_Techniques](https://github.com/NirDiamant/RAG_Techniques) | 做知识库问答的人 | 数十种进阶 RAG 技术的可运行 notebook，从分块策略到重排序和评估 |
| [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) | 所有大模型使用者 | 系统的提示工程方法、技巧和论文索引 |
| [Anthropic Courses](https://github.com/anthropics/courses)（已归档，2026-10） | 用 API 做开发的人 | 官方课程：提示工程、工具调用、模型评估；仓库已停止维护但内容仍可读，新课程见官方 [Anthropic Academy](https://anthropic.skilljar.com/) |

## 第四阶段：智能体（AI Agent）

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [AI Agents For Beginners](https://github.com/microsoft/ai-agents-for-beginners) | 想入门智能体的人 | 微软 18 课入门课程：智能体设计模式、工具调用、RAG、规划、多智能体协作 |
| [Hugging Face Agents Course](https://github.com/huggingface/agents-course) | 想动手做 Agent 的人 | 免费认证课程，用主流框架构建并评估智能体 |
| [agents-towards-production](https://github.com/NirDiamant/agents-towards-production) | 想把 Agent 做成真实产品的人 | 记忆、工具、安全防护、可观测性、部署等生产级环节的代码教程 |
| [learn-harness-engineering](https://github.com/walkinglabs/learn-harness-engineering) | 用 AI 编程智能体干活的工程师 | 项目制课程：为编程智能体搭建指令、工具、环境、状态和验证反馈（harness），附 Claude Code、Codex 等真实 harness 拆解，含简体中文 |
| [Claude Code: Everything You Need to Know](https://github.com/wesammustafa/Claude-Code-Everything-You-Need-to-Know) | 刚开始用 Claude Code 的工程师 | 社区编写的分级实操教程（初级 / 中级 / 高级）：每课在自己的练习仓库里动手并有自动检查，易变的事实标注出处和验证过的版本；需付费 Claude 订阅或 API 账号 |

## 第五阶段：MCP 与 Agent Skills（2025–2026 新标准）

智能体接外部工具和数据的方式正在标准化：MCP（Model Context Protocol）统一“模型怎么调用工具”，Agent Skills 统一“怎么把一套做事方法打包给智能体”。主流 AI 应用和编程助手已普遍支持。

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [MCP For Beginners](https://github.com/microsoft/mcp-for-beginners) | 想给 AI 接工具和数据的人 | 微软出品，多语言示例（Python/TypeScript/Java/.NET 等），从概念到自己写 MCP 服务器 |
| [Agent Skills](https://github.com/anthropics/skills) | 想复用和定制智能体能力的人 | 官方 Skills 示例与规范：一个文件夹装指令、脚本和资源，按需加载 |
| [MCP 2026-07-28 规范](https://modelcontextprotocol.io/specification/2026-07-28/changelog) | 写 MCP 服务器的人 | 协议推出以来最大的修订：无状态核心、发现机制、Tasks 扩展、MCP Apps，旧的 HTTP+SSE 传输已弃用；MCP 现由 Linux 基金会旗下的 [AAIF](https://aaif.io/) 托管 |
| [AGENTS.md](https://agents.md/) | 用编程智能体的人 | 写给编程智能体看的项目说明文件（开放格式），每个仓库放一份 |

**2026 年的智能体工程实践**（Anthropic Engineering 一手文章）：[工具设计](https://www.anthropic.com/engineering/writing-tools-for-agents) · [长任务运行框架](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) · [智能体评估](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents) · [多智能体系统](https://www.anthropic.com/engineering/multi-agent-research-system)。安全方面看 [OWASP 智能体应用十大风险（2026）](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/)。汇总解读见 [2026 AI 最佳实践](https://github.com/luckliu2007/ai-ml-data-roadmap/blob/main/best-practices-2026.md)。

## 中文资源

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [self-llm](https://github.com/datawhalechina/self-llm) | 想上手开源大模型的人 | 开源大模型的环境配置、部署、微调保姆级教程 |
| [happy-llm](https://github.com/datawhalechina/happy-llm) | 想懂原理的中文学习者 | 从零开始的大模型原理与实践教程 |
| [llm-universe](https://github.com/datawhalechina/llm-universe) | 中文应用开发新手 | 面向新手的大模型应用开发入门 |
| [hello-agents](https://github.com/datawhalechina/hello-agents) | 想系统学智能体的中文学习者 | 《从零开始构建智能体》，从原理到多智能体实践 |
| [easy-vibe](https://github.com/datawhalechina/easy-vibe) | 想用 AI 编程做出产品的人 | Vibe Coding 实战教程：从需求分析、原型到上线，分新手 / 初中级 / 进阶开发者三条路线，带交互式演示 |
| [deepagents-in-action](https://github.com/datawhalechina/deepagents-in-action) | 用 LangChain 生态做智能体的人 | 《Deep Agents 实战》：基于 LangChain / LangGraph Deep Agents，16 章图文 + 视频 + 实验模板，讲任务规划、文件系统、子 Agent 与上下文管理 |
| [awesome-agentic-ai-zh](https://github.com/WenyuChiou/awesome-agentic-ai-zh) | 想系统学智能体、偏好中文路线图的人 | 繁中 / 简中 / 英三语的 AI Agent 学习地图：Stage 0–8 从 LLM 基础到多智能体与生产化，分 CLI 智能体使用者和 Agent 开发者两条路线，附名词表、小练习和精选资源（[在线阅读](https://wenyuchiou.github.io/awesome-agentic-ai-zh/)） |

## 建议学习顺序

1. 先补 Python、线性代数、概率统计基础。
2. 第一阶段用 ML For Beginners 或 Machine Learning Zoomcamp 建立机器学习基础。
3. 想搞懂原理走第二阶段：nn-zero-to-hero → LLMs-from-scratch → reasoning-from-scratch，想看完整训练流程再跑一遍 nanochat；想快速做应用可以直接进第三阶段。
4. 第三阶段掌握提示工程和 RAG 之后，再进第四阶段学智能体，最后用第五阶段把自己的工具接进智能体。
5. 中文学习者可以用 Datawhale 系列（self-llm、happy-llm、llm-universe、hello-agents）配合任一阶段。

## 产出目标

- 做一个小型数据分析项目。
- 做一个机器学习 notebook，并解释模型效果。
- 做一个 LLM 应用 demo，比如问答、摘要或 RAG。
- 做一个能调用工具完成多步任务的智能体 demo。
- 写一个 MCP 服务器，把自己的数据（比如笔记或本仓库的资源表）接进 AI 助手。
