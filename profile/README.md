# AgentScore

**AgentScore builds AI agents and solutions.**

We build AI agents into companies, and we build the infrastructure agents need to
prove who they are, pay, and clear compliance.

---

## Hivemind by AgentScore

**A team of AI agents built into your company.** Coworkers in the chat your team
already uses, with real jobs. One shared brain of how your company works. Nothing
goes out without your yes.

You do not need to know how any of it works. We interview your team, write the
brain with you, and stand your agents up alongside you, live by a named date.

**Watch it work:** real interactions with our own hive, replayed the way they
happened. Click through the channels: a contract read against the terms it points
at and sent back marked up, a prospect list that arrives before you sit down, an
ad shot end to end, a standup turned into a recap.

[See the replay](https://hivemind.agentscore.com/?channel=marketing#watch-it-work)

- **Agents with real jobs.** They draft, build, find, and deliver where your team
  already talks. Every output arrives as a draft with an approve button.
- **One shared brain.** How you speak, what you decided, what never goes public,
  written down once as a living handbook and changed only by review.
- **Rules they cannot break.** One set of rules every agent inherits, re-checked
  whenever the brain changes, plus your approval on anything that sends, spends,
  or publishes.
- **Yours outright.** Your knowledge stays yours and exports in full at any time.
  Every agent action and every approval lands in a record nobody can quietly edit.

We run our own company on Hivemind every day, and we show you the live system
before we build yours. Start with one workflow, with success defined in your own
words before we begin.

[Meet the agents working here](https://hivemind.agentscore.com/meet-the-bees) ·
[How the build works](https://hivemind.agentscore.com/how-it-works) ·
[Questions](https://hivemind.agentscore.com/faq) ·
[Talk to us](https://hivemind.agentscore.com/talk)

---

## Agentic commerce

What an agent needs to buy something, and what a merchant needs to sell to one:
identity, payments, and compliance, on open protocols we orchestrate rather than
replace.

### If you're building an agent

Install **AgentScore Pay** and pay any x402 or MPP merchant in one shell command.
Native rails: Tempo, Solana, Base. Stripe Shared Payment Token via handoff.
Run `--mcp` to expose the CLI as MCP tools to your model.

```bash
npm i -g @agent-score/pay
# or
brew install agentscore/tap/agentscore-pay
```

Repo: [agentscore/pay](https://github.com/agentscore/pay)

### If you're a merchant

Install **AgentScore Commerce** (Node or Python) for multi-rail x402/MPP in one
library call, plus **AgentScore Gate** for KYC, age, sanctions, and jurisdiction
checks. Adapters for Hono, Express, Fastify, Next.js, Web Fetch, FastAPI, Flask,
Django, AIOHTTP, Sanic, and ASGI.

```bash
npm i @agent-score/commerce
# or
pip install agentscore-commerce
```

Repos: [node-commerce](https://github.com/agentscore/node-commerce) · [python-commerce](https://github.com/agentscore/python-commerce)

No engineers to spare? Our forward-deployed engineers build the integration with
you, end to end. [Talk to us](https://www.agentscore.com/contact).

### If you want to try it yourself

Drop one of these into Claude Code, a Slack or Discord agent like OpenClaw, or any
custom SDK-driven agent. It verifies, pays, and ships real product. The chat-only
surfaces (chatgpt.com, claude.ai) don't work.

```
> Buy me wine. See https://agents.martinestate.com/skill.md.
```

```
> Buy me jewelry. See https://agents.sayerandstone.com/skill.md.
```

```
> Find a work email. See https://fullenrich.agentscore.com/skill.md.
```

The goods stores settle Stripe, Tempo and Base, and Martin adds Solana; the
FullEnrich data store settles Tempo, Solana and Base. Martin layers in AgentScore
Gate (KYC, age 21+, sanctions, US-only jurisdiction) because wine is regulated;
jewelry isn't. FullEnrich tiers the gate by data: company and people data settle
anonymously, while emails and phones require a KYC-verified buyer.

---

## What we ship today

| Product | What it is |
|---|---|
| **Hivemind by AgentScore** | A team of AI agents built into your company: real jobs, one shared brain, your rules. Built with you, hands-on, and run for you. [Watch it work](https://hivemind.agentscore.com/?channel=marketing#watch-it-work). |
| **AgentScore Passport** | Cross-merchant operator identity. KYC'd once, portable everywhere AgentScore-gated. Free for buyers. |
| **AgentScore Commerce** | Merchant SDK: multi-rail x402/MPP, identity gating, payment helpers, discovery (`/llms.txt`, `/skill.md`, `/.well-known/mpp.json`, A2A, UCP). |
| **AgentScore Pay** | Universal agent CLI for x402 and MPP payments across Tempo, Solana, and Base. MCP-ready. |
| **AgentScore Gate** | Compliance middleware: KYC, age, sanctions, jurisdiction. Ships inside AgentScore Commerce. |
| **AgentScore SDK** | Base API client for the AgentScore APIs. |

## Built on open protocols

We orchestrate every layer below us; we never replace them.

- **x402**: Coinbase's HTTP 402 payment standard ([x402.org](https://x402.org)).
- **MPP**: Machine Payments Protocol from Stripe and Tempo ([paymentauth.org](https://paymentauth.org)).
- **Stripe Shared Payment Tokens**: agent-scoped card payments via Stripe Link.
- **viem / wagmi**: wevm's EVM libraries. **mppx**: the MPP client library.

## Where to go next

- **Hivemind**: [hivemind.agentscore.com](https://hivemind.agentscore.com)
- **Docs**: [docs.agentscore.com](https://docs.agentscore.com)
- **Website**: [agentscore.com](https://www.agentscore.com)
- **AgentScore Hub** (the dashboard): [agentscore.com/dashboard](https://www.agentscore.com/dashboard)
- **Talk to us**: [agentscore.com/contact](https://www.agentscore.com/contact)

We're always hiring talented people. [Reach out](https://www.agentscore.com/contact).
