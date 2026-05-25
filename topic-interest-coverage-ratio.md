---
schema: foundry-doc-v1
title: "Interest Coverage Ratio"
slug: topic-interest-coverage-ratio
short_description: "Debt-service metric requiring operating income to cover interest charges by at least 1.2×, balancing borrowing capacity against covenant compliance."
category: reference
type: reference
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-interest-coverage-ratio.es.md
cites: []
---

A minimum 1.2x interest coverage ratio constrains every Woodfine Direct-Hold asset — no new debt may be issued that would reduce operating-income-to-interest coverage below this floor. The constraint is self-imposed by the corporate entity as a fiduciary discipline; no external lender covenant requires it.

## What the ratio measures

ICR is the ratio of earnings before interest and taxes (EBIT) to total interest obligations. An ICR of 1.2 means the portfolio generates 1.2 dollars of operating income for every dollar of interest owed. At exactly 1.0, income covers interest exactly. Below 1.0, the portfolio cannot service its debt from operating income without drawing on capital reserves.

The 1.2 floor provides a 20% operating buffer. A vacancy rate increase, a maintenance expense spike, or a short-term tenant disruption can reduce income without breaching the interest obligation.

## Why 1.2

The 1.2 threshold is a deliberate structural choice, not a regulatory minimum. Traditional commercial real estate lending typically requires ICR covenants in the 1.2–1.4 range. At 1.2, the corporate entity accepts a tighter margin in exchange for higher borrowing capacity — maximizing the deployable asset base while maintaining the mathematical assurance that operating income covers debt.

## Relationship to asset protection

The ICR floor is the primary mechanism by which the Direct-Hold architecture protects physical assets from foreclosure. A corporate entity that allows its ICR to fall below 1.0 enters a state where debt service depends on capital drawdowns — a structurally unstable condition. The 1.2 constraint prevents this by design.

A foreclosure event in one asset vehicle cannot propagate to others because each asset is legally isolated. The ICR applies per-vehicle — it cannot be satisfied by cross-subsidizing a weak asset with a strong one.

A portfolio that maintains 1.2x ICR indefinitely avoids forced asset sales triggered by debt-service shortfalls, preserving long-term equity value without requiring capital injections.

## See also

- [[topic-direct-hold-framework]] — the ownership structure that the ICR constraint protects
- [[topic-redemption-elimination]] — why no cash reserve pool exists alongside the ICR floor
- [[topic-fiduciary-data-mandate]] — the parallel data-sovereignty discipline applied to every Direct-Hold asset

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licensed under [Creative Commons Attribution-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nd/4.0/).*
