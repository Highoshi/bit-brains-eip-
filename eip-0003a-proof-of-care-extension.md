# EIP-0003-a: Proof of Care Expansion & Post-Epoch Three Addendum

## Status
Draft

## Author
Alex Diaz (ONGOD)

## Created
2025-12-25

## Requires
EIP-0003

---

## Abstract

This addendum extends EIP-0003 by introducing post–Epoch Three specifications for Proof of Care expansion, identity continuity via ENS, privacy-preserving attestations, and the staged evolution of Bit Brains, Cerebrals, and Brainiacs.

It defines how the Bit Brains website functions as a coordination, measurement, and reward interface while preserving privacy through zero-knowledge (ZK) and cryptographic attestations.

---

## Motivation

Following the completion of Epoch Three and the first token distribution, the protocol requires:

- A scalable mechanism to measure ongoing Proof of Care
- Persistent identity across epochs and evolutions
- Privacy-preserving participation metrics
- A framework for future mechanical evolution without protocol breakage

This addendum formalizes those requirements.

---

## Specification

### 1. ENS as Canonical Identity Layer

- Ethereum Name Service (ENS) SHALL serve as the primary identifier for:
  - Proof of Care attribution
  - Reward eligibility
  - Evolutionary continuity
- All future rewards, benefits, and permissions are resolved through ENS ownership.
- ENS provides trust minimization, composability, and long-term scalability.

---

### 2. Proof of Care Measurement via Website Interface

- The Bit Brains website functions as a protocol meter, not a custodian.
- It aggregates participation signals including:
  - Continuous uptime
  - Motion-based or device-based attestations
  - Compute or GPU contribution (where applicable)
- Participation data is used for statistical insight and reward calculation.

---

### 3. Privacy via Zero-Knowledge Attestations

- Proof of Care signals SHALL be abstracted using zero-knowledge techniques.
- The system proves participation and consistency without exposing:
  - Raw biometric data
  - Device-level identifiers
  - Behavioral fingerprints
- ZK attestations act as depth signals of protocol engagement.

---

### 4. Evolutionary Roadmap

Post–Epoch Three introduces staged evolution:

- **Brains** → Genesis assets with ENS identity
- **Cerebrals** → Extensions representing delegated or amplified activity
- **Brainiacs** → Advanced entities reflecting long-term participation depth

Evolution is non-destructive and preserves identity continuity.

---

### 5. Treasury-Backed Rewards

- Proof of Care rewards are substantiated by the protocol treasury.
- Reward logic is epoch-based and adjustable.
- Mechanics may evolve, but the principle of verifiable contribution remains invariant.

---

## Rationale

This structure enables:
- Long-lived identity without re-minting
- Privacy-first participation
- Modular evolution of mechanics
- Clear separation between measurement, identity, and reward layers

---

## Backwards Compatibility

This addendum introduces no breaking changes.
It activates only after Epoch Three and builds directly on EIP-0003.

---

## Conclusion

EIP-0003-a establishes the foundation for sustained, private, and identity-centric Proof of Care, ensuring the Bit Brains protocol can evolve while maintaining coherence, trust, and participant alignment.
