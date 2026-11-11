<div align="center">

# OSIEL Labs

### Engineering the foundations of connected enterprise software.

**Modular systems · Reliable infrastructure · Thoughtful developer experience**

[Explore our repositories](https://github.com/orgs/OSIEL-Labs/repositories) · [About OSIEL](#what-were-building) · [Collaboration](#collaboration)

</div>

---

## Who we are

**OSIEL Labs** is the engineering organization behind **OSIEL**, an enterprise software initiative focused on building a modular, extensible and self-managed platform.

Our work prioritizes clear architectural boundaries, dependable operations, and software that can evolve with organizations of different sizes. We approach enterprise technology as a connected ecosystem rather than a collection of disconnected applications.

> **Our direction:** Build a solid ERP foundation that can grow into a broader suite of interoperable business applications.

## What we're building

### OSIEL — Enterprise platform

OSIEL is being designed around a modular core and domain-oriented capabilities, with an emphasis on:

- **Modularity:** well-defined domains and extensions without unnecessary operational complexity.
- **Interoperability:** APIs and integration points for native and external applications.
- **Data integrity:** trustworthy transactional processing, auditability and deliberate historical-data strategies.
- **Operational flexibility:** deployment patterns suited to different business scales.
- **Resilient experiences:** support for connected and selected offline-first workflows.
- **Maintainability:** traceable engineering decisions, testing and documentation.

OSIEL is **under active design and research**. This page describes engineering direction, not a claim that the full platform or its capabilities have been released.

## Technology direction

| Area | Direction |
| --- | --- |
| Core services | Go-first, with Rust where it adds clear value |
| Architecture | Modular monolith with internal hexagonal boundaries |
| Operational database | PostgreSQL |
| Messaging | NATS JetStream for applicable asynchronous workloads |
| Cache / key-value | Valkey-compatible approach under workload-specific evaluation |
| Interfaces | Lightweight, reusable UI components and external APIs |
| Desktop and offline | Rust/Tauri-based applications with local SQLite where appropriate |
| Historical data | Exploring PostgreSQL hot storage and Parquet-based cold archives |

Technology decisions may evolve as research and validation progress.

## Engineering principles

**Evidence before assumptions.** We document why systems behave as they do and distinguish verified implementation from intended design.

**Simplicity where possible.** We prefer cohesive, modular components over complexity without a measurable benefit.

**Security and integrity by design.** Authentication, authorization, tenancy boundaries, transactional guarantees and operational controls are foundational requirements.

**Open interfaces.** The platform is intended to support integration and extensibility without forcing every user experience into one frontend.

## Repositories and availability

Projects will appear in the [OSIEL Labs repository directory](https://github.com/orgs/OSIEL-Labs/repositories) as they are ready to be published. Research, internal prototypes and unreleased components may remain private.

Please treat each repository's README, license and contribution guidelines as authoritative for that specific project. **A public repository does not automatically imply an open-source license or production readiness.**

## Collaboration

We value focused technical discussions, reproducible bug reports and constructive architectural feedback.

When a project is open for external contributions, its repository will explain how to raise an issue, propose a change or report a security concern. For sensitive reports, follow the repository-specific security policy rather than opening a public issue.

## Status

**Research and development.** Public documentation will be expanded as components and governance policies are validated.

---

<div align="center">

**OSIEL Labs** · Building dependable foundations for enterprise software.

</div>
