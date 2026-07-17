---
topic: photochemistry
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 1
secondary_sources: 6
updated_by: codex
---

# Photochemistry — Equations

## Equation PHO-EQ001: Photon energy

Equation: `E_{\mathrm{p}} = h\nu = hc_0/\lambda_0`

Variables: `E_{\mathrm{p}}` is energy per photon; `h` is the Planck constant; `\nu` is frequency; `c_0` is the speed of light in vacuum; `\lambda_0` is vacuum wavelength.

Units: `E_{\mathrm{p}}` in joules per photon, `\nu` in reciprocal seconds, `\lambda_0` in metres, `h` in joule seconds, and `c_0` in metres per second.

Assumptions: The wavelength and speed refer to vacuum values. For an amount of photons, multiply by the Avogadro constant with the amount basis declared.

Limitations: Photon energy does not establish that a species absorbs at that wavelength, which state is populated, or which chemical pathway follows.

Sources: PHO-009

Status: Verified

## Equation PHO-EQ002: Beer–Lambert relation

Equation: `A_\lambda = \log_{10}(P_\lambda^0/P_\lambda) = \varepsilon_\lambda c l`

Variables: `A_\lambda` is decadic absorbance; `P_\lambda^0` and `P_\lambda` are incident and transmitted spectral radiant powers; `\varepsilon_\lambda` is the decadic molar absorption coefficient; `c` is amount concentration; `l` is optical path length.

Units: `A_\lambda` is dimensionless; a common consistent set is `\varepsilon_\lambda` in litres per mole per centimetre, `c` in moles per litre, and `l` in centimetres.

Assumptions: Collimated monochromatic radiation, a homogeneous isotropic medium, a declared absorbing species, and a regime in which absorbance is proportional to concentration and path length.

Limitations: Reflection, scattering, emission, concentration-dependent speciation, high optical density, polychromatic irradiation, and spatially varying fields can invalidate the simple one-dimensional relation.

Sources: PHO-010; PHO-018

Status: Verified

## Equation PHO-EQ003: Absorbed photon fraction from absorbance

Equation: `f_{\mathrm{abs}}(\lambda) = 1 - 10^{-A(\lambda)}`

Variables: `f_{\mathrm{abs}}(\lambda)` is the fraction of incident photons absorbed at wavelength `\lambda`; `A(\lambda)` is decadic absorbance at that wavelength.

Units: Both quantities are dimensionless.

Assumptions: The attenuation represented by `A` is attributable to absorption in the defined optical path and the incident and absorbed photon quantities share the same spectral and geometric basis.

Limitations: The expression cannot silently convert electrical lamp power or irradiance outside the reactor into absorbed photon flux; reflection, scattering, windows, nonuniform irradiation, and competing absorbers require explicit treatment.

Sources: PHO-010; PHO-011

Status: Verified

## Equation PHO-EQ004: Differential quantum yield

Equation: `\Phi(\lambda) = (\mathrm{d}x/\mathrm{d}t) / \{q_{n,\mathrm{p}}^0[1 - 10^{-A(\lambda)}]\}`

Variables: `\Phi(\lambda)` is the differential quantum yield for a defined event; `x` is the measured amount or amount-equivalent quantity; `q_{n,\mathrm{p}}^0` is incident photon flux on an amount basis; `A(\lambda)` is absorbance at the excitation wavelength.

Units: `\Phi` is dimensionless when numerator and denominator use compatible amount-per-time bases; `q_{n,\mathrm{p}}^0` is commonly moles of photons per second.

Assumptions: The event, excitation wavelength, optical geometry, time interval, conversion regime, and analytical response are declared; absorbed rather than merely incident photons form the denominator.

Limitations: Strict quantum-yield use assumes monochromatic excitation. Polychromatic fields, changing absorption spectra, secondary photolysis, dark reactions, chain processes, and spatial gradients require a more complete model.

Sources: PHO-011

Status: Verified

## Equation PHO-EQ005: Bounded actinometric photon-flux relation

Equation: `q_{n,\mathrm{p,abs}} = \Delta n_{\mathrm{act}}/(\Phi_{\mathrm{act}}\Delta t)`

Variables: `q_{n,\mathrm{p,abs}}` is absorbed photon flux in the actinometer; `\Delta n_{\mathrm{act}}` is amount of the monitored actinometric event; `\Phi_{\mathrm{act}}` is the applicable actinometer quantum yield; `\Delta t` is irradiation time.

Units: `q_{n,\mathrm{p,abs}}` in moles of photons per second, `\Delta n_{\mathrm{act}}` in moles, and `\Delta t` in seconds; `\Phi_{\mathrm{act}}` is dimensionless.

Assumptions: The selected actinometer, wavelength range, solvent, concentration, temperature, conversion range, optical geometry, analysis, and quantum-yield data follow a verified procedure.

Limitations: This compact relation does not replace actinometer-specific corrections for incomplete absorption, spectral bandwidth, photoproduct absorption, reversibility, side reactions, or reactor geometry.

Sources: PHO-012; PHO-014

Status: Verified

## Equation PHO-EQ006: Spectral first-order photolysis frequency

Equation: `J = \int F(\lambda)\,\sigma(\lambda,T)\,\Phi(\lambda,T)\,\mathrm{d}\lambda`

Variables: `J` is photolysis frequency for a specified reactant and channel; `F(\lambda)` is spectral actinic photon flux density; `\sigma(\lambda,T)` is absorption cross section; `\Phi(\lambda,T)` is channel-specific photolysis quantum yield; `T` is temperature.

Units: One consistent number basis uses `F` in photons per square centimetre per second per nanometre, `\sigma` in square centimetres per molecule, `\Phi` dimensionless, and `\mathrm{d}\lambda` in nanometres, yielding `J` in reciprocal seconds.

Assumptions: Spectral data, temperature, reaction channel, actinic field, wavelength grid, interpolation, and integration limits are declared and compatible.

Limitations: This atmospheric-style first-order expression is not a universal stirred-reactor rate law. Shielding, scattering, competing absorbers, mass transfer, concentration change, secondary chemistry, and reactor radiative transfer may require spatially resolved modelling.

Sources: PHO-013

Status: Verified
