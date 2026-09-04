<!--
  Randycarteronion/Randycarteronion profile README.
  Inspired by https://github.com/however-yir
  Built on top of the 6 original skill badges (Python / RTOS / C++ / C / Linux / Go)
  with new badges added from the 2026 enterprise AI work.
-->

# Hi, I'm Randycarteronion

AI Engineer & Backend Developer focused on **deployable, verifiable, and operable** systems — from kernel-adjacent C to enterprise Java AI platforms.

Currently working on:

- Spring AI / RAG / Tool Calling / MCP / multi-agent orchestration
- Java / Spring Boot enterprise backend engineering
- Embedded systems, RTOS, and hardware-firmware integration (ESP32, etc.)
- Cross-language systems: C / C++ / Python / Go / Vue3 / TypeScript

> *Randolph Carter nods in approval from the margin of the page.*

---

## 精选项目矩阵 / Featured Projects

```text
knowledgeops-agent  -> enterprise AI baseline: RAG, workflow, memory, evaluation, multi-tenant
BMS_F.F.R_R.C       -> robotic control firmware: C, real-time, deterministic
hardware-harness    -> ESP32 / firmware / wireless bring-up (Python, C, Arduino-flavor)
t00ls-               -> offensive security toolkit snippets (Python, Bash)
Ai-Thinker-ESP32-CAM -> edge vision (ESP32-CAM, JPEG, Wi-Fi streaming)
GUI_singbox_cn       -> GUI client for sing-box (proxy / networking)
Ros-Protocol         -> smart-contract prototype (Solidity)
```

| Project | Role | Stack | Notes |
|---|---|---|---|
| [`knowledgeops-agent`](https://github.com/Randycarteronion/knowledgeops-agent) | Enterprise AI platform baseline | Spring AI, RAG, JWT/RBAC, MCP, MySQL, Flyway, Docker | 23 bugs fixed across multi-tenant, SSRF, SQL injection, XSS, RCE sandboxing |
| [`BMS_F.F.R_R.C`](https://github.com/Randycarteronion/BMS_F.F.R_R.C) | Robotic / firmware control code | C, RTOS, deterministic loops | Stars: 12 |
| [`hardware-harness`](https://github.com/Randycarteronion/hardware-harness) | Hardware bring-up and test harness | Python, C, serial | ESP32 / sensor driver path |
| [`Ai-Thinker-ESP32-CAM`](https://github.com/Randycarteronion/Ai-Thinker-ESP32-CAM) | Edge camera streaming | C, ESP-IDF, Wi-Fi, JPEG | |
| [`t00ls-`](https://github.com/Randycarteronion/t00ls-) | Security tooling scripts | Python, Bash | |
| [`GUI_singbox_cn`](https://github.com/Randycarteronion/GUI_singbox_cn) | sing-box desktop GUI client | Vue, networking | |
| [`Ros-Protocol`](https://github.com/Randycarteronion/Ros-Protocol) | Smart-contract / on-chain prototype | Solidity | |

---

## 技术路径 / Technical Path

- **5 分钟**：浏览 [`knowledgeops-agent` README](https://github.com/Randycarteronion/knowledgeops-agent)、架构图与 quick-start，关注多租户 + Agent 沙箱 + RAG 链路。
- **20 分钟**：阅读 `bug_track.json`（23 个 bug 的完整记录 + 修复策略）+ `CHANGELOG.md` + `evaluator-contract` CI workflow —— 验证这是一个**可跑、可观测、可被 PR 评审**的工程。
- **深入**：从 `WorkspaceRuntime` 的沙箱边界（path 校验 + rg flag deny-list）到 `HttpMcpToolAdapter` 的 SSRF 防护；再到 `IngestionService.processQueuedJob` 的租户隔离。
- **底层**：切到 `BMS_F.F.R_R.C` / `hardware-harness` / `Ai-Thinker-ESP32-CAM` 看 C / RTOS / 嵌入式如何做最严谨的边界检查（与 Java 沙箱是同一套思路的不同表达）。

---

## 技术栈 / Tech Stack

### 保留你原有的核心栈
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/-C-00599C?style=flat-square&logo=c&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![RTOS](https://img.shields.io/badge/-RTOS-0091BD?style=flat-square&logo=freertos&logoColor=white)

### 2026 年企业 AI 工作中新增的栈
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Spring AI](https://img.shields.io/badge/-Spring%20AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![pgvector](https://img.shields.io/badge/-pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Element Plus](https://img.shields.io/badge/-Element%20Plus-409EFF?style=flat-square&logo=element&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Solidity](https://img.shields.io/badge/-Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)

### 学习中 / Currently Learning
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)

---

## 项目介绍 / About `knowledgeops-agent`

`knowledgeops-agent` is the centerpiece of the matrix above — an **enterprise-grade AI platform** built on Spring Boot 3.4 + Spring AI 1.1.

**What it ships today:**

- **RAG pipeline** with hybrid retrieval (vector + keyword + knowledge graph + optional web search), pgvector backend, multi-tenant metadata filtering, citation footers
- **ReAct agent** with tool calling, MCP server adapter, and a **trusted runtime sandbox** (`workspace_*` actions) that path-validates every read/write and deny-lists ripgrep flags that could pivot to command execution
- **Deep Research** multi-agent workflow (plan → search → write) with task / step / event sourcing
- **Memory system** with short / long / task / fact tiers, `expires_at` filtering, and daily cleanup
- **Multi-tenant isolation** across every storage path (MySQL, conversation, memory, ingestion job, vector store)
- **Cost governance**: per-tenant monthly budget, per-tier pricing, hard-limit guard
- **Auth**: JWT (jjwt 0.13) + rotating API key + refresh token (one-shot revoke on reuse) + RBAC + tenant header override guard
- **Rate limit** with proxy-aware client IP (handles nginx / k8s ingress / ALB)
- **Observability**: Micrometer + Prometheus + structured JSON logs + MDC traceId / requestId

**Engineering practices demonstrated in the repo:**

- 23 documented bugs (5 high, 5 medium, ...) → 20 fixed → 3 deliberately tracked but not fixed (architectural, not code)
- Per-bug branch + per-bug PR (some merged inline, some via fork-PR flow)
- All 5 CI jobs green on every merged commit: `Lint / Build / Test` · `backend-quality` · `frontend` · `Secret Scan` · `evaluator-contract`
- 500-line checkstyle ceiling enforced
- `bug_track.json` is the single source of truth: id, title, location, description, handling, severity, discovery date, related PR

---

## Open Source Contributions

（待补充：可以列出你对 `spring-ai-alibaba/examples` 或其他上游的 PR）

---

## 联系方式 / Contact

- GitHub: [@Randycarteronion](https://github.com/Randycarteronion)
- 兴趣：AI 工具、嵌入式与固件、企业级后端、咖啡馆、历史、旅行、电影、足球
- 引用 H. P. Lovecraft 笔下的 Randolph Carter 命名 — *"The most merciful thing in the world, I think, is the inability of the human mind to correlate all its contents."*

---

<!--
Randycarteronion/Randycarteronion is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
