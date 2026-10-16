# Alejandro Nahuel Salusso

**AI Agent Builder — agent systems, evals & governance** · Miami Beach, FL (US Eastern) · Bilingual ES/EN

I build agent systems end-to-end in Python, and I specialize in the part most builders skip: **verifying that agents actually did what they claim.** Evals as first-class artifacts, deterministic checks before expensive judgment, adoption gates calibrated to measured noise, and audit trails for everything.

## The work: ALMA

**[github.com/almaoficial/Alma](https://github.com/almaoficial/Alma)** — a self-improving agent system whose changes are adopted only when they measure better, never worse. Public code, pre-registered experiments, and an honest ledger of what works and what doesn't:

- **"Failures that look like successes" verifier** — confronts declared vs. actual outcomes, run by run. First full audit: 35 declared successes, 35 confirmed, 0 false passes.
- **Calibrated cheap evaluator** — 28/30 (0.933) on a 30-case battery at under US$0.001 per run, as the first filter before any expensive judge.
- **Adoption gate with a measured noise floor** (δ = 0.53) — improvements below the system's own noise are never auto-adopted.
- **82 pre-registered experiments** — expected results written before execution, misses published alongside hits.

Start with the 2-minute demo in the repo: `python3 demo/verify_demo.py` — it catches an agent reporting 30/30 tests when the log says 19.

### How those numbers were measured

- **δ = 0.53 (noise floor):** calibrated on 2026-09-30 — block bootstrap (B = 2000, z = 2.0) over repeated validator runs of an *unchanged* system, measuring how much "improvement" pure measurement noise produces. Result: 0.5331 → 0.53.
- **35/35 verifier audit:** run on 2026-10-11 over the window 2026-09-27 → 2026-10-10. Every declared success was confronted against the actual files and logs: 35 declared, 35 confirmed, 0 false passes. It measures report honesty, not system improvement.
- **28/30 cheap evaluator:** one 30-case battery used to *select* among three candidate judges (heuristic 17/30 · free model 0/30 · Mistral Nemo 28/30) — not to train or tune the winner. No independent holdout set yet; a held-out replication is declared future work.
- **Measured meta-loop adoptions so far: 0** — stated in the repo's "Honest state", next to the measurements.

*Name note: this ALMA — in development since July 2025 — is unrelated to the academic framework "ALMA: Automated meta-Learning of Memory designs for Agentic systems" (Xiong, Hu & Clune, arXiv:2602.07755, February 2026). Same acronym, different projects.*

## Also shipped

- A **WhatsApp ordering agent** running for a real food retailer (151-product live catalog, real prices, zero-invented-price auditing).
- The **ALMA Brakes Kit** — field manual, audit battery and operating templates packaging the governance layer for other builders.
- Article: *"ALMA: aprender cómo los agentes se equivocan menos"* (How agents learn to fail less), LinkedIn, Oct 2026.

## Background

Intensive six-module AI study program (completed). Independent builder full-time since Sep 2025. Available for contract work with full US Eastern overlap.

**Contact:** alesalusso10@gmail.com · [LinkedIn](https://www.linkedin.com/in/alejandro-nahuel-salusso-b8ab3b1b7)
