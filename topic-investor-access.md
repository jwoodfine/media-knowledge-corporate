---
schema: foundry-doc-v1
title: "Investor Access"
slug: topic-investor-access
aliases:
  - topic-investor-access
short_description: "How investors in Direct-Hold assets access position data, financial reports, and ledger records through the WMC investor portal."
category: operations
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-investor-access.es.md
cites: []
---

An investor in a WMC [[topic-direct-hold-framework|Direct-Hold]] asset holds a position in a specific named property. Access to position data, financial reports, and transaction records is provided through the investor portal operated by Woodfine Management Corp. The portal reflects the investor's [[topic-property-ledger-technology|ledger]] position — equity percentage, financial event history, and transfer records — for each asset in which they hold a position. The position is structured as a fractional [[topic-investment-units|investment unit]] in the named asset.

## Position data

Position data represents the investor's current fractional equity in the named asset: the percentage held, the date of acquisition, the acquisition cost recorded on the ledger, and the cumulative financial event history since acquisition. Position data is specific to the asset — it does not aggregate across multiple Direct-Hold positions. Each asset is its own financial and legal unit.

## Financial reports

WMC provides investors with periodic financial reports for each asset in which they hold a position. Reports cover asset-level performance: occupancy rate, rental income, debt service, distributions, and net operating income. Reports do not aggregate across assets; each report corresponds to a single asset and a single investor's position in that asset.

The frequency and format of financial reports is governed by WMC's investor communications standards, consistent with the [[topic-continuous-disclosure|disclosure obligations]] applicable under NI 51-102. Where financial events trigger material change reporting, that disclosure occurs through SEDAR+ as well as through the portal.

## Transfer records

When an investor transfers equity to a counterparty under the [[topic-equity-transfer-model|Equity Transfer Model]], the ledger records the transaction: timestamp, transferring party identity, acquiring party identity, and the percentage transferred. The transferring investor receives confirmation of the completed transaction. The acquiring investor receives an updated position statement reflecting the new equity percentage.

WMC updates the ledger to reflect the transfer. WMC does not approve or broker transfers between private parties — its role is to record the transaction accurately on the ledger and confirm the updated positions to both parties.

## No secondary market

WMC does not operate a secondary market, a matched-order book, or a buyback facility — see [[topic-redemption-elimination|Redemption Elimination]] for the structural rationale. Investors seeking liquidity identify a willing counterparty independently. The corporate entity does not intermediate this process and makes no representation about the availability or pricing of private liquidity for any specific asset.

Broker-dealer channels that operate independently of the corporate entity may be engaged by investors to arrange transfers; WMC makes no representation about the suitability, availability, or cost of such channels.

## Portal access

Portal access is credential-based. WMC is responsible for investor authentication and for provisioning and revoking portal access. PointSav maintains the portal infrastructure; WMC controls who is provisioned access and under what conditions. Credentials are issued at the time an investor completes the onboarding process for a specific asset.

## See also

- [[topic-equity-transfer-model|Equity Transfer Model]] — the mechanics of peer-to-peer equity transfers in Direct-Hold assets
- [[topic-continuous-disclosure|Continuous Disclosure Obligations]] — the OSC reporting requirements that govern financial disclosures made through the portal
- [[topic-property-ledger-technology|Property Ledger Technology]] — the technical infrastructure that maintains position data and financial event history

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licensed under [Creative Commons Attribution-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nd/4.0/).*
