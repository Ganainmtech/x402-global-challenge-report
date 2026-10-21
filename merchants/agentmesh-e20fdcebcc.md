# AgentMesh — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 68, 84).

## Identity and accounts

Merchant ID: `TTZKUU5KVlgzMkhFTjJMUzVXMldYMlBN`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | M6JQNJVX32HEN2LS5W2WX2PMSXPDHHKADVUATIQ5KQIVVVHSVILQNOS62A |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 68 | AgentMesh | Exact submitted wallet M6JQNJVX32HEN2LS5W2WX2PMSXPDHHKADVUATIQ5KQIVVVHSVILQNOS62A is a receiving account of this merchant. |
| 84 | AgentMesh | Exact submitted wallet M6JQNJVX32HEN2LS5W2WX2PMSXPDHHKADVUATIQ5KQIVVVHSVILQNOS62A is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 2,194 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 2,325.892000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 2,193 (99.9544%) · 2,325.882000 USDC (99.9996%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 1 (0.0456%) · 0.010000 USDC (0.0004%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-01 20:57:51 UTC / 2026-10-06 09:05:58 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/agentmesh-e20fdcebcc-transactions.csv.gz) · [All endpoints](../evidence/agentmesh-e20fdcebcc-endpoints.csv) · [Payer evidence](../evidence/agentmesh-e20fdcebcc-payers.csv) · [Daily metrics](../evidence/agentmesh-e20fdcebcc-daily.csv) · [Site and catalog data](../evidence/agentmesh-e20fdcebcc-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 2,193 (99.9544%) | 2,325.882000 (99.9996%) |
| NO-LINK-DETECTED | 1 (0.0456%) | 0.010000 (0.0004%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| SCI6OBXB326RUY5N7S2KPMSNX6QWMT4RTTMGDDKKL3OZB7TSPSV73Z7OGE | MERCHANT-FUNDED | 2,193 | 2,325.882000 (99.9996%) | created by merchant's creator; merchant sent 1,988 USDC ×23 (85% of paid); throwaway wallet; 69% of gaps &lt; 60s; pays 2 merchants |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 1 | 0.010000 (0.0004%) | pays 16 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://www.agent-mesh.app/api/x402/relay | 849 (38.6964%) | 827.918000 (35.5957%) | 2 | 0 | 848 |
| GET | https://www.agent-mesh.app/api/x402/relay/platform-fee | 689 (31.4038%) | 1,033.500000 (44.4346%) | 1 | 0 | 689 |
| GET | https://www.agent-mesh.app/api/x402/relay/run-total | 403 (18.3683%) | 110.980000 (4.7715%) | 1 | 0 | 403 |
| GET | https://www.agent-mesh.app/api/x402/relay/run-funding | 251 (11.4403%) | 353.234000 (15.1870%) | 1 | 0 | 251 |
| GET | https://wailist-agentmesh-production-f943.up.railway.app/x402/relay | 2 (0.0912%) | 0.260000 (0.0112%) | 1 | 0 | 2 |

Top 5 of 5 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: canix402-api.compx.io, wailist-agentmesh-production-f943.up.railway.app, www.agent-mesh.app.

Custom-domain candidates: canix402-api.compx.io, www.agent-mesh.app. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| canix402-api.compx.io | custom_domain_candidate | yes, cached | 2026-10-05T14:43:35.029000+00:00 | 5 |
| wailist-agentmesh-production-f943.up.railway.app | hosting_provider_domain | not established | 2026-08-01T18:33:14.666000+00:00 | 0 |
| www.agent-mesh.app | custom_domain_candidate | yes, cached | 2026-10-06T10:37:40.695000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| canix402-api.compx.io | CANIX402 \| Hunting down the best yields | CANIX402 | Canix402 is an x402-paid DeFi opportunity API for autonomous agents. Discover endpoints, pay in USDC, and fetch normalized APY data — including wallet-personalized yield recommendations. | https://canix402-api.compx.io/logo.png | https://canix402-api.compx.io/banner.png | not recorded |
| wailist-agentmesh-production-f943.up.railway.app | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |
| www.agent-mesh.app | AgentMesh | AgentMesh | Design, deploy, and monitor AI agent workflows. | https://www.agent-mesh.app/logo.png | https://www.agent-mesh.app/opengraph-image.png | #08070c |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| canix402-api.compx.io | A2A Agent Card | canix402 | https://canix402-api.compx.io/.well-known/agent-card.json | x402-gated DeFi data and walletless transaction API for agents. Paid requests settle in Algorand USDC, or Base USDC when that accept is listed, through the public Caddy gateway; no API keys or server-side wallet access. |
| canix402-api.compx.io | Agent Manifest | canix402 | https://canix402-api.compx.io/.well-known/agent.json | x402-gated DeFi data and walletless transaction API for agents. Paid requests settle in Algorand USDC, or Base USDC when that accept is listed, through the public Caddy gateway; no API keys or server-side wallet access. |
| canix402-api.compx.io | AI Plugin | canix402 | https://canix402-api.compx.io/.well-known/ai-plugin.json | DeFi data and walletless transaction API for agents, paid per call with USDC using x402. |
| canix402-api.compx.io | x402 Discovery | not recorded | https://canix402-api.compx.io/.well-known/x402 | not recorded |
| canix402-api.compx.io | llms.txt | CANIX402 | https://canix402-api.compx.io/llms.txt | not recorded |
| www.agent-mesh.app | A2A Agent Card | AgentMesh | https://www.agent-mesh.app/.well-known/agent-card.json | Design, deploy, and monitor AI agent workflows. Agents call tools through function calling and pay for x402-gated endpoints on Algorand mid-run, without a human in the loop. |
| www.agent-mesh.app | llms.txt | AgentMesh | https://www.agent-mesh.app/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 3 |
| Cached domain metadata count | 3 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 7 |
| Agent document types | ["agent-card", "agent-json", "ai-plugin", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 4 |
| Description count | 4 |
| Mime type count | 4 |
| Accepts count | 4 |
| Discovery count | 4 |
| Input documentation count | 4 |
| Output documentation count | 1 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-07 | 29 | 24.900000 | 1 | 0 | 29 (100.0000%) |
| 2026-09-08 | 84 | 74.332000 | 1 | 0 | 84 (100.0000%) |
| 2026-09-09 | 19 | 15.950000 | 1 | 0 | 19 (100.0000%) |
| 2026-09-10 | 41 | 24.540000 | 1 | 0 | 41 (100.0000%) |
| 2026-09-11 | 10 | 6.840000 | 1 | 0 | 10 (100.0000%) |
| 2026-09-12 | 9 | 5.270000 | 1 | 0 | 9 (100.0000%) |
| 2026-09-13 | 9 | 5.770000 | 1 | 0 | 9 (100.0000%) |
| 2026-09-14 | 79 | 97.260000 | 1 | 0 | 79 (100.0000%) |
| 2026-09-15 | 65 | 67.470000 | 1 | 0 | 65 (100.0000%) |
| 2026-09-16 | 70 | 72.450000 | 1 | 0 | 70 (100.0000%) |
| 2026-09-17 | 47 | 52.620000 | 1 | 0 | 47 (100.0000%) |
| 2026-09-18 | 52 | 57.350000 | 1 | 0 | 52 (100.0000%) |
| 2026-09-19 | 48 | 52.150000 | 1 | 0 | 48 (100.0000%) |
| 2026-09-20 | 49 | 51.190000 | 1 | 0 | 49 (100.0000%) |
| 2026-09-21 | 49 | 52.360000 | 1 | 0 | 49 (100.0000%) |
| 2026-09-22 | 23 | 24.830000 | 1 | 0 | 23 (100.0000%) |
| 2026-09-23 | 50 | 57.230000 | 1 | 0 | 50 (100.0000%) |
| 2026-09-24 | 60 | 70.870000 | 1 | 0 | 60 (100.0000%) |
| 2026-09-25 | 49 | 60.060000 | 1 | 0 | 49 (100.0000%) |
| 2026-09-26 | 55 | 63.820000 | 1 | 0 | 55 (100.0000%) |
| 2026-09-27 | 43 | 47.170000 | 1 | 0 | 43 (100.0000%) |
| 2026-09-28 | 90 | 107.870000 | 1 | 0 | 90 (100.0000%) |
| 2026-09-29 | 75 | 82.700000 | 1 | 0 | 75 (100.0000%) |
| 2026-09-30 | 74 | 83.350000 | 1 | 0 | 74 (100.0000%) |
| 2026-10-01 | 50 | 51.560000 | 1 | 0 | 50 (100.0000%) |
| 2026-10-02 | 72 | 78.300000 | 1 | 0 | 72 (100.0000%) |
| 2026-10-03 | 84 | 93.370000 | 1 | 0 | 84 (100.0000%) |
| 2026-10-04 | 48 | 51.860000 | 1 | 0 | 48 (100.0000%) |
| 2026-10-05 | 52 | 55.980000 | 1 | 0 | 52 (100.0000%) |
| 2026-10-06 | 9 | 9.120000 | 1 | 0 | 9 (100.0000%) |

Last 30 of 52 active days; all in the daily CSV.
