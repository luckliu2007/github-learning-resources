# 网络安全

写代码的人都需要基本的安全意识；想走安全方向的人，从“理解漏洞 → 合法靶场练手 → 系统路线”三步走。

> ⚠️ 只在下面这些**授权的练习平台**和自己的环境里练习攻击技术，未经授权测试他人系统是违法的。

## 推荐资源

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [OWASP Top 10](https://owasp.org/projects/top-ten) | 所有 Web 开发者 | 最常见的 10 类 Web 安全风险，写代码前必读 |
| [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) | 开发者 | 按主题给出的安全编码速查：认证、会话、输入校验、加密等（[GitHub](https://github.com/OWASP/CheatSheetSeries)） |
| [PortSwigger Web Security Academy](https://portswigger.net/web-security) | 想系统学 Web 安全的人 | Burp Suite 团队的免费课程，每类漏洞都有讲解 + 在线实验室，质量公认最好 |
| [OverTheWire Wargames](https://overthewire.org/wargames/) | 安全入门者 | 从 Bandit 开始，通过闯关练 Linux 命令行和基础安全技能 |
| [picoCTF](https://picoctf.org/) | 学生和 CTF 新手 | 卡内基梅隆大学主办的免费 CTF 练习平台，题目由浅入深 |
| [CTF Wiki](https://ctf-wiki.org/) | 中文 CTF 学习者 | 中文 CTF 知识库：Web、密码学、逆向、PWN 等方向的原理与题型（[GitHub](https://github.com/ctf-wiki/ctf-wiki)） |
| [Hacker101](https://www.hacker101.com/) | 想了解漏洞赏金的人 | HackerOne 的免费 Web 安全课程和 CTF |
| [roadmap.sh 网络安全路线图](https://roadmap.sh/cyber-security) | 想转安全方向的人 | 网络安全岗位需要掌握的知识地图 |

## 建议学习顺序

1. 所有开发者：读一遍 OWASP Top 10，并在自己的项目里对照 Cheat Sheet 检查认证和输入校验。
2. 想深入 Web 安全：按 PortSwigger Web Security Academy 的顺序学，每类漏洞做完实验室。
3. 补基础：用 OverTheWire Bandit 练命令行，再用 picoCTF 或 CTF Wiki 系统刷题。
4. 想转安全岗位：对照 roadmap.sh 路线图补网络、系统和云安全知识。

## 产出目标

- 给自己的一个项目做一次 OWASP Top 10 自查，写下发现和修复记录。
- 完成 PortSwigger 至少 3 类漏洞的全部实验室。
- 通关 OverTheWire Bandit。
