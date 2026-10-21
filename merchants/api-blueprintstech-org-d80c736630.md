# api.blueprintstech.org — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `VjdYV1lLWTNXQktXUk9OWDVOVEhGTks3`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | V7XWYKY3WBKWRONX5NTHFNK77A7O3IS7XEMIUJQM6ZLZRWYVNT763I333Y |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 10 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.012000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 3 (30.0000%) · 0.005000 USDC (41.6667%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 7 (70.0000%) · 0.007000 USDC (58.3333%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 10 (100.0000%) · 0.012000 USDC (100.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 3 (30.0000%) · 0.005000 USDC (41.6667%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-16 08:48:21 UTC / 2026-09-28 01:38:58 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/api-blueprintstech-org-d80c736630-transactions.csv.gz) · [All endpoints](../evidence/api-blueprintstech-org-d80c736630-endpoints.csv) · [Payer evidence](../evidence/api-blueprintstech-org-d80c736630-payers.csv) · [Daily metrics](../evidence/api-blueprintstech-org-d80c736630-daily.csv) · [Site and catalog data](../evidence/api-blueprintstech-org-d80c736630-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 7 (70.0000%) | 0.007000 (58.3333%) |
| SELF | 3 (30.0000%) | 0.005000 (41.6667%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| LNLA2AAADJPTVCQK7XAL5N7HZWIUV7XXPNJRGHJK5PMPHUOOR4WPO6XSAI | NO-LINK-DETECTED | 7 | 0.007000 (58.3333%) | throwaway wallet; pays 3 merchants |
| TV3772EIRZ5UTEMYG4NQJN7HKA5J3J6UKDC7RZKM2JI52E5KMYMAAFDKPU | SELF | 3 | 0.005000 (41.6667%) | merchant's own address; created by merchant; merchant sent 1.00 ALGO; merchant sent 0.079 USDC ×1 (1578% of paid); throwaway wallet |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

10 (100.0000%) settlements · 0.012000 (100.0000%) USDC. Paid by synthetic-indicated payers: 3 (30.0000%) settlements · 0.005000 (41.6667%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://api.blueprintstech.org/api/verify-counterparty | 8 (80.0000%) | 0.008000 (66.6667%) | 2 | 8 | 1 |
| POST | https://api.blueprintstech.org/api/agent-preflight | 1 (10.0000%) | 0.003000 (25.0000%) | 1 | 1 | 1 |
| POST | https://api.blueprintstech.org/api/verify-asset | 1 (10.0000%) | 0.001000 (8.3333%) | 1 | 1 | 1 |

Top 3 of 3 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.blueprintstech.org.

Custom-domain candidates: api.blueprintstech.org. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.blueprintstech.org | custom_domain_candidate | not established | 2026-10-01T15:51:20.362000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.blueprintstech.org | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
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
| Gaps | ["No cached descriptive homepage evidence on included public domains.", "No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 6 |
| Description count | 6 |
| Mime type count | 6 |
| Accepts count | 6 |
| Discovery count | 6 |
| Input documentation count | 6 |
| Output documentation count | 6 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-16 | 3 | 0.005000 | 1 | 3 | 3 (100.0000%) |
| 2026-08-26 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-08-27 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-08-28 | 3 | 0.003000 | 1 | 3 | 0 (0.0000%) |
| 2026-09-27 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-28 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |

Last 6 of 6 active days; all in the daily CSV.
