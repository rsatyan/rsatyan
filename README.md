# Hi, I'm Satyan 👋

📍 **Philadelphia** | 🏦 **30+ yrs FinServ** (PNC, JPMorgan, Barclays) | 🔬 **Patent Holder** | 🤖 **AI-Native Builder**

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Electron](https://img.shields.io/badge/-Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![CLI](https://img.shields.io/badge/-CLI-000000?style=flat-square&logo=gnu-bash&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/-Codex-121212?style=flat-square&logo=openai&logoColor=white)

> Building AI-powered tools for financial services. 30+ years leading technology transformation at major banks. Now shipping tools that make professionals faster.

✨ [**Tessel**](https://gettessel.com) (closed source) — Lightning-fast clipboard transformer for macOS, Windows, and Linux. Copy anything, press a hotkey, get instant results. Background removal, PHI redaction, data cleaning, format conversion. 100% private, runs locally.

---

## 🔬 Patents

| Patent | Title | Assignee |
|--------|-------|----------|
| [US 9245262](https://patents.google.com/patent/US9245262) | **Systems and methods for bookmark payment processing** | JPMorgan Chase |
| [US 9811810](https://patents.google.com/patent/US9811810) | **Purchase data transmission and analysis system** | JPMorgan Chase |
| [US 10453038](https://patents.google.com/patent/US10453038) | **Purchase data transmission and analysis system** (continuation) | JPMorgan Chase |

---

## 🏦 LendCtl Suite

Open-source CLI tools for AI-powered loan origination. **8 tools, 165+ tests, Apache-2.0.**

```bash
npm i -g finctl-cli creditctl mortctl autoloanctl persctl cardctl compctl auditctl
```

| Tool | Description | npm |
|------|-------------|-----|
| 📊 [finctl](https://github.com/rsatyan/finctl) | **Income & DTI Calculator** — W-2, self-employment, and other income analysis with Fannie Mae-compliant calculations. Computes front-end and back-end debt-to-income ratios. | [![npm](https://img.shields.io/npm/v/finctl-cli.svg?style=flat-square)](https://npmjs.com/package/finctl-cli) |
| 🔍 [creditctl](https://github.com/rsatyan/creditctl) | **Credit Report Analyzer** — Parse credit reports, analyze tradelines, calculate representative scores, simulate rapid rescores, and identify derogatory marks. | [![npm](https://img.shields.io/npm/v/creditctl.svg?style=flat-square)](https://npmjs.com/package/creditctl) |
| 🏠 [mortctl](https://github.com/rsatyan/mortctl) | **Mortgage Underwriting** — LTV/CLTV calculations, PMI estimation, conforming loan limits, FHA MIP, VA funding fees, and program eligibility (Conventional, FHA, VA). | [![npm](https://img.shields.io/npm/v/mortctl.svg?style=flat-square)](https://npmjs.com/package/mortctl) |
| 🚗 [autoloanctl](https://github.com/rsatyan/autoloanctl) | **Auto Loan Calculator** — Vehicle LTV analysis, payment calculations, GAP insurance recommendations, dealer reserve computation, and term recommendations by vehicle age. | [![npm](https://img.shields.io/npm/v/autoloanctl.svg?style=flat-square)](https://npmjs.com/package/autoloanctl) |
| 💰 [persctl](https://github.com/rsatyan/persctl) | **Personal Loan Engine** — Unsecured loan eligibility, risk-based rate quotes, payment calculations, and multi-term comparisons for debt consolidation scenarios. | [![npm](https://img.shields.io/npm/v/persctl.svg?style=flat-square)](https://npmjs.com/package/persctl) |
| 💳 [cardctl](https://github.com/rsatyan/cardctl) | **Credit Card Decisioning** — Credit limit calculations, APR assignment by tier, balance transfer analysis with break-even, and credit line increase eligibility. | [![npm](https://img.shields.io/npm/v/cardctl.svg?style=flat-square)](https://npmjs.com/package/cardctl) |
| ✅ [compctl](https://github.com/rsatyan/compctl) | **Compliance Checker** — TRID timing validation, ATR/QM safe harbor analysis, and ECOA-compliant adverse action notice generation. | [![npm](https://img.shields.io/npm/v/compctl.svg?style=flat-square)](https://npmjs.com/package/compctl) |
| 📝 [auditctl](https://github.com/rsatyan/auditctl) | **Audit Trail Manager** — Immutable logging with hash chaining, PII sanitization, decision replay, integrity verification, and exam-ready exports. | [![npm](https://img.shields.io/npm/v/auditctl.svg?style=flat-square)](https://npmjs.com/package/auditctl) |

---

## 🤖 LendCtl Skill — AI Agent Integration

**[lendctl-skill](https://github.com/rsatyan/lendctl-skill)** — Production-ready skill for AI-powered loan origination.

Works with **any LLM capable of tool/function calling**:
- ✅ OpenAI (GPT-4, GPT-4o)
- ✅ Anthropic (Claude 3.5, Claude Code)
- ✅ Google (Gemini)
- ✅ Open-source (Llama, Mixtral via Ollama)

**6 Complete Workflows:**
| Workflow | Description |
|----------|-------------|
| 🏠 Mortgage | Full origination from application to compliance check |
| 🚗 Auto | Vehicle financing with LTV and GAP analysis |
| 💰 Personal | Unsecured loan eligibility and debt consolidation |
| 💳 Credit Card | New cards, CLI requests, balance transfers |
| ⚖️ Compare | Multi-product comparison (personal vs HELOC vs refi) |
| 📈 Credit Advisor | Score improvement strategies with savings projections |

---

## 🌐 WebMCP

- 🔧 [wmcp-annotate](https://github.com/rsatyan/wmcp-annotate) — CLI tool that analyzes websites and generates WebMCP annotations, enabling AI agents to interact with any web application through the W3C WebMCP standard (Chrome 146+)

---

## What I'm Building

- **Tessel** — Desktop productivity tool for instant clipboard transforms
- **LendCtl** — AI-native lending tools replacing $800/seat LOS software
- **Agentic workflows** — Tools designed for AI agents, not just humans

---

## Connect

[![LinkedIn](https://img.shields.io/badge/-Satyan%20Avatara-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/satyan-avatara-b853601)
[![Twitter](https://img.shields.io/badge/-@rsatyan-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/rsatyan)

---

*Apache-2.0 © Avatar Consulting*
