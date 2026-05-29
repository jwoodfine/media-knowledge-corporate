---
schema: foundry-doc-v1
title: "Direct-Hold Framework"
slug: topic-direct-hold-framework
short_description: "A legal structure that issues asset-specific equity: each investor holds a fractional interest in a single named property, not a share in a commingled pool, eliminating cross-asset contagion."
category: governance
type: reference
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-direct-hold-framework.es.md
cites: []
---

The Direct-Hold framework is a legal ownership structure under which each investor holds a defined fractional interest in a single named [[topic-property-ledger-technology|property ledger]] rather than a proportional claim on a commingled pool. Each asset is constituted as an independent legal and financial unit, so a financial event affecting one asset cannot propagate to an investor's equity position in another. This article describes the framework's legal structure, the isolation mechanism, [[topic-equity-transfer-model|transfer and liquidity terms]] between investors, the [[topic-fiduciary-data-mandate|fiduciary data obligations]] that protect ledger integrity, and the [[topic-interest-coverage-ratio|interest coverage discipline]] applied per asset.

<!--claim id=asset-specific-equity confidence=structural cites=[]-->The framework issues property-specific equity: each investor holds a defined fractional interest in a single named property ledger, not a share in a commingled fund.<!--/claim-->

<!--claim id=independent-units confidence=structural cites=[]-->Each asset is its own legal and financial unit, isolated as an independent vehicle. A financial event affecting one asset cannot propagate to an investor's equity in another; the isolation is a property of the architecture, not a contractual promise.<!--/claim-->

## What it replaces

A traditional commercial real-estate fund operates on commingled capital. The fund holds many properties; an investor's share entitles them to a proportional claim on the pool, not on any specific asset. <!--claim id=pool-manager-discretion confidence=structural cites=[]-->The pool manager determines distributions, liquidity windows, and when assets are sold; the investor cannot consent to or dissent from any individual asset decision.<!--/claim--> This is the role the [[topic-principal-manager-role|principal manager role]] inverts under Direct-Hold: investor consent attaches to the specific asset rather than to a pooled vehicle.

The Direct-Hold framework removes the pool. Each property is its own legal and financial unit, and the investor is a direct equity holder in the specific asset they selected. There is no co-mingling with other properties and no fund-manager discretion over their capital.

## Legal isolation

<!--claim id=structural-isolation confidence=structural cites=[]-->Strict legal separation is structural. Each asset ledger is isolated as an independent vehicle, so a financial event affecting one asset — vacancy, litigation, refinancing — cannot propagate to the investor's equity in a different asset.<!--/claim-->

The isolation is a property of the architecture rather than of a contractual promise. An investor evaluating one asset's risk does not have to model the rest of a portfolio.

## Transfer and liquidity

<!--claim id=private-transfer confidence=structural cites=[]-->Equity transfers in the Direct-Hold model execute between private parties. There is no [[topic-redemption-elimination|redemption queue]], no liquidity window managed by the corporate entity, and no pooled cash reserve held to satisfy redemption requests.<!--/claim-->

An investor who wishes to exit locates a willing counterparty directly; the enterprise does not intermediate the process. The structure carries no pooled redemption obligation, so no asset is sold under pressure to fund another investor's exit.

## Governance

<!--claim id=asset-level-governance confidence=structural cites=[]-->Because each investor holds direct equity in a named asset, governance rights attach to that specific property. Investor consent mechanisms operate at the asset level, not at a portfolio-aggregation level.<!--/claim--> The [[topic-perpetual-equity-model|perpetual equity model]] applies these mechanisms to fractional [[topic-investment-units|investment units]] held without a fixed redemption horizon.

## See also

- [[topic-equity-transfer-model|Equity Transfer Model]] — how ownership interests in Direct-Hold assets change hands
- [[topic-fiduciary-data-mandate|Fiduciary Data Mandate]] — data governance requirements for the property ledger
- [[topic-interest-coverage-ratio|Interest Coverage Ratio]] — the debt-management constraint applied per asset
- [[topic-redemption-elimination|Redemption Elimination]] — why no redemption queue exists in this structure

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licensed under [Creative Commons Attribution-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nd/4.0/).*
