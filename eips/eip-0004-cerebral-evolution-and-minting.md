# EIP-0004: Cerebral NFTs & Reward Pathways

EIP: 0004  
Title: Cerebral NFTs and Reward Pathways  
Author: Alex Diaz  
Developer: OnGod  
Status: Draft  
Type: Standards Track  
Category: Core  
Created: 2025-12-22  

---

## Abstract

This EIP defines the Cerebral NFT layer within the Bit Brains ecosystem. Cerebrals function as the primary interface for staking, reward distribution, identity signaling, and future autonomous intelligence development.

This proposal establishes the structure, purpose, reward pathways, phase progression, expansion mechanics, and royalty routing for the Cerebral layer.

---

## Motivation

The Bit Brains protocol is designed to reward long-term alignment, continuity, and constructive participation over time.

This EIP introduces Cerebrals to:
- Expand participation without diluting core stewardship
- Enable staking-based reward distribution
- Support identity, ENS, and signaling primitives
- Create a progression path toward economic and autonomous utility

---

## Definitions

- **Brain**  
  The genesis NFT representing the earliest and longest-lived commitment to the Bit Brains ecosystem.

- **Cerebral**  
  An ERC-721 NFT derived from Brains or authorized Expansion Epochs, serving as a staking, participation, and progression primitive.

- **Proof of Care (PoC)**  
  Sustained participation, staking continuity, and ecosystem-aligned behavior maintained across defined epochs within a phase, validated by ZK accountability.

- **Phase**  
  A protocol lifecycle stage (e.g., Brain Phase, Cerebral Phase, Brainiac Phase) consisting of five (5) epochs.

- **Epoch**  
  A time-bounded accountability interval (approximately one month) within a phase, during which ZK proofs evaluate continuity, PoC signatures, and non-interference.

- **Expansion Epoch**  
  A governance-authorized event introducing additional Cerebrals to support ecosystem growth and broader participation.

- **Real World Assets (RWA)**  
  Tokenized or represented economic activities, goods, or services that exist outside purely digital systems.

---

## Cerebral Overview

Cerebrals are ERC-721 NFTs that represent active participation within the Bit Brains ecosystem. They serve as the primary interface for staking, reward distribution, identity signaling, and future autonomous intelligence development.

Cerebrals may be:
- Earned through Brain participation (Genesis entitlement path)
- Minted during authorized Expansion Epochs (Public + Treasury allocations)
- Utilized for staking and reward accrual
- Evolved into higher-order components over time

---

## Genesis Cerebrals

Each **Brain** is entitled to mint up to **two (2) Genesis Cerebrals** through defined staking and participation mechanics.

Genesis Cerebrals represent early alignment and inherit preferential reward pathways relative to later Expansion participants, subject to Proof of Care requirements.

---

## Brain-to-Cerebral Progression and Minting Eligibility

Brains that complete the Brain stage may optionally qualify to mint up to **two (2) Genesis Cerebrals**.

### Eligibility requirements

The Brain participant must fully stake:
- All earned Brain-phase BIT rewards (if/when distributed at Phase settlement), and
- Associated Brain participation rewards (as defined by protocol), and
- Maintain required staking continuity for the Cerebral eligibility window.

**Continuity requirement for Genesis Cerebral eligibility:**  
Full staking must be maintained continuously throughout **Phase 2 (Cerebral Phase) Epochs 1–5**.

Partial staking or early withdrawal during Phase 2 Epochs 1–5 disqualifies the Brain from full (two) Genesis Cerebral eligibility.

---

## Expansion Cerebrals

To support ecosystem growth and broader participation, the protocol authorizes Expansion Cerebrals through governance-approved Expansion Epochs.

Expansion Cerebrals:
- Are minted under defined supply constraints
- Receive lower base reward pathways than Genesis Cerebrals
- Retain the ability to increase reward capacity through sustained Proof of Care

---

## Expansion Epoch I — Public & Treasury Allocations

- **Total Cerebrals Minted:** 1,500  
- **Public Mint Allocation:** 1,350  
- **Team Treasury Allocation:** 50  
- **Reward Treasury Allocation:** 150  

Treasury-allocated Cerebrals are reserved exclusively for protocol-defined purposes, including:
- Long-term reward sustainability
- Ecosystem incentives and onboarding
- Contributor recognition
- Community-driven growth initiatives

---

## Secondary Market Royalty Structure (Expansion Epoch I)

All Expansion Epoch I Cerebrals are subject to a **3% secondary market royalty**, enforced at the contract level and distributed as follows:

- **1% → Reward Treasury**
- **1% → Artist**
- **1% → Founder**

These royalties reinforce long-term rewards funding, support creative contributors, and sustain protocol stewardship.

---

## Brain Holder Rendered Cerebral Artifacts

Brain holders may be entitled to receive a rendered Cerebral NFT representing symbolic and cultural linkage to the Cerebral layer.

Rendered Cerebral artifacts:
- Are art-focused NFTs
- May include an ENS-linked subdomain identifier
- Do not confer staking rights
- Do not emit rewards
- Do not participate in governance

These artifacts exist solely as identity and cultural primitives and do not constitute functional Cerebrals.

---

## Reward Distribution Framework

Cerebrals participate in protocol reward distribution through staking and epoch-based mechanisms. Reward emissions are sourced from fee allocations, royalty flows, and phase-defined distributions.

### Phase-based reward settlement (global rule)

Rewards are distributed **after every Phase**, not mid-phase.

Each Phase consists of **five (5) epochs**, with each epoch representing approximately **one (1) month** of participation. During each epoch, Zero-Knowledge Proof (ZKP) systems perform accountability analysis to validate:
- Staking continuity
- Proof of Care signatures
- Non-interference behavior

No rewards are distributed mid-phase.

### Phase 1 — Brain Phase (first unlock + BIT emergence)

During **Phase 1**, BIT rewards are distributed to Brain holders who:
- Stake their Brain NFTs, and
- Sign Proof of Care and continuity commitments

ZKP accountability runs monthly across **Epochs 1–5**.

**At the end of Phase 1 (Epoch 5),** following completion of ZKP validation, rewards are finalized.  
Within approximately **two (2) weeks into Epoch 6**, the protocol distributes Phase 1 rewards, marking the first emergence and distribution of the **Brain Intelligence Token (BIT)** within the Bit Brains ecosystem.

### Subsequent phases

Each subsequent Phase follows the same structure:
- Five epochs of participation and ZKP accountability
- Reward eligibility determined by Proof of Care and staking continuity
- Reward distribution occurs only after the final epoch of the Phase concludes

Epochs serve as accountability and analysis intervals, while Phases serve as reward settlement boundaries.

---

## Reward Pathway Hierarchy and Proof of Care

The Bit Brains protocol prioritizes continuity, stewardship, and long-term participation over short-term extraction.

Brains represent the earliest and longest-lived commitment within the ecosystem.

Cerebrals form the second-order participation layer and receive meaningful rewards, with clear pathway differentiation:
- **Genesis Cerebrals:** preferential pathways (earned via Brain participation + Phase 2 continuity)
- **Expansion Cerebrals:** public-access pathways (lower base than Genesis, upgradeable via Proof of Care)

---

## Phase Progression and Eligibility Summary

### Phase 1 — Brain Phase
- Brain NFT holders stake their Brain NFTs and sign Proof of Care + continuity commitments.
- ZKP accountability runs monthly across Epochs 1–5.
- **Rewards are distributed after Epoch 5**, within ~two weeks into Epoch 6 (first BIT emergence).

### Phase 2 — Cerebral Phase
Brain holders become eligible to mint up to **two (2) Genesis Cerebrals** if they:
- Stake their Brain NFT
- Stake their earned BIT rewards (as required by protocol)
- Maintain uninterrupted staking across **Phase 2 Epochs 1–5**

Failure to stake both assets continuously may reduce eligibility per protocol rules.

### Phase 3 — Brainiac Phase (eligibility outcome)
At completion of Phase 2:
- **Two (2) Brainiacs** may be spawned if both the Brain NFT and BIT rewards were staked continuously
- **One (1) Brainiac** may be spawned if only one of the two assets was staked

This structure rewards maximum continuity while allowing partial participation paths.

---

## Supply and Emissions Context

The Bit token has a maximum supply of **200,000,000 BIT**.

Cerebral rewards are not guaranteed, fixed, or unconditional.

---

## Security Considerations

Cerebrals introduce staking and reward mechanisms that require safeguards against:
- Reward manipulation
- Sybil behavior
- Premature extraction

Safeguards and audits will be addressed in future EIPs.

---

## Governance Considerations

Changes to Cerebral issuance, allocation, royalties, or reward pathways are subject to governance processes defined elsewhere.

---

## Conclusion

This EIP defines the Cerebral layer as a progression-based participation and reward system that prioritizes continuity, ZK-verified Proof of Care, and long-term stewardship within the Bit Brains ecosystem.
