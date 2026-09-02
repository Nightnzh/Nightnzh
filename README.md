<!-- ═══════════════════════════════════════════════════════ -->
<!--                        HEADER                           -->
<!-- ═══════════════════════════════════════════════════════ -->
<div align="center">

# Kevin Hsu · 許証皓

**Android engineer building point-of-sale systems — where software meets real hardware and real money.**

<p>
  <img src="https://img.shields.io/badge/Taiwan-🇹🇼-4A5568?style=for-the-badge" alt="Taiwan" />
  <img src="https://img.shields.io/badge/Open%20to-Remote-2EA043?style=for-the-badge" alt="Open to Remote" />
  <a href="mailto:nzh.xuu@gmail.com"><img src="https://img.shields.io/badge/Email-nzh.xuu%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://nightnzh.github.io"><img src="https://img.shields.io/badge/Website-nightnzh.github.io-2F3FD4?style=for-the-badge" alt="Website" /></a>
  <a href="README.zh-TW.md"><img src="https://img.shields.io/badge/繁體中文-README-0969DA?style=for-the-badge" alt="繁體中文" /></a>
</p>

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                       ABOUT ME                          -->
<!-- ═══════════════════════════════════════════════════════ -->

## 👨‍💻 About Me

I build and maintain the core Android product line for **self-service ordering kiosks and staff POS terminals** used by restaurant chains across Taiwan. Five years in, most of what I've learned comes from a constraint that ordinary apps don't have: **the software has to be right, because a bug means a customer's cash is stuck inside a machine on a Saturday night.**

- 💳 **Payment architecture** — Led the incremental migration of the payment module from legacy Java MVP to Kotlin MVVM, cutting coupling and making multi-stage flows testable
- 🏧 **Payments & cash hardware** — Integrated card readers, e-wallets and voucher providers alongside bill acceptors and coin hoppers, including the multi-stage change-return and refund paths between them
- 🚀 **Modernization at scale** — Led an AGP 8 + Kotlin 2.0 upgrade across a multi-module codebase, and built a Jetpack Compose design system with a reusable component library
- 🧪 **Testing culture** — Introduced MockK and Robolectric to a codebase with little coverage, focused on payment / loyalty / coupon logic, wired into GitLab CI
- 🔌 **Peripherals & LAN** — USB / serial / TCP integration for receipt and label printers and barcode scanners, plus LAN device discovery and fault-tolerant background sync
- 🤖 **Currently building** — Turning my own development workflow into tooling: reusable agent skills, review automation, and codebase-specific playbooks

> One codebase ships to several product lines across a fleet of boards with different Android versions and peripheral firmware. So I spend most of my review time on the two things that actually break in the field: **backward compatibility with already-shipped units, and shared code quietly leaking across product lines.**

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                  AREAS OF EXPERTISE                     -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🎯 Areas of Expertise

<div align="center">

| 🧠 Domain | 🔧 Technologies |
|---|---|
| **Android** | Kotlin, Java, Jetpack Compose, MVVM (ViewModel / LiveData / Flow), Room, CameraX |
| **Build & Scale** | Multi-module Gradle, product flavors, AGP 8, Kotlin 2.0, responsive dimension systems |
| **Hardware I/O** | USB / Serial / TCP, JNI & NDK, bill acceptors, coin hoppers, thermal & label printers, barcode scanners |
| **Networking** | LAN device discovery (NSD / mDNS), offline-tolerant background sync, WebSocket (STOMP) |
| **Backend** | Spring Boot, Java, REST API design |
| **Testing & CI** | JUnit, MockK, Robolectric, TDD, GitLab CI, detekt / checkstyle / lint / PMD |
| **AI Tooling** | Claude Code skills & subagents, MCP servers, agent workflow design |

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                     TECH STACK                          -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🛠️ Tech Stack & Tools

<div align="center">

### Languages
[![Languages](https://skillicons.dev/icons?i=kotlin,java,py,ts,dart,cs,bash)](https://skillicons.dev)

### Mobile & UI
[![Mobile](https://skillicons.dev/icons?i=androidstudio,gradle,flutter,figma)](https://skillicons.dev)

### Backend & Data
[![Backend](https://skillicons.dev/icons?i=spring,firebase,sqlite,mysql)](https://skillicons.dev)

### Tooling & Platform
[![Tooling](https://skillicons.dev/icons?i=git,gitlab,github,githubactions,docker,linux,idea,vscode)](https://skillicons.dev)

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                      EXPERIENCE                         -->
<!-- ═══════════════════════════════════════════════════════ -->

## 💼 Experience

| Role | Context | Period |
|---|---|---|
| **Android Engineer** | Restaurant POS systems — kiosks, staff terminals, pickup lockers | 2022 – Present |
| **Android Engineer** | Manufacturing group — internal apps and SDK modules | 2020 – 2021 |

*Most of my production work lives in private repositories. Happy to walk through architecture and trade-offs in a conversation.*

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    CONNECT WITH ME                      -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🤝 Connect with Me

<div align="center">

<a href="mailto:nzh.xuu@gmail.com">
  <img src="https://img.shields.io/badge/Email-nzh.xuu%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://github.com/Nightnzh">
  <img src="https://img.shields.io/badge/GitHub-Nightnzh-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="https://www.linkedin.com/in/%E8%A8%BC%E7%9A%93-%E8%A8%B1-b586ab238/">
  <img src="https://img.shields.io/badge/LinkedIn-Kevin%20Hsu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://nightnzh.github.io">
  <img src="https://img.shields.io/badge/Website-nightnzh.github.io-2F3FD4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" />
</a>

<br/><br/>

*💬 "The bug you can't reproduce is still costing someone real money."*

</div>
