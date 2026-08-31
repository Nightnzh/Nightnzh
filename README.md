## Kevin Hsu · 許証皓

**Android engineer building point-of-sale systems where software meets real hardware — and real money.**

📍 Taiwan · 🌏 Open to remote · [繁體中文版](README.zh-TW.md)

---

### What I do

I build and maintain the core Android product line for self-service ordering kiosks and staff POS terminals used by restaurant chains across Taiwan. Five years in, most of what I've learned comes from a constraint that web and mobile apps rarely have: **the software has to be right, because a bug means a customer's cash is stuck inside a machine on a Saturday night.**

- **Payment architecture.** Led the incremental migration of the payment module from legacy Java MVP to Kotlin MVVM, reducing coupling and making multi-stage flows testable.
- **Payments and cash hardware.** Integrated multiple card readers, e-wallets, and voucher providers alongside bill acceptors and coin hoppers — including the multi-stage change-return and refund paths that sit between them.
- **Modernization at scale.** Led an AGP 8 + Kotlin 2.0 upgrade across a multi-module codebase, and built a Jetpack Compose design system with a reusable component library and a responsive dimension scheme.
- **Testing culture.** Introduced MockK and Robolectric to a codebase that had little coverage, focused it on payment, loyalty, and coupon logic, and wired it into GitLab CI.
- **Peripherals and LAN.** USB / serial / TCP integration for receipt and label printers and barcode scanners, plus LAN device discovery and fault-tolerant background sync.

Because one codebase ships to several product lines and a fleet of boards with different Android versions and peripheral firmware, I spend a lot of my review time on the two things that actually break in the field: **backward compatibility with already-shipped units, and shared code quietly leaking across product lines.**

### What I'm building now

I've been turning my own development workflow into tooling — reusable agent skills, review automation, and codebase-specific playbooks — and keeping the general parts open source.

The goal isn't "using AI to write code faster." It's encoding the domain rules that actually catch bugs into something reviewable and repeatable.

### Tech

| | |
|---|---|
| **Languages** | Kotlin · Java · Python · TypeScript · Dart |
| **Android** | Jetpack Compose · MVVM (ViewModel / LiveData / Flow) · Room · CameraX · multi-module Gradle · product flavors · AGP 8 / Kotlin 2.0 |
| **Testing** | JUnit · MockK · Robolectric · TDD · GitLab CI |
| **Hardware** | USB / serial / TCP peripherals · bill acceptors & coin hoppers · thermal receipt and label printers · barcode scanners · LAN device discovery |
| **Backend** | Spring Boot · REST · WebSocket (STOMP) |
| **AI tooling** | Claude Code skills & subagents · MCP servers · agent workflow design |

### Experience

**Android Engineer** · Restaurant POS company, Taiwan · *2022 – Present*
**Android Engineer** · Manufacturing group, Taiwan · *2020 – 2021*

### Open source

**[my_skills](https://github.com/Nightnzh/my_skills)** — A versioned monorepo of agent skills with schema validation, generated docs, and CI. Python, MIT, bilingual.

*Most of my production work lives in private repositories. Happy to walk through architecture and trade-offs in a conversation.*

### Reach me

📧 [nzh.xuu@gmail.com](mailto:nzh.xuu@gmail.com) · 💼 LinkedIn <!-- TODO -->
