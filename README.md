# ⚡️ Circuit — Building the Future of Digital Trust
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](#)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](#)
[![Docs](https://img.shields.io/badge/docs-available-teal.svg)](#)
[![Powered by DFINITY](https://img.shields.io/badge/powered%20by-Internet%20Computer-orange.svg)](#)

---

### 🌐 Overview
**Circuit** is a unified suite of decentralized tools that simplify digital trust, continuity, and privacy — all built on the **Internet Computer (ICP)**.

Each app operates autonomously yet connects through **Circuit Hub**, your single control center for managing data, access, accountability, and digital legacy.

---

## 🚀 Live Applications

| App | Purpose | Description | Live URL |
|------|----------|--------------|-----------|
| **PingMe** | Accountability | Personal consistency tracker with time-based check-ins. | [Launch](#) |
| **Failsafe** | Data continuity | Autonomous, encrypted backup and recovery triggers. | [Launch](#) |
| **GuardianKey** | Shared access | Delegated key and credential sharing with recovery logic. | [Launch](#) |
| **LifeCheck** | Legacy handover | Automated inheritance and digital continuity management. | [Launch](#) |
| **Shield** | Privacy + governance | Privacy-enhanced token + DAO powering the Circuit ecosystem. | [Launch](#) |

---

## 🧭 Circuit Hub — Unified Dashboard
The **Circuit Hub** provides:
- Real-time analytics for all apps  
- Governance and proposal management (via Shield DAO)  
- Secure admin access (Internet Identity)  
- Live telemetry and system health  

🔗 [Access the Control Center](#)

---

## 🧠 Architecture
- **Frontend:** React + TypeScript  
- **Backend:** Motoko (Internet Computer canisters)  
- **Integration:** `get_metrics()` endpoints for all apps  
- **Governance:** SNS-compatible Shield DAO  
- **Hosting:** Decentralized asset canisters on ICP

---

## 🧩 Ecosystem Expansion
Circuit continues to evolve with a second generation of modular apps:

| App | Focus | Summary |
|------|--------|----------|
| **Signal** | Uptime monitoring | Realtime status pings + alerts with Circuit Hub integration. |
| **TrustCircle** | Social recovery | Guardian-based decentralized key recovery. |
| **TimeCapsule** | Timed encryption | Files/messages released after inactivity or schedule. |
| **Relay** | Secure handoff | Credential and access sharing with expiry + logs. |
| **LedgerLite** | Crypto digest | Privacy-safe analytics with “view key” transparency. |

---

## 📚 Documentation
- [Circuit Expansion Plan (PDF)](./docs/Circuit_Expansion_Plan.pdf)
- [Milestone Roadmap](./docs/ROADMAP.md)
- [Developer Guide](./docs/DEVELOPER_GUIDE.md)

---

## 🧱 Setup & Deployment

### Prerequisites
- [DFX SDK](https://internetcomputer.org/docs/current/developer-docs/quickstart/hello10mins/)
- Node.js 18+
- Internet Identity dev setup

### Local Deployment
```bash
dfx start --background
dfx deploy
npm run dev

## Environmental Variables
SHIELD_CANISTER_ID=
CIRCUIT_API_URL=
DFINITY_NETWORK=ic

🤝 Contributing
Pull requests and issue reports are welcome!
For major changes, open a discussion first to align on design direction.

🪙 License

MIT © 2025 Circuit Labs
Built with ❤️ on the Internet Computer (DFINITY)

Circuit is a human-centered digital trust network — autonomous, transparent, and privacy-secure — where data, continuity, and legacy all work together across decentralized systems.
