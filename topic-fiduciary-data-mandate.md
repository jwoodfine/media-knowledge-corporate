---
schema: foundry-doc-v1
title: "Fiduciary Data Mandate"
slug: topic-fiduciary-data-mandate
aliases:
  - topic-fiduciary-data-mandate
short_description: "Custody and sovereignty requirement that the corporate entity holds physical control of the ledger hardware and cryptographic keys, not a third-party custodian."
category: governance
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-fiduciary-data-mandate.es.md
cites: []
---

The Fiduciary Data Mandate is WMC's operating requirement that the corporate entity holds direct physical and cryptographic control of all records defining investor equity positions, asset valuations, and chain of title. The mandate treats reliance on third-party cloud infrastructure for investor [[topic-property-ledger-technology|ledger data]] as a fiduciary failure, not a vendor relationship: a corporate entity that cannot access its own ledger records without a third party's cooperation cannot independently discharge its obligations to investors. The mandate underpins the [[topic-direct-hold-framework|Direct-Hold framework]], enables the [[topic-equity-transfer-model|Equity Transfer Model]], and is applied alongside the [[topic-interest-coverage-ratio|Interest Coverage Ratio]] discipline at the asset level.

## What the mandate covers

The mandate applies to all data that records investor equity positions, asset valuations, transaction history, and chain of title. These records constitute the legal foundation of the investor relationship. The corporate entity cannot be the beneficial holder of assets if it does not control the data that defines those assets.

## Third-party cloud dependency as fiduciary risk

Traditional property investment vehicles rely on third-party software platforms, hosted databases, and cloud-native accounting systems. These create a structural vulnerability: the legal record of investor ownership is maintained by entities whose interests may diverge from the investor's. A cloud provider's service disruption, acquisition, or policy change can interrupt access to records the corporate entity does not physically control.

The Fiduciary Data Mandate closes this vulnerability by treating digital sovereignty as equivalent to physical asset ownership. A corporate entity that owns a building but cannot access the ledger proving it owns the building is functionally dispossessed.

## PointSav platform

The corporate entity's compliance with the mandate is supported by the PointSav platform under the [[topic-technology-services|technology services agreement]]. PointSav provides the operating infrastructure for investor ledger management: a self-hosted system where the corporate entity holds the private keys, the physical hardware, and operational control of the software stack. No third-party intermediary has access to ledger data without the corporate entity's cryptographic consent. The arrangement is governed by the [[topic-vendor-customer-model|vendor-customer model]] that separates platform operation from fiduciary responsibility.

## Scope and limits

The mandate applies to investor ledger data and chain-of-title records. It does not extend to marketing materials, tenant management systems, or communications infrastructure — those may use hosted services. The distinction: whatever would need to be produced in a legal dispute about investor ownership is within scope.

An investor cannot exercise governance rights over an asset whose legal ledger they cannot access. The mandate closes this structural gap: a corporate entity that controls its own ledger infrastructure can always produce the authoritative record, regardless of third-party service availability. The discipline complements broader [[topic-data-governance|data governance]] obligations and the [[topic-continuous-disclosure|continuous-disclosure regime]] applicable to the issuer.

## See also

- [[topic-direct-hold-framework]] — the ownership structure that the fiduciary mandate protects
- [[topic-equity-transfer-model]] — how ledger integrity supports free equity transfer
- [[topic-interest-coverage-ratio]] — the financial discipline applied alongside the data mandate

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licensed under [Creative Commons Attribution-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nd/4.0/).*
