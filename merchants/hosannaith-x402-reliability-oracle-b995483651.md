# Hosannaith — x402 Reliability Oracle — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 13).

## Identity and accounts

Merchant ID: `QkVBQ0pMVURPU1ZNUzZTVVFFVUFIV1JJ`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | BEACJLUDOSVMS6SUQEUAHWRI4VAAX7G4CVFOL3DWH2R4XHTLXT6VG5TFYU |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 13 | Hosannaith — x402 Reliability Oracle | Exact submitted wallet BEACJLUDOSVMS6SUQEUAHWRI4VAAX7G4CVFOL3DWH2R4XHTLXT6VG5TFYU is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 8 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.080000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 8 (100.0000%) · 0.080000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-29 15:24:16 UTC / 2026-10-01 13:22:08 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/hosannaith-x402-reliability-oracle-b995483651-transactions.csv.gz) · [All endpoints](../evidence/hosannaith-x402-reliability-oracle-b995483651-endpoints.csv) · [Payer evidence](../evidence/hosannaith-x402-reliability-oracle-b995483651-payers.csv) · [Daily metrics](../evidence/hosannaith-x402-reliability-oracle-b995483651-daily.csv) · [Site and catalog data](../evidence/hosannaith-x402-reliability-oracle-b995483651-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 8 (100.0000%) | 0.080000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| XYIAQHTBAEL7AAP3EGO4PC42L63NKN5TBHKQ4IGA2QQNUZ72EOOAFGKIGE | NO-LINK-DETECTED | 8 | 0.080000 (100.0000%) | throwaway wallet; same funder as merchant (hub) |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | http://api.hosannaith.com/reliability | 8 (100.0000%) | 0.080000 (100.0000%) | 1 | 0 | 0 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.hosannaith.com.

Custom-domain candidates: api.hosannaith.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.hosannaith.com | custom_domain_candidate | yes, cached | 2026-10-05T22:21:10.766000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.hosannaith.com | Hosannaith — x402 Reliability Oracle | Hosannaith | Verify any x402 endpoint's reliability — uptime, correct-402 behaviour, latency — before you route USDC to it. Live on Algorand Mainnet. | not recorded | https://hosannaith.com/og-image.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 0 |
| Agent document types | [] |
| Agent readiness evidence | catalog_only |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-09-29 | 2 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 5 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |

Last 3 of 3 active days; all in the daily CSV.
