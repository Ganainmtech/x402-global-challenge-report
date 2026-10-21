# Stelar Digital x402 Doctor + paid data endpoints — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 87).

## Identity and accounts

Merchant ID: `SEZISTVNRjRDNTVBWVVTUTJKRDJBRllN`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | HFHI5MF4C55AYUSQ2JD2AFYMUHWBNSE3SGU6N2YZ5ET5FUZD5YHZHXSWXU |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 87 | Stelar Digital x402 Doctor + paid data endpoints | Exact submitted wallet HFHI5MF4C55AYUSQ2JD2AFYMUHWBNSE3SGU6N2YZ5ET5FUZD5YHZHXSWXU is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 14 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.160000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 14 (100.0000%) · 0.160000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 12 (85.7143%) · 0.060000 USDC (37.5000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 14 · 0.175000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-27 04:39:22 UTC / 2026-10-06 00:04:44 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/stelar-digital-x402-doctor-paid-data-endpoints-f1b53c8541-transactions.csv.gz) · [All endpoints](../evidence/stelar-digital-x402-doctor-paid-data-endpoints-f1b53c8541-endpoints.csv) · [Payer evidence](../evidence/stelar-digital-x402-doctor-paid-data-endpoints-f1b53c8541-payers.csv) · [Daily metrics](../evidence/stelar-digital-x402-doctor-paid-data-endpoints-f1b53c8541-daily.csv) · [Site and catalog data](../evidence/stelar-digital-x402-doctor-paid-data-endpoints-f1b53c8541-site-and-catalog.json)

**Flag — self-payments excluded:** 14 settlements / 0.175000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 14 (100.0000%) | 0.160000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 14 | 0.160000 (100.0000%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

12 (85.7143%) settlements · 0.060000 (37.5000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://api-algo.stelardigital.com/pricecheck | 10 (71.4286%) | 0.050000 (31.2500%) | 1 | 10 | 0 |
| GET | https://api-algo.stelardigital.com/gridparams | 2 (14.2857%) | 0.100000 (62.5000%) | 1 | 0 | 0 |
| GET | https://api-algo.stelardigital.com/telemetry | 2 (14.2857%) | 0.010000 (6.2500%) | 1 | 2 | 0 |

Top 3 of 3 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api-algo.stelardigital.com.

Custom-domain candidates: api-algo.stelardigital.com. Registered email on a matching custom domain: **stelardigital.com**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api-algo.stelardigital.com | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 3 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api-algo.stelardigital.com | Stelar Digital | Stelar Digital | Machine-payable x402 API on Algorand mainnet — Stelar Digital. | https://api-algo.stelardigital.com/icon-s-512.png | https://api-algo.stelardigital.com/logo-512.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| api-algo.stelardigital.com | A2A Agent Card | stelar-x402-algorand | https://api-algo.stelardigital.com/.well-known/agent-card.json | Live x402 endpoints from an AI-managed crypto portfolio: telemetry, price checks, grid parameters, and a free-tier x402 Doctor conformance check for other builders' paid endpoints. One human. One AI. A whole company. |
| api-algo.stelardigital.com | x402 Discovery | Stelar Digital | https://api-algo.stelardigital.com/.well-known/x402 | Live x402 endpoints from an AI-managed crypto portfolio: telemetry, price checks, grid parameters, and a free-tier x402 Doctor conformance check for other builders' paid endpoints. One human. One AI. A whole company. |
| api-algo.stelardigital.com | llms.txt | Stelar Digital x402 API — Algorand mainnet — pay-per-call market data & tools | https://api-algo.stelardigital.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 3 |
| Agent document types | ["agent-card", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 5 |
| Description count | 5 |
| Mime type count | 5 |
| Accepts count | 5 |
| Discovery count | 5 |
| Input documentation count | 5 |
| Output documentation count | 5 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-27 | 3 | 0.060000 | 1 | 2 | 0 (0.0000%) |
| 2026-09-28 | 3 | 0.060000 | 1 | 2 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |

Last 10 of 10 active days; all in the daily CSV.
