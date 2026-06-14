---
schema: foundry-doc-v1
title: "Property Ledger Technology"
slug: topic-property-ledger-technology
aliases:
  - topic-property-ledger-technology
short_description: "Technology infrastructure underlying each WMC property ledger: cryptographic record of fractional equity holdings, asset events, and transfer history, maintained by PointSav Digital Systems under WMC custody."
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
paired_with: topic-property-ledger-technology.es.md
cites: []
---

Each asset maintained under the [[topic-direct-hold-framework|Direct-Hold framework]] has an associated property ledger. The ledger is the authoritative record of fractional equity assignments, asset financial events, and transfer history. Woodfine Management Corp. holds legal custody of the ledger under the [[topic-fiduciary-data-mandate|Fiduciary Data Mandate]]; PointSav Digital Systems maintains the technical infrastructure as the contracted technology provider under the [[topic-technology-services|technology services agreement]].

## What the ledger records

The property ledger captures three categories of information:

**Fractional equity assignments.** The ledger records who holds what percentage of the named asset at any point in time. Each investor's position is stated as a percentage of the specific property — not a share in a fund or a proportional claim on a pool. Each fractional holding is constituted as an [[topic-investment-units|investment unit]] in the named asset.

**Asset financial events.** Distributions, debt service transactions, appraisals, and other financial events affecting the asset are recorded in the ledger with timestamps and amounts. The record is append-only for operational entries; no prior financial event record can be overwritten.

**Transfer history.** Each peer-to-peer equity transfer is recorded with the timestamp of the transaction and the identities of the transferring and acquiring parties, consistent with the [[topic-equity-transfer-model|Equity Transfer Model]]. The ledger maintains a complete chain of title from the asset's initial equity issuance.

## Custody and control

WMC holds legal custody of all ledger data. PointSav maintains the technical infrastructure — private keys, server hardware, software stack — as a contracted services provider under the technology services agreement. The entity that holds the private keys and operates the ledger is the entity in effective technical control of the record. WMC, as the legal custodian, directs how the infrastructure is operated and can require data export or infrastructure transfer at any time.

## Sovereign control principle

A property owner that cannot access the ledger proving ownership of an asset is functionally dispossessed. The architecture is designed so that WMC can recover full operational control of the ledger independently of any single technology provider. Ledger data is stored in portable formats; the record is not locked to PointSav's specific software implementation.

## Integrity mechanisms

The append-only structure of operational records prevents retroactive modification of financial event history. Changes to the equity record — transfers, new assignments — require the F12 commit protocol: an explicit operator action that cannot be triggered automatically. No automated process can modify the equity record without a human operator explicitly authorizing the change.

## Not a public distributed ledger

The property ledger is a cryptographic record maintained by the corporate entity. It is not a public blockchain or a distributed ledger maintained by external validators. The corporate entity is the authority on ledger state. This is a deliberate design choice: public distributed ledgers introduce counterparty dependencies — validator networks, protocol governance bodies — that the architecture is specifically designed to avoid.

## See also

- [[topic-fiduciary-data-mandate|Fiduciary Data Mandate]] — WMC's obligations as the data custodian of the property ledger
- [[topic-data-governance|Data Governance]] — how personal and operational data are handled under WMC's custody framework
- [[topic-vendor-customer-model|Vendor-Customer Model]] — the services relationship under which PointSav maintains the technical infrastructure
- [WORM Ledger Architecture](https://documentation.pointsav.com/infrastructure/worm-ledger-architecture) — the underlying ledger architecture referenced in this article

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licensed under [Creative Commons Attribution-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nd/4.0/).*
