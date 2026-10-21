# DollarOne x402 Tester — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `TFFFWlJNVjY2Wjc1SzdBUVBGTFI0TDY2`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | LQEZRMV66Z75K7AQPFLR4L66MXTDTVWGKCPZNPESDGUQ3HEIMBZIAX7IPY |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 1 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.010000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 1 (100.0000%) · 0.010000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-25 03:35:09 UTC / 2026-09-25 03:35:09 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/dollarone-x402-tester-3e34ee99bf-transactions.csv.gz) · [All endpoints](../evidence/dollarone-x402-tester-3e34ee99bf-endpoints.csv) · [Payer evidence](../evidence/dollarone-x402-tester-3e34ee99bf-payers.csv) · [Daily metrics](../evidence/dollarone-x402-tester-3e34ee99bf-daily.csv) · [Site and catalog data](../evidence/dollarone-x402-tester-3e34ee99bf-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 1 (100.0000%) | 0.010000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| PA6OLEX3NICYFMOURSKBYDWCWK3QK3HY2VY5NZFMEJGMJLV5S3MBFFBZY4 | MERCHANT-FUNDED | 1 | 0.010000 (100.0000%) | created by merchant; merchant sent 1.00 ALGO; throwaway wallet |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | http://dollarone-x402-mainnet-production.up.railway.app/resolve-location | 1 (100.0000%) | 0.010000 (100.0000%) | 1 | 0 | 1 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: dollarone-x402-mainnet-production.up.railway.app, dollarone-x402-paytest-production.up.railway.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| dollarone-x402-mainnet-production.up.railway.app | hosting_provider_domain | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 2 |
| dollarone-x402-paytest-production.up.railway.app | hosting_provider_domain | yes, cached | 2026-09-25T03:01:04.872000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| dollarone-x402-mainnet-production.up.railway.app | DollarOne x402 Tester | not recorded | not recorded | not recorded | not recorded | not recorded |
| dollarone-x402-paytest-production.up.railway.app | DollarOne x402 Tester | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| dollarone-x402-mainnet-production.up.railway.app | x402 Discovery | DollarOne Mexico Location Intelligence API | http://dollarone-x402-mainnet-production.up.railway.app/.well-known/x402 | Turn noisy Mexican location text into deterministic structured fields for routing, CRM cleanup, civic reports, checkout, delivery and agent workflows. Supports all Mexican states plus selected municipality enrichment, with confidence, warnings and provenance. |
| dollarone-x402-mainnet-production.up.railway.app | llms.txt | DollarOne Mexico Location Intelligence API | http://dollarone-x402-mainnet-production.up.railway.app/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 2 |
| Agent document types | ["llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 2 |
| Description count | 2 |
| Mime type count | 2 |
| Accepts count | 2 |
| Discovery count | 2 |
| Input documentation count | 2 |
| Output documentation count | 2 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25 | 1 | 0.010000 | 1 | 0 | 1 (100.0000%) |

Last 1 of 1 active days; all in the daily CSV.
