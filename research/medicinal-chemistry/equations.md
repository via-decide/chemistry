---
topic: medicinal-chemistry
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Medicinal Chemistry — Bounded Equation Records

## MED-EQ001

Name: Cheng–Prusoff Equation for Inhibitor Affinity (K_i)

Symbolic form: K_i = \frac{IC_{50}}{1 + \frac{[S]}{K_m}}

Variables:
- K_i: True thermodynamic equilibrium dissociation constant of competitive inhibitor, \text{M}
- IC_{50}: Concentration of inhibitor causing 50% inhibition of enzyme activity, \text{M}
- [S]: Substrate concentration in bioassay, \text{M}
- K_m: Michaelis constant of substrate for enzyme, \text{M}

Assumptions: Competitive inhibition mechanism; Michaelis–Menten single-substrate kinetics.

Limitations: Invalid for non-competitive, uncompetitive, or tight-binding ($IC_{50} \approx 0.5 [E]_T$) inhibitors.

Applications: Spreads S128, S129; potency benchmarking and SAR comparison.

Sources: MED-001; MED-005

Verification status: Verified

## MED-EQ002

Name: Ligand Efficiency (LE)

Symbolic form: LE = \frac{1.37 \cdot pIC_{50}}{N_{\text{heavy}}} = \frac{-\Delta G^{\circ}}{N_{\text{heavy}}}

Variables:
- LE: Ligand efficiency per non-hydrogen atom, \text{kcal} \cdot \text{mol}^{-1} \cdot \text{heavy atom}^{-1}
- pIC_{50}: Negative logarithm of $IC_{50}$ ($\text{pIC}_{50} = -\log_{10} IC_{50}$ in Molar)
- N_{\text{heavy}}: Number of non-hydrogen (heavy) atoms in compound
- \Delta G^{\circ}: Binding free energy, \text{kcal} \cdot \text{mol}^{-1}

Assumptions: Standard temperature ($298 \text{ K}$); linear scaling of binding energy with heavy atom count.

Limitations: Benchmark target threshold is $LE \ge 0.3$; tends to penalize large natural products or rigid peptidomimetics.

Applications: Spreads S127, S128; hit-to-lead and fragment optimization.

Sources: MED-005

Verification status: Verified

## MED-EQ003

Name: Lipophilic Efficiency / Ligand Lipophilicity Efficiency (LLE / LipE)

Symbolic form: \text{LLE} = pIC_{50} - \log P

Variables:
- \text{LLE}: Lipophilic efficiency index, dimensionless
- pIC_{50}: Potency metric ($-\log_{10} IC_{50}$ or $pK_i$)
- \log P: Calculated or measured octanol-water partition coefficient of neutral compound

Assumptions: Target potency should be gained through specific directional interactions rather than non-specific hydrophobic grease.

Limitations: Target threshold is $\text{LLE} \ge 5.0 - 6.0$; for ionizable drugs at pH 7.4, $\log D_{7.4}$ is substituted ($	ext{LipE}_{7.4} = pIC_{50} - \log D_{7.4}$).

Applications: Spreads S128, S129; lead optimization property profiling.

Sources: MED-001; MED-005

Verification status: Verified

## MED-EQ004

Name: pH-Dependent Distribution Coefficient (Log D_7.4)

Symbolic form: \log D_{7.4} = \log P - \log_{10} \left(1 + 10^{\text{pH} - pK_a}\right) \quad (\text{for monoprotic acid})

Variables:
- \log D_{7.4}: Distribution coefficient of all neutral and ionized species between octanol and pH 7.4 aqueous buffer
- \log P: Partition coefficient of neutral form
- \text{pH}: Physiological pH ($7.4$)
- pK_a: Acid dissociation constant of drug compound

Assumptions: Monoprotic ionizable functional group ($HA \rightleftharpoons A^- + H^+$); octanol phase extracts only neutral species.

Limitations: Requires extended formula for amphoteric / zwitterionic molecules.

Applications: Spreads S128, S129; membrane permeability and ADME property prediction.

Sources: MED-001; MED-004

Verification status: Verified

## MED-EQ005

Name: Off-Target Safety Selectivity Ratio

Symbolic form: \text{Selectivity Ratio} = \frac{IC_{50,\text{off-target}}}{IC_{50,\text{on-target}}}

Variables:
- \text{Selectivity Ratio}: Margin ratio of off-target to on-target inhibition, scalar
- IC_{50,\text{off-target}}: Inhibitory concentration for safety target (e.g., hERG ion channel, CYP3A4), \text{M}
- IC_{50,\text{on-target}}: Inhibitory concentration for primary therapeutic target, \text{M}

Assumptions: Assays performed under consistent binding and substrate saturation regimes.

Limitations: Minimum safe hERG margin is typically $> 30-100 \times$ relative to free plasma $C_{\max}$.

Applications: Spreads S128, S129; candidate selection safety gate.

Sources: MED-004; MED-006

Verification status: Verified

## MED-EQ006

Name: Total Oral Bioavailability Fraction (F)

Symbolic form: F = f_a \cdot F_g \cdot F_h

Variables:
- F: Fractional oral bioavailability reaching systemic circulation ($0 \le F \le 1$)
- f_a: Fraction absorbed across intestinal lumen epithelial membrane
- F_g: Fraction escaping first-pass gut wall metabolic degradation
- F_h: Fraction escaping first-pass hepatic metabolism ($F_h = 1 - E_h$)

Assumptions: Oral solid or liquid dose administration under steady physiological liver blood flow.

Limitations: Ignores non-linear active transport saturation or formulation precipitation in GI tract.

Applications: Spreads S128, S130; preclinical PK profiling and candidate selection.

Sources: MED-001; MED-006

Verification status: Verified
