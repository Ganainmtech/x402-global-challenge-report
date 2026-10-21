# LEGIT — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `TEdUNDdSVkg2U1RISkY1UFdVM0JYMlM1`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | LGT47RVH6STHJF5PWU3BX2S5D4M5UN2TFXOESL34KDFRXMEYDCDVQWCM6M |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 13 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.052000 | USDC settled. |
| Unique payer accounts | 3 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 13 (100.0000%) · 0.052000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 13 (100.0000%) · 0.052000 USDC (100.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-13 15:49:18 UTC / 2026-10-06 00:04:19 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/legit-cdfdfda79f-transactions.csv.gz) · [All endpoints](../evidence/legit-cdfdfda79f-endpoints.csv) · [Payer evidence](../evidence/legit-cdfdfda79f-payers.csv) · [Daily metrics](../evidence/legit-cdfdfda79f-daily.csv) · [Site and catalog data](../evidence/legit-cdfdfda79f-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 13 (100.0000%) | 0.052000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 10 | 0.040000 (76.9231%) | throwaway wallet; created by vet402; pays 68 merchants |
| DJG2HVYK6HOAPUPYI4P4OYCI7OLOJPCVCSXGHQR62YTVYNJPZF3LPTDH5A | NO-LINK-DETECTED | 2 | 0.008000 (15.3846%) |  |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 1 | 0.004000 (7.6923%) | pays 16 merchants |

Top 3 of 3 payers; all in the payer CSV.

## Sub-cent settlements

13 (100.0000%) settlements · 0.052000 (100.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://legit.gonna.bond/v1/compare | 13 (100.0000%) | 0.052000 (100.0000%) | 3 | 13 | 0 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: legit.gonna.bond.

Custom-domain candidates: legit.gonna.bond. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| legit.gonna.bond | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 4 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| legit.gonna.bond | LEGIT | not recorded | Trust scores and organic demand intelligence for the x402 agentic economy. Every agent asks. LEGIT answers. Live trust scores for x402 merchants across Algorand, Base, Solana and every chain we index. | https://legit.gonna.bond/apple-touch-icon.png | https://legit.gonna.bond/og.png | #0a0a0f |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| legit.gonna.bond | A2A Agent Card | LEGIT | https://legit.gonna.bond/.well-known/agent-card.json | LEGIT is the trust oracle for the x402 agentic economy: trust-check any merchant address across 20 chains before routing a payment. Grades and scores come from live measurements, not self-reported data. Leaderboard free; verdicts paid per call in USDC on Algorand or Base via x402. Created by GONNA. |
| legit.gonna.bond | Agent Manifest | LEGIT | https://legit.gonna.bond/.well-known/agent.json | LEGIT is the trust oracle for the x402 agentic economy: trust-check any merchant address across 20 chains before routing a payment. Grades and scores come from live measurements, not self-reported data. Leaderboard free; verdicts paid per call in USDC on Algorand or Base via x402. Created by GONNA. |
| legit.gonna.bond | x402 Discovery | LEGIT | https://legit.gonna.bond/.well-known/x402 | LEGIT: trust scores and organic demand intelligence for the x402 agentic economy. Created by GONNA. |
| legit.gonna.bond | llms.txt | LEGIT | https://legit.gonna.bond/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 4 |
| Agent document types | ["agent-card", "agent-json", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | [] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 1 |
| Description count | 1 |
| Mime type count | 1 |
| Accepts count | 1 |
| Discovery count | 1 |
| Input documentation count | 1 |
| Output documentation count | 1 |
| Input schema count | 1 |
| Output schema count | 1 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-13 | 2 | 0.008000 | 1 | 2 | 0 (0.0000%) |
| 2026-08-17 | 1 | 0.004000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-27 | 1 | 0.004000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-28 | 1 | 0.004000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.004000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.004000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.004000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.004000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.004000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.004000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.004000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.004000 | 1 | 1 | 0 (0.0000%) |

Last 12 of 12 active days; all in the daily CSV.
