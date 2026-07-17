---
topic: mass-spectrometry
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Mass Spectrometry — Bounded Equation Records

## MS-EQ001

Name: Mass-to-Charge Ratio (m/z)

Symbolic form: \frac{m}{z} = \frac{m_{\text{ion}}}{z \cdot e}

Variables:
- \frac{m}{z}: Mass-to-charge ratio, unified atomic mass unit per elementary charge (or dimensionless IUPAC quantity)
- m_{\text{ion}}: Mass of the detected ion, \text{kg} (or \text{Da})
- z: Charge number (integer scalar, \pm 1, \pm 2, \dots)
- e: Elementary charge, $1.602176634 \times 10^{-19} \text{ C}$

Assumptions: Detected particle is an isolated gas-phase ion carrying integer electronic charges.

Limitations: $m/z$ does not yield mass alone unless charge state $z$ is independently assigned.

Applications: Spreads S106, S107; mass spectrum peak assignment and calibration.

Sources: MS-001; MS-002; MS-003

Verification status: Verified

## MS-EQ002

Name: Mass Resolving Power (FWHM Definition)

Symbolic form: R = \frac{m}{\Delta m_{\text{FWHM}}}

Variables:
- R: Resolving power, dimensionless
- m: Nominal or exact mass-to-charge ratio of the observed peak, \text{Th} (or \text{Da})
- \Delta m_{\text{FWHM}}: Peak width measured at half maximum intensity (Full Width at Half Maximum), \text{Th} (or \text{Da})

Assumptions: Peak profile is well-defined and symmetric; FWHM measurement criteria apply.

Limitations: Resolving power varies across mass range in Orbitrap and TOF analyzers; reporting $R$ requires specifying reference $m/z$.

Applications: Spreads S107, S109; high-resolution mass spectrometry performance evaluation.

Sources: MS-002; MS-004

Verification status: Verified

## MS-EQ003

Name: Time-of-Flight (TOF) Flight Time

Symbolic form: t = L \cdot \sqrt{\frac{m}{2 z e V_{\text{acc}}}}

Variables:
- t: Time of flight from source to detector, \text{s}
- L: Field-free flight tube length, \text{m}
- m: Ion mass, \text{kg}
- z: Ion charge number, dimensionless
- e: Elementary charge, \text{C}
- V_{\text{acc}}: Acceleration voltage applied in ion source, \text{V}

Assumptions: Ions acquire kinetic energy $E_k = z e V_{\text{acc}}$ in a short acceleration region and drift through field-free space.

Limitations: Neglects initial spatial and thermal kinetic energy spreads; requires reflectron correction for high resolution.

Applications: Spreads S106, S108; TOF mass analyzer calibration and design.

Sources: MS-002

Verification status: Verified

## MS-EQ004

Name: Quadrupole Stability Parameter (q_x)

Symbolic form: q_x = \frac{4 e V_{\text{rf}}}{m r_0^2 \Omega^2}

Variables:
- q_x: Dimensionless Mathieu stability equation parameter along x-axis
- e: Elementary charge, \text{C}
- V_{\text{rf}}: Peak RF potential amplitude applied to quadrupole rods, \text{V}
- m: Ion mass, \text{kg}
- r_0: Inscribed radius between quadrupole rods, \text{m}
- \Omega: Angular frequency of RF voltage, \text{rad} \cdot \text{s}^{-1}

Assumptions: Ideal hyperbolic quadrupole electric field with quadrupolar potential distribution.

Limitations: Valid inside stability boundary ($q_x < 0.908$); fringing fields and rod imperfections cause transmission losses.

Applications: Spreads S108, S109; quadrupole mass filter and ion-guide operating boundaries.

Sources: MS-002

Verification status: Verified

## MS-EQ005

Name: Monoisotopic Exact Mass and Isotope Abundance Defect

Symbolic form: \Delta m_{\text{iso}} = m_{(M+1)} - m_M

Variables:
- \Delta m_{\text{iso}}: Mass difference between first heavy isotope peak ($M+1$) and monoisotopic peak ($M$), \text{Da}
- m_M: Monoisotopic exact mass calculated using principal stable isotopes ($^{1}\text{H}, ^{12}\text{C}, ^{14}\text{N}, ^{16}\text{O}, ^{31}\text{P}, ^{32}\text{S}$), \text{Da}
- m_{(M+1)}: Exact mass of ion containing one $^{13}\text{C}$, $^{2}\text{H}$, or $^{15}\text{N}$ atom, \text{Da}

Assumptions: Natural terrestrial isotopic abundance distributions.

Limitations: Requires high-resolution measurement ($R > 20{,}000$) to resolve isotopic fine structure ($^{13}\text{C}$ vs $^{15}\text{N}$ vs $^{18}\text{O}$).

Applications: Spreads S107, S109; elemental formula determination and molecular identification.

Sources: MS-002; MS-006

Verification status: Verified

## MS-EQ006

Name: Mass Spectrometric Ion Transmission Efficiency

Symbolic form: \eta_{\text{trans}} = \frac{I_{\text{detector}}}{I_{\text{source}}}

Variables:
- \eta_{\text{trans}}: Fractional ion transmission efficiency, dimensionless
- I_{\text{detector}}: Ion current reaching detector, \text{A} (or ions/sec)
- I_{\text{source}}: Total ion current generated in ionization chamber, \text{A}

Assumptions: Steady-state ion beam generation and continuous ion counting.

Limitations: Varies strongly with $m/z$, space-charge limits, pressure in vacuum stages, and optics tuning.

Applications: Spreads S106, S108; instrument sensitivity and quantitative analysis boundaries.

Sources: MS-002; MS-005

Verification status: Verified
