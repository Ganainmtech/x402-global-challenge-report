# AgentFeed on Algorand — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 101).

## Identity and accounts

Merchant ID: `UVdPV1UyRTZCQjc2SEVRUlJNWFdaMk1V`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | QWOWU2E6BB76HEQRRMXWZ2MU4HAQIYZWEPP2W7Y377ZRDIW7ZKD4MMMEPM |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 101 | AgentFeed on Algorand | Exact submitted wallet QWOWU2E6BB76HEQRRMXWZ2MU4HAQIYZWEPP2W7Y377ZRDIW7ZKD4MMMEPM is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 30 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 1.200000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 6 (20.0000%) · 0.240000 USDC (20.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 24 (80.0000%) · 0.960000 USDC (80.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-12 18:53:59 UTC / 2026-10-06 00:09:39 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/agentfeed-on-algorand-1a1523fb21-transactions.csv.gz) · [All endpoints](../evidence/agentfeed-on-algorand-1a1523fb21-endpoints.csv) · [Payer evidence](../evidence/agentfeed-on-algorand-1a1523fb21-payers.csv) · [Daily metrics](../evidence/agentfeed-on-algorand-1a1523fb21-daily.csv) · [Site and catalog data](../evidence/agentfeed-on-algorand-1a1523fb21-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 6 (20.0000%) | 0.240000 (20.0000%) |
| NO-LINK-DETECTED | 24 (80.0000%) | 0.960000 (80.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 24 | 0.960000 (80.0000%) | throwaway wallet; created by vet402; pays 68 merchants |
| E3I2CZPCLKIEP2LYDIR62TZBNJT74EA2ATLWYNFGSA335HA7PQJLTFLZTU | MERCHANT-FUNDED | 6 | 0.240000 (20.0000%) | created by merchant; merchant sent 0.5 ALGO; merchant sent 0.7 USDC ×2 (292% of paid) |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://algo.ochinimus.app/v1/liquidations/window | 12 (40.0000%) | 0.240000 (20.0000%) | 2 | 0 | 2 |
| GET | https://algo.ochinimus.app/v2/liquidations/cascade | 3 (10.0000%) | 0.150000 (12.5000%) | 2 | 0 | 1 |
| GET | https://algo.ochinimus.app/v2/liquidations/universe | 3 (10.0000%) | 0.300000 (25.0000%) | 2 | 0 | 1 |
| GET | https://algo.ochinimus.app/v2/liquidations/window | 3 (10.0000%) | 0.060000 (5.0000%) | 2 | 0 | 1 |
| GET | https://algo.ochinimus.app/v2/venues/integrity | 3 (10.0000%) | 0.090000 (7.5000%) | 2 | 0 | 1 |
| GET | https://algo.ochinimus.app/v1/liquidations/cascade | 2 (6.6667%) | 0.100000 (8.3333%) | 1 | 0 | 0 |
| GET | https://algo.ochinimus.app/v1/liquidations/universe | 2 (6.6667%) | 0.200000 (16.6667%) | 1 | 0 | 0 |
| GET | https://algo.ochinimus.app/v1/venues/integrity | 2 (6.6667%) | 0.060000 (5.0000%) | 1 | 0 | 0 |

Top 8 of 8 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: algo.ochinimus.app.

Custom-domain candidates: algo.ochinimus.app. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| algo.ochinimus.app | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| algo.ochinimus.app | AgentFeed — forced-liquidation tape for AI agents, paid per call in USDC on Algorand | AgentFeed — forced-liquidation tape for AI agents, paid per call in USDC on Algorand | Every forced liquidation across 700+ USDT perpetuals on Binance, Bybit and OKX, sold per call in USDC over x402 on Algorand mainnet. No API key, no account, no subscription. Every response says whether the number was measured, genuinely absent, or unmeasured, and unmeasured is never billed. | https://algo.ochinimus.app/apple-touch-icon.png | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| algo.ochinimus.app | x402 Discovery | not recorded | https://algo.ochinimus.app/.well-known/x402 | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 1 |
| Agent document types | ["x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 8 |
| Description count | 8 |
| Mime type count | 8 |
| Accepts count | 8 |
| Discovery count | 8 |
| Input documentation count | 8 |
| Output documentation count | 0 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-12 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-08-16 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-16 | 4 | 0.200000 | 1 | 0 | 4 (100.0000%) |
| 2026-09-27 | 8 | 0.400000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 8 | 0.400000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |

Last 13 of 13 active days; all in the daily CSV.
