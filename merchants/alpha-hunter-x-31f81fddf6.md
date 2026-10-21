# Alpha Hunter X — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 72).

## Identity and accounts

Merchant ID: `QTVENTVTU1daRktUTVNaMkNDQ09NRFZN`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | ROO3X2KFNJVXIT2ZA6MFYOV7FRRZNVH2WIPO6TDWFVNEHVMQGFT6O4KFLA |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 72 | Alpha Hunter X | Exact submitted wallet ROO3X2KFNJVXIT2ZA6MFYOV7FRRZNVH2WIPO6TDWFVNEHVMQGFT6O4KFLA is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 1 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.050000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 1 (100.0000%) · 0.050000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-25 00:35:27 UTC / 2026-09-25 00:35:27 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/alpha-hunter-x-31f81fddf6-transactions.csv.gz) · [All endpoints](../evidence/alpha-hunter-x-31f81fddf6-endpoints.csv) · [Payer evidence](../evidence/alpha-hunter-x-31f81fddf6-payers.csv) · [Daily metrics](../evidence/alpha-hunter-x-31f81fddf6-daily.csv) · [Site and catalog data](../evidence/alpha-hunter-x-31f81fddf6-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 1 (100.0000%) | 0.050000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| 3KSUELDHDB73AVCRNQSJD27HVCAIET4LT34FPM6L25IQ34IMZMJM2D4V7E | MERCHANT-FUNDED | 1 | 0.050000 (100.0000%) | created by merchant; merchant sent 1.00 ALGO; merchant sent 0.22 USDC ×1 (440% of paid); throwaway wallet |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://alpha-hunter-x402-production.up.railway.app/v1/token/investigate | 1 (100.0000%) | 0.050000 (100.0000%) | 1 | 0 | 1 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: alpha-hunter-x402-production.up.railway.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| alpha-hunter-x402-production.up.railway.app | hosting_provider_domain | not established | 2026-10-01T15:51:20.362000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| alpha-hunter-x402-production.up.railway.app | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

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
| Agent readiness evidence | not_recorded |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "No cached descriptive homepage evidence on included public domains.", "No cached agent discovery documents on included public domains.", "No catalog resources on included public domains."] |

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
| 2026-09-25 | 1 | 0.050000 | 1 | 0 | 1 (100.0000%) |

Last 1 of 1 active days; all in the daily CSV.
