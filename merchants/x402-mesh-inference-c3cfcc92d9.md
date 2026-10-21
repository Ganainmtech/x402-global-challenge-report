# x402 Mesh Inference — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `NUdLSkNPQ0JGNk5ESUk2UkNUUDJDRE9U`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 5GKJCOCBF6NDII6RCTP2CDOTTJ4ACHE3QYJYHQOLI23E254BDUBTZKY6GA |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 26 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.092000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 26 (100.0000%) · 0.092000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 26 (100.0000%) · 0.092000 USDC (100.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 26 (100.0000%) · 0.092000 USDC (100.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-05 21:33:23 UTC / 2026-08-07 01:51:02 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/x402-mesh-inference-c3cfcc92d9-transactions.csv.gz) · [All endpoints](../evidence/x402-mesh-inference-c3cfcc92d9-endpoints.csv) · [Payer evidence](../evidence/x402-mesh-inference-c3cfcc92d9-payers.csv) · [Daily metrics](../evidence/x402-mesh-inference-c3cfcc92d9-daily.csv) · [Site and catalog data](../evidence/x402-mesh-inference-c3cfcc92d9-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 26 (100.0000%) | 0.092000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| VNAZPGAN6YVDMBADXR7NF25VY7ZKXAM6G65JZKU2W4OXFMVWQ7UEQ5ILCA | MERCHANT-FUNDED | 26 | 0.092000 (100.0000%) | created by merchant's creator; throwaway wallet; 80% of gaps &lt; 60s |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

26 (100.0000%) settlements · 0.092000 (100.0000%) USDC. Paid by synthetic-indicated payers: 26 (100.0000%) settlements · 0.092000 (100.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://x402-mesh-gateway.fly.dev/v1/inference | 17 (65.3846%) | 0.042000 (45.6522%) | 1 | 17 | 17 |
| POST | https://x402-mesh-gateway.fly.dev/v1/chat/completions | 9 (34.6154%) | 0.050000 (54.3478%) | 1 | 9 | 9 |

Top 2 of 2 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: x402-mesh-gateway.fly.dev.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| x402-mesh-gateway.fly.dev | hosting_provider_domain | yes, cached | 2026-10-04T16:58:40.572000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| x402-mesh-gateway.fly.dev | x402 Mesh Inference | not recorded | Pay-per-prompt AI inference settled on Algorand via HTTP 402. | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| x402-mesh-gateway.fly.dev | x402 Discovery | not recorded | https://x402-mesh-gateway.fly.dev/.well-known/x402 | Pay-per-prompt OpenAI-compatible chat completions routed across a mesh of independent GPU nodes, settled in USDC on Algorand via x402. |
| x402-mesh-gateway.fly.dev | llms.txt | x402 Mesh Inference | https://x402-mesh-gateway.fly.dev/llms.txt | not recorded |

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
| 2026-08-05 | 8 | 0.048000 | 1 | 8 | 8 (100.0000%) |
| 2026-08-06 | 16 | 0.032000 | 1 | 16 | 16 (100.0000%) |
| 2026-08-07 | 2 | 0.012000 | 1 | 2 | 2 (100.0000%) |

Last 3 of 3 active days; all in the daily CSV.
