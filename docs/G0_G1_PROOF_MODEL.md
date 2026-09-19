# G0/G1 Proof Model — ZANDELA Proof Engine

ZPE begins with a project-agnostic proof boundary.

## G0 constitutional focus

The local G0 validation report records PASS checks for:

- required fields;
- system and gate identity;
- project-agnostic core;
- constitutional invariants;
- prohibitions;
- separation contract;
- fail-closed behavior;
- human publication gate;
- project sovereignty.

This means the initial engine contract is structured to preserve the authority of source projects rather than silently absorb it.

## G1 adapter focus

The first integration target is ZANDELA / LIVING SYSTEM as a read-only fixture.

The adapter contract is designed so the proof engine can inspect a source project's evidence and authority references without acquiring authority to rewrite that source.

## Design principle

```text
source project sovereignty
→ read-only interchange
→ proof evaluation
→ explicit result
→ no implicit source mutation
```

The engine should remain reusable across projects rather than baking one project's ontology or gate structure into the core.
