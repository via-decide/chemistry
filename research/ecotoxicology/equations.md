---
topic: ecotoxicology
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Ecotoxicology — Bounded Equation Records

## ECO-EQ001

Name: Bioconcentration Factor (BCF)

Symbolic form: BCF = \frac{C_{\text{organism}}}{C_{\text{water}}} = \frac{k_1}{k_2}

Variables:
- BCF: Bioconcentration factor at steady state, \text{L} \cdot \text{kg}^{-1}
- C_{\text{organism}}: Concentration of chemical in organism tissue, \text{mg} \cdot \text{kg}^{-1}
- C_{\text{water}}: Concentration of chemical in surrounding water, \text{mg} \cdot \text{L}^{-1}
- k_1: Uptake rate constant from water, \text{L} \cdot \text{kg}^{-1} \cdot \text{day}^{-1}
- k_2: Depuration / elimination rate constant, \text{day}^{-1}

Assumptions: Steady-state exposure in aquatic bioassay (OECD 305).

Limitations: Applies to waterborne exposure; dietary exposure requires Biomagnification Factor (BMF).

Applications: Spreads S165, S166; environmental hazard assessment and PBT classification.

Sources: ECO-001; ECO-002

Verification status: Verified

## ECO-EQ002

Name: Hazard Quotient (HQ) and Risk Characterization Ratio (RCR)

Symbolic form: \text{HQ} = \frac{\text{PEC}}{\text{PNEC}}

Variables:
- \text{HQ}: Hazard Quotient, dimensionless
- \text{PEC}: Predicted Environmental Concentration in compartment (water, soil, sediment), \text{mg} \cdot \text{L}^{-1}
- \text{PNEC}: Predicted No-Effect Concentration ($PNEC = L(E)C_{50} / AF$), \text{mg} \cdot \text{L}^{-1}
- AF: Assessment / safety factor (10 to 1000 depending on toxicity dataset completeness)

Assumptions: Linear exposure-response risk scaling.

Limitations: $	ext{HQ} > 1.0$ indicates potential ecological risk requiring refined higher-tier risk assessment.

Applications: Spreads S165, S168; regulatory environmental risk assessment (REACH / EPA).

Sources: ECO-001; ECO-002

Verification status: Verified
