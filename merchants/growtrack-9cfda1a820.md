# Growtrack — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 57).

## Identity and accounts

Merchant ID: `QkJHREg2UFRJREJIRFJBMlZZRUxQTUlP`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | BBGDH6PTIDBHDRA2VYELPMIO7D7RSJD7NB4GUTZRXXUYYUW3ZKBYWM6VPE |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 57 | Growtrack | Exact submitted wallet BBGDH6PTIDBHDRA2VYELPMIO7D7RSJD7NB4GUTZRXXUYYUW3ZKBYWM6VPE is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 8 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.008000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 8 (100.0000%) · 0.008000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 8 (100.0000%) · 0.008000 USDC (100.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-29 05:36:50 UTC / 2026-10-06 00:03:52 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/growtrack-9cfda1a820-transactions.csv.gz) · [All endpoints](../evidence/growtrack-9cfda1a820-endpoints.csv) · [Payer evidence](../evidence/growtrack-9cfda1a820-payers.csv) · [Daily metrics](../evidence/growtrack-9cfda1a820-daily.csv) · [Site and catalog data](../evidence/growtrack-9cfda1a820-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 8 (100.0000%) | 0.008000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 8 | 0.008000 (100.0000%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

8 (100.0000%) settlements · 0.008000 (100.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://growtrack.pro/v1/portfolio/report | 8 (100.0000%) | 0.008000 (100.0000%) | 1 | 8 | 0 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: growtrack.pro.

Custom-domain candidates: growtrack.pro. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| growtrack.pro | custom_domain_candidate | yes, cached | 2026-10-04T04:13:05.093000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| growtrack.pro | Growtrack \| Multichain wallet intelligence | not recorded | Look up any EVM, Algorand, Solana or Bitcoin address and see its real holdings and USD value. Pay per query in USDC on Algorand via x402. | https://growtrack.pro/logo.png | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| growtrack.pro | x402 Discovery | Growtrack | https://growtrack.pro/.well-known/x402 | Multichain on-chain portfolio intelligence for Ethereum, Algorand, Solana and Bitcoin. Pay per request in USDC on Algorand via x402 — no API key, no account, no subscription. |
| growtrack.pro | llms.txt | Growtrack | https://growtrack.pro/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 2 |
| Agent document types | ["llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-09-29 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |

Last 8 of 8 active days; all in the daily CSV.
