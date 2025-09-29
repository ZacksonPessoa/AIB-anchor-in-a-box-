

**Anchor-in-a-Box (AIB)** is an open-source package to launch a **SEP-compatible Stellar Anchor** in hours, not weeks.  
It provides out-of-the-box support for **SEP-10 (Auth)**, **SEP-12 (KYC/KYB)**, **SEP-24 (Deposit/Withdraw)**, and **SEP-31 (Cross-Border Payments)**, plus observability, developer tooling, and demo wallets.

---

## ✨ Features

- **SEP-1**: `stellar.toml` generator + compliance linter  
- **SEP-10**: WebAuth server (JWT, multi-domain, multi-asset)  
- **SEP-12**: Customer API (KYC/KYB), schema validation, webhooks  
- **SEP-24**: Interactive Deposit/Withdraw UI, transaction callbacks  
- **SEP-31**: Receive-side quotes/fees, transaction updates, webhooks  
- **Demo Wallet**: Web (Wallet SDK/Freighter) + Mobile example (Expo)  
- **Observability**: p50/p95 latencies, error rates, business logs  

---

## 🚀 Why AIB?

- **Time-to-market**: bootstrap a full anchor with `docker compose up`  
- **Consistency**: standardized DX with Postman Collection, lint, demo wallet  
- **Production-ready**: Helm charts, SLOs, dashboards, runbooks  
- **Extensible**: adapters for PSPs/banks (ACH/SEPA/PIX mock included)  

---

## 📅 Roadmap

- **MVP (Weeks 1–8)** → Core SEPs, mock bank adapter, observability, demo wallet  
- **Testnet (Weeks 9–12)** → Public test environment, Helm, quickstart docs  
- **Mainnet Ready (Weeks 13–20)** → Security hardening, Admin UI, scaling playbooks  
- **Mainnet (Weeks 21–24)** → Public endpoints, SLO compliance, documentation  

---

## 📖 Documentation

- **Quickstart**: `docker compose up` → run anchor stack locally  
- **Postman Collection**: test SEP endpoints in minutes  
- **stellar.toml Wizard**: generate and validate your configuration  
- **Admin UI**: KYC review, limits, reconciliations  

---

## 🛠️ Status

- Current phase: **Development**  
- Prototype: SEPs 10/12/24/31 already tested locally  
- Next milestone: **Testnet deployment (Weeks 9–12)**  

---

## 📜 License

MIT License. Open-source and free to use.
