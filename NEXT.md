# NEXT.md — content-wiki-corporate

> **Scope: this repo only.** Cross-repo and workspace-level open
> items live at `~/Foundry/NEXT.md`.
>
> Read at session start. Update at session end.

Last updated: 2026-05-13.

---

## Currently open

### Stage 6 promotion pending

6 commits ahead of `origin/main` as of 2026-05-13. Master action
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
