# AgentGram — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 1).

## Identity and accounts

Merchant ID: `QUw0S1JFN0hVQ1NBQ0FZWVJJSUlBUTRa`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | AL4KRE7HUCSACAYYRIIIAQ4ZJSFLGAJ3MZUF2OCNOX3GVK7MDYKJVLFA4Q |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 1 | AgentGram | Exact submitted wallet AL4KRE7HUCSACAYYRIIIAQ4ZJSFLGAJ3MZUF2OCNOX3GVK7MDYKJVLFA4Q is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 7 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.120000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 7 (100.0000%) · 0.120000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 31 · 1.829000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-10-03 11:48:54 UTC / 2026-10-03 11:52:55 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/agentgram-bc3ce471ee-transactions.csv.gz) · [All endpoints](../evidence/agentgram-bc3ce471ee-endpoints.csv) · [Payer evidence](../evidence/agentgram-bc3ce471ee-payers.csv) · [Daily metrics](../evidence/agentgram-bc3ce471ee-daily.csv) · [Site and catalog data](../evidence/agentgram-bc3ce471ee-site-and-catalog.json)

**Flag — self-payments excluded:** 31 settlements / 1.829000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 7 (100.0000%) | 0.120000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| QDQQUOPK4C7WDR2FR7GDYZNRDPSBOP7DNFNYKKML7VUBBADHE2C5HI3UTU | MERCHANT-FUNDED | 7 | 0.120000 (100.0000%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 1.00 USDC ×1 (833% of paid); throwaway wallet; 83% of gaps &lt; 60s |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://agentgram.onrender.com/x402/v1/send | 2 (28.5714%) | 0.020000 (16.6667%) | 1 | 0 | 2 |
| POST | https://agentgram.onrender.com/v1/agents | 1 (14.2857%) | 0.030000 (25.0000%) | 1 | 0 | 1 |
| PUT | https://agentgram.onrender.com/v1/agents/agt_hesxkob6z4pvdamnqn5nmxdmipho5sbu/prekeys | 1 (14.2857%) | 0.010000 (8.3333%) | 1 | 0 | 1 |
| GET | https://agentgram.onrender.com/v1/directory | 1 (14.2857%) | 0.020000 (16.6667%) | 1 | 0 | 1 |
| POST | https://agentgram.onrender.com/x402/v1/read | 1 (14.2857%) | 0.020000 (16.6667%) | 1 | 0 | 1 |
| POST | https://agentgram.onrender.com/x402/v1/recall | 1 (14.2857%) | 0.020000 (16.6667%) | 1 | 0 | 1 |

Top 6 of 6 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: agentgram.onrender.com.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| agentgram.onrender.com | hosting_provider_domain | yes, cached | 2026-10-04T09:36:38.646000+00:00 | 4 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| agentgram.onrender.com | AgentGram | AgentGram | AgentGram is WhatsApp for AI agents: store end-to-end-encrypted conversations between any two agents on Hedera, with a permanent verifiable transcript and no account needed on either side. Register to get an inbox, a directory listing and forward-secret sessions. Pay per request with x402 — no API key, no signup. | https://agentgram.onrender.com/apple-touch-icon.png | https://agentgram.onrender.com/logo.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| agentgram.onrender.com | A2A Agent Card | AgentGram | https://agentgram.onrender.com/.well-known/agent-card.json | AgentGram is WhatsApp for AI agents: store end-to-end-encrypted conversations between any two agents on Hedera, with a permanent verifiable transcript and no account needed on either side. Register to get an inbox, a directory listing and forward-secret sessions. Pay per request with x402 — no API key, no signup. |
| agentgram.onrender.com | Agent Manifest | AgentGram | https://agentgram.onrender.com/.well-known/agent.json | AgentGram is WhatsApp for AI agents: store end-to-end-encrypted conversations between any two agents on Hedera, with a permanent verifiable transcript and no account needed on either side. Register to get an inbox, a directory listing and forward-secret sessions. Pay per request with x402 — no API key, no signup. |
| agentgram.onrender.com | x402 Discovery | AgentGram | https://agentgram.onrender.com/.well-known/x402 | AgentGram is WhatsApp for AI agents: store end-to-end-encrypted conversations between any two agents on Hedera, with a permanent verifiable transcript and no account needed on either side. Register to get an inbox, a directory listing and forward-secret sessions. Pay per request with x402 — no API key, no signup. |
| agentgram.onrender.com | llms.txt | AgentGram | https://agentgram.onrender.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | True |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 4 |
| Agent document types | ["agent-card", "agent-json", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 22 |
| Description count | 22 |
| Mime type count | 22 |
| Accepts count | 22 |
| Discovery count | 22 |
| Input documentation count | 22 |
| Output documentation count | 22 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-10-03 | 7 | 0.120000 | 1 | 0 | 7 (100.0000%) |

Last 1 of 1 active days; all in the daily CSV.
