# 移动开发

先选平台再选技术：只做 Android 用 Kotlin + Jetpack Compose，只做 iOS 用 Swift + SwiftUI，一套代码同时上两端再考虑 Flutter、React Native 或 Kotlin Multiplatform。三条路线的官方教程都免费。

## 推荐资源

| 资源 | 适合人群 | 学习重点 |
| --- | --- | --- |
| [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/course) | Android 入门（零编程基础也可） | Google 官方免费课程：Kotlin 基础、Compose 界面、导航、数据持久化，按单元做出可运行的 App |
| [Apple SwiftUI 教程](https://developer.apple.com/tutorials/swiftui) | iOS 入门 | Apple 官方分步教程，边做边学 SwiftUI 的界面、数据流和动画 |
| [App Dev Training（Apple 官方）](https://developer.apple.com/tutorials/app-dev-training) | 想系统做完一个 iOS App 的人 | Apple 官方项目式训练：从界面到数据持久化，完整做出一个 App |
| [Stanford CS193p](https://cs193p.stanford.edu/) | 有编程基础、想深入 iOS 的人 | 斯坦福 iOS 开发课，公开讲课视频，用 SwiftUI 讲架构（MVVM）和工程实践 |
| [Flutter 学习路径](https://docs.flutter.dev/learn/pathway) | 想一套代码做 Android + iOS 的人 | Flutter 官方学习路径：Dart 语言、组件、布局、状态管理 |
| [React Native 官方文档](https://reactnative.dev/docs/getting-started) | 会 React / JavaScript 的人 | 用 React 写原生 App，从环境搭建到核心组件 |
| [Kotlin Multiplatform 入门](https://kotlinlang.org/docs/multiplatform/get-started.html) | 已会 Kotlin / Android、想把代码共享到 iOS 的人 | JetBrains 官方文档：在 Android、iOS、桌面和 Web 之间共享业务逻辑，界面可以共享，也可以各端原生实现。Compose Multiplatform 的 iOS 支持已于 [2025-05 进入稳定版](https://blog.jetbrains.com/kotlin/2025/05/compose-multiplatform-1-8-0-released-compose-multiplatform-for-ios-is-stable-and-production-ready/) |

## 建议学习顺序

1. 先决定平台：只做 Android → Android Basics with Compose；只做 iOS → SwiftUI 教程，接着 App Dev Training；要两端 → Flutter（新手）、React Native（已会 React）或 Kotlin Multiplatform（已会 Kotlin / Android）。
2. 跟着官方课程做完至少一个完整 App，再看 CS193p 补架构。
3. 学会真机调试、打包和发布到测试渠道（Android 内测 / TestFlight）。

## 产出目标

- 发布一个自己会用的小 App（记账、习惯打卡、学习卡片等），README 附截图和下载方式。
- App 至少包含：多页面导航、本地数据持久化、一个网络请求。
- 写一篇复盘：选这个技术路线的理由，以及踩过的坑。
