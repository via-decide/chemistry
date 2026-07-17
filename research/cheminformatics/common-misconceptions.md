---
topic: cheminformatics
section: common-misconceptions
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 8
updated_by: codex
---

# Cheminformatics — Common Misconceptions

## INF-M001

Misconception: A SMILES string is a unique and immutable chemical identifier.

Correction: SMILES strings depend on syntax flavor, atom numbering order, and software canonicalization algorithms. Without explicit standardization and canonicalization (or conversion to InChI/InChIKey), two different SMILES strings can represent the exact same chemical structure.

Evidence: INF-001; INF-002; INF-004

Status: Verified

## INF-M002

Misconception: High Tanimoto similarity ($T > 0.85$) guarantees identical biological activity.

Correction: Small chemical modifications (e.g., single atom substitution or enantiomeric inversion) can cause dramatic changes in biological activity—a phenomenon known as an "activity cliff." High fingerprint similarity does not eliminate activity cliffs.

Evidence: INF-001; INF-005; INF-006

Status: Verified

## INF-M003

Misconception: Random cross-validation (random train/test split) accurately measures QSAR model real-world predictive performance.

Correction: Random splitting frequently places close structural analogs in both train and test sets, causing scaffold leakage. Scaffold splitting or temporal splitting is required to test true generalization to novel chemical series.

Evidence: INF-006

Status: Verified

## INF-M004

Misconception: Machine-learning chemical models can provide valid predictions for any input molecule regardless of structure.

Correction: Every QSAR model is bounded by its OECD Applicability Domain (AD). Predictions for molecules falling outside the descriptor or structural training domain are extrapolations with unquantified error.

Evidence: INF-006

Status: Verified
