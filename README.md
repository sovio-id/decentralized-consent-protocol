# Decentralized Consent Protocol (DCP)
Decentralized Consent Protocol (DCP) is a set of peer-to-peer data agreement interactions between various entities engaged in the Digital Consent workflows as described in the DPDPA

## 🎯 Problem Statement
The DPDP Act 2023 establishes clear legal requirements for obtaining, managing, withdrawing, and auditing user consent. However:
- The Act does not define a technical interoperability standard
- Existing implementations are platform-specific and non-portable
- Consent Managers risk becoming centralized points of control
- Cross-platform and cross-border consent verification remains difficult

DCP addresses this gap by defining a protocol layer—not a platform—that enables consent to function as digital public infrastructure.

## 🧩 What is DCP?
DCP is a protocol specification, not a product.

It defines:

- Standard roles
- Standard message flows
- Standard consent artifacts
- Standard verification and revocation mechanisms

All designed to align with DPDP Act consent requirements while remaining:
- Technology-neutral
- Consent Manager–agnostic
- Wallet- and identity-compatible
- Open-source and extensible

## 👥 Actors in the Protocol
DCP supports the following roles as described or implied under the DPDP Act:
- Data Principal (DP) : The individual to whom the personal data relates
- Data Fiduciary (DF) : The entity determining the purpose and means of processing personal data
- Consent Manager (CM) (optional) : An interoperable consent intermediary, if used
- Data Processor (DPo) : An entity processing personal data on behalf of a Data Fiduciary
- Auditor : An entity/person auditing the consent interactions for the purpose of auditing & reporting.

Each actor interacts via verifiable, peer-to-peer protocol messages rather than centralized APIs.

## 🔐 Core Design Principles
- Consent by design (not UI-driven consent)
- Privacy-preserving by default
- Minimal data disclosure
- Cryptographic auditability
- No central consent database
- Interoperability across ecosystems
- Alignment with Digital Public Infrastructure (DPI) Principles

## 🔄 Consent Lifecycle Covered by DCP
The protocol standardizes interactions across the full consent lifecycle:
- Consent notice issuance
- Consent request
- Consent grant or denial
- Consent modification / renewal
- Consent withdrawal
- Consent expiry & auto-revocation
- Consent status verification
- Audit & proof generation

Each interaction is represented as a verifiable protocol message.

## 📦 Key Protocol Artifacts

DCP standardizes the following artifacts:

- Consent Agreement Object
-- A machine-readable, signed record capturing purpose, scope, duration, and legal basis

- Consent Receipt
-- A portable, verifiable proof issued to the Data Principal

- Consent Status & Revocation Reference
-- Lightweight mechanisms to verify current consent validity without revealing personal data

- Audit Proofs
-- Cryptographic evidence of consent lifecycle events

## 🔧 Technology-Agnostic by Design
While compatible with:
- Decentralized Identifiers (DIDs)
- Verifiable Credentials (VCs)
- Digital wallets
- Secure messaging protocols

DCP does not mandate a specific identity or blockchain technology, allowing adopters to choose implementations suitable for their regulatory and operational context.

## 🌍 Ecosystem Compatibility
DCP is designed to interoperate with:
- India Stack & DPI initiatives
- Consent Managers under DPDP
- Account Aggregator (DEPA) ecosystem
- DigiLocker & digital credential systems
- Cross-border privacy frameworks (e.g., Alignment with GDPR or W3C Data Privacy Vocabulary)

## 🏛️ Governance & Open Source

- Open-source under a permissive license
- Neutral, vendor-independent protocol
- Community-driven evolution
- Intended for public good adoption
- Suitable for Digital Public Good (DPG) alignment

## 🚀 Project Goals
- Enable interoperable consent across platforms
- Reduce compliance friction for Data Fiduciaries
- Empower Data Principals with portable consent records
- Prevent consent monopolies
- Make consent verifiable, not just declarative

## ⚠️ Disclaimer
This project provides a technical protocol specification and does not constitute legal advice or regulatory certification. Organizations remain responsible for complying with all applicable laws and regulations under the DPDP Act, 2023.

## 🤝 Get Involved
We welcome:
- Protocol reviewers
- Legal & policy contributors
- Implementers & integrators
- Researchers & standards bodies

#### From [AYANWORKS](https://ayanworks.com) team who built and contributed [CREDEBL Platform](https://github.com/credebl) to Linux Foundation Decentralized Trust (LFDT)
