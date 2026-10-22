# Decentralized Platform for Digital Certificate Issuance and Verification

A blockchain-based web platform enabling trusted issuance, storage, and instant verification of digital certificates using smart contracts deployed on Sepolia testnet.

---

## Problem Statement

Certificate fraud and the inability to instantly verify academic credentials without contacting the issuing institution are persistent problems in the job market. HR representatives manually verify certificates by calling institutions — a process that takes 1–3 days. This platform eliminates that friction by storing certificates on-chain, making verification instant and tamper-proof.

**Target users:**
- **Issuers** — universities, colleges, professional training centers
- **Holders** — students and graduates
- **Verifiers** — employers and partner organizations

**Expected outcomes:**
- Deployed smart contracts for certificate minting and revocation
- Functional web portal for all three user roles
- Verified certificate lifecycle: issue → share → verify → revoke

---

## Team & Supervisor

| Name | Role | Contact |
|------|------|---------|
| Rakymov Alikhan | Developer | 240164@astanait.edu.kz |
| Kydyrbekova Aigerim Balgabaevna, PhD | Supervisor | Aigerim.Kydyrbekova@astanait.edu.kz |

**Group:** SE-2413 · Astana IT University

---

## Project Scope

- Ethereum-compatible blockchain (Sepolia testnet)
- ERC-721 NFT certificates with on-chain metadata
- DAO-governed issuer registry (multi-issuer support)
- On-chain certificate revocation
- Frontend with ethers.js integration
- Foundry toolchain for smart contract development and testing
- IPFS for certificate metadata storage

**Out of scope (v1):** mobile app, mainnet deployment, paid certificate marketplace

---

## Selected Technologies

| Decision | Chosen | Alternatives Considered |
|----------|--------|------------------------|
| Blockchain | Ethereum / Sepolia | Polygon, Hyperledger Fabric |
| Token standard | ERC-721 | ERC-1155, custom struct |
| Frontend | plain html,css,Js|
| Smart contract toolchain | Foundry | Hardhat |
| Metadata storage | IPFS | Arweave, on-chain JSON |

---

## License

MIT
