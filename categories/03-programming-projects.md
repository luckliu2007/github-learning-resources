# 编程语言和项目实践

## 主流语言的官方入门

先用官方教程学一门语言，比看二手教程更准确，也更新及时。[GitHub Octoverse 2026](https://github.blog/news-insights/octoverse/octoverse-commits-pushes-reach-new-highs-in-2026-as-developers-build-with-agents/) 显示，TypeScript、Python、JavaScript 仍是 GitHub 上贡献者最多的三门语言，Rust 的贡献者一年翻了一倍。

| 语言 | 资源 | 学习重点 |
| --- | --- | --- |
| Python | [Python 官方教程](https://docs.python.org/zh-cn/3/tutorial/) | 官方文档里的入门教程，有中文版：数据结构、函数、模块、类、标准库导览 |
| TypeScript | [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html) | 官方手册：类型系统、泛型、类型收窄；配合在线 Playground 边写边看 |
| Go | [A Tour of Go](https://go.dev/tour/) | 官方交互式教程，浏览器里直接运行，一两天走完语法和并发基础 |
| Rust | [The Rust Book](https://doc.rust-lang.org/book/) + [Rustlings](https://github.com/rust-lang/rustlings) | 官方书讲清所有权、借用、生命周期；Rustlings 是官方配套的小练习，修好编译错误就过关 |
| Java | [dev.java 学习](https://dev.java/learn/) | Oracle 官方的 Java 学习站：从语言基础到现代特性（记录类、模式匹配、虚拟线程） |

> 学语言阶段尽量少用 AI 补全，先把语法和报错读熟，见 [AI 时代怎么学](../ai-era-learning.md)。

## 项目实践

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp) | 新手到中级 | Web、Python、数据分析、认证项目 |
| [project-based-learning](https://github.com/practical-tutorials/project-based-learning) | 想边做边学的人 | 用项目学习语言、框架和工具 |
| [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) | 中级到高级 | 从零实现数据库、Git、Docker、解释器等 |
| [the-art-of-command-line](https://github.com/jlevy/the-art-of-command-line) | 所有开发者 | 命令行速成，一页读完的高密度实用技巧 |
| [30-seconds-of-code](https://github.com/Chalarangelo/30-seconds-of-code) | 想积累代码片段的人 | 短小可复用的编程片段，边查边学 |
| [Exercism](https://exercism.org/) | 想系统练一门语言的人 | 70 多种语言的免费练习路线，每道题有自动测试，可申请志愿导师人工点评 |
| [roadmap.sh 项目库](https://roadmap.sh/projects) | 不知道做什么项目的人 | 按前端、后端、DevOps 等方向和难度分级的项目题目，带需求说明 |

> 算法实现类资源（The Algorithms、javascript-algorithms）另见 [算法、数据结构和面试](04-algorithms-interviews.md)。

## 建议学习顺序

1. 用上面的官方教程或 freeCodeCamp 打一门语言的基础。
2. 用 Exercism 把一门语言练熟，再从 project-based-learning 或 roadmap.sh 项目库选一个小项目。
3. 把项目发布到自己的 GitHub，并写清楚运行方式。
4. 进阶时从 build-your-own-x 选一个底层项目。

## 产出目标

- 至少完成 3 个小项目。
- 每个项目都有 README、截图、运行说明和学习总结。
- 选一个项目重构一次，记录你为什么这么改。
