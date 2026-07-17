---
topic: surface-chemistry
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Surface Chemistry — Equations

## Equation SUR-EQ001: Surface excess for a two-phase reference system

Equation: `n_i^{\sigma} = n_i - V^{\alpha}c_i^{\alpha} - V^{\beta}c_i^{\beta}`

Variables: `n_i^{\sigma}` is the surface excess amount of component `i`; `n_i` is its total amount in the system; `V^{\alpha}` and `V^{\beta}` are the assigned bulk-phase volumes; `c_i^{\alpha}` and `c_i^{\beta}` are the corresponding bulk amount concentrations.

Units: Amount units for `n_i^{\sigma}` and `n_i`; volume for each `V`; amount per volume for each `c`.

Assumptions: A declared two-phase system, an explicitly chosen Gibbs dividing surface, homogeneous bulk reference regions, and compatible amount and volume bases.

Limitations: Surface excess is a reference-system quantity. Its numerical value can depend on the dividing-surface convention and it is not automatically the literal count of molecules in a geometrically sharp layer.

Sources: SUR-001; SUR-003

Status: Verified

## Equation SUR-EQ002: Surface excess concentration

Equation: `\Gamma_i = n_i^{\sigma}/A_s`

Variables: `\Gamma_i` is the surface excess concentration of component `i`; `n_i^{\sigma}` is its surface excess amount; `A_s` is the area of the chosen dividing surface or interface.

Units: Commonly moles per square metre for `\Gamma_i`, moles for `n_i^{\sigma}`, and square metres for `A_s`.

Assumptions: The same dividing-surface convention and interfacial area are used in the numerator and denominator.

Limitations: A rough, porous, heterogeneous, or evolving interface requires a stated area definition and measurement method; geometric, BET, and electrochemically active areas are not interchangeable.

Sources: SUR-001; SUR-004

Status: Verified

## Equation SUR-EQ003: Surface coverage

Equation: `\theta = N_{\mathrm{ads}}/N_{\mathrm{mono}}`

Variables: `\theta` is surface coverage; `N_{\mathrm{ads}}` is the number or amount of adsorbed entities assigned to the surface; `N_{\mathrm{mono}}` is the number or amount corresponding to a filled monolayer under the declared convention.

Units: Dimensionless when numerator and denominator use the same number or amount basis.

Assumptions: A defined adsorbate, surface, adsorption state, monolayer capacity, temperature, and coverage convention.

Limitations: Coverage does not by itself identify site geometry, adsorbate orientation, lateral interactions, pore filling, multilayer adsorption, or chemical state.

Sources: SUR-001; SUR-006; SUR-009

Status: Verified

## Equation SUR-EQ004: Langmuir adsorption isotherm

Equation: `\theta = bp/(1 + bp)`

Variables: `\theta` is fractional coverage; `p` is equilibrium adsorptive pressure; `b` is the equilibrium parameter for the declared temperature and standard-state convention.

Units: `\theta` and `bp` are dimensionless; if `p` is represented as a dimensional pressure, `b` has reciprocal-pressure units consistent with that pressure basis.

Assumptions: The selected Langmuir form represents a uniform population of independent sites, one adsorbate entity per site, monolayer occupancy, equilibrium, and no material lateral-interaction term.

Limitations: A visually good fit does not prove the assumptions. Dissociative adsorption, multiple site classes, lateral interactions, multilayers, pore filling, surface reconstruction, transport limitation, or changing speciation require another model.

Sources: SUR-001; SUR-010

Status: Verified

## Equation SUR-EQ005: Reversible surface work

Equation: `\delta w_{\mathrm{rev}} = \gamma\,\mathrm{d}A_s`

Variables: `\delta w_{\mathrm{rev}}` is reversible work associated with an interfacial-area change; `\gamma` is surface or interfacial tension for the declared interface; `A_s` is interfacial area.

Units: Joules for work, joules per square metre or newtons per metre for `\gamma`, and square metres for area.

Assumptions: Reversible area change under the declared temperature, pressure, composition, and mechanical constraints.

Limitations: For solids, anisotropy, strain, reconstruction, adsorption, and the distinction between surface free energy and surface stress can prevent a simple liquid-interface interpretation.

Sources: SUR-001; SUR-007

Status: Verified

## Equation SUR-EQ006: Gibbs adsorption relation

Equation: `\mathrm{d}\gamma = -\sum_i \Gamma_i\,\mathrm{d}\mu_i`

Variables: `\gamma` is interfacial tension; `\Gamma_i` is the surface excess concentration of component `i` under the chosen dividing-surface convention; `\mu_i` is its chemical potential.

Units: Each term has energy per area units when `\Gamma_i` is amount per area and `\mu_i` is energy per amount.

Assumptions: Interfacial equilibrium at fixed temperature with a declared pressure or mechanical constraint, composition variables, standard states, and Gibbs dividing surface.

Limitations: The familiar single-solute dilute-solution form requires additional ideality and dividing-surface choices. Dynamic adsorption, reacting interfaces, surface heterogeneity, and nonequilibrium gradients are outside this equilibrium differential relation.

Sources: SUR-001; SUR-003; SUR-004; SUR-007

Status: Verified

## Equation SUR-EQ007: BET linear form for gas physisorption

Equation: `p/[n_a(p^0-p)] = 1/(n_m C) + [(C-1)/(n_m C)](p/p^0)`

Variables: `p` is equilibrium pressure; `p^0` is saturation vapour pressure at the measurement temperature; `n_a` is the amount adsorbed at `p`; `n_m` is monolayer capacity; `C` is the BET parameter.

Units: `p/p^0` and `C` are dimensionless; the ordinate and intercept have reciprocal-amount units when `n_a` and `n_m` use an amount basis.

Assumptions: Gas physisorption data, declared adsorptive and temperature, equilibrium measurements, and a physically justified BET fitting region satisfying the applicable consistency criteria.

Limitations: The equation is not a universal surface-area law. Micropore filling, pore condensation, surface heterogeneity, nonphysical fitted parameters, an arbitrary linear range, or an unsuitable molecular cross-section can invalidate the result.

Sources: SUR-009; SUR-011

Status: Verified
