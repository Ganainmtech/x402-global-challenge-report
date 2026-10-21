# x402 Algorand Indexer — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `WDRPMlc3WEROWEFNUFdBVVJHR0w0VkRK`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | X4O2W7XDNXAMPWAURGGL4VDJMZTCO2EDOH7NPWBKFBKOTJQVPUYR5FRAMI |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 283 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 1.481800 | USDC settled. |
| Unique payer accounts | 4 | Distinct accounts that paid. |
| Synthetic-indicated | 16 (5.6537%) · 1.455100 USDC (98.1981%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 267 (94.3463%) · 0.026700 USDC (1.8019%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 280 (98.9399%) · 0.045200 USDC (3.0503%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 13 (4.5936%) · 0.018500 USDC (1.2485%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 81 · 0.058950 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-27 21:39:27 UTC / 2026-10-06 00:01:27 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/x402-algorand-indexer-cc83c84200-transactions.csv.gz) · [All endpoints](../evidence/x402-algorand-indexer-cc83c84200-endpoints.csv) · [Payer evidence](../evidence/x402-algorand-indexer-cc83c84200-payers.csv) · [Daily metrics](../evidence/x402-algorand-indexer-cc83c84200-daily.csv) · [Site and catalog data](../evidence/x402-algorand-indexer-cc83c84200-site-and-catalog.json)

**Flag — self-payments excluded:** 81 settlements / 0.058950 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| FLEET | 15 (5.3004%) | 0.528700 (35.6796%) |
| MERCHANT-FUNDED | 1 (0.3534%) | 0.926400 (62.5186%) |
| NO-LINK-DETECTED | 267 (94.3463%) | 0.026700 (1.8019%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| ALPHAZ3QXFFJOMSCBOCGHI5MMF5KSNGNICGTY72EKHYMJWWXNF34B4XNHI | MERCHANT-FUNDED | 1 | 0.926400 (62.5186%) | created by merchant's creator |
| JRG3CUVOFK3YJK3QDD4IOWKMHHRCWVTEMUSYKDN7U73FQO5ZYTCC7CEBRQ | FLEET | 15 | 0.528700 (35.6796%) | created 1 linked payer |
| DEV2HQ7QTFFD725CKX4IPUO63PRY3YZH6X627IYK2CRS6YEPVZUCZY443E | NO-LINK-DETECTED | 255 | 0.025500 (1.7209%) | throwaway wallet; 88% of gaps &lt; 60s |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 12 | 0.001200 (0.0810%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 4 of 4 payers; all in the payer CSV.

## Sub-cent settlements

280 (98.9399%) settlements · 0.045200 (3.0503%) USDC. Paid by synthetic-indicated payers: 13 (4.5936%) settlements · 0.018500 (1.2485%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://api.algorand-indexer.xyz/v2/transactions | 241 (85.1590%) | 0.024100 (1.6264%) | 1 | 241 | 0 |
| GET | https://api.algorand-indexer.xyz/v2/accounts/JRG3CUVOFK3YJK3QDD4IOWKMHHRCWVTEMUSYKDN7U73FQO5ZYTCC7CEBRQ | 24 (8.4806%) | 0.002400 (0.1620%) | 2 | 24 | 0 |
| GET | https://api.algorand-indexer.xyz/v2/accounts/X4O2W7XDNXAMPWAURGGL4VDJMZTCO2EDOH7NPWBKFBKOTJQVPUYR5FRAMI | 2 (0.7067%) | 0.000200 (0.0135%) | 1 | 2 | 0 |
| POST | https://algorand-indexer.xyz/api/v1/queries/results/1yrrjp3gDmY0VSfFKHi38KAMrS44vifF/unlock | 1 (0.3534%) | 0.000400 (0.0270%) | 1 | 1 | 1 |
| POST | https://algorand-indexer.xyz/api/v1/queries/results/2Ap4Drql0lRur2Z5U6VmitZPwfbXqDqH/unlock | 1 (0.3534%) | 0.000500 (0.0337%) | 1 | 1 | 1 |
| POST | https://algorand-indexer.xyz/api/v1/queries/results/3fSsIHWUfrHUpEowIyTyTj38Yxim9Jp8/unlock | 1 (0.3534%) | 0.000400 (0.0270%) | 1 | 1 | 1 |
| POST | https://algorand-indexer.xyz/api/v1/queries/results/FHI9T81T45mwybp_ORqWcEbq6FSHX3Pb/unlock | 1 (0.3534%) | 0.000700 (0.0472%) | 1 | 1 | 1 |
| (not recorded) | https://algorand-indexer.xyz/api/v1/queries/results/LyKX6LbYc6B38TGrDYvDeSpmU-1Huks_/unlock | 1 (0.3534%) | 0.139600 (9.4210%) | 1 | 0 | 1 |
| (not recorded) | https://algorand-indexer.xyz/api/v1/queries/results/RMMFuLR897biUVsC0QL5LZOKUUftqaId/unlock | 1 (0.3534%) | 0.370600 (25.0101%) | 1 | 0 | 1 |
| POST | https://algorand-indexer.xyz/api/v1/queries/results/T6VJGzjmcE_eNsScoPyC7s0m6NNTSbhc/unlock | 1 (0.3534%) | 0.000400 (0.0270%) | 1 | 1 | 1 |
| POST | https://algorand-indexer.xyz/api/v1/queries/results/_1gIcgeKeImYWC0WhtBsb3_IF0YZ0jEp/unlock | 1 (0.3534%) | 0.000400 (0.0270%) | 1 | 1 | 1 |
| (not recorded) | https://algorand-indexer.xyz/api/v1/queries/results/bXc_pje3PvxWL-uQO_cVe1KqyqG8KSCa/unlock | 1 (0.3534%) | 0.000400 (0.0270%) | 1 | 1 | 1 |
| POST | https://algorand-indexer.xyz/api/v1/queries/results/cZjh0_C61ddAVLAR50At_gueIpqvMsTt/unlock | 1 (0.3534%) | 0.000400 (0.0270%) | 1 | 1 | 1 |
| POST | https://algorand-indexer.xyz/api/v1/queries/results/kfN8aaWZUok2m_1BbFU_HHi6xrSANbgx/unlock | 1 (0.3534%) | 0.002300 (0.1552%) | 1 | 1 | 1 |
| POST | https://algorand-indexer.xyz/api/v1/queries/results/l4rdKm4xELEhMP_jE7CTDXCYRjcAWCui/unlock | 1 (0.3534%) | 0.009500 (0.6411%) | 1 | 1 | 1 |
| POST | https://algorand-indexer.xyz/api/v1/queries/results/l7Koj6X5gDZyAtQiNIylQGoyQSpsEYDS/unlock | 1 (0.3534%) | 0.000400 (0.0270%) | 1 | 1 | 1 |
| POST | https://algorand-indexer.xyz/api/v1/queries/results/pXqZ5GpQFYfvDkYoql39xtczLqfn2Gde/unlock | 1 (0.3534%) | 0.000400 (0.0270%) | 1 | 1 | 1 |
| POST | https://algorand-indexer.xyz/api/v1/queries/results/sWMsbf5JahgAf8uD6nXzlpH2lFvDHZOA/unlock | 1 (0.3534%) | 0.926400 (62.5186%) | 1 | 0 | 1 |
| (not recorded) | https://algorand-indexer.xyz/api/v1/queries/results/vxDpwiSjGGle8GM4sYkIY7St2gKrZOPJ/unlock | 1 (0.3534%) | 0.002300 (0.1552%) | 1 | 1 | 1 |

Top 19 of 19 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: algorand-indexer.xyz, api.algorand-indexer.xyz, testnet.algorand-indexer.xyz.

Custom-domain candidates: algorand-indexer.xyz, api.algorand-indexer.xyz, testnet.algorand-indexer.xyz. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| algorand-indexer.xyz | custom_domain_candidate | yes, cached | 2026-09-18T13:26:03.945000+00:00 | 5 |
| api.algorand-indexer.xyz | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 5 |
| testnet.algorand-indexer.xyz | custom_domain_candidate | yes, cached | 2026-08-30T21:44:14.409000+00:00 | 5 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| algorand-indexer.xyz | Indexer Analytics | x402 Algorand Indexer | Paid Algorand Indexer REST API implemented using the x402 spec on Algorand. Endpoints are an exact match to the indexer REST API endpoints, https://dev.algorand.co/reference/rest-api/overview/ | https://algorand-indexer.xyz/favicon.svg | not recorded | #0b1017 |
| api.algorand-indexer.xyz | Algorand Indexer · Pay per query | Algorand Indexer | Pay-per-query Algorand Indexer for autonomous agents. Accounts, assets, transactions, and blocks on MainNet — USDC micropayments via x402. | https://api.algorand-indexer.xyz/favicon.ico | https://api.algorand-indexer.xyz/og.png | #0b1017 |
| testnet.algorand-indexer.xyz | Algorand Indexer x402 (TestNet) | Algorand Indexer x402 (TestNet) | Pay-per-query Algorand Indexer for autonomous agents. Accounts, assets, transactions, and blocks on TestNet — USDC micropayments via x402. | https://testnet.algorand-indexer.xyz/favicon.ico | https://testnet.algorand-indexer.xyz/og.png | #0b1017 |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| algorand-indexer.xyz | A2A Agent Card | algorand-indexer-x402 | https://algorand-indexer.xyz/.well-known/agent-card.json | Paid Algorand Indexer REST API implemented using the x402 spec on Algorand. Endpoints are an exact match to the indexer REST API endpoints, https://dev.algorand.co/reference/rest-api/overview/ Paid requests settle in USDC on Algorand through the GoPlausible facilitator; no API keys or server-side wallets. |
| algorand-indexer.xyz | Agent Manifest | algorand-indexer-x402 | https://algorand-indexer.xyz/.well-known/agent.json | Paid Algorand Indexer REST API implemented using the x402 spec on Algorand. Endpoints are an exact match to the indexer REST API endpoints, https://dev.algorand.co/reference/rest-api/overview/ Paid requests settle in USDC on Algorand through the GoPlausible facilitator; no API keys or server-side wallets. |
| algorand-indexer.xyz | AI Plugin | x402 Algorand Indexer | https://algorand-indexer.xyz/.well-known/ai-plugin.json | Paid Algorand Indexer REST API implemented using the x402 spec on Algorand. Endpoints are an exact match to the indexer REST API endpoints, https://dev.algorand.co/reference/rest-api/overview/ |
| algorand-indexer.xyz | x402 Discovery | x402 Algorand Indexer | https://algorand-indexer.xyz/.well-known/x402 | Paid Algorand Indexer REST API implemented using the x402 spec on Algorand. Endpoints are an exact match to the indexer REST API endpoints, https://dev.algorand.co/reference/rest-api/overview/ |
| algorand-indexer.xyz | llms.txt | x402 Algorand Indexer | https://algorand-indexer.xyz/llms.txt | not recorded |
| api.algorand-indexer.xyz | A2A Agent Card | algorand-indexer-x402 | https://api.algorand-indexer.xyz/.well-known/agent-card.json | Paid Algorand Indexer REST API implemented using the x402 spec on Algorand. Endpoints are an exact match to the indexer REST API endpoints, https://dev.algorand.co/reference/rest-api/overview/ Paid requests settle in USDC on Algorand through the GoPlausible facilitator; no API keys or server-side wallets. |
| api.algorand-indexer.xyz | Agent Manifest | algorand-indexer-x402 | https://api.algorand-indexer.xyz/.well-known/agent.json | Paid Algorand Indexer REST API implemented using the x402 spec on Algorand. Endpoints are an exact match to the indexer REST API endpoints, https://dev.algorand.co/reference/rest-api/overview/ Paid requests settle in USDC on Algorand through the GoPlausible facilitator; no API keys or server-side wallets. |
| api.algorand-indexer.xyz | AI Plugin | x402 Algorand Indexer | https://api.algorand-indexer.xyz/.well-known/ai-plugin.json | Paid Algorand Indexer REST API implemented using the x402 spec on Algorand. Endpoints are an exact match to the indexer REST API endpoints, https://dev.algorand.co/reference/rest-api/overview/ |
| api.algorand-indexer.xyz | x402 Discovery | x402 Algorand Indexer | https://api.algorand-indexer.xyz/.well-known/x402 | Paid Algorand Indexer REST API implemented using the x402 spec on Algorand. Endpoints are an exact match to the indexer REST API endpoints, https://dev.algorand.co/reference/rest-api/overview/ |
| api.algorand-indexer.xyz | llms.txt | x402 Algorand Indexer | https://api.algorand-indexer.xyz/llms.txt | not recorded |
| testnet.algorand-indexer.xyz | A2A Agent Card | algorand-indexer-x402 | https://testnet.algorand-indexer.xyz/.well-known/agent-card.json | Pay-per-query Algorand TestNet Indexer API with x402 on TestNet USDC Paid requests settle in USDC on Algorand through the GoPlausible facilitator; no API keys or server-side wallets. |
| testnet.algorand-indexer.xyz | Agent Manifest | algorand-indexer-x402 | https://testnet.algorand-indexer.xyz/.well-known/agent.json | Pay-per-query Algorand TestNet Indexer API with x402 on TestNet USDC Paid requests settle in USDC on Algorand through the GoPlausible facilitator; no API keys or server-side wallets. |
| testnet.algorand-indexer.xyz | AI Plugin | Algorand Indexer x402 (TestNet) | https://testnet.algorand-indexer.xyz/.well-known/ai-plugin.json | Pay-per-query Algorand TestNet Indexer API with x402 on TestNet USDC |
| testnet.algorand-indexer.xyz | x402 Discovery | Algorand Indexer x402 (TestNet) | https://testnet.algorand-indexer.xyz/.well-known/x402 | Pay-per-query Algorand TestNet Indexer API with x402 on TestNet USDC |
| testnet.algorand-indexer.xyz | llms.txt | Algorand Indexer x402 (TestNet) | https://testnet.algorand-indexer.xyz/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
| Linked domain count | 3 |
| Cached domain metadata count | 3 |
| Domains with cached descriptive homepage evidence | 3 |
| Agent document count | 15 |
| Agent document types | ["agent-card", "agent-json", "ai-plugin", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 16 |
| Description count | 16 |
| Mime type count | 16 |
| Accepts count | 16 |
| Discovery count | 16 |
| Input documentation count | 16 |
| Output documentation count | 16 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-27 | 2 | 0.371000 | 1 | 1 | 2 (100.0000%) |
| 2026-08-28 | 3 | 1.068300 | 2 | 1 | 3 (100.0000%) |
| 2026-08-29 | 8 | 0.001100 | 2 | 8 | 1 (12.5000%) |
| 2026-08-30 | 158 | 0.016700 | 2 | 158 | 2 (1.2658%) |
| 2026-08-31 | 92 | 0.009200 | 1 | 92 | 0 (0.0000%) |
| 2026-09-03 | 1 | 0.000400 | 1 | 1 | 1 (100.0000%) |
| 2026-09-06 | 1 | 0.000400 | 1 | 1 | 1 (100.0000%) |
| 2026-09-20 | 1 | 0.000400 | 1 | 1 | 1 (100.0000%) |
| 2026-09-21 | 1 | 0.009500 | 1 | 1 | 1 (100.0000%) |
| 2026-09-27 | 2 | 0.000200 | 1 | 2 | 0 (0.0000%) |
| 2026-09-28 | 3 | 0.000600 | 2 | 3 | 1 (33.3333%) |
| 2026-09-29 | 1 | 0.000100 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.000100 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.000100 | 1 | 1 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.000100 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 4 | 0.003300 | 2 | 4 | 3 (75.0000%) |
| 2026-10-04 | 1 | 0.000100 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.000100 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.000100 | 1 | 1 | 0 (0.0000%) |

Last 19 of 19 active days; all in the daily CSV.
