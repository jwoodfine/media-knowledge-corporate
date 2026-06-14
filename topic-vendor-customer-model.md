---
schema: foundry-doc-v1
title: "Vendor-Customer Model"
slug: topic-vendor-customer-model
aliases:
  - topic-vendor-customer-model
short_description: "Structural separation between PointSav Digital Systems as technology vendor and Woodfine Management Corp. as commercial real estate operator and technology customer."
category: company
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-vendor-customer-model.es.md
cites: []
---

PointSav Digital Systems occupies the vendor role; Woodfine Management Corp. occupies the customer role within the [[topic-corporate-structure|Woodfine corporate structure]]. PointSav delivers technology platform services — [[topic-property-ledger-technology|property ledger]] infrastructure, investor portal, software maintenance — and WMC directs platform requirements, holds data custody under the [[topic-fiduciary-data-mandate|Fiduciary Data Mandate]], and is solely accountable for investment and fiduciary decisions affecting [[topic-direct-hold-framework|Direct-Hold]] assets.

## Vendor obligations

PointSav's obligations under the [[topic-technology-services|technology services agreement]] are operational and technical. The vendor is responsible for platform availability, software integrity, security posture, and ledger data consistency. PointSav does not exercise discretion over what data is stored, how it is classified, or how it is used — those decisions belong to WMC as the data custodian.

PointSav does not represent WMC to investors or regulators. PointSav does not provide compliance advice, investment advice, or fiduciary services. The vendor's scope ends at the platform boundary.

## Customer rights

WMC retains full legal custody of all data processed by the platform — see [[topic-data-governance|Data Governance]] for the full custody framework. If WMC engages a different technology provider, the property ledger data is portable — it does not remain with PointSav. The architecture is designed so that WMC can reconstruct full operational control of the ledger from exported data without dependency on any specific software implementation.

WMC directs the platform requirements. PointSav builds and maintains to those requirements. The customer determines what the platform does; the vendor determines how.

## Separation of failure modes

In a commingled structure — where a technology provider also participates in capital management — a failure in one domain compounds into the other. A technology outage affecting a platform operator who also manages capital creates simultaneous operational and financial risk.

The vendor-customer separation prevents this compounding. A technology failure at PointSav does not affect WMC's legal title to assets or the validity of equity records. A financial event at WMC does not interrupt PointSav's ability to maintain platform infrastructure. The failure modes are structurally isolated.

## Not a marketing relationship

PointSav does not market WMC's investment products, and WMC does not promote PointSav's technology platform as part of investor communications. The relationship is a services agreement, not a joint venture. Neither entity holds equity in the other's core business operations.

## See also

- [[topic-corporate-structure|Corporate Structure]] — the ownership relationship between both entities
- [[topic-technology-services|Technology Services Agreement]] — structure of the services contract between PointSav and WMC
- [[topic-data-governance|Data Governance]] — WMC's data custody obligations under the vendor-customer model

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licensed under [Creative Commons Attribution-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nd/4.0/).*
