# 🗺️ Circuit Roadmap 2025
### Transparent Development & Ecosystem Growth Plan

---

## ⚡️ Phase 1 — Immediate Priorities (Next 48 Hours)

- [ ] **Publish Shield** — deploy public preview and generate live URL  
- [ ] **Add `/shield` page** — create landing page route within Circuit marketing site  
- [ ] **Connect Shield data to Control Hub** — integrate DAO metrics and treasury stats  
- [ ] **Run webhook/events test** — verify metrics aggregation from all live apps  
- [ ] **Generate SNS Config Template** — `sns_config.json` for Shield DAO launch prep  

🧠 *Outcome:* Shield goes live and integrates fully into Circuit Hub with DAO readiness.

---

## 🔧 Phase 2 — Near-Term Development (Next 7–14 Days)

- [ ] Admin “Create Proposal” modal (submit Shield DAO proposals from Hub)  
- [ ] Implement zk-Proof Verifier module (replace stub with WASM verifier)  
- [ ] Add compliance and audit controls (rate limits, allow/deny lists, logs)  
- [ ] Docs Portal — deploy auto-generated technical documentation site  
- [ ] Circuit Hub roadmap page (interactive checklist & task tracker)  

🎯 *Outcome:* Governance, compliance, and documentation layers operational.

---

## 🌐 Phase 3 — Infrastructure Enhancements (30–60 Days)

- [ ] Enable real-time webhooks and event pipelines for all apps  
- [ ] Admin analytics panel for activity, uptime, DAO votes, and proposals  
- [ ] SNS launch for Shield DAO  
- [ ] Treasury metrics visualizations (ckBTC balance, inflow/outflow, health index)  
- [ ] Add localization support (EN/ES/FR)  

🧠 *Outcome:* Fully data-aware, globally accessible Hub with live governance.

---

## 🌱 Phase 4 — Future App Pipeline

Each app is modular and will integrate into Circuit Hub via the same `get_metrics()` standard.

| App | Focus | Description | Status |
|------|--------|--------------|--------|
| **Signal** | Uptime & reliability | Monitor endpoints, uptime %, and alerts. | 🧩 Planned |
| **TrustCircle** | Social recovery | Guardian-based key recovery & continuity. | 🧩 Planned |
| **TimeCapsule** | Timed encryption | Encrypted file/message release by date or inactivity. | 🧩 Planned |
| **Relay** | Credential handoff | Share access links & passwords with expiry. | 🧩 Planned |
| **LedgerLite** | Privacy analytics | Personal crypto digest & privacy report. | 🧩 Planned |

---

## 🧩 Integration Roadmap
- [ ] Add all five pipeline apps to Circuit homepage & `/admin`  
- [ ] Standardize metrics ingestion with `get_metrics()` schema  
- [ ] Unify filters (“Active”, “Legacy”, “In Development”) in Hub dashboard  
- [ ] Expand Circuit Hub to support user-generated modules (Phase 5)  

🎯 *Outcome:* Circuit becomes a composable ecosystem for decentralized utilities.

---

## 🎨 Brand & Experience Goals
- Unified design system (Deep Slate `#1E1E2F`, Teal `#3FE0C5`)  
- Minimal, futuristic interface using Inter / DM Sans  
- Card-based layouts with animated transitions  
- Consistent user journey between marketing site, Hub, and apps  

---

## 🧠 Long-Term Vision
> Circuit is evolving into a **human-centered digital trust network** —  
> autonomous, transparent, and privacy-secure.  
> Every app strengthens the foundation of decentralized confidence  
> where data, continuity, and legacy converge under user control.

---

## 📅 Tracking
Each roadmap task is mirrored in the `/roadmap` dashboard inside the Circuit Hub for live progress tracking.  
Use that interface to toggle completion, assign owners, and timestamp milestones.
