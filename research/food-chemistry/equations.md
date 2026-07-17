---
topic: food-chemistry
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Food Chemistry — Bounded Equation Records

## FOO-EQ001

Name: Water Activity Equation

Symbolic form: a_w = \frac{p}{p_0} = \gamma_w \cdot x_w

Variables:
- a_w: Water activity in food matrix, scalar ($0 \le a_w \le 1.0$)
- p: Vapor pressure of water in food system at temperature T, \text{Pa}
- p_0: Vapor pressure of pure water at same temperature T, \text{Pa}
- \gamma_w: Activity coefficient of water in food matrix
- x_w: Mole fraction of water in food system

Assumptions: Equilibrium relative humidity ($ERH = a_w \times 100%$).

Limitations: $a_w$, not total moisture content (% water), dictates microbial growth, lipid oxidation rate, and Maillard browning kinetics.

Applications: Spreads S135, S136; food stability and shelf-life prediction.

Sources: FOO-001; FOO-002

Verification status: Verified

## FOO-EQ002

Name: Lipid Peroxide Value (PV) Calculation

Symbolic form: \text{PV} = \frac{(V_{\text{sample}} - V_{\text{blank}}) \cdot N_{\text{thiosulfate}} \cdot 1000}{m_{\text{oil}}}

Variables:
- \text{PV}: Peroxide value, \text{meq } O_2 \cdot \text{kg}^{-1} \text{ fat}
- V_{\text{sample}}, V_{\text{blank}}: Volume of sodium thiosulfate titrant used for sample and blank, \text{mL}
- N_{\text{thiosulfate}}: Normality of sodium thiosulfate solution, \text{eq} \cdot \text{L}^{-1}
- m_{\text{oil}}: Mass of oil/fat sample, \text{g}

Assumptions: Iodometric titration of hydroperoxides ($ROOH + 2I^- + 2H^+ \to ROH + I_2 + H_2O$).

Limitations: PV measures initial primary oxidation products; decreases as peroxides decompose into secondary aldehydes/ketones (requiring p-Anisidine value).

Applications: Spreads S135, S136; lipid rancidity and oil quality control.

Sources: FOO-001; FOO-002

Verification status: Verified
