---
topic: clinical-chemistry
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Clinical Chemistry — Bounded Equation Records

## CLN-EQ001

Name: Clinical Diagnostic Sensitivity and Specificity

Symbolic form: \text{Sensitivity} = \frac{TP}{TP + FN}, \quad \text{Specificity} = \frac{TN}{TN + FP}

Variables:
- TP: True Positives (diseased individuals with positive test result)
- TN: True Negatives (healthy individuals with negative test result)
- FP: False Positives (healthy individuals with positive test result)
- FN: False Negatives (diseased individuals with negative test result)

Assumptions: Gold-standard clinical disease diagnosis reference.

Limitations: Sensitivity and specificity depend on the selected decision threshold / cutoff concentration.

Applications: Spreads S139, S140; clinical assay validation and diagnostic decision limits.

Sources: CLN-001; CLN-002

Verification status: Verified

## CLN-EQ002

Name: Friedewald Equation for Estimated LDL-Cholesterol

Symbolic form: [\text{LDL-C}] = [\text{Total Cholesterol}] - [\text{HDL-C}] - \frac{[\text{Triglycerides}]}{5} \quad (\text{in mg/dL})

Variables:
- [\text{LDL-C}]: Low-density lipoprotein cholesterol, \text{mg/dL}
- [\text{Total Cholesterol}]: Total serum cholesterol, \text{mg/dL}
- [\text{HDL-C}]: High-density lipoprotein cholesterol, \text{mg/dL}
- [\text{Triglycerides}]: Serum triglyceride concentration, \text{mg/dL}

Assumptions: Fasting patient blood sample; VLDL cholesterol estimated as $	ext{Triglycerides}/5$.

Limitations: Invalid if serum triglycerides exceed $400 \text{ mg/dL}$ or in type III hyperlipoproteinemia.

Applications: Spreads S139, S140; clinical lipid panel reporting.

Sources: CLN-002

Verification status: Verified
