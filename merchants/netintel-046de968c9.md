# NetIntel — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 75, 79).

## Identity and accounts

Merchant ID: `S0dJRVdFV05JWldaQjREVkdWRlc0RkFQ`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | KGIEWEWNIZWZB4DVGVFW4FAPL3DON6HT5WFHWMDH42SNAYWVPRQ7YBP6EM |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 75 | NetIntel | Exact submitted wallet KGIEWEWNIZWZB4DVGVFW4FAPL3DON6HT5WFHWMDH42SNAYWVPRQ7YBP6EM is a receiving account of this merchant. |
| 79 | NetIntel | Exact submitted wallet KGIEWEWNIZWZB4DVGVFW4FAPL3DON6HT5WFHWMDH42SNAYWVPRQ7YBP6EM is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 247 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 4.399000 | USDC settled. |
| Unique payer accounts | 3 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 247 (100.0000%) · 4.399000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 109 (44.1296%) · 0.379000 USDC (8.6156%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 70 · 3.188000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-27 04:32:38 UTC / 2026-10-06 02:16:27 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/netintel-046de968c9-transactions.csv.gz) · [All endpoints](../evidence/netintel-046de968c9-endpoints.csv) · [Payer evidence](../evidence/netintel-046de968c9-payers.csv) · [Daily metrics](../evidence/netintel-046de968c9-daily.csv) · [Site and catalog data](../evidence/netintel-046de968c9-site-and-catalog.json)

**Flag — self-payments excluded:** 70 settlements / 3.188000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 247 (100.0000%) | 4.399000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 227 | 4.123000 (93.7258%) | throwaway wallet; 89% of gaps &lt; 60s; created by vet402; pays 68 merchants |
| XALLOLSAOW5HVPCKK6NSTUTPVFWB3K6MNFKDXHMXULFYGN6GYXT4UU4UXA | NO-LINK-DETECTED | 17 | 0.273000 (6.2060%) | throwaway wallet; 63% of gaps &lt; 60s; pays 9 merchants |
| 2MSEYNHSCPWU6IJOSZI6R54P4BN2CDFMELTMD3GHIVMSF7SQZIUUF6BJLQ | NO-LINK-DETECTED | 3 | 0.003000 (0.0682%) | throwaway wallet; created by vet402; pays 3 merchants |

Top 3 of 3 payers; all in the payer CSV.

## Sub-cent settlements

109 (44.1296%) settlements · 0.379000 (8.6156%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://algo.netintel.dev/email/verify | 13 (5.2632%) | 0.013000 (0.2955%) | 2 | 13 | 0 |
| GET | https://algo.netintel.dev/exa/answer | 11 (4.4534%) | 0.110000 (2.5006%) | 2 | 0 | 0 |
| GET | https://algo.netintel.dev/web/search | 7 (2.8340%) | 0.070000 (1.5913%) | 2 | 0 | 0 |
| POST | https://algo.netintel.dev/domain/vendor-risk | 3 (1.2146%) | 0.300000 (6.8197%) | 2 | 0 | 0 |
| GET | https://algo.netintel.dev/github-intel/analyze | 3 (1.2146%) | 0.090000 (2.0459%) | 2 | 0 | 0 |
| GET | https://algo.netintel.dev/web/extract | 3 (1.2146%) | 0.009000 (0.2046%) | 2 | 3 | 0 |
| POST | https://algo.netintel.dev/api/v1/chat/completions | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/api/v1/embeddings | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/breach-check/password | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/bulk-domain/check | 2 (0.8097%) | 0.200000 (4.5465%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/calendar/ics | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/cert-transparency/lookup | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/classify | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/cloud-fingerprint/analyze | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/content-moderate | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/convert | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/crypto/market | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/crypto/ohlc | 2 (0.8097%) | 0.040000 (0.9093%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/crypto/price | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/currency-exchange/batch | 2 (0.8097%) | 0.040000 (0.9093%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/currency-exchange/history | 2 (0.8097%) | 0.040000 (0.9093%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/dns/lookup | 2 (0.8097%) | 0.004000 (0.0909%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/email-auth | 2 (0.8097%) | 0.004000 (0.0909%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/email-intel/analyze | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/email/verify | 2 (0.8097%) | 0.002000 (0.0455%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/embeddings | 2 (0.8097%) | 0.002000 (0.0455%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/exa/answer | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/exa/contents | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/exa/search | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/exa/search | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/extract/address | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/extract/contact | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/extract/invoice | 2 (0.8097%) | 0.040000 (0.9093%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/extract/resume | 2 (0.8097%) | 0.040000 (0.9093%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/extract/table | 2 (0.8097%) | 0.040000 (0.9093%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/gas/price | 2 (0.8097%) | 0.004000 (0.0909%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/holidays/check | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/iban/validate | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/iban/validate | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/ip-blacklist/check | 2 (0.8097%) | 0.100000 (2.2732%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/ip-geo/locate | 2 (0.8097%) | 0.004000 (0.0909%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/ip-reputation/analyze | 2 (0.8097%) | 0.100000 (2.2732%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/ip-risk/score | 2 (0.8097%) | 0.200000 (4.5465%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/json/repair | 2 (0.8097%) | 0.040000 (0.9093%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/jwt-inspector/decode | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/lang-detect/analyze | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/market/snapshot | 2 (0.8097%) | 0.100000 (2.2732%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/money/parse | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/name-gen/suggest | 2 (0.8097%) | 0.100000 (2.2732%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/npm-intel/analyze | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/og-scraper/extract | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/openai/gpt-4-1 | 2 (0.8097%) | 0.180000 (4.0918%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/openai/gpt-4-1-mini | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/openai/gpt-4-1-nano | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/openai/gpt-4o | 2 (0.8097%) | 0.200000 (4.5465%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/openai/gpt-4o-mini | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/openai/gpt-5-4-mini | 2 (0.8097%) | 0.080000 (1.8186%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/openai/gpt-5-4-nano | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/openai/gpt-5-6-luna | 2 (0.8097%) | 0.120000 (2.7279%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/openai/gpt-5-nano | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/page-extract/read | 2 (0.8097%) | 0.100000 (2.2732%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/phone-intel/analyze | 2 (0.8097%) | 0.100000 (2.2732%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/prediction/market | 2 (0.8097%) | 0.006000 (0.1364%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/prediction/market | 2 (0.8097%) | 0.006000 (0.1364%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/prediction/markets | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/prediction/markets | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/redirect/trace | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/robots-txt/analyze | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/rss-parser/fetch | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/schema/map | 2 (0.8097%) | 0.080000 (1.8186%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/schema/validate | 2 (0.8097%) | 0.040000 (0.9093%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/security-headers/analyze | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/semantic/rank | 2 (0.8097%) | 0.040000 (0.9093%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/sitemap-parser/fetch | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/ssl/analyze | 2 (0.8097%) | 0.014000 (0.3183%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/ssl/cert | 2 (0.8097%) | 0.006000 (0.1364%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/ssl/cert | 2 (0.8097%) | 0.006000 (0.1364%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/subnet/calc | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/tech-fingerprint/analyze | 2 (0.8097%) | 0.100000 (2.2732%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/text/chunk | 2 (0.8097%) | 0.002000 (0.0455%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/text/stats | 2 (0.8097%) | 0.002000 (0.0455%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/text/stats | 2 (0.8097%) | 0.002000 (0.0455%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/tld-price/compare | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/token/info | 2 (0.8097%) | 0.040000 (0.9093%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/translate/batch | 2 (0.8097%) | 0.100000 (2.2732%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/translate/long | 2 (0.8097%) | 0.040000 (0.9093%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/translate/short | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/translate/structured | 2 (0.8097%) | 0.040000 (0.9093%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/typosquat/scan | 2 (0.8097%) | 0.100000 (2.2732%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/url-safety/check | 2 (0.8097%) | 0.020000 (0.4546%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/username-check/lookup | 2 (0.8097%) | 0.060000 (1.3639%) | 1 | 0 | 0 |
| POST | https://algo.netintel.dev/v1/chat/completions | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/v1/embeddings | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/wallet/balance | 2 (0.8097%) | 0.010000 (0.2273%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/wallet/intel | 2 (0.8097%) | 0.100000 (2.2732%) | 1 | 0 | 0 |
| GET | https://algo.netintel.dev/weather/current | 2 (0.8097%) | 0.004000 (0.0909%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/weather/current | 2 (0.8097%) | 0.004000 (0.0909%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/weather/forecast | 2 (0.8097%) | 0.006000 (0.1364%) | 1 | 2 | 0 |
| POST | https://algo.netintel.dev/weather/forecast | 2 (0.8097%) | 0.006000 (0.1364%) | 1 | 2 | 0 |
| GET | https://algo.netintel.dev/web/fetch | 2 (0.8097%) | 0.006000 (0.1364%) | 1 | 2 | 0 |

Top 100 of 116 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: algo.netintel.dev.

Custom-domain candidates: algo.netintel.dev. Registered email on a matching custom domain: **netintel.dev**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| algo.netintel.dev | custom_domain_candidate | not established | 2026-10-06T03:30:55.813000+00:00 | 4 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| algo.netintel.dev | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| algo.netintel.dev | A2A Agent Card | NetIntel Algo | https://algo.netintel.dev/.well-known/agent-card.json | Pay-per-call API for AI agents settling on Algorand — 141 endpoints spanning domain & DNS intelligence, IP & network intelligence, security & threat checks, email intelligence, web scraping & page metadata, structured extraction, text understanding, chat completions & image generation, conversion & utilities, package & repo intel, and phone & identity checks. Every endpoint is paid per call over the x402 micropayment protocol: no API keys, no signup, no subscriptions. |
| algo.netintel.dev | Agent Manifest | NetIntel Algo | https://algo.netintel.dev/.well-known/agent.json | Pay-per-call API for AI agents settling on Algorand — 141 endpoints spanning domain & DNS intelligence, IP & network intelligence, security & threat checks, email intelligence, web scraping & page metadata, structured extraction, text understanding, chat completions & image generation, conversion & utilities, package & repo intel, and phone & identity checks. Every endpoint is paid per call over the x402 micropayment protocol: no API keys, no signup, no subscriptions. |
| algo.netintel.dev | AI Plugin | NetIntel Algo | https://algo.netintel.dev/.well-known/ai-plugin.json | 141 endpoints spanning domain & DNS intelligence, IP & network intelligence, security & threat checks, email intelligence, web scraping & page metadata, structured extraction, text understanding, chat completions & image generation, conversion & utilities, package & repo intel, and phone & identity checks. Pay-per-call via x402 on Algorand. |
| algo.netintel.dev | llms.txt | NetIntel Algo | https://algo.netintel.dev/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 0 |
| Agent document count | 4 |
| Agent document types | ["agent-card", "agent-json", "ai-plugin", "llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No cached descriptive homepage evidence on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 137 |
| Description count | 137 |
| Mime type count | 137 |
| Accepts count | 137 |
| Discovery count | 137 |
| Input documentation count | 137 |
| Output documentation count | 137 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-27 | 106 | 1.843000 | 2 | 51 | 0 (0.0000%) |
| 2026-09-28 | 116 | 2.275000 | 1 | 49 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 6 | 0.154000 | 2 | 2 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 10 | 0.091000 | 2 | 1 | 0 (0.0000%) |
| 2026-10-05 | 2 | 0.011000 | 2 | 1 | 0 (0.0000%) |
| 2026-10-06 | 3 | 0.021000 | 2 | 1 | 0 (0.0000%) |

Last 10 of 10 active days; all in the daily CSV.
