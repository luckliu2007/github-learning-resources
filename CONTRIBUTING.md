# 贡献指南

欢迎推荐资源、修正失效链接和描述错误。参与前请先读 [行为准则](CODE_OF_CONDUCT.md)。

## 参与方式

| 你想做什么 | 怎么做 |
| --- | --- |
| 推荐一个资源 | 填 [推荐资源表单](https://github.com/luckliu2007/github-learning-resources/issues/new?template=resource-suggestion.yml) |
| 报告失效链接 | 填 [失效链接表单](https://github.com/luckliu2007/github-learning-resources/issues/new?template=broken-link.yml) |
| 指出数字或描述有误 | 填 [内容勘误表单](https://github.com/luckliu2007/github-learning-resources/issues/new?template=content-error.yml)，附原文链接 |
| 直接修改 | Fork 后新建分支，改完发 Pull Request，按 PR 模板自查 |

## 收录标准

- 与分类主题直接相关，有明确的学习价值，不只是工具清单。
- 自己打开核实过：内容有实质、有文档，不是空壳或纯营销。
- 优先收录免费、公开、结构清楚的资源；付费内容要写明。
- 不收录盗版书籍、侵权课程或搬运内容；不收录有加密代币推广、刷星或仿冒迹象的项目。
- 不因为星标高就自动收录；同类已有更好的，就不再加。
- 研究和调查数字只引用原文，并标注发布日期。

## 条目格式

在对应分类页添加一行，模仿同一张表里现有条目的写法和长度：

```md
| [资源名](https://github.com/owner/repo) | 适合人群 | 学习重点 |
```

## 提交前检查

- 链接可访问（CI 的 Link Check 会自动检查所有 Markdown 链接）。
- 描述准确、分类合理，没有复制原项目的大段内容。
- 新增分类文件时，已在 README 的“分类目录”登记。

## 维护约定

- 失效链接由 [Link Check 工作流](https://github.com/luckliu2007/github-learning-resources/actions/workflows/link-check.yml) 每周自动体检，无需再手动逐条检查。
- 新增资源时先写“为什么值得学”，再放链接。
- 不要把同类资源堆太多，宁可保留 5 个真正会用的。
- 不复制课程正文、书籍内容或原项目 README，大段内容请回到原链接阅读。
- 课程、标准和年度报告的新版本按 [ROADMAP.md](ROADMAP.md) 的“持续跟踪”表定期核对。
- 一个资源只在它的“主分类”写完整条目，其它分类需要提及时用“另见”引用，避免重复维护。
- 每天的[内容雷达](https://github.com/luckliu2007/content-radar)会检查已收录项目是否归档、删除或改名，并按主题发现候选；候选经人工核实后才会收录。
