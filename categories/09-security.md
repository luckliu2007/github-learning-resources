# 网络安全

写代码的人都需要基本的安全意识；想走安全方向的人，从“理解漏洞 → 合法靶场练手 → 系统路线”三步走。

> ⚠️ 只在下面这些**授权的练习平台**和自己的环境里练习攻击技术，未经授权测试他人系统是违法的。

## 推荐资源

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [OWASP Top 10:2025](https://top10.owasp.org/2025) | 所有 Web 开发者 | 最常见的 10 类 Web 安全风险，写代码前必读。2025 年版新增“软件供应链失败”（第 3 位，覆盖依赖、构建系统和分发渠道被攻破）和“异常情况处理不当”（第 10 位）；“安全配置错误”升到第 2 位（[项目主页](https://owasp.org/projects/top-ten)） |
| [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) | 开发者 | 按主题给出的安全编码速查：认证、会话、输入校验、加密等（[GitHub](https://github.com/OWASP/CheatSheetSeries)） |
| [OpenSSF：Developing Secure Software（LFD121）](https://training.linuxfoundation.org/training/developing-secure-software-lfd121/) | 想系统学安全开发的程序员 | OpenSSF 开发、Linux 基金会提供的免费自学课程（16–20 小时）：安全设计原则、输入校验、供应链安全、静态与动态分析、威胁建模和密码学，有测验、实验和期末考试 |
| [PortSwigger Web Security Academy](https://portswigger.net/web-security) | 想系统学 Web 安全的人 | Burp Suite 团队的免费课程，每类漏洞都有讲解 + 在线实验室，质量公认最好 |
| [OverTheWire Wargames](https://overthewire.org/wargames/) | 安全入门者 | 从 Bandit 开始，通过闯关练 Linux 命令行和基础安全技能 |
| [picoCTF](https://picoctf.org/) | 学生和 CTF 新手 | 卡内基梅隆大学主办的免费 CTF 练习平台，题目由浅入深 |
| [CTF Wiki](https://ctf-wiki.org/) | 中文 CTF 学习者 | 中文 CTF 知识库：Web、密码学、逆向、PWN 等方向的原理与题型（[GitHub](https://github.com/ctf-wiki/ctf-wiki)） |
| [PortSwigger：Web LLM attacks](https://portswigger.net/web-security/llm-attacks) | 做 AI 应用的开发者 | Web Security Academy 的大模型攻击专题：提示注入（含间接注入）、过度授权、不安全的输出处理，配在线实验室；大模型应用的完整风险清单见 [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/) |
| [Hacker101](https://www.hacker101.com/) | 想了解漏洞赏金的人 | HackerOne 的免费 Web 安全课程和 CTF |
| [roadmap.sh 网络安全路线图](https://roadmap.sh/cyber-security) | 想转安全方向的人 | 网络安全岗位需要掌握的知识地图 |

## 建议学习顺序

1. 所有开发者：读一遍 OWASP Top 10:2025，并在自己的项目里对照 Cheat Sheet 检查认证和输入校验；想系统补安全开发，学完 OpenSSF 的 LFD121。
   - 2025 年版把供应链列为第 3 大风险：锁定依赖版本、开启依赖告警，AI 工具链也一样（2026-03 曾有 AI 网关 LiteLLM 的两个 PyPI 版本被投毒）。
2. 想深入 Web 安全：按 PortSwigger Web Security Academy 的顺序学，每类漏洞做完实验室。
3. 补基础：用 OverTheWire Bandit 练命令行，再用 picoCTF 或 CTF Wiki 系统刷题。
4. 想转安全岗位：对照 roadmap.sh 路线图补网络、系统和云安全知识。
5. 做 AI 应用的开发者：做完 PortSwigger 的 Web LLM attacks 实验室，再对照 OWASP 大模型应用十大风险检查自己的应用。

## 产出目标

- 给自己的一个项目做一次 OWASP Top 10:2025 自查，写下发现和修复记录；重点检查依赖是否锁定版本。
- 完成 PortSwigger 至少 3 类漏洞的全部实验室。
- 通关 OverTheWire Bandit。
