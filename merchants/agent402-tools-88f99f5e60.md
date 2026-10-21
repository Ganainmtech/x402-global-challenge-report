# Agent402.Tools — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 60).

## Identity and accounts

Merchant ID: `QzdJSUhHN1NQTFBaNUg3WlQ2SFczVVYy`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | C7IIHG7SPLPZ5H7ZT6HW3UV2OQMQQE6Y2HBNGZXSLRJULE42BEE2OY2XIE |
| Algorand | W4GZHN36X35LGSJTTLNZNFPGSSBLMJKFLCMZK4NBLQGUS6PYPPCDB67UOE |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 60 | Agent402.Tools | Exact submitted wallet C7IIHG7SPLPZ5H7ZT6HW3UV2OQMQQE6Y2HBNGZXSLRJULE42BEE2OY2XIE is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 7,043 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 102.867865 | USDC settled. |
| Unique payer accounts | 6 | Distinct accounts that paid. |
| Synthetic-indicated | 6,973 (99.0061%) · 101.494865 USDC (98.6653%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 70 (0.9939%) · 1.373000 USDC (1.3347%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 4,965 (70.4955%) · 11.242865 USDC (10.9294%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 4,936 (70.0838%) · 11.172865 USDC (10.8614%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 7 (0.0994%) · 0.029000 USDC (0.0282%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 1 · 0.080000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-23 02:29:55 UTC / 2026-10-06 01:50:38 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/agent402-tools-88f99f5e60-transactions.csv.gz) · [All endpoints](../evidence/agent402-tools-88f99f5e60-endpoints.csv) · [Payer evidence](../evidence/agent402-tools-88f99f5e60-payers.csv) · [Daily metrics](../evidence/agent402-tools-88f99f5e60-daily.csv) · [Site and catalog data](../evidence/agent402-tools-88f99f5e60-site-and-catalog.json)

**Flag — self-payments excluded:** 1 settlements / 0.080000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 6,973 (99.0061%) | 101.494865 (98.6653%) |
| NO-LINK-DETECTED | 70 (0.9939%) | 1.373000 (1.3347%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| ZKFACAZATPUUYUXVVVE7QWMMZTSMLGQVA4G4QKW7D2UI7FCIFE3QB2SHRE | MERCHANT-FUNDED | 6,953 | 100.934865 (98.1209%) | created by merchant; merchant sent 100 ALGO; merchant sent 143 USDC ×8 (142% of paid); 98% of gaps &lt; 60s; pays 4 merchants |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 44 | 0.620000 (0.6027%) | throwaway wallet; 70% of gaps &lt; 60s; created by vet402; pays 68 merchants |
| ZKFACAZATPUUYUXVVVE7QWMMZTSMLGQVA4G4QKW7D2UI7FCIFE3QB2SHRE | MERCHANT-FUNDED | 20 | 0.560000 (0.5444%) | created by merchant; merchant sent 100 ALGO; merchant sent 143 USDC ×8 (25536% of paid); pays 4 merchants |
| LP6QRRBRDTDSP4HF7CSPWJV4AG4QWE437OYHGW7K5Y7DETKCSK5H3HCA7Q | NO-LINK-DETECTED | 4 | 0.400000 (0.3888%) | rekeyed → JKFVZM…Z34Y; pays 3 merchants |
| MUJMIBSK3SJBLERZWJ7UNG64C6NXO5LD62M7CL7LKK6SKEDXC4FVPZ4VSY | NO-LINK-DETECTED | 14 | 0.274000 (0.2664%) | throwaway wallet; 69% of gaps &lt; 60s; pays 10 merchants |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 1 | 0.050000 (0.0486%) | throwaway wallet; created by vet402; pays 68 merchants |
| 57F2QR2RAI5LYJ2F4ZIC6AJEIINS62WGA7TLSILCAZOZHS7CLTPFU6QQVU | NO-LINK-DETECTED | 4 | 0.026000 (0.0253%) | throwaway wallet; pays 4 merchants |
| VPF2BUWTDVT7OKK4NKPIJBIBBQ5PSKYNRE4BGNTLHDJY6WDL4DAGFKWF4Q | NO-LINK-DETECTED | 3 | 0.003000 (0.0029%) | throwaway wallet; pays 4 merchants |

Top 8 of 8 payers; all in the payer CSV.

## Sub-cent settlements

4,965 (70.4955%) settlements · 11.242865 (10.9294%) USDC. Paid by synthetic-indicated payers: 4,936 (70.0838%) settlements · 11.172865 (10.8614%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://agent402.tools/api/hash | 142 (2.0162%) | 0.142000 (0.1380%) | 3 | 142 | 131 |
| POST | https://agent402.tools/api/solidity-scan | 32 (0.4544%) | 0.320000 (0.3111%) | 2 | 0 | 30 |
| POST | https://agent402.tools/api/llm-pro | 19 (0.2698%) | 1.900000 (1.8470%) | 2 | 0 | 15 |
| POST | https://agent402.tools/api/extract | 18 (0.2556%) | 0.180000 (0.1750%) | 2 | 0 | 16 |
| POST | https://agent402.tools/api/pdf | 18 (0.2556%) | 0.180000 (0.1750%) | 2 | 0 | 16 |
| POST | https://agent402.tools/api/render | 18 (0.2556%) | 0.320000 (0.3111%) | 2 | 0 | 16 |
| POST | https://agent402.tools/api/audio-convert | 17 (0.2414%) | 0.340000 (0.3305%) | 2 | 0 | 16 |
| POST | https://agent402.tools/api/audio-normalize | 17 (0.2414%) | 0.340000 (0.3305%) | 2 | 0 | 16 |
| POST | https://agent402.tools/api/code-run | 17 (0.2414%) | 0.340000 (0.3305%) | 2 | 0 | 16 |
| POST | https://agent402.tools/api/code-run-pro | 17 (0.2414%) | 0.850000 (0.8263%) | 2 | 0 | 16 |
| POST | https://agent402.tools/api/embed-large | 17 (0.2414%) | 0.170000 (0.1653%) | 2 | 0 | 16 |
| POST | https://agent402.tools/api/onchain-sql | 17 (0.2414%) | 0.340000 (0.3305%) | 2 | 0 | 16 |
| GET | https://agent402.tools/api/search | 17 (0.2414%) | 0.310000 (0.3014%) | 2 | 0 | 16 |
| GET | https://agent402.tools/api/search-images | 17 (0.2414%) | 0.340000 (0.3305%) | 2 | 0 | 16 |
| GET | https://agent402.tools/api/search-news | 17 (0.2414%) | 0.310000 (0.3014%) | 2 | 0 | 16 |
| GET | https://agent402.tools/api/search-videos | 17 (0.2414%) | 0.340000 (0.3305%) | 2 | 0 | 16 |
| POST | https://agent402.tools/api/skill/defi-protocol-scanner | 17 (0.2414%) | 0.735000 (0.7145%) | 2 | 0 | 16 |
| POST | https://agent402.tools/api/skill/fixed-income-desk | 17 (0.2414%) | 0.674000 (0.6552%) | 2 | 0 | 16 |
| POST | https://agent402.tools/api/tts | 17 (0.2414%) | 0.850000 (0.8263%) | 2 | 0 | 16 |
| GET | https://agent402.tools/api/answer | 16 (0.2272%) | 1.280000 (1.2443%) | 1 | 0 | 16 |
| GET | https://agent402.tools/api/company-financials | 16 (0.2272%) | 0.320000 (0.3111%) | 2 | 0 | 15 |
| POST | https://agent402.tools/api/image-ocr | 16 (0.2272%) | 0.160000 (0.1555%) | 1 | 0 | 16 |
| POST | https://agent402.tools/api/multi-search | 16 (0.2272%) | 1.280000 (1.2443%) | 1 | 0 | 16 |
| POST | https://agent402.tools/api/skill/earnings-deep-dive | 16 (0.2272%) | 0.756000 (0.7349%) | 2 | 0 | 15 |
| POST | https://agent402.tools/api/skill/financial-analysis | 16 (0.2272%) | 1.005000 (0.9770%) | 1 | 0 | 16 |
| POST | https://agent402.tools/api/skill/options-analytics | 16 (0.2272%) | 0.662000 (0.6435%) | 2 | 0 | 15 |
| POST | https://agent402.tools/api/skill/security-audit | 16 (0.2272%) | 1.407000 (1.3678%) | 1 | 0 | 16 |
| POST | https://agent402.tools/api/transcribe | 16 (0.2272%) | 0.480000 (0.4666%) | 1 | 0 | 16 |
| POST | https://agent402.tools/api/transcribe-pro | 16 (0.2272%) | 1.600000 (1.5554%) | 1 | 0 | 16 |
| POST | https://agent402.tools/api/tts-hd | 16 (0.2272%) | 1.600000 (1.5554%) | 1 | 0 | 16 |
| GET | https://agent402.tools/api/crypto-history | 15 (0.2130%) | 0.225000 (0.2187%) | 1 | 0 | 15 |
| GET | https://agent402.tools/api/crypto-market | 15 (0.2130%) | 0.225000 (0.2187%) | 1 | 0 | 15 |
| POST | https://agent402.tools/api/image-gen | 15 (0.2130%) | 0.450000 (0.4375%) | 1 | 0 | 15 |
| POST | https://agent402.tools/api/llm | 15 (0.2130%) | 0.150000 (0.1458%) | 1 | 0 | 15 |
| POST | https://agent402.tools/api/route/execute | 15 (0.2130%) | 0.150000 (0.1458%) | 1 | 0 | 15 |
| GET | https://agent402.tools/api/screenshot | 15 (0.2130%) | 0.192000 (0.1866%) | 2 | 3 | 14 |
| GET | https://agent402.tools/api/search-suggest | 15 (0.2130%) | 0.015000 (0.0146%) | 1 | 15 | 15 |
| POST | https://agent402.tools/api/semver | 15 (0.2130%) | 0.015000 (0.0146%) | 1 | 15 | 15 |
| POST | https://agent402.tools/api/sitemap | 15 (0.2130%) | 0.042000 (0.0408%) | 1 | 15 | 15 |
| POST | https://agent402.tools/api/skill/api-investigation | 15 (0.2130%) | 1.086000 (1.0557%) | 1 | 0 | 15 |
| POST | https://agent402.tools/api/skill/dns-network-ops | 15 (0.2130%) | 0.862000 (0.8380%) | 1 | 0 | 15 |
| POST | https://agent402.tools/api/skill/earnings-watch | 15 (0.2130%) | 1.107000 (1.0761%) | 1 | 0 | 15 |
| POST | https://agent402.tools/api/skill/inflation-check | 15 (0.2130%) | 1.127000 (1.0956%) | 1 | 0 | 15 |
| POST | https://agent402.tools/api/skill/locale-brief | 15 (0.2130%) | 0.614000 (0.5969%) | 2 | 3 | 13 |
| POST | https://agent402.tools/api/skill/schema-guard | 15 (0.2130%) | 0.614000 (0.5969%) | 2 | 3 | 13 |
| POST | https://agent402.tools/api/skill/yield-dashboard | 15 (0.2130%) | 1.088000 (1.0577%) | 1 | 0 | 15 |
| POST | https://agent402.tools/api/slugify | 15 (0.2130%) | 0.015000 (0.0146%) | 1 | 15 | 15 |
| GET | https://agent402.tools/api/x402-audit | 15 (0.2130%) | 0.150000 (0.1458%) | 1 | 0 | 15 |
| POST | https://agent402.tools/v1/chat/completions | 15 (0.2130%) | 0.300000 (0.2916%) | 2 | 0 | 14 |
| POST | https://agent402.tools/api/a2a-card-validate | 14 (0.1988%) | 0.028000 (0.0272%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/add-time | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/age | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/barcode-decode | 14 (0.1988%) | 0.038000 (0.0369%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/barcode-lookup | 14 (0.1988%) | 0.070000 (0.0680%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/base-convert | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/base32 | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/base58 | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/base64 | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/business-days | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/calc | 14 (0.1988%) | 0.026000 (0.0253%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/card-validate | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/case | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/cidr | 14 (0.1988%) | 0.026000 (0.0253%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/college-lookup | 14 (0.1988%) | 0.056000 (0.0544%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/color | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/count | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/country-info | 14 (0.1988%) | 0.026000 (0.0253%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/crc32 | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/cron-next | 14 (0.1988%) | 0.026000 (0.0253%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/csv-to-json | 14 (0.1988%) | 0.028000 (0.0272%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/csv-to-md | 14 (0.1988%) | 0.028000 (0.0272%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/date-diff | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/dedupe-lines | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/device-recalls | 14 (0.1988%) | 0.056000 (0.0544%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/dns | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/dns-lookup | 14 (0.1988%) | 0.064000 (0.0622%) | 2 | 14 | 13 |
| GET | https://agent402.tools/api/drug-adverse-events | 14 (0.1988%) | 0.050000 (0.0486%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/drug-recalls | 14 (0.1988%) | 0.056000 (0.0544%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/duration | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/earthquakes | 14 (0.1988%) | 0.040000 (0.0389%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/edgar-13f-holdings | 14 (0.1988%) | 0.310000 (0.3014%) | 2 | 2 | 13 |
| GET | https://agent402.tools/api/edgar-company-facts | 14 (0.1988%) | 0.310000 (0.3014%) | 2 | 2 | 13 |
| POST | https://agent402.tools/api/email-validate | 14 (0.1988%) | 0.026000 (0.0253%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/embed | 14 (0.1988%) | 0.067000 (0.0651%) | 2 | 14 | 13 |
| POST | https://agent402.tools/api/epoch-convert | 14 (0.1988%) | 0.014000 (0.0136%) | 2 | 14 | 13 |
| POST | https://agent402.tools/api/extract-entities | 14 (0.1988%) | 0.028000 (0.0272%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/fec-candidates | 14 (0.1988%) | 0.056000 (0.0544%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/federal-awards | 14 (0.1988%) | 0.070000 (0.0680%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/fema-disasters | 14 (0.1988%) | 0.056000 (0.0544%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/finance | 14 (0.1988%) | 0.062000 (0.0603%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/food-recalls | 14 (0.1988%) | 0.056000 (0.0544%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/fx-rate | 14 (0.1988%) | 0.040000 (0.0389%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/geo-lookup | 14 (0.1988%) | 0.042000 (0.0408%) | 1 | 14 | 14 |
| GET | https://agent402.tools/api/geocode | 14 (0.1988%) | 0.038000 (0.0369%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/hex | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/hmac | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/html-entities | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/html-to-markdown | 14 (0.1988%) | 0.026000 (0.0253%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/http-check | 14 (0.1988%) | 0.038000 (0.0369%) | 1 | 14 | 14 |
| POST | https://agent402.tools/api/iban-validate | 14 (0.1988%) | 0.014000 (0.0136%) | 1 | 14 | 14 |

Top 100 of 623 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: agent402.tools.

Custom-domain candidates: agent402.tools. Registered email on a matching custom domain: **agent402.tools**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| agent402.tools | custom_domain_candidate | yes, cached | 2026-10-05T11:21:22.355000+00:00 | 4 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| agent402.tools | Agent402: 500+ pay-per-call tools for AI agents over x402 and MPP | Agent402 | Agentic Finance for AI agents: 500+ pay-per-call tools, metered models and finished reports over x402 and MPP, or by card. No signup, no API keys. | https://agent402.tools/logo.png | https://agent402.tools/card.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| agent402.tools | A2A Agent Card | Agent402 | https://agent402.tools/.well-known/agent-card.json | Pay-per-call web tools for autonomous agents: 605 priced endpoints settled in USDC over x402 or MPP, free via proof of work, or prepaid by card. No account and no API key. The same catalog is callable over MCP at https://agent402.tools/mcp and documented at https://agent402.tools/openapi.json. |
| agent402.tools | Agent Manifest | Agent402 | https://agent402.tools/.well-known/agent.json | Pay-per-call web tools for autonomous agents: 605 priced endpoints settled in USDC over x402 or MPP, free via proof of work, or prepaid by card. No account and no API key. The same catalog is callable over MCP at https://agent402.tools/mcp and documented at https://agent402.tools/openapi.json. |
| agent402.tools | x402 Discovery | Agent402.Tools | https://agent402.tools/.well-known/x402 | not recorded |
| agent402.tools | llms.txt | Agent402.Tools | https://agent402.tools/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
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
| Resource count | 623 |
| Description count | 623 |
| Mime type count | 623 |
| Accepts count | 623 |
| Discovery count | 623 |
| Input documentation count | 623 |
| Output documentation count | 119 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-06 | 3 | 0.003000 | 1 | 3 | 3 (100.0000%) |
| 2026-09-07 | 540 | 6.081000 | 1 | 394 | 540 (100.0000%) |
| 2026-09-08 | 2 | 0.002000 | 1 | 2 | 2 (100.0000%) |
| 2026-09-09 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-10 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-11 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-12 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-13 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-14 | 554 | 4.826865 | 1 | 446 | 554 (100.0000%) |
| 2026-09-16 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-17 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-18 | 6 | 0.006000 | 1 | 6 | 6 (100.0000%) |
| 2026-09-19 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-20 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-09-21 | 200 | 2.471000 | 1 | 134 | 200 (100.0000%) |
| 2026-09-22 | 4 | 0.040000 | 1 | 0 | 4 (100.0000%) |
| 2026-09-23 | 2 | 0.020000 | 1 | 0 | 2 (100.0000%) |
| 2026-09-24 | 2 | 0.011000 | 1 | 1 | 2 (100.0000%) |
| 2026-09-25 | 2 | 0.020000 | 1 | 0 | 2 (100.0000%) |
| 2026-09-26 | 1 | 0.010000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-27 | 35 | 0.633000 | 2 | 8 | 1 (2.8571%) |
| 2026-09-28 | 112 | 3.574000 | 2 | 1 | 107 (95.5357%) |
| 2026-09-29 | 1 | 0.010000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-30 | 1 | 0.010000 | 1 | 0 | 1 (100.0000%) |
| 2026-10-01 | 2 | 0.002000 | 2 | 2 | 1 (50.0000%) |
| 2026-10-02 | 2 | 0.002000 | 2 | 2 | 1 (50.0000%) |
| 2026-10-03 | 2 | 0.002000 | 2 | 2 | 1 (50.0000%) |
| 2026-10-04 | 2 | 0.002000 | 2 | 2 | 1 (50.0000%) |
| 2026-10-05 | 158 | 3.789000 | 2 | 52 | 157 (99.3671%) |
| 2026-10-06 | 2 | 0.002000 | 2 | 2 | 1 (50.0000%) |

Last 30 of 73 active days; all in the daily CSV.
