# Chemistry Knowledge Base

Canonical, source-traceable chemistry research corpus for downstream generation systems.

## Repository Contract

- Topic records live under `research/<topic-slug>/`.
- Every Markdown record starts with YAML front matter.
- Verified knowledge records use claim blocks that reference stable evidence identifiers.
- Evidence is stored once per topic in `references.md` and referenced elsewhere by ID.
- Future work belongs only in `research-queue.md`.
- Educational exposition, tutorials, and simplified summaries are out of scope.
- Mirror sources are retained only when the original source was not present in collected source data; preferred-source replacement is recorded in notes or the research queue.

## Required Topic Files

Each topic directory contains:

- `overview.md`
- `history.md`
- `fundamentals.md`
- `mathematics.md`
- `equations.md`
- `terminology.md`
- `laboratory.md`
- `industrial.md`
- `applications.md`
- `common-misconceptions.md`
- `research-frontier.md`
- `research-queue.md`
- `references.md`
- `metadata.yaml`
