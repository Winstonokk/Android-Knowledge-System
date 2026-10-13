# 🚀 Android Systematic Learning Path (Android 系统化学习路线)

> 🎯 **目标**：从“会用 API”到“理解底层原理与系统机制”，通过 8 周的时间重建完整的 Android 知识体系，兼顾**理论学习、实战 Demo 与高频面试题**。

---

## 📅 8 周学习路线图概览

| 周期 | 主题 | 核心知识点 | 练习 Demo | 面试题 | 状态 |
| :---: | :--- | :--- | :---: | :---: | :---: |
| **Week 01** | **Java, Kotlin, JVM & 并发** | 集合原理 / 反射与注解 / 协程基础 / JVM 内存与 GC | [📁 Demo](./weeks/week-01-java-kotlin-jvm/demo) | [💡 面试题](./weeks/week-01-java-kotlin-jvm/interview.md) | 🟢 简单 |
| **Week 02** | **组件、生命周期与进程机制** | 四大组件 / Activity 任务栈 / Context / 进程杀死与恢复 | [📁 Demo](./weeks/week-02-components-and-process/demo) | [💡 面试题](./weeks/week-02-components-and-process/interview.md) | 🟡 中等 |
| **Week 03** | **View 绘制、事件分发与 Handler** | Measure/Layout/Draw / 滑动冲突 / Handler 源码 / 刷新机制 | [📁 Demo](./weeks/week-03-view-and-handler/demo) | [💡 面试题](./weeks/week-03-view-and-handler/interview.md) | 🔴 核心 |
| **Week 04** | **协程、Flow & Jetpack 架构** | 结构化并发 / StateFlow / ViewModel / Room / WorkManager | [📁 Demo](./weeks/week-04-coroutine-and-jetpack/demo) | [💡 面试题](./weeks/week-04-coroutine-and-jetpack/interview.md) | 🟡 中等 |
| **Week 05** | **Android Framework & Binder 源码** | Zygote / Binder 通信 / Activity 启动流程 / WMS 与绘制 | [📁 Demo](./weeks/week-05-framework-and-binder/demo) | [💡 面试题](./weeks/week-05-framework-and-binder/interview.md) | 🔴 难点 |
| **Week 06** | **ANR、Crash、内存与性能分析** | ANR 日志分析 / Heap Dump 内存泄漏 / Perfetto / 启动优化 | [📁 Demo](./weeks/week-06-performance-and-anr/demo) | [💡 面试题](./weeks/week-06-performance-and-anr/interview.md) | 🔴 核心 |
| **Week 07** | **Gradle、构建系统、存储与兼容** | AGP 与变体 / R8 混淆 / Scoped Storage / 版本适配 | [📁 Demo](./weeks/week-07-gradle-and-storage/demo) | [💡 面试题](./weeks/week-07-gradle-and-storage/interview.md) | 🟡 中等 |
| **Week 08** | **安全、测试与综合实战** | 组件安全 / 单元测试 / 架构演练 / 综合模拟面试 | [📁 Demo](./weeks/week-08-security-test-and-project/demo) | [💡 面试题](./weeks/week-08-security-test-and-project/interview.md) | 🟢 实战 |

---

## 📂 工程目录结构

工程严格按“周”划分，包含**笔记总结（`README.md`）**、**高频面试题（`interview.md`）**以及**可运行的示例代码（`demo/`）**：

```text
.
├── README.md                              # 仓库主页与学习总览
└── weeks/
    ├── week-01-java-kotlin-jvm/           # 第 1 周：语言基础与 JVM
    │   ├── README.md                      # 知识点详细总结与官方文档指南
    │   ├── interview.md                   # 本周高频面试题与解答
    │   └── demo/                          # 练习代码（LRU缓存、注解解析器等）
    ├── week-02-components-and-process/    # 第 2 周：组件与进程机制
    ├── week-03-view-and-handler/          # 第 3 周：View绘制与Handler原理
    ├── week-04-coroutine-and-jetpack/     # 第 4 周：协程与Jetpack架构
    ├── week-05-framework-and-binder/      # 第 5 周：Framework与Binder源码
    ├── week-06-performance-and-anr/       # 第 6 周：性能优化与ANR排查
    ├── week-07-gradle-and-storage/        # 第 7 周：构建系统与存储兼容
    └── week-08-security-test-and-project/ # 第 8 周：综合实战与模拟面试
