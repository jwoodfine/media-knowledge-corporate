---
schema: foundry-doc-v1
title: "Redemption Elimination"
slug: topic-redemption-elimination
short_description: "Structural elimination of investor redemption rights, removing the cash-reserve drag and run-mechanics risk inherent to pooled real estate vehicles."
category: governance
type: reference
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-redemption-elimination.es.md
cites: []
---

Woodfine Direct-Hold assets carry no redemption queue — each investor's equity corresponds to a specific property, and liquidity depends on the private market for that asset, not on the corporate entity's cash reserves. Because no commingled pool exists, the condition that makes redemption mechanisms necessary is absent by design.

## Why redemption queues exist

In a pooled fund, a redemption queue manages the tension between investor liquidity requests and the illiquid nature of physical real estate. The fund holds a cash reserve to honor near-term redemptions. If redemption requests exceed the reserve, the queue activates — investors wait while the fund sells assets or raises fresh capital.

The cash reserve is a structural liability. It earns less than the underlying assets. It must be maintained even when no redemptions are pending. Its size is a judgment call subject to manager discretion.

## What the Direct-Hold architecture removes

The Direct-Hold architecture removes the condition that requires a cash reserve. There is no pooled capital. Each investor's equity corresponds to a specific property, not to a share in a pool. The corporate entity does not promise to return capital on demand — because there is no pool to draw from.

An investor who wants to exit locates a willing buyer in the private market. The investor receives the proceeds of that private sale. The corporate entity updates the ledger. No cash reserve is tapped. No other investor's position is affected.

## Artificial bank runs

A redemption queue is vulnerable to a coordination failure: if investors anticipate that the queue will be suspended, early redemption requests can trigger the very suspension they feared. This is a structural instability in pooled vehicles.

The Direct-Hold architecture is immune to this failure mode. There is no queue to join, no suspension to anticipate, and no first-mover advantage to coordinating an early exit. An investor's equity is determined by the private market for that specific asset — not by the behavior of other investors in a shared pool.

## Investor implications

The structural consequence for investors is explicit: Woodfine Management Corp. does not provide a redemption facility. Liquidity depends on the private market for the specific asset. The Direct-Hold structure carries a different risk profile than a pooled fund — the corporate entity makes no liquidity commitment it cannot fulfill, because no pooled capital exists from which such a commitment could be honored.

Without a redemption queue, no coordinated exit pressure can destabilize the portfolio. Long-term equity compounds without the structural drag of a cash reserve that earns less than the underlying assets.

## See also

- [[topic-direct-hold-framework]] — the ownership structure that makes redemption mechanisms unnecessary
- [[topic-equity-transfer-model]] — how investors exit their positions in practice
- [[topic-interest-coverage-ratio]] — the debt-service discipline that removes the need for cash reserves

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licensed under [Creative Commons Attribution-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nd/4.0/).*
