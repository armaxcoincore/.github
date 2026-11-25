# ArmaxCoin Core (`@armaxcoincore`)

**Open-Source Systems Engineering · Go · Blockchain Infrastructure · Applied Cryptography · Network Security**

ArmaxCoin Core is an independent open-source engineering organization focused on building reliable software systems, exploring applied cryptography, and developing decentralized infrastructure using Go.

Our work spans systems programming, distributed systems, blockchain protocols, network security, and infrastructure engineering.

We believe in transparent development, reproducible builds, responsible security practices, and open technical collaboration.

---

## Engineering Focus

| Domain | Focus Areas |
|---|---|
| **Go Systems Engineering** | Backend services, concurrency, CLI tools, performance, and system-level development |
| **Blockchain Infrastructure** | Proof-of-Work protocols, node architecture, transaction processing, and distributed consensus |
| **Applied Cryptography** | Post-quantum cryptography, digital signatures, hashing, and secure key management |
| **Network Engineering & Security** | P2P communication, TLS, network hardening, DoS mitigation, and secure RPC |
| **Storage & Reliability** | Embedded databases, atomic operations, data consistency, and recovery mechanisms |
| **Cross-Platform Development** | Linux, Windows, macOS, ARM64, and resource-constrained environments |

---

## Flagship Project

### ArmaxCoin — Experimental Layer-1 Proof-of-Work Blockchain

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/armaxcoincore/armax-coin/blob/main/LICENSE)
[![Go](https://img.shields.io/badge/Go-1.27%2B-00ADD8?logo=go&logoColor=white)](https://go.dev/)
[![Network](https://img.shields.io/badge/Network-ARMX--TESTNET--1-orange)](https://github.com/armaxcoincore/armax-coin/blob/main/docs/TESTNET.md)

**Repository:** [github.com/armaxcoincore/armax-coin](https://github.com/armaxcoincore/armax-coin)

An experimental Layer-1 blockchain built in Go, exploring deterministic Proof-of-Work consensus, post-quantum transaction security, and decentralized network infrastructure.

Key engineering components:

- NIST FIPS 204 ML-DSA-65 post-quantum transaction signatures.
- ArmaxHash v2 proof-of-work algorithm.
- Armax-ASERT-AW deterministic difficulty adjustment.
- P2P networking with TLS 1.3 and TOFU certificate pinning.
- Embedded storage using bbolt and atomic reorganization handling.
- Full node, CPU miner, Stratum client, CLI wallet, and desktop wallet.

**Network Status: Public Testnet Only**

The network operates on `ARMX-TESTNET-1`. Mainnet remains disabled (`core.MainnetLaunched = false`) pending independent technical and security reviews.

Testnet coins (`tARMX`) have no current market value or liquidity and are not an investment product.

[Technical Documentation](https://github.com/armaxcoincore/armax-coin/tree/main/docs) · [Testnet Guide](https://github.com/armaxcoincore/armax-coin/blob/main/docs/TESTNET.md) · [Mainnet Readiness](https://github.com/armaxcoincore/armax-coin/blob/main/docs/MAINNET_READINESS.md)

---

## Development Principles

1. **Open Development** — Transparent source code, documented changes, and accessible technical discussions.
2. **Security First** — Explicit trust boundaries, secure defaults, and responsible vulnerability disclosure.
3. **Deterministic Engineering** — Predictable system behavior, exact arithmetic, and reproducible execution.
4. **Resource Efficiency** — Practical software designed to operate across different hardware configurations.
5. **Responsible Releases** — Testing, validation, and independent review before production deployment.

---

## Open-Source Collaboration

We welcome developers, researchers, infrastructure operators, and open-source contributors interested in:

- Go programming and systems development.
- Blockchain and distributed systems.
- Linux infrastructure and node operations.
- Applied cryptography and protocol security.
- Networking, P2P architecture, and reliability engineering.
- Testing, documentation, and security research.

Contributions through issues, discussions, pull requests, and independent testing are welcome.

For security-sensitive vulnerabilities, please use private vulnerability reporting rather than public issues.

---

## Organization & Resources

| Resource | Link |
|---|---|
| GitHub Organization | [github.com/armaxcoincore](https://github.com/armaxcoincore) |
| Flagship Project | [ArmaxCoin Repository](https://github.com/armaxcoincore/armax-coin) |
| Website | [armax-coin.cloud](https://armax-coin.cloud) |
| Technical Documentation | [Project Documentation](https://github.com/armaxcoincore/armax-coin/tree/main/docs) |
| Releases | [GitHub Releases](https://github.com/armaxcoincore/armax-coin/releases) |
| Security Reporting | [Private Vulnerability Reporting](https://github.com/armaxcoincore/armax-coin/security/advisories/new) |
| Contact | dev@armax-coin.cloud |

---

*Building reliable systems. Exploring secure protocols. Contributing to open-source engineering.*
