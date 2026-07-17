---
topic: toxicology
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Toxicology — Bounded Equation Records

## TOX-EQ001

Name: Sigmoidal Dose-Response Equation (Hill Equation)

Symbolic form: E = E_{\max} \cdot \frac{D^n}{\text{TD}_{50}^n + D^n}

Variables:
- E: Observed toxic response / effect magnitude, % of max
- E_{\max}: Maximum achievable toxic response, %
- D: Administered chemical dose, \text{mg} \cdot \text{kg}^{-1} \text{ body weight}
- \text{TD}_{50}: Toxic dose producing 50% maximal toxic response (or $LD_{50}$ for lethality), \text{mg} \cdot \text{kg}^{-1}
- n: Hill cooperativity slope factor, dimensionless

Assumptions: Reversible toxicant-receptor binding kinetics; homogeneous animal cohort.

Limitations: Invalid for non-monotonic hormetic dose-response curves.

Applications: Spreads S161, S162; toxicological safety threshold determination.

Sources: TOX-001; TOX-002

Verification status: Verified

## TOX-EQ002

Name: Acceptable Daily Intake (ADI) / Reference Dose (RfD)

Symbolic form: \text{ADI} = \frac{\text{NOAEL}}{\text{UF} \cdot \text{MF}}

Variables:
- \text{ADI}: Acceptable Daily Intake (or oral Reference Dose RfD), \text{mg} \cdot \text{kg}^{-1} \text{ bw} \cdot \text{day}^{-1}
- \text{NOAEL}: No-Observed-Adverse-Effect Level from chronic animal study, \text{mg} \cdot \text{kg}^{-1} \cdot \text{day}^{-1}
- \text{UF}: Uncertainty Factor (typically $10 \times 10 = 100$ for inter-species and intra-species variability)
- \text{MF}: Modifying Factor based on study quality ($0.1 - 10$)

Assumptions: Threshold mechanism of toxicity (non-carcinogenic).

Limitations: Non-threshold genotoxic carcinogens require benchmark dose ($BMD_{10}$) and slope factor modeling.

Applications: Spreads S161, S164; chemical safety regulatory limit derivation (FDA/EPA/EFSA).

Sources: TOX-001; TOX-002

Verification status: Verified
