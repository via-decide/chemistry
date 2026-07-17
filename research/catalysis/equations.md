---
topic: catalysis
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Catalysis — Bounded Equation Records

## CAT-EQ001

Name: Turnover Frequency (TOF)

Symbolic form: \text{TOF} = \frac{1}{N_{\text{active}}} \cdot \frac{dn_{\text{product}}}{dt}

Variables:
- \text{TOF}: Turnover frequency, \text{s}^{-1}
- N_{\text{active}}: Number of active catalytic sites (or moles of active sites), \text{mol}
- \frac{dn_{\text{product}}}{dt}: Rate of product formation, \text{mol} \cdot \text{s}^{-1}

Assumptions: Rate is measured under differential or zero-order regime before significant product inhibition or deactivation occurs.

Limitations: Active site density $N_{\text{active}}$ must be measured independently (e.g., chemisorption, site titration) rather than assumed equal to total catalyst mass.

Applications: Spreads S093, S094; catalyst performance benchmarking and intrinsic activity comparison.

Sources: CAT-003

Verification status: Verified

## CAT-EQ002

Name: Turnover Number (TON)

Symbolic form: \text{TON} = \frac{n_{\text{product}}}{n_{\text{catalyst}}}

Variables:
- \text{TON}: Turnover number, dimensionless
- n_{\text{product}}: Moles of product formed over complete reaction lifetime, \text{mol}
- n_{\text{catalyst}}: Moles of catalyst added (or active sites), \text{mol}

Assumptions: Reaction runs until catalyst deactivates completely or substrate is fully consumed.

Limitations: Does not describe instant reaction velocity; requires specifying total reaction duration or complete deactivation boundary.

Applications: Spreads S093, S094; total catalyst lifetime and stability metric.

Sources: CAT-004

Verification status: Verified

## CAT-EQ003

Name: Fractional Substrate Conversion

Symbolic form: X_A = \frac{n_{A,0} - n_A}{n_{A,0}}

Variables:
- X_A: Fractional conversion of limiting reactant A, dimensionless ($0 \le X_A \le 1$)
- n_{A,0}: Initial moles of reactant A, \text{mol}
- n_A: Moles of unreacted A remaining at time t, \text{mol}

Assumptions: Closed batch or constant molar flow steady-state reactor.

Limitations: Conversion alone does not specify desired product formation when side reactions occur.

Applications: Spreads S094, S095; catalytic reactor design and process balance.

Sources: CAT-001; CAT-002

Verification status: Verified

## CAT-EQ004

Name: Product Selectivity

Symbolic form: S_P = \frac{n_P - n_{P,0}}{\nu_P \cdot (n_{A,0} - n_A)}

Variables:
- S_P: Fractional selectivity to desired product P, dimensionless
- n_P - n_{P,0}: Moles of P formed, \text{mol}
- n_{A,0} - n_A: Moles of limiting reactant A consumed, \text{mol}
- \nu_P: Stoichiometric coefficient ratio of P relative to A

Assumptions: Constant volume or molar flow reactor without secondary unmeasured side losses.

Limitations: Selectivity is often a function of conversion $X_A$; must be reported alongside conversion.

Applications: Spreads S094, S096; reaction pathway evaluation and platform comparison.

Sources: CAT-007

Verification status: Verified

## CAT-EQ005

Name: Catalytic Yield

Symbolic form: Y_P = X_A \cdot S_P

Variables:
- Y_P: Overall yield of desired product P, dimensionless ($0 \le Y_P \le 1$)
- X_A: Fractional conversion of limiting reactant A, dimensionless
- S_P: Product selectivity, dimensionless

Assumptions: Consistent stoichiometric and mass-balance definitions for conversion and selectivity.

Limitations: High yield requires both high conversion and high selectivity; cannot be deduced from conversion alone.

Applications: Spreads S094, S095; process economics and industrial metrics.

Sources: CAT-001; CAT-007

Verification status: Verified

## CAT-EQ006

Name: Langmuir–Hinshelwood Bimolecular Surface Reaction Rate

Symbolic form: r = \frac{k \cdot K_A K_B P_A P_B}{(1 + K_A P_A + K_B P_B)^2}

Variables:
- r: Reaction rate per unit catalyst mass or area, \text{mol} \cdot \text{g}^{-1} \cdot \text{s}^{-1}
- k: Intrinsic surface reaction rate constant, \text{mol} \cdot \text{g}^{-1} \cdot \text{s}^{-1}
- K_A, K_B: Adsorption equilibrium constants for species A and B, \text{bar}^{-1}
- P_A, P_B: Partial pressures of A and B in gas phase, \text{bar}

Assumptions: Surface reaction between co-adsorbed A and B is the rate-determining step; competitive Langmuir adsorption.

Limitations: Neglects surface heterogeneity, lateral interactions, and mass-transfer diffusion resistance across catalyst pores.

Applications: Spreads S094, S095; heterogeneous catalytic rate modeling.

Sources: CAT-002

Verification status: Verified
