# 数据工程、云计算与 DevOps

把代码可靠地跑在生产环境里需要三块能力：**数据管道**（数据从哪来、怎么加工、存在哪）、**云平台**（资源怎么申请、怎么付费、怎么管权限），以及 **DevOps**（构建、部署、监控、基础设施即代码）。容器和 Kubernetes 的入门资源见 [Web、后端和工程能力](05-web-backend-engineering.md)。

## 数据工程

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [Data Engineering Zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) | 想系统入门数据工程的人 | DataTalksClub 的免费课程，可以跟着期班学，也可以随时自学：容器化、工作流编排、数据仓库、批处理、流处理，最后做一个端到端项目 |
| [data-engineer-handbook](https://github.com/DataExpert-io/data-engineer-handbook) | 想找数据工程学习资料的人 | 数据工程学习资源总表：入门路线、书籍、课程、社区、博客和练手项目 |

## 云计算（官方免费学习平台）

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [AWS Skill Builder](https://skillbuilder.aws/) | 用 AWS 的人 | AWS 官方学习平台，有大量免费的数字课程和认证备考内容 |
| [Microsoft Learn 培训](https://learn.microsoft.com/en-us/training/) | 用 Azure 的人 | 微软官方免费学习路径，按角色和认证组织，部分模块提供免费的沙盒实验环境 |
| [Google Cloud Skills Boost](https://www.skills.google/) | 用 Google Cloud 的人 | Google Cloud 官方学习平台：课程、动手实验和技能徽章 |

## DevOps 与基础设施即代码

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [roadmap.sh DevOps 路线图](https://roadmap.sh/devops) | 想转 DevOps 的人 | 从操作系统、网络到 CI/CD、监控的完整知识地图 |
| [90DaysOfDevOps](https://github.com/MichaelCade/90DaysOfDevOps) | 想按天推进的自学者 | 每天一个主题、90 天覆盖 DevOps 核心知识，社区维护，有多语言版本 |
| [devops-exercises](https://github.com/bregman-arie/devops-exercises) | 准备 DevOps 面试的人 | Linux、网络、Docker、Kubernetes、云、Terraform 等方向的大量练习题与问答 |
| [Terraform 官方教程](https://developer.hashicorp.com/terraform/tutorials) | 学基础设施即代码的人 | HashiCorp 官方分步教程，按云厂商分别给出示例 |

## 建议学习顺序

1. 先选定一家云厂商，用它的官方平台学完入门路径（不要三家同时学）。
2. 用 roadmap.sh 定位自己缺哪块，再按 90DaysOfDevOps 的节奏系统补齐。
3. 想走数据方向，完整跟一遍 Data Engineering Zoomcamp，并做完结课项目。
4. 用 Terraform 把自己的一个项目部署到云上，做到“删掉重来也能一键恢复”。
5. 面试前用 devops-exercises 查漏补缺。

## 产出目标

- 用 Terraform 部署一个带数据库的小服务，代码放到 GitHub。
- 给自己的项目配好 CI/CD：推送代码后自动测试、自动部署。
- 完成一个端到端数据管道：抓取数据 → 清洗 → 入仓 → 出报表，并能定时运行。
- 养成看账单的习惯：记录项目每月的云费用，用完的资源及时删除。
