# [name redacted] AI — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 2).

## Identity and accounts

Merchant ID: `SVlOUUNMWEpVUUZDUUxBUVlONFlPVVlW`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | IYNQCLXJUQFCQLAQYN4YOUYVHKIRHNIPP3HKBTEJC5666FJDZKY5AFEJUI |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 2 | [name redacted] AI | Exact submitted wallet IYNQCLXJUQFCQLAQYN4YOUYVHKIRHNIPP3HKBTEJC5666FJDZKY5AFEJUI is a receiving account of this merchant.; Project name and submitted domain independently corroborate the selected account identity. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 271 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 1.042000 | USDC settled. |
| Unique payer accounts | 6 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 271 (100.0000%) · 1.042000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 257 (94.8339%) · 0.482000 USDC (46.2572%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 1 (0.3690%) · 0.001000 USDC (0.0960%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-08 00:01:57 UTC / 2026-10-06 00:02:13 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/name-redacted-ai-b3d9d76e2f-transactions.csv.gz) · [All endpoints](../evidence/name-redacted-ai-b3d9d76e2f-endpoints.csv) · [Payer evidence](../evidence/name-redacted-ai-b3d9d76e2f-payers.csv) · [Daily metrics](../evidence/name-redacted-ai-b3d9d76e2f-daily.csv) · [Site and catalog data](../evidence/name-redacted-ai-b3d9d76e2f-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 271 (100.0000%) | 1.042000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 131 | 0.501000 (48.0806%) | throwaway wallet; 84% of gaps &lt; 60s; created by vet402; pays 68 merchants |
| 67PVQ2ABMTNV7TPTLMQYOV5D7LRFOXY6I2ORB5V4XSSF3ADZEKQKKTFHSU | NO-LINK-DETECTED | 103 | 0.433000 (41.5547%) | throwaway wallet; 89% of gaps &lt; 60s |
| MUJMIBSK3SJBLERZWJ7UNG64C6NXO5LD62M7CL7LKK6SKEDXC4FVPZ4VSY | NO-LINK-DETECTED | 34 | 0.105000 (10.0768%) | throwaway wallet; 64% of gaps &lt; 60s; pays 10 merchants |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 1 | 0.001000 (0.0960%) | pays 16 merchants |
| 2ZFD4V2OQPYJNRS25BBELH6FDH7FB7KLQ77IY5XITZKYW3AXX42K7QP45Y | NO-LINK-DETECTED | 1 | 0.001000 (0.0960%) | throwaway wallet; pays 2 merchants |
| 2MSEYNHSCPWU6IJOSZI6R54P4BN2CDFMELTMD3GHIVMSF7SQZIUUF6BJLQ | NO-LINK-DETECTED | 1 | 0.001000 (0.0960%) | throwaway wallet; created by vet402; pays 3 merchants |

Top 6 of 6 payers; all in the payer CSV.

## Sub-cent settlements

257 (94.8339%) settlements · 0.482000 (46.2572%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://algorand.name-redacted.services/base-ecosystem-news | 21 (7.7491%) | 0.021000 (2.0154%) | 3 | 21 | 0 |
| GET | https://algorand.name-redacted.services/news-recaps | 13 (4.7970%) | 0.039000 (3.7428%) | 3 | 13 | 0 |
| GET | https://algorand.name-redacted.services/fx-rates | 12 (4.4280%) | 0.012000 (1.1516%) | 4 | 12 | 0 |
| GET | https://algorand.name-redacted.services/twitter-summary | 6 (2.2140%) | 0.006000 (0.5758%) | 3 | 6 | 0 |
| GET | https://algorand.name-redacted.services/analyst-ratings | 4 (1.4760%) | 0.012000 (1.1516%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/crypto-news | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/dividend-intel | 4 (1.4760%) | 0.012000 (1.1516%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/dns-lookup | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/domain-age | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/earnings-calendar | 4 (1.4760%) | 0.012000 (1.1516%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/equity-news | 4 (1.4760%) | 0.012000 (1.1516%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/funding-rates | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/hl-transaction-history | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/hyperliquid-account | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/hyperliquid-market | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/insider-trades | 4 (1.4760%) | 0.012000 (1.1516%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/institutional-holdings | 4 (1.4760%) | 0.012000 (1.1516%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/macro-regime | 4 (1.4760%) | 0.012000 (1.1516%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/pm-markets | 4 (1.4760%) | 0.004000 (0.3839%) | 3 | 4 | 0 |
| GET | https://algorand.name-redacted.services/pm-search | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/pools-search | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/portfolio | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/supported-tokens | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/technical-signals | 4 (1.4760%) | 0.012000 (1.1516%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/token-details | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/token-fundamentals | 4 (1.4760%) | 0.012000 (1.1516%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/token-price | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/token-security | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/transaction-history | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/trending-altcoins | 4 (1.4760%) | 0.008000 (0.7678%) | 3 | 4 | 0 |
| GET | https://algorand.name-redacted.services/weather | 4 (1.4760%) | 0.007000 (0.6718%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/web-extract | 4 (1.4760%) | 0.020000 (1.9194%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/web-json-extract | 4 (1.4760%) | 0.020000 (1.9194%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/web-links | 4 (1.4760%) | 0.012000 (1.1516%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/whois-lookup | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/yield-farming-active | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/yield-farming-historical | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/yield-markets | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/yield-recommendations | 4 (1.4760%) | 0.004000 (0.3839%) | 2 | 4 | 0 |
| GET | https://algorand.name-redacted.services/8k-material-events | 3 (1.1070%) | 0.009000 (0.8637%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/chain-status | 3 (1.1070%) | 0.003000 (0.2879%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/domain-report | 3 (1.1070%) | 0.060000 (5.7582%) | 2 | 0 | 0 |
| GET | https://algorand.name-redacted.services/equity-intel | 3 (1.1070%) | 0.009000 (0.8637%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/equity-smart-money | 3 (1.1070%) | 0.018000 (1.7274%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/equity-smart-money-brief | 3 (1.1070%) | 0.300000 (28.7908%) | 2 | 0 | 0 |
| GET | https://algorand.name-redacted.services/filtered-news | 3 (1.1070%) | 0.003000 (0.2879%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/form-144-filings | 3 (1.1070%) | 0.015000 (1.4395%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/form-4-feed | 3 (1.1070%) | 0.009000 (0.8637%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/gas-oracle | 3 (1.1070%) | 0.003000 (0.2879%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/kol-sentiment | 3 (1.1070%) | 0.008000 (0.7678%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/market-risk | 3 (1.1070%) | 0.006000 (0.5758%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/pm-crypto | 3 (1.1070%) | 0.003000 (0.2879%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/pm-movers | 3 (1.1070%) | 0.006000 (0.5758%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/pools-trending | 3 (1.1070%) | 0.003000 (0.2879%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/protocol-revenue-leaders | 3 (1.1070%) | 0.003000 (0.2879%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/stablecoin-watch | 3 (1.1070%) | 0.003000 (0.2879%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/token-score | 3 (1.1070%) | 0.030000 (2.8791%) | 2 | 0 | 0 |
| GET | https://algorand.name-redacted.services/tokenized-equities | 3 (1.1070%) | 0.003000 (0.2879%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/tokenized-stock-movers | 3 (1.1070%) | 0.009000 (0.8637%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/tradfi-data | 3 (1.1070%) | 0.009000 (0.8637%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/yield-alpha | 3 (1.1070%) | 0.006000 (0.5758%) | 2 | 3 | 0 |
| GET | https://algorand.name-redacted.services/base-season | 2 (0.7380%) | 0.003000 (0.2879%) | 2 | 2 | 0 |
| GET | https://algorand.name-redacted.services/mega-report | 2 (0.7380%) | 0.100000 (9.5969%) | 2 | 0 | 0 |
| GET | https://algorand.name-redacted.services/rh-season | 2 (0.7380%) | 0.002000 (0.1919%) | 1 | 2 | 0 |
| GET | https://algorand.name-redacted.services/token-alpha | 2 (0.7380%) | 0.010000 (0.9597%) | 2 | 2 | 0 |
| (not recorded) | (not recorded) | 1 (0.3690%) | 0.001000 (0.0960%) | 1 | 1 | 0 |
| GET | https://algorand.name-redacted.services/defi-analytics | 1 (0.3690%) | 0.001000 (0.0960%) | 1 | 1 | 0 |
| GET | https://algorand.name-redacted.services/holder-analytics | 1 (0.3690%) | 0.030000 (2.8791%) | 1 | 0 | 0 |
| GET | https://algorand.name-redacted.services/token-top-holders | 1 (0.3690%) | 0.020000 (1.9194%) | 1 | 0 | 0 |
| GET | https://algorand.name-redacted.services/wallet-holdings | 1 (0.3690%) | 0.020000 (1.9194%) | 1 | 0 | 0 |

Top 70 of 70 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: algorand.name-redacted.services.

Custom-domain candidates: algorand.name-redacted.services. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| algorand.name-redacted.services | custom_domain_candidate | yes, cached | 2026-10-05T19:41:59.411000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| algorand.name-redacted.services | [name redacted] AI | not recorded | 71 read-only agent endpoints with x402 prices payable in USDC on Algorand MainNet. | https://algorand.name-redacted.services/favicon.ico | https://name-redacted.xyz/static/images/og/brand.png | #0B0E2A |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| algorand.name-redacted.services | x402 Discovery | not recorded | https://algorand.name-redacted.services/.well-known/x402 | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 1 |
| Agent document types | ["x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 69 |
| Description count | 69 |
| Mime type count | 69 |
| Accepts count | 69 |
| Discovery count | 69 |
| Input documentation count | 69 |
| Output documentation count | 69 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-08 | 33 | 0.100000 | 2 | 32 | 0 (0.0000%) |
| 2026-08-09 | 29 | 0.090000 | 2 | 28 | 0 (0.0000%) |
| 2026-08-10 | 36 | 0.260000 | 2 | 31 | 0 (0.0000%) |
| 2026-08-17 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-08-25 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-05 | 39 | 0.088000 | 1 | 38 | 0 (0.0000%) |
| 2026-09-27 | 60 | 0.242000 | 1 | 57 | 0 (0.0000%) |
| 2026-09-28 | 64 | 0.252000 | 2 | 61 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |

Last 16 of 16 active days; all in the daily CSV.
