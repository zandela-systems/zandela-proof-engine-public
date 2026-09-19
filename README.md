# ZANDELA Proof Engine

**Governed proof infrastructure for claims, state transitions, evidence, and publication readiness.**

ZANDELA Proof Engine (ZPE) is being built as a standalone, project-independent proof system. Its purpose is to make consequential claims and state changes inspectable before they become canonical or public.

The core idea is simple:

> **A system should be able to explain why a claim was accepted, why another was rejected, what evidence supported the decision, and who had authority to promote the result.**

## What ZPE is

ZPE is designed to evaluate candidate changes against explicit proof contracts.

A typical flow is:

```text
candidate claim
→ evidence binding
→ deterministic validation
→ adversarial checks
→ human ratification when required
→ canonical state transition
→ publication-safe proof artifact
```

The engine is intentionally separated from any one project. ZANDELA / LIVING SYSTEM is the first acceptance environment, not the definition of the engine.

## First acceptance scenario

The initial end-to-end demonstration is designed to prove two opposite outcomes:

1. an unsupported AI-proposed maturity claim is rejected;
2. canonical state remains unchanged;
3. a supported, human-ratified change passes;
4. canonical state advances;
5. the public renderer updates;
6. a proof capsule / demonstration package is produced.

That scenario is useful because the result is falsifiable: the engine either preserves the authority boundary or it does not.

## Current build direction

The program is structured around:

- proof contracts;
- typed evidence;
- claim/state validation;
- provenance;
- deterministic validators;
- execution receipts;
- adversarial review;
- human ratification;
- publication gating;
- proof capsules.

## Governing rules

- Evidence before assertion
- Observation ≠ inference ≠ conclusion
- Concept ≠ prototype ≠ production
- Candidate ≠ canonical
- Models may propose; they do not inherit promotion authority
- Rejected and superseded states remain part of the record
- Proof artifacts must be inspectable by both humans and machines

## Public boundary

This repository is a **sanitized public showcase**.

It intentionally excludes:
- credentials and secrets;
- private canonical state;
- sensitive evidence;
- internal prompts and raw agent traces;
- proprietary implementation details not intended for publication.

The private canonical repository remains the engineering source of truth.

## Related system

ZPE is being designed to integrate first with **ZANDELA / LIVING SYSTEM** while remaining reusable across other governed systems.

- [ZANDELA / LIVING SYSTEM public showcase](https://github.com/zandela-systems/zandela-living-system-public)
- [zandela.systems](https://zandela.systems)

## Status

Active build. Public material here represents only what has passed the publication boundary.

---

**Proof before promotion. Evidence before publication.**
