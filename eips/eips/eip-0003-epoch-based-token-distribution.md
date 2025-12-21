EIP: 0003
Title: Epoch-Based Token Distribution and Unlock Framework
Author: Alex Diaz
Status: Draft
Type: Standards Track
Created: 2025-12-21
Requires: EIP-0001, EIP-0002

Abstract

This EIP defines the epoch-based token distribution and unlock framework
for the Bit Brains protocol. The framework aligns token availability with
time-based participation, patience, and economic stewardship rather than
immediate liquidity or speculative access.

Token unlocks are progressive, cumulative, and tied to epoch completion.

Motivation

Early token distribution is a common source of misalignment in decentralized
protocols, often favoring short-term actors over long-term participants.

Bit Brains introduces an epoch-based unlock model to ensure that economic
availability reflects sustained alignment with the protocol’s values and
mechanics, as defined in EIP-0001 and EIP-0002.

Definitions

Epoch: A fixed-duration time period as defined in EIP-0002, used as the
primary accounting unit for participation and unlocks.

Public Allocation: Tokens designated for broad, permissionless availability
to participants, subject to epoch-based unlock constraints.

Cumulative Unlock: A distribution model in which unlocked tokens accumulate
over time and are never re-locked.

Supply Parameters

Total Token Supply: 80,000,000

Public Unlock Allocation: 85% of total supply (68,000,000 tokens)

Epoch Duration: 2 months per epoch

Total Epochs: 5

Total Unlock Horizon: 10 months

Epoch-Based Unlock Schedule

Token availability increases at the completion of each epoch. Unlocks are
cumulative and irreversible.

Epoch 1 (Months 0–2)
Cumulative Unlock: 17%
Tokens Unlocked: 13,600,000

Epoch 2 (Months 2–4)
Cumulative Unlock: 34%
Tokens Unlocked: 27,200,000

Epoch 3 (Months 4–6)
Cumulative Unlock: 51%
Tokens Unlocked: 40,800,000

Epoch 4 (Months 6–8)
Cumulative Unlock: 68%
Tokens Unlocked: 54,400,000

Epoch 5 (Months 8–10)
Cumulative Unlock: 85%
Tokens Unlocked: 68,000,000

Unlock Mechanics

Unlocks occur only at epoch boundaries.
Unlocked tokens remain unlocked permanently.
No cliff unlocks are present beyond epoch completion.
Token availability does not imply guaranteed rewards or yields.

The remaining 15% of total supply is intentionally excluded from this EIP
and may be defined in future specifications.

Relationship to Epoch Proof-of-Care

This EIP defines when tokens become available, not how influence or rewards
are earned.

Participation, influence, and care mechanics are defined exclusively in
EIP-0002. Token availability and participation are related but independent
dimensions.

Design Principles

Public-first distribution
Patience as an economic signal
Progressive, predictable unlocks
Minimal complexity
Auditability and clarity

Non-Goals

This EIP does not define:
- Governance rights
- Yield calculations
- Reward distribution formulas
- Secondary market behavior
- Offspring or derivative token systems

Rationale

By aligning token availability with time and epochs, Bit Brains reinforces
economic stewardship and discourages premature extraction.

The framework ensures that participants who demonstrate patience and
alignment are favored over short-term opportunistic behavior.

Security Considerations

Risks include strategic behavior around epoch boundaries and market
anticipation of unlock events. These risks are mitigated through transparent,
predictable scheduling and the absence of sudden liquidity cliffs.

Copyright

Copyright and related rights waived via CC0.
