# Algo Verdict API — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `TUdWVVpXRDJBUUlMR0dJUEVYUzZLTTNP`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | MGVUZWD2AQILGGIPEXS6KM3ONVJDFX7HEVVM4WHTVMUYLTD74VFQ5CO7BU |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 13 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.580000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 12 (92.3077%) · 0.550000 USDC (94.8276%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 1 (7.6923%) · 0.030000 USDC (5.1724%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 1 (7.6923%) · 0.030000 USDC (5.1724%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-26 15:46:58 UTC / 2026-07-27 22:30:29 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/algo-verdict-api-0b8a22c0b6-transactions.csv.gz) · [All endpoints](../evidence/algo-verdict-api-0b8a22c0b6-endpoints.csv) · [Payer evidence](../evidence/algo-verdict-api-0b8a22c0b6-payers.csv) · [Daily metrics](../evidence/algo-verdict-api-0b8a22c0b6-daily.csv) · [Site and catalog data](../evidence/algo-verdict-api-0b8a22c0b6-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 12 (92.3077%) | 0.550000 (94.8276%) |
| NO-LINK-DETECTED | 1 (7.6923%) | 0.030000 (5.1724%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| YRXVIEPOQJPGYUDPUQBT7UF3AMVX7VEOZEHRI5M5N4FBNYOIZY6ZWJBAF4 | MERCHANT-FUNDED | 12 | 0.550000 (94.8276%) | created by merchant's creator; throwaway wallet; 91% of gaps &lt; 60s |
| 57F2QR2RAI5LYJ2F4ZIC6AJEIINS62WGA7TLSILCAZOZHS7CLTPFU6QQVU | NO-LINK-DETECTED | 1 | 0.030000 (5.1724%) | throwaway wallet; pays 4 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://algorand-inteligence-api-production.up.railway.app/watch/poll | 2 (15.3846%) | 0.020000 (3.4483%) | 1 | 0 | 2 |
| (not recorded) | (not recorded) | 1 (7.6923%) | 0.030000 (5.1724%) | 1 | 0 | 0 |
| POST | https://algorand-inteligence-api-production.up.railway.app/ask | 1 (7.6923%) | 0.120000 (20.6897%) | 1 | 0 | 1 |
| POST | https://algorand-inteligence-api-production.up.railway.app/contract/analyze | 1 (7.6923%) | 0.050000 (8.6207%) | 1 | 0 | 1 |
| POST | https://algorand-inteligence-api-production.up.railway.app/discover | 1 (7.6923%) | 0.030000 (5.1724%) | 1 | 0 | 1 |
| POST | https://algorand-inteligence-api-production.up.railway.app/portfolio | 1 (7.6923%) | 0.040000 (6.8966%) | 1 | 0 | 1 |
| POST | https://algorand-inteligence-api-production.up.railway.app/reputation | 1 (7.6923%) | 0.020000 (3.4483%) | 1 | 0 | 1 |
| POST | https://algorand-inteligence-api-production.up.railway.app/smart-money | 1 (7.6923%) | 0.100000 (17.2414%) | 1 | 0 | 1 |
| POST | https://algorand-inteligence-api-production.up.railway.app/token/analyze | 1 (7.6923%) | 0.050000 (8.6207%) | 1 | 0 | 1 |
| POST | https://algorand-inteligence-api-production.up.railway.app/tx/explain | 1 (7.6923%) | 0.020000 (3.4483%) | 1 | 0 | 1 |
| POST | https://algorand-inteligence-api-production.up.railway.app/tx/simulate | 1 (7.6923%) | 0.020000 (3.4483%) | 1 | 0 | 1 |
| POST | https://algorand-inteligence-api-production.up.railway.app/wallet/analyze | 1 (7.6923%) | 0.080000 (13.7931%) | 1 | 0 | 1 |

Top 12 of 12 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: algorand-inteligence-api-production.up.railway.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| algorand-inteligence-api-production.up.railway.app | hosting_provider_domain | yes, cached | 2026-10-06T03:39:25.990000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| algorand-inteligence-api-production.up.railway.app | Algo Verdict API — The blockchain intelligence layer for AI agents, wallets and DeFi | Algo Verdict API | Explainable blockchain intelligence that AI agents buy per request, settled in USDC on Algorand over x402. No API key, no account, no subscription. | https://algorand-inteligence-api-production.up.railway.app/apple-touch-icon.png | https://algoverdict.xyz/og.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| algorand-inteligence-api-production.up.railway.app | x402 Discovery | Algo Verdict API | https://algorand-inteligence-api-production.up.railway.app/.well-known/x402 | Explainable blockchain intelligence for AI agents, wallets and DeFi, paid per request in USDC on Algorand via x402. |
| algorand-inteligence-api-production.up.railway.app | llms.txt | Algo Verdict API | https://algorand-inteligence-api-production.up.railway.app/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
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
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 11 |
| Description count | 11 |
| Mime type count | 11 |
| Accepts count | 11 |
| Discovery count | 11 |
| Input documentation count | 11 |
| Output documentation count | 11 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-07-26 | 12 | 0.550000 | 1 | 0 | 12 (100.0000%) |
| 2026-07-27 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |

Last 2 of 2 active days; all in the daily CSV.
