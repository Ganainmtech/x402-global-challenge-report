# GlianaAI — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 58).

## Identity and accounts

Merchant ID: `U1EyTlo2VFZHU0dZN01RTkVEWUsyN1dY`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | SQ2NZ6TVGSGY7MQNEDYK27WX5TEDTV6WDPVIZO77DGKHJGAYV6ZYJUKT5U |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 58 | GlianaAI | Exact submitted wallet SQ2NZ6TVGSGY7MQNEDYK27WX5TEDTV6WDPVIZO77DGKHJGAYV6ZYJUKT5U is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 43 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.605664 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 43 (100.0000%) · 0.605664 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 19 (44.1860%) · 0.053000 USDC (8.7507%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 19 (44.1860%) · 0.053000 USDC (8.7507%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-07 19:15:01 UTC / 2026-09-29 05:20:25 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/glianaai-0b1d413e81-transactions.csv.gz) · [All endpoints](../evidence/glianaai-0b1d413e81-endpoints.csv) · [Payer evidence](../evidence/glianaai-0b1d413e81-payers.csv) · [Daily metrics](../evidence/glianaai-0b1d413e81-daily.csv) · [Site and catalog data](../evidence/glianaai-0b1d413e81-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 43 (100.0000%) | 0.605664 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| YRFVBLDS6BDNYCVH77S3YIMLB5XIID77O7DYDYWHHZ5GZ3A4GFIZILNR3Y | MERCHANT-FUNDED | 43 | 0.605664 (100.0000%) | created by merchant; merchant sent 0.5 ALGO; throwaway wallet; 83% of gaps &lt; 60s |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

19 (44.1860%) settlements · 0.053000 (8.7507%) USDC. Paid by synthetic-indicated payers: 19 (44.1860%) settlements · 0.053000 (8.7507%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://api.glianalabs.com/a402/tools/embed | 4 (9.3023%) | 0.004000 (0.6604%) | 1 | 4 | 4 |
| POST | https://api.glianalabs.com/a402/claude-fable-5 | 1 (2.3256%) | 0.075264 (12.4267%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/gpt-4o-transcribe | 1 (2.3256%) | 0.032400 (5.3495%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/grok-imagine-image | 1 (2.3256%) | 0.024000 (3.9626%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/auto-og | 1 (2.3256%) | 0.030000 (4.9532%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/card | 1 (2.3256%) | 0.020000 (3.3022%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/code-image | 1 (2.3256%) | 0.020000 (3.3022%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/defi-tvl | 1 (2.3256%) | 0.010000 (1.6511%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/dex-pairs | 1 (2.3256%) | 0.010000 (1.6511%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/domain-lookup | 1 (2.3256%) | 0.002000 (0.3302%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/exchange-rate | 1 (2.3256%) | 0.002000 (0.3302%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/filing-digest | 1 (2.3256%) | 0.100000 (16.5108%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/filing-events | 1 (2.3256%) | 0.005000 (0.8255%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/filing-search | 1 (2.3256%) | 0.005000 (0.8255%) | 1 | 1 | 1 |
| (not recorded) | https://api.glianalabs.com/a402/tools/gas-price | 1 (2.3256%) | 0.010000 (1.6511%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/gas-price | 1 (2.3256%) | 0.010000 (1.6511%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/insider-trades | 1 (2.3256%) | 0.015000 (2.4766%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/institutional-holders | 1 (2.3256%) | 0.010000 (1.6511%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/market-brief | 1 (2.3256%) | 0.030000 (4.9532%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/meme | 1 (2.3256%) | 0.020000 (3.3022%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/moderate | 1 (2.3256%) | 0.001000 (0.1651%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/og-image | 1 (2.3256%) | 0.020000 (3.3022%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/ownership-changes | 1 (2.3256%) | 0.010000 (1.6511%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/planned-insider-sales | 1 (2.3256%) | 0.010000 (1.6511%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/quote-card | 1 (2.3256%) | 0.020000 (3.3022%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/rerank | 1 (2.3256%) | 0.001000 (0.1651%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/rpc | 1 (2.3256%) | 0.002000 (0.3302%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/scrape | 1 (2.3256%) | 0.005000 (0.8255%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/screenshot | 1 (2.3256%) | 0.005000 (0.8255%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/search | 1 (2.3256%) | 0.005000 (0.8255%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/stock-brief | 1 (2.3256%) | 0.012000 (1.9813%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/stock-filings | 1 (2.3256%) | 0.005000 (0.8255%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/stock-fundamentals | 1 (2.3256%) | 0.010000 (1.6511%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/swap-build | 1 (2.3256%) | 0.005000 (0.8255%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/swap-quote | 1 (2.3256%) | 0.002000 (0.3302%) | 1 | 1 | 1 |
| (not recorded) | https://api.glianalabs.com/a402/tools/token-price | 1 (2.3256%) | 0.002000 (0.3302%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/token-price | 1 (2.3256%) | 0.002000 (0.3302%) | 1 | 1 | 1 |
| POST | https://api.glianalabs.com/a402/tools/tweet-image | 1 (2.3256%) | 0.020000 (3.3022%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tools/youtube-thumbnail | 1 (2.3256%) | 0.020000 (3.3022%) | 1 | 0 | 1 |
| POST | https://api.glianalabs.com/a402/tts-1 | 1 (2.3256%) | 0.014000 (2.3115%) | 1 | 0 | 1 |

Top 40 of 40 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.glianalabs.com.

Custom-domain candidates: api.glianalabs.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.glianalabs.com | custom_domain_candidate | yes, cached | 2026-10-05T22:42:53.953000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.glianalabs.com | GlianaAI — pay-per-call AI inference across 90+ models | GlianaAI | One endpoint for 90+ generative AI models, live market data, SEC filings and identity APIs — image, video, music, speech, LLM chat, crypto and FX rates, DEX liquidity, gas, US company fundamentals and insider trades, document OCR and face matching. Pay per request in USDC on Tempo, Base, Solana, Algorand or BNB Chain with no signup, or top up a prepaid balance in rupiah. | https://ai.glianalabs.com/apple-touch-icon.png | https://ai.glianalabs.com/og.png | #fcfcfd |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| api.glianalabs.com | x402 Discovery | GlianaAI | https://api.glianalabs.com/.well-known/x402 | Pay-per-call AI models, live market data, SEC filings and identity APIs over HTTP 402. No signup and no API key: every call settles from the caller’s own wallet. |
| api.glianalabs.com | llms.txt | GlianaAI | https://api.glianalabs.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 2 |
| Agent document types | ["llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 38 |
| Description count | 38 |
| Mime type count | 38 |
| Accepts count | 38 |
| Discovery count | 38 |
| Input documentation count | 38 |
| Output documentation count | 38 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-07 | 2 | 0.012000 | 1 | 1 | 2 (100.0000%) |
| 2026-09-29 | 41 | 0.593664 | 1 | 18 | 41 (100.0000%) |

Last 2 of 2 active days; all in the daily CSV.
