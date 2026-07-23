# Web、后端和工程能力

## 推荐资源

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [developer-roadmap](https://github.com/nilbuild/developer-roadmap) | 不知道学什么顺序的人 | 前端、后端、DevOps、AI 等路线图 |
| [Web Dev For Beginners](https://github.com/microsoft/Web-Dev-For-Beginners) | Web 新手 | HTML、CSS、JavaScript 基础项目 |
| [awesome-react](https://github.com/enaqx/awesome-react) | React 学习者 | React 生态资源和工具 |
| [public-apis](https://github.com/public-apis/public-apis) | 做练手项目的人 | 免费公开 API，用于项目实践 |
| [system-design-primer](https://github.com/donnemartin/system-design-primer) | 后端和架构方向 | 系统设计核心主题 |
| [awesome-scalability](https://github.com/binhnguyennus/awesome-scalability) | 想深入高可用/高并发的人 | 真实系统的可扩展性、可靠性案例与论文 |
| [The Twelve-Factor App](https://12factor.net/) | 写后端服务的人 | 云原生应用的 12 条工程准则 |
| [postgres 官方教程 / PostgreSQL Exercises](https://pgexercises.com/) | 补数据库的人 | 用真实数据练 SQL 查询和索引 |
| [awesome-docker](https://github.com/veggiemonk/awesome-docker) | 做部署/DevOps 的人 | 容器化、编排、CI/CD 工具索引 |
| [kubernetes/kubernetes（配 kubernetes.io 教程）](https://kubernetes.io/zh-cn/docs/tutorials/) | 想学编排的人 | K8s 官方交互式教程 |

## 建议学习顺序

1. 用 developer-roadmap 确定方向（前端 / 后端 / DevOps）。
2. Web 新手从 Microsoft 的 Web Dev For Beginners 开始。
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
