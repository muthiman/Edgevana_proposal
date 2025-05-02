# Edgevana × Int3facechain — Validator Partnership Proposal

> **Date:** 2 May 2025  
> **Prepared by:** *Int3facechain Foundation*

---

## 1 · Executive Summary
Bitfrost is a high-performance Layer-1 blockchain implementing a novel leaderless, dynamic Threshold Signature Scheme (TSS) for secure cross-chain asset transfers. Built using a modified Cosmos SDK with Proof-of-Authority consensus, Bitfrost establishes trust-minimised bridges between heterogeneous blockchain architectures, particularly focusing on unlocking UTXO-based assets for broader ecosystem utility.
The protocol’s core innovation lies in its dynamic validator set implementation that,unlike previous TSS implementations requiring periodic key rotations during validator changes, Bitfrost’s architecture allows continuous operation with dynamic membership adjustments without interrupting service. The system employs a distributed multi-party computation (MPC) security model where no single validator possesses complete key material, yet a supermajority can collaboratively generate cryptographic signatures for cross-chain transactions.

Bitfrost’s bridge infrastructure comprises specialised validator components—scanners monitoring source chains for relevant transactions, observers validating transaction data, signers participating in the leaderless ECDSA threshold signature scheme, and clients broadcasting validated transactions to destination chains. This architecture currently facilitates $200K-$2M in daily transaction volume between UTXO chains and the Cosmos ecosystem.


The blockchain is secured by **1 billion INT3** via a dynamic **inflation‑deflation monetary design**. To deepen decentralisation and throughput we seek premier infrastructure partners. We invite **Edgevana** to operate a validator under a six‑month incentive programme that minimises capital outlay yet delivers attractive upside.

---

## 2 · Opportunity Overview

| Item | Terms |
|------|-------|
| **Validator‑set target** | 19 active validators (currently < 10) |
| **Up‑front hardware / hosting cost** | **$0** – fully covered by the Foundation |
| **INT3 purchase requirement** | **$50,000 – $200,000** ≈ 1–4 M INT3 |
| **Foundation delegation** | **+100% stake match** for the **first 6 months** |
| **Reward corridor (APR)** | 5% – 20%, adaptive |
| **Fee‑burn offset** | Up to **5 M INT3 / yr** burned at full usage |

---

## 3 · Economic Rationale

### 3.1 Reward Formula

```
APR = clip[ α_min + (α_max - α_min)(1 - v/v*)(REF_STAKE·v/S), 5%, 20% ]
```

Where:
* `v` — active validator count
* `v*` — ideal validator count (19)
* `S` — total INT3 staked
* `REF_STAKE` — reference stake (2.5M INT3)
* `clip[x, min, max]` — constrains x to the range [min, max]

With the ideal set reached, APR smoothly settles at 5%, keeping long‑run inflation below 0.5% of total supply.

### 3.2 Edgevana Return Scenarios (first 12 months)

| Scenario | Self‑stake | Foundation delegation (mo 1–6) | Effective stake (mo 1–6) | Stake (mo 7–12) | Indicative APR† | INT3 earned | Notes |
|----------|-----------|---------------------------------|---------------------------|------------------|-----------------|-------------|-------|
| **Starter** | 1 M | +1 M | 2 M | 1 M | 16% → 12% | ~260 k | Entry size |
| **Core** | 2.5 M | +2.5 M | 5 M | 2.5 M | 16% → 9% | ~625 k | Matches REF_STAKE |
| **Max** | 4 M | +4 M | 8 M | 4 M | 15% → 8% | ~870 k | Upper end |

†Assumes 8 validators, 15 M INT3 staked, 30% usage.

> *Example:* At **$0.05 / INT3**, the *Core* scenario yields **≈ $31k** in rewards during the incentive window, on a $125k capital allocation.

---

## 4 · Responsibilities & Commitments

### 4.1 Edgevana
* Operate a highly available, performance‑tuned validator (≥ 99.9% uptime).
* Participate in governance votes and security upgrades.
* Supply quarterly infrastructure & performance reports.

### 4.2 Int3facechain Foundation
* Provide & fund validator infrastructure (cloud or bare‑metal).
* Delegate INT3 equal to Edgevana's self‑bond for six months (non‑custodial).
* Offer 24 × 7 validator engineering support & monitoring.
* Review delegation after six months based on KPIs.

---

## 5 · Timeline

| Milestone | Target date |
|-----------|-------------|
| Memorandum of Understanding signed | **15 May 2025** |
| Infrastructure provisioned | **22 May 2025** |
| Validator live | **29 May 2025** |
| Incentive window ends | **1 Dec 2025** |
| Delegation review | **Dec 2025** |

---

## 6 · Strategic Benefits for Edgevana
1. **Early‑mover yield** while the validator set is still growing.
2. **Zero cap‑ex** — Foundation covers hardware & hosting.
3. **Aligned economics** — Fee burning supports long‑term scarcity.
4. **Brand visibility** on explorer & governance forums.

---

## 7 · Next Steps
We welcome a brief alignment call. Upon agreement we will circulate an MoU reflecting these terms and onboard Edgevana immediately.

---

© 2025 Int3facechain Foundation  
*Contact:* partnerships@int3face.org
