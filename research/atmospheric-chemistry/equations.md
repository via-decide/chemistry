---
topic: atmospheric-chemistry
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Atmospheric Chemistry — Bounded Equation Records

## ATM-EQ001

Name: Photolysis Frequency / J-Value

Symbolic form: J_i = \int_{\lambda} \sigma_i(\lambda, T) \cdot \phi_i(\lambda, T) \cdot F(\lambda) \, d\lambda

Variables:
- J_i: First-order photolysis rate coefficient for atmospheric species i, \text{s}^{-1}
- \sigma_i: Absorption cross-section, \text{cm}^2 \cdot \text{molecule}^{-1}
- \phi_i: Quantum yield for specific photo-dissociation channel, dimensionless
- F: Actinic solar flux density, \text{photons} \cdot \text{cm}^{-2} \cdot \text{s}^{-1} \cdot \text{nm}^{-1}

Assumptions: Isotropic actinic flux distribution; temperature-dependent cross-sections.

Limitations: Actinic flux $F(\lambda)$ varies rapidly with altitude, solar zenith angle, cloud cover, and column ozone.

Applications: Spreads S157, S158; stratospheric ozone and tropospheric photochemical smog kinetics.

Sources: ATM-001; ATM-003

Verification status: Verified

## ATM-EQ002

Name: Atmospheric Chemical Lifetime (Tau)

Symbolic form: \tau_i = \frac{[C_i]}{\sum k_j [X_j] [C_i] + J_i [C_i] + L_{\text{dep}} [C_i]} = \frac{1}{\sum k_j [X_j] + J_i + k_{\text{dep}}}

Variables:
- \tau_i: Atmospheric chemical residence time / lifetime, \text{s} (or days/years)
- [C_i]: Concentration of species i, \text{molecules} \cdot \text{cm}^{-3}
- k_j: Bimolecular reaction rate constant with oxidant $X_j$ (OH, $O_3$, $NO_3$), \text{cm}^3 \cdot \text{molecule}^{-1} \cdot \text{s}^{-1}
- J_i: Photolysis frequency, \text{s}^{-1}
- k_{\text{dep}}: First-order deposition rate (wet + dry), \text{s}^{-1}

Assumptions: Pseudo-first-order removal kinetics under steady-state oxidant fields.

Limitations: Invalid if local emission inputs exceed transport mixing time scale ($u / L_{scale}$).

Applications: Spreads S157, S158; pollutant transport and global warming potential calculations.

Sources: ATM-002; ATM-003

Verification status: Verified
