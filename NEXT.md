# NEXT.md — content-wiki-corporate

> **Scope: this repo only.** Cross-repo and workspace-level open
> items live at `~/Foundry/NEXT.md`.
>
> Read at session start. Update at session end.

Last updated: 2026-05-17.

---

## Currently open

### ⚠ Divergence — cluster clone vs canonical (Master must resolve before Stage 6)

**2026-05-17 audit finding.** The canonical at
`/srv/foundry/customer/content-wiki-corporate` has an independent commit
(`b0c78f6` — "strip topic- prefix; assign governance/reference categories")
that the cluster clone does not have. The canonical uses bare filenames
(`direct-hold-framework.md`); the cluster clone uses `topic-*` prefix
filenames (`topic-direct-hold-framework.md`). These conventions are
incompatible. A plain `git push origin main` from the cluster clone
would conflict.

**Resolution options for Master:**
1. Rebase the cluster clone onto the canonical's commit, then adapt
   the cluster's YAML slug values to use bare slugs.
2. Or: merge the canonical commit into the cluster clone, resolve
   filename convention disagreement, and push to GitHub canonical.

Until resolved: do NOT run `promote.sh` for this repo.

**Other canonical gaps** (things in cluster clone not yet in canonical):
- `leapfrog-facts.yaml` — cluster has it (with `topic-` slugs); canonical has none → DYK panel doesn't render
- `about.md`, `contact.md`, `disclaimers.md` — cluster added these; canonical has none → footer links 404
- `index.es.md` — cluster added; canonical has none → "Leer en Español →" link 404
- `short_description` in all 5 article frontmatter fields

### Stage 6 promotion pending (8 commits on cluster)

8 commits ahead of `origin/main` as of 2026-05-17. After canonical
divergence is resolved, Master runs Stage 6.

Commits ready (most recent first):
- `cad20d0` — fix featured/DYK slugs, category, short_description, wikilinks; add index.es, about, contact, disclaimers
- Previous 7 commits as listed in 2026-05-13 entry below. Master action
required — run `~/Foundry/bin/promote.sh` from
`clones/project-knowledge/content-wiki-corporate/`. After promotion
rebuild binary and restart `local-knowledge-corporate.service` (port 9095).

Commits ready:
- `c65be14` — home-page YAML: featured rotation pool (5-week) + DYK panel
- `16c5563` — DataGraph enrichment pass: consequence-first leads + vocabulary fix
- `b6a8cad` — glossary-corporate: v9 terminology sync
- `e681a92` — Lede-only index.md: strip double-rendered chrome
- `34c767b` — Add featured-topic.yaml pin: redemption-elimination
- `1e819df` — Update home page: fix wikilinks, sentence-case, ENGINE directives

### `.agent/rules/` bootstrap pending

No local rule files yet. Bootstrap order when a session activates
this work:

1. Create `.agent/rules/repo-layout.md` — allowed root files;
   defect-closure procedure for a flat-layout repo.
2. Create `.agent/rules/cleanup-log.md` — open questions and
   in-flight editorial decisions.
3. Update `CLAUDE.md` §6 to point at both files.

### Article backlog

Five active topic pairs (direct-hold-framework, equity-transfer-model,
fiduciary-data-mandate, interest-coverage-ratio, redemption-elimination).
Possible next articles (not committed — surface to operator before starting):

- Corporate entity overview articles (Woodfine Management Corp.,
  Woodfine Capital Projects Inc.)
- Forward-looking roadmap article (planned / intended language only,
  BCSC rule applies)
- Glossary expansion beyond `glossary-corporate.csv`

### BCSC language review

Prior outbox message noted the User Guide (now deleted from wiki)
contained Sovereign Data Foundation current-tense language. A
systematic pass over all five active topic pairs to verify BCSC
compliance is recommended before any public-facing milestone
requiring disclosure review. See `~/Foundry/CLAUDE.md` §6
BCSC posture rule.

---

## Recently closed

- **2026-05-13 — Repo-level `CLAUDE.md` missing.** CLAUDE.md created
  this session; defect closed.

## Pointers

- Workspace-level open items: `~/Foundry/NEXT.md`
- Workspace changelog: `~/Foundry/CHANGELOG.md`
- Content rendering contract: `content-wiki-documentation/.agent/rules/content-contract.md`
