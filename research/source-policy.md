---
topic: repository
section: source-policy
status: draft
version: 1.0
last_reviewed: 2026-07-09
confidence: medium
primary_sources: 0
secondary_sources: 0
updated_by: codex
---

# Chemistry Corpus Source Policy

## Purpose

This repository is a chemistry evidence library. It prioritizes reliable, human-authored source material over narrative documentation.

## Source Tiers

### Tier 0 — Standards and Evaluated Data

Preferred for definitions, symbols, constants, and evaluated datasets.

- IUPAC Gold Book
- IUPAC Green Book
- NIST Chemistry WebBook
- NIST Atomic Spectra Database
- PubChem / NIH
- CODATA / BIPM where applicable

### Tier 1 — Handbooks and Encyclopedias

Preferred for industrial, applied, process, and tabulated-data sections.

- CRC Handbook of Chemistry and Physics
- Perry's Chemical Engineers' Handbook
- Ullmann's Encyclopedia of Industrial Chemistry
- Kirk-Othmer Encyclopedia of Chemical Technology
- Lange's Handbook of Chemistry

### Tier 2 — Peer-Reviewed Reviews

Preferred for `research-frontier.md` files.

- Chemical Reviews
- Accounts of Chemical Research
- Chemical Society Reviews
- Nature Reviews Chemistry
- Reviews of Modern Physics where physical chemistry overlaps
- Springer, Elsevier, Wiley, and RSC review volumes

### Tier 3 — Primary and Historical Literature

Preferred for history files and primary-literature files.

- Original papers
- Nobel lectures
- Historical books
- Patents
- Laboratory manuals
- Standards documents

### Tier 4 — Teaching Sources

Useful for scaffold and pedagogy, but should not dominate mature research packages.

- OpenStax
- ChemLibreTexts
- MIT OpenCourseWare
- NPTEL
- University lecture notes

## Evidence Handling Rules

- Do not add source-policy evidence links unless the linked URL directly supports the source-policy statement.
- Prefer the original publisher URL over mirrors.
- Record mirror usage in `Notes` and add replacement work to `research-queue.md`.
- Preserve DOI, URL, publication, authors, and verification status for every evidence item.
