# circuit-project
Dead man's switch suite of projects

🔒 Future Integration: vetKeys Support

Circuit’s architecture is designed for long-term compatibility with upcoming cryptographic standards on the Internet Computer. While the current system uses client-side encryption and canister-based timers to power its autonomous “dead man’s switch” logic, its modular key management layer is structured to seamlessly adopt vetKeys once available.

vetKeys (verifiable encryption and threshold keys) will enable multi-party key control and verifiable decryption, removing single points of failure. This integration will enhance privacy, trust, and decentralization — especially for GuardianKey and LifeCheck, which handle shared or delayed data releases.

🧩 Planned vetKeys Architecture Diagram (Text Summary)
 ┌─────────────────────────────────────────────────────────────┐
 │                      Circuit Framework                      │
 │─────────────────────────────────────────────────────────────│
 │ Apps: PingMe | Failsafe | GuardianKey | LifeCheck            │
 │    │                 │                 │                     │
 │    ▼                 ▼                 ▼                     │
 │  Encrypted payloads → Key Manager Layer (modular interface)  │
 │                                   │                          │
 │                                   ▼                          │
 │                       vetKeys Integration (future)            │
 │             ┌────────────────────────────────────┐            │
 │             │ Threshold Key Shards (M-of-N)      │            │
 │             │ Verifiable Encryption/Decryption   │            │
 │             │ Proofs shared across canisters     │            │
 │             └────────────────────────────────────┘            │
 │                                   │                          │
 │                                   ▼                          │
 │                       Authorized Recipients / Guardians       │
 └─────────────────────────────────────────────────────────────┘


Explanation:
Circuit’s modular encryption system will delegate cryptographic operations to the vetKeys layer when DFINITY releases developer support. vetKeys will allow data to be encrypted once, distributed among trusted canisters or guardians, and decrypted only when a threshold of approvals or time conditions are met. This ensures verifiable access control without compromising decentralization or user privacy.

🗓️ Implementation Roadmap

Phase 1 – Current (Live)

Client-side encryption and timer-based triggers power the dead man’s switch logic.

Each app operates autonomously but shares a consistent encryption interface.

Phase 2 – vetKeys Early Adoption (Future Release)

Replace or extend existing key-management logic with a vetKeys-enabled API once available.

Introduce M-of-N guardian approvals for LifeCheck and GuardianKey unlocks.

Deploy a new cryptographic verification canister to validate decryption proofs.

Phase 3 – Full vetKeys Integration

Transition all key release and legacy management flows to threshold-based, verifiable decryption.

Expose vetKeys-backed functionality in the Circuit Control Room for auditability and transparency.

Publish an updated SDK and documentation for developers integrating with Circuit’s trust framework.

📚 References & Research

DFINITY Forum: vetKeys Cryptography Discussion
 — overview of DFINITY’s research initiative.

DFINITY Medium: The Future of Cryptography on the Internet Computer
 — high-level look at threshold encryption and verifiable key management.

IC Developer Docs: Certified Variables and Cryptographic APIs
 — current reference for verified state and key handling.

DFINITY Research Paper: Verifiable Threshold Encryption (PDF)
 — foundational cryptographic concepts behind vetKeys.

Circuit is engineered to evolve alongside the Internet Computer’s cryptographic roadmap — ensuring that as the ecosystem advances, user trust, transparency, and autonomy remain at its core.

🧠 ICP Cryptography Alignment

Circuit’s design directly aligns with the Internet Computer’s core principles of decentralized automation, verifiable computation, and trustless continuity. Each app—PingMe, Failsafe, GuardianKey, and LifeCheck—demonstrates how autonomous canisters and certified data can perform real-world tasks securely without off-chain infrastructure.

By using timed canister triggers, Internet Identity authentication, and certified asset delivery, Circuit embodies the Internet Computer’s vision of end-to-end decentralization. Future adoption of vetKeys and threshold cryptography will further extend this trust model, enabling verifiable, multi-party control over encrypted data and access logic. In doing so, Circuit showcases how personal accountability, data continuity, and digital legacy management can operate entirely within a self-sovereign Internet ecosystem.
