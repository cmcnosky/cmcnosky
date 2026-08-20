# Chris McNosky

**Target roles:** AI evaluation · agent reliability · AI quality operations · technical program management

I turn ambiguous AI-system requirements into testable acceptance criteria, adversarial evaluations, reproducible evidence, and clear release decisions. I direct AI-assisted technical work and own the scope, architecture, review gates, and final judgment.

## What I bring to a team

- Turn unclear goals into written requirements, failure modes, and decision-ready test plans.

- Design adversarial evaluations that expose false passes, unsupported completion claims, and missing constraints.

- Convert findings into correction, regression, and release gates that engineering and operating teams can use.

## Selected proof

### 1. [Tokio select! cfg-gated branches](https://github.com/tokio-rs/tokio/pull/8374) — took a difficult issue to a non-draft upstream PR

I scoped and directed the AI-assisted Rust contribution for Tokio issue #3974 after two earlier contributor attempts closed. I derived the design contract from why those attempts failed, set the regression gates, and made the submission decision. Full upstream CI is green; the PR awaits maintainer review.

### 2. Side Effects Lab — held a change out of integration despite 1,336 passing tests

In my evaluation lab, a second, separately prompted adversarial review found two paths where acceptance logic could approve spec-violating behavior. I required correction and retest before integration. [View public project context](https://github.com/cmcnosky/side-effects-lab); the review record itself is private.

### 3. [Stinger](https://github.com/cmcnosky/stinger) — built an inspectable agent-integrity evaluator

Stinger is a model-agnostic CLI and GitHub Action with 30 public development and conformance scenarios and seven deterministic detectors. When a real run exposed a classification defect, I preserved the wrong evidence, directed the fix, and required refusal and non-refusal regression coverage.

## Hiring fit

I am pursuing full-time roles in AI evaluation and agent reliability, including quality-operations and technical-program versions of that work. Contract work is also available for bounded evaluation and reliability reviews.

[Portfolio](https://cmcnosky.github.io/why-hire/) · [NoFuckery AI evidence briefs](https://cmcnosky.github.io/nofuckery/) · [cmcnosky@gmail.com](mailto:cmcnosky@gmail.com)
