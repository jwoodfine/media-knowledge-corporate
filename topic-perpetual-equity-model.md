---
schema: foundry-doc-v1
title: "Perpetual Equity Model"
slug: topic-perpetual-equity-model
category: governance
type: topic
content_type: topic
status: active
quality: complete
language_protocol: PROSE-TOPIC
short_description: "The investment framework under which equity is held indefinitely without a fixed redemption horizon."
paired_with: topic-perpetual-equity-model.es.md
audience: public
bcsc_class: public-disclosure-safe
language: en
last_edited: 2026-06-16
see_also:
  - topic-investment-units
  - topic-redemption-elimination
  - topic-direct-hold-framework
---

The Perpetual Equity Model describes the investment framework applied to [[topic-investment-units|investment units]] in named real assets. Under this model, equity is held indefinitely without a fixed redemption horizon, maturity date, or mandatory exit event.

Positions are transferred through the secondary market rather than redeemed by the issuing entity. This structure eliminates redemption queues and liquidity reserves while allowing equity to compound over an indefinite holding period. See [[topic-redemption-elimination|Redemption Elimination]] for the structural rationale.

## Overview

The Perpetual Equity Model is a structural departure from conventional real-asset vehicles that operate on fixed fund cycles of seven to twelve years. By removing the compulsory liquidation event, the model allows the underlying asset to remain under consistent stewardship — capital expenditure decisions, tenant relationships, and financing arrangements are not constrained by the requirement to prepare an asset for forced sale at a predetermined date.

Equity positions are denominated in [[topic-investment-units|investment units]] recorded in the property ledger for each named asset. The number of units in circulation is fixed at issuance; the issuing entity does not issue additional units except through formally documented corporate decisions.

## Secondary Market

Investors who require liquidity identify willing counterparties independently. The corporate entity does not intermediate the exit, maintain a buyback facility, or commit to any form of put right. The secondary market for investment units in a given asset is thin by design — a consequence of the asset-specific, fixed-supply structure rather than a deficiency to be corrected.

Transfer mechanics are straightforward: the seller identifies a counterparty, agrees a price bilaterally, and the property ledger is updated to reflect the new unit holder. No corporate consent is required; no notification period applies to the transfer itself.

## Distribution Policy

Distributions are declared per asset, not across the portfolio. The issuing entity declares distributions from operating income when the asset's interest coverage ratio (ICR) stands at or above 1.2×. A distribution is not declared from an asset below the 1.2× ICR floor; the floor is a covenant established in the applicable direct-hold vehicle's governing agreement that governs borrowing capacity, consistent with the 1.2–1.4× range typical of commercial real-estate lending.

When distributions are declared, they are paid proportionally across all outstanding units of the relevant asset. No unit within the same asset carries a preferential distribution right over another.

## Asset Disposition

Dispositions — sales, refinancings with equity return, or structural reorganisations — are corporate decisions made at the asset level. Proceeds are allocated to unit holders in proportion to their registered unit counts. The Perpetual Equity Model does not prohibit disposition; it removes the compulsory-exit mechanism that drives fund-cycle liquidation.

In a disposition, the property ledger for the relevant asset is closed and final proceeds are distributed. Unit holders receive their proportional share; the asset exits the holding structure. No other asset in the structure is affected.

## Interest Coverage Ratio Constraint

The 1.2× ICR floor is the primary operating constraint that governs the model in practice. Because distributions are suspended below 1.2× and the holding horizon is indefinite, an asset that falls below the floor enters a cash-preservation state: operating income is retained, debt service continues, and the asset is managed toward ratio restoration before distributions resume.

The per-asset ICR measurement is structural: an underperforming asset does not draw on operating income from other properties in the corporate structure. Cross-subsidy is not available.

## The bottom line

The Perpetual Equity Model replaces the fund cycle's compulsory exit with a secondary-market transfer mechanism. For a unit holder, this eliminates forced-sale risk and the bid-ask discount that fixed-fund-cycle vehicles realise at wind-down. The 1.2× ICR floor and per-asset distribution calculation retain cash at the asset level when operating performance is under pressure — a buffer that a pooled vehicle with blended-portfolio distributions would dilute across the portfolio.

## See also

- [[topic-investment-units|Investment Units]]
- [[topic-redemption-elimination|Redemption Elimination]]
- [[topic-direct-hold-framework|Direct-Hold Framework]]
