# EIP-0006: ENS Verification, Reward Routing, and Cerebral Lineage

## Status
Draft

## Author
Bit Brains Protocol

## Created
2025-12-26

## Abstract
This proposal defines a mandatory Ethereum Name Service (ENS)–based verification and reward routing mechanism for the Bit Brains Protocol. It establishes ENS resolution as the canonical payout destination for all rewards, introduces ENS-linked security guarantees, and specifies mint-time lineage metadata for Phase 2 Cerebrals.

## Motivation
To ensure transparent, non-custodial, and verifiable reward distribution, the protocol must bind rewards to identities that are:
- Human-readable
- On-chain verifiable
- User-controlled

ENS provides a canonical identity layer that satisfies these requirements while enabling composability with zero-knowledge (ZK) accounting systems.

## Specification

### 1. ENS Wallet Resolution (Phase 1: Brains)

#### Requirement
Each Genesis Brain MUST be associated with a deterministic ENS subdomain under `bitbrains.eth`.

Example format:
- `brain-####.bitbrains.eth`

#### Rules
- The Brain holder MUST resolve their ENS subdomain to a wallet they control.
- Rewards are routed exclusively to the resolved address of the ENS name.
- Arbitrary payout addresses MUST NOT be accepted.
- ENS resolution is the first required verification step for rewards eligibility.

#### Gas Responsibility
- ENS record updates and resolution gas costs are paid by the Brain holder.
- The protocol does NOT subsidize ENS gas fees.

### 2. Reward Accrual and Redemption

- Rewards accrue internally while a Brain remains staked.
- No on-chain transactions are required during accrual.
- When a holder chooses to claim rewards:
  - The holder initiates the transaction.
  - The holder pays the gas fee.
  - Rewards are released to the resolved ENS address.

### 3. Zero-Knowledge Accounting (ZK)

- ZK proofs MAY be used for eligibility, accounting, and compliance checks.
- ENS resolution remains the canonical payout destination regardless of ZK implementation.
- ZK systems MUST NOT override ENS-based routing.

## Phase 2: Cerebrals — ENS + Lineage

### ENS Naming (Cerebrals)
Each Cerebral MUST have a deterministic ENS subdomain under `bitbrains.eth`:

- `cerebral.<NN>.bitbrains.eth`

Where `<NN>` is a zero-padded Cerebral index (e.g., `01`, `02`, …).

### Artwork
- Cerebral NFTs SHOULD display only the Cerebral number (e.g., `01`) on the artwork.
- ENS names are NOT required to be displayed visually on the card.

### Mint-Time Lineage Metadata (Immutable)
At mint, each Cerebral MUST include immutable metadata linking it to its origin Brain.

Required metadata fields:
- `originBrainId`
- `cerebralIndex`
- `cerebralEnsName`
- `lineageNumber` (format: `<originBrainId>-<cerebralIndex>`)

This metadata MUST be set at mint and MUST NOT be modifiable.

### Provenance Guarantees
- Lineage establishes provable origin of each Cerebral.
- ENS + lineage binds rewards, ownership, and provenance to a single verifiable identity.

## Security Considerations
- ENS resolution prevents reward redirection attacks.
- User-controlled ENS ensures non-custodial payouts.
- Lineage metadata prevents counterfeit or orphaned Cerebrals.
- ZK accounting can enforce eligibility without revealing private data.

## Rationale
ENS provides a stable identity layer that:
- Is composable across Ethereum tooling
- Supports human-readable verification
- Enables deterministic reward routing
- Integrates cleanly with ZK systems

## Backward Compatibility
This proposal introduces no breaking changes for unstaked or inactive assets. Rewards eligibility begins once ENS resolution is completed.

## Reference Implementation
- ENS Manager (external): https://app.ens.domains
- Bit Brains ENS Verification Page: `/ens`

## Conclusion
ENS resolution is the canonical identity and reward routing mechanism of the Bit Brains Protocol. Combined with mint-time lineage and optional ZK accounting, this establishes a secure, scalable, and verifiable foundation for Phase 1 Brains and Phase 2 Cerebrals.
