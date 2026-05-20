# Repo Layout — content-wiki-corporate

Canonical rule for what files belong at the repo root.
Read at session start. Update only when the rule itself changes.

Last updated: 2026-05-20.

---

## Root — allowed files

| File | Purpose |
|---|---|
| `CLAUDE.md` | Repo-scope guide (references workspace AGENT.md) |
| `CODE_OF_CONDUCT.md` | Required by GitHub org |
| `LICENSE` | Repo licence |
| `NEXT.md` | Repo-scope open items |
| `README.md` | English README |
| `README.es.md` | Spanish README (bilingual pair) |
| `TRADEMARK.md` | Trademark notice |
| `index.md` | Wiki home page (engine renders at `/`) |
| `index.es.md` | Spanish home page |
| `about.md` | About this wiki |
| `contact.md` | Contact information |
| `disclaimers.md` | Disclosure and liability disclaimers |
| `featured-topic.yaml` | Home-page featured article pin |
| `leapfrog-facts.yaml` | Home-page DYK panel facts |
| `glossary-corporate.csv` | Term glossary |
| `topic-*.md` | Wiki articles (English) |
| `topic-*.es.md` | Wiki articles (Spanish bilingual pairs) |

Not allowed at root: scripts, data files, zip/tar archives, loose research notes, stray operational documents.

## `.agent/` directory

`.agent/` holds session state and rules. Contents:
- `inbox.md`, `outbox.md` — mailbox
- `rules/repo-layout.md` (this file)
- `rules/cleanup-log.md` — open editorial decisions

## Defect closure

If a file appears at root that is not in the allowed list:
1. Determine its correct home (a sibling repo or a subdirectory).
2. Move with `git mv` (intra-repo) or add-and-remove (cross-repo).
3. Log the closure in `cleanup-log.md`.
Do not loosen this rule to accommodate a misplaced file.
