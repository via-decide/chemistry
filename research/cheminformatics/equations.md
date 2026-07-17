---
topic: cheminformatics
section: equations
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 6
updated_by: codex
---

# Cheminformatics — Bounded Equation Records

## INF-EQ001

Name: Tanimoto Similarity Coefficient

Symbolic form: T(A,B) = \frac{c}{a + b - c} = \frac{|A \cap B|}{|A \cup B|}

Variables:
- T(A,B): Tanimoto similarity score between binary molecular fingerprints A and B, scalar ($0 \le T \le 1$)
- a: Number of active bits set in fingerprint A
- b: Number of active bits set in fingerprint B
- c: Number of active bits shared by both fingerprints A and B ($|A \cap B|$)

Assumptions: Binary bit-vector representations (e.g., ECFP4, MACCS); fixed bit length or sparse count vector.

Limitations: Tanimoto score depends strongly on fingerprint type and bit density; $T > 0.85$ is a conventional threshold for structural similarity but does not guarantee identical biological activity (activity cliffs).

Applications: Spreads S114, S115; chemical similarity search and clustering.

Sources: INF-001; INF-005

Verification status: Verified

## INF-EQ002

Name: Dice Similarity Coefficient

Symbolic form: S_{\text{Dice}}(A,B) = \frac{2 c}{a + b} = \frac{2 |A \cap B|}{|A| + |B|}

Variables:
- S_{\text{Dice}}: Dice similarity score between binary fingerprints A and B, scalar ($0 \le S_{\text{Dice}} \le 1$)
- a: Active bits in fingerprint A
- b: Active bits in fingerprint B
- c: Shared active bits between A and B

Assumptions: Binary molecular fingerprint representation.

Limitations: Dice score gives higher numerical weights to shared features compared to Tanimoto; monotonic transformation exists between Tanimoto and Dice.

Applications: Spreads S115; alternative molecular similarity scoring.

Sources: INF-001; INF-005

Verification status: Verified

## INF-EQ003

Name: Euclidean Distance in Molecular Descriptor Space

Symbolic form: d(x, y) = \sqrt{\sum_{i=1}^D (x_i - y_i)^2}

Variables:
- d(x, y): Euclidean distance between compound x and compound y in D-dimensional descriptor space
- x_i, y_i: Normalized value of i-th molecular descriptor (e.g., MW, LogP, TPSA, rotatable bonds)
- D: Total number of descriptors

Assumptions: Descriptors are scaled/standardized (z-score normalized) to prevent high-magnitude features from dominating distance.

Limitations: Sensitive to correlated features and non-linear distance metrics; requires dimensionality reduction (PCA/t-SNE) for high D.

Applications: Spreads S115, S117; applicability domain boundary definition.

Sources: INF-001; INF-006

Verification status: Verified

## INF-EQ004

Name: QSAR Model Coefficient of Determination (R^2)

Symbolic form: R^2 = 1 - \frac{\sum_{i=1}^N (y_i - \hat{y}_i)^2}{\sum_{i=1}^N (y_i - \bar{y})^2}

Variables:
- R^2: Goodness-of-fit statistic for QSAR training set, scalar ($0 \le R^2 \le 1$)
- y_i: Experimental activity/property value for compound i
- \hat{y}_i: Model-predicted activity/property value for compound i
- \bar{y}: Mean experimental activity across training set

Assumptions: Linear or non-linear regression model fitted on training set compounds.

Limitations: High $R^2$ on training data alone does not prove predictive power for new molecules (overfitting hazard).

Applications: Spreads S115, S117; QSAR model training evaluation.

Sources: INF-006

Verification status: Verified

## INF-EQ005

Name: QSAR Cross-Validated Predictive Metric (Q^2_CV)

Symbolic form: Q^2_{\text{CV}} = 1 - \frac{\sum_{i=1}^N (y_i - \hat{y}_{i, \text{out}})^2}{\sum_{i=1}^N (y_i - \bar{y})^2}

Variables:
- Q^2_{\text{CV}}: Cross-validated coefficient of determination (leave-one-out or k-fold CV), scalar
- \hat{y}_{i, \text{out}}: Predicted activity of compound i when excluded from model training fold
- y_i: Observed experimental activity of compound i
- \bar{y}: Mean experimental activity across dataset

Assumptions: Balanced k-fold or leave-one-out cross-validation scheme without data leakage across folds.

Limitations: OECD guidance specifies $Q^2_{\text{CV}} > 0.5$ as minimum threshold, but external validation test set ($R^2_{\text{ext}} > 0.6$) is mandatory for regulatory acceptance.

Applications: Spreads S116, S117; QSAR model validation and regulatory submission gate.

Sources: INF-006

Verification status: Verified

## INF-EQ006

Name: Lipinski Rule-of-Five Compliance Parameter

Symbolic form: \text{Ro5 Violations} = \sum_{k=1}^4 \mathbb{I}(\text{Rule}_k \text{ violated})

Variables:
- \text{Ro5 Violations}: Integer count of rule breaches ($0 \le \text{Violations} \le 4$)
- \text{Rule}_1: Molar mass $MW \le 500 \text{ g/mol}$
- \text{Rule}_2: Lipophilicity $\log P \le 5$
- \text{Rule}_3: Hydrogen bond donors $HBD \le 5$ (OH + NH groups)
- \text{Rule}_4: Hydrogen bond acceptors $HBA \le 10$ (N + O atoms)

Assumptions: Neutral, small-molecule oral drug candidates.

Limitations: Rule of Five applies specifically to passive gastrointestinal absorption of small molecules; invalid for natural products, peptides, macrocycles, and active transporter substrates.

Applications: Spreads S114, S115; drug-likeness filtering and compound library profiling.

Sources: INF-001; INF-004

Verification status: Verified
