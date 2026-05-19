<h1 align="center">
    <strong>merkle-lib</strong>
    <br>
    <sup><sub>MERKLE TREES AND SPARSE MERKLE TREES</sub></sup>
</h1>

<p align="center">
    <a href="https://crates.io/crates/merkle-lib"><img alt="crates.io" src="https://img.shields.io/crates/v/merkle-lib.svg"></a>
    <a href="https://docs.rs/merkle-lib"><img alt="docs.rs" src="https://docs.rs/merkle-lib/badge.svg"></a>
    <a href="https://github.com/jamesgober/merkle-lib/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/jamesgober/merkle-lib/actions/workflows/ci.yml/badge.svg"></a>
    <a href="#license"><img alt="license" src="https://img.shields.io/badge/license-Apache--2.0%20OR%20MIT-blue.svg"></a>
</p>

<p align="center">Pluggable hash algorithms, proof generation and verification, tree diffing, serializable proofs. Foundation for content-addressed storage, distributed sync, and tamper-evident structures.</p>

---

## Status

**Active development.** Scaffolded and on the path to 1.0. See [.dev/ROADMAP.md](.dev/ROADMAP.md) for milestone tracking.

The public API is not yet stable. Pin specific versions; expect changes pre-1.0.

---

## What it does

Merkle tree and sparse Merkle tree library for data integrity, incremental hashing, and distributed data sync. Pluggable hash algorithms, proof generation and verification, tree diffing, and serializable proofs.

---

## Quick start

```toml
[dependencies]
merkle-lib = "0.1"
```

---

## Standards

- **REPS** governs every decision. See [REPS.md](REPS.md).
- **MSRV:** Rust 1.75.
- **Edition:** 2024.
- **Cross-platform:** Linux, macOS, Windows.

---

## License

Dual-licensed under either of:

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE))
- MIT License ([LICENSE-MIT](LICENSE-MIT))

at your option.

---

<sub>Copyright &copy; 2026 <strong>James Gober</strong>. All rights reserved.</sub>