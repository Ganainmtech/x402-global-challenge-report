# algorand-api.pxke.me — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `S1NBVk9ZVFZOQjdBNk5LQ000VzJXQk9P`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | KSAVOYTVNB7A6NKCM4W2WBOOGFHWH2SEGR5T6OGB7THCAT5E36LDFEBTII |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 23 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.386000 | USDC settled. |
| Unique payer accounts | 4 | Distinct accounts that paid. |
| Synthetic-indicated | 10 (43.4783%) · 0.373000 USDC (96.6321%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 13 (56.5217%) · 0.013000 USDC (3.3679%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 16 (69.5652%) · 0.016000 USDC (4.1451%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 3 (13.0435%) · 0.003000 USDC (0.7772%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 1 (4.3478%) · 0.100000 USDC (25.9067%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-30 13:46:00 UTC / 2026-10-06 00:02:08 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/algorand-api-pxke-me-af9431750a-transactions.csv.gz) · [All endpoints](../evidence/algorand-api-pxke-me-af9431750a-endpoints.csv) · [Payer evidence](../evidence/algorand-api-pxke-me-af9431750a-payers.csv) · [Daily metrics](../evidence/algorand-api-pxke-me-af9431750a-daily.csv) · [Site and catalog data](../evidence/algorand-api-pxke-me-af9431750a-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 10 (43.4783%) | 0.373000 (96.6321%) |
| NO-LINK-DETECTED | 13 (56.5217%) | 0.013000 (3.3679%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| E4UYF3FWIIMVXHUZCLC5EEN2XWJGLBH4AQPY65A7IYFPLI22BBEZMW57WE | MERCHANT-FUNDED | 8 | 0.371000 (96.1140%) | created by merchant's creator; 57% of gaps &lt; 60s |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 10 | 0.010000 (2.5907%) | throwaway wallet; created by vet402; pays 68 merchants |
| XALLOLSAOW5HVPCKK6NSTUTPVFWB3K6MNFKDXHMXULFYGN6GYXT4UU4UXA | NO-LINK-DETECTED | 3 | 0.003000 (0.7772%) | throwaway wallet; pays 9 merchants |
| BPARA5URZ6OGE5IQMBEKDVSHRECDBFBNROKIGFPUQ5IYAKU5IFEY3OAELY | MERCHANT-FUNDED | 2 | 0.002000 (0.5181%) | created by merchant's creator; merchant sent 5.00 ALGO; throwaway wallet |

Top 4 of 4 payers; all in the payer CSV.

## Sub-cent settlements

16 (69.5652%) settlements · 0.016000 (4.1451%) USDC. Paid by synthetic-indicated payers: 3 (13.0435%) settlements · 0.003000 (0.7772%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://algorand-api.pxke.me/api/v1/x402/news/search | 15 (65.2174%) | 0.015000 (3.8860%) | 3 | 15 | 2 |
| POST | (no host recorded) | 1 (4.3478%) | 0.100000 (25.9067%) | 1 | 0 | 1 |
| POST | https://algorand-api.pxke.me/api/v1/x402/board | 1 (4.3478%) | 0.050000 (12.9534%) | 1 | 0 | 1 |
| GET | https://algorand-api.pxke.me/api/v1/x402/features/demand | 1 (4.3478%) | 0.050000 (12.9534%) | 1 | 0 | 1 |
| POST | https://algorand-api.pxke.me/api/v1/x402/features/e21771740b4b4f128f931a8bbec13a9f/vote | 1 (4.3478%) | 0.020000 (5.1813%) | 1 | 0 | 1 |
| POST | https://algorand-api.pxke.me/api/v1/x402/grades | 1 (4.3478%) | 0.020000 (5.1813%) | 1 | 0 | 1 |
| GET | https://algorand-api.pxke.me/api/v1/x402/grades/score | 1 (4.3478%) | 0.030000 (7.7720%) | 1 | 0 | 1 |
| POST | https://algorand-api.pxke.me/api/v1/x402/list | 1 (4.3478%) | 0.100000 (25.9067%) | 1 | 0 | 1 |
| GET | https://algorand-api.pxke.me/api/v1/x402/ping | 1 (4.3478%) | 0.001000 (0.2591%) | 1 | 1 | 1 |

Top 9 of 9 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: algorand-api.pxke.me.

Custom-domain candidates: algorand-api.pxke.me. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| algorand-api.pxke.me | custom_domain_candidate | not established | 2026-10-01T15:51:20.362000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| algorand-api.pxke.me | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| algorand-api.pxke.me | x402 Discovery | PXke x402 marketplace | https://algorand-api.pxke.me/.well-known/x402 | Composite x402 marketplace on Algorand: start here; services. All under one payTo. |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 0 |
| Agent document count | 1 |
| Agent document types | ["x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No cached descriptive homepage evidence on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 7 |
| Description count | 7 |
| Mime type count | 7 |
| Accepts count | 7 |
| Discovery count | 7 |
| Input documentation count | 7 |
| Output documentation count | 7 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-30 | 7 | 0.370000 | 1 | 0 | 7 (100.0000%) |
| 2026-08-31 | 3 | 0.003000 | 2 | 3 | 3 (100.0000%) |
| 2026-09-27 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-28 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 4 | 0.004000 | 2 | 4 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |

Last 12 of 12 active days; all in the daily CSV.
