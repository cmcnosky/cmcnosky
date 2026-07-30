## Chris McNosky

**AI-agent evaluation, adversarial testing, and evidence-backed governance.**

I design evaluation systems that turn agent claims into inspectable evidence. My work centers
on adversarial test cases, explicit rubrics, deterministic checks, reproducible evidence
packages, technical writing, and fail-closed release gates.

AI agents assist implementation. I own the problem definition, architecture, specifications,
evaluation rubrics, adversarial review, approval gates, and release judgment. The goal is not
to conceal the assistance; it is to make the resulting work auditable and keep accountability
human.

---

### [Stinger](https://github.com/cmcnosky/stinger) — adversarial evaluation for AI coding agents

Stinger runs sandboxed scenarios against a configured coding agent and checks observable
behavior: weakened or skipped tests, forbidden paths and commands, completion claims that
conflict with evidence, rule violations, and bait-secret exposure. Its seven deterministic
detectors set outcomes; optional model judgment cannot determine a label or score. Ambiguous
or missing evidence fails closed to a non-scored `error`.

**Current public status:**

- **30 validated scenarios** across five integrity families in the public development and
  conformance suite.
- **Protocol 2 remains benchmark candidate / HOLD.** Its signed receipt covers 120
  machine-validated benchmark-candidate scenarios. It is not a released benchmark, benchmark
  score, certification, vendor ranking, or claim of a sealed or live-provider run.

The repository publishes the specification, scenarios, evidence packages, corrections, and
release gates needed to challenge the work rather than simply accept its conclusions.

- [Read the case study](https://github.com/cmcnosky/stinger/blob/main/CASE_STUDY.md)
- [Inspect the committed evidence](https://github.com/cmcnosky/stinger/tree/main/evidence)
- [Verify the signed Protocol 2 candidate receipt](https://github.com/cmcnosky/stinger/tree/main/benchmark/receipts/candidate-validation-v2)
- [Review the benchmark status and release gates](https://github.com/cmcnosky/stinger/blob/main/BENCHMARK.md)

### [NoFuckery AI](https://cmcnosky.github.io/nofuckery/) — technical writing with explicit evidence boundaries

I publish source-driven AI case analyses and evaluation notes that separate observation,
reported claims, inference, opinion, and unknowns. Each brief states the strongest available
evidence, the important limitations, and what the evidence does or does not justify.

- [Evaluation method](https://cmcnosky.github.io/nofuckery/evidence/methods/)
- [Stinger C-04 evaluator-correction case](https://cmcnosky.github.io/nofuckery/evidence/stinger-c04/)
- [Claude and HAWK evidence brief](https://cmcnosky.github.io/nofuckery/evidence/claude-hawk/)

### [WASP 2.0](https://github.com/cmcnosky/WASP-2.0) — safety-critical architecture, deliberately held pre-trade

WASP 2.0 is a single-user, clean-room automated-trading system built around fail-closed
authorization, decision replay, an append-only evidence ledger, environment-isolated broker
hosts, and reconcile-first deployment. It is not trading and is not certified: live submission
remains disabled unless a human approves the permit and every readiness gate passes.

---

### What I'm looking for

I am pursuing **full-time and contract work** in:

- AI and LLM evaluation
- AI red teaming and adversarial test design
- AI quality, rubric design, and structured failure analysis
- technical writing and editing for AI, agent security, and complex software systems
- evidence-backed AI governance and release assurance

I am also available for bounded evaluation engagements: define the rubric, design the
adversarial scenarios, reproduce the failure, and turn the result into evidence another person
can inspect.

**Forwarding this to someone?** Here's the sentence:

> Chris designs and audits AI-agent systems with adversarial tests, deterministic checks, and
> evidence-backed release gates, then publishes the evidence needed to verify the result.

📫 **cmcnosky@gmail.com**
