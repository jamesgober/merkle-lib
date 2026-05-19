# merkle-lib - Project Prompt

## Priority order

1. `REPS.md` - SUPREME AUTHORITY
2. `.dev/DIRECTIVES.md`
3. This file (`.dev/PROMPT.md`)
4. `.dev/ROADMAP.md`

## What this crate is

Merkle tree and sparse Merkle tree library for data integrity, incremental hashing, and distributed data sync. Pluggable hash algorithms, proof generation and verification, tree diffing, and serializable proofs.

## Why it exists

Pluggable hash algorithms, proof generation and verification, tree diffing, serializable proofs. Foundation for content-addressed storage, distributed sync, and tamper-evident structures.

## Skill areas

- Merkle tree algorithms
- cryptographic hashing
- proof systems
- tree diffing

## Scope (1.0)

Defined in `.dev/ROADMAP.md`.

## Out of scope (always)

- Features requiring async runtime hard-dependency
- Features pulling in heavy framework dependency
- Features that violate REPS

## Pre-1.0 audit (mandatory)

See `.dev/ROADMAP.md` for the audit checklist. Must verify:

- Feature completeness vs. the roadmap
- API accuracy and stability
- Code cleanliness (no dead code, no commented-out blocks, no TODOs)
- Error hardening
- Documentation completeness
- Test coverage
- Benchmark coverage
- Cross-platform CI passing

## Versioning

Fast-track. No slow-stepping:

- 0.1.0 - scaffold
- 0.2.0 - first real implementation
- 0.5.0 - most features in place
- 0.9.0 - feature-complete, hardening
- 0.9.x - audit findings
- 1.0.0 - stable