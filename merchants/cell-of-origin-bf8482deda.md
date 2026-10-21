# Cell of Origin — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `RFNJSUo2U0NHTVoyRFlBVEs3STdHUk9T`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | DSIIJ6SCGMZ2DYATK7I7GROSUT7INIIZJUE4Q7RSOSUR7PCNUYCX3XIKBI |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 20 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.220000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 20 (100.0000%) · 0.220000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-04 05:04:22 UTC / 2026-10-06 00:06:05 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/cell-of-origin-bf8482deda-transactions.csv.gz) · [All endpoints](../evidence/cell-of-origin-bf8482deda-endpoints.csv) · [Payer evidence](../evidence/cell-of-origin-bf8482deda-payers.csv) · [Daily metrics](../evidence/cell-of-origin-bf8482deda-daily.csv) · [Site and catalog data](../evidence/cell-of-origin-bf8482deda-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 20 (100.0000%) | 0.220000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| IIGMZH2273DOTPQDT5ZFKIWGRZVJUF3CRB4Z5NQJZMARERYEZGNOU4MA2U | NO-LINK-DETECTED | 10 | 0.120000 (54.5455%) | throwaway wallet |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 10 | 0.100000 (45.4545%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://api.celloforigin.com/enter | 16 (80.0000%) | 0.160000 (72.7273%) | 2 | 0 | 0 |
| (not recorded) | https://api.celloforigin.com/convert | 2 (10.0000%) | 0.040000 (18.1818%) | 1 | 0 | 0 |
| (not recorded) | https://api.celloforigin.com/side | 2 (10.0000%) | 0.020000 (9.0909%) | 1 | 0 | 0 |

Top 3 of 3 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.celloforigin.com.

Custom-domain candidates: api.celloforigin.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.celloforigin.com | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.celloforigin.com | Cell of Origin | not recorded | A deterministic thirty-second fight between two single-celled organisms. | https://api.celloforigin.com/icon.svg | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| api.celloforigin.com | x402 Discovery | Cell of Origin | https://api.celloforigin.com/.well-known/x402 | A deterministic 30-second fight between two single-celled organisms. |
| api.celloforigin.com | llms.txt | Cell of Origin | https://api.celloforigin.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 2 |
| Agent document types | ["llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No catalog resources on included public domains."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 0 |
| Description count | 0 |
| Mime type count | 0 |
| Accepts count | 0 |
| Discovery count | 0 |
| Input documentation count | 0 |
| Output documentation count | 0 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-04 | 4 | 0.040000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-08 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-09 | 5 | 0.070000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-27 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |

Last 13 of 13 active days; all in the daily CSV.
