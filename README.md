<!--
  Randycarteronion/Randycarteronion profile README.
  Written in first person, in the voice of a hardware/embedded engineer who
  also pokes at Python tooling and is now learning Spring AI.
  Not a copy of however-yir.
-->

# Hi, I'm Randycarteronion (a.k.a. randevermist)

I am a **hardware / embedded** person who also writes Python tools when I need to automate something. My GitHub login honours Randolph Carter from H. P. Lovecraft — *"The most merciful thing in the world, I think, is the inability of the human mind to correlate all its contents."*

I am interested in works of art and elegant code. I am currently learning **Rust**, **Go** and (slowly) **Spring AI** so I can stop hand-soldering every time I want a smarter box.

I can't stand clueless client-side managers who pretend to be experts and act full of themselves!!!

这世界有很多的可能性，然而，然而。 未来会是什么样子，令人期待。

---

## What I actually work on

- **Battery management & STM32 firmware** — most of my "real" work is bare-metal C on STM32F103 + bq76920. I ship protection logic (over/under voltage, overcurrent, short-circuit, balancing) for a LiFePO4 pack.
- **ESP32 bring-up & sensor glue** — Ai-Thinker ESP32-CAM + DHT 温湿度, the usual "first PCB after blinking an LED" stuff.
- **Python tooling that solves one small annoyance** — auto sign-in, printer control, telegram file-id fetchers. Nothing pretty, but I use them daily.
- **A hardware execution runtime for AI coding agents** — `hardware-harness`: let an LLM agent flash, run, observe, and test an MCU the same way it can already run shell.
- **Smart contracts** — `Ros-Protocol`: a consent-management suite (Solidity + Hardhat) intended as a Digital Public Good (UN SDG 16).
- **A CLI for printing on receipt printers** — `RZ_print`, which talks to 佳博 Gprinter drivers and pairs with QZ Tray.
- **A cross-platform sing-box GUI client** — `GUI_singbox_cn`, with strong log analysis built in.
- **A keyboard remapper** so my laptop can drive Steam Remote Play on a 32-inch display without a tiny-keyboard death.

I also keep a fork of `however-yir/knowledgeops-agent` (`knowledgeops-agent` here) — I am reading it to learn how enterprise Spring AI agents are wired, not to claim it as my own work.

---

## 语言 / 工具 / 平台

### 我最熟的（嵌入式 + 底层）
![C](https://img.shields.io/badge/-C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![STM32](https://img.shields.io/badge/-STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/-FreeRTOS-0091BD?style=flat-square&logo=freertos&logoColor=white)
![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![KiCad](https://img.shields.io/badge/-KiCad-314CB6?style=flat-square&logo=kicad&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

### 用来自动化日常琐事的
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Solidity](https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Hardhat](https://img.shields.io/badge/-Hardhat-FFF100?style=flat-square&logo=hardhat&logoColor=black)
![Vue](https://img.shields.io/badge/-Vue-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### 正在学 / 正在读源码
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring AI](https://img.shields.io/badge/-Spring%20AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

---

## 项目目录 / What is in each repo

| Repository | What it actually is | Lang |
|---|---|---|
| [`BMS_F.F.R_R.C`](https://github.com/Randycarteronion/BMS_F.F.R_R.C) | CawBMS — 磷酸铁锂电池管理系统；STM32F103cbt6 + bq76920；过欠压 / 短路 / 过流保护 + 被动均衡。MIT 协议开源复刻。 | C |
| [`Ai-Thinker-ESP32-CAM`](https://github.com/Randycarteronion/Ai-Thinker-ESP32-CAM) | Ai-Thinker ESP32-CAM 摄像头 + 温湿度传感器集成。 | C |
| [`hardware-harness`](https://github.com/Randycarteronion/hardware-harness) | 给 AI 编码 agent 用的硬件执行 runtime：build → flash → run → observe → test，结构化反馈。 | Python |
| [`t00ls-`](https://github.com/Randycarteronion/t00ls-) | t00ls 论坛自动签到脚本，两种范式（requests / Selenium）。 | Python |
| [`tg_bot_fileid2`](https://github.com/Randycarteronion/tg_bot_fileid2) | 通过 TG url 拿 file_id 的小自动机，预备与 tdl 合用，未来想用 C++ 重写。 | Python |
| [`RZ_print`](https://github.com/Randycarteronion/RZ_print) | 命令行打印参数管理 + 调用佳博 Gprinter，可配 QZ Tray。 | Python |
| [`GUI_singbox_cn`](https://github.com/Randycarteronion/GUI_singbox_cn) | sing-box 跨平台 GUI + 日志分析。 | Vue |
| [`steam--`](https://github.com/Randycarteronion/steam--) | Steam 远程同乐键盘映射（"让 A330 客机也能用大键盘"）。 | C# |
| [`Ros-Protocol`](https://github.com/Randycarteronion/Ros-Protocol) | Consent Management Smart Contract Suite（Solidity + Hardhat），UN SDG 16 Digital Public Good。 | Solidity |
| [`C-Plus-Plus2`](https://github.com/Randycarteronion/C-Plus-Plus2) | 各种数学 / ML / 算法题用 C++ 教学性实现集合。 | C++ |
| [`ev-server`](https://github.com/Randycarteronion/ev-server) | Open e-Mobility 充电桩管理后端 fork（不是我的项目，跟着学）。 | Java |
| [`knowledgeops-agent`](https://github.com/Randycarteronion/knowledgeops-agent) | **fork** of `however-yir/knowledgeops-agent`，用来读 Spring AI 企业级 agent 怎么搭。**不是我的项目。** | Java |
| [`Randy.Carter1028`](https://github.com/Randycarteronion/Randy.Carter1028) | 还在加载…… | — |

我不维护"stars 数"之类的虚荣指标。仓库数量多是因为我把每个小实验都独立成仓，不爱用 monorepo。

---

## What I am reading / learning

- H. P. Lovecraft 短篇集 — 我换这个名字不只是装，Randolph Carter 在 *Through the Gates of the Silver Key* 里的失重感是我能描述"调试嵌入式 race condition"的最接近文学表达。
- **Rust** — 想在下一个无 RTOS 的小项目里用它取代 C++，看 async/await 能不能救我写裸机状态机的手。
- **Spring AI** — fork 上述仓库是因为我对 agent / tool calling / multi-tenant RAG 完全没经验，从工程基线读比从 blog 读稳。
- 跟着 [`knowledgeops-agent`](https://github.com/however-yir/knowledgeops-agent) 的 `bug_track.json` 学怎么写后端 PR：23 个 bug、20 个已修、5 类 CI check、checkstyle 上限、bug 编号管理……是教学材料。

---

## 联系方式 / How to reach me

- GitHub issues 是首选
- 兴趣：嵌入式、固件、CLI 工具、企业 AI 后端（学）、咖啡馆、历史、旅行、电影、足球
- 引用 Lovecraft 的话收尾吧：*"That is not dead which can eternal lie, and with strange aeons even death may die."*

---

<!--
Randycarteronion/Randycarteronion is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
