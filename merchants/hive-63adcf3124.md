# Hive — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `UEJCNTRQV0JQQksyQzNNVTIyWE43UFNE`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | PBB54PWBPBK2C3MU22XN7PSD6WECYVY2ONJVI34OLYCY7UHSFY4RJIW5IY |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 387 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 3.302000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 387 (100.0000%) · 3.302000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 226 (58.3979%) · 0.692000 USDC (20.9570%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-05 23:22:15 UTC / 2026-08-08 02:29:34 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/hive-63adcf3124-transactions.csv.gz) · [All endpoints](../evidence/hive-63adcf3124-endpoints.csv) · [Payer evidence](../evidence/hive-63adcf3124-payers.csv) · [Daily metrics](../evidence/hive-63adcf3124-daily.csv) · [Site and catalog data](../evidence/hive-63adcf3124-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 387 (100.0000%) | 3.302000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| ZJHIT6OT7VPUWA5FTVJ63GKNGHYJH665NJQ35OC7XHFWI5PGICUGUB5HO4 | NO-LINK-DETECTED | 386 | 3.297000 (99.8486%) | 61% of gaps &lt; 60s |
| SJ22FPK5EKMKQJKLEQJLRTOJAKRI7VO6D4N5LW7YTIMKZNPBWT4N27E3G4 | NO-LINK-DETECTED | 1 | 0.005000 (0.1514%) |  |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

226 (58.3979%) settlements · 0.692000 (20.9570%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | http://head-hive.fly.dev/api/memory/recall | 146 (37.7261%) | 0.292000 (8.8431%) | 1 | 146 | 0 |
| POST | http://head-hive.fly.dev/api/ask | 123 (31.7829%) | 1.230000 (37.2502%) | 1 | 0 | 0 |
| POST | http://head-hive.fly.dev/api/memory/store | 80 (20.6718%) | 0.400000 (12.1139%) | 2 | 80 | 0 |
| POST | http://head-hive.fly.dev/api/extract | 19 (4.9096%) | 0.380000 (11.5082%) | 1 | 0 | 0 |
| POST | http://head-hive.fly.dev/api/plan | 18 (4.6512%) | 0.900000 (27.2562%) | 1 | 0 | 0 |
| POST | http://head-hive.fly.dev/api/analyze | 1 (0.2584%) | 0.100000 (3.0285%) | 1 | 0 | 0 |

Top 6 of 6 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: head-hive.fly.dev.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| head-hive.fly.dev | hosting_provider_domain | yes, cached | 2026-10-06T10:42:01.803000+00:00 | 4 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| head-hive.fly.dev | Head · Hive | Hive | Hive sells AI reasoning skills and agent infrastructure (memory, inbox, escrow, job queues) over the open x402 standard. Pay per call in USDC on Algorand MainNet via the GoPlausible facilitator (Global x402 Challenge). Base settlement is optional when configured. No Hive account or API key — payment is the credential. | https://head-hive.fly.dev/logo.png | https://head-hive.fly.dev/og.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| head-hive.fly.dev | A2A Agent Card | Hive | http://head-hive.fly.dev/.well-known/agent-card.json | Hive sells AI reasoning skills and agent infrastructure (memory, inbox, escrow, job queues) over the open x402 standard. Pay per call in USDC on Algorand MainNet via the GoPlausible facilitator (Global x402 Challenge). Base settlement is optional when configured. No Hive account or API key — payment is the credential. |
| head-hive.fly.dev | AI Plugin | Head · Hive | http://head-hive.fly.dev/.well-known/ai-plugin.json | AI skills and agent infrastructure, paid per request in USDC — for people, teams, and autonomous agents. |
| head-hive.fly.dev | x402 Discovery | Hive | http://head-hive.fly.dev/.well-known/x402 | Hive sells AI reasoning skills and agent infrastructure (memory, inbox, escrow, job queues) over the open x402 standard. Pay per call in USDC on Algorand MainNet via the GoPlausible facilitator (Global x402 Challenge). Base settlement is optional when configured. No Hive account or API key — payment is the credential. |
| head-hive.fly.dev | llms.txt | Head · Hive | http://head-hive.fly.dev/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 4 |
| Agent document types | ["agent-card", "ai-plugin", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 6 |
| Description count | 6 |
| Mime type count | 6 |
| Accepts count | 6 |
| Discovery count | 6 |
| Input documentation count | 6 |
| Output documentation count | 6 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-05 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-08-06 | 118 | 1.065000 | 1 | 69 | 0 (0.0000%) |
| 2026-08-07 | 206 | 1.587000 | 1 | 114 | 0 (0.0000%) |
| 2026-08-08 | 62 | 0.645000 | 1 | 42 | 0 (0.0000%) |

Last 4 of 4 active days; all in the daily CSV.
