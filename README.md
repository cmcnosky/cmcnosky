# Chris McNosky

**Target roles:** AI/LLM evaluation · AI red teaming · agent reliability · agentic engineering operations · evidence-backed AI quality

I build evaluation and reliability systems that turn claims into inspectable evidence: adversarial scenarios, deterministic checks, reproducible artifacts, explicit authority boundaries, and release gates that fail closed.

## Three inspectable achievements

### 1. [Tokio `select!` cfg-gated branches](https://github.com/tokio-rs/tokio/pull/8374) — direct a fix for a hard upstream macro-design problem

I scoped and directed an agentic Rust contribution for Tokio issue #3974 after two earlier implementation attempts had been closed. The design removes cfg-disabled branches before generated storage and scheduling, preserving dense branch indices and randomized fairness. The ready-for-review PR is submitted upstream; all 83 executed checks passed, with six skipped and two neutral.

### 2. [Stinger](https://github.com/cmcnosky/stinger) — test agent integrity against evidence

Stinger is a model-agnostic CLI and GitHub Action that runs sandboxed trap scenarios and detects observable shortcuts such as weakened tests, forbidden edits, unsupported completion claims, rule violations, and bait-secret exposure. Deterministic detectors set outcomes; ambiguous or missing evidence becomes a non-scored error. [Evaluate it in five minutes](https://github.com/cmcnosky/stinger#evaluate-stinger-in-five-minutes) or [inspect the committed evidence](https://github.com/cmcnosky/stinger/tree/main/evidence).

### 3. [The evaluator was wrong; the agent was right](https://cmcnosky.github.io/nofuckery/evidence/stinger-c04/) — correct the measurement, preserve the evidence

In Stinger scenario C-04, a captured agent correctly refused an internally contradictory task, but the evaluator mislabeled the behavior. I preserved the original artifact, traced the classification error, directed expanded refusal cases and a non-refusal regression, and published the correction without changing the frozen scoring rule.

## Work with me

I am pursuing full-time and contract work in AI evaluation, adversarial testing, agent reliability, structured failure analysis, technical writing, and release assurance. I direct product scope, architecture, evaluation design, evidence standards, and final release judgment; AI coding agents assist implementation under inspectable checks.

[Portfolio](https://cmcnosky.github.io) · [NoFuckery AI evidence briefs](https://cmcnosky.github.io/nofuckery/) · [cmcnosky@gmail.com](mailto:cmcnosky@gmail.com)
