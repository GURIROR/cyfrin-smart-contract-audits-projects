# 🐶 Puppy Raffle Smart Contract Audit

This repository contains a smart contract audit for **Puppy Raffle**, a decentralized raffle system where users can win NFTs representing puppies of varying rarity.

---

## 📋 Audit Overview

- **Audit Period:** August 25 – September 1, 2023  
- **Auditor:** Gurmeet Kalyan  
- **Methodology:** Manual Review + Proof-of-Concept Testing (Foundry)  
- **Tools Used:** Foundry, Slither  
- **Scope:** `PuppyRaffle.sol`

---

## 🛡️ Issue Summary

| Severity       | Count |
|----------------|-------|
| High           | 4     |
| Medium         | 4     |
| Low            | 0     |
| Informational  | 8     |
| **Total**      | 16    |

📄 Read the full audit report in:
- [`puppy-raffle-audit.md`](./audit.md) — Markdown format
- [`puppy-raffle-audit.pdf`](./audit.pdf) — Polished PDF format

---

## 📁 Repository Structure

```bash
puppy-raffle-audit/
├── audit.md               # Full markdown audit report
├── audit.pdf              # Exported PDF version
├── README.md              # This file
├── src/                   # (Optional) Contract under audit
├── test/                  # Foundry tests with exploit PoCs
└── findings/              # (Optional) One markdown per issue
