# WhaleTape — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 90).

## Identity and accounts

Merchant ID: `SjRRN1pLVU5FN0NSV0pHVVhLWDNNWUo1`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | ZVZV3J2VQNLTH6MNLOL5IHZECJQVXVSVAK3NNJA6FD7LLNZ5NRHQAIL2J4 |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 90 | WhaleTape | Exact submitted wallet ZVZV3J2VQNLTH6MNLOL5IHZECJQVXVSVAK3NNJA6FD7LLNZ5NRHQAIL2J4 is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 120 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 5.392000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 62 (51.6667%) · 3.516000 USDC (65.2077%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 58 (48.3333%) · 1.876000 USDC (34.7923%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 32 (26.6667%) · 0.032000 USDC (0.5935%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 16 (13.3333%) · 0.016000 USDC (0.2967%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-02 17:31:33 UTC / 2026-10-06 00:04:08 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/whaletape-9e588da01e-transactions.csv.gz) · [All endpoints](../evidence/whaletape-9e588da01e-endpoints.csv) · [Payer evidence](../evidence/whaletape-9e588da01e-payers.csv) · [Daily metrics](../evidence/whaletape-9e588da01e-daily.csv) · [Site and catalog data](../evidence/whaletape-9e588da01e-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 62 (51.6667%) | 3.516000 (65.2077%) |
| NO-LINK-DETECTED | 58 (48.3333%) | 1.876000 (34.7923%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| EOSKWEY2TDFWI5W65HMSONG57RJXPRSTQ2AG5NOULB7FOTR6XVITF2NTIM | MERCHANT-FUNDED | 62 | 3.516000 (65.2077%) | created by merchant; merchant sent 52.30 ALGO; throwaway wallet; 75% of gaps &lt; 60s |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 58 | 1.876000 (34.7923%) | throwaway wallet; 67% of gaps &lt; 60s; created by vet402; pays 68 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

32 (26.6667%) settlements · 0.032000 (0.5935%) USDC. Paid by synthetic-indicated payers: 16 (13.3333%) settlements · 0.016000 (0.2967%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://whaletape.xyz/algo/coverage | 20 (16.6667%) | 0.020000 (0.3709%) | 2 | 20 | 10 |
| GET | https://whaletape.xyz/coverage | 5 (4.1667%) | 0.005000 (0.0927%) | 2 | 5 | 3 |
| GET | https://whaletape.xyz/algo/analysis | 4 (3.3333%) | 0.400000 (7.4184%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/flows | 4 (3.3333%) | 0.080000 (1.4837%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/flows/classes | 4 (3.3333%) | 0.180000 (3.3383%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/liquidations | 4 (3.3333%) | 0.080000 (1.4837%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/liquidations/BTC | 4 (3.3333%) | 0.080000 (1.4837%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/liquidations/ETH | 4 (3.3333%) | 0.080000 (1.4837%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/liquidations/HYPE | 4 (3.3333%) | 0.080000 (1.4837%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/liquidations/SOL | 4 (3.3333%) | 0.080000 (1.4837%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/markets/full | 4 (3.3333%) | 0.130000 (2.4110%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/pulse | 4 (3.3333%) | 0.080000 (1.4837%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/recommendations | 4 (3.3333%) | 0.080000 (1.4837%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/signals | 4 (3.3333%) | 0.180000 (3.3383%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/squeeze | 4 (3.3333%) | 0.130000 (2.4110%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/whales | 4 (3.3333%) | 0.080000 (1.4837%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/whales/events | 4 (3.3333%) | 0.130000 (2.4110%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/whales/positions | 4 (3.3333%) | 0.130000 (2.4110%) | 2 | 0 | 2 |
| GET | https://whaletape.xyz/algo/index/ranking | 3 (2.5000%) | 0.150000 (2.7819%) | 2 | 0 | 1 |
| GET | https://whaletape.xyz/algo/index/summary | 3 (2.5000%) | 0.070000 (1.2982%) | 2 | 0 | 1 |
| GET | https://whaletape.xyz/coverage/BTC | 3 (2.5000%) | 0.003000 (0.0556%) | 2 | 3 | 1 |
| POST | https://whaletape.xyz/algo/alerts | 2 (1.6667%) | 1.980000 (36.7211%) | 1 | 0 | 2 |
| GET | https://whaletape.xyz/algo/ask | 2 (1.6667%) | 0.500000 (9.2730%) | 1 | 0 | 2 |
| GET | https://whaletape.xyz/algo/coverage/BTC | 2 (1.6667%) | 0.002000 (0.0371%) | 1 | 2 | 0 |
| GET | https://whaletape.xyz/algo/coverage/[symbol] | 2 (1.6667%) | 0.002000 (0.0371%) | 1 | 2 | 2 |
| GET | https://whaletape.xyz/algo/history/BTC | 2 (1.6667%) | 0.100000 (1.8546%) | 1 | 0 | 0 |
| GET | https://whaletape.xyz/algo/history/[symbol] | 2 (1.6667%) | 0.020000 (0.3709%) | 1 | 0 | 2 |
| GET | https://whaletape.xyz/algo/markets/class/[asset_class] | 2 (1.6667%) | 0.020000 (0.3709%) | 1 | 0 | 2 |
| GET | https://whaletape.xyz/algo/markets/class/crypto | 2 (1.6667%) | 0.100000 (1.8546%) | 1 | 0 | 0 |
| GET | https://whaletape.xyz/algo/premium | 2 (1.6667%) | 0.240000 (4.4510%) | 1 | 0 | 2 |
| GET | https://whaletape.xyz/algo/whale/0x5b5d51203a0f9079f8aeb098a6523a13f298c060 | 2 (1.6667%) | 0.140000 (2.5964%) | 1 | 0 | 0 |
| GET | https://whaletape.xyz/algo/whale/[address] | 2 (1.6667%) | 0.040000 (0.7418%) | 1 | 0 | 2 |

Top 32 of 32 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: whaletape.xyz.

Custom-domain candidates: whaletape.xyz. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| whaletape.xyz | custom_domain_candidate | yes, cached | 2026-10-05T21:24:10.425000+00:00 | 4 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| whaletape.xyz | WhaleTape · Hyperliquid Smart Money | WhaleTape | Hyperliquid whale data, sold by the call, settled on chain. Pay with USDC on Base, Solana or Algorand. No account. | https://whaletape.xyz/favicon.ico | https://whaletape.xyz/og.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| whaletape.xyz | A2A Agent Card | Hyperliquid Smart Money Data API | https://whaletape.xyz/.well-known/agent-card.json | Pay-per-request market intelligence from Hyperliquid: whale positioning, open-interest and funding signals, squeeze radar and AI market briefs. Crypto, equities, commodities, FX and indices. |
| whaletape.xyz | Agent Manifest | Hyperliquid Smart Money Data API | https://whaletape.xyz/.well-known/agent.json | Pay-per-request market intelligence from Hyperliquid: whale positioning, open-interest and funding signals, squeeze radar and AI market briefs. Crypto, equities, commodities, FX and indices. |
| whaletape.xyz | x402 Discovery | Hyperliquid Smart Money Data API | https://whaletape.xyz/.well-known/x402 | Pay-per-request market intelligence from Hyperliquid: whale positioning, open-interest and funding signals, squeeze radar and AI market briefs. Crypto, equities, commodities, FX and indices. |
| whaletape.xyz | llms.txt | Hyperliquid Smart Money Data API (https://whaletape.xyz) | https://whaletape.xyz/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 4 |
| Agent document types | ["agent-card", "agent-json", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No catalog resources on included public domains."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 0 |
| Description count | 0 |
| Mime type count | 0 |
| Accepts count | 0 |
| Discovery count | 0 |
| Input documentation count | 0 |
| Output documentation count | 0 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02 | 29 | 1.737000 | 1 | 7 | 29 (100.0000%) |
| 2026-09-03 | 29 | 1.775000 | 1 | 5 | 29 (100.0000%) |
| 2026-09-05 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-11 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-18 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-19 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-27 | 21 | 0.373000 | 1 | 3 | 0 (0.0000%) |
| 2026-09-28 | 29 | 1.495000 | 1 | 5 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |

Last 16 of 16 active days; all in the daily CSV.
