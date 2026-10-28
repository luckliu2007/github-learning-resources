# AI 时代怎么学（2026）

**核实日期：2026-10-27。** AI 编程助手已经是开发者的日常工具。这一页回答一个问题：**用这份导航学习时，AI 该怎么用，才能学得更快，而不是学得更浅？** 结论来自研究和权威调查，每条都附来源。

## 一、我们现在知道什么

| 证据 | 发现 | 对学习者意味着什么 |
| --- | --- | --- |
| Anthropic 随机对照实验（[2026-01](https://www.anthropic.com/research/AI-assistance-coding-skills)） | 52 名（多为初级）Python 工程师学习一个新的异步库 Trio。用 AI 的一组完成得只快了约 2 分钟（差异不显著），但随后的测验平均分是 50%，手写组是 67%；**差距最大的是调试题** | 让 AI 直接写代码，任务能完成，但你学到的少，尤其是“为什么出错”的能力 |
| 同一实验的使用方式分析 | 得分高（平均 65% 以上）的人：先让 AI 生成代码再追问原理、要代码时同时要解释、只问概念问题并自己解决报错。得分低（平均不到 40%）的人：全部交给 AI 写、开始自己写后来全部交给 AI、靠 AI 反复调试 | 同样用 AI，**问“为什么”的人学会了，只要答案的人没学会**（研究者提醒这是相关关系，不是因果） |
| METR 随机对照实验（[2025-07](https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/)） | 16 名资深开源开发者、246 个真实任务：用 AI 时反而多花了 19% 的时间，但他们事后仍以为 AI 让自己快了 20%。METR 已在 [2026-02](https://metr.org/blog/2026-02-24-uplift-update/) 注明这一结果过时：新工具下很可能已经提速，但很多开发者不愿意参加“禁用 AI”的对照组，新数据因此不可靠 | **别相信“感觉变快了”**，用测试通过、项目完成这些可检验的结果衡量自己 |
| [Stack Overflow 开发者调查 2026](https://survey.stackoverflow.co/2026/ai) | 83% 的受访者在工作中使用 AI 工具；48% 只在“能轻松验证输出时”才信任它，只有 6.6% 信任它做重要决策；17.1% 因为担心丧失技能而在工作或学习中避免使用 AI | 专业开发者的共识是：AI 很有用，但输出要验证。验证能力本身就要靠扎实的基础 |
| [GitHub Octoverse 2025](https://github.blog/news-insights/octoverse/octoverse-a-new-developer-joins-github-every-second-as-ai-leads-typescript-to-1/) | GitHub 上已有 1.8 亿多开发者，一年新增 3600 多万；80% 的新开发者在第一周就用上了 Copilot；2025-08 起 TypeScript 按月度贡献者数超过 Python，成为 GitHub 上使用最多的语言 | 新手从第一天起就会接触 AI，所以更需要一套“怎么用”的规矩 |
| [CS50 学术诚信政策](https://cs50.harvard.edu/x/honesty/) | 哈佛 CS50 允许使用课程自己的 AI 助教 CS50 Duck，不允许使用会直接给出答案或补全代码的其他 AI 工具 | 顶级入门课的选择：AI 可以当导师，不能当代写 |

## 二、七条学习规则

1. **学新东西时先自己写，卡住了问“为什么”，不要只要答案。** 让 AI 解释概念、指出思路，而不是交出完整代码。依据：Anthropic 实验中得分高的三种用法。
2. **打开工具的“学习模式”。** 跟 CS50 课时用 [CS50 Duck](https://cs50.ai/)；用 Claude Code 写练习项目时切到 [Learning 输出风格](https://code.claude.com/docs/en/output-styles)，它会在关键决策处留下 `TODO(human)` 让你自己写；ChatGPT 的学习模式（[Study Mode](https://techcrunch.com/2025/07/29/openai-launches-study-mode-in-chatgpt)）和 Gemini 的引导式学习（[Guided Learning](https://techcrunch.com/2025/08/06/google-takes-on-chatgpts-study-mode-with-new-guided-learning-tool-in-gemini/)）也会用提问代替直接给答案。依据：Anthropic 研究者建议学习时考虑使用 AI 工具提供的学习模式。
3. **调试自己来。** 先读报错、加日志、缩小范围，实在找不到再让 AI 帮忙，并让它解释原因。调试是 Anthropic 实验里差距最大的能力，也是以后审查 AI 代码最需要的能力。
4. **AI 写的代码，你要能讲清楚每一行。** 提交前用自己的话写下“改了什么、为什么这么改”；讲不清就先别提交。否则代码越来越多，你对它的理解却跟不上（Thoughtworks 技术雷达称之为“认知债”，见 [AI 技术雷达](https://github.com/luckliu2007/ai-ml-data-roadmap/blob/main/tech-radar-2026.md)）。
5. **用测试验证，不靠感觉。** 每个练习项目都写测试，让测试结果告诉你代码对不对。METR 的实验中，开发者对 AI 带来的提速估计明显过高（感觉快了 20%，实测慢了 19%）。
6. **每周留出“无 AI”的练习时间。** 刷题、做 Exercism 练习、写小程序时关掉 AI 补全。很多课程考试和技术面试仍不允许使用 AI；即使允许，面试官也会追问你能不能解释自己的代码。
7. **把 AI 当陪练，而不是代考。** 让它出题考你、扮演面试官、评审你写好的代码、把你的解释挑出漏洞。这些用法都是在练你的能力，而不是替代它。

## 三、各分类怎么配合 AI 学

| 分类 | 别让 AI 替你做 | 可以让 AI 帮你做 |
| --- | --- | --- |
| [Git 和 GitHub](categories/01-git-github.md) | 解决冲突、理解 rebase 的过程 | 解释一条看不懂的命令；用 Copilot 课程体验 AI 怎么在 PR 里协作 |
| [计算机科学基础](categories/02-computer-science.md) | 课程作业和实验（CS50 的规定就是例子） | 用 CS50 Duck 或学习模式讲解概念、出练习题 |
| [编程语言和项目实践](categories/03-programming-projects.md) | 第一次实现一个功能 | 做完后评审代码、建议更地道的写法；项目里重复性的样板代码 |
| [算法和面试](categories/04-algorithms-interviews.md) | 解题本身 | 做完后分析复杂度、给出更优解；模拟面试官追问 |
| [Web 和后端](categories/05-web-backend-engineering.md) | 第一次搭项目骨架、写认证和数据库访问 | 查文档、解释报错、补测试 |
| [AI 和机器学习](categories/06-ai-ml-data.md) | 从零实现类课程（nn-zero-to-hero、LLMs-from-scratch、CS336）的核心代码 | 解释论文和公式；搭实验环境 |
| [网络安全](categories/09-security.md) | 靶场题目的解题过程 | 解释漏洞原理；按 OWASP 清单检查自己的代码 |

## 四、一周节奏示例

| 时间 | 做什么 | AI 怎么用 |
| --- | --- | --- |
| 周一到周三，每天 1 小时 | 跟一门主课（例如 CS50、The Odin Project、OSTEP） | 学习模式，只问概念 |
| 周四 1 小时 | 无 AI 练习：刷 3 道题或做 2 个 Exercism 练习 | 关掉 |
| 周五到周末，3 小时 | 做自己的项目 | 可以用编程智能体，但每次提交前写清改动说明，测试必须通过 |
| 周日 30 分钟 | 复盘：这周哪些东西离开 AI 也能做出来？ | 让 AI 根据你的笔记出 5 道题自测 |

> 想把 AI 用进产品和工作流，或者要在团队里制定 AI 使用规则，见 [ai-ml-data-roadmap](https://github.com/luckliu2007/ai-ml-data-roadmap)。
>
> 学外语时怎么用 AI 陪练、哪些练法有研究支持，见 [英语学习的研究证据](https://github.com/luckliu2007/English-study/blob/main/docs/sla-evidence.md)。
