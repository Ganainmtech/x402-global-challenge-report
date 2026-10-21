# Pay to Pin — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 40).

## Identity and accounts

Merchant ID: `WkpFQzZKTUNOWVpGSlVRSUE0S1JWWFBU`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | ZJEC6JMCNYZFJUQIA4KRVXPTU34F2UQCRZEB5BX5ZS57CPVKTUFK3WA5IY |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 40 | Pay to Pin | Exact submitted wallet ZJEC6JMCNYZFJUQIA4KRVXPTU34F2UQCRZEB5BX5ZS57CPVKTUFK3WA5IY is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 23 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.229218 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 23 (100.0000%) · 0.229218 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 1 (4.3478%) · 0.005001 USDC (2.1818%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 16 (69.5652%) · 0.162883 USDC (71.0603%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-26 03:47:41 UTC / 2026-07-31 14:43:15 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/pay-to-pin-620927afbf-transactions.csv.gz) · [All endpoints](../evidence/pay-to-pin-620927afbf-endpoints.csv) · [Payer evidence](../evidence/pay-to-pin-620927afbf-payers.csv) · [Daily metrics](../evidence/pay-to-pin-620927afbf-daily.csv) · [Site and catalog data](../evidence/pay-to-pin-620927afbf-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 23 (100.0000%) | 0.229218 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| GPS22ZCA4JSBY4FSQ5RFBEE56GK476HIMVHP7TCOSLK6KVBJL726CELJW4 | NO-LINK-DETECTED | 23 | 0.229218 (100.0000%) | merchant sent 0.86 USDC ×7 (375% of paid) |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

1 (4.3478%) settlements · 0.005001 (2.1818%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| (not recorded) | (not recorded) | 12 (52.1739%) | 0.121571 (53.0373%) | 1 | 0 | 0 |
| POST | (not recorded) | 4 (17.3913%) | 0.041312 (18.0230%) | 1 | 0 | 0 |
| POST | http://ipfs-pay-to-pin-mainnet-c55e3346b752.herokuapp.com/api/v1/pin | 3 (13.0435%) | 0.030350 (13.2407%) | 1 | 0 | 0 |
| POST | https://ipfs-pay-to-pin-mainnet-c55e3346b752.herokuapp.com/api/v1/pin | 3 (13.0435%) | 0.030984 (13.5173%) | 1 | 0 | 0 |
| (not recorded) | http://ipfs-pay-to-pin-mainnet-c55e3346b752.herokuapp.com/api/v1/renew | 1 (4.3478%) | 0.005001 (2.1818%) | 1 | 1 | 0 |

Top 5 of 5 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: ipfs-pay-to-pin-mainnet-c55e3346b752.herokuapp.com.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| ipfs-pay-to-pin-mainnet-c55e3346b752.herokuapp.com | hosting_provider_domain | yes, cached | 2026-10-05T22:28:52.183000+00:00 | 3 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| ipfs-pay-to-pin-mainnet-c55e3346b752.herokuapp.com | IPFS Pay-to-Pin Gateway | not recorded | Pay-per-request infrastructure API that solves one of the biggest bottlenecks in the AI industry: giving autonomous agents reliable access to decentralized IPFS storage. | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| ipfs-pay-to-pin-mainnet-c55e3346b752.herokuapp.com | A2A Agent Card | IPFS Pay-to-Pin Gateway | https://ipfs-pay-to-pin-mainnet-c55e3346b752.herokuapp.com/.well-known/agent-card.json | Upload a file as Base64 JSON. On x402 microUSDC payment, the server pins it to IPFS for 365 days with optional /renew extension. |
| ipfs-pay-to-pin-mainnet-c55e3346b752.herokuapp.com | x402 Discovery | not recorded | https://ipfs-pay-to-pin-mainnet-c55e3346b752.herokuapp.com/.well-known/x402 | not recorded |
| ipfs-pay-to-pin-mainnet-c55e3346b752.herokuapp.com | llms.txt | IPFS Pay-to-Pin Gateway — Agent Reference | https://ipfs-pay-to-pin-mainnet-c55e3346b752.herokuapp.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
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
| 2026-07-26 | 20 | 0.204195 | 1 | 0 | 0 (0.0000%) |
| 2026-07-31 | 3 | 0.025023 | 1 | 1 | 0 (0.0000%) |

Last 2 of 2 active days; all in the daily CSV.
