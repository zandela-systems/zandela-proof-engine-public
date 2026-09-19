# Public Architecture

ZANDELA Proof Engine is designed as a project-independent proof system.

## Governing flow

```text
candidate state
→ proof contract
→ evidence binding
→ deterministic validation
→ adversarial checks
→ human ratification where required
→ canonical transition
→ publication-safe proof artifact
```

## Architectural separation

The engine is intended to keep separate:
- evidence acquisition;
- claim/state evaluation;
- authority;
- canonical promotion;
- rendering/publication.

The first acceptance adapter is ZANDELA / LIVING SYSTEM, but the engine is designed so adapters can be replaced without redefining the core proof model.

## Public boundary

This document omits private schemas, internal prompts, sensitive evidence, unpublished implementation detail, and credentials.
