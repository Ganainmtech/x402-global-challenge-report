# Rampa — LATAM stablecoin cash-out & FX intelligence for AI agents — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `VjdRWVdNTjdEUzRFUUk0WTdKTFZZWE9C`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | V7QYWMN7DS4EQI4Y7JLVYXOBBYLO3VUQGGSRB2P52AUBX326ZPNORFU4KY |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 10 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.180000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 10 (100.0000%) · 0.180000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-27 02:55:13 UTC / 2026-07-28 13:49:54 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/rampa-latam-stablecoin-cash-out-fx-intelligence-for-ai-agents-d5494334be-transactions.csv.gz) · [All endpoints](../evidence/rampa-latam-stablecoin-cash-out-fx-intelligence-for-ai-agents-d5494334be-endpoints.csv) · [Payer evidence](../evidence/rampa-latam-stablecoin-cash-out-fx-intelligence-for-ai-agents-d5494334be-payers.csv) · [Daily metrics](../evidence/rampa-latam-stablecoin-cash-out-fx-intelligence-for-ai-agents-d5494334be-daily.csv) · [Site and catalog data](../evidence/rampa-latam-stablecoin-cash-out-fx-intelligence-for-ai-agents-d5494334be-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 10 (100.0000%) | 0.180000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| DEVCP7SJ54FXHIG5D7JWEI3QYHUKPQYJZXIRCPBXV32PRAMWBVH3T3GKVY | NO-LINK-DETECTED | 10 | 0.180000 (100.0000%) | throwaway wallet; same funder as merchant (hub) |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | http://rampa-x402-production.up.railway.app/v1/rates | 6 (60.0000%) | 0.060000 (33.3333%) | 1 | 0 | 0 |
| GET | http://rampa-x402-production.up.railway.app/v1/fees | 1 (10.0000%) | 0.020000 (11.1111%) | 1 | 0 | 0 |
| GET | http://rampa-x402-production.up.railway.app/v1/route | 1 (10.0000%) | 0.050000 (27.7778%) | 1 | 0 | 0 |
| GET | http://rampa-x402-production.up.railway.app/v1/spread | 1 (10.0000%) | 0.030000 (16.6667%) | 1 | 0 | 0 |
| GET | http://rampa-x402-production.up.railway.app/v1/yields | 1 (10.0000%) | 0.020000 (11.1111%) | 1 | 0 | 0 |

Top 5 of 5 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: rampa-x402-production.up.railway.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| rampa-x402-production.up.railway.app | hosting_provider_domain | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| rampa-x402-production.up.railway.app | Rampa — LATAM stablecoin cash-out & FX intelligence for AI agents | not recorded | Best net off-ramp route, spreads, arbitrage, yields and fees across 11 LATAM countries. Pay-per-call via x402 on Algorand. | http://rampa-x402-production.up.railway.app/logo.png | https://rampa-x402-production.up.railway.app/logo.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| rampa-x402-production.up.railway.app | A2A Agent Card | Rampa | http://rampa-x402-production.up.railway.app/.well-known/agent-card.json | Real-time LATAM stablecoin cash-out, FX, spreads, yields and fee intelligence for AI agents. Pay-per-request in USDC on Algorand via x402. 11 countries. |
| rampa-x402-production.up.railway.app | llms.txt | Rampa | http://rampa-x402-production.up.railway.app/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 2 |
| Agent document types | ["agent-card", "llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-07-27 | 8 | 0.160000 | 1 | 0 | 0 (0.0000%) |
| 2026-07-28 | 2 | 0.020000 | 1 | 0 | 0 (0.0000%) |

Last 2 of 2 active days; all in the daily CSV.
