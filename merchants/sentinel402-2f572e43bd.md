# Sentinel402 — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 74).

## Identity and accounts

Merchant ID: `TUFHS0RFV1k1SVo2TUJZTEtHTEhONFVX`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | MAGKDEWY5IZ6MBYLKGLHN4UWFM2BYCJ5R62C5AU6JASOY2HAS6XP5SHRII |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 74 | Sentinel402 | Exact submitted wallet MAGKDEWY5IZ6MBYLKGLHN4UWFM2BYCJ5R62C5AU6JASOY2HAS6XP5SHRII is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 13 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.900000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 13 (100.0000%) · 0.900000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-24 23:38:04 UTC / 2026-10-06 00:10:39 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/sentinel402-2f572e43bd-transactions.csv.gz) · [All endpoints](../evidence/sentinel402-2f572e43bd-endpoints.csv) · [Payer evidence](../evidence/sentinel402-2f572e43bd-payers.csv) · [Daily metrics](../evidence/sentinel402-2f572e43bd-daily.csv) · [Site and catalog data](../evidence/sentinel402-2f572e43bd-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 13 (100.0000%) | 0.900000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 10 | 0.500000 (55.5556%) | throwaway wallet; created by vet402; pays 68 merchants |
| W3ZYUXCWMOKC6DNO2IDQEAL7FD5UF7V6AR7AWBKMDYBCOU5ORSMNKSVZM4 | NO-LINK-DETECTED | 3 | 0.400000 (44.4444%) | same funder as merchant (hub) |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://43.162.105.66.sslip.io/v1/scan/signature | 11 (84.6154%) | 0.550000 (61.1111%) | 2 | 0 | 0 |
| POST | https://43.162.105.66.sslip.io/v1/scan/address | 1 (7.6923%) | 0.100000 (11.1111%) | 1 | 0 | 0 |
| POST | https://43.162.105.66.sslip.io/v1/scan/contract | 1 (7.6923%) | 0.250000 (27.7778%) | 1 | 0 | 0 |

Top 3 of 3 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: 43.162.105.66.sslip.io.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| 43.162.105.66.sslip.io | hosting_provider_domain | not established | 2026-10-06T01:26:10.028000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| 43.162.105.66.sslip.io | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

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
| 2026-09-24 | 3 | 0.400000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-27 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |

Last 11 of 11 active days; all in the daily CSV.
