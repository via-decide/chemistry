---
topic: nuclear-chemistry
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Nuclear Chemistry — Equations

## Equation NUC-EQ001: Single-radionuclide decay differential equation

Equation: `\frac{\mathrm{d}N}{\mathrm{d}t} = -\lambda N`

Variables: `N`, number of nuclei in the specified radionuclide state; `t`, elapsed time; `\lambda`, decay constant for that state.

Units: `N` is a count; `t` is time; `\lambda` has reciprocal-time units.

Assumptions: A single radionuclide state with a time-invariant decay constant; no production, replenishment, or removal process other than the specified spontaneous decay.

Limitations: A decay chain, branching decay, activation, chemical transfer, detector response, and sample loss require additional terms or a different model.

Applications: Decay correction, activity projection, and half-life calculations.

Source: NUC-004; NUC-006; NUC-012

Verification: Verified

## Equation NUC-EQ002: Integrated single-radionuclide decay law

Equation: `N(t) = N_0\exp(-\lambda t)`

Variables: `N(t)`, number of specified nuclei at time `t`; `N_0`, number at the declared reference time; `\lambda`, decay constant; `t`, elapsed time.

Units: `N(t)` and `N_0` are counts; `\lambda t` is dimensionless.

Assumptions: The assumptions of NUC-EQ001 and a declared reference time at which `N=N_0`.

Limitations: It does not predict the decay time of an individual nucleus and does not represent parent–daughter ingrowth without coupled equations.

Applications: Projecting population or activity between reference times.

Source: NUC-006; NUC-012

Verification: Verified

## Equation NUC-EQ003: Activity–population relation

Equation: `A = -\frac{\mathrm{d}N}{\mathrm{d}t} = \lambda N`

Variables: `A`, activity of the specified radioactive material; `N`, number of nuclei in the specified state; `t`, time; `\lambda`, decay constant.

Units: `A` has reciprocal-second units in SI and is expressed in becquerels, where `1 Bq = 1 s^{-1}`; `\lambda` has reciprocal-time units.

Assumptions: The activity and population refer to the same radionuclide state and the same time.

Limitations: Instrument counts or count rate are not activity until geometry, efficiency, emission probability, background, dead time, and other corrections are addressed.

Applications: Converting between radionuclide population and activity.

Source: NUC-005; NUC-006; NUC-014

Verification: Verified

## Equation NUC-EQ004: Half-life relation

Equation: `t_{1/2} = \frac{\ln 2}{\lambda}`

Variables: `t_{1/2}`, half-life for one decay process; `\lambda`, decay constant for that process.

Units: `t_{1/2}` has time units reciprocal to the units selected for `\lambda`.

Assumptions: Single exponential decay with a time-invariant decay constant.

Limitations: Effective, biological, or multicomponent half-times are not interchangeable with the physical half-life defined here.

Applications: Converting decay constant to half-life and calculating elapsed decay intervals.

Source: NUC-006; NUC-007; NUC-012

Verification: Verified

## Equation NUC-EQ005: Nuclear reaction or transformation energy balance

Equation: `Q = \left(\sum m_{\mathrm{initial}} - \sum m_{\mathrm{final}}\right)c^2`

Variables: `Q`, net energy released when positive or required when negative under the stated reaction convention; `m`, rest masses of the declared initial and final species; `c`, speed of light in vacuum.

Units: With SI masses and `c`, `Q` is in joules; nuclear tables commonly convert atomic mass units to electronvolts using declared conversion factors.

Assumptions: A balanced nuclear transformation and one consistent mass convention, including correct electron bookkeeping when atomic masses are used.

Limitations: `Q` is not automatically the kinetic energy of one product; recoil, excitation, emitted radiation, neutrinos, and other products share the energy and momentum balance.

Applications: Relating mass difference to transformation energy and checking energetic feasibility.

Source: NUC-010; NUC-011

Verification: Verified

## Equation NUC-EQ006: HPGe full-energy-peak activity measurement

Equation: `A = \frac{N(E)}{T\,\epsilon(E)\,P(E)}\prod_i C_i`

Variables: `A`, source activity; `N(E)`, net counts in the full-energy peak at energy `E`; `T`, live time; `\epsilon(E)`, full-energy-peak efficiency; `P(E)`, gamma-ray emission probability; `C_i`, declared correction factors.

Units: `N(E)`, `\epsilon(E)`, `P(E)`, and correction factors are dimensionless under the cited convention; `T` is in seconds; `A` is in reciprocal seconds or becquerels.

Assumptions: A calibrated HPGe gamma-spectrometry system, matched source geometry, a background-corrected peak area, valid emission data, and all material corrections required by the cited NIST procedure.

Limitations: The equation is not detector-independent. Peak fitting, dead time, pile-up, cascade summing, attenuation, geometry, efficiency, emission probability, and decay corrections can contribute to the result and its uncertainty.

Applications: Converting full-energy-peak counts to source activity and making the counts-versus-decays boundary explicit.

Source: NUC-014

Verification: Verified
