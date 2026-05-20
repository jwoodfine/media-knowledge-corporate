# Cleanup Log — content-wiki-corporate

Living record of in-flight cleanup work, open questions, and decisions.
Read at session start. Update when meaningful cleanup occurs.

Last updated: 2026-05-20.

---

## Active issues

### ⚠ Cluster-clone / canonical convention divergence (Master must resolve)

The canonical at `/srv/foundry/customer/content-wiki-corporate/` uses bare filenames
(`direct-hold-framework.md`). The cluster-clone uses `topic-*` prefix filenames
(`topic-direct-hold-framework.md`). These are incompatible — a plain git push from
the cluster-clone would conflict.

Canonical also lacks: `leapfrog-facts.yaml`, `about.md`, `contact.md`,
`disclaimers.md`, `index.es.md`, `short_description` fields, and all
C8–C10 content.

Resolution: Master Session must rebase or merge to reconcile the convention, then promote via Stage 6.
Until resolved: do NOT run `promote.sh` for this repo.

### BCSC language review (recommended before public milestone)

The five original financial topic pairs (direct-hold-framework, equity-transfer-model,
fiduciary-data-mandate, interest-coverage-ratio, redemption-elimination) were authored
prior to the formal BCSC posture codification. A systematic pass to verify forward-looking
language discipline is recommended before any public-facing disclosure review milestone.
No known violations — this is a precautionary verification.

---

## Recently closed

### 2026-05-20 — C8–C10: 10 new topics + ES bilingual pairs

`cb53200` (Peter, 2026-05-20): 4 company-identity topics + 6 operational topics + 10 ES
bilingual pairs. Closes the article-backlog open item from NEXT.md §Article backlog.

### 2026-05-20 — YAML expansion + about.md scope update

featured-topic.yaml rotation pool expanded to 15 topics. leapfrog-facts.yaml expanded to
9 facts. about.md content scope updated to reflect the 15-article corpus.

### 2026-05-20 — .agent/rules/ bootstrap

repo-layout.md and cleanup-log.md (this file) created. Closes the bootstrap pending item
from NEXT.md.

---

## Open questions

None currently — surface here when editorial decisions are deferred.
