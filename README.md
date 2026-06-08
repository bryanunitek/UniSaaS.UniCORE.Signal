# UniSaaS.UniCORE.Signal

**SCAFFOLD-ANCHOR repository — initial scaffold 2026-06-04.**

Full scaffolding, upstream-fork integration, and source-code work all pending a fresh dedicated kickoff arc. This initial commit exists to lock the repository's identity, licence position, and place in the UniCORE Sanity Check fleet so the work cannot be forgotten.

Author: **Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom.**
First commit: **2026-06-04 16:45 UTC.**

---

## What this repository is

`bryanunitek/UniSaaS.UniCORE.Signal` is the **Signal** family member: SaaS-deployment-shape public gift surface. Documentation today; source code at certification.

**Family purpose:** Open-source secure messaging server. End-to-end encrypted messaging with on-premise deployment capability for law-firm-grade secure communications.

**Role in UniCORE:** Secure messaging substrate — UniCORE.GVB substrate-services explore Signal-Server deployments for enterprise-grade secure communications where data sovereignty requires messages to never leave customer-controlled infrastructure.

**Deployment shape:** This is the **SaaS-shape** member of the family. It tracks the same upstream codebase as [`UniCORE.Signal`](https://github.com/bryanunitek/UniCORE.Signal) (on-prem shape) but carries SaaS-specific configuration, multi-tenant isolation patterns, and cloud-native deployment artefacts.

---

## Upstream

- **Upstream project:** [https://github.com/signalapp/Signal-Server](https://github.com/signalapp/Signal-Server)
- **Upstream licence:** AGPL-3.0
- **Our relationship:** Fork-and-extend. Upstream codebase consumed verbatim; our code additions carry AGPL-3.0; our documentation additions under CC BY 4.0.

---

## Platforms

Windows · Linux · macOS · iOS · Android

---

## Family — the four-repo pattern

- [`UniCORE.Signal`](https://github.com/bryanunitek/UniCORE.Signal) — public on-prem-deployment-shape gift surface
- `bryanunitek/UniSaaS.UniCORE.Signal` — public SaaS-deployment-shape gift surface ← **this repo**
- `bryanunitek/UniCORE.Signal-Claw` (private) — on-prem-shape working repository
- `bryanunitek/UniSaaS.UniCORE.Signal-Claw` (private) — SaaS-shape working repository

---

## Status

**SCAFFOLD-ANCHOR** as of 2026-06-04. See [`STATUS.md`](STATUS.md).

---

## Contact

- **Public discussion:** [GitHub Discussions](https://github.com/bryanunitek/UniSaaS.UniCORE.Signal/discussions)
- **Private contact:** [LinkedIn — Bryan Fred](https://www.linkedin.com/in/bryan-fred-02209753/)

---

*Author: Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom. Public. Given, not sold. Irrevocable.*
