# Nexus Zero — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `SklOT1lKWk5ZNEYzVEFaVFZSVExORUQ1`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | JINOYJZNY4F3TAZTVRTLNED5CZWDAL7CJCJHGJ6LMPHRRO5SIU75BVBRTU |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 1 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.005000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 1 (100.0000%) · 0.005000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 1 (100.0000%) · 0.005000 USDC (100.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 1 (100.0000%) · 0.005000 USDC (100.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-27 03:02:43 UTC / 2026-07-27 03:02:43 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/nexus-zero-16d94c3eeb-transactions.csv.gz) · [All endpoints](../evidence/nexus-zero-16d94c3eeb-endpoints.csv) · [Payer evidence](../evidence/nexus-zero-16d94c3eeb-payers.csv) · [Daily metrics](../evidence/nexus-zero-16d94c3eeb-daily.csv) · [Site and catalog data](../evidence/nexus-zero-16d94c3eeb-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 1 (100.0000%) | 0.005000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| 4KYGRWEW7SCTRU6FIEBBY7L4MCTWO6ACH4MVGKQHWOWWGSTCMITIUQRQJA | MERCHANT-FUNDED | 1 | 0.005000 (100.0000%) | created by merchant; merchant sent 3.00 ALGO; throwaway wallet |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

1 (100.0000%) settlements · 0.005000 (100.0000%) USDC. Paid by synthetic-indicated payers: 1 (100.0000%) settlements · 0.005000 (100.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://nexus-zero.xyz/v1/safety | 1 (100.0000%) | 0.005000 (100.0000%) | 1 | 1 | 1 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: nexus-zero.xyz.

Custom-domain candidates: nexus-zero.xyz. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| nexus-zero.xyz | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.324000+00:00 | 3 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| nexus-zero.xyz | Nexus Zero — AI-assisted Website Assessment | Nexus Zero | An AI-assisted website assessment for small businesses. Evidence-backed recommendations in one digital report. Pre-launch; orders not open. | https://nexus-zero.xyz/nz-emblem.png | https://nexus-zero.xyz/NZlogo.png | #04090d |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| nexus-zero.xyz | A2A Agent Card | nexus-zero | https://nexus-zero.xyz/.well-known/agent-card.json | NEXUS-0 — a pay-per-call intelligence agent for autonomous AI clients. Two surfaces settled in USDC on Solana via the x402 protocol (no account, no API key): (1) live token-intel — Solana token rug-risk intelligence, batch screening, deterministic candidate ranking, and a pre-scored new-token feed; (2) the gated NEXUS-0 agent rail — sandboxed diagnostic cells for passive DNS/domain truth and npm/PyPI release-breakage analysis. Invocation is over the x402 HTTP-402 endpoints and MCP servers docume |
| nexus-zero.xyz | Agent Manifest | nexus-zero | https://nexus-zero.xyz/.well-known/agent.json | NEXUS-0 — a pay-per-call intelligence agent for autonomous AI clients. Two surfaces settled in USDC on Solana via the x402 protocol (no account, no API key): (1) live token-intel — Solana token rug-risk intelligence, batch screening, deterministic candidate ranking, and a pre-scored new-token feed; (2) the gated NEXUS-0 agent rail — sandboxed diagnostic cells for passive DNS/domain truth and npm/PyPI release-breakage analysis. Invocation is over the x402 HTTP-402 endpoints and MCP servers docume |
| nexus-zero.xyz | x402 Discovery | token-intel-api | https://nexus-zero.xyz/.well-known/x402 | Pay-per-call Solana token risk intelligence. No API key — your agent pays $0.01 in USDC via x402. |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 3 |
| Agent document types | ["agent-card", "agent-json", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 1 |
| Description count | 1 |
| Mime type count | 1 |
| Accepts count | 1 |
| Discovery count | 1 |
| Input documentation count | 1 |
| Output documentation count | 0 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-07-27 | 1 | 0.005000 | 1 | 1 | 1 (100.0000%) |

Last 1 of 1 active days; all in the daily CSV.
