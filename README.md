# Curated Reading List & Standards for Web3 Supply Chain Architecture

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Substrate](https://img.shields.io/badge/Substrate-FRAME-E6007A.svg)](https://substrate.io/)
[![Arbitrum](https://img.shields.io/badge/Arbitrum-AnyTrust-28A0F0.svg)](https://arbitrum.io/)
[![JAM Graypaper](https://img.shields.io/badge/Polkadot%20JAM-v0.7.2-black.svg)](https://graypaper.com/)
[![Portal](https://img.shields.io/badge/Portal-CLTD%20European%20Digital%20Trade%20Center-blue)](https://solomonbrokerage.com/cltd/)

## Mandatory Legal Attribution Notice (Estonian Copyright Act AutÕS § 12)

> **Mandatory Attribution Notice:**  
> Engineered under the DTLMF Architecture Blueprint. Original Concept and Intellectual Property © 2025–2026 Solomon Brokerage OÜ (Tallinn, Republic of Estonia). Sole Founder & Strategic Architect: Alejandro De La Parra Solomon. Licensed under MIT / CC BY 4.0.

## Regulatory Non-Affiliation Disclaimer

> **DISCLAIMER:**  
> DTLMF operates strictly as a voluntary B2B trade finance enablement utility outside the mandatory B2A platform certification scope of Regulation (EU) 2020/1056 Articles 11–13.

---

## Executive Overview

A curated technical compendium of authoritative academic specifications, regulatory whitepapers, architectural Gray Papers, and engineering standards for building enterprise Web3 supply chain networks and Shariah-compliant digital trade finance infrastructures.

---

## Production Core Repositories & Live Portal

This reading list directly informs the engineering of our production open-source engines:

* **Layer 1 Substrate Compliance Core:** [`polkadot-efti-compliance-core`](https://github.com/adelaparras/polkadot-efti-compliance-core) – Substrate FRAME pallets (`pallet-did-registry`, `pallet-efti-anchor-vc`) and XCMP KILT dispatchers.
* **Layer 2 Arbitrum Settlement Engine:** [`arbitrum-shariah-settlement-engine`](https://github.com/adelaparras/arbitrum-shariah-settlement-engine) – AAOIFI-compliant Murabaha, Musharakah, and Takaful EVM settlement contracts.
* **Client-Side Canonicalizer SDK:** [`dtlmf-efti-jcs-sdk`](https://github.com/adelaparras/dtlmf-efti-jcs-sdk) – Open RFC 8785 JSON Canonicalization Scheme and SHA-256 digest generator.
* **European Digital Trade Center (CLTD) Portal:** [https://solomonbrokerage.com/cltd/](https://solomonbrokerage.com/cltd/)

---

## The 5 Technical Architecture Pillars

```
+-------------------------------------------------------------------------------------------------+
|                               Web3 Supply Chain Technical Pillars                               |
+-------------------------------------------------------------------------------------------------+
|                                                                                                 |
|   Pillar 1: Blockchain Primitives & Substrate FRAME Architecture                                |
|   * Polkadot Host & Runtime Abstractions, Wasm/PolkaVM Execution Environment                    |
|   * Deterministic State Transitions, Custom Weight / Benchmarking Economics                     |
|   * Polkadot JAM (Join-Accumulate Machine) Gray Paper v0.7.2 (Gavin Wood)                       |
|                                                                                                 |
|   Pillar 2: Layer 2 EVM Scaling & Arbitrum AnyTrust Data Availability                           |
|   * Optimistic Rollups vs. AnyTrust Data Availability Committees (DAC)                          |
|   * Sub-Second State Finality, Micro-Transaction Gas Optimization for Maritime Cargo Units      |
|   * Nitro Technology Stack & Stylus Multi-Language Execution Contracts                          |
|                                                                                                 |
|   Pillar 3: Decentralized Identity (DID) & eIDAS Verifiable Credentials                        |
|   * W3C Recommendation: Decentralized Identifiers (DIDs) v1.0 & Verifiable Credentials v2.0    |
|   * Regulation (EU) 910/2014 (eIDAS) & European Digital Identity Framework (eIDAS 2.0)         |
|   * KILT Protocol Decentralized Trust & Revocation Infrastructures                              |
|                                                                                                 |
|   Pillar 4: Sovereign Privacy & Cryptographic Data Interoperability                            |
|   * RFC 8785: JSON Canonicalization Scheme (JCS) Specification                                  |
|   * AES-GCM-256 Envelope Encryption & Hardware Security Module (KMS/PKCS#11) Key Management    |
|   * GDPR Article 5(1)(c) "Hashes On-Chain, PII Off-Chain" Data Minimization Frameworks          |
|                                                                                                 |
|   Pillar 5: Islamic Fintech & AAOIFI Shariah Governance Standards                               |
|   * AAOIFI Shariah Standard No. 12: Sharikah (Musharakah) and Modern Corporations               |
|   * AAOIFI Shariah Standard No. 20: Sale on Murabaha to the Purchase Orderer                   |
|   * AAOIFI Shariah Standard No. 26: Islamic Insurance (Takaful) Rules & Operational Surpluses   |
|   * IFSB IS-1 & IS-2 Capital Adequacy Frameworks for Islamic Financial Institutions             |
+-------------------------------------------------------------------------------------------------+
```

---

## Essential Specifications & Primary Links

1. **European Union eFTI & eIDAS Standards:**
   - [Regulation (EU) 2020/1056 on electronic freight transport information (eFTI)](https://eur-lex.europa.eu/eli/reg/2020/1056/oj)
   - [Commission Delegated Regulation (EU) 2024/2529 (eFTI Common Data Sets)](https://eur-lex.europa.eu/eli/reg_del/2024/2529/oj)
   - [Regulation (EU) No 910/2014 on electronic identification and trust services (eIDAS)](https://eur-lex.europa.eu/eli/reg/2014/910/oj)

2. **Decentralized Protocol Specifications:**
   - [Polkadot: Join-Accumulate Machine (JAM) Gray Paper v0.7.2](https://graypaper.com/)
   - [RFC 8785: JSON Canonicalization Scheme (JCS)](https://datatracker.ietf.org/doc/html/rfc8785)
   - [W3C Decentralized Identifiers (DIDs) v1.0](https://www.w3.org/TR/did-core/)
   - [W3C Verifiable Credentials Data Model v2.0](https://www.w3.org/TR/vc-data-model-2.0/)

3. **Shariah & Financial Regulatory Standards:**
   - [AAOIFI Shariah Standards Official Repository](http://aaoifi.com/)
   - [IFSB Standards: Capital Adequacy Requirements for Sukuk, Securitisations and Real Estate](https://www.ifsb.org/)
   - [Bank for International Settlements (BIS): SME Trade Finance Disconnect & Digitalization (2025)](https://www.bis.org/)
