---
topic: chromatography
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Chromatography — Bounded Equation Records

## CHR-EQ001

Name: Retention Factor (k)

Symbolic form: k = \frac{t_R - t_0}{t_0}

Variables:
- k: Retention factor (formerly capacity factor $k'$), dimensionless
- t_R: Retention time of analyte peak, \text{s} (or \text{min})
- t_0: Unretained peak retention time (dead time / hold-up time), \text{s} (or \text{min})

Assumptions: Isocratic / isothermal operation; unretained tracer experiences zero thermodynamic interaction with stationary phase.

Limitations: Invalid for gradient elution where mobile-phase velocity and composition change dynamically.

Applications: Spreads S110, S111; peak retention characterization and thermodynamic partitioning metric.

Sources: CHR-001; CHR-002; CHR-003

Verification status: Verified

## CHR-EQ002

Name: Separation Selectivity (Alpha)

Symbolic form: \alpha = \frac{k_2}{k_1} = \frac{t_{R2} - t_0}{t_{R1} - t_0} \quad (k_2 > k_1)

Variables:
- \alpha: Separation factor / relative retention selectivity, dimensionless ($\alpha \ge 1.0$)
- k_1, k_2: Retention factors of two adjacent peaks (1 and 2)
- t_{R1}, t_{R2}: Retention times of peaks 1 and 2, \text{s}

Assumptions: Identical column temperature, stationary phase, and mobile phase conditions for both peaks.

Limitations: $\alpha = 1.0$ indicates zero thermodynamic separation; high $\alpha$ does not guarantee complete resolution if band broadening is severe.

Applications: Spreads S111, S113; stationary phase and mobile phase selection metric.

Sources: CHR-002; CHR-004

Verification status: Verified

## CHR-EQ003

Name: Column Efficiency (Number of Theoretical Plates, N)

Symbolic form: N = 16 \cdot \left(\frac{t_R}{W}\right)^2 = 5.545 \cdot \left(\frac{t_R}{W_{1/2}}\right)^2

Variables:
- N: Number of theoretical plates, dimensionless
- t_R: Retention time of peak, \text{s}
- W: Peak width at baseline between tangents, \text{s}
- W_{1/2}: Peak width at half maximum height (FWHM), \text{s}

Assumptions: Gaussian peak shape profile.

Limitations: Asymmetric / tailing peaks require asymmetric model corrections (e.g., Foley–Dorsey equation).

Applications: Spreads S111, S112; column packing quality and efficiency rating.

Sources: CHR-002; CHR-005

Verification status: Verified

## CHR-EQ004

Name: Height Equivalent to a Theoretical Plate (HETP / H)

Symbolic form: H = \frac{L}{N}

Variables:
- H: Height equivalent to a theoretical plate (HETP), \text{m} (or \mu\text{m})
- L: Column length, \text{m}
- N: Number of theoretical plates, dimensionless

Assumptions: Uniform packing density and constant flow profile along length $L$.

Limitations: Lower $H$ specifies higher column efficiency; dependent on linear velocity $u$.

Applications: Spreads S111, S112; column performance evaluation.

Sources: CHR-002; CHR-005

Verification status: Verified

## CHR-EQ005

Name: Chromatographic Resolution (R_s) and Purnell Equation

Symbolic form: R_s = \frac{2 (t_{R2} - t_{R1})}{W_1 + W_2} = \frac{\sqrt{N}}{4} \cdot \left(\frac{\alpha - 1}{\alpha}\right) \cdot \left(\frac{k_2}{1 + k_2}\right)

Variables:
- R_s: Chromatographic resolution between adjacent peaks 1 and 2, dimensionless
- t_{R1}, t_{R2}: Retention times of peaks 1 and 2, \text{s}
- W_1, W_2: Baseline widths of peaks 1 and 2, \text{s}
- N: Average plate number, dimensionless
- \alpha: Selectivity, dimensionless
- k_2: Retention factor of second peak, dimensionless

Assumptions: Near-equal peak heights and Gaussian band shapes; $R_s \ge 1.5$ specifies baseline separation (99.7% purity).

Limitations: Valid for closely eluting peak pairs ($alpha approx 1$).

Applications: Spreads S110, S111; method optimization and separation acceptance criteria.

Sources: CHR-002; CHR-004; CHR-005

Verification status: Verified

## CHR-EQ006

Name: Van Deemter Equation for Column Band Broadening

Symbolic form: H = A + \frac{B}{u} + C \cdot u

Variables:
- H: Plate height (HETP), \text{m}
- A: Eddy diffusion term ($A = 2 \lambda d_p$), \text{m}
- B: Longitudinal molecular diffusion coefficient ($B = 2 \gamma D_m$), \text{m}^2 \cdot \text{s}^{-1}
- C: Mass transfer resistance term ($C = C_s + C_m$), \text{s}
- u: Mobile phase linear velocity, \text{m} \cdot \text{s}^{-1}

Assumptions: Packed column with spherical particles under laminar flow; constant temperature.

Limitations: Open tubular capillary columns (GC) have $A = 0$ (Golay equation); non-porous vs porous particles alter $C$ term significantly.

Applications: Spreads S111, S112; optimal linear velocity $u_{opt}$ determination.

Sources: CHR-002; CHR-005; CHR-006

Verification status: Verified
