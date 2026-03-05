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

## Use Cases

### 🤖 Autonomous Trading Agents
An AI trading agent is authorized to execute swaps on your behalf — but only up to $500 per trade, only on whitelisted DEXs, and never between 2–6 AM. Any trade exceeding the limit is queued for your approval before it broadcasts.

### 🛒 E-commerce Procurement Bots
Your purchasing agent can autonomously restock inventory using a virtual card — but only with approved vendors, with a $5,000 monthly cap, and purchases automatically expire after 30 days if unused.

### 🏢 Enterprise Agent Fleets
A company deploys 50 AI agents, each with isolated virtual cards and wallet scopes. Finance can audit every transaction across all agents from a single dashboard, with no access to private keys.

### 🧪 Research & Experimentation
A research agent runs DeFi strategies autonomously in a sandboxed environment. Gains are re-invested; losses are capped at a daily budget. No human oversight needed for routine operations — but the audit trail is always available.

---

## FAQ

**Q: Does Orclave ever hold my private keys?**
No. Orclave Layer is architecturally non-custodial — your private keys are never transmitted to or stored by Orclave. This is a cryptographic guarantee, not a policy choice.

**Q: What chains does Orclave support?**
Orclave supports EVM-compatible chains (Ethereum, Base, Arbitrum, Polygon, etc.), Solana, and major DeFi protocols natively. More integrations are added regularly.

**Q: What happens if an agent tries to exceed a spending limit?**
The transaction is blocked before it reaches the blockchain. Depending on your configuration, the agent receives an error, or the transaction is queued for manual approval.

**Q: Can I set different rules for different agents?**
Yes. Each agent gets its own wallet and/or virtual card with independent policies. You can group agents under shared policies or configure each one individually.

**Q: Is Orclave audited?**
Security audits are in progress ahead of mainnet launch. Our infrastructure is SOC 2 Type II compliant and all data is encrypted in transit (TLS 1.3) and at rest (AES-256).

---

## Contact

For partnerships, enterprise enquiries, or early access:
📧 [contact@orclave.com](mailto:contact@orclave.com)

---

<div align="center">
  <sub>Copyright © 2025 Orclave. All rights reserved.</sub>
</div>
