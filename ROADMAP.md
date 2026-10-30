# 路线图

## 定位

按学习目标分类的 GitHub 优质学习资源导航：计算机基础、项目实践、算法面试、Web 工程、AI/LLM、中文资源、工具库、网络安全、数据与云、移动、游戏与图形学，并附“AI 时代怎么学”的方法页。AI 应用与管理者路线见独立仓库 [ai-ml-data-roadmap](https://github.com/luckliu2007/ai-ml-data-roadmap)。

## 2026-10-21 全面升级（已完成）

- 计算机基础页重写为“入门 → 工具 → 核心课程 → 进阶”四步路线：新增 CS50x、CS 自学指南、The Missing Semester、Teach Yourself CS、OSTEP、CMU 15-445、Crafting Interpreters。
- Git、项目实践、算法、Web、工具库各页补充 Learn Git Branching、Exercism、roadmap.sh 项目库、NeetCode、doocs/leetcode、MDN、The Odin Project、Full Stack Open、DevDocs、tldr-pages。
- 中文资源页修正两条标题与内容不符的条目，新增 HelloGitHub、科技爱好者周刊、中国独立开发者项目列表。
- 新增“网络安全”分类（OWASP、PortSwigger Web Security Academy、OverTheWire、picoCTF、CTF Wiki 等）。

## 2026-10-30 更新（已完成）

- [AI 时代怎么学](ai-era-learning.md) 改用 GitHub Octoverse 2026（2026-10-28）：超过 40% 的 PR 由智能体起草第一版，AI 辅助代码审查使用量一年增长 90% 以上；第 4 条规则补充“练审查”的依据。
- Git 页新增 Google 代码审查指南；编程语言页的语言排名改用 Octoverse 2026。

## 2026-10-27 最新内容升级（已完成）

- 新增 [AI 时代怎么学（2026）](ai-era-learning.md)：Anthropic 随机对照实验（AI 辅助对技能形成的影响）、METR 开发者效率实验、Stack Overflow 2026 调查、GitHub Octoverse 2025、CS50 的 AI 政策，归纳七条学习规则和各分类的 AI 用法。
- 编程语言页新增“主流语言的官方入门”（Python、TypeScript、Go、Rust + Rustlings、Java）。
- 计算机基础新增 Nand2Tetris、MIT 6.1810；算法新增 OI Wiki、system-design-101；Web 新增 javascript.info、web.dev Learn。
- AI 页新增斯坦福 CS336（2026 春）、Hugging Face LLM Course、LLM Zoomcamp，智能体工程实践补充 Anthropic 新文章和 AI 技术雷达。
- 安全页更新为 OWASP Top 10:2025，新增 OpenSSF LFD121 和 PortSwigger Web LLM attacks；数据与 DevOps 新增 MLOps Zoomcamp、Kubernetes The Hard Way；移动新增 Kotlin Multiplatform；图形学新增 WebGPU Fundamentals。
- Git 页新增 GitHub Skills 的 Copilot 系列课程；中文页新增 Python-100-Days。

## 待补强方向

- [x] 数据工程（数据管道、数仓、流处理）的系统课程（`categories/10-data-cloud-devops.md`，2026-10-22）
- [x] 云计算与 DevOps 实践路线（云厂商免费课程、基础设施即代码）（同上，2026-10-22）
- [x] 移动开发（Android / iOS / 跨平台）（`categories/11-mobile.md`，2026-10-22）
- [x] 游戏开发与图形学入门（`categories/12-game-graphics.md`，2026-10-22）

## 持续跟踪

这些课程、标准和年度报告会定期更新。每周一自动审核时检查一次，有新版本就更新对应页面和 [AI 时代怎么学](ai-era-learning.md)，并在这里更新日期。

| 事项 | 当前状态（2026-10-27 核对） | 触发更新的条件 |
| --- | --- | --- |
| GitHub Octoverse | 2026 年版（2026-10-28 发布）已收录（2026-10-30） | 新一年的报告发布（通常在 10 月底） |
| Stack Overflow 开发者调查 | 2026 年版为最新 | 新一年的调查结果发布 |
| OWASP Top 10 | 2025 年版为最新 | 发布新版本 |
| 斯坦福 CS336 | 2026 春季版为最新 | 新学期课程上线 |
| AI 辅助学习的研究 | Anthropic（2026-01）、METR（2025-07 研究，2026-02 更新说明） | Anthropic、METR 或顶级高校发布新的对照实验 |
| CS50 的 AI 政策 | 只允许使用课程自带的 CS50 Duck | 政策调整 |

## 维护机制

- **每日**：[内容雷达](https://github.com/luckliu2007/content-radar)扫描已收录项目的健康度并发现候选，每日审核核实后收录（每天最多 3 条），CI 通过后自动合并。
- **每周一**：审核任务按上方“待补强方向”联网检索一手资料，每次最多补 2 条。
- **每季度**：人工复盘本文件，勾掉已完成的方向，补充新的方向。

> “待补强方向”中的条目完成后改为 `[x]` 并注明日期。
