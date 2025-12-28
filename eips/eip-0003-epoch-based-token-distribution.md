---EIP-0003: finalize token supply and distribution standard

Author: Bit Brains Protocol
Developer: On God
- Define fixed 200M max supply with no inflation
- Introduce hard-capped 3-phase emissions (60M total)
- Specify canonical allocations for treasury, team, ecosystem growth,
  and NFT staking / Proof of Care rewards
- Add optional extensions for exit penalties, NFT royalties, and ENS-based routing
discussions-to: TBD
status: Draft
type: Standards Track
category: Economic
created: 2025-12-28
---

## Abstract

EIP-0003 defines the fixed token supply, allocation, and phased emission schedule for the Bit Brains Protocol. This specification establishes a hard-capped supply, a three-phase emissions program that terminates permanently after Phase 3, and explicit allocations for protocol treasury, team, ecosystem growth, and NFT staking / Proof of Care continuity rewards.

## Motivation

Token launches frequently suffer from unclear allocation, inflationary drift, and premature liquidity extraction. EIP-0003 addresses these failures by enforcing a fixed maximum supply, capped emissions with no extensions, and treasury-held incentive pools aligned with long-term participation and protocol continuity.

## Specification

### Total Supply

- **Maximum supply:** **200,000,000 tokens**
- **Inflation:** None
- **Additional emissions:** Not permitted beyond Phase 3

### Phase Emissions (Hard-Capped)

Emissions occur across three complete phases with no mid-phase unlocks and no emissions after Phase 3.

- **Phase 1:** 20,000,000 tokens
- **Phase 2:** 20,000,000 tokens
- **Phase 3:** 20,000,000 tokens

**Total phase emissions:** **60,000,000 tokens (30%)**

There is no Phase 4 and no discretionary minting authority.

### Allocation (Fully Accounted)

All tokens are allocated at genesis and accounted for within the fixed supply.

| Category | Tokens | % of Supply |
|---|---:|---:|
| Phase Emissions (3 phases) | 60,000,000 | 30% |
| Treasury Reserve | 40,000,000 | 20% |
| Team Allocation | 30,000,000 | 15% |
| NFT Staking / Proof of Care Rewards (Treasury-held) | 40,000,000 | 20% |
| Ecosystem Growth Treasury | 30,000,000 | 15% |
| **TOTAL SUPPLY** | **200,000,000** | **100%** |

### Allocation Notes

**Treasury Reserve (20%)**  
Held to support protocol solvency, stabilization mechanisms, governance-approved initiatives, and optional buyback or burn programs if adopted by governance.

**Team Allocation (15%)**  
Reserved for contributors and operators. Vesting or lock schedules, if applicable, MUST be defined by subsequent standards or governance resolutions.

**NFT Staking / Proof of Care Rewards (20%, Treasury-held)**  
A dedicated pool reserved for NFT staking rewards and Proof of Care continuity incentives. Distribution is eligibility-based and governed by protocol-defined reward mechanisms.

**Ecosystem Growth Treasury (15%)**  
Reserved for ecosystem expansion, including developer grants, partnerships, infrastructure, and adoption incentives.

## Optional Extensions (Non-Normative)

The following mechanisms MAY be adopted via subsequent standards or governance but are not required by this EIP:

### Progressive Downstream Exit Penalty
A phased penalty MAY apply to early exits or withdrawals:
- Phase 1: 30%
- Phase 2: 20%
- Phase 3: 10%

Penalties route to the Treasury Reserve.

### NFT Secondary Royalties
A baseline secondary royalty MAY be applied:
- 3% total (1% Founder, 1% Artist, 1% Treasury)

### ENS-Based Reward Routing
Reward eligibility and routing MAY require ENS resolution as the canonical identity layer, with optional zero-knowledge proofs for eligibility verification.

## Security and Economic Considerations

- Fixed supply prevents inflationary dilution.
- Hard-capped emissions reduce liquidity shock risk.
- Treasury-held incentive pools prevent uncontrolled distribution.
- Explicit accounting improves auditability and governance clarity.

## Copyright

Copyright and related rights waived via CC0.
