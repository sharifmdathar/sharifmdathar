# Md Athar Sharif

**Backend & systems engineer** — Rust, Kotlin, distributed systems, ZK/Stellar.
B.Tech CSE, IIIT Naya Raipur · Raipur, India

[![site](https://img.shields.io/badge/%F0%9F%8C%90-athar.is--a.dev-0b0b0f?style=flat-square&labelColor=0b0b0f)](https://athar.is-a.dev)
[![LinkedIn](https://img.shields.io/badge/%F0%9F%92%BC-LinkedIn-0A66C2?style=flat-square&labelColor=0A66C2)](https://www.linkedin.com/in/md-athar-sharif-ba90a630a/)

I build systems that have to be right, not just running — ZK-verified contracts,
and software that institutions actually depend on.

---

## Flagship projects

### [IIITNR Inventory System](https://github.com/sharifmdathar/iiitnr-inventory-app) · [live](https://inventory.iiitnr.ac.in)

Institute-wide inventory management, officially adopted by IIIT Naya Raipur.
Android, iOS, desktop, and web from one shared Kotlin codebase — offline-first,
JWT + role-based access.

`Kotlin Multiplatform` · `Jetpack Compose` · `Fastify` · `PostgreSQL`

<!-- TODO: the 43-release count appears on athar.is-a.dev but is unverified via API (first releases page showed 30+). Add once confirmed. -->

### [ChainChit](https://github.com/sharifmdathar/ChainChit) · [live](https://chain-chit.vercel.app)

On-chain chit fund (rotating savings) on Stellar: 5 Soroban contracts, ~3.9K lines
of Rust, covering group lifecycle, sealed bidding, identity, reputation, and
dispute resolution. Deployed on testnet with 50+ users. Black Belt, Stellar
Journey to Mastery.

`Rust` · `Soroban` · `Next.js` · `TypeScript`

### [AegisProcure](https://github.com/sharifmdathar/AegisProcure) · [live](https://aegis-procure.vercel.app)

Trustless sealed-bid reverse auctions for B2B/GovTech procurement on Midnight —
bids stay confidential end to end while the chain still verifies validity.
4 ZK circuits: create, commit, reveal, finalize.

`Compact` · `Midnight` · `ZK` · `Next.js`

### [TrustVault](https://github.com/sharifmdathar/trustvault) · [live](https://trustvault-ten.vercel.app/)

Decentralized escrow on Stellar with built-in arbitration and fee sponsorship,
plus contract-level timeout enforcement. Blue Belt, Stellar Journey to Mastery.

`Soroban` · `React` · `TypeScript`

### [MARL Fleet Rebalancing](https://github.com/sharifmdathar/marl-fleet-rebalancing)

Measurement study: how do frozen RL fleet-rebalancing policies degrade when
deployment demand differs from training demand? 62 NYC zones with real ride-hail
demand, IPPO/MAPPO against tuned LP and greedy baselines.

`Python` · `PettingZoo` · `RL`

### [Dynamic Island for Omarchy](https://github.com/sharifmdathar/dynamic-island-omarchy)

QML media/notification bar widget for Omarchy (Hyprland), published and verified
in the official plugin marketplace.

`QML` · `Hyprland`

### [Delhi-NCR PM2.5](https://github.com/sharifmdathar/delhi-ncr-pm25)

Hourly PM2.5 spatiotemporal forecasting for Delhi-NCR — does a wind-aware dynamic
graph beat a static distance graph?

`Python`

---

## Stack

**Languages** Rust · Kotlin · Go · TypeScript
**Systems** distributed systems (Raft) · ZK / Stellar / Soroban / Midnight

---

## Currently

Building a from-scratch Raft consensus implementation with a deterministic
simulation harness. Open to internships and systems/ZK engineering collaborations.

<!-- TODO: Tuishark (packet-sniffer TUI), uded (hardware-diagnostics CLI), mini-redis — all currently private; no links until public. -->
<!-- TODO: Go is listed above, but the only Go repos are private (iiitnr-inventory-app-go, codecrafters-claude-go). Confirm before a recruiter goes looking. -->
