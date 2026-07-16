---
topic: solubility
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 0
secondary_sources: 5
updated_by: codex
---

# Solubility — Equations

## Equation SOL-EQ001: Standard reaction equilibrium constant

Equation: `K^\circ = \prod_i a_i^{\nu_i}`

Variables: `K^\circ`, dimensionless standard equilibrium constant for the declared reaction; `a_i`, dimensionless activity of species `i`; `\nu_i`, signed stoichiometric number, positive for products and negative for reactants.

Units: `K^\circ`, `a_i`, and `\nu_i` are dimensionless.

Assumptions: One balanced reaction, declared standard states, equilibrium, and a consistent activity convention.

Limitations: Concentration-only substitutions require a justified activity-coefficient approximation. Coupled reactions require a mass-balance and speciation system rather than one isolated expression.

Applications: Constructing dissolution and coupled-equilibrium models.

Source: SOL-005; SOL-006

Verification: Verified

## Equation SOL-EQ002: Concentration-scale activity relation

Equation: `a_i = \gamma_{c,i}\frac{c_i}{c^\circ}`

Variables: `a_i`, dimensionless activity; `\gamma_{c,i}`, concentration-scale activity coefficient; `c_i`, amount concentration; `c^\circ`, standard amount concentration on the same scale.

Units: `a_i` and `\gamma_{c,i}` are dimensionless; `c_i` and `c^\circ` must use the same concentration units.

Assumptions: A declared concentration-based standard state and activity-coefficient convention.

Limitations: Molality, mole-fraction, electrolyte, and mixed-solvent conventions use different coefficients and standard states. Single-ion activities are convention-dependent in experimental practice.

Applications: Making the concentration-to-activity correction explicit.

Source: SOL-006; SOL-007

Verification: Verified

## Equation SOL-EQ003: Thermodynamic solubility product for an ionic solid

Reaction: `\mathrm{M}_p\mathrm{A}_q(s) \rightleftharpoons p\,\mathrm{M}^{z_M} + q\,\mathrm{A}^{z_A}`

Equation: `K_{sp}^\circ = a_{\mathrm{M}}^p a_{\mathrm{A}}^q`

Variables: `K_{sp}^\circ`, thermodynamic solubility product; `a_M` and `a_A`, ion activities; `p` and `q`, stoichiometric coefficients.

Units: All terms are dimensionless under the thermodynamic convention.

Assumptions: The named pure solid has unit activity, the dissolution reaction is balanced, and the specified solution is at equilibrium with that solid.

Limitations: Different polymorphs, hydrates, solvates, ion pairs, complexes, protonation states, and standard-state conventions require separate reactions or additional equilibria.

Applications: Saturation and precipitation calculations.

Source: SOL-004; SOL-005

Verification: Verified

## Equation SOL-EQ004: Ion-activity product

Equation: `IAP = a_{\mathrm{M}}^p a_{\mathrm{A}}^q`

Variables: `IAP`, ion-activity product for the declared dissolution reaction at the sampled state; other variables as in SOL-EQ003.

Units: Dimensionless under the same convention as `K_{sp}^\circ`.

Assumptions: Activities and stoichiometry refer to the same reaction, temperature, pressure, and thermodynamic database as the comparison solubility product.

Limitations: `IAP` is not an equilibrium constant and does not by itself predict a kinetic rate or induction time.

Applications: Comparing a measured or modelled solution state with mineral saturation.

Source: SOL-010

Verification: Verified

## Equation SOL-EQ005: Saturation index

Equation: `SI = \log_{10}\left(\frac{IAP}{K_{sp}^\circ}\right)`

Variables: `SI`, saturation index; `IAP`, ion-activity product; `K_{sp}^\circ`, applicable thermodynamic solubility product.

Units: `SI` and the logarithm argument are dimensionless.

Assumptions: `IAP` and `K_{sp}^\circ` share the same reaction, standard states, temperature, pressure, activity model, and database convention.

Interpretation: `SI<0`, undersaturated; `SI=0`, saturated; `SI>0`, supersaturated with respect to the named phase.

Limitations: Supersaturation identifies thermodynamic potential, not guaranteed immediate precipitation; nucleation, inhibition, transport, and metastable phases remain outside the equation.

Applications: Water chemistry, scale formation, dissolution, and precipitation assessment.

Source: SOL-010

Verification: Verified

## Equation SOL-EQ006: Idealized molar-solubility relation

Equation: `K_{sp}^\circ \approx (p s)^p(q s)^q`

Variables: `s`, molar solubility of formula units; `p` and `q`, dissolution stoichiometric coefficients.

Units: The displayed approximation is dimensionally valid only after each concentration is divided by the declared standard concentration; the compact classroom form suppresses those ratios.

Assumptions: Pure water or an otherwise compositionally simple solution, no initial common ions, complete dissociation into the displayed ions, no complexation or acid–base coupling, and activity coefficients approximated as unity.

Limitations: This is not a general conversion between `K_{sp}` and solubility. It fails when the assumptions above are not justified.

Applications: A bounded entry example before activity, common-ion, and speciation corrections are introduced.

Source: SOL-004; SOL-005; SOL-007; SOL-010

Verification: Verified
