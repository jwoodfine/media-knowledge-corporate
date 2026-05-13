# content-wiki-corporate — Repo Guide

> Repo-level complement to `~/Foundry/CLAUDE.md`.
> A session that opens here inherits the workspace guide and
> then applies the repo-specific rules below. Read cold at
> session start.

Last updated: 2026-05-13.

---

## 1. What this repo is

`content-wiki-corporate` holds the corporate documentation wiki
for Woodfine Management Corp. as flat Markdown content. Scope:

- Topic articles covering equity structures, direct-hold
  frameworks, fiduciary mandates, redemption models, and related
  institutional themes.
- A repo-root `index.md` serving as the wiki home.
- `featured-topic.yaml` and `leapfrog-facts.yaml` consumed by the
  wiki engine for homepage rotation and the leapfrog-facts panel.
- `glossary-corporate.csv` — corporate terminology master list.

This repo is **content only**. No code. No compiled binaries.

Classification per workspace §8: **content-wiki repo** — flat
collection, no project registry. The per-project-cluster
mechanism does not apply; sessions operate as Root Claude.

**Flat layout.** Unlike `content-wiki-documentation`, this repo
does not use category subdirectories. Articles live at repo root.
The `topic-*` filename prefix is canonical here (five active pairs
plus `index.md`).

Served at `corporate.woodfinegroup.com` via
`local-knowledge-corporate.service` (port 9095).

## 2. Role expectations

A session in this repo is **Root Claude for
`content-wiki-corporate`**. Scope of writes:

- `CLAUDE.md` (this file), `NEXT.md` — repo metadata.
- `index.md`, `featured-topic.yaml`, `leapfrog-facts.yaml`,
  `glossary-corporate.csv` — homepage and glossary maintenance.
- `topic-*.md` and `topic-*.es.md` — article authorship and
  refinement.

Out of scope:

- Workspace files under `~/Foundry/`.
- Code in the monorepo.
- Direct pushes to canonical `origin` (see §4).

## 3. Audience and voice

Articles address an **institutional finance audience** — investment
bankers, asset managers, portfolio managers, and auditors reviewing
Woodfine Management Corp. holdings and structures. Prose standard:
Bloomberg / Financial Times institutional register. No marketing
vocabulary, no AI-product language.

Every article is written as if a Goldman Sachs banker will read it
cold. Clear noun phrases; consequence-first sentences; no hedges.

## 4. Commit flow

Staging-tier repo. Same flow as `content-wiki-documentation`:

- `~/Foundry/bin/commit-as-next.sh "<message>"` — alternates
  `jwoodfine` / `pwoodfine` identities per commit.
- `git add <specific files>` — never `git add .` or `-A`.
- Push deferred to Stage 6 (`~/Foundry/bin/promote.sh`). Do not
  push directly to canonical.

| Remote | Target |
|---|---|
| `origin` | `woodfine/content-wiki-corporate` — canonical; Stage 6 only |
| `origin-staging-j` | `jwoodfine/content-wiki-corporate` |
| `origin-staging-p` | `pwoodfine/content-wiki-corporate` |

## 5. Content rules

- **Bilingual.** Every article has an EN `.md` and an ES `.es.md`
  strategic-adaptation pair. `index.md` / `index.es.md` both
  maintained. Operational files (CLAUDE.md, NEXT.md) are
  English-only.
- **BCSC disclosure rule (critical).** This wiki is publicly
  served. Sovereign Data Foundation is referenced in
  **planned / intended** terms only — never as a current equity
  holder, active auditor, or governance body. Every article and
  the `index.md` lede must satisfy this rule. If in doubt, flag
  and do not publish.
- **Canonical names.** Nomenclature Matrix names verbatim.
  No synonyms, no legacy terms.
- **No competitor names.** Never name competitors. Use category
  descriptions (e.g., "managed real-estate platforms").
- **Edit in place.** No `_V2` files. Git history is the record.
- **ADR hard rules:** SYS-ADR-07, SYS-ADR-10, SYS-ADR-19.

## 6. Local rules

`.agent/rules/` bootstrap is pending (open item in NEXT.md).
Until that directory exists, this CLAUDE.md is the sole local
rule source. When bootstrapped, add at minimum:

- `repo-layout.md` — allowed root files and defect procedure.
- `cleanup-log.md` — in-flight decisions.

## 7. Where to look next

- `NEXT.md` — repo-scope open items.
- `~/Foundry/CLAUDE.md` — workspace guide (inherited).
- `content-wiki-documentation/.agent/rules/content-contract.md`
  — the shared article rendering contract; applies here too.
- `~/Foundry/NOTAM.md` — time-sensitive workspace warnings.
