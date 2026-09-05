<!--
  Randycarteronion/Randycarteronion profile README.
  First-person, embedded-engineer voice. Restores the original English
  intro from the pre-rewrite README, and folds the rest around the
  three-layer stack (底层 / 平台 / 应用).
-->

# Hi, I'm Randycarteronion (a.k.a. randevermist)

- Hello, humans! I love you! I'm randevermist. I chose this name to honor Randolph Carter, a character created by H. P. Lovecraft, one of my favorite science fiction and horror writers.
- I'm interested in works of art and elegant code.
- I'm currently learning Rust, Go and (slowly) Spring AI so I can stop hand-soldering every time I want a smarter box.
- I can't stand clueless client-side managers who pretend to be experts and act full of themselves!!!

这世界有很多的可能性，然而，然而。未来会是什么样子，令人期待。

---

## What I actually work on

`hardware-harness` is the centre of gravity of this profile. It is a **hardware execution runtime for AI coding agents**: a small Python runtime that gives an LLM agent the same primitives an engineer has on a real bench — `build → flash → run → observe → test` — with structured feedback, capability contracts, and adapter plugins. That is the project I am betting on.

Everything else is adjacent:

- **Battery management & STM32 firmware** — bare-metal C on STM32F103 + bq76920. Protection logic (over/under voltage, overcurrent, short-circuit, passive balancing) for a LiFePO4 pack. The thing that taught me what "read the datasheet twice" really means.
- **ESP32 bring-up & sensor glue** — Ai-Thinker ESP32-CAM + DHT 温湿度. The "first PCB after blinking an LED" tier.
- **Smart contracts** — `Ros-Protocol`: a consent-management suite (Solidity + Hardhat) intended as a Digital Public Good (UN SDG 16).
- **A CLI for printing on receipt printers** — `RZ_print`, which talks to 佳博 Gprinter drivers and pairs with QZ Tray.
- **A cross-platform sing-box GUI client** — `GUI_singbox_cn`, with strong log analysis built in.
- **A keyboard remapper** so my laptop can drive Steam Remote Play on a 32-inch display without a tiny-keyboard death.
- **Small annoyances, automated** — t00ls forum auto sign-in, telegram file-id fetchers. I use them daily; they are not pretty.

I do not count stars. The repo count is high because I split every small experiment into its own repo instead of monorepoing.

---

## 技术栈 / Stack

Three layers, the way I actually think about the work:

### 底层 / Hardware & Systems
![C](https://img.shields.io/badge/-C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![STM32](https://img.shields.io/badge/-STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/-FreeRTOS-0091BD?style=flat-square&logo=freertos&logoColor=white)
![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![KiCad](https://img.shields.io/badge/-KiCad-314CB6?style=flat-square&logo=kicad&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

### 平台 / Platform & Tooling
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Solidity](https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Hardhat](https://img.shields.io/badge/-Hardhat-FFF100?style=flat-square&logo=hardhat&logoColor=black)
![Vue](https://img.shields.io/badge/-Vue-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

### 应用层 / Application
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring AI](https://img.shields.io/badge/-Spring%20AI-6DB33F?style=flat-square&logo=spring&logoColor=white)

### 正在学
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)

---

## 项目目录 / What is in each repo

| Repository | What it actually is | Lang |
|---|---|---|
| [`hardware-harness`](https://github.com/Randycarteronion/hardware-harness) | **Main project.** Hardware execution runtime for AI coding agents (build → flash → run → observe → test, structured feedback). | Python |
| [`BMS_F.F.R_R.C`](https://github.com/Randycarteronion/BMS_F.F.R_R.C) | CawBMS — 磷酸铁锂电池管理系统；STM32F103cbt6 + bq76920；过欠压 / 短路 / 过流保护 + 被动均衡。MIT 协议开源复刻。 | C |
| [`Ai-Thinker-ESP32-CAM`](https://github.com/Randycarteronion/Ai-Thinker-ESP32-CAM) | Ai-Thinker ESP32-CAM 摄像头 + 温湿度传感器集成。 | C |
| [`t00ls-`](https://github.com/Randycarteronion/t00ls-) | t00ls 论坛自动签到脚本，两种范式（requests / Selenium）。 | Python |
| [`tg_bot_fileid2`](https://github.com/Randycarteronion/tg_bot_fileid2) | 通过 TG url 拿 file_id 的小自动机，预备与 tdl 合用，未来想用 C++ 重写。 | Python |
| [`RZ_print`](https://github.com/Randycarteronion/RZ_print) | 命令行打印参数管理 + 调用佳博 Gprinter，可配 QZ Tray。 | Python |
| [`GUI_singbox_cn`](https://github.com/Randycarteronion/GUI_singbox_cn) | sing-box 跨平台 GUI + 日志分析。 | Vue |
| [`steam--`](https://github.com/Randycarteronion/steam--) | Steam 远程同乐键盘映射（"让 A330 客机也能用大键盘"）。 | C# |
| [`Ros-Protocol`](https://github.com/Randycarteronion/Ros-Protocol) | Consent Management Smart Contract Suite（Solidity + Hardhat），UN SDG 16 Digital Public Good。 | Solidity |
| [`C-Plus-Plus2`](https://github.com/Randycarteronion/C-Plus-Plus2) | 各种数学 / ML / 算法题用 C++ 教学性实现集合。 | C++ |
| [`ev-server`](https://github.com/Randycarteronion/ev-server) | Open e-Mobility 充电桩管理后端 fork（不是我的项目，跟着学）。 | Java |
| [`Randy.Carter1028`](https://github.com/Randycarteronion/Randy.Carter1028) | 还在加载…… | — |
| [`knowledgeops-agent`](https://github.com/Randycarteronion/knowledgeops-agent) | **共创者**：Spring AI 企业级 agent 工程基线，主要由 `however-yir` 设计与维护，我在自己的 fork 上做 bug 修复与 PR。 | Java |

---

## 联系方式 / How to reach me

- GitHub issues 是首选
- 兴趣：嵌入式、固件、CLI 工具、企业 AI 后端（学）、咖啡馆、历史、旅行、电影、足球
- 引用 Lovecraft 的话收尾：*"That is not dead which can eternal lie, and with strange aeons even death may die."*

---

<!--
Randycarteronion/Randycarteronion is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
