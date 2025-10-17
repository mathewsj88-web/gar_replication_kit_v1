# Governance Adherence Ratio (GAR) Replication Kit v1.0

Welcome!  
This repository lets independent researchers, analysts, and students **replicate and learn** the core ideas behind the **Governance Adherence Ratio (GAR)** and its companion metric, the **Discipline-Drift Index (DDI)** — created by **Osiris Research LLC**.

---

## 🧠  What GAR and DDI Measure

| Metric | Intuition | Range |
|---------|------------|-------|
| **GAR (Governance Adherence Ratio)** | How faithfully a decision process follows its predefined rules. GAR = 1 means perfect adherence; lower values signal increasing deviation. | 0 – 1 |
| **DDI (Discipline-Drift Index)** | How rapidly discipline decays over time — the “entropy” of governance. Higher DDI = faster drift from rules. | 0 – ∞ (unitless) |

Together, they quantify *discipline behavior* the way volatility quantifies risk.

---

## 🚀  Five-Minute Quickstart (Colab or Local)

1. **Open in Colab**  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mathewsjonathan/gar_replication_kit_v1/blob/main/00_quickstart_runme.ipynb)


2. **Run the Notebook**  
   - The first cell installs dependencies.  
   - The second cell loads sample data and computes headline GAR / DDI values.  
   - The final cell writes a small `verification_result.json` confirming reproducibility.

3. **Check Your Result**  
   You’ll see something like:
   ```
   GAR = 0.72 ± 0.01  
   DDI = 0.15 ± 0.02  
   headline_pass = True
   ```
   These match the canonical expected outputs in `data/expected_headlines.json`.

4. **Submit Your Verification**
   - Upload or email the JSON file per instructions below.  
   - Passing replications receive a **GAR Replicator v1** badge.

---

## 🧩  Repository Structure
```
gar_replication_kit_v1/
├─ data/                     # sample data + expected outputs
├─ notebooks/                # 00_quickstart_runme + tutorial notebooks
├─ src/                      # gar.py, ddi.py, utils.py
├─ tests/                    # pytest unit + integration tests
├─ verification/             # verification script + template
├─ docs/                     # protocol, falsifiers, citation
├─ LICENSE.md                # Osiris Research License (non-commercial)
└─ manifest.json             # file checksums + provenance
```

---

## 📚  Learning Objectives

Running this kit will teach you:
1. **How adherence becomes data** – see rule-following quantified like volatility or beta.  
2. **How drift emerges** – watch DDI rise as discipline weakens.  
3. **How to verify research reproducibility** – understand tolerances and ICC scoring.  
4. **How falsification works** – read `docs/falsifiers.md` to see what would disprove the model.

---

## 🧪  Replication Integrity Targets
| Metric | Target |
|---------|--------|
| GAR Δ Tolerance | ± 0.01 |
| DDI Δ Tolerance | ± 0.02 |
| ICC (Inter-class Correlation) | ≥ 0.90 |
| Median Run Time | ≤ 15 min |

---

## 🏅  How to Earn the GAR Replicator Badge
1. Run the Quickstart and pass verification.  
2. Complete the two reflection questions at the end of the notebook.  
3. Submit your JSON + short answers via the form.  
Successful participants are listed (opt-in) on the **Replication Dashboard**.

---

## 🔒  License & Usage
This repository is released under the **Osiris Research License (Research & Teaching Use Only)**.  
See [LICENSE.md](LICENSE.md).  Not for commercial or investment use.

© Osiris Research LLC  •  Governance-as-a-Service™, Governance Adherence Ratio™, and Discipline-Drift Index™ are trademarks of Osiris Research LLC.

---

## 📖  Citation
If you use this kit, please cite:
> Mathews, J. (2025). *The Governance Adherence Ratio: Quantifying Discipline Behavior.* SSRN Paper No. XXXXXX.  
> Osiris Research LLC, Independent Governance Research Provider.

---

## 📨  Contact / Verification Submissions
- Web form: https://osirisresearch.typeform.com/garreplication  
- Email: replications@osirisresearch.com

*For research and educational purposes only. Not investment advice.*
