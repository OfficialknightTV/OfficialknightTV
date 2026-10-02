# Merveille Okouya

**Independent AI systems researcher & builder · MBANI Labs / MBANI Systems**

I design and test practical AI, automation, and data systems with an emphasis on **agent reliability, evidence grounding, provenance, contradiction handling, reproducibility, security, and operational systems engineering**.

> **MBANI Labs discovers. MBANI Systems delivers.**

## Current work

### [MBANI Agent Reliability Benchmark](https://github.com/OfficialknightTV/mbani-agent-reliability-benchmark)

**Public research protocol v0.1 — Evaluating Agent Reliability Under Conflicting and Incomplete Evidence.**

The repository is now more than a written protocol. Its current `main` branch includes:

- machine-enforced case, model-output, and run contracts
- gold-isolation and referential-integrity checks
- a strict deterministic canonical matcher
- a deterministic D0 baseline
- an executable scorer
- adversarial unit tests and repository-integrity CI
- an exploratory ceiling-test track kept separate from formal benchmark evidence

The benchmark remains **pre-experiment**: formal model runs, independent annotation, frozen held-out evaluation, and validated benchmark results have not yet been completed.

### MBANI NEXUS

**Private MBANI engineering system — intelligence to execution.**

NEXUS connects the MBANI workflow from observed signals through Labs research and evidence, experiments and validation, decision, and Systems delivery.

```text
SIGNALS
  ↓
MBANI LABS
  ↓
RESEARCH → EVIDENCE → HYPOTHESES → EXPERIMENTS → VALIDATION
  ↓
DECISION
  ↓
MBANI SYSTEMS
  ↓
SCOPE → DESIGN → BUILD → OPERATE
  ↓
MEASURE → NEW SIGNALS
```

The current NEXUS release candidate is being hardened across **Vercel, Netlify, and Cloudflare**. Its latest release-candidate commit passes repository hygiene plus Vercel, Netlify, and Cloudflare CI, including Cloudflare TypeScript validation and a local Cloudflare production build.

That release candidate is still an **open pull request** and has not yet been represented as merged `main` state.

NEXUS is also used for adaptive builder-ceiling testing. Those ceiling tests are exploratory engineering records, not formal benchmark results.

## Other public work

### [Merveille OS](https://github.com/OfficialknightTV/merveille-os)

Local-first React + Tauri/Rust desktop prototype for priorities, next-action logic, completed-work history, evidence notes, and SQLite-backed state.

### [Python Practice Vault](https://github.com/OfficialknightTV/python-practice-vault)

Python automation prototype for discovering, organizing, classifying, and maintaining local learning repositories and environments.

## MBANI operating model

**MBANI Labs** handles research, experimentation, prototypes, uncertainty, and capability discovery.

**MBANI Systems** handles scoped, validated implementation and operational delivery.

The distinction is deliberate: exploratory work is not represented as validated production capability until the evidence supports that transition.

## Working principles

- Separate **source, claim, evidence, and inference**.
- Preserve unresolved contradictions instead of forcing false certainty.
- Keep exploratory ceiling tests separate from formal evaluation.
- Distinguish implemented, tested, deployed, and validated states.
- Prefer reproducible contracts, tests, logs, and audit trails.
- Treat credentials, private evidence, and production data as security boundaries.
- Report limitations and failures alongside successful results.

## Current direction

I am developing MBANI as a practical research-and-delivery system: use experiments to discover what works, preserve evidence about what failed, then convert validated findings into repeatable systems.
