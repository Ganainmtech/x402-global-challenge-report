# MicroVern — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 25).

## Identity and accounts

Merchant ID: `R09YUktERUdZS0pUTkFKU1BGQVZVUVFI`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | GOXRKDEGYKJTNAJSPFAVUQQHHWMKBI7IW5PJ6G65X32OCYBMN6WYNNOPGE |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 25 | MicroVern | Exact submitted wallet GOXRKDEGYKJTNAJSPFAVUQQHHWMKBI7IW5PJ6G65X32OCYBMN6WYNNOPGE is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 10 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.100000 | USDC settled. |
| Unique payer accounts | 3 | Distinct accounts that paid. |
| Synthetic-indicated | 1 (10.0000%) · 0.010000 USDC (10.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 9 (90.0000%) · 0.090000 USDC (90.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 1 (10.0000%) · 0.010000 USDC (10.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-26 02:40:21 UTC / 2026-10-06 00:07:40 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/microvern-3c4bc3b7c8-transactions.csv.gz) · [All endpoints](../evidence/microvern-3c4bc3b7c8-endpoints.csv) · [Payer evidence](../evidence/microvern-3c4bc3b7c8-payers.csv) · [Daily metrics](../evidence/microvern-3c4bc3b7c8-daily.csv) · [Site and catalog data](../evidence/microvern-3c4bc3b7c8-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 1 (10.0000%) | 0.010000 (10.0000%) |
| NO-LINK-DETECTED | 9 (90.0000%) | 0.090000 (90.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 7 | 0.070000 (70.0000%) | throwaway wallet; created by vet402; pays 68 merchants |
| CW4A7FSJGKBYABWMDUM6VHEK6GYOGSRPDCJKQEIFRSQN3JKQ773VCALN3M | NO-LINK-DETECTED | 2 | 0.020000 (20.0000%) | throwaway wallet |
| KUBSPBIUIPE4CH473F6ZVNSRFJT5W6QAW6RJ65AUEDFD4UUFU5IOKE2ERE | MERCHANT-FUNDED | 1 | 0.010000 (10.0000%) | created by merchant; merchant sent 0.25 ALGO; throwaway wallet |

Top 3 of 3 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://microvern-x402-mainnet.onrender.com/v1/inspect-transaction | 9 (90.0000%) | 0.090000 (90.0000%) | 2 | 0 | 0 |
| (not recorded) | (not recorded) | 1 (10.0000%) | 0.010000 (10.0000%) | 1 | 0 | 1 |

Top 2 of 2 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: microvern-x402-mainnet.onrender.com.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| microvern-x402-mainnet.onrender.com | hosting_provider_domain | not established | 2026-10-01T15:51:20.362000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| microvern-x402-mainnet.onrender.com | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 0 |
| Agent document count | 0 |
| Agent document types | [] |
| Agent readiness evidence | catalog_only |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "No cached descriptive homepage evidence on included public domains.", "No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 1 |
| Description count | 1 |
| Mime type count | 1 |
| Accepts count | 1 |
| Discovery count | 1 |
| Input documentation count | 1 |
| Output documentation count | 1 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-26 | 1 | 0.010000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-29 | 2 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |

Last 9 of 9 active days; all in the daily CSV.
