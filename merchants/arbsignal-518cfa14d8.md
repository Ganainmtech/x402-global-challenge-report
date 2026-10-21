# ArbSignal — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `TjJCSEJPUUVJNVRRUUtGS0hEUkRVQUNB`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | N2BHBOQEI5TQQKFKHDRDUACAZE6E55X6VO2U67IQAYBRRLB7LSMO6YRQSM |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 39 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 3.204000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 27 (69.2308%) · 2.504000 USDC (78.1523%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 12 (30.7692%) · 0.700000 USDC (21.8477%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 2 (5.1282%) · 0.004000 USDC (0.1248%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 2 (5.1282%) · 0.004000 USDC (0.1248%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-22 16:06:20 UTC / 2026-10-06 00:03:08 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/arbsignal-518cfa14d8-transactions.csv.gz) · [All endpoints](../evidence/arbsignal-518cfa14d8-endpoints.csv) · [Payer evidence](../evidence/arbsignal-518cfa14d8-payers.csv) · [Daily metrics](../evidence/arbsignal-518cfa14d8-daily.csv) · [Site and catalog data](../evidence/arbsignal-518cfa14d8-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 27 (69.2308%) | 2.504000 (78.1523%) |
| NO-LINK-DETECTED | 12 (30.7692%) | 0.700000 (21.8477%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| 57F2QR2RAI5LYJ2F4ZIC6AJEIINS62WGA7TLSILCAZOZHS7CLTPFU6QQVU | MERCHANT-FUNDED | 27 | 2.504000 (78.1523%) | created by merchant's creator; merchant sent 3.00 USDC ×1 (120% of paid); throwaway wallet; 77% of gaps &lt; 60s; pays 4 merchants |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 12 | 0.700000 (21.8477%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

2 (5.1282%) settlements · 0.004000 (0.1248%) USDC. Paid by synthetic-indicated payers: 2 (5.1282%) settlements · 0.004000 (0.1248%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://arbsignal-production.up.railway.app/arb/scan | 29 (74.3590%) | 2.704000 (84.3945%) | 2 | 2 | 27 |
| GET | https://arbsignal-production.up.railway.app/arb/pair | 10 (25.6410%) | 0.500000 (15.6055%) | 1 | 0 | 0 |

Top 2 of 2 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: arbsignal-production.up.railway.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| arbsignal-production.up.railway.app | hosting_provider_domain | yes, cached | 2026-10-05T05:54:38.334000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| arbsignal-production.up.railway.app | ArbSignal | ArbSignal | Live cross-DEX arbitrage scanner for Algorand — pay-per-call over x402. Finds the same asset priced differently across Tinyman, Pact, HumbleSwap & Folks, ranked by net spread after fees. | https://arbsignal-production.up.railway.app/apple-touch-icon.png | https://arbsignal-production.up.railway.app/apple-touch-icon.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| arbsignal-production.up.railway.app | A2A Agent Card | ArbSignal | http://arbsignal-production.up.railway.app/.well-known/agent-card.json | Live cross-DEX arbitrage scanner for Algorand — pay-per-call over x402. Finds the same asset priced differently across Tinyman, Pact, HumbleSwap & Folks, ranked by net spread after fees. |
| arbsignal-production.up.railway.app | llms.txt | ArbSignal | http://arbsignal-production.up.railway.app/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 2 |
| Agent document types | ["agent-card", "llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 3 |
| Description count | 3 |
| Mime type count | 3 |
| Accepts count | 3 |
| Discovery count | 3 |
| Input documentation count | 3 |
| Output documentation count | 3 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-22 | 1 | 0.002000 | 1 | 1 | 1 (100.0000%) |
| 2026-08-25 | 26 | 2.502000 | 1 | 1 | 26 (100.0000%) |
| 2026-09-27 | 2 | 0.150000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 2 | 0.150000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |

Last 12 of 12 active days; all in the daily CSV.
