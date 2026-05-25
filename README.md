# Tally

> **Say yes. Tally it.** — A task delegation and tracking system for human–AI teams.
> Keep using your Slack / Teams. Every "yes" just stops getting lost.

🌐 [yestally.com](https://yestally.com) · ⭐ [github.com/yestally/tally](https://github.com/yestally/tally) · Open source · Built in public
📧 [signup@yestally.com](mailto:signup@yestally.com) (join waitlist) · [info@yestally.com](mailto:info@yestally.com) (general inquiries)
🌍 English · [简体中文](./README.zh-CN.md)

**Tally** is named after the *tally stick* — split wooden tokens used in medieval bookkeeping. Two halves were given to each party; matched together, they sealed a transaction. The name also means *to count, track, or reconcile*. One word, two meanings — exactly what we do: **the token of a promise, and the act of tracking it through.**

---

## Status

🚧 **Early prototype.** No runnable MVP yet. What's done:
- ✅ Complete product architecture and design decisions (internal)
- ✅ High-fidelity HTML mockups (see [mockups/](./mockups/))
- ⏳ MVP engineering (not started)

---

## What

You type into your existing IM:

> **"@Bob, can you ship the PRD by Wednesday?"**

Tally automatically:
- Recognizes it as a task and structures it as a **tally** (a tracked token)
- Assigns an Agent to follow up
- Pings Bob on Tuesday: still no progress?
- Summarizes everything into your morning brief

**Slack / Teams / DingTalk keep working.** Tally is the invisible task layer underneath.

As you get comfortable, let Agents do more than just follow up — research, drafting, review, even delegating to each other. They walk a task all the way through without you herding each step.

---

## Why

| Today | Tally |
|---|---|
| DingTalk "DING" and Slack reminders are afterthoughts | Tasks ARE the product, not an add-on |
| Linear / Jira are too heavy to write a ticket | Natural-language delegation, auto-structured |
| Tasks disappear into the message stream | Every task has someone (or some Agent) on it |
| You leave the office, progress is reconstructed by memory | Morning brief: what happened while you slept |

---

## Core Concepts

| Concept | What it is |
|---|---|
| **Tally** (the token) | A delegated task with a two-halves metaphor — issued and sealed when done |
| **Topic** | A grouping/filter for tallies (project, department, customer) |
| **Living Document** | The artifact a tally produces, owned by the topic, citable by other tallies |
| **Task Chat** | A per-tally chat room, auto-archived when sealed |
| **Tally Assistant** | Your executive assistant — keeps tabs on every tally so you don't have to |
| **Causality View** | The audit trail behind every sealed tally — who authorized what, on what evidence |
| **Lounge** | A private, encrypted side-channel for human-to-human (break-glass access for compliance) |

---

## Mockups (open in browser)

| File | What |
|---|---|
| [mockups/onboarding-en.html](./mockups/onboarding-en.html) | 9-screen product walkthrough (English) |
| [mockups/onboarding.html](./mockups/onboarding.html) | 9-screen product walkthrough (中文) |
| [mockups/home-v2.html](./mockups/home-v2.html) | Daily home screen — morning brief, decisions, tallies |
| [mockups/mockup.html](./mockups/mockup.html) | Intent Workspace detail view |

---

## Repo Structure

```
.
├── README.md                ← You are here (English)
├── README.zh-CN.md          ← 中文版
└── mockups/                  ← Browseable high-fidelity prototypes
    ├── home-v2.html
    ├── onboarding-en.html
    ├── onboarding.html
    └── mockup.html
```

---

## Roadmap

- [x] Product architecture and core abstractions (Intent, Workline, Causality, Topic)
- [x] Key design decisions across 11+ rounds of debate
- [x] High-fidelity mockups (5 core views, 2 languages)
- [ ] **MVP**: single user + single Agent + tally creation / tracking / archive
- [ ] Multi-Agent (A2A) delegation
- [ ] DingTalk / Slack integration (as identity + notification, not as host)
- [ ] Lounge layer (Break-Glass encryption)
- [ ] Closed beta open

---

## Contributing

The project is at its earliest stage. If you:

- Are a **PM, Tech Lead, or anyone with real "task delegation pain"** — open an Issue describing your scenario
- Care about **Agent collaboration, A2A protocols, provenance / audit** — start a Discussion on architecture
- Want to **join early development** — introduce yourself in an Issue

We're looking for both validation and contradicting evidence. Don't be polite — be useful.

---

## Contact

- 📧 [signup@yestally.com](mailto:signup@yestally.com) — Join the waitlist
- 📧 [info@yestally.com](mailto:info@yestally.com) — General inquiries, partnerships, press
- 🌐 [yestally.com](https://yestally.com) — Website (coming)
- 🐦 X / Twitter — coming
