<div align="center">

# Walid Slim

### Hotels talk to AI through infrastructure I built.

**AI Product Engineer** · I design and run the Model Context Protocol layer of [Velma AI](https://www.quicktext.im) — the gateway, the auth, the interactive apps — connecting hundreds of hotels to Claude, ChatGPT, and whatever comes next.

[![Portfolio](https://img.shields.io/badge/Portfolio-interview_it-34d399?style=for-the-badge)](https://slim00walid-prog.github.io/portfolio/)
[![Email](https://img.shields.io/badge/Email-slim00walid@gmail.com-0c8f63?style=for-the-badge)](mailto:slim00walid@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-slim--walid-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/slim-walid)

`57 MCP tools` · `7 providers` · `1,400+ commits` · `100+ booking-engine integrations` · `97% issue resolution`
<sub>counted from git across 16 production repos · Jira 2023–2026 — not estimated</sub>

</div>

---

### Don't read my portfolio. Interview it.

My portfolio is itself an MCP server. Add it to Claude and ask my career anything:

```bash
claude mcp add walid-slim -- npx -y github:slim00walid-prog/portfolio
```
```
› what did walid build, and what's the evidence?
› get_case_study gateway
› get_evidence "oauth"
```

---

### What I do

I build the **infrastructure where AI agents meet real businesses** — safely. Three systems define the work:

| | System | What it proves |
|---|---|---|
| 🏰 | **The Gateway** — company-wide MCP gateway (NestJS, 25K LOC) | 57 tools, OAuth 2.1, per-tool scopes, audit, Kubernetes |
| 🛎️ | **The Concierge** — embeddable AI hotel concierge | 4 LLM providers, 18+ tools, two-tier memory, `<5ms` warm |
| 🪟 | **MCP Apps** — interactive UI inside Claude & ChatGPT | live PMS bookings rendered in the agent |

A single thread runs through everything I build: **move trust from the prompt to the protocol.** Instructions are wishes; enforced interfaces are guarantees.

---

### Open source

**Frontier — bold bets on where agents are going**

- 💸 [**agent-pay-mcp**](https://github.com/slim00walid-prog/agent-pay-mcp) — pay-per-call tools: agents spend money safely via budget-capped, single-use signed vouchers *(x402 / HTTP 402)*
- 🛡️ [**mcp-tool-poisoning-scanner**](https://github.com/slim00walid-prog/mcp-tool-poisoning-scanner) — a security linter that catches prompt-injection & tool-poisoning hidden in MCP servers before you trust them
- 🧠 [**portable-memory-mcp**](https://github.com/slim00walid-prog/portable-memory-mcp) — one user-owned memory shared across Claude, ChatGPT & Cursor. No lock-in

**Foundations — production patterns, extracted**

- 🧩 [**nestjs-mcp-kit**](https://github.com/slim00walid-prog/nestjs-mcp-kit) — decorator-based MCP providers for NestJS: tools as code, generated scopes, per-caller tool visibility
- 🪟 [**mcp-apps-demo**](https://github.com/slim00walid-prog/mcp-apps-demo) — a tool result that renders as interactive UI inside the agent *(`ui://` + structuredContent/widgetData split)*
- 🔐 [**mcp-oauth-example**](https://github.com/slim00walid-prog/mcp-oauth-example) — OAuth 2.1 for MCP in one readable file: RFC 7591, PKCE, RS256/JWKS, RFC 9728 discovery

---

### Toolbox

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-34d399?style=flat-square)

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OAuth2.1](https://img.shields.io/badge/OAuth_2.1_·_PKCE-EB5424?style=flat-square&logo=auth0&logoColor=white)

<div align="center"><sub>Building the agent layer for hospitality — and the safety rails the whole industry needs. Open to roles & collaboration.</sub></div>
