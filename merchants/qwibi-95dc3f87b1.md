# QWIBI — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 27).

## Identity and accounts

Merchant ID: `V1BZN1ZTSFRMU0kyU09HS0RXN1RSRlZZ`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | WPY7VSHTLSI2SOGKDW7TRFVYRTMME77NDU62QPGOGBEG32LULHCYDEIG4I |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 27 | QWIBI | Exact submitted wallet WPY7VSHTLSI2SOGKDW7TRFVYRTMME77NDU62QPGOGBEG32LULHCYDEIG4I is a receiving account of this merchant.; Project name and submitted domain independently corroborate the selected account identity. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 16 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 4.440000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 11 (68.7500%) · 4.390000 USDC (98.8739%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 5 (31.2500%) · 0.050000 USDC (1.1261%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-30 17:47:34 UTC / 2026-10-06 00:08:52 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/qwibi-95dc3f87b1-transactions.csv.gz) · [All endpoints](../evidence/qwibi-95dc3f87b1-endpoints.csv) · [Payer evidence](../evidence/qwibi-95dc3f87b1-payers.csv) · [Daily metrics](../evidence/qwibi-95dc3f87b1-daily.csv) · [Site and catalog data](../evidence/qwibi-95dc3f87b1-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 11 (68.7500%) | 4.390000 (98.8739%) |
| NO-LINK-DETECTED | 5 (31.2500%) | 0.050000 (1.1261%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| QY3B3IA7B2QVPO6PYVCVDG6PSMUYFMZMWIBHJVTLEJW4WQKFM2K43G5BNI | MERCHANT-FUNDED | 11 | 4.390000 (98.8739%) | created by merchant; merchant sent 0.8 ALGO; merchant sent 9.00 USDC ×2 (205% of paid); throwaway wallet |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 5 | 0.050000 (1.1261%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://www.qwibi.xyz/api/x402/verify | 9 (56.2500%) | 0.090000 (2.0270%) | 2 | 0 | 4 |
| POST | https://www.qwibi.xyz/api/x402/data-clean | 1 (6.2500%) | 0.500000 (11.2613%) | 1 | 0 | 1 |
| POST | https://www.qwibi.xyz/api/x402/financial-model | 1 (6.2500%) | 0.500000 (11.2613%) | 1 | 0 | 1 |
| POST | https://www.qwibi.xyz/api/x402/forecasting | 1 (6.2500%) | 0.250000 (5.6306%) | 1 | 0 | 1 |
| POST | https://www.qwibi.xyz/api/x402/market-intelligence | 1 (6.2500%) | 0.500000 (11.2613%) | 1 | 0 | 1 |
| POST | https://www.qwibi.xyz/api/x402/report-writeup | 1 (6.2500%) | 0.100000 (2.2523%) | 1 | 0 | 1 |
| POST | https://www.qwibi.xyz/api/x402/text-to-sql-bi | 1 (6.2500%) | 0.500000 (11.2613%) | 1 | 0 | 1 |
| POST | https://www.qwibi.xyz/api/x402/wallet-statement | 1 (6.2500%) | 2.000000 (45.0450%) | 1 | 0 | 1 |

Top 8 of 8 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: www.qwibi.xyz.

Custom-domain candidates: www.qwibi.xyz. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| www.qwibi.xyz | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| www.qwibi.xyz | Qwibi | Qwibi | Verified analyst work, paid one request at a time with x402 on Algorand. | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| www.qwibi.xyz | Agent Manifest | Qwibi | https://www.qwibi.xyz/.well-known/agent.json | Pay-per-request AI analyst desk for agentic finance. Agents pay with x402 on Algorand for finished, cited, and cryptographically attested analyst deliverables. |
| www.qwibi.xyz | llms.txt | Qwibi | https://www.qwibi.xyz/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 2 |
| Agent document types | ["agent-json", "llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 8 |
| Description count | 8 |
| Mime type count | 8 |
| Accepts count | 8 |
| Discovery count | 8 |
| Input documentation count | 8 |
| Output documentation count | 8 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-30 | 1 | 0.010000 | 1 | 0 | 1 (100.0000%) |
| 2026-10-01 | 11 | 4.390000 | 2 | 0 | 10 (90.9091%) |
| 2026-10-02 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |

Last 6 of 6 active days; all in the daily CSV.
