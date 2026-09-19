# Demo Walkthrough — Read-Only Project Adapter

## Goal

Show that ZPE can inspect a governed source project without silently strengthening authority or mutating the source.

## Input

A frozen ZANDELA / LIVING SYSTEM Gate 5 fixture containing claims, authority references, warnings, and source commit identity.

## Expected behavior

ZPE must:

1. validate the interchange schema;
2. preserve the source commit identity;
3. preserve the source validation status;
4. preserve warnings;
5. resolve claim/evidence references;
6. resolve authority references;
7. reject missing claim evidence;
8. reject missing authority evidence;
9. perform no source mutation.

## Recorded result

The G1 read-only conformance report records all checks as PASS and:

`source_mutation_performed: false`

This is a narrow but important proof: integration does not imply inherited authority.
