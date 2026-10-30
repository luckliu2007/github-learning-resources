# Git 和 GitHub

## 推荐资源

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [GitHub Skills: Introduction to GitHub](https://github.com/skills/introduction-to-github) | 完全新手 | issue、分支、提交、pull request |
| [first-contributions](https://github.com/firstcontributions/first-contributions) | 想第一次参与开源的人 | fork、clone、修改、提交 PR |
| [Pro Git（官方免费书）](https://git-scm.com/book/zh/v2) | 想系统搞懂 Git 的人 | 从基础到内部原理，中文全本免费 |
| [git-cheat-sheet](https://github.com/arslanbilal/git-cheat-sheet) | 记不住命令的人 | 常用 Git 命令速查（中英对照） |
| [GitHub CLI (`gh`)](https://github.com/cli/cli) | 命令行党 | 在终端里管理 issue、PR、release |
| [gitignore](https://github.com/github/gitignore) | 所有开发者 | 为不同语言和框架选择合理的 `.gitignore` |
| [Oh My Git!（游戏化学习）](https://github.com/git-learning-game/oh-my-git) | 觉得 Git 抽象的人 | 用可视化小游戏理解分支和提交图 |
| [Learn Git Branching](https://learngitbranching.js.org/?locale=zh_CN) | 想真正搞懂分支、rebase 的人 | 浏览器里的交互式 Git 关卡，实时画出提交树，有中文界面（[GitHub](https://github.com/pcottle/learnGitBranching)） |
| [GitHub Skills：Getting Started with GitHub Copilot](https://github.com/skills/getting-started-with-github-copilot) | 会用 Git、想学 AI 协作的人 | GitHub 官方互动课程，在自己的仓库里一步步练习 Copilot；后续课程还有 [Copilot 编程智能体处理 issue](https://github.com/skills/expand-your-team-with-copilot)、[Copilot 代码评审](https://github.com/skills/copilot-code-review)、[在 Copilot 中接入 MCP](https://github.com/skills/integrate-mcp-with-copilot) |
| [Google 工程实践：代码审查指南](https://google.github.io/eng-practices/review/) | 开始给别人或 AI 的 PR 提意见的人 | 审查时看什么（设计、功能、复杂度、测试、命名、注释、文档）、评论怎么写、作者怎么回应。这是 Google 内部规范的公开版，2024 年起不再更新，但仍是最常被引用的代码审查指南 |

## 建议学习顺序

1. 先完成 GitHub Skills 的入门练习。
2. 用 Learn Git Branching 练熟分支、合并和 rebase，再用 first-contributions 做一次真实 PR。
3. 给自己的学习仓库加 README、目录和 `.gitignore`。
4. 学会 star、watch、fork、issue、pull request 的区别。
5. 基本功扎实之后，用 GitHub Skills 的 Copilot 系列课程练习和 AI 协作：让智能体在分支上提交 PR，你来评审、提修改意见、决定是否合并。评审时对照 Google 代码审查指南的检查项。怎么用 AI 才不影响学习，见 [AI 时代怎么学](../ai-era-learning.md)。

## 产出目标

- 建一个自己的学习日志仓库。
- 至少提交 10 次有意义的 commit。
- 向一个练习项目提交一次 pull request。
- 评审一次 AI 提交的 pull request：至少提出一条修改意见，并说明理由。
