---
topic: crystallography
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 0
secondary_sources: 3
updated_by: codex
---

# Crystallography — Equations

## Equation CRY-EQ001: Reciprocal-lattice vector

Equation: `\mathbf{H}_{hkl} = h\mathbf{a}^{*} + k\mathbf{b}^{*} + l\mathbf{c}^{*}`

Variables: `\mathbf{H}_{hkl}`, reciprocal-lattice vector; `h`, `k`, `l`, integer Miller indices; `\mathbf{a}^{*}`, `\mathbf{b}^{*}`, `\mathbf{c}^{*}`, reciprocal-basis vectors.

Units: In the IUCr dictionary convention used here, reciprocal-length units.

Assumptions: A defined direct crystallographic basis and its reciprocal basis.

Limitations: Some physics conventions incorporate a factor of `2\pi` in reciprocal vectors; conventions must not be mixed.

Applications: Indexing lattice planes and connecting direct and reciprocal space.

Source: CRY-003

Verification: Verified

## Equation CRY-EQ002: Indexed interplanar spacing

Equation: `d_{hkl} = 1 / |\mathbf{H}_{hkl}|`

Variables: `d_{hkl}`, perpendicular spacing for the indexed plane family; `|\mathbf{H}_{hkl}|`, magnitude of the associated reciprocal-lattice vector.

Units: `d_{hkl}` has length units; `|\mathbf{H}_{hkl}|` has reciprocal-length units.

Assumptions: IUCr reciprocal-lattice convention without a `2\pi` factor; indexed direct-lattice plane family.

Limitations: A different reciprocal-space convention changes the numerical factor; the equation alone does not provide unit-cell metric relationships for every crystal system.

Applications: Converting reciprocal-space positions into plane spacings.

Source: CRY-003

Verification: Verified

## Equation CRY-EQ003: Bragg relation

Equation: `n\lambda = 2d\sin\theta`

Variables: `n`, integer reflection order; `\lambda`, incident wavelength; `d`, lattice-plane spacing; `\theta`, angle between the incident beam and reflecting plane.

Units: `\lambda` and `d` use the same length unit; `\theta` is an angle.

Assumptions: Elastic scattering and constructive interference from a family of lattice planes; angle convention explicitly uses `\theta`, not the measured `2\theta` scan coordinate.

Limitations: Peak position alone does not determine a complete structure; instrumental, sample, and indexing effects must be handled separately.

Applications: Relating diffraction angle, wavelength, and plane spacing.

Source: CRY-003; CRY-004

Verification: Verified

## Equation CRY-EQ004: Weighted least-squares refinement objective

Equation: `\sum_i w_i\left(Y_{o,i} - Y_{c,i}\right)^2`

Variables: `Y_{o,i}`, observed reflection measure; `Y_{c,i}`, calculated measure from the structural model; `w_i`, assigned weight; `i`, reflection index.

Units: Each residual term has the squared units of the chosen reflection measure multiplied by its weighting convention.

Assumptions: Declared reflection measure, weighting model, structural parameterization, constraints, and restraints.

Limitations: A lower objective value does not alone establish model correctness; model choice, data quality, parameter correlations, and validation alerts remain material.

Applications: Refining a trial crystal-structure model against diffraction observations.

Source: CRY-006

Verification: Verified
