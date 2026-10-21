# Web、后端和工程能力

## 推荐资源

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [developer-roadmap](https://github.com/nilbuild/developer-roadmap) | 不知道学什么顺序的人 | 前端、后端、DevOps、AI 等路线图 |
| [Web Dev For Beginners](https://github.com/microsoft/Web-Dev-For-Beginners) | Web 新手 | HTML、CSS、JavaScript 基础项目 |
| [MDN 学习 Web 开发](https://developer.mozilla.org/zh-CN/docs/Learn_web_development) | 所有 Web 学习者 | Mozilla 官方的 Web 开发教程，HTML/CSS/JS 讲得最准确，有中文版 |
| [The Odin Project](https://www.theodinproject.com/) | 想走完整全栈路线的人 | 免费全栈课程：基础课之后选 JavaScript（Node）或 Ruby on Rails 方向，每节以从零做项目收尾，有 Discord 社区互评 |
| [Full Stack Open（赫尔辛基大学）](https://fullstackopen.com/en/) | 已会前端、想补后端的人 | React、Node/Express、MongoDB、GraphQL、TypeScript 等 13 个部分，免费并提供结课证书 |
| [awesome-react](https://github.com/enaqx/awesome-react) | React 学习者 | React 生态资源和工具 |
| [public-apis](https://github.com/public-apis/public-apis) | 做练手项目的人 | 免费公开 API，用于项目实践 |
| [system-design-primer](https://github.com/donnemartin/system-design-primer) | 后端和架构方向 | 系统设计核心主题 |
| [awesome-scalability](https://github.com/binhnguyennus/awesome-scalability) | 想深入高可用/高并发的人 | 真实系统的可扩展性、可靠性案例与论文 |
| [awesome-architecture](https://github.com/study8677/awesome-architecture) | 想从“会写代码”走向“会做架构”的人 | 中英双语架构图谱：26 篇架构教程、25 个热门系统架构模板、6 个端到端案例，覆盖分布式系统、RAG 和编程智能体等 AI 原生系统（[在线阅读](https://study8677.github.io/awesome-architecture/)） |
| [The Twelve-Factor App](https://12factor.net/) | 写后端服务的人 | 云原生应用的 12 条工程准则 |
| [postgres 官方教程 / PostgreSQL Exercises](https://pgexercises.com/) | 补数据库的人 | 用真实数据练 SQL 查询和索引 |
| [awesome-docker](https://github.com/veggiemonk/awesome-docker) | 做部署/DevOps 的人 | 容器化、编排、CI/CD 工具索引 |
| [kubernetes/kubernetes（配 kubernetes.io 教程）](https://kubernetes.io/zh-cn/docs/tutorials/) | 想学编排的人 | K8s 官方交互式教程 |

## 建议学习顺序

1. 用 developer-roadmap 确定方向（前端 / 后端 / DevOps）。
2. Web 新手从 MDN 或 Web Dev For Beginners 入门；想走完整全栈路线，选 The Odin Project 作主线，已会前端再用 Full Stack Open 补后端。
3. 做项目时从 public-apis 找真实数据源。
4. 后端方向按“系统设计 → 数据库（SQL 实操）→ 缓存/消息队列 → 容器化部署 → 可观测性”推进：
   - 设计思路看 system-design-primer 与 awesome-scalability；
   - SQL 用 PostgreSQL Exercises 动手练；
   - 工程规范对照 The Twelve-Factor App；
   - 部署与编排从 awesome-docker、Kubernetes 官方教程入手。

## 产出目标

- 做一个真实可访问的 Web 项目。
- README 写清技术栈、功能、部署方式。
- 至少接入一个公开 API。
