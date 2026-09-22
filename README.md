# Chris McNosky

**Full stack web development · AI evaluation · agent reliability**

I build web applications and evaluation tools, with a focus on clear requirements,
failure analysis, and evidence that another person can inspect. I am Founder / Full
Stack Web Developer / AI Evaluation & Governance at NoFuckery AI.

[Portfolio](https://cmcnosky.github.io/) · [Career profile and résumé](https://cmcnosky.github.io/why-hire/) · [LinkedIn](https://www.linkedin.com/in/chris-mcnosky/) · [Email](mailto:cmcnosky@gmail.com)

## Selected work

### [Stinger](https://github.com/cmcnosky/stinger) · Python / agent evaluation

An evaluation CLI and reusable GitHub Actions workflow for testing coding-agent behavior against
explicit integrity rules. Seven deterministic detectors check changes, claims,
and traces; reports retain the evidence behind the result.

**Start here:** [offline demo](https://github.com/cmcnosky/stinger/tree/main/demo) ·
[detector implementations](https://github.com/cmcnosky/stinger/tree/main/src/stinger/detectors) ·
[preserved evaluator failure and correction](https://cmcnosky.github.io/nofuckery/evidence/stinger-c04/)

### [Tokio: conditional `select!` branches](https://github.com/tokio-rs/tokio/pull/8374) · Rust

A submitted implementation of `#[cfg]` support for `select!` branches. The change
removes disabled branches before generated storage and scheduling. My work covers
the design contract, implementation direction, regression requirements, and evidence
review. The pull request contains the implementation, tests, and upstream checks.

**Start here:** [implementation and tests](https://github.com/tokio-rs/tokio/pull/8374/files) ·
[problem statement](https://github.com/tokio-rs/tokio/issues/3974)

### [Read Shruti](https://readshruti.com) · Next.js / TypeScript / Cloudflare

Co-created and released an author website with three book pages, retailer links,
search metadata, Cloudflare Worker API routes, and D1-backed aggregate page-view
and retailer-click measurement.

**Start here:** [live website](https://readshruti.com)

### [WASP 2.0](https://github.com/cmcnosky/WASP-2.0) · Rust / Python / PostgreSQL

A trading-system project organized around a shared strategy and risk core, durable
order intents, reconciliation, and explicit authorization gates. Python research
uses the Rust core through PyO3. The repository documents the current implementation
and readiness requirements.

**Start here:** [architecture](https://github.com/cmcnosky/WASP-2.0/blob/main/docs/ARCHITECTURE.md) ·
[implementation status](https://github.com/cmcnosky/WASP-2.0/blob/main/docs/IMPLEMENTATION_STATUS.md) ·
[order-safety tests](https://github.com/cmcnosky/WASP-2.0/blob/main/crates/trader-execution/tests/order_safety.rs)

## More to inspect

- [Grafana ShortURL fix](https://github.com/grafana/grafana/pull/131070): a submitted compatibility change using the authenticated organization ID to build response URLs, with regression coverage for local, cloud, and application-subpath cases.
- [Side Effects Lab](https://github.com/cmcnosky/side-effects-lab): a reliability-lab foundation with guarded operation state, authority checks, and event ledgers. The README separates the implemented kernel from the planned simulator and demo.
- [High Pie storefront](https://github.com/cmcnosky/high-pie-hemp-website): a responsive HTML/CSS/JavaScript catalog preview with shared product data and a repository-local verification script.
- [NoFuckery AI](https://cmcnosky.github.io/nofuckery/): technical evidence briefs, methods, and correction records.

Open to full-time roles and scoped projects in full stack web development, AI
evaluation, and agent reliability. [Get in touch](mailto:cmcnosky@gmail.com).
