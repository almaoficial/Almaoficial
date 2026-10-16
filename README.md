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

## Also shipped

- A **WhatsApp ordering agent** running for a real food retailer (151-product live catalog, real prices, zero-invented-price auditing).
- The **ALMA Brakes Kit** — field manual, audit battery and operating templates packaging the governance layer for other builders.
- Article: *"ALMA: aprender cómo los agentes se equivocan menos"* (How agents learn to fail less), LinkedIn, Oct 2026.

## Background

Master's in AI (completed, 6/6 modules). Independent builder full-time since Sep 2025. Available for contract work with full US Eastern overlap.

**Contact:** alesalusso10@gmail.com · [LinkedIn](https://www.linkedin.com/in/alejandro-nahuel-salusso-b8ab3b1b7)
