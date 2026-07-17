---
topic: biochemistry
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Biochemistry — Bounded Equation Records

## BCH-EQ001

Name: Michaelis–Menten Enzyme Kinetic Rate Equation

Symbolic form: v = \frac{V_{\max} \cdot [S]}{K_m + [S]}

Variables:
- v: Initial reaction velocity, \text{mol} \cdot \text{L}^{-1} \cdot \text{s}^{-1} (or \mu\text{mol} / \text{min})
- V_{\max}: Maximum enzymatic rate at substrate saturation ($V_{\max} = k_{\text{cat}} [E]_T$), \text{mol} \cdot \text{L}^{-1} \cdot \text{s}^{-1}
- [S]: Free substrate concentration, \text{mol} \cdot \text{L}^{-1} (\text{M})
- K_m: Michaelis constant (substrate concentration at $v = 0.5 V_{\max}$), \text{mol} \cdot \text{L}^{-1} (\text{M})

Assumptions: Single-substrate steady-state approximation ($d[ES]/dt = 0$); $[S] \gg [E]_T$; reverse product step $P \to S$ is negligible initial in assay.

Limitations: Invalid for multi-substrate ping-pong reactions, allosteric cooperative enzymes (Hill kinetics), or severe enzyme denaturation/inhibition.

Applications: Spreads S124, S125; enzyme activity assays and kinetic characterization.

Sources: BCH-004; BCH-005

Verification status: Verified

## BCH-EQ002

Name: Lineweaver–Burk Double-Reciprocal Linear Transformation

Symbolic form: \frac{1}{v} = \left(\frac{K_m}{V_{\max}}\right) \cdot \frac{1}{[S]} + \frac{1}{V_{\max}}

Variables:
- \frac{1}{v}: Inverse of initial reaction rate, (\text{mol} \cdot \text{L}^{-1} \cdot \text{s}^{-1})^{-1}
- \frac{1}{[S]}: Inverse of substrate concentration, \text{M}^{-1}
- \frac{K_m}{V_{\max}}: Slope of double-reciprocal plot, \text{s}
- \frac{1}{V_{\max}}: Y-intercept of double-reciprocal plot, (\text{mol} \cdot \text{L}^{-1} \cdot \text{s}^{-1})^{-1}
- -\frac{1}{K_m}: X-intercept of double-reciprocal plot, \text{M}^{-1}

Assumptions: Michaelis–Menten mechanism holds.

Limitations: Distorts experimental error at low $[S]$ (high $1/[S]$); non-linear regression on un-transformed data is preferred for parameter estimation.

Applications: Spreads S124, S125; visual diagnosis of enzyme inhibition mechanisms.

Sources: BCH-004; BCH-005

Verification status: Verified

## BCH-EQ003

Name: Catalytic Efficiency (k_cat / K_m)

Symbolic form: \text{Catalytic Efficiency} = \frac{k_{\text{cat}}}{K_m}

Variables:
- k_{\text{cat}}: Turnover number ($k_{\text{cat}} = V_{\max} / [E]_T$), \text{s}^{-1}
- K_m: Michaelis constant, \text{M}
- \frac{k_{\text{cat}}}{K_m}: Second-order rate constant for free enzyme and free substrate interaction, \text{M}^{-1} \cdot \text{s}^{-1}

Assumptions: Substrate concentration $[S] \ll K_m$.

Limitations: Upper theoretical diffusion limit is $10^8 - 10^9 \text{ M}^{-1} \cdot \text{s}^{-1}$ (catalytic perfection).

Applications: Spreads S124, S125; comparative enzyme efficiency evaluation.

Sources: BCH-004; BCH-005

Verification status: Verified

## BCH-EQ004

Name: Competitive Enzyme Inhibition Kinetics

Symbolic form: v = \frac{V_{\max} \cdot [S]}{K_m \left(1 + \frac{[I]}{K_i}\right) + [S]}

Variables:
- v: Initial velocity in presence of competitive inhibitor I, \text{M} \cdot \text{s}^{-1}
- [I]: Inhibitor concentration, \text{M}
- K_i: Inhibitor dissociation constant ($E + I \rightleftharpoons EI$), \text{M}
- K_m^{\text{app}} = K_m \left(1 + \frac{[I]}{K_i}\right): Apparent Michaelis constant, \text{M}

Assumptions: Inhibitor binds exclusively to free enzyme active site $E$; $V_{\max}$ remains unchanged at infinite $[S]$.

Limitations: Does not apply to non-competitive or uncompetitive inhibitors which bind $ES$ complexes.

Applications: Spreads S124, S125; enzyme inhibition assay modeling and drug target kinetics.

Sources: BCH-004; BCH-005

Verification status: Verified

## BCH-EQ005

Name: Thermodynamic Reaction Coupling Free Energy

Symbolic form: \Delta G^{\circ}_{\text{overall}} = \Delta G^{\circ}_1 + \Delta G^{\circ}_2

Variables:
- \Delta G^{\circ}_{\text{overall}}: Net standard Gibbs free energy change of coupled reaction system, \text{kJ} \cdot \text{mol}^{-1}
- \Delta G^{\circ}_1: Standard free energy of exergonic driver reaction (e.g., ATP hydrolysis: $-30.5 \text{ kJ/mol}$), \text{kJ} \cdot \text{mol}^{-1}
- \Delta G^{\circ}_2: Standard free energy of endergonic synthetic reaction ($+ \Delta G^{\circ}$), \text{kJ} \cdot \text{mol}^{-1}

Assumptions: Shared chemical intermediate links driver and target reaction steps.

Limitations: Overall reaction is spontaneous only if $\Delta G^{\circ}_{\text{overall}} < 0$; actual intracellular free energy $\Delta G$ depends on actual species activities.

Applications: Spreads S124, S126; metabolic energy accounting and ATP-driven biosynthesis.

Sources: BCH-001; BCH-002

Verification status: Verified

## BCH-EQ006

Name: Henderson–Hasselbalch Biological Buffer Equation

Symbolic form: \text{pH} = pK_a + \log_{10} \left( \frac{[A^-]}{[HA]} \right)

Variables:
- \text{pH}: Negative logarithm of hydrogen ion activity ($-\log_{10} a_{H^+}$)
- pK_a: Negative logarithm of acid dissociation constant ($-\log_{10} K_a$)
- [A^-]: Molar concentration of conjugate base (e.g., $\text{HPO}_4^{2-}$ or bicarbonate), \text{M}
- [HA]: Molar concentration of weak acid (e.g., $\text{H}_2\text{PO}_4^-$ or carbonic acid), \text{M}

Assumptions: Ionic strength and activity coefficient corrections are constant; buffer capacity is maximal when $\text{pH} = pK_a$.

Limitations: Invalid at extreme pH ($<2$ or $>12$) or very high ionic strength.

Applications: Spreads S124, S125; physiological buffer formulation and enzyme assay pH control.

Sources: BCH-001; BCH-002

Verification status: Verified
