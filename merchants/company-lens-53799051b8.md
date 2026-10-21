# Company Lens — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 83).

## Identity and accounts

Merchant ID: `UU9MQUgyQUxFS0QzQk9DUks0TFZCSE5S`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | QOLAH2ALEKD3BOCRK4LVBHNRAAZKIJYVQHNHUMY5UC6UEUBGBEF2JMTX3Q |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 83 | Company Lens | Exact submitted wallet QOLAH2ALEKD3BOCRK4LVBHNRAAZKIJYVQHNHUMY5UC6UEUBGBEF2JMTX3Q is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 5 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 2.500000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 5 (100.0000%) · 2.500000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-21 23:07:00 UTC / 2026-09-22 14:57:30 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/company-lens-53799051b8-transactions.csv.gz) · [All endpoints](../evidence/company-lens-53799051b8-endpoints.csv) · [Payer evidence](../evidence/company-lens-53799051b8-payers.csv) · [Daily metrics](../evidence/company-lens-53799051b8-daily.csv) · [Site and catalog data](../evidence/company-lens-53799051b8-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 5 (100.0000%) | 2.500000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| TJNEQKITOYTGIDU3GCADWOP6HFHY2QAAB6BDCEBDU5XHO7535RPJWESPEA | MERCHANT-FUNDED | 5 | 2.500000 (100.0000%) | created by merchant; merchant sent 39.69 ALGO; merchant sent 4.43 USDC ×1 (177% of paid); throwaway wallet |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | http://companylens-api-production.up.railway.app/company/00445790 | 5 (100.0000%) | 2.500000 (100.0000%) | 1 | 0 | 5 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: companylens-api-production.up.railway.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| companylens-api-production.up.railway.app | hosting_provider_domain | yes, cached | 2026-10-05T06:55:10.732000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| companylens-api-production.up.railway.app | CompanyLens — UK company risk checks for AI agents | not recorded | Risk profiles for UK companies from live Companies House data. 0.50 USDC per lookup via x402 on Algorand. No account or API key. | not recorded | https://companylens.xyz/og.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| companylens-api-production.up.railway.app | llms.txt | CompanyLens | http://companylens-api-production.up.railway.app/llms.txt | not recorded |

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
| 2026-09-21 | 1 | 0.500000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-22 | 4 | 2.000000 | 1 | 0 | 4 (100.0000%) |

Last 2 of 2 active days; all in the daily CSV.
