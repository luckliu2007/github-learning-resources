# 游戏开发与图形学

两条路线：**做游戏**（用现成引擎快速做出可玩的作品）和**学图形学**（理解屏幕上每个像素是怎么算出来的）。前者先出成果，后者打底子，可以并行。

## 做游戏

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [CS50's Introduction to Game Development](https://cs50.harvard.edu/games/) | 有编程基础的游戏新手 | 哈佛 CS50 系列的游戏开发课：通过重做经典游戏学游戏循环、碰撞、状态管理，免费 |
| [Godot：你的第一个 2D 游戏](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html) | 想用开源引擎的人 | Godot 官方入门教程，从零做出一个完整的 2D 小游戏 |
| [Unity Learn](https://learn.unity.com/) | 想用 Unity 的人 | Unity 官方学习平台，按入门到进阶的学习路径组织 |
| [Game Programming Patterns](https://gameprogrammingpatterns.com/) | 想写好游戏代码的人 | 免费在线书：游戏循环、组件、对象池等游戏开发中最常用的设计模式 |

## 图形学

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [GAMES101 现代计算机图形学入门](https://sites.cs.ucsb.edu/~lingqi/teaching/games101.html) | 中文学习者 | 闫令琪老师的中文图形学入门课：变换、光栅化、着色、几何、光线追踪，配作业，广受好评的中文入门课 |
| [LearnOpenGL](https://learnopengl.com/) | 想动手写渲染器的人 | 从窗口、着色器到光照、阴影、PBR 的 OpenGL 教程，有[中文版](https://learnopengl-cn.github.io/) |
| [Ray Tracing in One Weekend](https://raytracing.github.io/) | 想理解光线追踪的人 | 免费系列小书，用几百行代码从零写出一个光线追踪渲染器 |

## 建议学习顺序

1. 想先做出东西：Godot 或 Unity 官方入门教程做一个小游戏 → CS50 Games 系统补基础 → 读 Game Programming Patterns 改进代码结构。
2. 想学图形学：GAMES101 打理论基础 → 跟 LearnOpenGL 写一个能加载模型、有光照的渲染器 → 用 Ray Tracing in One Weekend 写一个光线追踪器。
3. 数学不够时补线性代数（向量、矩阵、变换），GAMES101 前两讲有复习。

## 产出目标

- 做完一个可玩的小游戏并发布（itch.io 或网页版），README 附玩法说明和截图。
- 完成 GAMES101 的作业，或用 LearnOpenGL 写出一个带光照的场景。
- 用 Ray Tracing in One Weekend 渲染一张自己的图片，放进作品集。
