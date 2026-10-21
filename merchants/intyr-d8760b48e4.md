# Intyr — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 11).

## Identity and accounts

Merchant ID: `RVhXWVhDQVBKN0JVVktBTkdGTU5UQUxU`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | EXWYXCAPJ7BUVKANGFMNTALTCTFJNV2AYKB3ERKVVKRXOJJREGQ5NJBKUI |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 11 | Intyr | Exact submitted wallet EXWYXCAPJ7BUVKANGFMNTALTCTFJNV2AYKB3ERKVVKRXOJJREGQ5NJBKUI is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 7 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.700000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 1 (14.2857%) · 0.100000 USDC (14.2857%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 6 (85.7143%) · 0.600000 USDC (85.7143%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-30 23:00:18 UTC / 2026-10-06 00:11:26 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/intyr-d8760b48e4-transactions.csv.gz) · [All endpoints](../evidence/intyr-d8760b48e4-endpoints.csv) · [Payer evidence](../evidence/intyr-d8760b48e4-payers.csv) · [Daily metrics](../evidence/intyr-d8760b48e4-daily.csv) · [Site and catalog data](../evidence/intyr-d8760b48e4-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 1 (14.2857%) | 0.100000 (14.2857%) |
| NO-LINK-DETECTED | 6 (85.7143%) | 0.600000 (85.7143%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 6 | 0.600000 (85.7143%) | throwaway wallet; created by vet402; pays 68 merchants |
| HHHWQXWFW3S5MMYJXRCA4Y6XTMM4ESR26TYP3HHWXX27AUFUZCYEXK7OZQ | MERCHANT-FUNDED | 1 | 0.100000 (14.2857%) | created by merchant; merchant sent 0.5 ALGO; merchant sent 3.00 USDC ×1 (3000% of paid); throwaway wallet |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://intyr.name-redacted.workers.dev/v1/trips/check | 7 (100.0000%) | 0.700000 (100.0000%) | 2 | 0 | 1 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: intyr.name-redacted.workers.dev.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| intyr.name-redacted.workers.dev | hosting_provider_domain | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 4 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| intyr.name-redacted.workers.dev | Intyr | Intyr | An x402-paid API that checks, commits and recovers multi-supplier trips for AI agents, with a free public verifier. | https://intyr.name-redacted.workers.dev/apple-touch-icon.png | https://intyr.name-redacted.workers.dev/og.png | #FFFFFF |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| intyr.name-redacted.workers.dev | A2A Agent Card | Intyr | https://intyr.name-redacted.workers.dev/.well-known/agent-card.json | When an AI agent books a flight, a hotel and a transfer from different suppliers and one fails, Intyr stops or unwinds the rest inside limits set before paying, and leaves a receipt anyone can check. |
| intyr.name-redacted.workers.dev | Agent Manifest | Intyr | https://intyr.name-redacted.workers.dev/.well-known/agent.json | When an AI agent books a flight, a hotel and a transfer from different suppliers and one fails, Intyr stops or unwinds the rest inside limits set before paying, and leaves a receipt anyone can check. |
| intyr.name-redacted.workers.dev | x402 Discovery | not recorded | https://intyr.name-redacted.workers.dev/.well-known/x402 | not recorded |
| intyr.name-redacted.workers.dev | llms.txt | Intyr | https://intyr.name-redacted.workers.dev/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
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
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-09-30 | 1 | 0.100000 | 1 | 0 | 1 (100.0000%) |
| 2026-10-01 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |

Last 7 of 7 active days; all in the daily CSV.
