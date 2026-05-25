# Tally

> **Say yes. Tally it.** —— 人和 Agent 的任务分派与追踪系统。
> 你的 Slack / 钉钉继续用，但每个"好"都不再被忘记。

🌐 [yestally.com](https://yestally.com) · ⭐ [github.com/yestally/tally](https://github.com/yestally/tally) · Open source · Built in public
📧 [signup@yestally.com](mailto:signup@yestally.com)（加入 waitlist）· [info@yestally.com](mailto:info@yestally.com)（其它咨询）
🌍 [English](./README.md) · 简体中文

**Tally** 取自 *tally stick*：西方古代用作凭证的劈半木棍，合而为一才能验证——是中国"虎符"的对等物。它同时也指"清点/追踪"。一个名字两层含义，精准对应我们做的事：**任务的凭证 + 任务的追踪**。

---

## Status

🚧 **Early prototype.** 还没有可运行的 MVP。当前阶段产出：
- ✅ 完整的产品骨架与设计决策（内部档案）
- ✅ 高保真 HTML mockups（见 [mockups/](./mockups/)）
- ⏳ MVP 工程实施（未开始）

---

## What

你在已有的 IM 里说一句：

> **"@Bob 周三给我 PRD"**

Tally 自动：
- 识别为任务，结构化跟踪
- 分配一个 Agent 给它跟进
- 周二自动提醒：Bob 还没动，要不要追一下
- 完成后自动汇总到你的早晨简报

**Slack / 钉钉 / 飞书继续用。Tally 是无感的任务追踪层。**

随着你逐渐适应，可以让 Agent 接更多的活：调研、整理、撰写、审阅——它们之间也能互相委派、互审、走完一个任务而不需要你逐条跟。

---

## Why

| 现状 | Tally |
|---|---|
| 钉钉 DING/TODO 是事后补丁 | 任务是产品骨架，不是附加功能 |
| Slack Reminder 鸡肋 | Agent 主动跟进、提醒、升级 |
| Linear / Jira 太重，写票太累 | 用自然语言分派，系统自动结构化 |
| 任务在消息流里发出就没了 | 每件事都有人/Agent 在跟着 |
| 你不在公司，进展全靠人脑回顾 | 早晨简报：你睡觉时发生了什么 |

---

## Mockups（在浏览器直接打开）

| 文件 | 内容 |
|---|---|
| [mockups/onboarding.html](./mockups/onboarding.html) | 9 屏产品介绍（中文） |
| [mockups/onboarding-en.html](./mockups/onboarding-en.html) | 9-screen walkthrough (English) |
| [mockups/home-v2.html](./mockups/home-v2.html) | 日常主入口（早间简报 + 虎符墙 + 议题） |
| [mockups/mockup.html](./mockups/mockup.html) | Intent Workspace 详细形态 |

---

## Repo Structure

```
.
├── README.md                ← 英文版
├── README.zh-CN.md           ← 你在这里
└── mockups/                  ← 可在浏览器打开的高保真原型
    ├── home-v2.html
    ├── onboarding.html
    ├── onboarding-en.html
    └── mockup.html
```

---

## Roadmap

- [x] 产品骨架与核心抽象（Intent / Workline / Causality）
- [x] 关键设计决策（A/B/C 三轮 + 私密温情层 + Break-Glass 信任架构）
- [x] 高保真 mockups（4 个核心界面）
- [ ] **MVP**: 单用户 + 单 Agent + Intent 创建 / 追踪 / 留痕
- [ ] Multi-Agent (A2A) 委派
- [ ] 接入 Slack / 钉钉 / 飞书（嵌入式工作台）
- [ ] 私密温情层（Break-Glass 加密）
- [ ] 开放 closed beta

---

## Contributing

项目处于极早期。如果你：
- 是 PM / Tech Lead，对"任务分派与追踪"有真实痛点 → 欢迎在 Issues 描述你的场景
- 关心 Agent 协作、A2A 协议、Provenance/留痕 → 欢迎在 Discussions 讨论架构
- 想加入早期共建 → 在 Issues 自我介绍即可
