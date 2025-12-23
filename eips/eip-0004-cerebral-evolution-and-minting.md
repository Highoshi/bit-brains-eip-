# EIP-0004: Phase One Deployment Architecture (Ethereum ZK Rollup)

## Abstract

This EIP defines the Phase One deployment architecture for the Bit Brains protocol. Phase One establishes Brains as Ethereum-native entities deployed on an Ethereum-based zero-knowledge (ZK) rollup, providing a canonical environment for identity, stewardship, epoch progression, and proof-of-care accumulation.

---

## Motivation

Bit Brains is designed as a long-lived public-good protocol that prioritizes verifiability, composability, and alignment with Ethereum standards. Phase One intentionally limits scope to ensure a stable, auditable foundation before introducing optional extensions or experimental features.

Deploying on an Ethereum ZK rollup enables scalable interaction while preserving Ethereum security guarantees and ecosystem compatibility.

---

## Specification

### Canonical Execution Environment

- Phase One MUST be deployed on an Ethereum-based ZK rollup.
- Ethereum remains the canonical source of truth for:
  - Brain identity
  - Stewardship
  - Epoch timing
  - Proof-of-care state
  - Token unlock conditions

---

### Brain Representation

- Brains are represented in Phase One by non-fungible tokens (NFTs).
- These NFTs serve as proof-of-concept vessels and proof-of-care witnesses.
- NFT ownership establishes stewardship but does not imply autonomous behavior.

---

### Epoch System

- Epochs are fixed-duration time intervals enforced on-chain.
- Epoch progression is deterministic and globally verifiable.
- Proof-of-care accrues exclusively through valid epoch participation.

---

### Identity and Naming

- Brains MAY be optionally associated with Ethereum Name Service (ENS) records.
- ENS records serve as human-readable identifiers and metadata pointers only.
- ENS resolution MUST NOT affect canonical protocol logic.

---

### Open Source and Transparency (Phase One)

Phase One of the Bit Brains protocol is intentionally specified as fully open source and publicly verifiable.

All contracts, interfaces, and protocol mechanics defined in this phase MUST be implemented using open-source code and deployed in a manner that permits independent verification by any third party.

Epoch progression, proof-of-care validation, and Brain lifecycle state transitions MUST be observable and auditable on-chain within the selected Ethereum-based ZK rollup environment.

No privacy-preserving mechanisms are required or assumed in Phase One.

Future protocol phases MAY introduce optional privacy-preserving extensions, provided such extensions do not alter or invalidate the core invariants defined in Phase One.

---

## Explicit Exclusions

The following are intentionally excluded from Phase One:

- Cerebral layers
- Offspring or derivative systems
- Private execution or privacy-preserving mechanisms
- Cross-chain state execution

These components may be introduced in future phases and are out of scope for this EIP.

---

## Rationale

Restricting Phase One to a single Ethereum-native execution environment ensures clarity, minimizes risk, and preserves a canonical source of truth for time and care. This design enables future extensibility without compromising protocol integrity.

---

## Backwards Compatibility

This EIP introduces no breaking changes and defines Phase One architecture only.

---

## Copyright

CC0-1.0 Universal
