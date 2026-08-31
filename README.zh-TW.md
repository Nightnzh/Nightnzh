## 許証皓 Kevin Hsu

**Android 工程師。做的是軟體要直接面對真實硬體與真實金流的 POS 系統。**

📍 台灣 · 🌏 可遠端 · [English](README.md)

---

### 我在做的事

我負責開發與維護自助點餐機與店員 POS 收銀機的核心 Android 產品線，服務全台連鎖餐飲品牌。五年下來，我學到最多的，來自一個一般 App 沒有的限制：**軟體必須是對的，因為一個 bug 代表週六晚上有顧客的現金卡在機器裡。**

- **付款架構。** 主導付款模組從舊有 Java MVP 漸進遷移至 Kotlin MVVM，降低耦合，讓多階段流程真的可被測試。
- **支付與現金硬體。** 整合多家刷卡機、行動支付與抵用券方案，並串接紙鈔機、硬幣機等現金硬體——包含夾在中間的多階段找零與退券路徑。
- **大規模現代化。** 主導多模組 codebase 的 AGP 8 + Kotlin 2.0 升級，並建置 Jetpack Compose 設計系統，產出可重用元件庫與適應性尺寸規範。
- **測試文化。** 在原本幾乎沒有覆蓋率的專案導入 MockK 與 Robolectric，聚焦付款、會員點數與優惠券邏輯，並接上 GitLab CI 自動驗證。
- **周邊與區網。** USB／Serial／TCP 整合發票與標籤印表機、條碼掃描器，並維護區網設備探索與離線容錯的背景同步機制。

因為同一份 codebase 要出貨到多條產品線、以及一整批 Android 版本與周邊韌體都不同的機型，我 review 時花最多時間在兩件真的會在現場出事的事上：**對已出貨機台的向下相容，以及共用程式碼悄悄跨產品線洩漏。**

### 我現在在做的

我把自己的開發流程逐步工具化——可重用的 agent skills、review 自動化、專案專屬的判斷準則——並把其中通用的部分開源。

重點不是「用 AI 寫得比較快」，而是把真正能抓到 bug 的領域規則，編碼成可被審查、可被重複執行的東西。

### 技術

| | |
|---|---|
| **語言** | Kotlin · Java · Python · TypeScript · Dart |
| **Android** | Jetpack Compose · MVVM（ViewModel / LiveData / Flow）· Room · CameraX · 多模組 Gradle · product flavors · AGP 8／Kotlin 2.0 |
| **測試** | JUnit · MockK · Robolectric · TDD · GitLab CI |
| **硬體整合** | USB／Serial／TCP 周邊 · 紙鈔機與硬幣機 · 熱感發票與標籤印表機 · 條碼掃描器 · 區網設備探索 |
| **後端** | Spring Boot · REST · WebSocket（STOMP） |
| **AI 工具** | Claude Code skills 與 subagent · MCP server · agent 工作流設計 |

### 經歷

**Android 軟體工程師** · 餐飲 POS 系統商，台灣 · *2022 – 現在*
**Android 軟體工程師** · 製造業集團，台灣 · *2020 – 2021*

### 開源

**[my_skills](https://github.com/Nightnzh/my_skills)** — 版本化的 agent skills monorepo，含 schema 驗證、自動產生文件與 CI。Python、MIT、中英雙語。

*我大部分的產線工作都在私有 repo。架構與取捨很樂意當面聊。*

### 聯絡我

📧 [nzh.xuu@gmail.com](mailto:nzh.xuu@gmail.com) · 💼 LinkedIn <!-- TODO -->
