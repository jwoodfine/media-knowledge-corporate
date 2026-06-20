---
schema: foundry-doc-v1
title: "Investment Units"
slug: topic-investment-units
category: governance
type: topic
content_type: topic
status: active
quality: complete
language_protocol: PROSE-TOPIC
short_description: "The fractional equity units issued in each named real asset under the Direct-Hold framework."
paired_with: topic-investment-units.es.md
audience: public
bcsc_class: public-disclosure-safe
language: en
last_edited: 2026-06-16
see_also:
  - topic-perpetual-equity-model
  - topic-direct-hold-framework
  - topic-property-ledger-technology
---

Investment units are the fractional equity interests issued in each named real asset under MCorp's [[topic-direct-hold-framework|Direct-Hold]] framework. Each investment unit represents a percentage ownership of the specific property — not a share in a pooled fund or a proportional claim on a portfolio.

Units are recorded in the [[topic-property-ledger-technology|property ledger]] for the named asset. They are freely transferable to willing counterparties without requiring corporate approval. The [[topic-perpetual-equity-model|Perpetual Equity Model]] governs the holding horizon for these units.

## Overview

Investment units are asset-specific instruments. A unit issued in one named property carries no claim on, and confers no exposure to, any other property in the MCorp holding structure. This isolation is structural: it derives from the Direct-Hold framework rather than from contractual representation. An investor holding units in three separate assets holds three separate positions with three separate ledgers, three separate operating statements, and three separate distribution entitlements.

## Denomination and Issuance

The unit count for a named asset is established at the time of onboarding and recorded as the fixed supply in the property ledger. Denomination is expressed as a fractional percentage: one unit in a 10,000-unit register represents 0.01 percent of the economic interest in that asset.

The issuing entity does not create additional units without a formally documented corporate resolution. Dilution is therefore not an inherent feature of the instrument; any decision to increase unit supply is a material corporate decision subject to full disclosure to existing unit holders before it takes effect.

## Rights

Each investment unit in a named asset carries three categories of rights.

**Economic rights.** Unit holders receive a proportional share of distributions declared for the relevant asset. Distributions, when declared, are paid in proportion to outstanding unit counts; no unit within the same asset carries a preferential distribution right over another.

**Transfer rights.** Units are freely transferable to willing counterparties. Transfers are recorded in the property ledger in the sequence received; no transfer requires prior consent from the issuing entity or from other unit holders. The transferee acquires the full economic and information rights of the transferor upon ledger settlement.

**Information rights.** Unit holders in a named asset receive periodic operating statements for that asset, including revenue, operating expenses, and the current interest coverage ratio. Information is asset-specific and does not extend to other properties in the corporate holding structure.

## Interest Coverage Ratio

Each asset in the Direct-Hold portfolio maintains an interest coverage ratio (ICR) floor of 1.2× — operating income to debt service — as a self-imposed operating constraint. The ICR is calculated per asset; there is no cross-subsidy between properties. An asset operating between 1.2× and 1.4× ICR is within the range typical of commercial real-estate lending covenants. An asset below 1.2× enters a preservation protocol in which distributions are suspended until the ratio is restored.

The ICR floor is a direct protection for unit holders: it prevents distributions from being drawn from a property whose operating income is insufficient to sustain them. No distribution is declared from an asset whose ICR falls below 1.2×.

## Relationship to the Perpetual Equity Model

Investment units are the instrument through which the [[topic-perpetual-equity-model|Perpetual Equity Model]] is expressed. The perpetual holding horizon — no mandatory exit, no fixed fund cycle — means unit holders do not face a compulsory redemption event. Liquidity is available through the secondary market by identifying a willing counterparty; the corporate entity does not participate in the exit.

## The bottom line

Investment units are asset-specific, fixed-supply instruments with no cross-exposure between properties in the corporate structure. The 1.2× ICR floor suspends distributions before they outpace operating income. Transfers require no corporate consent. For a regulated buyer, the combination of ledger-recorded ownership, structural asset isolation, and an ICR-linked distribution gate provides a predictable framework for permanent equity allocation to named real property.

## See also

- [[topic-perpetual-equity-model|Perpetual Equity Model]]
- [[topic-direct-hold-framework|Direct-Hold Framework]]
- [[topic-property-ledger-technology|Property Ledger Technology]]
