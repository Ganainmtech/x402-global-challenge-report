# Arbiter — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `R0JSTzVFTTRKTTU3UERQUzRBNTMzVjdK`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | GBRO5EM4JM57PDPS4A533V7JZNWFWB7S6IRT5UZNQYPPUN7XEEGJLEHW6I |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 11 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.302000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 6 (54.5455%) · 0.276000 USDC (91.3907%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 5 (45.4545%) · 0.026000 USDC (8.6093%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 6 (54.5455%) · 0.012000 USDC (3.9735%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 3 (27.2727%) · 0.006000 USDC (1.9868%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-06 11:16:24 UTC / 2026-08-07 10:11:16 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/arbiter-2b0a0e7e46-transactions.csv.gz) · [All endpoints](../evidence/arbiter-2b0a0e7e46-endpoints.csv) · [Payer evidence](../evidence/arbiter-2b0a0e7e46-payers.csv) · [Daily metrics](../evidence/arbiter-2b0a0e7e46-daily.csv) · [Site and catalog data](../evidence/arbiter-2b0a0e7e46-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 6 (54.5455%) | 0.276000 (91.3907%) |
| NO-LINK-DETECTED | 5 (45.4545%) | 0.026000 (8.6093%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| CTPTCHRJ4GK5BWESYO6BMKMJ7E62FUXW55OJH3B5WIRA5JK22VATB5RH54 | MERCHANT-FUNDED | 6 | 0.276000 (91.3907%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 1.50 USDC ×1 (543% of paid); throwaway wallet |
| MUJMIBSK3SJBLERZWJ7UNG64C6NXO5LD62M7CL7LKK6SKEDXC4FVPZ4VSY | NO-LINK-DETECTED | 5 | 0.026000 (8.6093%) | throwaway wallet; 75% of gaps &lt; 60s; pays 10 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

6 (54.5455%) settlements · 0.012000 (3.9735%) USDC. Paid by synthetic-indicated payers: 3 (27.2727%) settlements · 0.006000 (1.9868%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://arbiter-hs23.onrender.com/v1/judge/transaction | 6 (54.5455%) | 0.012000 (3.9735%) | 2 | 6 | 3 |
| POST | https://arbiter-hs23.onrender.com/v1/judge/counterparty | 4 (36.3636%) | 0.040000 (13.2450%) | 2 | 0 | 2 |
| POST | https://arbiter-hs23.onrender.com/v1/judge/human | 1 (9.0909%) | 0.250000 (82.7815%) | 1 | 0 | 1 |

Top 3 of 3 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: arbiter-hs23.onrender.com, arbiter-x402.fly.dev.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| arbiter-hs23.onrender.com | hosting_provider_domain | yes, cached | 2026-10-06T06:30:00.618000+00:00 | 1 |
| arbiter-x402.fly.dev | hosting_provider_domain | not established | 2026-08-22T04:18:08.594000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| arbiter-hs23.onrender.com | Arbiter — judgment for autonomous agents | Arbiter | A paid API that tells an AI agent whether an action is safe before it takes it. Transaction firewall, counterparty verification and human judgment, settled per call in USDC on Algorand. | https://arbiter-hs23.onrender.com/icon.png | https://arbiter-hs23.onrender.com/icon.png | #06090d |
| arbiter-x402.fly.dev | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| arbiter-hs23.onrender.com | x402 Discovery | not recorded | https://arbiter-hs23.onrender.com/.well-known/x402 | not recorded |
| arbiter-x402.fly.dev | x402 Discovery | not recorded | https://arbiter-x402.fly.dev/.well-known/x402 | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 2 |
| Agent document types | ["x402"] |
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
| 2026-08-06 | 4 | 0.264000 | 1 | 2 | 4 (100.0000%) |
| 2026-08-07 | 7 | 0.038000 | 2 | 4 | 2 (28.5714%) |

Last 2 of 2 active days; all in the daily CSV.
