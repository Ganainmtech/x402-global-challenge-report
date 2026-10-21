# Coil — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `TFlJVklVU04zRkFGSUMyTlVONlVZVTJW`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | LYIVIUSN3FAFIC2NUN6UYU2VN764U6YTCPTIX2O6EWYYU5WHAJHYMVTZM4 |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 74 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.924000 | USDC settled. |
| Unique payer accounts | 3 | Distinct accounts that paid. |
| Synthetic-indicated | 26 (35.1351%) · 0.486000 USDC (52.5974%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 48 (64.8649%) · 0.438000 USDC (47.4026%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 46 (62.1622%) · 0.164000 USDC (17.7489%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 16 (21.6216%) · 0.066000 USDC (7.1429%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-23 01:14:12 UTC / 2026-10-06 00:03:36 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/coil-fea19f4445-transactions.csv.gz) · [All endpoints](../evidence/coil-fea19f4445-endpoints.csv) · [Payer evidence](../evidence/coil-fea19f4445-payers.csv) · [Daily metrics](../evidence/coil-fea19f4445-daily.csv) · [Site and catalog data](../evidence/coil-fea19f4445-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 26 (35.1351%) | 0.486000 (52.5974%) |
| NO-LINK-DETECTED | 48 (64.8649%) | 0.438000 (47.4026%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| C42E5YJ3XUUHQWG5UAKQRAFYAYUREL5NEDT2Z3XMVKUOYFQULWLYFUHP44 | MERCHANT-FUNDED | 22 | 0.466000 (50.4329%) | merchant sent 0.62 USDC ×3 (134% of paid); throwaway wallet; 71% of gaps &lt; 60s |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 48 | 0.438000 (47.4026%) | throwaway wallet; 60% of gaps &lt; 60s; created by vet402; pays 68 merchants |
| EVX3H7N77J5LRFPK745EOZFTGITE7TRJNVJ2CJJ5P7XV4GJOAJR6AIQVMU | MERCHANT-FUNDED | 4 | 0.020000 (2.1645%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 0.05 USDC ×1 (250% of paid); throwaway wallet |

Top 3 of 3 payers; all in the payer CSV.

## Sub-cent settlements

46 (62.1622%) settlements · 0.164000 (17.7489%) USDC. Paid by synthetic-indicated payers: 16 (21.6216%) settlements · 0.066000 (7.1429%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://coil.trade/api/crypto/gate | 12 (16.2162%) | 0.012000 (1.2987%) | 2 | 12 | 2 |
| GET | https://coil.trade/api/board/regime | 7 (9.4595%) | 0.035000 (3.7879%) | 3 | 7 | 5 |
| GET | https://coil.trade/api/board/asof | 3 (4.0541%) | 0.060000 (6.4935%) | 2 | 0 | 1 |
| GET | https://coil.trade/api/board/brief | 3 (4.0541%) | 0.060000 (6.4935%) | 2 | 0 | 1 |
| GET | https://coil.trade/api/board/buylist | 3 (4.0541%) | 0.060000 (6.4935%) | 2 | 0 | 1 |
| GET | https://coil.trade/api/board/crypto | 3 (4.0541%) | 0.015000 (1.6234%) | 2 | 3 | 1 |
| GET | https://coil.trade/api/board/day | 3 (4.0541%) | 0.030000 (3.2468%) | 2 | 0 | 1 |
| GET | https://coil.trade/api/board/hold | 3 (4.0541%) | 0.015000 (1.6234%) | 2 | 3 | 1 |
| GET | https://coil.trade/api/board/indices | 3 (4.0541%) | 0.015000 (1.6234%) | 2 | 3 | 1 |
| GET | https://coil.trade/api/board/leaders | 3 (4.0541%) | 0.030000 (3.2468%) | 2 | 0 | 1 |
| GET | https://coil.trade/api/board/movers | 3 (4.0541%) | 0.015000 (1.6234%) | 2 | 3 | 1 |
| GET | https://coil.trade/api/board/name | 3 (4.0541%) | 0.015000 (1.6234%) | 2 | 3 | 1 |
| GET | https://coil.trade/api/board/rotation | 3 (4.0541%) | 0.015000 (1.6234%) | 2 | 3 | 1 |
| GET | https://coil.trade/api/board/sector | 3 (4.0541%) | 0.030000 (3.2468%) | 2 | 0 | 1 |
| GET | https://coil.trade/api/board/sectors | 3 (4.0541%) | 0.030000 (3.2468%) | 2 | 0 | 1 |
| GET | https://coil.trade/api/board/top-volume | 3 (4.0541%) | 0.060000 (6.4935%) | 2 | 0 | 1 |
| GET | https://coil.trade/api/crypto/day | 3 (4.0541%) | 0.015000 (1.6234%) | 2 | 3 | 1 |
| GET | https://coil.trade/api/crypto/night | 3 (4.0541%) | 0.003000 (0.3247%) | 2 | 3 | 1 |
| GET | https://coil.trade/api/crypto/setup | 3 (4.0541%) | 0.150000 (16.2338%) | 2 | 0 | 1 |
| GET | https://coil.trade/api/tradfi-risk | 3 (4.0541%) | 0.009000 (0.9740%) | 2 | 3 | 1 |
| GET | https://coil.trade/api/board/agent | 1 (1.3514%) | 0.250000 (27.0563%) | 1 | 0 | 1 |

Top 21 of 21 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: coil.trade.

Custom-domain candidates: coil.trade. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| coil.trade | custom_domain_candidate | yes, cached | 2026-10-05T03:23:11.973000+00:00 | 4 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| coil.trade | Coil — AI Stock Scanner & Rules-Based Trading Engine | Coil | Coil is an AI stock scanner that hash-commits every score before the market can judge it and publishes its forward-return audit even when negative — right now it does. S&P 500, Nasdaq-100 and a macro book re-scored about every 5 minutes: read the board ($12/mo) or feed it to your own AI agent over MCP ($29/mo). Agents can pay per call in USDC from $0.001. | https://coil.trade/assets/img/icon-192.png | https://coil.trade/assets/img/og-cover.png | #06070a |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| coil.trade | A2A Agent Card | Coil | https://coil.trade/.well-known/agent-card.json | Market data and trading signals for AI agents — x402/USDC from $0.001, no account, no API key, no signup. 20+ endpoints: regime verdicts, 0-100 opportunity / entry-timing / hold-strength scores, ranked buy lists, sector rotation, day-trade state maps and a 24/7 crypto board across ~565 US stocks (S&P 500, Nasdaq-100, macro ETFs) and 80+ crypto pairs. Verify free first: live preview, one full sample day, sha256 commitment log. Research, not advice. |
| coil.trade | Agent Manifest | Coil | https://coil.trade/.well-known/agent.json | Market data and trading signals for AI agents — x402/USDC from $0.001, no account, no API key, no signup. 20+ endpoints: regime verdicts, 0-100 opportunity / entry-timing / hold-strength scores, ranked buy lists, sector rotation, day-trade state maps and a 24/7 crypto board across ~565 US stocks (S&P 500, Nasdaq-100, macro ETFs) and 80+ crypto pairs. Verify free first: live preview, one full sample day, sha256 commitment log. Research, not advice. |
| coil.trade | x402 Discovery | not recorded | https://coil.trade/.well-known/x402 | not recorded |
| coil.trade | llms.txt | Coil | https://coil.trade/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
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
| Resource count | 21 |
| Description count | 21 |
| Mime type count | 21 |
| Accepts count | 21 |
| Discovery count | 21 |
| Input documentation count | 21 |
| Output documentation count | 21 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-07-23 | 4 | 0.020000 | 1 | 4 | 4 (100.0000%) |
| 2026-08-14 | 17 | 0.400000 | 1 | 8 | 17 (100.0000%) |
| 2026-08-20 | 4 | 0.061000 | 1 | 3 | 4 (100.0000%) |
| 2026-08-24 | 1 | 0.005000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-27 | 20 | 0.215000 | 1 | 11 | 0 (0.0000%) |
| 2026-09-28 | 20 | 0.215000 | 1 | 11 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |

Last 14 of 14 active days; all in the daily CSV.
