<div align="center">

<img src="public/logo_transparent.png" alt="Orclave Layer" width="80" />

# Orclave Layer

**The programmable spending layer for autonomous AI agents.**

Set limits. Enforce rules. Safeguard assets — without sacrificing agent autonomy.

[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js)](https://nextjs.org)
[![Supabase](https://img.shields.io/badge/Auth-Supabase-3ECF8E?style=flat-square&logo=supabase)](https://supabase.com)

</div>

---

## Overview

As AI agents begin executing real financial transactions autonomously, there is no infrastructure layer that enforces *your* rules. Orclave Layer sits **between your agent and the blockchain**, enforcing programmable spending policies on every on-chain or off-chain action.

**Your agents keep full autonomy. You keep full control.**

---

## How It Works

Orclave Layer acts as a middleware between your AI agents and any financial endpoint — wallets, virtual cards, or DeFi protocols. Every transaction request from an agent passes through the Orclave Rules Engine before it is signed or broadcast.

```
Your AI Agent → Orclave Layer (Rules Engine) → Blockchain / Payment Network
```

1. **You define the rules** — Set per-transaction limits, daily spend caps, address whitelists, merchant restrictions, and time-based gates from the dashboard.
2. **Your agent requests a transaction** — It sends the action to Orclave's API just like any standard wallet or payment call.
3. **Orclave validates the request** — The Rules Engine checks the action against your active policies in real time.
4. **The transaction is approved or blocked** — Compliant actions execute immediately. Flagged actions are queued for human approval or rejected outright.
5. **Everything is logged** — Every decision, approval, and rejection is written to an immutable audit trail.

---

## Core Capabilities

### 🔐 Non-Custodial Wallets
AI agents can hold and transact on-chain without you handing over your private keys. Orclave issues scoped, policy-bound wallets that expire or revoke automatically.

### 💳 Virtual Cards for Agents
Issue Visa-compatible virtual cards directly to your AI agents. Each card carries its own spending limit, merchant category restrictions, and automatic expiry — purpose-built for autonomous workflows.

### ⚙️ Spending Rules Engine
Define fine-grained policies that enforce themselves:
- Per-transaction and daily spend caps
- Address whitelists and blacklists
- Merchant category restrictions
- Time-based windows (e.g. business hours only)
- Chain-specific restrictions

### ✅ Approval Gates
Flag high-value or unusual transactions before they execute. Your team receives a real-time request to approve or reject — giving you a human checkpoint without blocking your agent's workflow.

### 📋 Full Audit Trail
Every action your agent takes is logged immutably. See the full history of approvals, rejections, amounts, timestamps, and addresses — all in one dashboard.

### 🔗 Native DeFi Integrations
Orclave Layer works across EVM-compatible chains, Solana, and major DeFi protocols out of the box. No custom adapters required.

---

## Getting Started

```bash
git clone https://github.com/orclave/orclave-layer.git
cd orclave-layer
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | [Next.js 15](https://nextjs.org/) — App Router |
| Auth | [Supabase](https://supabase.com/) — Google & GitHub OAuth |
| Styling | Vanilla CSS with custom design tokens |
| Fonts | Syne & DM Sans via Google Fonts |
| Deployment | [Vercel](https://vercel.com/) |

---

## Contact

For partnerships, enterprise enquiries, or early access:
📧 [contact@orclave.com](mailto:contact@orclave.com)

---

<div align="center">
  <sub>Copyright © 2025 Orclave. All rights reserved.</sub>
</div>
