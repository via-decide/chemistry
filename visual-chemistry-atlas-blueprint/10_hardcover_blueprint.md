# Visual Chemistry Atlas — Hardcover Production Blueprint

## Operating pipeline

SOURCE
↓
`via-decide/chemistry` at commit `4fa3d18928395d0216c4940d32e5c366f3a4e13c`
↓
ACCESS / ENTRY
↓
645-file exhaustive repository inventory plus official-source spot checks
↓
INTENT CAPTURE
↓
Premium full-color visual reference atlas; deterministic pages; no unsupported claims or illustrations
↓
STATE / LOGIC ENGINE
↓
Normalized dependency graph + source registry + three-state page gate + unique figure registry
↓
ACTIONS
↓
Citation mismatch gate passed → fill missing schema and prerequisites → verify equations/mechanisms → commission art → science proof → print proof
↓
OUTPUT / METRICS
↓
184 spreads / 368 pages / 40 chapters / 184 dominant visuals

## Target publication specification

This specification is locked as the editorial and costing target. Paper, signature, hinge, and spine values remain `Needs verification` until a named print partner approves a bound dummy and manufacturing worksheet.

| Attribute | Specification |
| --- | --- |
| Trim | 240 × 300 mm portrait |
| Interior | 368 pages; 23 signatures × 16 pages |
| Binding | Sewn case binding, square back, reinforced hinges |
| Paper | 130–135 gsm matte/silk coated archival stock; opacity proof required |
| Color | CMYK process with spot-proofed hazard and verification colors |
| Bleed | 3 mm; 8 mm minimum live-area margin; 18 mm binding-side safe zone |
| Grid | 12-column spread grid; 6 columns per page; 4 mm baseline; modular 8 mm spacing |
| Typography | Humanist sans for navigation; high-legibility serif or sans for body; monospaced/tabular numerals for data |
| Body copy | 9.5–10.5 pt, 13–14 pt leading; 55–75 characters per line |
| Captions/labels | 7.5 pt minimum at final size |
| Dominant visual | Exactly one per spread; figure ID `FIG-001` through `FIG-184` |
| Page identity | Stable spread ID + edition-specific page range + source packet version |
| Accessibility | Color plus shape/pattern encoding; alt text and label list for every figure |

## Platform and manufacturing gate

The primary 240 × 300 mm sewn-case edition is a custom-printer product, not an Amazon KDP hardcover. KDP currently supports 8.25 × 11 in as its largest comparable hardcover trim, premium color rather than standard color, and case-laminate construction without a dust jacket. A KDP edition would therefore be a separately repaginated SKU, not the same production file.

| Route | Status | Release condition |
| --- | --- | --- |
| Custom premium hardcover | **Needs verification** | Printer confirms 240 × 300 mm trim, 23 × 16-page signatures, paper bulk/opacity, sewn-case construction, bleed, hinge, spine, and color proof |
| KDP derivative | **Unavailable from this layout** | Rebuild at 8.25 × 11 in, choose premium color and case laminate, recalculate margins and pagination, then generate the cover from the final page count |

Authoritative checks: [KDP trim, page-count, bleed, and margin options](https://kdp.amazon.com/help/topic/GVBQ3CMEQW3W2VL6); [KDP case-laminate hardcover requirements](https://kdp.amazon.com/help/topic/GAVW3FZZAKA2KY3B); [KDP color options](https://kdp.amazon.com/help/topic/GX56BFPW4BKNPGFW); [KDP cover calculator](https://kdp.amazon.com/cover-calculator).

## Mandatory page template

Every content page uses the following blocks in this exact order. Facing pages share one main visual, but both pages retain the same ordered content slots in the production XML/Markdown record. If a slot is not supported, it is marked `Unavailable` and the page remains blocked; the slot is never removed or silently filled.

```text
Title

One-line summary

Main visual

Key concept

Scientific explanation

Industrial relevance

Common misconception

Research corner

QR codes

Cross references
```

### Block explanations

| Block | Production rule |
| --- | --- |
| Title | Maximum 8 words; names the scientific object or relationship, not a slogan |
| One-line summary | One falsifiable or bounded statement; maximum 25 words |
| Main visual | The single dominant figure from the page map and visual register |
| Key concept | Controlled term or model with source ID |
| Scientific explanation | Mechanism, causal structure, equation assumptions, or evidence boundary; no unsupported simplification |
| Industrial relevance | Named process, instrument, material, control, or decision with explicit system boundary |
| Common misconception | Repository misconception record plus corrective explanation and evidence; `Unavailable` blocks final page |
| Research corner | Paper or standard contextualized by question, method/evidence, date, limitation, and relation to page |
| QR codes | Maximum two; only versioned registry destinations with rights and persistence owner |
| Cross references | Stable topic slug plus printed page range; bidirectional validation required |

## Book metadata estimate

| Metric | Planned | Repository-ready now | Gap / rule |
| --- | ---: | ---: | --- |
| Total spreads | 184 | 184 mapped | Fixed |
| Total interior pages | 368 | 368 mapped | Fixed; cover and endpapers excluded |
| Topic chapters | 40 | 40 directories | Fixed |
| Dominant illustrations | 184 | 0 existing | All custom; one per spread |
| Custom diagrams excluding comparison tables/full-page art | 168 | 0 existing | Commission only after source packet gate |
| Dominant comparison-table spreads | 15 | 15 repository table objects | Existing tables require editorial normalization |
| Equation targets | 120 metadata slots | 15 explicit equation records | 105 slots need extraction/verification |
| Deduplicated research/source records | 197 | 197 inventoried | Status varies; see reference matrix |
| QR codes | Up to 64 placements; 32 unique verified source destinations currently eligible | 32 unique eligible destinations | Maximum two per spread; no QR for unverified sources |
| Glossary entries | 397 candidates | 397 extracted candidates | Definitions remain gated by terminology sources |
| Index size | 1,200–1,500 entries/locators across 10 pages | Topic and term locators mapped | Final figure, equation, equipment, process, people, and industry subentries added after copy edit |
| Equation locator | 2 pages | 15 explicit records | Expand only after equation audit |
| Source/standards map | 2 pages | Source registry built | Print only stable organizations and evaluated datasets |

## Page-state gate

| State | Topic spreads | Allowed work | Exit condition |
| --- | ---: | --- | --- |
| Verified | 42 | Detailed design, science illustration, and copy fitting | Claim/source trace, page template completeness, and SME approval |
| Needs Research | 74 | Wireframe, source packet assembly, and content repair | All mandatory source classes resolved or explicitly unavailable with editorial approval |
| Missing | 44 | No illustration; backlog only | Missing equation, mechanism, misconception, or schema record added and verified |

## Research-paper placement contract

A research paper may enter a page only when all fields exist: source ID; exact title; authors; publication; year/date; DOI or stable URL; paper type; peer-review state where relevant; page question; evidence used; limitation; relationship to prior concepts; and QR rights/persistence state. A paper title or link without this context remains in the reference matrix and never appears on a designed page.

## Production stages and acceptance metrics

| Stage | Output | Acceptance metric |
| --- | --- | --- |
| 0. Repository repair | Canonical schema, graph, evidence IDs, and corrected links | Zero semantic link mismatches; zero missing required files; zero duplicate canonical IDs |
| 1. Scientific source packets | One packet per spread | Every callout traceable to a verified source or marked unavailable |
| 2. Low-fidelity layout | 184 wireframes | Template order present; one dominant visual; page budget respected |
| 3. Illustration | Editable masters and label lists | 100% figure IDs; SME markup closed; no unreferenced labels |
| 4. Copy fitting | Page records and captions | No overset; equations unit-checked; cross-references resolve bidirectionally |
| 5. Science proof | Annotated PDF proof | Zero P0 scientific errors; all P1 items dispositioned |
| 6. Print proof | Wet/digital contract proof and bound dummy | Color, line, type, gutter, opacity, and QR scan pass |
| 7. Edition release | Print files, source registry, errata endpoint | Checksums, rights, version, and correction owner recorded |

## Risks / failure modes

- Citation corruption can make a scientifically correct sentence unpublishable because the supplied evidence does not support it.
- Equal four-spread allocation may expose sparse topics; the correct response is to hold the page, not inflate it with generic chemistry.
- Visual consistency can become scientific sameness. Reusing grammar is allowed; reusing an explanatory diagram or changing only labels is prohibited.
- Industrial cutaways may imply proprietary or unsafe process details. Show principle-level boundaries unless an authoritative public source supports detail.
- QR destinations can rot or redirect. Use a maintained registry that stores canonical URL, archived fallback where lawful, last check, and edition.
- A 368-page 240 × 300 mm book is heavy. Paper, hinge, gutter, and lay-flat performance require a bound dummy before final imposition.
- Formula density can overwhelm visual pages. Equation walkthroughs must state variables, units, assumptions, and limits rather than add derivations indiscriminately.

## Monetisation logic

- Primary product: premium hardcover reference atlas with durable visual and industrial differentiation.
- Leverage: the same source packets, figure masters, glossary, index, and cross-reference graph can power licensed classroom posters, chapter PDFs, slide assets, and the Alchemist app without rewriting chemistry.
- Defensibility: source traceability, editioned QR registry, industrial context, and reviewed scientific illustration are the monetizable system; generic page count is not.
- Cost control: do not commission final art for `Needs Research` or `Missing` spreads. This prevents expensive redraws after science review.

## Feasibility + effort

| Workstream | Effort class | Dependency |
| --- | --- | --- |
| P0 schema and source-packet repair | High | Immediate; citation mismatch gate passed, remaining contract gaps block production |
| Prerequisite bridge research | Medium–high | Required before dependent copy |
| Equation and mechanism extraction | High | Required before quantitative/mechanistic art |
| 184 illustration commissions | Very high | Starts only on verified source packets |
| Copy, indexing, QR registry, proofing | High | Parallel after 60–70% figures stabilize |
| Printing and binding | Standard premium-book workflow | Requires color proof and bound dummy |

A realistic execution model is 9–15 months with a managing editor, chemistry lead, subject reviewers, research editors, art director, 2–4 scientific illustrators, technical production designer, copy editor/indexer, and print-production partner. Faster delivery requires reducing scope, not bypassing verification.

## Verdict

**CHANGE.** The repository is suitable as an evidence-oriented seed corpus and has now been converted into a deterministic production map. The later-batch semantic citation contamination is repaired, but missing schema, equations, mechanisms, misconceptions, prerequisites, and visuals still block unrestricted page design.

## One next action

Restore the four missing contract records and canonical front matter for each of the 20 later-batch topics, preserving the now-zero semantic source/link mismatch gate.
