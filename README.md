# Hotels talk to AI through infrastructure I built.

I'm **Walid Slim** — AI Product Engineer at [Quicktext / Velma AI](https://www.quicktext.im).
I design and run the **Model Context Protocol layer** of a hospitality AI platform:
the gateway, the auth, the interactive apps — connecting hundreds of hotels to
**Claude, ChatGPT, and whatever comes next**.

```
57 MCP tools · 7 providers · 1,400+ commits · 100+ booking-engine integrations · 97% issue resolution
sources: git across 16 production repos · Jira 2023–2026 — counted, not estimated
```

### Don't read my portfolio. Interview it.

My portfolio is an MCP server. Add it to Claude and ask my career anything:

```bash
claude mcp add walid-slim -- npx -y github:slim00walid-prog/portfolio
```

```
› what did walid build, and what's the evidence?
› get_case_study gateway
› get_evidence "oauth"
```

### The three systems that define me

| | | |
|---|---|---|
| **The Moat** | Company-wide MCP gateway — 57 tools, OAuth 2.1, per-tool scopes, audit, k8s | NestJS · 25K LOC |
| **The Product** | AI hotel concierge — 4 LLM providers, 18+ tools, two-tier memory, <5ms warm | Next.js 15 · React 19 |
| **The Frontier** | MCP Apps — real React UI inside Claude & ChatGPT, live PMS bookings | ui:// · Apaleo |

### Frontier — bold bets on where agents are going (2026)

- [**agent-pay-mcp**](https://github.com/slim00walid-prog/agent-pay-mcp) — pay-per-call tools: agents spend money safely via budget-capped, single-use signed vouchers (the x402 / HTTP 402 revival)
- [**mcp-tool-poisoning-scanner**](https://github.com/slim00walid-prog/mcp-tool-poisoning-scanner) — a security linter that catches prompt-injection & tool-poisoning hidden in MCP servers before you trust them
- [**portable-memory-mcp**](https://github.com/slim00walid-prog/portable-memory-mcp) — one user-owned memory shared across Claude, ChatGPT & Cursor. No lock-in

### Foundations — production patterns, extracted

- [**nestjs-mcp-kit**](https://github.com/slim00walid-prog/nestjs-mcp-kit) — decorator-based MCP providers for NestJS: tools as code, generated scopes, per-caller tool visibility
- [**mcp-apps-demo**](https://github.com/slim00walid-prog/mcp-apps-demo) — a tool result that renders as interactive UI inside the agent (`ui://` + `structuredContent`/`widgetData` split)
- [**mcp-oauth-example**](https://github.com/slim00walid-prog/mcp-oauth-example) — OAuth 2.1 for MCP in one readable file: RFC 7591, PKCE, RS256/JWKS, RFC 9728 discovery

**Site:** [slim00walid-prog.github.io/portfolio](https://slim00walid-prog.github.io/portfolio/) ·
**CV:** [pdf](https://slim00walid-prog.github.io/portfolio/Walid_Slim_CV_2026.pdf) ·
**Contact:** slim00walid@gmail.com · [LinkedIn](https://www.linkedin.com/in/slim-walid)
