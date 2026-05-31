<div align="center">

# Adarsh Prashar

### Backend & distributed-systems engineer · building [RiskKernel](https://github.com/prashar32/riskkernel) (open-source agent reliability) and [The Sunrize](https://thesunrize.com) (AI trading co-pilot)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-adarshprashar-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/adarshprashar)
[![Email](https://img.shields.io/badge/Email-adarsh.prashar32@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:adarsh.prashar32@gmail.com)
[![Codeforces](https://img.shields.io/badge/Codeforces-Candidate%20Master%20·%202048-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/prashar32)
[![The Sunrize](https://img.shields.io/badge/The%20Sunrize-live-22c55e?style=flat-square)](https://thesunrize.com)
[![RiskKernel](https://img.shields.io/badge/RiskKernel-live-22c55e?style=flat-square)](https://github.com/prashar32/riskkernel)

</div>

---

## 🚢 The Sunrize — AI trading co-pilot

<a href="https://thesunrize.com">
  <img src="./assets/thesunrize.png" alt="The Sunrize — Mission Control" width="100%" />
</a>

🔗 **[thesunrize.com](https://thesunrize.com)** · private beta

Built solo, end-to-end. Frontend, backend, agents, risk engine, broker integration, billing, infra.

| Component | What it does |
|---|---|
| **Six-agent AI architecture** | HELM (orchestrator) · PULSE (news) · PRISM (technicals) · HORIZON (macro) · SENTRY (risk) · LEDGER (auto-journal). Multi-model — Claude + GPT — with per-user spend caps. |
| **Server-enforced risk engine** | 2% per trade · 6% monthly cap · 15% position size · 3 concurrent positions. Hard-coded, no overrides. |
| **Live broker execution** | Zerodha Kite via official API. Smart bracket orders. Idempotent under network retries. |
| **Nifty straddle scalper** | Automated ATM straddle. Black-Scholes pricing, India-VIX-derived IV for paper mode. |

![Next.js](https://img.shields.io/badge/Next.js%2014-000000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-072654?style=flat-square&logo=razorpay&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-181818?style=flat-square)

---

## 🛡️ RiskKernel — open-source SRE layer for AI agents

🔗 **[github.com/prashar32/riskkernel](https://github.com/prashar32/riskkernel)** · Apache-2.0 · Go core + Python SDK

A self-hosted reliability runtime for AI agents. Deterministic cost / loop / time budgets and a kill switch — all enforced in compiled Go, never by an LLM.

| Capability | What it does |
|---|---|
| **Deterministic enforcement** | Cost, loop, and wall-time budgets enforced in compiled Go. No "the model decides when to stop." |
| **Kill switch** | Pull the plug at the runtime layer. Survives any prompt-injection or agent reasoning failure. |
| **Crash-resumable runs** | SQLite-backed run state. Restart anywhere in the loop. Git-native, owned memory. |
| **Human approval gates** | Side-effecting tool calls (writes, payments, deletes) require a human signature. |
| **OpenTelemetry GenAI export** | Plug into the OTel ecosystem; no proprietary lock-in. |
| **One env var to adopt** | BYO key, no telemetry, no signups. |

Adapters for Claude Agent SDK, OpenAI Agents SDK, and LangChain.

Positioning: the *risk-engine / SRE layer* for AI agents. Not a gateway (LiteLLM), not an observability dashboard (Langfuse), not a content-guardrail engine — interoperates with all of them.

> "I've spent years building deterministic risk engines that wrap non-deterministic systems — the kind where a mistake costs real money. The safe part was never the smart part; it was the hard-coded layer around it. RiskKernel generalizes that discipline for AI agents."

---

## 🏢 Previously at Omniful

First backend engineer when the team was 10. Stayed through it crossing 150.

<table>
<tr>
<td width="50%" valign="top">

**Order Management Service**
75K+ orders/day · 99.9999% uptime · first commit → launch

**Shipment Management Service** — *"the brain"*
500K+ shipments/month · +35% delivery accuracy

**ClickHouse analytics layer**
1M+ transactions/month · sub-second p95

**Rule Management Service**
−50% feature rollout time · 800+ global sellers

</td>
<td width="50%" valign="top">

**Centralized Logging Service**
Adopted by every backend team · cut platform-wide incident response 40%

**Monolith → microservices** (+ DB migration)
Led end-to-end · zero downtime, zero data loss

**Platform reliability**
SLO-driven monitoring, automated deploys, unified API versioning, 10× peak-traffic scaling

**IC scope**
Built platform tooling from concept to production as the team scaled 10 → 150+

</td>
</tr>
</table>

Stack: Go · PostgreSQL · MongoDB · RocksDB · Redis · Kafka · ClickHouse · AWS

> Most of my code lives in private org repos. **[Snapshot of recent activity →](https://github.com/adarsh-omniful)**

---

## 🏆 Competitive Programming

<table>
<tr>
<td width="50%" valign="top" align="center">

<a href="https://codeforces.com/profile/prashar32">
  <img src="https://codeforces-readme-stats.vercel.app/api/card?username=prashar32&theme=midnight-purple" alt="Codeforces stats" />
</a>

</td>
<td width="50%" valign="top" align="center">

<a href="https://leetcode.com/prashar32">
  <img src="https://leetcard.jacoblin.cool/prashar32?theme=dark&font=Source%20Code%20Pro&ext=heatmap" alt="LeetCode stats" />
</a>

</td>
</tr>
</table>

| Platform | Status |
|---|---|
| **Codeforces** | Candidate Master · 2048 *(top ~100 in India)* |
| **CodeChef** | 6★ · 2208 |
| **LeetCode** | Guardian · 2249 *(top 0.5%, all-time)* |
| **ICPC** | 2× Regionalist |
| **Google Code Jam** | Round 2 qualifier (2021) |
| **Meta Hacker Cup** | Round 2 qualifier (2021) |

**~3,000 problems solved.** Set 400+ problems for InterviewBit / Scaler Academy hiring contests.

---

## 🧠 Outside work

Independent evaluation work on frontier LLMs — rubric design, response grading, inter-rater reliability, eval pipelines.

---

## 🛠️ Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

---

<div align="center">

👀 **Open to founding-engineer · backend · AI-infra roles.**

**[adarsh.prashar32@gmail.com](mailto:adarsh.prashar32@gmail.com) · [linkedin.com/in/adarshprashar](https://linkedin.com/in/adarshprashar) · [github.com/prashar32](https://github.com/prashar32)**

</div>
