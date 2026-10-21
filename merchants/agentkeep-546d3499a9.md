# AgentKeep — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 37, 38).

## Identity and accounts

Merchant ID: `MlZJVTJOMjVTMlRSQUo1NFpUVVk1Q1NG`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 2VIU2N25S2TRAJ54ZTUY5CSFADU6Y5KEMKAWTRWR2ODNTPULNGHBKWEPTQ |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 37 | Agent Keep | Exact submitted wallet 2VIU2N25S2TRAJ54ZTUY5CSFADU6Y5KEMKAWTRWR2ODNTPULNGHBKWEPTQ is a receiving account of this merchant. |
| 38 | Agent Keep | Exact submitted wallet 2VIU2N25S2TRAJ54ZTUY5CSFADU6Y5KEMKAWTRWR2ODNTPULNGHBKWEPTQ is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 95 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.372500 | USDC settled. |
| Unique payer accounts | 4 | Distinct accounts that paid. |
| Synthetic-indicated | 59 (62.1053%) · 0.188500 USDC (50.6040%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 36 (37.8947%) · 0.184000 USDC (49.3960%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 76 (80.0000%) · 0.142500 USDC (38.2550%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 50 (52.6316%) · 0.088500 USDC (23.7584%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-23 22:59:19 UTC / 2026-10-06 00:02:22 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/agentkeep-546d3499a9-transactions.csv.gz) · [All endpoints](../evidence/agentkeep-546d3499a9-endpoints.csv) · [Payer evidence](../evidence/agentkeep-546d3499a9-payers.csv) · [Daily metrics](../evidence/agentkeep-546d3499a9-daily.csv) · [Site and catalog data](../evidence/agentkeep-546d3499a9-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 59 (62.1053%) | 0.188500 (50.6040%) |
| NO-LINK-DETECTED | 36 (37.8947%) | 0.184000 (49.3960%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 35 | 0.182000 (48.8591%) | throwaway wallet; created by vet402; pays 68 merchants |
| BM3BWAMR23YJQYP7CWRRZAKJ6PVQYM2QITPOPQ3FXI3HWWQKGST6RVTF2M | MERCHANT-FUNDED | 51 | 0.172500 (46.3087%) | created by merchant; merchant sent 0.5 ALGO; throwaway wallet; 52% of gaps &lt; 60s |
| EINK3NJNGXUG6XG4CTNBI3WVRX2W3I3FTNPCN423DEMHHZVQG3BTK6HAJM | MERCHANT-FUNDED | 8 | 0.016000 (4.2953%) | created by merchant; merchant sent 0.5 ALGO; merchant sent 0.2 USDC ×1 (1250% of paid); throwaway wallet |
| 2MSEYNHSCPWU6IJOSZI6R54P4BN2CDFMELTMD3GHIVMSF7SQZIUUF6BJLQ | NO-LINK-DETECTED | 1 | 0.002000 (0.5369%) | throwaway wallet; created by vet402; pays 3 merchants |

Top 4 of 4 payers; all in the payer CSV.

## Sub-cent settlements

76 (80.0000%) settlements · 0.142500 (38.2550%) USDC. Paid by synthetic-indicated payers: 50 (52.6316%) settlements · 0.088500 (23.7584%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://api.agentkeep.online/v1/memory | 28 (29.4737%) | 0.028000 (7.5168%) | 3 | 28 | 18 |
| POST | https://api.agentkeep.online/v1/artifacts | 10 (10.5263%) | 0.050000 (13.4228%) | 3 | 10 | 6 |
| GET | https://api.agentkeep.online/v1/budget/receipts | 10 (10.5263%) | 0.020000 (5.3691%) | 3 | 10 | 2 |
| POST | https://api.agentkeep.online/v1/fetch | 6 (6.3158%) | 0.060000 (16.1074%) | 2 | 0 | 2 |
| GET | https://api.agentkeep.online/v1/trust | 5 (5.2632%) | 0.010000 (2.6846%) | 2 | 5 | 1 |
| PUT | https://agent-keep-3jimn6j2va-ew.a.run.app/v1/memory/canary | 3 (3.1579%) | 0.003000 (0.8054%) | 1 | 3 | 3 |
| POST | https://api.agentkeep.online/v1/notify | 3 (3.1579%) | 0.060000 (16.1074%) | 1 | 0 | 0 |
| POST | https://api.agentkeep.online/v1/owner/bind/email | 3 (3.1579%) | 0.030000 (8.0537%) | 1 | 0 | 0 |
| POST | https://agent-keep-684642514120.europe-west1.run.app/v1/artifacts | 2 (2.1053%) | 0.010000 (2.6846%) | 1 | 2 | 2 |
| GET | https://agent-keep-684642514120.europe-west1.run.app/v1/budget/receipts | 2 (2.1053%) | 0.004000 (1.0738%) | 1 | 2 | 2 |
| POST | https://agent-keep-684642514120.europe-west1.run.app/v1/fetch | 2 (2.1053%) | 0.020000 (5.3691%) | 1 | 0 | 2 |
| PUT | https://agent-keep-684642514120.europe-west1.run.app/v1/memory/canary | 2 (2.1053%) | 0.002000 (0.5369%) | 1 | 2 | 2 |
| (not recorded) | https://agent-keep-684642514120.europe-west1.run.app/v1/owner/bind/email | 2 (2.1053%) | 0.020000 (5.3691%) | 1 | 0 | 2 |
| POST | https://agent-keep-684642514120.europe-west1.run.app/v1/owner/bind/email | 2 (2.1053%) | 0.020000 (5.3691%) | 1 | 0 | 2 |
| GET | https://agent-keep-684642514120.europe-west1.run.app/v1/trust | 2 (2.1053%) | 0.004000 (1.0738%) | 1 | 2 | 2 |
| PUT | https://api.agentkeep.online/v1/memory/canary | 2 (2.1053%) | 0.002000 (0.5369%) | 1 | 2 | 2 |
| PUT | https://agent-keep-3jimn6j2va-ew.a.run.app/v1/memory/agentkeep | 1 (1.0526%) | 0.001000 (0.2685%) | 1 | 1 | 1 |
| POST | https://agent-keep-684642514120.europe-west1.run.app/v1/notify | 1 (1.0526%) | 0.020000 (5.3691%) | 1 | 0 | 1 |
| DELETE | https://api.agentkeep.online/v1/memory/canary | 1 (1.0526%) | 0.000500 (0.1342%) | 1 | 1 | 1 |
| PUT | https://api.agentkeep.online/v1/memory/founders-note | 1 (1.0526%) | 0.001000 (0.2685%) | 1 | 1 | 1 |
| PUT | https://api.agentkeep.online/v1/memory/launch-notes | 1 (1.0526%) | 0.001000 (0.2685%) | 1 | 1 | 1 |
| PUT | https://api.agentkeep.online/v1/memory/meditation-file | 1 (1.0526%) | 0.001000 (0.2685%) | 1 | 1 | 1 |
| PUT | https://api.agentkeep.online/v1/memory/personal-photo | 1 (1.0526%) | 0.001000 (0.2685%) | 1 | 1 | 1 |
| PUT | https://api.agentkeep.online/v1/memory/rehearsal:grant-notes:192229 | 1 (1.0526%) | 0.001000 (0.2685%) | 1 | 1 | 1 |
| PUT | https://api.agentkeep.online/v1/memory/rehearsal:launch-film:214118 | 1 (1.0526%) | 0.001000 (0.2685%) | 1 | 1 | 1 |
| PUT | https://api.agentkeep.online/v1/memory/task:grant:notes | 1 (1.0526%) | 0.001000 (0.2685%) | 1 | 1 | 1 |
| PUT | https://api.agentkeep.online/v1/memory/test-note | 1 (1.0526%) | 0.001000 (0.2685%) | 1 | 1 | 1 |

Top 27 of 27 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: agent-keep-3jimn6j2va-ew.a.run.app, agent-keep-684642514120.europe-west1.run.app, agentkeep.online, api.agentkeep.online.

Custom-domain candidates: agentkeep.online, api.agentkeep.online. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| agent-keep-3jimn6j2va-ew.a.run.app | hosting_provider_domain | not established | not recorded | 1 |
| agent-keep-684642514120.europe-west1.run.app | hosting_provider_domain | yes, cached | not recorded | 4 |
| agentkeep.online | custom_domain_candidate | yes, cached | 2026-09-30T17:29:07.279000+00:00 | 3 |
| api.agentkeep.online | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 4 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| agent-keep-3jimn6j2va-ew.a.run.app | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |
| agent-keep-684642514120.europe-west1.run.app | AgentKeep — agent OS primitives, paid per request (x402 / Algorand USDC) | AgentKeep | Wallet-scoped OS primitives for AI agents — memory, fetch, budget receipts, trust, and owner-bound notify. No signup, no API keys. Pay per call with x402 (USDC on Algorand Mainnet via GoPlausible). | not recorded | not recorded | #0B1F1A |
| agentkeep.online | AgentKeep — Keep going. | AgentKeep | OS primitives for wallet agents: memory, files, human approval, receipts. Pay USDC per call on Algorand. | https://agentkeep.online/brand/logo.png | https://agentkeep.online/brand/logo.png | not recorded |
| api.agentkeep.online | AgentKeep API — wallet memory, fetch, receipts, and notify (x402) | AgentKeep | HTTP API for AI agents. Pay per request with USDC on Algorand Mainnet through the GoPlausible x402 facilitator. No signup and no API keys. Product site: agentkeep.online. | not recorded | not recorded | #0B1F1A |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| agent-keep-3jimn6j2va-ew.a.run.app | x402 Discovery | not recorded | https://agent-keep-3jimn6j2va-ew.a.run.app/.well-known/x402 | not recorded |
| agent-keep-684642514120.europe-west1.run.app | A2A Agent Card | AgentKeep | https://agent-keep-684642514120.europe-west1.run.app/.well-known/agent-card.json | Wallet-scoped OS primitives for AI agents — memory, fetch, budget receipts, trust, and owner-bound notify. No signup, no API keys. Pay per call with x402 (USDC on Algorand Mainnet via GoPlausible). |
| agent-keep-684642514120.europe-west1.run.app | Agent Manifest | AgentKeep | https://agent-keep-684642514120.europe-west1.run.app/.well-known/agent.json | Wallet-scoped OS primitives for AI agents — memory, fetch, budget receipts, trust, and owner-bound notify. No signup, no API keys. Pay per call with x402 (USDC on Algorand Mainnet via GoPlausible). |
| agent-keep-684642514120.europe-west1.run.app | x402 Discovery | AgentKeep | https://agent-keep-684642514120.europe-west1.run.app/.well-known/x402 | Wallet-scoped agent OS primitives over x402: memory, fetch, budget receipts, trust probes, and owner-bound notify. No signup — pay per call in USDC on Algorand Mainnet via GoPlausible. Challenge tag: x402-global-challenge. |
| agent-keep-684642514120.europe-west1.run.app | llms.txt | AgentKeep | https://agent-keep-684642514120.europe-west1.run.app/llms.txt | not recorded |
| agentkeep.online | Agent Manifest | AgentKeep | https://agentkeep.online/.well-known/agent.json | Wallet-scoped memory, fetch, receipts, trust, and human approval for AI agents. Pay per call with x402 USDC on Algorand Mainnet. No signup and no API key. |
| agentkeep.online | AI Plugin | AgentKeep | https://agentkeep.online/.well-known/ai-plugin.json | Wallet memory, URL fetch, receipts, and human approval. Pay per call with USDC on Algorand. |
| agentkeep.online | llms.txt | AgentKeep | https://agentkeep.online/llms.txt | not recorded |
| api.agentkeep.online | A2A Agent Card | AgentKeep | https://api.agentkeep.online/.well-known/agent-card.json | Wallet-scoped OS primitives for AI agents — memory, fetch, budget receipts, trust, and owner-bound notify. No signup, no API keys. Pay per call with x402 (USDC on Algorand Mainnet via GoPlausible). |
| api.agentkeep.online | Agent Manifest | AgentKeep | https://api.agentkeep.online/.well-known/agent.json | Wallet-scoped OS primitives for AI agents — memory, fetch, budget receipts, trust, and owner-bound notify. No signup, no API keys. Pay per call with x402 (USDC on Algorand Mainnet via GoPlausible). |
| api.agentkeep.online | x402 Discovery | AgentKeep | https://api.agentkeep.online/.well-known/x402 | Wallet-scoped agent OS primitives over x402: memory, fetch, budget receipts, trust probes, and owner-bound notify. No signup — pay per call in USDC on Algorand Mainnet via GoPlausible. Challenge tag: x402-global-challenge. |
| api.agentkeep.online | llms.txt | AgentKeep | https://api.agentkeep.online/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
| Linked domain count | 4 |
| Cached domain metadata count | 4 |
| Domains with cached descriptive homepage evidence | 3 |
| Agent document count | 12 |
| Agent document types | ["agent-card", "agent-json", "ai-plugin", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 26 |
| Description count | 26 |
| Mime type count | 26 |
| Accepts count | 26 |
| Discovery count | 26 |
| Input documentation count | 26 |
| Output documentation count | 26 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-23 | 4 | 0.004000 | 1 | 4 | 4 (100.0000%) |
| 2026-09-24 | 15 | 0.100000 | 1 | 8 | 15 (100.0000%) |
| 2026-09-26 | 7 | 0.021500 | 1 | 6 | 7 (100.0000%) |
| 2026-09-27 | 12 | 0.071000 | 2 | 8 | 0 (0.0000%) |
| 2026-09-28 | 39 | 0.141000 | 3 | 33 | 26 (66.6667%) |
| 2026-09-29 | 6 | 0.011000 | 2 | 6 | 4 (66.6667%) |
| 2026-09-30 | 5 | 0.016000 | 2 | 4 | 3 (60.0000%) |
| 2026-10-01 | 2 | 0.003000 | 1 | 2 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |

Last 13 of 13 active days; all in the daily CSV.
