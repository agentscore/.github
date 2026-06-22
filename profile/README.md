# AgentScore

**The agentic commerce stack.**

Identity, payments, and compliance — orchestrated for AI agents.

---

## If you're building an agent

Install **AgentScore Pay** and pay any 402 or MPP merchant in one shell command.
Native rails: Tempo, Solana, Base. Stripe Shared Payment Token via handoff.
Run `--mcp` to expose the CLI as MCP tools to your model.

```bash
npm i -g @agent-score/pay
# or
brew install agentscore/tap/agentscore-pay
```

Repo: [agentscore/pay](https://github.com/agentscore/pay)

## If you're a merchant

Install **AgentScore Commerce** (Node or Python) for multi-rail 402 in one
library call, plus **AgentScore Gate** for KYC, age, sanctions, and
jurisdiction checks. Adapters for Hono, Express, Fastify, Next.js, Web Fetch,
FastAPI, Flask, Django, AIOHTTP, Sanic, and ASGI.

```bash
npm i @agent-score/commerce
# or
pip install agentscore-commerce
```

Repos: [node-commerce](https://github.com/agentscore/node-commerce) · [python-commerce](https://github.com/agentscore/python-commerce)

## If you're exploring

Drop one of these into Claude Code, a Slack/Discord agent like OpenClaw, or any custom SDK-driven agent. It verifies, pays, and ships real product. The chat-only surfaces (chatgpt.com, claude.ai) don't work.

```
> Buy me wine. See https://agents.martinestate.com/skill.md.
```

```
> Buy me jewelry. See https://agents.sayerandstone.com/skill.md.
```

Both storefronts ship multi-rail 402 payments (Stripe, Tempo, Solana, Base). Martin layers in AgentScore Gate (KYC + age 21+ + sanctions + US-only jurisdiction) because wine is regulated; jewelry isn't.

---

## What we ship today

| Product | What it is |
|---|---|
| **AgentScore Passport** | Cross-merchant operator identity. KYC'd once, portable everywhere AgentScore-gated. Free for buyers, forever. |
| **AgentScore Commerce** | Merchant SDK — multi-rail 402, identity gating, payment helpers, discovery (`/llms.txt`, `/skill.md`, `/.well-known/mpp.json`, A2A, UCP). |
| **AgentScore Pay** | Universal agent CLI for x402 + MPP payments across Tempo, Solana, and Base. MCP-ready. |
| **AgentScore Gate** | Compliance middleware — KYC, age, sanctions, jurisdiction. Ships inside AgentScore Commerce. |
| **AgentScore SDK** | Base API client for the AgentScore APIs. |

## Built on open protocols

We orchestrate every layer below us; we never replace them.

- **x402** — Coinbase's HTTP 402 payment standard.
- **MPP** — Machine Payments Protocol from Tempo and paymentauth.org.
- **Stripe Shared Payment Tokens** — agent-scoped card payments via Stripe Link.
- **viem / wagmi** — wevm's EVM libraries. **mppx** — the MPP client library.

## Where to go next

- **Docs** — [docs.agentscore.sh](https://docs.agentscore.sh)
- **Website** — [agentscore.sh](https://agentscore.sh)
- **AgentScore Hub** (merchant dashboard) — [agentscore.sh/dashboard](https://agentscore.sh/dashboard)
- **Talk to us** — [agentscore.sh/contact](https://agentscore.sh/contact)

We're always hiring talented people — [reach out](https://agentscore.sh/contact).
