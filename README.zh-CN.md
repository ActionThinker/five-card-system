# 五卡体系 · Five-Card System

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen.svg)](https://github.com/actionthinker/five-card-system)

> **把你的经验变成AI能读懂的知识资产。**

---

## 为什么需要五卡体系

2026年的AI可以在一秒内读完人类历史上所有的书、论文、代码库。但它读不了你在某个项目里踩过的坑，读不了你谈判时那个"感觉不对"的瞬间，读不了你做了十年才知道什么时候该打破规则的那个判断。

**你的经验——决策直觉、方法诀窍、失败教训——构成了你最有价值的资产。但它们存在于一个AI完全看不见的地方：你的隐性记忆里。**

五卡体系是一套开源的结构化工具，把任何人的经验变成五张卡片：案例卡、决策卡、方法论卡、风险卡、偏好卡。每张卡同时为两个读者服务——**人 + AI**。

---

## 五卡画布

五卡画布是一张A4纸。就像商业模式画布把商业计划拆成九个格子，五卡画布把你的经验拆成五个格子。

```
┌─────────────────────────────────────────────────┐
│                                                  │
│    [决策卡]                    [方法论卡]         │
│         ↘                      ↙                 │
│              [案例卡]                             │
│         ↙                      ↘                 │
│    [风险卡]                    [偏好卡]           │
│                                                  │
└─────────────────────────────────────────────────┘
```

📥 **[下载画布](./canvas/five-card-canvas.html)** — 打印一张A4，25分钟填完你的第一张画布。

---

## 五张卡片

| 卡片 | 回答的问题 | 一句话 |
|:---|:---|:---|
| 📖 **案例卡** | 发生了什么？ | 所有经验的锚点——从故事开始 |
| 🌟 **决策卡** | 你怎么选的？ | 暴露判断逻辑和排除的选项 |
| ⚡ **方法论卡** | 什么做法可复用？ | 跨案例验证的做法和检查清单 |
| ⚠️ **风险卡** | 什么会出错？ | 你踩过的坑，AI最难获取的经验 |
| 💭 **偏好卡** | 你喜欢/在意什么？ | 你的品味和风格——AI时代最稀缺 |

---

## 快速开始

### 第一步：下载画布
打印或打开 [五卡画布](./canvas/five-card-canvas.html)

### 第二步：填你的第一张画布（25分钟）
从**案例卡**开始——回忆你最近做的一个重要决定或项目，把它真实地写下来。然后向外扩展，填写其他四张卡。

```
案例卡 (5分钟) → 决策卡 (5分钟) → 方法论卡 + 风险卡 (10分钟) → 偏好卡 (5分钟)
```

### 第三步：深入阅读
浏览 [实践手册](./handbook/)，了解每张卡的填写方法和完整示例。

---

## 社区案例

五卡体系的真正价值来自真实世界的经验。查看 [examples/](./examples/) 目录，了解如何提交你自己的案例。

---

## 关于作者

**陈露 (ActionThinker)** — 五卡体系的创立者。致力于将人类隐性经验转化为AI可消费的结构化知识资产。OPC共识宪章起草人，神经网络式组织架构的实践者。

- 🌐 [actionthinker.com](https://actionthinker.com)
- 📚 飞书知识库 (即将上线)

---

## 许可

本项目采用 [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](./LICENSE) 许可协议。

你可以自由地分享、改编本作品，甚至用于商业目的，只需署名并以相同方式共享。

---

## 目录结构

```
five-card-system/
├── README.md                    # 双语主文档
├── README.zh-CN.md              # 中文版（本文件）
├── LICENSE                      # CC BY-SA 4.0 完整法律文本
├── CONTRIBUTING.md              # 贡献指南
├── canvas/
│   └── five-card-canvas.html    # A4打印版画布
├── handbook/
│   ├── 01-什么是五卡体系.md
│   ├── 02-五卡画布使用指南.md
│   ├── 03-案例卡.md
│   ├── 04-方法论卡.md
│   ├── 05-决策卡.md
│   ├── 06-风险卡.md
│   ├── 07-偏好卡.md
│   └── 08-从卡片到Agent.md
└── examples/
    └── README.md
```

---

<p align="center">
  <sub>© 陈露 / ActionThinker · CC BY-SA 4.0 · 五卡体系</sub><br>
  <sub><a href="https://actionthinker.com">actionthinker.com</a> · 飞书知识库 (即将上线)</sub>
</p>
