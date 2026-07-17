---
topic: chemical-engineering
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Chemical Engineering — Bounded Equation Records

## CHE-EQ001

Name: General Control Volume Mass Balance

Symbolic form: \frac{d m_{\text{sys}}}{dt} = \sum \dot{m}_{in} - \sum \dot{m}_{out} + \dot{m}_{gen} - \dot{m}_{cons}

Variables:
- \frac{d m_{\text{sys}}}{dt}: Rate of accumulation of mass within control volume, \text{kg} \cdot \text{s}^{-1}
- \dot{m}_{in}, \dot{m}_{out}: Mass flow rates into and out of control volume, \text{kg} \cdot \text{s}^{-1}
- \dot{m}_{gen}, \dot{m}_{cons}: Mass generation and consumption rates by chemical reaction, \text{kg} \cdot \text{s}^{-1}

Assumptions: Well-defined control volume boundaries.

Limitations: At steady state, $d m_{\text{sys}}/dt = 0$.

Applications: Spreads S148, S149; chemical plant process design and reactor sizing.

Sources: CHE-001; CHE-002

Verification status: Verified

## CHE-EQ002

Name: Continuous Stirred-Tank Reactor (CSTR) Design Equation

Symbolic form: V_{\text{CSTR}} = \frac{F_{A0} \cdot X_A}{-r_A}

Variables:
- V_{\text{CSTR}}: Reactor volume, \text{m}^3 (or \text{L})
- F_{A0}: Molar inlet flow rate of reactant A, \text{mol} \cdot \text{s}^{-1}
- X_A: Fractional conversion of reactant A, scalar ($0 \le X_A \le 1$)
- -r_A: Reaction rate evaluated at exit stream concentration, \text{mol} \cdot \text{m}^{-3} \cdot \text{s}^{-1}

Assumptions: Perfect spatial mixing ($C_A = C_{A,out}$ everywhere in reactor); steady state.

Limitations: CSTR requires larger volume than PFR for positive-order kinetics at high conversion.

Applications: Spreads S148, S150; industrial reactor design and scale-up.

Sources: CHE-001; CHE-002

Verification status: Verified
