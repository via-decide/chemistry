---
topic: polymer-chemistry
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Polymer Chemistry — Bounded Equation Records

## POL-EQ001

Name: Carothers Equation for Step-Growth Polymerization

Symbolic form: \bar{X}_n = \frac{1}{1 - p} \quad (\text{for stoichiometric 1:1 functional group ratio})

Variables:
- \bar{X}_n: Number-average degree of polymerization (average number of monomer units per polymer chain)
- p: Fractional functional group conversion ($0 \le p < 1.0$)

Assumptions: Step-growth polymerization (e.g., polyester or polyamide); equal reactivity of functional groups; no side reactions.

Limitations: High molecular weight ($ar{X}_n > 100$) requires extremely high conversion ($p > 0.99$).

Applications: Spreads S131, S132; condensation polymer design and stoichiometry control.

Sources: POL-001; POL-002

Verification status: Verified

## POL-EQ002

Name: Number-Average and Weight-Average Molecular Mass

Symbolic form: M_n = \frac{\sum N_i M_i}{\sum N_i}, \quad M_w = \frac{\sum N_i M_i^2}{\sum N_i M_i}, \quad PDI = \frac{M_w}{M_n}

Variables:
- M_n: Number-average molar mass, \text{g} \cdot \text{mol}^{-1}
- M_w: Weight-average molar mass, \text{g} \cdot \text{mol}^{-1}
- N_i: Number of polymer chains containing molar mass $M_i$
- PDI: Dispersity / Polydispersity Index ($PDI \ge 1.0$)

Assumptions: Continuous polymer chain molecular weight distribution.

Limitations: $PDI = 1.0$ represents ideal monodisperse polymer (e.g., natural proteins or living polymerization).

Applications: Spreads S131, S132; polymer characterization and GPC analysis.

Sources: POL-001; POL-002

Verification status: Verified
