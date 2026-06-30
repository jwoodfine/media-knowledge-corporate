---
schema: foundry-doc-v1
title: "Corporate Structure"
slug: topic-corporate-structure
aliases:
  - topic-corporate-structure
short_description: "Three-entity structure under Woodfine Capital Projects Inc., separating the technology vendor from the commercial real estate operator."
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
paired_with: topic-corporate-structure.es.md
cites: []
---

Woodfine Capital Projects Inc. is the federally incorporated Canadian parent company holding two wholly-owned subsidiaries: PointSav Digital Systems and MCorp. The three entities occupy distinct roles — ownership, technology, and commercial operations — that do not overlap. The arrangement implements the [[topic-vendor-customer-model|vendor-customer model]] at the corporate level and underpins the [[topic-direct-hold-framework|Direct-Hold framework]] under which WMC operates, with [[topic-fiduciary-data-mandate|fiduciary data custody]] held by WMC and platform services delivered by PointSav.

## Key takeaways

- Three entities occupy non-overlapping roles: Woodfine Capital Projects Inc. provides governance and ownership; PointSav Digital Systems delivers technology services; MCorp manages investor relations, originates and governs direct-hold limited partnerships, and operates as fiduciary data custodian.
- PointSav cannot make investment decisions and does not hold equity in managed properties; WMC cannot modify platform code — the separation is enforced at the corporate boundary, not by contract alone.
- The design intent is that an operational failure at PointSav does not impair WMC's fiduciary function, and a financial event at WMC does not impair PointSav's platform operations.

## Parent entity

Woodfine Capital Projects Inc. is incorporated under the Canada Business Corporations Act (CBCA), with its registered office in British Columbia. It is the 100% owner of both subsidiaries and provides the governance framework within which each operates. The parent entity does not itself manage real estate assets or develop technology products. Its function is structural: it holds the ownership relationship and sets the policy framework that governs the two operating entities below it.

## Technology vendor

PointSav Digital Systems is a wholly-owned subsidiary of Woodfine Capital Projects Inc. PointSav develops and maintains the [[topic-property-ledger-technology|property ledger]] platform, investor portal, and data infrastructure that the commercial operator uses to manage Direct-Hold assets, under the [[topic-technology-services|technology services agreement]].

PointSav does not hold equity in any managed property. PointSav does not make investment decisions and does not manage investor relations. Its mandate is confined to technology: platform development, ledger integrity, security posture, and system availability. Investment and capital decisions belong to the commercial operator.

## Commercial operator

MCorp (Woodfine Management Corp.) is a wholly-owned subsidiary of Woodfine Capital Projects Inc. WMC manages investor relations, originates and governs the direct-hold limited partnerships through which commercial assets are held, and operates the property ledger as fiduciary data custodian. Legal title to each property is held by a separate WCP Titleco nominee company that is beneficially owned by the applicable direct-hold limited partnership; WMC holds interests in those partnerships as part of the management structure and acts as the investor-facing entity for the Direct-Hold programme.

WMC is the entity with which investors transact. It is responsible for asset governance, investor communications, and the accuracy of property ledger records.

## Separation principle

The three-entity structure separates technology decisions from real estate decisions at the corporate level. PointSav cannot make investment decisions; its charter is technology services. WMC cannot modify platform code; that is PointSav's domain. Neither entity has authority in the other's operational scope.

This separation is structural, not contractual. A contract can be amended; a corporate boundary requires a restructuring. The design intent is that neither an operational failure at PointSav nor a financial event at WMC automatically impairs the other entity's core function.

## The bottom line

The three-entity structure is a governance architecture, not a tax or administrative convenience. By placing technology decisions inside PointSav and investment decisions inside WMC, the group prevents either function from encroaching on the other. Investors transact with WMC; they do not have a direct legal relationship with the technology platform, and PointSav has no authority over the investment decisions that affect investor capital. The corporate boundary makes this separation durable: altering it requires a restructuring, not a policy amendment.

## See also

- [[topic-vendor-customer-model|Vendor-Customer Model]] — the services relationship between PointSav and WMC
- [[topic-direct-hold-framework|Direct-Hold Framework]] — the asset ownership structure WMC operates
- [[topic-regulatory-posture|Regulatory Posture]] — OSC disclosure obligations applicable to the group

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licensed under [Creative Commons Attribution-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nd/4.0/).*
