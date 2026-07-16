# Content Gaps and Repair List

Audit boundary: `4fa3d18928395d0216c4940d32e5c366f3a4e13c`. This is a publication-risk register, not replacement chemistry content.

## Release-blocking findings

| Priority | Failure | Evidence | Repair condition |
| --- | --- | --- | --- |
| Closed | Semantic citation contamination | 0 source/link-domain mismatch mentions across 0 files after repair commit `4fa3d18` | Reopen immediately if a named source and linked destination diverge |
| P0 | Later-batch schema failure | Audit baseline: 220 topic Markdown files lacked required front matter and 80 required topic files were absent. After repair batch R01: 209 lack front matter and 76 required files are absent | Continue restoring the four missing core records and migrating all Markdown records for the remaining 19 affected topics |
| P0 | No scientific visual evidence | Zero image assets, zero Mermaid diagrams, zero embedded images, and zero mechanism headings | Commission visuals only after figure-level source packets are verified |
| P0 | Quantitative incompleteness | 15 explicit equation records versus 120 equation targets named in metadata | Extract, verify, define, unit-check, and scope every equation before typesetting |
| P0 | Mechanism incompleteness | Five phrase mentions of reaction mechanisms but no explicit mechanism record | Add source-verified elementary steps, electron accounting, conditions, stereochemical outcome, and limitations before any arrow-pushing art |
| P1 | Template duplication | 3 exact and 24 normalized duplicate groups | Replace generic claims, quality scores, histories, and misconception templates with topic-specific records |
| P1 | Duplicate evidence identifiers | Evidence IDs are redefined across files in 9 topics | Store each evidence record once and reference it by canonical ID |
| P1 | Graph duplication and defect | 17 duplicate node mentions; 18 duplicate edge mentions; missing endpoint `quantum-mechanics` | Produce one canonical node/edge graph and validate all endpoints |
| P1 | Dataset absence | `datasets.md` files contain source catalogs but no dataset payloads, schemas, checksums, or licenses | Add external dataset manifests or explicitly keep data external with stable identifiers and retrieval dates |

## Repair execution log

| Batch | Date | Topic | Contract repair | Evidence normalization | Quantitative repair | Gate outcome |
| --- | --- | --- | --- | --- | --- | --- |
| R01 | 2026-07-17 | `quantum-chemistry` | Created `equations.md`, `terminology.md`, `common-misconceptions.md`, and `research-queue.md`; added contract front matter to all 11 existing Markdown records | Added 18 unique claim IDs and six canonical evidence IDs; removed duplicated inline evidence destinations from topic records | Added two bounded Schrödinger-equation records with variables, units, assumptions, limitations, sources, and explicit verification status | Repository schema restored for this topic. Equation spread S024 remains `Missing` until Born–Oppenheimer separation and basis expansion are sourced; other quantum-chemistry spreads remain `Needs Research` |

R01 deliberately does not promote page readiness. Creating a record is not equivalent to verifying its scientific content.

## Page readiness outcome

| Topic-spread status | Spreads | Pages |
| --- | ---: | ---: |
| Verified | 42 | 84 |
| Needs Research | 74 | 148 |
| Missing | 44 | 88 |

No topic spread marked `Missing` may enter illustration. `Needs Research` spreads may enter low-fidelity wireframing only; scientific art and final copy remain blocked.

## Missing chemistry required for a coherent atlas

These are prerequisite or bridge domains referenced by the repository but not represented as complete topic packages.

| Gap | Why it is required | Affected topics | Repair form |
| --- | --- | --- | --- |
| Measurement, units, significant figures, and uncertainty | `scientific-measurement` is a declared prerequisite; the atlas currently starts quantitative work without a controlled measurement language | Atomic structure; stoichiometry; analytical chemistry; all laboratory pages | Add a prerequisite capsule or a full topic package with IUPAC Green Book and metrology sources |
| States of matter, gases, liquids, and phase diagrams | Phase behavior is distributed across thermodynamics and solutions with no coherent entry point | Thermodynamics; chemical engineering; atmospheric chemistry; solutions | Add a phase-behavior bridge chapter or verified capsules |
| Electron configuration and molecular geometry | Both are assumed by bonding and periodic trends but not complete topic nodes | Periodic table; bonding; coordination; spectroscopy | Add prerequisite visual capsules and graph nodes |
| Intermolecular forces | Declared as a dependency but absent as a topic | Solutions; solubility; materials; biochemistry | Add a bounded model and force/energy hierarchy |
| Oxidation–reduction outside electrochemical cells | Redox is a prerequisite for electrochemistry and inorganic chemistry but has no package | Electrochemistry; inorganic; environmental; biochemistry | Add oxidation-number, electron-balance, and chemical-redox records |
| Chemical nomenclature and formula language | Standards are scattered by topic; readers lack one naming and formula grammar | Inorganic; organic; coordination; polymers; biochemistry | Add a source-controlled nomenclature map, not a prose chapter |
| Transport phenomena and reaction engineering | Chemical engineering names these dependencies but does not provide equations or worked boundaries | Chemical engineering; catalysis; kinetics; environmental treatment | Add momentum, heat, mass transfer, residence-time, and reactor-model records |
| Process safety | Laboratory safety does not cover relief, runaway, containment, HAZOP, layers of protection, or permit systems | Chemical engineering; industrial spreads; kinetics; green chemistry | Add a distinct process-safety package with standards and incident evidence |
| Laboratory methods beyond safety | Apparatus and method validation are distributed but no core laboratory-methods package exists | Every experimental spread | Add sampling, calibration, glassware, separation, uncertainty, and record-integrity modules |
| Organic mechanisms and reaction classes | Organic chemistry has no explicit mechanism records | Organic; medicinal; polymer; biochemistry; food | Add mechanism records only from primary/review/textbook sources with conditions and limitations |
| Biochemical pathways and enzyme kinetics | Biochemistry is mainly nomenclature anchors and collection queues | Biochemistry; medicinal; food; clinical; toxicology | Add pathway, assay, kinetics, structure, and regulation evidence |

## Weak or incomplete repository sections

| Section class | Finding | Production impact |
| --- | --- | --- |
| `common-misconceptions.md` | Present in 21 topics after R01; many earlier files still contain a blank template and the repaired quantum record has no promotable misconception evidence | The mandatory misconception block cannot be populated reliably |
| `equations.md` | Present in 21 topics after R01 and contains 17 explicit records total | Quantitative spreads are missing or under-specified |
| `terminology.md` | Present in 21 topics after R01; 19 later-batch topics still use informal queues | Glossary cannot be treated as controlled vocabulary |
| `research-queue.md` | Present in 21 topics after R01; 19 later-batch topics still embed future work inside content files | Work status and publishable evidence are mixed |
| `research-frontier.md` | Early packages contain generic claims; later packages contain more specific papers whose claim support and context still require page-level verification | Research corner cannot be promoted automatically |
| `industrial.md` | All topics have a file, but many are bullet lists or generic source anchors | Plant and equipment visuals lack process conditions, boundaries, and authoritative industrial references |
| `history.md` | Several normalized duplicates and weak primary-source extraction | Timelines risk repeating generic history or misdating discoveries |
| `quality-score.yaml` | Only 20 topics have scores; exact score files are duplicated by batch | Score cannot compare maturity across topics |

## Topic-by-topic repair queue

| Topic | Missing required files | Missing front matter | Claims | Equations | Verified sources | Citation mismatches | Required repair |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| `laboratory-safety` | None | 0 | 8 | 0 | 1 | 0 | verify quantitative model/data |
| `atomic-structure` | None | 0 | 14 | 1 | 2 | 0 | topic-specific science and art review |
| `periodic-table` | None | 0 | 15 | 0 | 3 | 0 | extract equations |
| `stoichiometry` | None | 0 | 15 | 1 | 3 | 0 | topic-specific science and art review |
| `quantum-chemistry` | None | 0 | 18 | 2 | 3 | 0 | R01 contract repair complete; verify equation locators, extract Born–Oppenheimer and basis-set records, promote terminology and misconception evidence, and independently verify review claims |
| `chemical-bonding` | None | 0 | 18 | 0 | 3 | 0 | extract equations |
| `inorganic-chemistry` | None | 0 | 8 | 1 | 2 | 0 | topic-specific science and art review |
| `coordination-chemistry` | None | 0 | 10 | 1 | 1 | 0 | topic-specific science and art review |
| `crystallography` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 0 | 0 | create missing contract files; add front matter and claim IDs; extract equations; verify at least one authoritative source per spread |
| `nuclear-chemistry` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 0 | 0 | create missing contract files; add front matter and claim IDs; extract equations; verify at least one authoritative source per spread |
| `thermochemistry` | None | 0 | 17 | 2 | 4 | 0 | topic-specific science and art review |
| `chemical-thermodynamics` | None | 0 | 30 | 0 | 1 | 0 | extract equations |
| `statistical-mechanics` | None | 0 | 30 | 0 | 0 | 0 | extract equations; verify at least one authoritative source per spread |
| `solutions-and-colloids` | None | 0 | 11 | 1 | 1 | 0 | topic-specific science and art review |
| `chemical-equilibrium` | None | 0 | 30 | 0 | 0 | 0 | extract equations; verify at least one authoritative source per spread |
| `acids-and-bases` | None | 0 | 30 | 0 | 2 | 0 | extract equations |
| `solubility` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 0 | 0 | create missing contract files; add front matter and claim IDs; extract equations; verify at least one authoritative source per spread |
| `electrochemistry` | None | 0 | 9 | 2 | 0 | 0 | verify at least one authoritative source per spread |
| `chemical-kinetics` | None | 0 | 30 | 0 | 0 | 0 | extract equations; verify at least one authoritative source per spread |
| `photochemistry` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 1 | 0 | create missing contract files; add front matter and claim IDs; extract equations |
| `surface-chemistry` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 1 | 0 | create missing contract files; add front matter and claim IDs; extract equations |
| `catalysis` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 1 | 0 | create missing contract files; add front matter and claim IDs; extract equations |
| `analytical-chemistry` | None | 0 | 13 | 1 | 2 | 0 | topic-specific science and art review |
| `spectroscopy` | None | 0 | 11 | 2 | 2 | 0 | topic-specific science and art review |
| `mass-spectrometry` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 0 | 0 | create missing contract files; add front matter and claim IDs; extract equations; verify at least one authoritative source per spread |
| `chromatography` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 0 | 0 | create missing contract files; add front matter and claim IDs; extract equations; verify at least one authoritative source per spread |
| `cheminformatics` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 0 | 0 | create missing contract files; add front matter and claim IDs; verify quantitative model/data; verify at least one authoritative source per spread |
| `organic-chemistry` | None | 0 | 11 | 1 | 3 | 0 | topic-specific science and art review |
| `biochemistry` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 0 | 0 | create missing contract files; add front matter and claim IDs; extract equations; verify at least one authoritative source per spread |
| `medicinal-chemistry` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 2 | 0 | create missing contract files; add front matter and claim IDs; extract equations |
| `polymer-chemistry` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 2 | 0 | create missing contract files; add front matter and claim IDs; extract equations |
| `food-chemistry` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 1 | 0 | create missing contract files; add front matter and claim IDs; extract equations |
| `clinical-chemistry` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 0 | 0 | create missing contract files; add front matter and claim IDs; extract equations; verify at least one authoritative source per spread |
| `materials-chemistry` | None | 0 | 10 | 1 | 3 | 0 | topic-specific science and art review |
| `chemical-engineering` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 0 | 0 | create missing contract files; add front matter and claim IDs; extract equations; verify at least one authoritative source per spread |
| `environmental-chemistry` | None | 0 | 10 | 1 | 2 | 0 | topic-specific science and art review |
| `atmospheric-chemistry` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 2 | 0 | create missing contract files; add front matter and claim IDs; extract equations |
| `toxicology` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 1 | 0 | create missing contract files; add front matter and claim IDs; extract equations |
| `ecotoxicology` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 0 | 0 | create missing contract files; add front matter and claim IDs; extract equations; verify at least one authoritative source per spread |
| `green-chemistry` | equations.md, terminology.md, common-misconceptions.md, research-queue.md | 11 | 0 | 0 | 1 | 0 | create missing contract files; add front matter and claim IDs; extract equations |

## Repair sequence

1. Freeze commit and canonical source IDs.
2. Repair semantic citation mismatches; do not begin art while a named source points elsewhere.
3. Restore repository contract for the 20 later-batch topics.
4. Fill prerequisite bridge domains and repair the graph.
5. Extract equations, mechanisms, tables, and experimental boundaries into structured records.
6. Verify industrial examples with standards, handbooks, patents, regulatory documents, or primary process sources.
7. Promote spreads from `Missing` to `Needs Research`, then to `Verified` only through recorded editorial gates.
