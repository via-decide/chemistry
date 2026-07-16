# Repository Inventory

## Audit boundary

- Repository: `https://github.com/via-decide/chemistry.git`
- Commit: `4fa3d18928395d0216c4940d32e5c366f3a4e13c`
- Commit date: `2026-07-17T02:40:40+05:30`
- Commit subject: fix: repair later-batch citation targets
- Audit date: `2026-07-16`
- Scope: every tracked file at the recorded commit; `.git` internals excluded.

## Corpus totals

| Metric | Count | Interpretation |
| --- | ---: | --- |
| Tracked files | 645 | Complete inventory below |
| Repository content bytes | 608,647 | Excludes Git objects |
| Lines | 23,620 | Markdown, YAML, README, and license |
| Word tokens by regex | 71,482 | Editorial sizing only |
| Topic directories | 40 | Every directory has a metadata record |
| Markdown files | 534 | Includes README and source policy |
| YAML files | 110 | Metadata and graph records |
| Topic Markdown missing required front matter | 220 | Contract failure concentrated in 20 later-batch topics |
| Explicit equation records | 15 | Equation names in metadata are targets, not verified equation records |
| Markdown table objects | 15 | Mostly terminology/schema tables |
| Image assets | 0 | No repository illustrations or photographs |
| Dataset payload assets | 0 | `datasets.md` files are catalogs, not data payloads |
| Mermaid or code-native diagrams | 0 | No existing diagrams to reuse |
| Markdown image embeds | 0 | None |
| Explicit reaction-mechanism headings | 0 | Mechanisms must be researched before illustration |
| Unique URL mentions | 140 | Availability is not equivalent to claim support |
| Unique valid DOI strings | 53 | Duplicates across topic files collapsed |

### File types

| Extension | Files |
| --- | ---: |
| `.md` | 534 |
| `.yaml` | 110 |
| `[no extension]` | 1 |

## Topic package inventory

| Topic | Files | Required missing | Claims | Equations | Evidence blocks | Tables | URLs | DOI mentions | Missing front matter | Maturity signal |
| --- | ---: | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| `acids-and-bases` | 19 | None | 30 | 0 | 11 | 0 | 4 | 8 | 0 | Structured claim package |
| `analytical-chemistry` | 19 | None | 13 | 1 | 11 | 1 | 7 | 8 | 0 | Structured claim package |
| `atmospheric-chemistry` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 5 | 2 | 11 | Source-anchor / queue package |
| `atomic-structure` | 17 | None | 14 | 1 | 6 | 1 | 4 | 3 | 0 | Structured claim package |
| `biochemistry` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 4 | 0 | 11 | Source-anchor / queue package |
| `catalysis` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 6 | 5 | 11 | Source-anchor / queue package |
| `chemical-bonding` | 17 | None | 18 | 0 | 7 | 1 | 6 | 2 | 0 | Structured claim package |
| `chemical-engineering` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 3 | 0 | 11 | Source-anchor / queue package |
| `chemical-equilibrium` | 17 | None | 30 | 0 | 8 | 0 | 1 | 0 | 0 | Structured claim package |
| `chemical-kinetics` | 16 | None | 30 | 0 | 7 | 0 | 3 | 7 | 0 | Structured claim package |
| `chemical-thermodynamics` | 16 | None | 30 | 0 | 9 | 0 | 5 | 8 | 0 | Structured claim package |
| `cheminformatics` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 6 | 2 | 11 | Source-anchor / queue package |
| `chromatography` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 2 | 2 | 11 | Source-anchor / queue package |
| `clinical-chemistry` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 3 | 0 | 11 | Source-anchor / queue package |
| `coordination-chemistry` | 19 | None | 10 | 1 | 9 | 1 | 3 | 6 | 0 | Structured claim package |
| `crystallography` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 1 | 0 | 11 | Source-anchor / queue package |
| `ecotoxicology` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 4 | 2 | 11 | Source-anchor / queue package |
| `electrochemistry` | 19 | None | 9 | 2 | 12 | 1 | 4 | 12 | 0 | Structured claim package |
| `environmental-chemistry` | 19 | None | 10 | 1 | 14 | 1 | 4 | 0 | 0 | Structured claim package |
| `food-chemistry` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 4 | 0 | 11 | Source-anchor / queue package |
| `green-chemistry` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 3 | 1 | 11 | Source-anchor / queue package |
| `inorganic-chemistry` | 19 | None | 8 | 1 | 13 | 1 | 5 | 0 | 0 | Structured claim package |
| `laboratory-safety` | 19 | None | 8 | 0 | 15 | 1 | 5 | 0 | 0 | Structured claim package |
| `mass-spectrometry` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 5 | 2 | 11 | Source-anchor / queue package |
| `materials-chemistry` | 19 | None | 10 | 1 | 14 | 1 | 4 | 7 | 0 | Structured claim package |
| `medicinal-chemistry` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 3 | 0 | 11 | Source-anchor / queue package |
| `nuclear-chemistry` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 1 | 2 | 11 | Source-anchor / queue package |
| `organic-chemistry` | 19 | None | 11 | 1 | 15 | 1 | 8 | 11 | 0 | Structured claim package |
| `periodic-table` | 18 | None | 15 | 0 | 8 | 1 | 5 | 1 | 0 | Structured claim package |
| `photochemistry` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 7 | 4 | 11 | Source-anchor / queue package |
| `polymer-chemistry` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 6 | 3 | 11 | Source-anchor / queue package |
| `quantum-chemistry` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 6 | 3 | 11 | Source-anchor / queue package |
| `solubility` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 4 | 2 | 11 | Source-anchor / queue package |
| `solutions-and-colloids` | 19 | None | 11 | 1 | 12 | 1 | 4 | 12 | 0 | Structured claim package |
| `spectroscopy` | 19 | None | 11 | 2 | 12 | 1 | 6 | 12 | 0 | Structured claim package |
| `statistical-mechanics` | 19 | None | 30 | 0 | 8 | 0 | 3 | 4 | 0 | Structured claim package |
| `stoichiometry` | 19 | None | 15 | 1 | 9 | 1 | 7 | 1 | 0 | Structured claim package |
| `surface-chemistry` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 3 | 2 | 11 | Source-anchor / queue package |
| `thermochemistry` | 19 | None | 17 | 2 | 10 | 1 | 6 | 4 | 0 | Structured claim package |
| `toxicology` | 13 | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 0 | 0 | 0 | 0 | 3 | 0 | 11 | Source-anchor / queue package |

## Duplicate and redundancy audit

- Exact duplicate groups: **3** groups covering **20** files.
- Normalized duplicate groups: **24** groups covering **94** files. Normalization removes front matter, topic names, and evidence identifiers; these groups indicate template-level repetition, not necessarily byte identity.
- No filenames identify standalone articles or `Copy of` article records. Duplicate-content findings below are therefore file-section duplication, not duplicate article editions.

### Exact duplicate groups

1. `research/acids-and-bases/quality-score.yaml`; `research/atomic-structure/quality-score.yaml`; `research/chemical-bonding/quality-score.yaml`; `research/chemical-equilibrium/quality-score.yaml`; `research/chemical-kinetics/quality-score.yaml`; `research/chemical-thermodynamics/quality-score.yaml`; `research/periodic-table/quality-score.yaml`; `research/statistical-mechanics/quality-score.yaml`; `research/stoichiometry/quality-score.yaml`; `research/thermochemistry/quality-score.yaml`
2. `research/analytical-chemistry/quality-score.yaml`; `research/electrochemistry/quality-score.yaml`; `research/organic-chemistry/quality-score.yaml`; `research/solutions-and-colloids/quality-score.yaml`; `research/spectroscopy/quality-score.yaml`
3. `research/coordination-chemistry/quality-score.yaml`; `research/environmental-chemistry/quality-score.yaml`; `research/inorganic-chemistry/quality-score.yaml`; `research/laboratory-safety/quality-score.yaml`; `research/materials-chemistry/quality-score.yaml`

### Normalized duplicate groups

1. `research/acids-and-bases/quality-score.yaml`; `research/atomic-structure/quality-score.yaml`; `research/chemical-bonding/quality-score.yaml`; `research/chemical-equilibrium/quality-score.yaml`; `research/chemical-kinetics/quality-score.yaml`; `research/chemical-thermodynamics/quality-score.yaml`; `research/periodic-table/quality-score.yaml`; `research/statistical-mechanics/quality-score.yaml`; `research/stoichiometry/quality-score.yaml`; `research/thermochemistry/quality-score.yaml`
2. `research/analytical-chemistry/common-misconceptions.md`; `research/coordination-chemistry/common-misconceptions.md`; `research/electrochemistry/common-misconceptions.md`; `research/environmental-chemistry/common-misconceptions.md`; `research/inorganic-chemistry/common-misconceptions.md`; `research/laboratory-safety/common-misconceptions.md`; `research/materials-chemistry/common-misconceptions.md`; `research/organic-chemistry/common-misconceptions.md`; `research/solutions-and-colloids/common-misconceptions.md`; `research/spectroscopy/common-misconceptions.md`
3. `research/analytical-chemistry/history.md`; `research/electrochemistry/history.md`; `research/environmental-chemistry/history.md`; `research/materials-chemistry/history.md`; `research/organic-chemistry/history.md`; `research/spectroscopy/history.md`
4. `research/analytical-chemistry/industrial.md`; `research/coordination-chemistry/industrial.md`; `research/environmental-chemistry/industrial.md`
5. `research/analytical-chemistry/mathematics.md`; `research/organic-chemistry/mathematics.md`; `research/solutions-and-colloids/mathematics.md`; `research/spectroscopy/mathematics.md`
6. `research/analytical-chemistry/quality-score.yaml`; `research/electrochemistry/quality-score.yaml`; `research/organic-chemistry/quality-score.yaml`; `research/solutions-and-colloids/quality-score.yaml`; `research/spectroscopy/quality-score.yaml`
7. `research/atomic-structure/common-misconceptions.md`; `research/chemical-bonding/common-misconceptions.md`; `research/periodic-table/common-misconceptions.md`; `research/stoichiometry/common-misconceptions.md`; `research/thermochemistry/common-misconceptions.md`
8. `research/atomic-structure/research-frontier.md`; `research/chemical-bonding/research-frontier.md`; `research/periodic-table/research-frontier.md`; `research/stoichiometry/research-frontier.md`; `research/thermochemistry/research-frontier.md`
9. `research/chemical-bonding/equations.md`; `research/periodic-table/equations.md`
10. `research/chemical-bonding/industrial.md`; `research/periodic-table/industrial.md`
11. `research/chemical-bonding/laboratory.md`; `research/stoichiometry/laboratory.md`
12. `research/chemical-kinetics/applications.md`; `research/chemical-thermodynamics/applications.md`; `research/statistical-mechanics/applications.md`
13. `research/chemical-kinetics/common-misconceptions.md`; `research/chemical-thermodynamics/common-misconceptions.md`; `research/statistical-mechanics/common-misconceptions.md`
14. `research/chemical-kinetics/equations.md`; `research/chemical-thermodynamics/equations.md`; `research/statistical-mechanics/equations.md`
15. `research/chemical-kinetics/fundamentals.md`; `research/chemical-thermodynamics/fundamentals.md`; `research/statistical-mechanics/fundamentals.md`
16. `research/chemical-kinetics/history.md`; `research/chemical-thermodynamics/history.md`; `research/statistical-mechanics/history.md`
17. `research/chemical-kinetics/industrial.md`; `research/chemical-thermodynamics/industrial.md`; `research/statistical-mechanics/industrial.md`
18. `research/chemical-kinetics/laboratory.md`; `research/chemical-thermodynamics/laboratory.md`; `research/statistical-mechanics/laboratory.md`
19. `research/chemical-kinetics/mathematics.md`; `research/chemical-thermodynamics/mathematics.md`; `research/statistical-mechanics/mathematics.md`
20. `research/chemical-kinetics/terminology.md`; `research/chemical-thermodynamics/terminology.md`; `research/statistical-mechanics/terminology.md`
21. `research/coordination-chemistry/laboratory.md`; `research/inorganic-chemistry/laboratory.md`; `research/materials-chemistry/laboratory.md`; `research/solutions-and-colloids/laboratory.md`
22. `research/coordination-chemistry/quality-score.yaml`; `research/environmental-chemistry/quality-score.yaml`; `research/inorganic-chemistry/quality-score.yaml`; `research/laboratory-safety/quality-score.yaml`; `research/materials-chemistry/quality-score.yaml`
23. `research/inorganic-chemistry/datasets.md`; `research/laboratory-safety/datasets.md`
24. `research/stoichiometry/history.md`; `research/thermochemistry/history.md`

## Orphan and broken-reference classification

| Class | Finding |
| --- | --- |
| Orphan topic directories | None: all 40 topic slugs occur in repository graph node files. |
| Orphan infrastructure | None: README, license, source policy, and graph batches are repository-level infrastructure. |
| Orphan assets | None because there are no binary assets. |
| Broken local evidence references | No undefined evidence IDs were detected in claim `Evidence:` fields. |
| Duplicate evidence identifiers | Present across multiple files within 9 topics; violates the ‘store evidence once’ contract and must be canonicalized. |
| Semantic citation mismatches | 0 source/link-domain mismatch mentions across 0 files after the later-batch repair. |
| Graph endpoint defect | `quantum-mechanics` is referenced by an edge but absent from all repository node files. |

## Complete per-file inventory

| # | Path | Topic / role | Section | Bytes | Words | Front matter / status | Claims | Equations | Evidence | Tables | URLs | DOIs | Audit flags |
| ---: | --- | --- | --- | ---: | ---: | --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| 1 | `LICENSE` | repository root | LICENSE | 1060 | 169 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 2 | `README.md` | repository root | README.md | 1922 | 254 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 3 | `research/acids-and-bases/applications.md` | acids-and-bases | applications | 791 | 100 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 4 | `research/acids-and-bases/common-misconceptions.md` | acids-and-bases | common-misconceptions | 900 | 122 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 5 | `research/acids-and-bases/datasets.md` | acids-and-bases | datasets | 1246 | 167 | draft | 0 | 0 | 3 | 0 | 3 | 2 | None |
| 6 | `research/acids-and-bases/equations.md` | acids-and-bases | equations | 750 | 104 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 7 | `research/acids-and-bases/fundamentals.md` | acids-and-bases | fundamentals | 920 | 123 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 8 | `research/acids-and-bases/graph.yaml` | acids-and-bases | graph | 782 | 84 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 9 | `research/acids-and-bases/history.md` | acids-and-bases | history | 862 | 115 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 10 | `research/acids-and-bases/industrial.md` | acids-and-bases | industrial | 853 | 110 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 11 | `research/acids-and-bases/laboratory.md` | acids-and-bases | laboratory | 856 | 113 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 12 | `research/acids-and-bases/mathematics.md` | acids-and-bases | mathematics | 897 | 120 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 13 | `research/acids-and-bases/metadata.yaml` | acids-and-bases | metadata | 1391 | 134 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 14 | `research/acids-and-bases/overview.md` | acids-and-bases | overview | 965 | 132 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 15 | `research/acids-and-bases/primary-literature.md` | acids-and-bases | primary-literature | 832 | 108 | draft | 0 | 0 | 1 | 0 | 0 | 0 | None |
| 16 | `research/acids-and-bases/quality-score.yaml` | acids-and-bases | quality-score | 718 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 17 | `research/acids-and-bases/references.md` | acids-and-bases | references | 1450 | 191 | draft | 0 | 0 | 4 | 0 | 4 | 3 | None |
| 18 | `research/acids-and-bases/research-frontier.md` | acids-and-bases | research-frontier | 881 | 116 | draft | 0 | 0 | 1 | 0 | 1 | 1 | unfinished/queue content |
| 19 | `research/acids-and-bases/research-queue.md` | acids-and-bases | research-queue | 806 | 108 | in_progress | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 20 | `research/acids-and-bases/standards.md` | acids-and-bases | standards | 941 | 125 | draft | 0 | 0 | 2 | 0 | 2 | 2 | None |
| 21 | `research/acids-and-bases/terminology.md` | acids-and-bases | terminology | 741 | 104 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 22 | `research/analytical-chemistry/applications.md` | analytical-chemistry | applications | 516 | 56 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 23 | `research/analytical-chemistry/common-misconceptions.md` | analytical-chemistry | common-misconceptions | 366 | 42 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 24 | `research/analytical-chemistry/datasets.md` | analytical-chemistry | datasets | 714 | 92 | draft | 0 | 0 | 1 | 0 | 1 | 1 | None |
| 25 | `research/analytical-chemistry/equations.md` | analytical-chemistry | equations | 554 | 61 | draft | 0 | 1 | 0 | 0 | 0 | 0 | None |
| 26 | `research/analytical-chemistry/fundamentals.md` | analytical-chemistry | fundamentals | 483 | 53 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 27 | `research/analytical-chemistry/graph.yaml` | analytical-chemistry | graph | 715 | 67 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 28 | `research/analytical-chemistry/history.md` | analytical-chemistry | history | 912 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 29 | `research/analytical-chemistry/industrial.md` | analytical-chemistry | industrial | 927 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 30 | `research/analytical-chemistry/laboratory.md` | analytical-chemistry | laboratory | 575 | 64 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 31 | `research/analytical-chemistry/mathematics.md` | analytical-chemistry | mathematics | 932 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 32 | `research/analytical-chemistry/metadata.yaml` | analytical-chemistry | metadata | 1318 | 120 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 33 | `research/analytical-chemistry/overview.md` | analytical-chemistry | overview | 498 | 57 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 34 | `research/analytical-chemistry/primary-literature.md` | analytical-chemistry | primary-literature | 559 | 58 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 35 | `research/analytical-chemistry/quality-score.yaml` | analytical-chemistry | quality-score | 727 | 78 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 36 | `research/analytical-chemistry/references.md` | analytical-chemistry | references | 2424 | 327 | draft | 0 | 0 | 5 | 0 | 5 | 4 | None |
| 37 | `research/analytical-chemistry/research-frontier.md` | analytical-chemistry | research-frontier | 1484 | 183 | draft | 0 | 0 | 2 | 0 | 2 | 0 | unfinished/queue content |
| 38 | `research/analytical-chemistry/research-queue.md` | analytical-chemistry | research-queue | 785 | 82 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 39 | `research/analytical-chemistry/standards.md` | analytical-chemistry | standards | 1700 | 225 | draft | 0 | 0 | 3 | 0 | 2 | 3 | None |
| 40 | `research/analytical-chemistry/terminology.md` | analytical-chemistry | terminology | 1427 | 155 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 41 | `research/atmospheric-chemistry/applications.md` | atmospheric-chemistry | applications | 962 | 104 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 42 | `research/atmospheric-chemistry/fundamentals.md` | atmospheric-chemistry | fundamentals | 998 | 120 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 43 | `research/atmospheric-chemistry/graph.yaml` | atmospheric-chemistry | graph | 898 | 78 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 44 | `research/atmospheric-chemistry/history.md` | atmospheric-chemistry | history | 983 | 125 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 45 | `research/atmospheric-chemistry/industrial.md` | atmospheric-chemistry | industrial | 890 | 101 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 46 | `research/atmospheric-chemistry/laboratory.md` | atmospheric-chemistry | laboratory | 576 | 63 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 47 | `research/atmospheric-chemistry/mathematics.md` | atmospheric-chemistry | mathematics | 649 | 75 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 48 | `research/atmospheric-chemistry/metadata.yaml` | atmospheric-chemistry | metadata | 1035 | 89 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 49 | `research/atmospheric-chemistry/overview.md` | atmospheric-chemistry | overview | 895 | 107 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 50 | `research/atmospheric-chemistry/primary-literature.md` | atmospheric-chemistry | primary-literature | 660 | 79 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 51 | `research/atmospheric-chemistry/references.md` | atmospheric-chemistry | references | 883 | 115 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 52 | `research/atmospheric-chemistry/research-frontier.md` | atmospheric-chemistry | research-frontier | 875 | 106 | missing | 0 | 0 | 0 | 0 | 1 | 1 | missing front matter; unfinished/queue content |
| 53 | `research/atmospheric-chemistry/standards.md` | atmospheric-chemistry | standards | 969 | 127 | missing | 0 | 0 | 0 | 0 | 1 | 1 | missing front matter |
| 54 | `research/atomic-structure/applications.md` | atomic-structure | applications | 430 | 50 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 55 | `research/atomic-structure/common-misconceptions.md` | atomic-structure | common-misconceptions | 455 | 50 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 56 | `research/atomic-structure/datasets.md` | atomic-structure | datasets | 1072 | 139 | draft | 0 | 0 | 2 | 0 | 1 | 1 | None |
| 57 | `research/atomic-structure/equations.md` | atomic-structure | equations | 622 | 84 | draft | 0 | 1 | 0 | 0 | 0 | 0 | None |
| 58 | `research/atomic-structure/fundamentals.md` | atomic-structure | fundamentals | 594 | 79 | draft | 2 | 0 | 0 | 0 | 0 | 0 | None |
| 59 | `research/atomic-structure/history.md` | atomic-structure | history | 488 | 60 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 60 | `research/atomic-structure/industrial.md` | atomic-structure | industrial | 387 | 47 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 61 | `research/atomic-structure/laboratory.md` | atomic-structure | laboratory | 469 | 57 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 62 | `research/atomic-structure/mathematics.md` | atomic-structure | mathematics | 568 | 79 | draft | 2 | 0 | 0 | 0 | 0 | 0 | None |
| 63 | `research/atomic-structure/metadata.yaml` | atomic-structure | metadata | 1584 | 162 | not required | 0 | 0 | 0 | 0 | 0 | 0 | duplicate YAML key: related_topics |
| 64 | `research/atomic-structure/overview.md` | atomic-structure | overview | 852 | 105 | draft | 2 | 0 | 0 | 0 | 0 | 0 | None |
| 65 | `research/atomic-structure/primary-literature.md` | atomic-structure | primary-literature | 1190 | 161 | draft | 1 | 0 | 1 | 0 | 1 | 0 | unfinished/queue content |
| 66 | `research/atomic-structure/quality-score.yaml` | atomic-structure | quality-score | 718 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 67 | `research/atomic-structure/references.md` | atomic-structure | references | 2108 | 280 | draft | 0 | 0 | 3 | 0 | 3 | 2 | unfinished/queue content |
| 68 | `research/atomic-structure/research-frontier.md` | atomic-structure | research-frontier | 862 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 69 | `research/atomic-structure/research-queue.md` | atomic-structure | research-queue | 1330 | 151 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 70 | `research/atomic-structure/terminology.md` | atomic-structure | terminology | 837 | 96 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 71 | `research/biochemistry/applications.md` | biochemistry | applications | 684 | 76 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 72 | `research/biochemistry/fundamentals.md` | biochemistry | fundamentals | 977 | 110 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 73 | `research/biochemistry/graph.yaml` | biochemistry | graph | 807 | 74 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 74 | `research/biochemistry/history.md` | biochemistry | history | 915 | 107 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 75 | `research/biochemistry/industrial.md` | biochemistry | industrial | 553 | 54 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 76 | `research/biochemistry/laboratory.md` | biochemistry | laboratory | 609 | 68 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 77 | `research/biochemistry/mathematics.md` | biochemistry | mathematics | 658 | 75 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 78 | `research/biochemistry/metadata.yaml` | biochemistry | metadata | 1009 | 86 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 79 | `research/biochemistry/overview.md` | biochemistry | overview | 874 | 108 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 80 | `research/biochemistry/primary-literature.md` | biochemistry | primary-literature | 665 | 71 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 81 | `research/biochemistry/references.md` | biochemistry | references | 1373 | 171 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter; unfinished/queue content |
| 82 | `research/biochemistry/research-frontier.md` | biochemistry | research-frontier | 1120 | 124 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 83 | `research/biochemistry/standards.md` | biochemistry | standards | 1389 | 178 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter |
| 84 | `research/catalysis/applications.md` | catalysis | applications | 1365 | 161 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter |
| 85 | `research/catalysis/fundamentals.md` | catalysis | fundamentals | 1012 | 126 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 86 | `research/catalysis/graph.yaml` | catalysis | graph | 780 | 70 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 87 | `research/catalysis/history.md` | catalysis | history | 610 | 67 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 88 | `research/catalysis/industrial.md` | catalysis | industrial | 867 | 100 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 89 | `research/catalysis/laboratory.md` | catalysis | laboratory | 818 | 95 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 90 | `research/catalysis/mathematics.md` | catalysis | mathematics | 649 | 76 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 91 | `research/catalysis/metadata.yaml` | catalysis | metadata | 1095 | 95 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 92 | `research/catalysis/overview.md` | catalysis | overview | 732 | 91 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 93 | `research/catalysis/primary-literature.md` | catalysis | primary-literature | 672 | 80 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 94 | `research/catalysis/references.md` | catalysis | references | 1629 | 233 | missing | 0 | 0 | 0 | 0 | 4 | 0 | missing front matter |
| 95 | `research/catalysis/research-frontier.md` | catalysis | research-frontier | 1820 | 236 | missing | 0 | 0 | 0 | 0 | 3 | 3 | missing front matter |
| 96 | `research/catalysis/standards.md` | catalysis | standards | 951 | 136 | missing | 0 | 0 | 0 | 0 | 2 | 2 | missing front matter |
| 97 | `research/chemical-bonding/applications.md` | chemical-bonding | applications | 439 | 54 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 98 | `research/chemical-bonding/common-misconceptions.md` | chemical-bonding | common-misconceptions | 455 | 50 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 99 | `research/chemical-bonding/datasets.md` | chemical-bonding | datasets | 1084 | 139 | draft | 0 | 0 | 2 | 0 | 1 | 1 | None |
| 100 | `research/chemical-bonding/equations.md` | chemical-bonding | equations | 329 | 41 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 101 | `research/chemical-bonding/fundamentals.md` | chemical-bonding | fundamentals | 835 | 105 | draft | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 102 | `research/chemical-bonding/history.md` | chemical-bonding | history | 433 | 53 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 103 | `research/chemical-bonding/industrial.md` | chemical-bonding | industrial | 848 | 106 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 104 | `research/chemical-bonding/laboratory.md` | chemical-bonding | laboratory | 848 | 106 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 105 | `research/chemical-bonding/mathematics.md` | chemical-bonding | mathematics | 613 | 83 | draft | 2 | 0 | 0 | 0 | 0 | 0 | None |
| 106 | `research/chemical-bonding/metadata.yaml` | chemical-bonding | metadata | 1557 | 152 | not required | 0 | 0 | 0 | 0 | 0 | 0 | duplicate YAML key: related_topics |
| 107 | `research/chemical-bonding/overview.md` | chemical-bonding | overview | 871 | 108 | draft | 2 | 0 | 0 | 0 | 0 | 0 | None |
| 108 | `research/chemical-bonding/primary-literature.md` | chemical-bonding | primary-literature | 1475 | 198 | draft | 0 | 0 | 2 | 0 | 2 | 1 | None |
| 109 | `research/chemical-bonding/quality-score.yaml` | chemical-bonding | quality-score | 718 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 110 | `research/chemical-bonding/references.md` | chemical-bonding | references | 1823 | 229 | draft | 0 | 0 | 3 | 0 | 3 | 0 | unfinished/queue content |
| 111 | `research/chemical-bonding/research-frontier.md` | chemical-bonding | research-frontier | 862 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 112 | `research/chemical-bonding/research-queue.md` | chemical-bonding | research-queue | 1173 | 132 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 113 | `research/chemical-bonding/terminology.md` | chemical-bonding | terminology | 798 | 98 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 114 | `research/chemical-engineering/applications.md` | chemical-engineering | applications | 933 | 104 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 115 | `research/chemical-engineering/fundamentals.md` | chemical-engineering | fundamentals | 1097 | 121 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 116 | `research/chemical-engineering/graph.yaml` | chemical-engineering | graph | 877 | 82 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 117 | `research/chemical-engineering/history.md` | chemical-engineering | history | 1009 | 125 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 118 | `research/chemical-engineering/industrial.md` | chemical-engineering | industrial | 834 | 95 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 119 | `research/chemical-engineering/laboratory.md` | chemical-engineering | laboratory | 623 | 66 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 120 | `research/chemical-engineering/mathematics.md` | chemical-engineering | mathematics | 953 | 98 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 121 | `research/chemical-engineering/metadata.yaml` | chemical-engineering | metadata | 1079 | 95 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 122 | `research/chemical-engineering/overview.md` | chemical-engineering | overview | 974 | 114 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 123 | `research/chemical-engineering/primary-literature.md` | chemical-engineering | primary-literature | 624 | 76 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 124 | `research/chemical-engineering/references.md` | chemical-engineering | references | 885 | 114 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 125 | `research/chemical-engineering/research-frontier.md` | chemical-engineering | research-frontier | 932 | 108 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 126 | `research/chemical-engineering/standards-and-handbooks.md` | chemical-engineering | standards-and-handbooks | 1055 | 136 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 127 | `research/chemical-equilibrium/applications.md` | chemical-equilibrium | applications | 744 | 84 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 128 | `research/chemical-equilibrium/common-misconceptions.md` | chemical-equilibrium | common-misconceptions | 899 | 112 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 129 | `research/chemical-equilibrium/equations.md` | chemical-equilibrium | equations | 826 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 130 | `research/chemical-equilibrium/fundamentals.md` | chemical-equilibrium | fundamentals | 791 | 104 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 131 | `research/chemical-equilibrium/history.md` | chemical-equilibrium | history | 771 | 97 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 132 | `research/chemical-equilibrium/industrial.md` | chemical-equilibrium | industrial | 771 | 94 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 133 | `research/chemical-equilibrium/laboratory.md` | chemical-equilibrium | laboratory | 814 | 95 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 134 | `research/chemical-equilibrium/mathematics.md` | chemical-equilibrium | mathematics | 792 | 103 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 135 | `research/chemical-equilibrium/metadata.yaml` | chemical-equilibrium | metadata | 1343 | 132 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 136 | `research/chemical-equilibrium/overview.md` | chemical-equilibrium | overview | 865 | 106 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 137 | `research/chemical-equilibrium/primary-literature.md` | chemical-equilibrium | primary-literature | 1001 | 134 | draft | 0 | 0 | 1 | 0 | 1 | 0 | unfinished/queue content |
| 138 | `research/chemical-equilibrium/quality-score.yaml` | chemical-equilibrium | quality-score | 718 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 139 | `research/chemical-equilibrium/references.md` | chemical-equilibrium | references | 1344 | 176 | draft | 0 | 0 | 3 | 0 | 1 | 0 | None |
| 140 | `research/chemical-equilibrium/research-frontier.md` | chemical-equilibrium | research-frontier | 1245 | 142 | draft | 0 | 0 | 2 | 0 | 0 | 0 | None |
| 141 | `research/chemical-equilibrium/research-queue.md` | chemical-equilibrium | research-queue | 765 | 87 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 142 | `research/chemical-equilibrium/standards.md` | chemical-equilibrium | standards | 1079 | 129 | draft | 0 | 0 | 2 | 0 | 0 | 0 | None |
| 143 | `research/chemical-equilibrium/terminology.md` | chemical-equilibrium | terminology | 783 | 98 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 144 | `research/chemical-kinetics/applications.md` | chemical-kinetics | applications | 876 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 145 | `research/chemical-kinetics/common-misconceptions.md` | chemical-kinetics | common-misconceptions | 894 | 110 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 146 | `research/chemical-kinetics/equations.md` | chemical-kinetics | equations | 870 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 147 | `research/chemical-kinetics/fundamentals.md` | chemical-kinetics | fundamentals | 876 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 148 | `research/chemical-kinetics/history.md` | chemical-kinetics | history | 866 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 149 | `research/chemical-kinetics/industrial.md` | chemical-kinetics | industrial | 872 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 150 | `research/chemical-kinetics/laboratory.md` | chemical-kinetics | laboratory | 872 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 151 | `research/chemical-kinetics/mathematics.md` | chemical-kinetics | mathematics | 874 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 152 | `research/chemical-kinetics/metadata.yaml` | chemical-kinetics | metadata | 1328 | 129 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 153 | `research/chemical-kinetics/overview.md` | chemical-kinetics | overview | 832 | 104 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 154 | `research/chemical-kinetics/primary-literature.md` | chemical-kinetics | primary-literature | 1103 | 137 | draft | 0 | 0 | 1 | 0 | 1 | 1 | None |
| 155 | `research/chemical-kinetics/quality-score.yaml` | chemical-kinetics | quality-score | 718 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 156 | `research/chemical-kinetics/references.md` | chemical-kinetics | references | 1788 | 244 | draft | 0 | 0 | 3 | 0 | 3 | 3 | None |
| 157 | `research/chemical-kinetics/research-frontier.md` | chemical-kinetics | research-frontier | 1905 | 263 | draft | 0 | 0 | 3 | 0 | 3 | 3 | None |
| 158 | `research/chemical-kinetics/research-queue.md` | chemical-kinetics | research-queue | 759 | 87 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 159 | `research/chemical-kinetics/terminology.md` | chemical-kinetics | terminology | 874 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 160 | `research/chemical-thermodynamics/applications.md` | chemical-thermodynamics | applications | 906 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 161 | `research/chemical-thermodynamics/common-misconceptions.md` | chemical-thermodynamics | common-misconceptions | 924 | 110 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 162 | `research/chemical-thermodynamics/equations.md` | chemical-thermodynamics | equations | 900 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 163 | `research/chemical-thermodynamics/fundamentals.md` | chemical-thermodynamics | fundamentals | 906 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 164 | `research/chemical-thermodynamics/history.md` | chemical-thermodynamics | history | 896 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 165 | `research/chemical-thermodynamics/industrial.md` | chemical-thermodynamics | industrial | 902 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 166 | `research/chemical-thermodynamics/laboratory.md` | chemical-thermodynamics | laboratory | 902 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 167 | `research/chemical-thermodynamics/mathematics.md` | chemical-thermodynamics | mathematics | 904 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 168 | `research/chemical-thermodynamics/metadata.yaml` | chemical-thermodynamics | metadata | 1369 | 136 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 169 | `research/chemical-thermodynamics/overview.md` | chemical-thermodynamics | overview | 835 | 104 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 170 | `research/chemical-thermodynamics/quality-score.yaml` | chemical-thermodynamics | quality-score | 718 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 171 | `research/chemical-thermodynamics/references.md` | chemical-thermodynamics | references | 1469 | 189 | draft | 0 | 0 | 3 | 0 | 3 | 3 | None |
| 172 | `research/chemical-thermodynamics/research-frontier.md` | chemical-thermodynamics | research-frontier | 1629 | 209 | draft | 0 | 0 | 3 | 0 | 3 | 3 | None |
| 173 | `research/chemical-thermodynamics/research-queue.md` | chemical-thermodynamics | research-queue | 771 | 87 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 174 | `research/chemical-thermodynamics/standards.md` | chemical-thermodynamics | standards | 1468 | 191 | draft | 0 | 0 | 3 | 0 | 2 | 2 | None |
| 175 | `research/chemical-thermodynamics/terminology.md` | chemical-thermodynamics | terminology | 904 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 176 | `research/cheminformatics/applications.md` | cheminformatics | applications | 919 | 104 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 177 | `research/cheminformatics/fundamentals.md` | cheminformatics | fundamentals | 1186 | 140 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter |
| 178 | `research/cheminformatics/graph.yaml` | cheminformatics | graph | 849 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 179 | `research/cheminformatics/history.md` | cheminformatics | history | 991 | 122 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 180 | `research/cheminformatics/industrial.md` | cheminformatics | industrial | 820 | 91 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 181 | `research/cheminformatics/laboratory.md` | cheminformatics | laboratory | 959 | 117 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 182 | `research/cheminformatics/mathematics.md` | cheminformatics | mathematics | 619 | 63 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 183 | `research/cheminformatics/metadata.yaml` | cheminformatics | metadata | 946 | 80 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 184 | `research/cheminformatics/overview.md` | cheminformatics | overview | 1014 | 123 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 185 | `research/cheminformatics/primary-literature.md` | cheminformatics | primary-literature | 922 | 115 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 186 | `research/cheminformatics/references.md` | cheminformatics | references | 1561 | 213 | missing | 0 | 0 | 0 | 0 | 4 | 0 | missing front matter; unfinished/queue content |
| 187 | `research/cheminformatics/research-frontier.md` | cheminformatics | research-frontier | 1508 | 182 | missing | 0 | 0 | 0 | 0 | 2 | 1 | missing front matter; unfinished/queue content |
| 188 | `research/cheminformatics/standards-and-datasets.md` | cheminformatics | standards-and-datasets | 1348 | 169 | missing | 0 | 0 | 0 | 0 | 3 | 1 | missing front matter |
| 189 | `research/chromatography/applications.md` | chromatography | applications | 861 | 93 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 190 | `research/chromatography/fundamentals.md` | chromatography | fundamentals | 921 | 101 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 191 | `research/chromatography/graph.yaml` | chromatography | graph | 802 | 73 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 192 | `research/chromatography/history.md` | chromatography | history | 626 | 66 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 193 | `research/chromatography/industrial.md` | chromatography | industrial | 758 | 83 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 194 | `research/chromatography/laboratory.md` | chromatography | laboratory | 585 | 62 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 195 | `research/chromatography/mathematics.md` | chromatography | mathematics | 575 | 64 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 196 | `research/chromatography/metadata.yaml` | chromatography | metadata | 1016 | 86 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 197 | `research/chromatography/overview.md` | chromatography | overview | 651 | 73 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 198 | `research/chromatography/primary-literature.md` | chromatography | primary-literature | 637 | 67 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 199 | `research/chromatography/references.md` | chromatography | references | 849 | 115 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 200 | `research/chromatography/research-frontier.md` | chromatography | research-frontier | 836 | 88 | missing | 0 | 0 | 0 | 0 | 1 | 1 | missing front matter; unfinished/queue content |
| 201 | `research/chromatography/standards.md` | chromatography | standards | 973 | 119 | missing | 0 | 0 | 0 | 0 | 1 | 1 | missing front matter |
| 202 | `research/clinical-chemistry/applications.md` | clinical-chemistry | applications | 892 | 103 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 203 | `research/clinical-chemistry/fundamentals.md` | clinical-chemistry | fundamentals | 1066 | 131 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 204 | `research/clinical-chemistry/graph.yaml` | clinical-chemistry | graph | 854 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 205 | `research/clinical-chemistry/history.md` | clinical-chemistry | history | 1069 | 136 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 206 | `research/clinical-chemistry/industrial.md` | clinical-chemistry | industrial | 825 | 99 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 207 | `research/clinical-chemistry/laboratory.md` | clinical-chemistry | laboratory | 906 | 104 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 208 | `research/clinical-chemistry/mathematics.md` | clinical-chemistry | mathematics | 939 | 119 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 209 | `research/clinical-chemistry/metadata.yaml` | clinical-chemistry | metadata | 992 | 83 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 210 | `research/clinical-chemistry/overview.md` | clinical-chemistry | overview | 1100 | 138 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 211 | `research/clinical-chemistry/primary-literature.md` | clinical-chemistry | primary-literature | 717 | 86 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 212 | `research/clinical-chemistry/references.md` | clinical-chemistry | references | 1594 | 215 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter; unfinished/queue content |
| 213 | `research/clinical-chemistry/research-frontier.md` | clinical-chemistry | research-frontier | 1506 | 184 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 214 | `research/clinical-chemistry/standards.md` | clinical-chemistry | standards | 1388 | 198 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 215 | `research/coordination-chemistry/applications.md` | coordination-chemistry | applications | 520 | 57 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 216 | `research/coordination-chemistry/common-misconceptions.md` | coordination-chemistry | common-misconceptions | 370 | 42 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 217 | `research/coordination-chemistry/datasets.md` | coordination-chemistry | datasets | 623 | 84 | draft | 0 | 0 | 1 | 0 | 1 | 1 | None |
| 218 | `research/coordination-chemistry/equations.md` | coordination-chemistry | equations | 588 | 69 | draft | 0 | 1 | 0 | 0 | 0 | 0 | None |
| 219 | `research/coordination-chemistry/fundamentals.md` | coordination-chemistry | fundamentals | 423 | 52 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 220 | `research/coordination-chemistry/graph.yaml` | coordination-chemistry | graph | 864 | 78 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 221 | `research/coordination-chemistry/history.md` | coordination-chemistry | history | 764 | 87 | draft | 1 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 222 | `research/coordination-chemistry/industrial.md` | coordination-chemistry | industrial | 937 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 223 | `research/coordination-chemistry/laboratory.md` | coordination-chemistry | laboratory | 937 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 224 | `research/coordination-chemistry/mathematics.md` | coordination-chemistry | mathematics | 438 | 45 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 225 | `research/coordination-chemistry/metadata.yaml` | coordination-chemistry | metadata | 1296 | 125 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 226 | `research/coordination-chemistry/overview.md` | coordination-chemistry | overview | 428 | 50 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 227 | `research/coordination-chemistry/primary-literature.md` | coordination-chemistry | primary-literature | 1449 | 184 | draft | 0 | 0 | 2 | 0 | 2 | 1 | None |
| 228 | `research/coordination-chemistry/quality-score.yaml` | coordination-chemistry | quality-score | 712 | 77 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 229 | `research/coordination-chemistry/references.md` | coordination-chemistry | references | 1601 | 216 | draft | 0 | 0 | 3 | 0 | 3 | 2 | None |
| 230 | `research/coordination-chemistry/research-frontier.md` | coordination-chemistry | research-frontier | 1004 | 125 | draft | 0 | 0 | 1 | 0 | 1 | 1 | unfinished/queue content |
| 231 | `research/coordination-chemistry/research-queue.md` | coordination-chemistry | research-queue | 1076 | 115 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 232 | `research/coordination-chemistry/standards.md` | coordination-chemistry | standards | 1076 | 144 | draft | 0 | 0 | 2 | 0 | 2 | 1 | None |
| 233 | `research/coordination-chemistry/terminology.md` | coordination-chemistry | terminology | 1398 | 151 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 234 | `research/crystallography/applications.md` | crystallography | applications | 614 | 60 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 235 | `research/crystallography/fundamentals.md` | crystallography | fundamentals | 666 | 69 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 236 | `research/crystallography/graph.yaml` | crystallography | graph | 758 | 70 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 237 | `research/crystallography/history.md` | crystallography | history | 742 | 80 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 238 | `research/crystallography/industrial.md` | crystallography | industrial | 579 | 57 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 239 | `research/crystallography/laboratory.md` | crystallography | laboratory | 671 | 70 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 240 | `research/crystallography/mathematics.md` | crystallography | mathematics | 667 | 72 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 241 | `research/crystallography/metadata.yaml` | crystallography | metadata | 961 | 81 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 242 | `research/crystallography/overview.md` | crystallography | overview | 893 | 98 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 243 | `research/crystallography/primary-literature.md` | crystallography | primary-literature | 713 | 75 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 244 | `research/crystallography/references.md` | crystallography | references | 510 | 56 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 245 | `research/crystallography/research-frontier.md` | crystallography | research-frontier | 941 | 94 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 246 | `research/crystallography/standards.md` | crystallography | standards | 1197 | 138 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 247 | `research/ecotoxicology/applications.md` | ecotoxicology | applications | 937 | 113 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 248 | `research/ecotoxicology/fundamentals.md` | ecotoxicology | fundamentals | 1019 | 124 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 249 | `research/ecotoxicology/graph.yaml` | ecotoxicology | graph | 882 | 74 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 250 | `research/ecotoxicology/history.md` | ecotoxicology | history | 697 | 81 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 251 | `research/ecotoxicology/industrial.md` | ecotoxicology | industrial | 1022 | 114 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 252 | `research/ecotoxicology/laboratory.md` | ecotoxicology | laboratory | 683 | 74 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 253 | `research/ecotoxicology/mathematics.md` | ecotoxicology | mathematics | 650 | 70 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 254 | `research/ecotoxicology/metadata.yaml` | ecotoxicology | metadata | 1017 | 83 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 255 | `research/ecotoxicology/overview.md` | ecotoxicology | overview | 1069 | 127 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 256 | `research/ecotoxicology/primary-literature.md` | ecotoxicology | primary-literature | 637 | 75 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 257 | `research/ecotoxicology/references.md` | ecotoxicology | references | 1455 | 205 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter |
| 258 | `research/ecotoxicology/research-frontier.md` | ecotoxicology | research-frontier | 1431 | 178 | missing | 0 | 0 | 0 | 0 | 1 | 1 | missing front matter; unfinished/queue content |
| 259 | `research/ecotoxicology/standards.md` | ecotoxicology | standards | 1085 | 144 | missing | 0 | 0 | 0 | 0 | 1 | 1 | missing front matter |
| 260 | `research/electrochemistry/applications.md` | electrochemistry | applications | 451 | 48 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 261 | `research/electrochemistry/common-misconceptions.md` | electrochemistry | common-misconceptions | 358 | 40 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 262 | `research/electrochemistry/datasets.md` | electrochemistry | datasets | 1243 | 176 | draft | 0 | 0 | 2 | 0 | 1 | 2 | None |
| 263 | `research/electrochemistry/equations.md` | electrochemistry | equations | 913 | 124 | draft | 0 | 2 | 0 | 0 | 0 | 0 | None |
| 264 | `research/electrochemistry/fundamentals.md` | electrochemistry | fundamentals | 417 | 50 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 265 | `research/electrochemistry/graph.yaml` | electrochemistry | graph | 857 | 74 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 266 | `research/electrochemistry/history.md` | electrochemistry | history | 892 | 102 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 267 | `research/electrochemistry/industrial.md` | electrochemistry | industrial | 490 | 57 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 268 | `research/electrochemistry/laboratory.md` | electrochemistry | laboratory | 527 | 60 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 269 | `research/electrochemistry/mathematics.md` | electrochemistry | mathematics | 684 | 77 | draft | 1 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 270 | `research/electrochemistry/metadata.yaml` | electrochemistry | metadata | 1444 | 138 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 271 | `research/electrochemistry/overview.md` | electrochemistry | overview | 527 | 55 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 272 | `research/electrochemistry/primary-literature.md` | electrochemistry | primary-literature | 1555 | 204 | draft | 0 | 0 | 2 | 0 | 2 | 2 | None |
| 273 | `research/electrochemistry/quality-score.yaml` | electrochemistry | quality-score | 727 | 78 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 274 | `research/electrochemistry/references.md` | electrochemistry | references | 2095 | 282 | draft | 0 | 0 | 4 | 0 | 4 | 4 | None |
| 275 | `research/electrochemistry/research-frontier.md` | electrochemistry | research-frontier | 1014 | 121 | draft | 0 | 0 | 1 | 0 | 1 | 1 | None |
| 276 | `research/electrochemistry/research-queue.md` | electrochemistry | research-queue | 1008 | 114 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 277 | `research/electrochemistry/standards.md` | electrochemistry | standards | 1648 | 216 | draft | 0 | 0 | 3 | 0 | 1 | 3 | None |
| 278 | `research/electrochemistry/terminology.md` | electrochemistry | terminology | 1341 | 141 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 279 | `research/environmental-chemistry/applications.md` | environmental-chemistry | applications | 552 | 61 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 280 | `research/environmental-chemistry/common-misconceptions.md` | environmental-chemistry | common-misconceptions | 372 | 42 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 281 | `research/environmental-chemistry/datasets.md` | environmental-chemistry | datasets | 1592 | 184 | draft | 0 | 0 | 3 | 0 | 3 | 0 | None |
| 282 | `research/environmental-chemistry/equations.md` | environmental-chemistry | equations | 566 | 63 | draft | 0 | 1 | 0 | 0 | 0 | 0 | None |
| 283 | `research/environmental-chemistry/fundamentals.md` | environmental-chemistry | fundamentals | 476 | 55 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 284 | `research/environmental-chemistry/graph.yaml` | environmental-chemistry | graph | 934 | 86 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 285 | `research/environmental-chemistry/history.md` | environmental-chemistry | history | 945 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 286 | `research/environmental-chemistry/industrial.md` | environmental-chemistry | industrial | 960 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 287 | `research/environmental-chemistry/laboratory.md` | environmental-chemistry | laboratory | 670 | 75 | draft | 1 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 288 | `research/environmental-chemistry/mathematics.md` | environmental-chemistry | mathematics | 435 | 44 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 289 | `research/environmental-chemistry/metadata.yaml` | environmental-chemistry | metadata | 1360 | 126 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 290 | `research/environmental-chemistry/overview.md` | environmental-chemistry | overview | 513 | 55 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 291 | `research/environmental-chemistry/primary-literature.md` | environmental-chemistry | primary-literature | 1615 | 178 | draft | 0 | 0 | 2 | 0 | 2 | 0 | None |
| 292 | `research/environmental-chemistry/quality-score.yaml` | environmental-chemistry | quality-score | 712 | 77 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 293 | `research/environmental-chemistry/references.md` | environmental-chemistry | references | 2114 | 249 | draft | 0 | 0 | 4 | 0 | 4 | 0 | None |
| 294 | `research/environmental-chemistry/research-frontier.md` | environmental-chemistry | research-frontier | 2364 | 274 | draft | 0 | 0 | 4 | 0 | 4 | 0 | unfinished/queue content |
| 295 | `research/environmental-chemistry/research-queue.md` | environmental-chemistry | research-queue | 1130 | 114 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 296 | `research/environmental-chemistry/standards.md` | environmental-chemistry | standards | 777 | 94 | draft | 0 | 0 | 1 | 0 | 1 | 0 | None |
| 297 | `research/environmental-chemistry/terminology.md` | environmental-chemistry | terminology | 1523 | 157 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 298 | `research/food-chemistry/applications.md` | food-chemistry | applications | 876 | 104 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 299 | `research/food-chemistry/fundamentals.md` | food-chemistry | fundamentals | 871 | 102 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 300 | `research/food-chemistry/graph.yaml` | food-chemistry | graph | 831 | 78 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 301 | `research/food-chemistry/history.md` | food-chemistry | history | 631 | 74 | missing | 0 | 0 | 0 | 0 | 0 | 0 | missing front matter; unfinished/queue content |
| 302 | `research/food-chemistry/industrial.md` | food-chemistry | industrial | 808 | 94 | missing | 0 | 0 | 0 | 0 | 0 | 0 | missing front matter |
| 303 | `research/food-chemistry/laboratory.md` | food-chemistry | laboratory | 829 | 100 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 304 | `research/food-chemistry/mathematics.md` | food-chemistry | mathematics | 647 | 73 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 305 | `research/food-chemistry/metadata.yaml` | food-chemistry | metadata | 1017 | 91 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 306 | `research/food-chemistry/overview.md` | food-chemistry | overview | 933 | 110 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 307 | `research/food-chemistry/primary-literature.md` | food-chemistry | primary-literature | 665 | 81 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 308 | `research/food-chemistry/references.md` | food-chemistry | references | 1648 | 205 | missing | 0 | 0 | 0 | 0 | 4 | 0 | missing front matter |
| 309 | `research/food-chemistry/research-frontier.md` | food-chemistry | research-frontier | 1642 | 196 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 310 | `research/food-chemistry/standards-and-sources.md` | food-chemistry | standards-and-sources | 961 | 124 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 311 | `research/graph/edges.batch-3.yaml` | repository graph | edges.batch-3.yaml | 1213 | 97 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 312 | `research/graph/edges.batch-4.yaml` | repository graph | edges.batch-4.yaml | 947 | 82 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 313 | `research/graph/edges.batch-5.yaml` | repository graph | edges.batch-5.yaml | 1175 | 97 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 314 | `research/graph/edges.batch-6.yaml` | repository graph | edges.batch-6.yaml | 1110 | 89 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 315 | `research/graph/edges.batch-7.yaml` | repository graph | edges.batch-7.yaml | 986 | 73 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 316 | `research/graph/edges.batch-8.yaml` | repository graph | edges.batch-8.yaml | 1169 | 93 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 317 | `research/graph/edges.yaml` | repository graph | edges.yaml | 4757 | 411 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 318 | `research/graph/index.yaml` | repository graph | index.yaml | 246 | 28 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 319 | `research/graph/nodes.batch-3.yaml` | repository graph | nodes.batch-3.yaml | 741 | 87 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 320 | `research/graph/nodes.batch-4.yaml` | repository graph | nodes.batch-4.yaml | 509 | 57 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 321 | `research/graph/nodes.batch-5.yaml` | repository graph | nodes.batch-5.yaml | 481 | 55 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 322 | `research/graph/nodes.batch-6.yaml` | repository graph | nodes.batch-6.yaml | 700 | 80 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 323 | `research/graph/nodes.batch-7.yaml` | repository graph | nodes.batch-7.yaml | 628 | 62 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 324 | `research/graph/nodes.batch-8.yaml` | repository graph | nodes.batch-8.yaml | 534 | 57 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 325 | `research/graph/nodes.yaml` | repository graph | nodes.yaml | 3991 | 417 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 326 | `research/green-chemistry/applications.md` | green-chemistry | applications | 869 | 107 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 327 | `research/green-chemistry/fundamentals.md` | green-chemistry | fundamentals | 1089 | 133 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 328 | `research/green-chemistry/graph.yaml` | green-chemistry | graph | 904 | 84 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 329 | `research/green-chemistry/history.md` | green-chemistry | history | 1025 | 142 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 330 | `research/green-chemistry/industrial.md` | green-chemistry | industrial | 946 | 124 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 331 | `research/green-chemistry/laboratory.md` | green-chemistry | laboratory | 983 | 120 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 332 | `research/green-chemistry/mathematics.md` | green-chemistry | mathematics | 879 | 114 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 333 | `research/green-chemistry/metadata.yaml` | green-chemistry | metadata | 1089 | 98 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 334 | `research/green-chemistry/overview.md` | green-chemistry | overview | 884 | 112 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 335 | `research/green-chemistry/primary-literature.md` | green-chemistry | primary-literature | 671 | 89 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 336 | `research/green-chemistry/references.md` | green-chemistry | references | 1417 | 194 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter; unfinished/queue content |
| 337 | `research/green-chemistry/research-frontier.md` | green-chemistry | research-frontier | 1912 | 251 | missing | 0 | 0 | 0 | 0 | 2 | 1 | missing front matter; unfinished/queue content |
| 338 | `research/green-chemistry/standards.md` | green-chemistry | standards | 1128 | 154 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 339 | `research/inorganic-chemistry/applications.md` | inorganic-chemistry | applications | 527 | 58 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 340 | `research/inorganic-chemistry/common-misconceptions.md` | inorganic-chemistry | common-misconceptions | 364 | 42 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 341 | `research/inorganic-chemistry/datasets.md` | inorganic-chemistry | datasets | 232 | 26 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 342 | `research/inorganic-chemistry/equations.md` | inorganic-chemistry | equations | 576 | 69 | draft | 0 | 1 | 0 | 0 | 0 | 0 | None |
| 343 | `research/inorganic-chemistry/fundamentals.md` | inorganic-chemistry | fundamentals | 397 | 47 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 344 | `research/inorganic-chemistry/graph.yaml` | inorganic-chemistry | graph | 854 | 84 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 345 | `research/inorganic-chemistry/history.md` | inorganic-chemistry | history | 856 | 97 | draft | 1 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 346 | `research/inorganic-chemistry/industrial.md` | inorganic-chemistry | industrial | 567 | 67 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 347 | `research/inorganic-chemistry/laboratory.md` | inorganic-chemistry | laboratory | 922 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 348 | `research/inorganic-chemistry/mathematics.md` | inorganic-chemistry | mathematics | 444 | 46 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 349 | `research/inorganic-chemistry/metadata.yaml` | inorganic-chemistry | metadata | 1367 | 129 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 350 | `research/inorganic-chemistry/overview.md` | inorganic-chemistry | overview | 448 | 57 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 351 | `research/inorganic-chemistry/primary-literature.md` | inorganic-chemistry | primary-literature | 1664 | 208 | draft | 0 | 0 | 2 | 0 | 2 | 0 | None |
| 352 | `research/inorganic-chemistry/quality-score.yaml` | inorganic-chemistry | quality-score | 712 | 77 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 353 | `research/inorganic-chemistry/references.md` | inorganic-chemistry | references | 2570 | 330 | draft | 0 | 0 | 5 | 0 | 5 | 0 | None |
| 354 | `research/inorganic-chemistry/research-frontier.md` | inorganic-chemistry | research-frontier | 2370 | 295 | draft | 0 | 0 | 4 | 0 | 4 | 0 | unfinished/queue content |
| 355 | `research/inorganic-chemistry/research-queue.md` | inorganic-chemistry | research-queue | 1191 | 128 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 356 | `research/inorganic-chemistry/standards.md` | inorganic-chemistry | standards | 1215 | 159 | draft | 0 | 0 | 2 | 0 | 2 | 0 | None |
| 357 | `research/inorganic-chemistry/terminology.md` | inorganic-chemistry | terminology | 1323 | 147 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 358 | `research/laboratory-safety/applications.md` | laboratory-safety | applications | 922 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 359 | `research/laboratory-safety/common-misconceptions.md` | laboratory-safety | common-misconceptions | 360 | 42 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 360 | `research/laboratory-safety/datasets.md` | laboratory-safety | datasets | 228 | 26 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 361 | `research/laboratory-safety/equations.md` | laboratory-safety | equations | 306 | 38 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 362 | `research/laboratory-safety/fundamentals.md` | laboratory-safety | fundamentals | 404 | 49 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 363 | `research/laboratory-safety/graph.yaml` | laboratory-safety | graph | 785 | 84 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 364 | `research/laboratory-safety/history.md` | laboratory-safety | history | 749 | 89 | draft | 1 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 365 | `research/laboratory-safety/industrial.md` | laboratory-safety | industrial | 578 | 68 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 366 | `research/laboratory-safety/laboratory.md` | laboratory-safety | laboratory | 635 | 77 | draft | 1 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 367 | `research/laboratory-safety/mathematics.md` | laboratory-safety | mathematics | 432 | 46 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 368 | `research/laboratory-safety/metadata.yaml` | laboratory-safety | metadata | 1258 | 127 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 369 | `research/laboratory-safety/overview.md` | laboratory-safety | overview | 414 | 54 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 370 | `research/laboratory-safety/primary-literature.md` | laboratory-safety | primary-literature | 1478 | 188 | draft | 0 | 0 | 2 | 0 | 2 | 0 | None |
| 371 | `research/laboratory-safety/quality-score.yaml` | laboratory-safety | quality-score | 712 | 77 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 372 | `research/laboratory-safety/references.md` | laboratory-safety | references | 2668 | 354 | draft | 0 | 0 | 5 | 0 | 5 | 0 | None |
| 373 | `research/laboratory-safety/research-frontier.md` | laboratory-safety | research-frontier | 1866 | 243 | draft | 0 | 0 | 3 | 0 | 3 | 0 | unfinished/queue content |
| 374 | `research/laboratory-safety/research-queue.md` | laboratory-safety | research-queue | 904 | 100 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 375 | `research/laboratory-safety/standards.md` | laboratory-safety | standards | 2683 | 357 | draft | 0 | 0 | 5 | 0 | 5 | 0 | None |
| 376 | `research/laboratory-safety/terminology.md` | laboratory-safety | terminology | 1255 | 144 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 377 | `research/mass-spectrometry/applications.md` | mass-spectrometry | applications | 1078 | 126 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 378 | `research/mass-spectrometry/fundamentals.md` | mass-spectrometry | fundamentals | 829 | 104 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 379 | `research/mass-spectrometry/graph.yaml` | mass-spectrometry | graph | 832 | 78 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 380 | `research/mass-spectrometry/history.md` | mass-spectrometry | history | 670 | 78 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 381 | `research/mass-spectrometry/industrial.md` | mass-spectrometry | industrial | 1011 | 119 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 382 | `research/mass-spectrometry/laboratory.md` | mass-spectrometry | laboratory | 852 | 104 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 383 | `research/mass-spectrometry/mathematics.md` | mass-spectrometry | mathematics | 612 | 71 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 384 | `research/mass-spectrometry/metadata.yaml` | mass-spectrometry | metadata | 1062 | 94 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 385 | `research/mass-spectrometry/overview.md` | mass-spectrometry | overview | 883 | 112 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 386 | `research/mass-spectrometry/primary-literature.md` | mass-spectrometry | primary-literature | 648 | 76 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 387 | `research/mass-spectrometry/references.md` | mass-spectrometry | references | 1192 | 167 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter; unfinished/queue content |
| 388 | `research/mass-spectrometry/research-frontier.md` | mass-spectrometry | research-frontier | 1168 | 143 | missing | 0 | 0 | 0 | 0 | 2 | 1 | missing front matter; unfinished/queue content |
| 389 | `research/mass-spectrometry/standards.md` | mass-spectrometry | standards | 999 | 137 | missing | 0 | 0 | 0 | 0 | 2 | 1 | missing front matter |
| 390 | `research/materials-chemistry/applications.md` | materials-chemistry | applications | 444 | 51 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 391 | `research/materials-chemistry/common-misconceptions.md` | materials-chemistry | common-misconceptions | 364 | 42 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 392 | `research/materials-chemistry/datasets.md` | materials-chemistry | datasets | 1727 | 234 | draft | 0 | 0 | 3 | 0 | 3 | 2 | None |
| 393 | `research/materials-chemistry/equations.md` | materials-chemistry | equations | 626 | 69 | draft | 0 | 1 | 0 | 0 | 0 | 0 | None |
| 394 | `research/materials-chemistry/fundamentals.md` | materials-chemistry | fundamentals | 446 | 52 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 395 | `research/materials-chemistry/graph.yaml` | materials-chemistry | graph | 892 | 80 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 396 | `research/materials-chemistry/history.md` | materials-chemistry | history | 907 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 397 | `research/materials-chemistry/industrial.md` | materials-chemistry | industrial | 556 | 62 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 398 | `research/materials-chemistry/laboratory.md` | materials-chemistry | laboratory | 922 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 399 | `research/materials-chemistry/mathematics.md` | materials-chemistry | mathematics | 452 | 46 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 400 | `research/materials-chemistry/metadata.yaml` | materials-chemistry | metadata | 1297 | 122 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 401 | `research/materials-chemistry/overview.md` | materials-chemistry | overview | 443 | 49 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 402 | `research/materials-chemistry/primary-literature.md` | materials-chemistry | primary-literature | 1540 | 195 | draft | 0 | 0 | 2 | 0 | 2 | 0 | None |
| 403 | `research/materials-chemistry/quality-score.yaml` | materials-chemistry | quality-score | 712 | 77 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 404 | `research/materials-chemistry/references.md` | materials-chemistry | references | 2179 | 296 | draft | 0 | 0 | 4 | 0 | 4 | 2 | None |
| 405 | `research/materials-chemistry/research-frontier.md` | materials-chemistry | research-frontier | 2365 | 317 | draft | 0 | 0 | 4 | 0 | 4 | 2 | unfinished/queue content |
| 406 | `research/materials-chemistry/research-queue.md` | materials-chemistry | research-queue | 1011 | 105 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 407 | `research/materials-chemistry/standards.md` | materials-chemistry | standards | 694 | 87 | draft | 0 | 0 | 1 | 0 | 1 | 1 | None |
| 408 | `research/materials-chemistry/terminology.md` | materials-chemistry | terminology | 1382 | 150 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 409 | `research/medicinal-chemistry/applications.md` | medicinal-chemistry | applications | 902 | 103 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 410 | `research/medicinal-chemistry/fundamentals.md` | medicinal-chemistry | fundamentals | 821 | 98 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 411 | `research/medicinal-chemistry/graph.yaml` | medicinal-chemistry | graph | 898 | 82 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 412 | `research/medicinal-chemistry/history.md` | medicinal-chemistry | history | 608 | 71 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 413 | `research/medicinal-chemistry/industrial.md` | medicinal-chemistry | industrial | 713 | 82 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 414 | `research/medicinal-chemistry/laboratory.md` | medicinal-chemistry | laboratory | 592 | 65 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 415 | `research/medicinal-chemistry/mathematics.md` | medicinal-chemistry | mathematics | 573 | 66 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 416 | `research/medicinal-chemistry/metadata.yaml` | medicinal-chemistry | metadata | 1019 | 85 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 417 | `research/medicinal-chemistry/overview.md` | medicinal-chemistry | overview | 834 | 99 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 418 | `research/medicinal-chemistry/primary-literature.md` | medicinal-chemistry | primary-literature | 589 | 68 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 419 | `research/medicinal-chemistry/references.md` | medicinal-chemistry | references | 1196 | 162 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter; unfinished/queue content |
| 420 | `research/medicinal-chemistry/research-frontier.md` | medicinal-chemistry | research-frontier | 1284 | 159 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 421 | `research/medicinal-chemistry/standards.md` | medicinal-chemistry | standards | 851 | 120 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 422 | `research/nuclear-chemistry/applications.md` | nuclear-chemistry | applications | 514 | 54 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 423 | `research/nuclear-chemistry/fundamentals.md` | nuclear-chemistry | fundamentals | 481 | 54 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 424 | `research/nuclear-chemistry/graph.yaml` | nuclear-chemistry | graph | 855 | 78 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 425 | `research/nuclear-chemistry/history.md` | nuclear-chemistry | history | 625 | 71 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 426 | `research/nuclear-chemistry/industrial.md` | nuclear-chemistry | industrial | 512 | 54 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 427 | `research/nuclear-chemistry/laboratory.md` | nuclear-chemistry | laboratory | 511 | 55 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 428 | `research/nuclear-chemistry/mathematics.md` | nuclear-chemistry | mathematics | 563 | 64 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 429 | `research/nuclear-chemistry/metadata.yaml` | nuclear-chemistry | metadata | 1064 | 94 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 430 | `research/nuclear-chemistry/overview.md` | nuclear-chemistry | overview | 481 | 50 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 431 | `research/nuclear-chemistry/primary-literature.md` | nuclear-chemistry | primary-literature | 556 | 64 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 432 | `research/nuclear-chemistry/references.md` | nuclear-chemistry | references | 359 | 48 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 433 | `research/nuclear-chemistry/research-frontier.md` | nuclear-chemistry | research-frontier | 685 | 73 | missing | 0 | 0 | 0 | 0 | 1 | 1 | missing front matter; unfinished/queue content |
| 434 | `research/nuclear-chemistry/standards.md` | nuclear-chemistry | standards | 620 | 81 | missing | 0 | 0 | 0 | 0 | 1 | 1 | missing front matter |
| 435 | `research/organic-chemistry/applications.md` | organic-chemistry | applications | 414 | 50 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 436 | `research/organic-chemistry/common-misconceptions.md` | organic-chemistry | common-misconceptions | 360 | 42 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 437 | `research/organic-chemistry/datasets.md` | organic-chemistry | datasets | 2141 | 277 | draft | 0 | 0 | 4 | 0 | 4 | 2 | None |
| 438 | `research/organic-chemistry/equations.md` | organic-chemistry | equations | 531 | 66 | draft | 0 | 1 | 0 | 0 | 0 | 0 | None |
| 439 | `research/organic-chemistry/fundamentals.md` | organic-chemistry | fundamentals | 413 | 48 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 440 | `research/organic-chemistry/graph.yaml` | organic-chemistry | graph | 861 | 80 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 441 | `research/organic-chemistry/history.md` | organic-chemistry | history | 897 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 442 | `research/organic-chemistry/industrial.md` | organic-chemistry | industrial | 565 | 64 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 443 | `research/organic-chemistry/laboratory.md` | organic-chemistry | laboratory | 598 | 70 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 444 | `research/organic-chemistry/mathematics.md` | organic-chemistry | mathematics | 917 | 107 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 445 | `research/organic-chemistry/metadata.yaml` | organic-chemistry | metadata | 1398 | 134 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 446 | `research/organic-chemistry/overview.md` | organic-chemistry | overview | 508 | 59 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 447 | `research/organic-chemistry/primary-literature.md` | organic-chemistry | primary-literature | 559 | 61 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 448 | `research/organic-chemistry/quality-score.yaml` | organic-chemistry | quality-score | 727 | 78 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 449 | `research/organic-chemistry/references.md` | organic-chemistry | references | 2566 | 346 | draft | 0 | 0 | 5 | 0 | 5 | 4 | None |
| 450 | `research/organic-chemistry/research-frontier.md` | organic-chemistry | research-frontier | 1665 | 212 | draft | 0 | 0 | 3 | 0 | 3 | 2 | unfinished/queue content |
| 451 | `research/organic-chemistry/research-queue.md` | organic-chemistry | research-queue | 837 | 93 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 452 | `research/organic-chemistry/standards.md` | organic-chemistry | standards | 1845 | 248 | draft | 0 | 0 | 3 | 0 | 2 | 3 | None |
| 453 | `research/organic-chemistry/terminology.md` | organic-chemistry | terminology | 1230 | 138 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 454 | `research/periodic-table/applications.md` | periodic-table | applications | 418 | 52 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 455 | `research/periodic-table/common-misconceptions.md` | periodic-table | common-misconceptions | 451 | 50 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 456 | `research/periodic-table/datasets.md` | periodic-table | datasets | 1438 | 190 | draft | 0 | 0 | 3 | 0 | 2 | 0 | None |
| 457 | `research/periodic-table/equations.md` | periodic-table | equations | 325 | 41 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 458 | `research/periodic-table/fundamentals.md` | periodic-table | fundamentals | 618 | 80 | draft | 2 | 0 | 0 | 0 | 0 | 0 | None |
| 459 | `research/periodic-table/graph.yaml` | periodic-table | graph | 693 | 67 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 460 | `research/periodic-table/history.md` | periodic-table | history | 615 | 77 | draft | 2 | 0 | 0 | 0 | 0 | 0 | None |
| 461 | `research/periodic-table/industrial.md` | periodic-table | industrial | 840 | 106 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 462 | `research/periodic-table/laboratory.md` | periodic-table | laboratory | 447 | 55 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 463 | `research/periodic-table/mathematics.md` | periodic-table | mathematics | 441 | 54 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 464 | `research/periodic-table/metadata.yaml` | periodic-table | metadata | 1572 | 161 | not required | 0 | 0 | 0 | 0 | 0 | 0 | duplicate YAML key: related_topics |
| 465 | `research/periodic-table/overview.md` | periodic-table | overview | 860 | 106 | draft | 2 | 0 | 0 | 0 | 0 | 0 | None |
| 466 | `research/periodic-table/primary-literature.md` | periodic-table | primary-literature | 1342 | 179 | draft | 0 | 0 | 2 | 0 | 2 | 0 | None |
| 467 | `research/periodic-table/quality-score.yaml` | periodic-table | quality-score | 718 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 468 | `research/periodic-table/references.md` | periodic-table | references | 1739 | 228 | draft | 0 | 0 | 3 | 0 | 3 | 1 | unfinished/queue content |
| 469 | `research/periodic-table/research-frontier.md` | periodic-table | research-frontier | 854 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 470 | `research/periodic-table/research-queue.md` | periodic-table | research-queue | 1362 | 157 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 471 | `research/periodic-table/terminology.md` | periodic-table | terminology | 807 | 93 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 472 | `research/photochemistry/applications.md` | photochemistry | applications | 1408 | 171 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter |
| 473 | `research/photochemistry/fundamentals.md` | photochemistry | fundamentals | 1079 | 131 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter |
| 474 | `research/photochemistry/graph.yaml` | photochemistry | graph | 803 | 72 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 475 | `research/photochemistry/history.md` | photochemistry | history | 1011 | 127 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 476 | `research/photochemistry/industrial.md` | photochemistry | industrial | 1110 | 122 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 477 | `research/photochemistry/laboratory.md` | photochemistry | laboratory | 824 | 92 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 478 | `research/photochemistry/mathematics.md` | photochemistry | mathematics | 606 | 73 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 479 | `research/photochemistry/metadata.yaml` | photochemistry | metadata | 968 | 83 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 480 | `research/photochemistry/overview.md` | photochemistry | overview | 535 | 61 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 481 | `research/photochemistry/primary-literature.md` | photochemistry | primary-literature | 561 | 62 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 482 | `research/photochemistry/references.md` | photochemistry | references | 1761 | 247 | missing | 0 | 0 | 0 | 0 | 4 | 0 | missing front matter; unfinished/queue content |
| 483 | `research/photochemistry/research-frontier.md` | photochemistry | research-frontier | 2584 | 349 | missing | 0 | 0 | 0 | 0 | 3 | 3 | missing front matter |
| 484 | `research/photochemistry/standards.md` | photochemistry | standards | 943 | 127 | missing | 0 | 0 | 0 | 0 | 2 | 1 | missing front matter |
| 485 | `research/polymer-chemistry/applications.md` | polymer-chemistry | applications | 947 | 115 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 486 | `research/polymer-chemistry/fundamentals.md` | polymer-chemistry | fundamentals | 1053 | 135 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 487 | `research/polymer-chemistry/graph.yaml` | polymer-chemistry | graph | 906 | 82 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 488 | `research/polymer-chemistry/history.md` | polymer-chemistry | history | 902 | 117 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 489 | `research/polymer-chemistry/industrial.md` | polymer-chemistry | industrial | 918 | 114 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 490 | `research/polymer-chemistry/laboratory.md` | polymer-chemistry | laboratory | 1004 | 112 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 491 | `research/polymer-chemistry/mathematics.md` | polymer-chemistry | mathematics | 614 | 75 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 492 | `research/polymer-chemistry/metadata.yaml` | polymer-chemistry | metadata | 919 | 77 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 493 | `research/polymer-chemistry/overview.md` | polymer-chemistry | overview | 780 | 92 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 494 | `research/polymer-chemistry/primary-literature.md` | polymer-chemistry | primary-literature | 605 | 72 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 495 | `research/polymer-chemistry/references.md` | polymer-chemistry | references | 1988 | 272 | missing | 0 | 0 | 0 | 0 | 4 | 0 | missing front matter |
| 496 | `research/polymer-chemistry/research-frontier.md` | polymer-chemistry | research-frontier | 2012 | 269 | missing | 0 | 0 | 0 | 0 | 3 | 2 | missing front matter |
| 497 | `research/polymer-chemistry/standards.md` | polymer-chemistry | standards | 1233 | 170 | missing | 0 | 0 | 0 | 0 | 2 | 1 | missing front matter |
| 498 | `research/quantum-chemistry/applications.md` | quantum-chemistry | applications | 932 | 103 | missing | 0 | 0 | 0 | 0 | 0 | 0 | missing front matter |
| 499 | `research/quantum-chemistry/fundamentals.md` | quantum-chemistry | fundamentals | 1184 | 143 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 500 | `research/quantum-chemistry/graph.yaml` | quantum-chemistry | graph | 844 | 80 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 501 | `research/quantum-chemistry/history.md` | quantum-chemistry | history | 945 | 121 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 502 | `research/quantum-chemistry/industrial.md` | quantum-chemistry | industrial | 812 | 90 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 503 | `research/quantum-chemistry/laboratory.md` | quantum-chemistry | laboratory | 881 | 98 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 504 | `research/quantum-chemistry/mathematics.md` | quantum-chemistry | mathematics | 1006 | 119 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 505 | `research/quantum-chemistry/metadata.yaml` | quantum-chemistry | metadata | 1204 | 107 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 506 | `research/quantum-chemistry/overview.md` | quantum-chemistry | overview | 964 | 116 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 507 | `research/quantum-chemistry/primary-literature.md` | quantum-chemistry | primary-literature | 646 | 80 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 508 | `research/quantum-chemistry/references.md` | quantum-chemistry | references | 1373 | 195 | missing | 0 | 0 | 0 | 0 | 4 | 0 | missing front matter; unfinished/queue content |
| 509 | `research/quantum-chemistry/research-frontier.md` | quantum-chemistry | research-frontier | 2028 | 280 | missing | 0 | 0 | 0 | 0 | 3 | 2 | missing front matter |
| 510 | `research/quantum-chemistry/standards-and-datasets.md` | quantum-chemistry | standards-and-datasets | 1301 | 165 | missing | 0 | 0 | 0 | 0 | 2 | 1 | missing front matter |
| 511 | `research/solubility/applications.md` | solubility | applications | 914 | 109 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 512 | `research/solubility/fundamentals.md` | solubility | fundamentals | 947 | 112 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 513 | `research/solubility/graph.yaml` | solubility | graph | 866 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 514 | `research/solubility/history.md` | solubility | history | 625 | 73 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 515 | `research/solubility/industrial.md` | solubility | industrial | 868 | 100 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 516 | `research/solubility/laboratory.md` | solubility | laboratory | 583 | 63 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 517 | `research/solubility/mathematics.md` | solubility | mathematics | 680 | 77 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 518 | `research/solubility/metadata.yaml` | solubility | metadata | 982 | 83 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 519 | `research/solubility/overview.md` | solubility | overview | 950 | 120 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 520 | `research/solubility/primary-literature.md` | solubility | primary-literature | 646 | 73 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 521 | `research/solubility/references.md` | solubility | references | 916 | 127 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 522 | `research/solubility/research-frontier.md` | solubility | research-frontier | 1035 | 131 | missing | 0 | 0 | 0 | 0 | 1 | 1 | missing front matter; unfinished/queue content |
| 523 | `research/solubility/standards.md` | solubility | standards | 886 | 115 | missing | 0 | 0 | 0 | 0 | 1 | 1 | missing front matter |
| 524 | `research/solutions-and-colloids/applications.md` | solutions-and-colloids | applications | 433 | 53 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 525 | `research/solutions-and-colloids/common-misconceptions.md` | solutions-and-colloids | common-misconceptions | 370 | 44 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 526 | `research/solutions-and-colloids/datasets.md` | solutions-and-colloids | datasets | 2014 | 268 | draft | 0 | 0 | 4 | 0 | 4 | 4 | None |
| 527 | `research/solutions-and-colloids/equations.md` | solutions-and-colloids | equations | 497 | 64 | draft | 0 | 1 | 0 | 0 | 0 | 0 | None |
| 528 | `research/solutions-and-colloids/fundamentals.md` | solutions-and-colloids | fundamentals | 400 | 48 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 529 | `research/solutions-and-colloids/graph.yaml` | solutions-and-colloids | graph | 728 | 70 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 530 | `research/solutions-and-colloids/history.md` | solutions-and-colloids | history | 698 | 84 | draft | 1 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 531 | `research/solutions-and-colloids/industrial.md` | solutions-and-colloids | industrial | 579 | 67 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 532 | `research/solutions-and-colloids/laboratory.md` | solutions-and-colloids | laboratory | 937 | 112 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 533 | `research/solutions-and-colloids/mathematics.md` | solutions-and-colloids | mathematics | 942 | 112 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 534 | `research/solutions-and-colloids/metadata.yaml` | solutions-and-colloids | metadata | 1278 | 121 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 535 | `research/solutions-and-colloids/overview.md` | solutions-and-colloids | overview | 508 | 62 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 536 | `research/solutions-and-colloids/primary-literature.md` | solutions-and-colloids | primary-literature | 1018 | 128 | draft | 0 | 0 | 1 | 0 | 1 | 1 | None |
| 537 | `research/solutions-and-colloids/quality-score.yaml` | solutions-and-colloids | quality-score | 727 | 78 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 538 | `research/solutions-and-colloids/references.md` | solutions-and-colloids | references | 2018 | 268 | draft | 0 | 0 | 4 | 0 | 4 | 4 | None |
| 539 | `research/solutions-and-colloids/research-frontier.md` | solutions-and-colloids | research-frontier | 1065 | 129 | draft | 0 | 0 | 1 | 0 | 1 | 1 | unfinished/queue content |
| 540 | `research/solutions-and-colloids/research-queue.md` | solutions-and-colloids | research-queue | 910 | 101 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 541 | `research/solutions-and-colloids/standards.md` | solutions-and-colloids | standards | 1085 | 152 | draft | 0 | 0 | 2 | 0 | 1 | 2 | None |
| 542 | `research/solutions-and-colloids/terminology.md` | solutions-and-colloids | terminology | 1544 | 181 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 543 | `research/source-policy.md` | repository policy | source-policy | 2054 | 260 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 544 | `research/spectroscopy/applications.md` | spectroscopy | applications | 462 | 50 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 545 | `research/spectroscopy/common-misconceptions.md` | spectroscopy | common-misconceptions | 350 | 40 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 546 | `research/spectroscopy/datasets.md` | spectroscopy | datasets | 1601 | 221 | draft | 0 | 0 | 3 | 0 | 3 | 3 | None |
| 547 | `research/spectroscopy/equations.md` | spectroscopy | equations | 737 | 100 | draft | 0 | 2 | 0 | 0 | 0 | 0 | None |
| 548 | `research/spectroscopy/fundamentals.md` | spectroscopy | fundamentals | 387 | 43 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 549 | `research/spectroscopy/graph.yaml` | spectroscopy | graph | 889 | 82 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 550 | `research/spectroscopy/history.md` | spectroscopy | history | 872 | 102 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 551 | `research/spectroscopy/industrial.md` | spectroscopy | industrial | 608 | 66 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 552 | `research/spectroscopy/laboratory.md` | spectroscopy | laboratory | 545 | 65 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 553 | `research/spectroscopy/mathematics.md` | spectroscopy | mathematics | 892 | 102 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 554 | `research/spectroscopy/metadata.yaml` | spectroscopy | metadata | 1270 | 119 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 555 | `research/spectroscopy/overview.md` | spectroscopy | overview | 537 | 64 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 556 | `research/spectroscopy/primary-literature.md` | spectroscopy | primary-literature | 1562 | 200 | draft | 0 | 0 | 2 | 0 | 2 | 2 | None |
| 557 | `research/spectroscopy/quality-score.yaml` | spectroscopy | quality-score | 727 | 78 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 558 | `research/spectroscopy/references.md` | spectroscopy | references | 2058 | 270 | draft | 0 | 0 | 4 | 0 | 4 | 4 | None |
| 559 | `research/spectroscopy/research-frontier.md` | spectroscopy | research-frontier | 1405 | 180 | draft | 0 | 0 | 2 | 0 | 2 | 2 | unfinished/queue content |
| 560 | `research/spectroscopy/research-queue.md` | spectroscopy | research-queue | 870 | 97 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 561 | `research/spectroscopy/standards.md` | spectroscopy | standards | 674 | 87 | draft | 0 | 0 | 1 | 0 | 1 | 1 | None |
| 562 | `research/spectroscopy/terminology.md` | spectroscopy | terminology | 1241 | 133 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 563 | `research/statistical-mechanics/applications.md` | statistical-mechanics | applications | 896 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 564 | `research/statistical-mechanics/common-misconceptions.md` | statistical-mechanics | common-misconceptions | 914 | 110 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 565 | `research/statistical-mechanics/datasets.md` | statistical-mechanics | datasets | 987 | 119 | draft | 0 | 0 | 2 | 0 | 1 | 0 | unfinished/queue content |
| 566 | `research/statistical-mechanics/equations.md` | statistical-mechanics | equations | 890 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 567 | `research/statistical-mechanics/fundamentals.md` | statistical-mechanics | fundamentals | 896 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 568 | `research/statistical-mechanics/graph.yaml` | statistical-mechanics | graph | 715 | 67 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 569 | `research/statistical-mechanics/history.md` | statistical-mechanics | history | 886 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 570 | `research/statistical-mechanics/industrial.md` | statistical-mechanics | industrial | 892 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 571 | `research/statistical-mechanics/laboratory.md` | statistical-mechanics | laboratory | 892 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 572 | `research/statistical-mechanics/mathematics.md` | statistical-mechanics | mathematics | 894 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 573 | `research/statistical-mechanics/metadata.yaml` | statistical-mechanics | metadata | 1368 | 131 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 574 | `research/statistical-mechanics/overview.md` | statistical-mechanics | overview | 812 | 95 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 575 | `research/statistical-mechanics/primary-literature.md` | statistical-mechanics | primary-literature | 941 | 111 | draft | 0 | 0 | 1 | 0 | 1 | 0 | None |
| 576 | `research/statistical-mechanics/quality-score.yaml` | statistical-mechanics | quality-score | 718 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 577 | `research/statistical-mechanics/references.md` | statistical-mechanics | references | 1583 | 200 | draft | 0 | 0 | 3 | 0 | 3 | 2 | None |
| 578 | `research/statistical-mechanics/research-frontier.md` | statistical-mechanics | research-frontier | 987 | 117 | draft | 0 | 0 | 1 | 0 | 1 | 1 | unfinished/queue content |
| 579 | `research/statistical-mechanics/research-queue.md` | statistical-mechanics | research-queue | 698 | 82 | in_progress | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 580 | `research/statistical-mechanics/standards.md` | statistical-mechanics | standards | 690 | 88 | draft | 0 | 0 | 1 | 0 | 1 | 1 | None |
| 581 | `research/statistical-mechanics/terminology.md` | statistical-mechanics | terminology | 894 | 108 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 582 | `research/stoichiometry/applications.md` | stoichiometry | applications | 400 | 44 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 583 | `research/stoichiometry/common-misconceptions.md` | stoichiometry | common-misconceptions | 449 | 48 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 584 | `research/stoichiometry/datasets.md` | stoichiometry | datasets | 932 | 117 | draft | 0 | 0 | 2 | 0 | 1 | 0 | None |
| 585 | `research/stoichiometry/equations.md` | stoichiometry | equations | 621 | 69 | draft | 0 | 1 | 0 | 0 | 0 | 0 | None |
| 586 | `research/stoichiometry/fundamentals.md` | stoichiometry | fundamentals | 442 | 51 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 587 | `research/stoichiometry/graph.yaml` | stoichiometry | graph | 853 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 588 | `research/stoichiometry/history.md` | stoichiometry | history | 830 | 102 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 589 | `research/stoichiometry/industrial.md` | stoichiometry | industrial | 427 | 51 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 590 | `research/stoichiometry/laboratory.md` | stoichiometry | laboratory | 836 | 102 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 591 | `research/stoichiometry/mathematics.md` | stoichiometry | mathematics | 395 | 44 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 592 | `research/stoichiometry/metadata.yaml` | stoichiometry | metadata | 1523 | 150 | not required | 0 | 0 | 0 | 0 | 0 | 0 | duplicate YAML key: related_topics |
| 593 | `research/stoichiometry/overview.md` | stoichiometry | overview | 804 | 95 | draft | 2 | 0 | 0 | 0 | 0 | 0 | None |
| 594 | `research/stoichiometry/primary-literature.md` | stoichiometry | primary-literature | 1312 | 160 | draft | 0 | 0 | 2 | 0 | 2 | 0 | None |
| 595 | `research/stoichiometry/quality-score.yaml` | stoichiometry | quality-score | 718 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 596 | `research/stoichiometry/references.md` | stoichiometry | references | 1787 | 216 | draft | 0 | 0 | 3 | 0 | 3 | 0 | unfinished/queue content |
| 597 | `research/stoichiometry/research-frontier.md` | stoichiometry | research-frontier | 850 | 104 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 598 | `research/stoichiometry/research-queue.md` | stoichiometry | research-queue | 1150 | 120 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 599 | `research/stoichiometry/standards.md` | stoichiometry | standards | 998 | 131 | draft | 0 | 0 | 2 | 0 | 2 | 1 | None |
| 600 | `research/stoichiometry/terminology.md` | stoichiometry | terminology | 820 | 87 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 601 | `research/surface-chemistry/applications.md` | surface-chemistry | applications | 685 | 81 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 602 | `research/surface-chemistry/fundamentals.md` | surface-chemistry | fundamentals | 682 | 81 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 603 | `research/surface-chemistry/graph.yaml` | surface-chemistry | graph | 879 | 80 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 604 | `research/surface-chemistry/history.md` | surface-chemistry | history | 632 | 76 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 605 | `research/surface-chemistry/industrial.md` | surface-chemistry | industrial | 794 | 90 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 606 | `research/surface-chemistry/laboratory.md` | surface-chemistry | laboratory | 535 | 58 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 607 | `research/surface-chemistry/mathematics.md` | surface-chemistry | mathematics | 591 | 67 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 608 | `research/surface-chemistry/metadata.yaml` | surface-chemistry | metadata | 943 | 84 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 609 | `research/surface-chemistry/overview.md` | surface-chemistry | overview | 532 | 65 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 610 | `research/surface-chemistry/primary-literature.md` | surface-chemistry | primary-literature | 572 | 67 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 611 | `research/surface-chemistry/references.md` | surface-chemistry | references | 1254 | 164 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter; unfinished/queue content |
| 612 | `research/surface-chemistry/research-frontier.md` | surface-chemistry | research-frontier | 769 | 84 | missing | 0 | 0 | 0 | 0 | 1 | 1 | missing front matter; unfinished/queue content |
| 613 | `research/surface-chemistry/standards.md` | surface-chemistry | standards | 778 | 113 | missing | 0 | 0 | 0 | 0 | 1 | 1 | missing front matter |
| 614 | `research/thermochemistry/applications.md` | thermochemistry | applications | 405 | 45 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 615 | `research/thermochemistry/common-misconceptions.md` | thermochemistry | common-misconceptions | 453 | 48 | draft | 0 | 0 | 0 | 0 | 0 | 0 | unfinished/queue content |
| 616 | `research/thermochemistry/datasets.md` | thermochemistry | datasets | 1037 | 130 | draft | 0 | 0 | 2 | 0 | 1 | 1 | None |
| 617 | `research/thermochemistry/equations.md` | thermochemistry | equations | 909 | 120 | draft | 0 | 2 | 0 | 0 | 0 | 0 | None |
| 618 | `research/thermochemistry/fundamentals.md` | thermochemistry | fundamentals | 585 | 73 | draft | 2 | 0 | 0 | 0 | 0 | 0 | None |
| 619 | `research/thermochemistry/graph.yaml` | thermochemistry | graph | 831 | 70 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 620 | `research/thermochemistry/history.md` | thermochemistry | history | 838 | 102 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 621 | `research/thermochemistry/industrial.md` | thermochemistry | industrial | 503 | 59 | draft | 1 | 0 | 0 | 0 | 0 | 0 | None |
| 622 | `research/thermochemistry/laboratory.md` | thermochemistry | laboratory | 525 | 67 | draft | 2 | 0 | 0 | 0 | 0 | 0 | None |
| 623 | `research/thermochemistry/mathematics.md` | thermochemistry | mathematics | 722 | 97 | draft | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 624 | `research/thermochemistry/metadata.yaml` | thermochemistry | metadata | 1550 | 154 | not required | 0 | 0 | 0 | 0 | 0 | 0 | duplicate YAML key: related_topics |
| 625 | `research/thermochemistry/overview.md` | thermochemistry | overview | 806 | 98 | draft | 2 | 0 | 0 | 0 | 0 | 0 | None |
| 626 | `research/thermochemistry/primary-literature.md` | thermochemistry | primary-literature | 995 | 129 | draft | 0 | 0 | 2 | 0 | 1 | 0 | None |
| 627 | `research/thermochemistry/quality-score.yaml` | thermochemistry | quality-score | 718 | 76 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 628 | `research/thermochemistry/references.md` | thermochemistry | references | 2109 | 273 | draft | 0 | 0 | 4 | 0 | 4 | 1 | unfinished/queue content |
| 629 | `research/thermochemistry/research-frontier.md` | thermochemistry | research-frontier | 858 | 104 | in_progress | 3 | 0 | 0 | 0 | 0 | 0 | None |
| 630 | `research/thermochemistry/research-queue.md` | thermochemistry | research-queue | 1189 | 132 | draft | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 631 | `research/thermochemistry/standards.md` | thermochemistry | standards | 1030 | 135 | draft | 0 | 0 | 2 | 0 | 2 | 2 | None |
| 632 | `research/thermochemistry/terminology.md` | thermochemistry | terminology | 815 | 97 | draft | 0 | 0 | 0 | 1 | 0 | 0 | None |
| 633 | `research/toxicology/applications.md` | toxicology | applications | 856 | 101 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 634 | `research/toxicology/fundamentals.md` | toxicology | fundamentals | 854 | 105 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 635 | `research/toxicology/graph.yaml` | toxicology | graph | 827 | 72 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 636 | `research/toxicology/history.md` | toxicology | history | 938 | 119 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 637 | `research/toxicology/industrial.md` | toxicology | industrial | 848 | 102 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 638 | `research/toxicology/laboratory.md` | toxicology | laboratory | 843 | 100 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 639 | `research/toxicology/mathematics.md` | toxicology | mathematics | 576 | 70 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter; unfinished/queue content |
| 640 | `research/toxicology/metadata.yaml` | toxicology | metadata | 1001 | 83 | not required | 0 | 0 | 0 | 0 | 0 | 0 | None |
| 641 | `research/toxicology/overview.md` | toxicology | overview | 896 | 113 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
| 642 | `research/toxicology/primary-literature.md` | toxicology | primary-literature | 693 | 78 | missing | 0 | 0 | 0 | 0 | 1 | 0 | missing front matter |
| 643 | `research/toxicology/references.md` | toxicology | references | 1333 | 181 | missing | 0 | 0 | 0 | 0 | 3 | 0 | missing front matter; unfinished/queue content |
| 644 | `research/toxicology/research-frontier.md` | toxicology | research-frontier | 1583 | 195 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter; unfinished/queue content |
| 645 | `research/toxicology/standards.md` | toxicology | standards | 1610 | 221 | missing | 0 | 0 | 0 | 0 | 2 | 0 | missing front matter |
