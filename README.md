# Chris McNosky

**Technical project delivery · software quality · full-stack web delivery · AI evaluation**

I turn ambiguous problems into testable requirements and delivered software. I
identify needed expertise, direct implementation and separate review, and make
acceptance and release decisions from reproducible evidence. My work spans
open-source software, AI evaluation, and web delivery. I am Founder / Full Stack
Web Developer / AI Evaluation & Governance at NoFuckery AI.

[Portfolio](https://cmcnosky.github.io/) · [Career profile and résumé](https://cmcnosky.github.io/why-hire/) · [LinkedIn](https://www.linkedin.com/in/chris-mcnosky/) · [Email](mailto:cmcnosky@gmail.com)

## Selected work

### [Tokio: conditional `select!` branches](https://github.com/tokio-rs/tokio/pull/8374) · Rust

Delivered a working Rust implementation for Tokio's five-year-old E-hard feature
request. Identified why earlier attempts skewed randomized selection and broke
existing `select!` syntax, then filtered disabled branches from generated storage
and polling. Feature code and tests remained unchanged from the initial submission
through subsequent maintainer questions. Directed a controlled 450-invocation
study across Rust 1.88/1.98 compilers: no unexpected results through 64 branches;
upstream CI passed.

**Status:** The pull request is open and unmerged. **Start here:** [implementation
and tests](https://github.com/tokio-rs/tokio/pull/8374/files) · [original feature
request](https://github.com/tokio-rs/tokio/issues/3974)

### [Grafana: merged ShortURL compatibility fix](https://github.com/grafana/grafana/pull/131070) · Go

Delivered a backend compatibility fix that was approved and merged upstream.
The fix uses the authenticated numeric organization ID for non-Cloud response
links, omits `orgId` in Grafana Cloud, and preserves configured application
subpaths. Table-driven handler regressions cover default, named, conflicting,
and Cloud namespace cases. The merge closed the tracked bug.

**Start here:** [merged pull request and tests](https://github.com/grafana/grafana/pull/131070) ·
[original problem](https://github.com/grafana/grafana/issues/130873) ·
[merge commit](https://github.com/grafana/grafana/commit/6a038175eb0b75a8f25338748af3742c60dbc6d8)

### [Stinger](https://github.com/cmcnosky/stinger) · Python / agent evaluation

An evaluation CLI and reusable GitHub Actions workflow for testing coding-agent
behavior against explicit integrity rules. Seven deterministic detectors check
changes, claims, and traces; reports retain the evidence behind the result.

**Start here:** [offline demo](https://github.com/cmcnosky/stinger/tree/main/demo) ·
[detector implementations](https://github.com/cmcnosky/stinger/tree/main/src/stinger/detectors) ·
[preserved evaluator failure and correction](https://cmcnosky.github.io/nofuckery/evidence/stinger-c04/)

### [Read Shruti](https://readshruti.com) · Next.js / TypeScript / Cloudflare

Co-created and released an author website with three book pages, retailer links,
search metadata, Cloudflare Worker API routes, and D1-backed aggregate page-view
and retailer-click measurement.

**Start here:** [live website](https://readshruti.com)

### [WASP 2.0](https://github.com/cmcnosky/WASP-2.0) · Rust / Python / PostgreSQL

A trading-system project organized around a shared strategy and risk core,
durable order intents, reconciliation, and explicit authorization gates. Python
research uses the Rust core through PyO3. The repository documents the current
implementation and readiness requirements.

**Start here:** [architecture](https://github.com/cmcnosky/WASP-2.0/blob/main/docs/ARCHITECTURE.md) ·
[implementation status](https://github.com/cmcnosky/WASP-2.0/blob/main/docs/IMPLEMENTATION_STATUS.md) ·
[order-safety tests](https://github.com/cmcnosky/WASP-2.0/blob/main/crates/trader-execution/tests/order_safety.rs)

## More to inspect

- [Side Effects Lab](https://github.com/cmcnosky/side-effects-lab): held a change
  out of integration despite 1,336 passing tests after separate adversarial
  review found two ways its acceptance logic could approve behavior that violated
  the specification. The public repository contains the reliability-lab
  foundation; the review record itself is private.
- [High Pie storefront](https://github.com/cmcnosky/high-pie-hemp-website): a
  responsive HTML/CSS/JavaScript catalog preview with shared product data and a
  repository-local verification script.
- [NoFuckery AI](https://cmcnosky.github.io/nofuckery/): technical evidence
  briefs, methods, and correction records.

Open to full-time roles where I can define ambiguous work, direct technical
execution, and own evidence-based quality and release decisions, including
technical project delivery, software quality, AI evaluation, and full-stack web
delivery. Contract work is also available for bounded delivery, evaluation, and
reliability reviews. [Get in touch](mailto:cmcnosky@gmail.com).
