# Hashlock-Algo — Proof of Existence on Algorand — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `NE9FT1ZTS1NaR0c1UUdJUTVVVVNCQU9G`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 4OEOVSKSZGG5QGIQ5UUSBAOF3AKR5PP5YZ2K2FKP2SIGEYK3NG4CO6MN4M |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 25 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.220000 | USDC settled. |
| Unique payer accounts | 5 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 25 (100.0000%) · 0.220000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 24 (96.0000%) · 0.120000 USDC (54.5455%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 3 (12.0000%) · 0.015000 USDC (6.8182%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 5 · 0.120000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-26 22:08:03 UTC / 2026-10-06 00:05:40 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/hashlock-algo-proof-of-existence-on-algorand-00e47beccd-transactions.csv.gz) · [All endpoints](../evidence/hashlock-algo-proof-of-existence-on-algorand-00e47beccd-endpoints.csv) · [Payer evidence](../evidence/hashlock-algo-proof-of-existence-on-algorand-00e47beccd-payers.csv) · [Daily metrics](../evidence/hashlock-algo-proof-of-existence-on-algorand-00e47beccd-daily.csv) · [Site and catalog data](../evidence/hashlock-algo-proof-of-existence-on-algorand-00e47beccd-site-and-catalog.json)

**Flag — self-payments excluded:** 5 settlements / 0.120000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 25 (100.0000%) | 0.220000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 10 | 0.145000 (65.9091%) | throwaway wallet; created by vet402; pays 68 merchants |
| 6RQQABWXKGBP3LAAGDR4AXFSJNKXESGRYATSGVWJEHF2FKUEKSSJGW4KVQ | NO-LINK-DETECTED | 12 | 0.060000 (27.2727%) | throwaway wallet |
| YZOAE4K3TXFTNIZTM7BXQ6DNQCNDZH2WKGZI4JNSRRPK7SNNRQP2J6CI7M | NO-LINK-DETECTED | 1 | 0.005000 (2.2727%) |  |
| XK4YIH3GGA4YEYICOF2GSCWKC6TMJ3Q4Z5YY4NQHKUNMRRYRSAYEMUPML4 | NO-LINK-DETECTED | 1 | 0.005000 (2.2727%) |  |
| XB7OV5MBYEK4GOY3HR2QLNFTDUIFIL53D7XYXCMBT6HGMD6AH6IIYVQ5YA | NO-LINK-DETECTED | 1 | 0.005000 (2.2727%) |  |

Top 5 of 5 payers; all in the payer CSV.

## Sub-cent settlements

24 (96.0000%) settlements · 0.120000 (54.5455%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://hashlock.pronodealgo.xyz/hashlock-algo-mainnet/api/timestamp | 21 (84.0000%) | 0.105000 (47.7273%) | 2 | 21 | 0 |
| (not recorded) | (not recorded) | 3 (12.0000%) | 0.015000 (6.8182%) | 3 | 3 | 0 |
| POST | https://hashlock.pronodealgo.xyz/hashlock-algo-mainnet/api/timestamp-batch | 1 (4.0000%) | 0.100000 (45.4545%) | 1 | 0 | 0 |

Top 3 of 3 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: hashlock.pronodealgo.xyz.

Custom-domain candidates: hashlock.pronodealgo.xyz. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| hashlock.pronodealgo.xyz | custom_domain_candidate | yes, cached | 2026-10-05T17:17:02.698000+00:00 | 3 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| hashlock.pronodealgo.xyz | Hashlock-Algo — Proof of Existence on Algorand | not recorded | Timestamp any document for 0.005 USDC via the x402 protocol. Free public verification — built for humans and AI agents. | https://hashlock.pronodealgo.xyz/hashlock-algo.jpg | https://hashlock.pronodealgo.xyz/og.jpg | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| hashlock.pronodealgo.xyz | A2A Agent Card | Hashlock-Algo | https://hashlock.pronodealgo.xyz/.well-known/agent-card.json | Proof of existence on Algorand. Timestamp any document's SHA-256 hash for 0.005 USDC via the x402 protocol (Algorand USDC or Base USDC, gasless EIP-3009). Free public verification, history and stats. PDF certificate returned with every timestamp. Metadata stays private by default (GDPR-friendly); optional on-chain publication and signature-based proof of ownership. |
| hashlock.pronodealgo.xyz | x402 Discovery | Hashlock-Algo | https://hashlock.pronodealgo.xyz/.well-known/x402 | Proof of existence on Algorand. Timestamp any document's SHA-256 hash for 0.005 USDC via x402 (Algorand USDC or Base USDC). Verification is free and public forever. Full API docs: https://hashlock.pronodealgo.xyz/llms.txt — OpenAPI: https://hashlock.pronodealgo.xyz/api/openapi.json |
| hashlock.pronodealgo.xyz | llms.txt | Hashlock-Algo — Proof of Existence on Algorand | https://hashlock.pronodealgo.xyz/llms.txt | not recorded |

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
| Resource count | 2 |
| Description count | 2 |
| Mime type count | 0 |
| Accepts count | 2 |
| Discovery count | 2 |
| Input documentation count | 2 |
| Output documentation count | 2 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-26 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-08-27 | 2 | 0.010000 | 2 | 2 | 0 (0.0000%) |
| 2026-08-28 | 12 | 0.060000 | 1 | 12 | 0 (0.0000%) |
| 2026-09-28 | 2 | 0.105000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |

Last 12 of 12 active days; all in the daily CSV.
