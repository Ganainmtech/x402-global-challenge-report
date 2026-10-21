# pay-to-pin.duckdns.org — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `VzVJUlhKV1BTWE5VSlZTTjJNT0VKR1RE`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | W5IRXJWPSXNUJVSN2MOEJGTDGKUGFKUDVPTR5ZQVMDG5O4KYD5M3QPG3TE |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 7 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.072456 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 7 (100.0000%) · 0.072456 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-10 00:35:38 UTC / 2026-08-14 01:30:31 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/pay-to-pin-duckdns-org-d2fd252467-transactions.csv.gz) · [All endpoints](../evidence/pay-to-pin-duckdns-org-d2fd252467-endpoints.csv) · [Payer evidence](../evidence/pay-to-pin-duckdns-org-d2fd252467-payers.csv) · [Daily metrics](../evidence/pay-to-pin-duckdns-org-d2fd252467-daily.csv) · [Site and catalog data](../evidence/pay-to-pin-duckdns-org-d2fd252467-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 7 (100.0000%) | 0.072456 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| 5ATVED6HTAKIDVGZ34YZ6XBEHAAX4CNIOLYOATV2ONAZUXIWPDGZRQHOHY | MERCHANT-FUNDED | 7 | 0.072456 (100.0000%) | merchant sent 0.069 USDC ×1 (95% of paid); 67% of gaps &lt; 60s; rekeyed → DRDYIP…25ZY |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | http://pay-to-pin.duckdns.org/api/v1/pin | 4 (57.1429%) | 0.042420 (58.5459%) | 1 | 0 | 4 |
| (not recorded) | http://pay-to-pin.duckdns.org/api/v1/pin | 3 (42.8571%) | 0.030036 (41.4541%) | 1 | 0 | 3 |

Top 2 of 2 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: pay-to-pin.duckdns.org.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| pay-to-pin.duckdns.org | hosting_provider_domain | not established | 2026-10-06T00:03:02.327000+00:00 | 3 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| pay-to-pin.duckdns.org | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| pay-to-pin.duckdns.org | A2A Agent Card | IPFS Pay-to-Pin Gateway | http://pay-to-pin.duckdns.org/.well-known/agent-card.json | Upload a file as Base64 JSON. On x402 microUSDC payment, the server pins it to IPFS for 365 days with optional /renew extension. |
| pay-to-pin.duckdns.org | x402 Discovery | not recorded | http://pay-to-pin.duckdns.org/.well-known/x402 | not recorded |
| pay-to-pin.duckdns.org | llms.txt | IPFS Pay-to-Pin Gateway — Agent Reference | http://pay-to-pin.duckdns.org/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 0 |
| Agent document count | 3 |
| Agent document types | ["agent-card", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "No cached descriptive homepage evidence on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-08-10 | 2 | 0.022396 | 1 | 0 | 2 (100.0000%) |
| 2026-08-14 | 5 | 0.050060 | 1 | 0 | 5 (100.0000%) |

Last 2 of 2 active days; all in the daily CSV.
