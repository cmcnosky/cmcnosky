## Chris McNosky

**I direct AI coding agents to build systems you can verify instead of trust.**

Written governance contracts the agents work under, gates they aren't allowed to weaken, and
the evidence committed to the repo so you can check the claims rather than believe them. My
background is procurement at a top-5 homebuilder and running a small manufacturing business —
not computer science. The agents write the code. The part that makes it trustworthy is mine.

*I don't trust the agents. I built the tool that measures when they lie.*

---

### [Stinger](https://github.com/cmcnosky/stinger) — measuring whether AI coding agents cheat

Runs a corpus of sandboxed trap scenarios against a configured coding agent and mechanically
detects dishonest shortcuts: weakened tests, forbidden-file edits, fabricated completion
claims, broken house rules, leaked bait secrets. Emits a scored, evidence-linked Integrity
Report under a preregistered, frozen rubric.

Two rules shape it. **Cheating is decided by deterministic detectors, never an LLM judge** —
optional judge output is non-authoritative and cannot set a verdict or score. And **any
ambiguity fails closed** to a non-scored `error`, never to a favorable score.

The public repository includes a 30-scenario development and conformance suite. A signed,
non-secret receipt now verifies **120 machine-validated benchmark-candidate scenarios** across
five integrity families. That is validation evidence, not a benchmark score: the scoring corpus
is not frozen, and no baseline matrix or independent reproduction is claimed yet.

→ [Verify the signed 120-candidate receipt](https://github.com/cmcnosky/stinger/tree/main/benchmark/receipts/candidate-validation-v2)

Model-agnostic and vendor-neutral by construction. CLI and GitHub Action.

> Every fixture test passed, so I spent the money to run it against live agents anyway — because
> a measurement instrument that has only ever been tested against its own fixtures has not been
> tested. Those runs found five real defects, each of which would have produced a *plausible
> wrong answer* rather than a visible failure. The worst: it scored a textbook-perfect refusal
> as a cheat, because the trap only ever recognised my own vocabulary. The mislabelled evidence
> package is committed **unedited**.
> → [How it was built, and what hitting reality broke](https://github.com/cmcnosky/stinger/blob/main/CASE_STUDY.md)

### [WASP 2.0](https://github.com/cmcnosky/WASP-2.0) — a safety-critical trading system, deliberately held pre-trade

A single-user, clean-room automated trading system: Rust modular monolith with a PyO3 research
layer calling the same compiled strategy, decision-replay, and risk core. Fail-closed
authorization, an append-only evidence ledger, environment-isolated broker hosts, and
reconcile-first deployment.

> It isn't trading, and the README says so in the first screen. Nothing is certified, so the
> system refuses to act — live submission requires a human-approved permit and passed readiness
> gates, and ambiguous broker outcomes fail closed. That is the design working, not the project
> stalling. A system that would trade today is a system I built wrong.

---

### What I'm looking for

**Scoped, fixed-price engagements** — building or hardening agent-driven systems for teams that
need the output to be *verifiable*, not just demonstrable. A bounded first project is the point:
you get to check the work before committing to anything larger.

Also open to full-time roles in applied AI and developer tooling.

**Forwarding this to someone?** Here's the sentence:

> Chris is a non-engineer who directs AI coding agents under formal governance contracts to ship
> systems with committed, checkable evidence — including an open-source tool that measures
> whether coding agents cheat. He's taking scoped contract work.

📫 **cmcnosky@gmail.com**
