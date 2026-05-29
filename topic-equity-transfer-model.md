---
schema: foundry-doc-v1
title: "Equity Transfer Model"
slug: topic-equity-transfer-model
short_description: "Peer-to-peer transfer mechanism that allows investors to exit their position directly to willing counterparties, without requiring a liquidity pool or corporate buyback."
category: governance
type: reference
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-equity-transfer-model.es.md
cites: []
---

Woodfine [[topic-direct-hold-framework|Direct-Hold]] equity transfers freely between private parties; the corporate entity records the change but does not approve or intermediate it. Two structural principles govern the model: freely transferable equity and strict peer-to-peer execution — no corporate intermediation, no liquidity windows. The model relies on the [[topic-fiduciary-data-mandate|fiduciary data mandate]] for ledger integrity and operates alongside the [[topic-interest-coverage-ratio|interest coverage ratio]] discipline applied at the asset level.

## Freely transferable equity

Woodfine Management Corp. issues freely transferable private equity in each isolated [[topic-property-ledger-technology|property ledger]]. "Freely transferable" means the holder may offer their interest to any willing counterparty without requiring corporate approval for the transfer itself. The corporate entity maintains the ledger but does not control who may acquire equity in it. Each unit of equity issued constitutes an [[topic-investment-units|investment unit]] in the named asset.

This distinguishes the model from restricted-equity structures — common in private real estate vehicles — where the issuer retains right of first refusal, imposes transfer restrictions, or requires investor qualification re-approval on each transfer.

## Peer-to-peer execution

Transfer execution is strictly between private parties. The corporate entity does not maintain a secondary market, a matched-order book, or a buyback facility. An investor seeking liquidity locates a willing counterparty through their own commercial relationships or through broker-dealer channels that operate independently of the corporate entity.

## No subjective liquidity requirements

Traditional fund structures impose redemption gates, liquidity reserves, and lock-up periods subject to fund manager discretion. The Equity Transfer Model contains none of these mechanisms — see [[topic-redemption-elimination|Redemption Elimination]] for the structural rationale. Liquidity terms are determined by the market of willing buyers, not by corporate entity policy. The [[topic-perpetual-equity-model|perpetual equity model]] applies the same logic over an indefinite holding horizon.

## Ledger integrity

The asset ledger records each transfer with a full chain of title. Ownership of a fractional interest is a ledger entry, not a paper certificate. The mathematical integrity of the ledger is maintained by the corporate entity's fiduciary data systems — described further in [[topic-fiduciary-data-mandate|Fiduciary Data Mandate]].

## See also

- [[topic-direct-hold-framework|Direct-Hold Framework]] — the ownership structure that makes equity freely transferable
- [[topic-fiduciary-data-mandate|Fiduciary Data Mandate]] — data governance requirements that underpin ledger integrity
- [[topic-redemption-elimination|Redemption Elimination]] — why no corporate buyback facility exists

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licensed under [Creative Commons Attribution-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nd/4.0/).*
