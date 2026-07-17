---
topic: green-chemistry
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Green Chemistry — Bounded Equation Records

## GRE-EQ001

Name: Atom Economy (AE)

Symbolic form: \text{AE} = \frac{\text{Molar Mass of Desired Product}}{\sum \text{Molar Mass of All Reactants}} \times 100\%

Variables:
- \text{AE}: Theoretical atom economy percentage ($0 \le \text{AE} \le 100%$)
- \text{Molar Mass of Desired Product}: Stoichiometric molecular weight of target product, \text{g} \cdot \text{mol}^{-1}
- \sum \text{Molar Mass of All Reactants}: Sum of stoichiometric molecular weights of all starting materials, \text{g} \cdot \text{mol}^{-1}

Assumptions: 100% reaction yield and exact stoichiometric reactant input.

Limitations: Ignores reaction yield, solvent mass, catalyst waste, and workup reagents (addressed by E-Factor).

Applications: Spreads S169, S170; synthetic route greenness rating.

Sources: GRE-001; GRE-002

Verification status: Verified

## GRE-EQ002

Name: Environmental Factor (E-Factor)

Symbolic form: \text{E-Factor} = \frac{\text{Total Mass of Waste (kg)}}{\text{Mass of Desired Product (kg)}}

Variables:
- \text{E-Factor}: Mass ratio of waste to target product, kg waste / kg product
- \text{Total Mass of Waste}: Mass of all raw materials, solvents, reagents, and water disposed of as waste, \text{kg}
- \text{Mass of Desired Product}: Mass of isolated, purified target product, \text{kg}

Assumptions: Complete mass balance accounting including solvent loss and workup effluent.

Limitations: Does not weight waste toxicity (addressed by Environmental Impact Factor $Q \times E$).

Applications: Spreads S169, S170; industrial process sustainability evaluation (Sheldon E-factor).

Sources: GRE-001; GRE-002

Verification status: Verified
