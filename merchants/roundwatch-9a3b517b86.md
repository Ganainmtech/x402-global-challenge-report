# RoundWatch — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 56, 96).

## Identity and accounts

Merchant ID: `RVFQTE4zMkhQTFBHQkNOUE9aVUw2Qkwz`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | EQPLN32HPLPGBCNPOZUL6BL34CTNQGT3VAAMNAJWSIZGQ5CUNXOHB634XY |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 56 | RoundWatch | Exact submitted wallet EQPLN32HPLPGBCNPOZUL6BL34CTNQGT3VAAMNAJWSIZGQ5CUNXOHB634XY is a receiving account of this merchant. |
| 96 | RoundWatch | Exact submitted wallet EQPLN32HPLPGBCNPOZUL6BL34CTNQGT3VAAMNAJWSIZGQ5CUNXOHB634XY is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 7 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.201000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 6 (85.7143%) · 0.181000 USDC (90.0498%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 1 (14.2857%) · 0.020000 USDC (9.9502%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 1 (14.2857%) · 0.001000 USDC (0.4975%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 1 (14.2857%) · 0.001000 USDC (0.4975%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-16 10:26:05 UTC / 2026-09-29 16:04:37 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/roundwatch-9a3b517b86-transactions.csv.gz) · [All endpoints](../evidence/roundwatch-9a3b517b86-endpoints.csv) · [Payer evidence](../evidence/roundwatch-9a3b517b86-payers.csv) · [Daily metrics](../evidence/roundwatch-9a3b517b86-daily.csv) · [Site and catalog data](../evidence/roundwatch-9a3b517b86-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 6 (85.7143%) | 0.181000 (90.0498%) |
| NO-LINK-DETECTED | 1 (14.2857%) | 0.020000 (9.9502%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| 3YFZ47IAKPB4H6B7U6MXI35HCAB5E6DA47UANIHOON53J7I5SMXUSYQXQQ | MERCHANT-FUNDED | 6 | 0.181000 (90.0498%) | created by merchant; merchant sent 21.00 ALGO; throwaway wallet |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 1 | 0.020000 (9.9502%) | merchant sent 0.02 USDC ×1 (100% of paid); throwaway wallet; created by vet402; pays 68 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

1 (14.2857%) settlements · 0.001000 (0.4975%) USDC. Paid by synthetic-indicated payers: 1 (14.2857%) settlements · 0.001000 (0.4975%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://roundwatch-api.onrender.com/v1/watch | 7 (100.0000%) | 0.201000 (100.0000%) | 2 | 1 | 6 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: roundwatch-api.onrender.com.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| roundwatch-api.onrender.com | hosting_provider_domain | yes, cached | 2026-10-04T21:41:17.211000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| roundwatch-api.onrender.com | RoundWatch — Algorand x402 Payment Monitoring API | RoundWatch | Durable payment monitoring for one exact future Algorand USDC payment, with verified on-chain evidence. | https://roundwatch.observer/favicon.svg | https://roundwatch.observer/roundwatch-og.jpg | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| roundwatch-api.onrender.com | llms.txt | RoundWatch | https://roundwatch-api.onrender.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 1 |
| Agent document types | ["llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-09-16 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-22 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-24 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-25 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-27 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 2 | 0.120000 | 1 | 0 | 2 (100.0000%) |

Last 6 of 6 active days; all in the daily CSV.
