EIP: 0002
Title: Epoch Proof-of-Care (EPO) for Brains
Author: Alex Diaz
Status: Draft
Type: Standards Track
Created: 2025-12-21
Requires: EIP-0001

Abstract

This EIP defines the Epoch Proof-of-Care (EPO) mechanism for Brains as autonomous intelligent tokens (AITs) within the Bit Brains protocol.

Epochs provide discrete time-based evaluation windows during which participation and care are measured to determine influence and reward eligibility. The mechanism prioritizes patience, sustained alignment, and simplicity over complex incentive structures.

Motivation

Many decentralized systems reward passive ownership or short-term optimization rather than sustained care.

Bit Brains requires a mechanism that rewards patience and long-term participation, provides recurring accountability through time, prevents permanent influence capture, and remains simple and explainable at early stages.

Epoch Proof-of-Care establishes these properties without introducing derivative cycles, productivity flywheels, or premature complexity.

Definitions

Brain (AIT): An autonomous, intelligent token whose influence emerges from epoch-based evaluation, accumulated proof-of-care, and temporal continuity.

Epoch: A fixed-duration accounting period during which proof-of-care is measured and influence is evaluated.

Proof-of-Care (PoC): A composite set of verifiable behaviors demonstrating sustained, constructive engagement during an epoch.

Epoch Duration

Epochs apply to Brains as the foundational participation primitive of the protocol.

Epoch length is approximately two (2) months. Epochs repeat continuously, and influence is evaluated at each epoch boundary.

Epoch duration is parameterized and may be adjusted in future EIPs, provided such changes remain consistent with the stewardship principles defined in EIP-0001.

Epoch Lifecycle

Each epoch proceeds through the following phases:

Initialization: Epoch parameters are fixed and the prior epoch state is finalized.

Active Phase: Brains participate in the protocol and proof-of-care signals are accumulated.

Finalization: Care signals are evaluated and influence and reward eligibility are determined.

Transition: Influence renewal or decay is applied and the next epoch begins.

Proof-of-Care Signals

Proof-of-Care is a composite signal composed of multiple verifiable behaviors that may evolve over time.

Examples include sustained participation across consecutive epochs, active engagement with protocol mechanisms, and actions that support network health and alignment.

Asset ownership or capital provision alone does not constitute proof-of-care. Care must be demonstrated through continued participation over time.

Influence and Rewards

Influence is earned, not permanent. Influence renews through continued proof-of-care and decays in the absence of participation. Rewards follow influence, not the reverse.

Epoch boundaries ensure that influence remains renewable and contingent on patience and alignment.

Simplicity and Patience

The Bit Brains protocol intentionally prioritizes simplicity in its initial design. Rather than introducing multiple incentive loops or productivity amplifiers, the system rewards patience through sustained participation across epochs.

Additional mechanisms are intentionally deferred to future EIPs once the core Brain mechanics are validated.

Rationale

Epoch-based evaluation introduces accountability through time. Proof-of-care introduces alignment through action. Simplicity preserves legitimacy and long-term adaptability.

Security Considerations

Potential risks include sybil participation, strategic epoch boundary behavior, and manipulation of care signals. Mitigation strategies will be addressed in future EIPs.

Copyright

Copyright and related rights waived via CC0.
