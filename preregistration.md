# MIR v1 — Preregistration (Timestamped on first commit)

## Purpose
Pre-register hypotheses and falsifiers for the Governance Adherence Ratio (GAR) and Discipline-Drift Index (DDI).

## Hypotheses
- **H1 (Adherence):** Higher GAR is associated with lower realized drawdowns and volatility.
- **H2 (Persistence):** GAR exhibits positive month-to-month autocorrelation.
- **H3 (Drift):** Higher DDI predicts greater subsequent instability (volatility spikes / larger drawdowns).
- **H4 (Incremental):** DDI adds explanatory power beyond GAR and standard factor controls.

## Falsifiers (“What would prove us wrong?”)
- F1: After controls, GAR’s relationship with drawdowns is statistically insignificant.
- F2: GAR autocorrelation ≈ 0.
- F3: DDI has high correlation (≥0.7) with basic volatility or turnover metrics.
- F4: Independent replication cannot reproduce headline results within pre-set tolerances.

## Data & Processing (summary)
- Synthetic/public-derived sample; processing rules documented in `docs/protocol.md`.

## Analysis Plan
- Regressions with FF5+MOM controls; out-of-sample checks; ICC for replication (target ≥ 0.9).

## Timestamps
- Created: 2025-10-17
- First public commit hash: <TO-FILL>
