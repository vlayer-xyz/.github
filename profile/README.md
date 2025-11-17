# vlayer

[**vlayer**](https://vlayer.xyz) empowers developers to extract, verify, and integrate real‑world web data into smart contracts. Powered by advanced **Zero‑Knowledge Proofs (ZKP)** and **Multi‑Party Computation (MPC)**, vlayer enables cryptographic verification of website and API data without revealing any sensitive underlying information.

With **Web Proofs**, you gain a unified toolkit that supports:
* [**server‑side proving**](https://docs.vlayer.xyz/server-side/introduction) for REST API, GraphQL or OAUTH calls.
* [**client‑side proving**](https://docs.vlayer.xyz/client-side/introduction) via browser extension and mobile verifier apps for session‑based sites.
* [**ZK proving**](https://docs.vlayer.xyz/blockchain/introduction), compressing proofs into zero-knowledge proofs so proofs can be verified on-chain .

---

## Example Use Case

Looking for a practical example? Check out the [**zk GitHub Contribution Verifier**](https://github.com/vlayer-xyz/zk-github-contribution-verifier), which demonstrates how to generate and verify GitHub contribution proofs using vlayer’s Web Proofs

---

## What is vouch?

[vouch](https://getvouch.io/) is a client-side proving system built on top of vlayer. It allows users to generate verifiable proofs from authenticated websites directly in their browser without exposing cookies, credentials, or private data.

Vouch enables:
- Privacy-preserving proofs tied to logged-in web sessions.
- Local TLS-based capture and proof generation via the browser extension.
- Simple verification by applications or smart contracts.

---

## Getting Started

Jump into the 📖 **[vlayer Docs](https://docs.vlayer.xyz/introduction.html)** for a full introduction, developer guides, and architectural explanations.

---

## Contributing

We welcome contributions from the community! Visit the **[Contributing Guide](https://book.vlayer.xyz/appendix/contributing/overview.html)** to learn about our development workflow, coding standards, and how to get involved.

---

## License

vlayer v1.0 adopts a **dual licensing model**:

* **vlayer Labs Ltd.** is the designated commercial licensor.
* The public codebase is provided under the **Business Source License (BSL) 1.1)**.
* After three years, the license automatically converts to the **MIT License**.

This model keeps the technology open for community innovation, protects early-stage development, and transitions to a fully permissive license to support long‑term growth.

By contributing, you agree that your contributions will be licensed under **BSL 1.1**.

---

## Acknowledgements

This project is inspired by and built upon the efforts of the open‑source community. Special thanks to:

* **[Steel](https://crates.io/crates/risc0-steel)** — Hardened off‑chain execution for EVM dapps.

---

## Security Audits

* ✅ **Veridise Audit Report (Q2 2025)** — [View Report](./audits/audit-2025-q2-veridise.pdf)
