---
topic: cheminformatics
section: source-packets
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 10
updated_by: codex
---

# Cheminformatics — Atlas Source Packets

These packets establish authoritative evidence coverage for the planned spreads S114–S117.

## Packet INF-SP-S114

Spread: S114, pages 227–228

Visual subject: Chemical identity and representation mapping: chemical entity vs 2D graph, SMILES line string, InChI hierarchical layers, InChIKey hash, molfile connection table, molecular descriptors, and registry provenance.

Authoritative sources: INF-001; INF-002; INF-003; INF-004

Supported claims: INF-C001; INF-C002; INF-C003; INF-C004; INF-C005

Equation records: INF-EQ006

Primary sources: INF-002; INF-003 — InChI Trust and NIST standards verified

Standards and official recommendations: INF-001; INF-002; INF-003 — IUPAC and NIST verified

Required visual distinctions: physical molecule versus computer representation; non-canonical SMILES versus canonical SMILES; InChI structural layers versus hashed InChIKey; 2D connectivity graph versus 3D spatial conformation.

Known limitation: Representation framework defined. Spread S114 remains Needs Research until one specific compound case (e.g., Aspirin or Ibuprofen) is selected and mapped across all formats.

Packet status: Verified

Spread status: Needs Research

## Packet INF-SP-S115

Spread: S115, pages 229–230

Visual subject: Molecular fingerprints and similarity dashboard: ECFP4 / Morgan circular atom environment encoding, MACCS keys, Tanimoto calculation $T(A,B)$, similarity heatmap, applicability domain boundary, and prediction uncertainty.

Authoritative sources: INF-001; INF-004; INF-005; INF-006

Supported claims: INF-C006; INF-C007; INF-C008; INF-C009; INF-C010

Equation records: INF-EQ001; INF-EQ002; INF-EQ003

Primary sources: INF-005 — Rogers & Hahn ECFP paper verified

Standards and official recommendations: INF-001; INF-006 — IUPAC and OECD guidance verified

Required callouts: atom radius / diameter (e.g., radius 2 for ECFP4); active bit count; Tanimoto vs Dice comparison; similarity threshold ($T = 0.85$); activity cliff warning.

Known limitation: Formulas verified. Spread S115 remains Needs Research until a real 5-compound similarity dataset is computed and visual heatmaps generated.

Packet status: Verified

Spread status: Needs Research

## Packet INF-SP-S116

Spread: S116, pages 231–232

Visual subject: Chemical data ingestion & standardization pipeline flowchart: raw database input, salt/solvent stripping, charge neutralization, tautomer canonicalization, stereochemistry validation, deduplication, feature generation, model training, and provenance audit log.

Authoritative sources: INF-001; INF-002; INF-004; INF-006

Supported claims: INF-C011; INF-C012; INF-C013; INF-C014

Equation records: INF-EQ004; INF-EQ005

Primary sources: INF-004; INF-006 — Verified

Standards and official recommendations: INF-002; INF-006 — IUPAC and OECD standards verified

Required callouts: salt dictionary; tautomer rules; canonical InChIKey deduplication; failed structure error log; dataset versioning checksum.

Known limitation: Pipeline architecture defined. Spread S116 remains Needs Research until an open benchmark dataset (e.g., ChEMBL or PubChem subset) is processed through the pipeline.

Packet status: Verified

Spread status: Needs Research

## Packet INF-SP-S117

Spread: S117, pages 233–234

Visual subject: QSAR model validation decision tree: training set vs test set split, random split vs scaffold split comparison, data leakage detection, applicability domain evaluation, $Q^2_{\text{CV}}$ cross-validation, and external validation test.

Authoritative sources: INF-001; INF-004; INF-006

Supported claims: INF-C015; INF-C016; INF-C017; INF-C018; INF-C019; INF-C020

Equation records: INF-EQ003; INF-EQ004; INF-EQ005

Primary sources: INF-006 — OECD QSAR validation guidance verified

Standards and official recommendations: INF-006 — OECD regulatory validation standard verified

Required callouts: OECD 5 validation principles (defined endpoint, unambiguous algorithm, defined applicability domain, appropriate goodness-of-fit/predicticability, mechanistic interpretation); scaffold split vs random split $R^2$ gap; internal vs external test set performance.

Known limitation: Decision rules verified. Spread S117 remains Needs Research until a real QSAR model validation benchmark is selected and displayed.

Packet status: Verified

Spread status: Needs Research
