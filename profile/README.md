# AgentScore

**Infrastructure for AI agents.**

Agents that buy: identity, payments, and compliance, orchestrated on any rail.
Agents that work: Hivemind by AgentScore, a governed brain and agent team inside your company.

---

## If you're building an agent

Install **AgentScore Pay** and pay any x402 or MPP merchant in one shell command.
Native rails: Tempo, Solana, Base. Stripe Shared Payment Token via handoff.
Run `--mcp` to expose the CLI as MCP tools to your model.

```bash
npm i -g @agent-score/pay
# or
brew install agentscore/tap/agentscore-pay
```

Repo: [agentscore/pay](https://github.com/agentscore/pay)

## If you're a merchant

Install **AgentScore Commerce** (Node or Python) for multi-rail x402/MPP in one
library call, plus **AgentScore Gate** for KYC, age, sanctions, and
jurisdiction checks. Adapters for Hono, Express, Fastify, Next.js, Web Fetch,
FastAPI, Flask, Django, AIOHTTP, Sanic, and ASGI.

```bash
npm i @agent-score/commerce
# or
pip install agentscore-commerce
```

Repos: [node-commerce](https://github.com/agentscore/node-commerce) · [python-commerce](https://github.com/agentscore/python-commerce)

No engineers to spare? Our forward-deployed engineers build the integration with you, end to end. [Talk to us](https://www.agentscore.com/contact).

## If you're exploring

Drop one of these into Claude Code, a Slack/Discord agent like OpenClaw, or any custom SDK-driven agent. It verifies, pays, and ships real product. The chat-only surfaces (chatgpt.com, claude.ai) don't work.

```
> Buy me wine. See https://agents.martinestate.com/skill.md.
```

```
> Buy me jewelry. See https://agents.sayerandstone.com/skill.md.
```

Both storefronts ship multi-rail x402/MPP payments (Stripe, Tempo, Base; Martin adds Solana). Martin layers in AgentScore Gate (KYC + age 21+ + sanctions + US-only jurisdiction) because wine is regulated; jewelry isn't.

---

## If you want agents working inside your company

**Hivemind by AgentScore** is our second line: one governed source of truth for how your
company works, and agent employees in your Slack that read it, own real jobs, and wait
for a human yes on anything that ships. We run our own company on it every day.
[Watch it work](https://www.agentscore.com/hivemind).

## What we ship today

| Product | What it is |
|---|---|
| **AgentScore Passport** | Cross-merchant operator identity. KYC'd once, portable everywhere AgentScore-gated. Free for buyers, forever. |
| **AgentScore Commerce** | Merchant SDK: multi-rail x402/MPP, identity gating, payment helpers, discovery (`/llms.txt`, `/skill.md`, `/.well-known/mpp.json`, A2A, UCP). |
| **AgentScore Pay** | Universal agent CLI for x402 + MPP payments across Tempo, Solana, and Base. MCP-ready. |
| **AgentScore Gate** | Compliance middleware: KYC, age, sanctions, jurisdiction. Ships inside AgentScore Commerce. |
| **AgentScore SDK** | Base API client for the AgentScore APIs. |
| **Hivemind by AgentScore** | A governed company brain plus agent employees in Slack, with a human yes on every write. |

## Built on open protocols

We orchestrate every layer below us; we never replace them.

- **x402**: Coinbase's HTTP 402 payment standard ([x402.org](https://x402.org)).
- **MPP**: Machine Payments Protocol from Stripe and Tempo ([paymentauth.org](https://paymentauth.org)).
- **Stripe Shared Payment Tokens**: agent-scoped card payments via Stripe Link.
- **viem / wagmi**: wevm's EVM libraries. **mppx**: the MPP client library.

## Where to go next

- **Docs**: [docs.agentscore.com](https://docs.agentscore.com)
- **Website**: [agentscore.com](https://www.agentscore.com)
- **AgentScore Commerce Hub** (the dashboard): [agentscore.com/dashboard](https://www.agentscore.com/dashboard)
- **Talk to us**: [agentscore.com/contact](https://www.agentscore.com/contact)

We're always hiring talented people. [Reach out](https://www.agentscore.com/contact).
