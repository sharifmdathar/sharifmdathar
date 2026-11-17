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
JWT + role-based access. 47 releases.

`Kotlin Multiplatform` · `Jetpack Compose` · `Fastify` · `PostgreSQL`

### [ChainChit](https://github.com/sharifmdathar/ChainChit) · [live](https://chain-chit.vercel.app)

On-chain chit fund (rotating savings) on Stellar: 5 Soroban contracts, ~3.9K lines
of Rust, covering group lifecycle, sealed bidding, identity, reputation, and
dispute resolution. Deployed on testnet with 50+ testnet users. Black Belt, Stellar
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
deployment demand differs from training demand? 16 Manhattan zones, 108 hourly
windows (6–14 April 2026), IPPO/MAPPO against tuned LP and greedy baselines.

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

## Open source

- [mpvRex/REX-Player#198](https://github.com/mpvRex/REX-Player/pull/198) — merged
- [dotfiles/dotfiles.github.com#429](https://github.com/dotfiles/dotfiles.github.com/pull/429) — merged
- [privateersclub/wiki#93](https://github.com/privateersclub/wiki/pull/93) — merged
- [mihonapp/mihon#4238](https://github.com/mihonapp/mihon/pull/4238) — vertical edge-swipe brightness gesture, with unit tests (open PR)
- [crmne/zapfast#1038](https://github.com/crmne/zapfast/pull/1038) — show the sender's name in the media viewer header for group chats (open PR)
- [alam00000/bentopdf#993](https://github.com/alam00000/bentopdf/pull/993) — externalize the `HASH_PARAMS` shim so CSP allows it (open PR)
- [alam00000/bentopdf#992](https://github.com/alam00000/bentopdf/pull/992) — Split-by-max-file-size, +353/−13 (open PR)
- [alam00000/bentopdf#980](https://github.com/alam00000/bentopdf/issues/980) — CSP blocks the inline `HASH_PARAMS` script in Add Stamps (issue)
- [alam00000/bentopdf#991](https://github.com/alam00000/bentopdf/issues/991) — split PDF by maximum file size (feature request)
- [mihonapp/mihon#4234](https://github.com/mihonapp/mihon/issues/4234) — left-edge vertical swipe gesture to adjust reader brightness (feature request)
- [oven-sh/bun#28722](https://github.com/oven-sh/bun/issues/28722) — `Date.now()` integer-overflow report (closed as fixed upstream)

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
