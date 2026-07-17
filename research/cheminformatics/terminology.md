---
topic: cheminformatics
section: terminology
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 8
updated_by: codex
---

# Cheminformatics — Terminology & Controlled Vocabulary

## INF-T001

Term: Cheminformatics

Definition: The application of computer, information, and data science methodologies to solve problems in chemical structure representation, storage, search, analysis, and property prediction.

Source: INF-001; INF-004

Status: Verified

## INF-T002

Term: SMILES

Definition: Simplified Molecular-Input Line-Entry System; a ASCII line notation for representing molecular chemical structures as human-readable graph strings.

Source: INF-001; INF-004

Status: Verified

## INF-T003

Term: InChI & InChIKey

Definition: IUPAC International Chemical Identifier; a digital textual barcode representing chemical substance structure in hierarchical layers (main, charge, stereochemistry, isotope), paired with a fixed 27-character hashed InChIKey for rapid database indexing.

Source: INF-002; INF-003

Status: Verified

## INF-T004

Term: Molecular Graph

Definition: A mathematical graph representation of a molecule where vertices represent atoms and edges represent chemical bonds, specified by an adjacency matrix or connection table.

Source: INF-001; INF-004

Status: Verified

## INF-T005

Term: Molecular Fingerprint

Definition: A fixed-length binary or count vector encoding the presence or frequency of specific substructures, circular atom environments (e.g., ECFP4 / Morgan), or topological features in a molecule.

Source: INF-001; INF-005

Status: Verified

## INF-T006

Term: Tanimoto Coefficient

Definition: A mathematical ratio ($T = c / (a + b - c)$) measuring structural overlap between two binary molecular fingerprints.

Source: INF-001; INF-005

Status: Verified

## INF-T007

Term: Molecular Descriptor

Definition: A quantitative mathematical or physical property derived from a chemical structure (1D composition, 2D graph topology, or 3D conformation) used for QSAR modeling.

Source: INF-001; INF-006

Status: Verified

## INF-T008

Term: QSAR / QSPR

Definition: Quantitative Structure-Activity (or Property) Relationship; statistical or machine-learning models correlating quantitative chemical descriptors to biological activity or physical properties.

Source: INF-006

Status: Verified

## INF-T009

Term: Applicability Domain (AD)

Definition: The specific chemical, structural, and descriptor space in which a QSAR model has been trained and validated, defining the boundary within which predictions are reliable.

Source: INF-006

Status: Verified

## INF-T010

Term: Chemical Standardization

Definition: A systematic data-cleaning workflow that removes salts/solvents, neutralizes charges, unifies tautomers, and canonicalizes chemical representations before modeling.

Source: INF-002; INF-004

Status: Verified

## INF-T011

Term: Scaffold Split

Definition: A dataset partitioning method that groups molecules by core chemical scaffold (e.g., Murcko scaffold) into train and test sets to evaluate model generalization to novel chemical series.

Source: INF-006

Status: Verified

## INF-T012

Term: Data Leakage

Definition: An evaluation flaw where information from the test set (e.g., identical compounds or closely related analogs) contaminates the training set, artificially inflating validation metrics.

Source: INF-006

Status: Verified

## INF-T013

Term: Chemical Provenance

Definition: The documented history and metadata lineage of a chemical structure record, recording original raw source, extraction date, standardization pipeline, and version history.

Source: INF-003; INF-004

Status: Verified

## INF-T014

Term: Lipinski Rule of Five

Definition: A set of four physical property guidelines (MW $\le 500$, LogP $\le 5$, HBD $\le 5$, HBA $\le 10$) predicting oral bioavailability of small-molecule drug candidates.

Source: INF-001; INF-004

Status: Verified
