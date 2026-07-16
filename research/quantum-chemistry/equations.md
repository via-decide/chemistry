---
topic: quantum-chemistry
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: low
primary_sources: 1
secondary_sources: 0
updated_by: codex
---

# Quantum Chemistry — Equations

## Equation QC-EQ001: Time-dependent Schrödinger equation

Equation: `i\hbar \frac{\partial \Psi(\mathbf{r},t)}{\partial t} = \hat{H}\Psi(\mathbf{r},t)`

Variables: `i`, imaginary unit; `\hbar`, reduced Planck constant; `\Psi`, time-dependent state wavefunction; `\mathbf{r}`, spatial coordinates; `t`, time; `\hat{H}`, Hamiltonian operator.

Units: `\hat{H}` has energy units; `t` has time units; `\hbar` has energy-time units; the normalization convention determines the dimensions of `\Psi`.

Assumptions: Non-relativistic quantum mechanics; a defined Hamiltonian, state space, boundary conditions, and normalization convention.

Limitations: The equation record does not specify a molecular Hamiltonian, relativistic correction, open-system term, numerical representation, or solution method.

Applications: Time evolution and spectroscopy models.

Source: QC-001

Verification: Needs verification; exact course-page derivation locator has not been recorded.

## Equation QC-EQ002: Time-independent Schrödinger equation

Equation: `\hat{H}\psi(\mathbf{r}) = E\psi(\mathbf{r})`

Variables: `\hat{H}`, Hamiltonian operator; `\psi`, stationary-state eigenfunction; `E`, energy eigenvalue; `\mathbf{r}`, spatial coordinates.

Units: `\hat{H}` and `E` have energy units; the normalization convention determines the dimensions of `\psi`.

Assumptions: Time-independent Hamiltonian; stationary-state formulation; defined boundary conditions and normalization.

Limitations: A computable molecular model still requires a specified Hamiltonian and declared approximations; the record does not imply an exact many-electron solution.

Applications: Bound-state energy and electronic-structure formulations.

Source: QC-001

Verification: Needs verification; exact course-page derivation locator has not been recorded.
