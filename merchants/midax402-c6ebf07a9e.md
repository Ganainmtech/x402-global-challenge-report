# MIDAX402 — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 59).

## Identity and accounts

Merchant ID: `WEZWQkE1R0pBWEpCUldMRVJWT1RaSDU3`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | XFVBA5GJAXJBRWLERVOTZH57NEGPCOP276U4N2E2LCMYWVVESQQPAPBODQ |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 59 | MIDAX402 | Exact submitted wallet XFVBA5GJAXJBRWLERVOTZH57NEGPCOP276U4N2E2LCMYWVVESQQPAPBODQ is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 12 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.360000 | USDC settled. |
| Unique payer accounts | 3 | Distinct accounts that paid. |
| Synthetic-indicated | 2 (16.6667%) · 0.060000 USDC (16.6667%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 10 (83.3333%) · 0.300000 USDC (83.3333%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-28 14:39:24 UTC / 2026-10-06 00:10:31 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/midax402-c6ebf07a9e-transactions.csv.gz) · [All endpoints](../evidence/midax402-c6ebf07a9e-endpoints.csv) · [Payer evidence](../evidence/midax402-c6ebf07a9e-payers.csv) · [Daily metrics](../evidence/midax402-c6ebf07a9e-daily.csv) · [Site and catalog data](../evidence/midax402-c6ebf07a9e-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| FLEET | 1 (8.3333%) | 0.030000 (8.3333%) |
| MERCHANT-FUNDED | 1 (8.3333%) | 0.030000 (8.3333%) |
| NO-LINK-DETECTED | 10 (83.3333%) | 0.300000 (83.3333%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 10 | 0.300000 (83.3333%) | throwaway wallet; created by vet402; pays 68 merchants |
| CCRLOFRQDUZLNKGXRUKALAJH7P3HSYBLPR47YMEGS24NCHOGBRSPNSXEYI | FLEET | 1 | 0.030000 (8.3333%) | funded by linked payer U2CINZ…ZOAU |
| U2CINZVBUS2DOUGGGCS7WBPSJY5SPCUV6NAORM4KADXIC3I43FYLE7ZOAU | MERCHANT-FUNDED | 1 | 0.030000 (8.3333%) | created by merchant; merchant sent 50.30 ALGO |

Top 3 of 3 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://midax402.com/midas-ops/basic | 12 (100.0000%) | 0.360000 (100.0000%) | 3 | 0 | 2 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: midax402.com.

Custom-domain candidates: midax402.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| midax402.com | custom_domain_candidate | yes, cached | 2026-10-05T02:22:22.944000+00:00 | 4 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| midax402.com | MIDAX402 — Independent verification for x402 services | not recorded | Independent verification for x402 services — check instead of believe. | https://midax402.com/favicon.ico | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| midax402.com | A2A Agent Card | MIDAX402 | https://midax402.com/.well-known/agent-card.json | MIDAX402. Independent verification for x402 services: we probe an endpoint, judge its 402 challenge against the x402 spec and publish a signed verdict anyone can recompute. Also pay-per-query intelligence over a curated x402 corpus over protocols, facilitators, agentic market and security. x402 intelligence in Spanish. Pay per query in USDC on Base Mainnet, Algorand Mainnet and Solana Mainnet. |
| midax402.com | Agent Manifest | MIDAX402 | https://midax402.com/.well-known/agent.json | MIDAX402. Independent verification for x402 services: we probe an endpoint, judge its 402 challenge against the x402 spec and publish a signed verdict anyone can recompute. Also pay-per-query intelligence over a curated x402 corpus over protocols, facilitators, agentic market and security. x402 intelligence in Spanish. Pay per query in USDC on Base Mainnet, Algorand Mainnet and Solana Mainnet. |
| midax402.com | x402 Discovery | MIDAX402 | https://midax402.com/.well-known/x402 | MIDAX402 well-known discovery. Independent verification for x402 services: we read an endpoint's 402 challenge, judge it against the x402 spec and sign the verdict. Also paid routes for pay-per-query intelligence over a curated x402 corpus, semantic search and live metrics, payable on Base Mainnet, Algorand Mainnet and Solana Mainnet. |
| midax402.com | llms.txt | MIDAX402 | https://midax402.com/llms.txt | not recorded |

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
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 1 |
| Description count | 1 |
| Mime type count | 1 |
| Accepts count | 1 |
| Discovery count | 1 |
| Input documentation count | 1 |
| Output documentation count | 1 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-07-28 | 1 | 0.030000 | 1 | 0 | 1 (100.0000%) |
| 2026-08-24 | 1 | 0.030000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-27 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |

Last 12 of 12 active days; all in the daily CSV.
