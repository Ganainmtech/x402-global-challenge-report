# AgentWork — Web evidence for agents — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `UEZIWUxWSFg3N0FOTlFWRjY3TEs2RVZZ`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | PFHYLVHX77ANNQVF67LK6EVYB34D5VDIUOWLOL5SX367M366DBLOQQAOCA |
| Algorand | UKVN5G2BYZPHMYFBW6C2574F6AZ3F2ACQLBLZJI62RPXBXHDHL62R3Q344 |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 20 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.400000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 20 (100.0000%) · 0.400000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 2 (10.0000%) · 0.010000 USDC (2.5000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 1 · 0.080000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-07 07:23:24 UTC / 2026-10-06 00:05:05 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/agentwork-web-evidence-for-agents-a1e8f391ba-transactions.csv.gz) · [All endpoints](../evidence/agentwork-web-evidence-for-agents-a1e8f391ba-endpoints.csv) · [Payer evidence](../evidence/agentwork-web-evidence-for-agents-a1e8f391ba-payers.csv) · [Daily metrics](../evidence/agentwork-web-evidence-for-agents-a1e8f391ba-daily.csv) · [Site and catalog data](../evidence/agentwork-web-evidence-for-agents-a1e8f391ba-site-and-catalog.json)

**Flag — self-payments excluded:** 1 settlements / 0.080000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 20 (100.0000%) | 0.400000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| MUJMIBSK3SJBLERZWJ7UNG64C6NXO5LD62M7CL7LKK6SKEDXC4FVPZ4VSY | NO-LINK-DETECTED | 5 | 0.250000 (62.5000%) | throwaway wallet; 50% of gaps &lt; 60s; pays 10 merchants |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 14 | 0.140000 (35.0000%) | throwaway wallet; created by vet402; pays 68 merchants |
| MUJMIBSK3SJBLERZWJ7UNG64C6NXO5LD62M7CL7LKK6SKEDXC4FVPZ4VSY | NO-LINK-DETECTED | 1 | 0.010000 (2.5000%) | throwaway wallet; pays 10 merchants |

Top 3 of 3 payers; all in the payer CSV.

## Sub-cent settlements

2 (10.0000%) settlements · 0.010000 (2.5000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://api.agentwork.run/v1/web/changes | 11 (55.0000%) | 0.105000 (26.2500%) | 2 | 1 | 0 |
| POST | https://api.agentwork.run/v1/jobs | 3 (15.0000%) | 0.240000 (60.0000%) | 1 | 0 | 0 |
| POST | https://api.agentwork.run/v1/pdf/read | 3 (15.0000%) | 0.030000 (7.5000%) | 2 | 0 | 0 |
| POST | https://api.agentwork.run/v1/web/read | 3 (15.0000%) | 0.025000 (6.2500%) | 2 | 1 | 0 |

Top 4 of 4 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.agentwork.run.

Custom-domain candidates: api.agentwork.run. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.agentwork.run | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 3 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.agentwork.run | AgentWork — Web evidence for agents | not recorded | Web reads and change checks: $0.005 on Base, $0.01 on Algorand; digital PDF-to-text $0.01. Structured JSON, hashes and x402 USDC. No API key. | https://api.agentwork.run/icon.svg | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| api.agentwork.run | A2A Agent Card | AgentWork Web Evidence | https://api.agentwork.run/.well-known/agent-card.json | Extract webpage and digital PDF text for RAG and research; detect documentation, pricing and policy changes with hashes and line differences. USDC on Base or Algorand. |
| api.agentwork.run | x402 Discovery | not recorded | https://api.agentwork.run/.well-known/x402 | not recorded |
| api.agentwork.run | llms.txt | AgentWork Web Evidence | https://api.agentwork.run/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 3 |
| Agent document types | ["agent-card", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-08-07 | 3 | 0.240000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-08 | 3 | 0.020000 | 1 | 2 | 0 (0.0000%) |
| 2026-09-27 | 3 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 3 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |

Last 12 of 12 active days; all in the daily CSV.
