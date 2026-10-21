# AlgoCheck — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `VDJJM0ZLRFM1WVJVRzI2WkszWVZIQ0s0`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | T2I3FKDS5YRUG26ZK3YVHCK45G2OLNCTGWXIYF6J6M75KZB4Q33UWNRMPQ |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 12 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.240000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 2 (16.6667%) · 0.040000 USDC (16.6667%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 10 (83.3333%) · 0.200000 USDC (83.3333%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-19 21:49:49 UTC / 2026-10-06 00:09:47 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/algocheck-246e461e2d-transactions.csv.gz) · [All endpoints](../evidence/algocheck-246e461e2d-endpoints.csv) · [Payer evidence](../evidence/algocheck-246e461e2d-payers.csv) · [Daily metrics](../evidence/algocheck-246e461e2d-daily.csv) · [Site and catalog data](../evidence/algocheck-246e461e2d-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 2 (16.6667%) | 0.040000 (16.6667%) |
| NO-LINK-DETECTED | 10 (83.3333%) | 0.200000 (83.3333%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 10 | 0.200000 (83.3333%) | throwaway wallet; created by vet402; pays 68 merchants |
| 5WYCGG3CI3N7UE75UJFXKR5G5OXDCXEO2W4NPQY6GNUJLVRFWKQZVOCBOE | MERCHANT-FUNDED | 2 | 0.040000 (16.6667%) | created by merchant; merchant sent 0.4 ALGO; merchant sent 0.041 USDC ×1 (104% of paid); throwaway wallet |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://algocheckmain.vercel.app/api/v1/analyze/31566704 | 12 (100.0000%) | 0.240000 (100.0000%) | 2 | 0 | 2 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: algocheckmain.vercel.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| algocheckmain.vercel.app | hosting_provider_domain | yes, cached | 2026-10-04T20:43:45.415000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| algocheckmain.vercel.app | AlgoCheck — ASA Risk Analysis | not recorded | AlgoCheck — Transparent risk analysis for Algorand Standard Assets. | https://algocheckmain.vercel.app/favicon.svg | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | True |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 0 |
| Agent document types | [] |
| Agent readiness evidence | catalog_only |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-08-19 | 2 | 0.040000 | 1 | 0 | 2 (100.0000%) |
| 2026-09-27 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |

Last 11 of 11 active days; all in the daily CSV.
