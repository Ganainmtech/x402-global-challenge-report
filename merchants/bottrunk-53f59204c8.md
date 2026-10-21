# BotTrunk — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 85).

## Identity and accounts

Merchant ID: `VVRXUzMzVE03SVQ3TklOSlNGV1M1S1ZH`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | UTWS33TM7IT7NINJSFWS5KVGL73G4ERJMYDKHF7KE4WDXHYO4L7V2PNMRE |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 85 | BotTrunk | Exact submitted wallet UTWS33TM7IT7NINJSFWS5KVGL73G4ERJMYDKHF7KE4WDXHYO4L7V2PNMRE is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 31 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 42.377957 | USDC settled. |
| Unique payer accounts | 4 | Distinct accounts that paid. |
| Synthetic-indicated | 15 (48.3871%) · 42.037957 USDC (99.1977%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 16 (51.6129%) · 0.340000 USDC (0.8023%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 1 (3.2258%) · 0.005000 USDC (0.0118%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 1 (3.2258%) · 0.005000 USDC (0.0118%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-11 01:43:14 UTC / 2026-10-06 00:09:53 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/bottrunk-53f59204c8-transactions.csv.gz) · [All endpoints](../evidence/bottrunk-53f59204c8-endpoints.csv) · [Payer evidence](../evidence/bottrunk-53f59204c8-payers.csv) · [Daily metrics](../evidence/bottrunk-53f59204c8-daily.csv) · [Site and catalog data](../evidence/bottrunk-53f59204c8-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 15 (48.3871%) | 42.037957 (99.1977%) |
| NO-LINK-DETECTED | 16 (51.6129%) | 0.340000 (0.8023%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| C3CNCKZLKB6BZOFU32I7YPWPLAXCGFFLTEZ76DTD7AB4KDZWN6AR6LIWOQ | MERCHANT-FUNDED | 2 | 41.572957 (98.1004%) | created by merchant; merchant sent 2.00 ALGO; throwaway wallet |
| YF5OYVBYYXNQKFXSHVW7ZPK22X4APVPWYAPE6Y3Y7PCXKMSU5LTAQYHQUM | MERCHANT-FUNDED | 11 | 0.370000 (0.8731%) | created by merchant; merchant sent 2.00 ALGO; merchant sent 2.00 USDC ×1 (541% of paid); throwaway wallet; 50% of gaps &lt; 60s |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 16 | 0.340000 (0.8023%) | throwaway wallet; created by vet402; pays 68 merchants |
| LQAWG3WUMKWTFGEFCCOET6JGPRKD2JFYPIJ6HPIRYAC6QDUJSBDVMCKPFQ | MERCHANT-FUNDED | 2 | 0.095000 (0.2242%) | created by merchant; merchant sent 169 ALGO; merchant sent 1.00 USDC ×1 (1053% of paid); throwaway wallet |

Top 4 of 4 payers; all in the payer CSV.

## Sub-cent settlements

1 (3.2258%) settlements · 0.005000 (0.0118%) USDC. Paid by synthetic-indicated payers: 1 (3.2258%) settlements · 0.005000 (0.0118%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://api.bottrunk.com/s/extract-links | 15 (48.3871%) | 0.300000 (0.7079%) | 2 | 0 | 5 |
| POST | https://api.bottrunk.com/s/scrape-markdown | 5 (16.1290%) | 0.365000 (0.8613%) | 3 | 1 | 5 |
| POST | https://api.bottrunk.com/s/url-health | 4 (12.9032%) | 0.080000 (0.1888%) | 2 | 0 | 2 |
| POST | https://api.bottrunk.com/s/domain-dns | 3 (9.6774%) | 0.090000 (0.2124%) | 2 | 0 | 1 |
| POST | https://api.bottrunk.com/s/page-metadata | 3 (9.6774%) | 0.060000 (0.1416%) | 2 | 0 | 1 |
| POST | https://api.bottrunk.com/s/deposit-bac-1000 | 1 (3.2258%) | 41.482957 (97.8881%) | 1 | 0 | 1 |

Top 6 of 6 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.bottrunk.com, bottrunk.com.

Custom-domain candidates: api.bottrunk.com, bottrunk.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.bottrunk.com | custom_domain_candidate | yes, cached | not recorded | 5 |
| bottrunk.com | custom_domain_candidate | yes, cached | 2026-10-06T05:37:53.292000+00:00 | 5 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.bottrunk.com | BotTrunk — services your agent can buy | BotTrunk | A catalog of services an AI agent can buy on its own: pay per call in USDC over x402 on Algorand. Data utilities and work done by real people. No accounts, no API keys. | https://api.bottrunk.com/apple-touch-icon.png | not recorded | not recorded |
| bottrunk.com | BotTrunk — services your agent can buy | BotTrunk | A catalog of services an AI agent can buy on its own: pay per call in USDC over x402 on Algorand. Data utilities and work done by real people. No accounts, no API keys. | https://bottrunk.com/apple-touch-icon.png | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| api.bottrunk.com | A2A Agent Card | BotTrunk | https://api.bottrunk.com/.well-known/agent-card.json | Services an AI agent can buy on its own, paid per call in USDC over x402 on Algorand. Data utilities and work done by real people. No accounts, no API keys, no subscriptions. |
| api.bottrunk.com | Agent Manifest | BotTrunk | https://api.bottrunk.com/.well-known/agent.json | Services an AI agent can buy on its own, paid per call in USDC over x402 on Algorand. Data utilities and work done by real people. No accounts, no API keys, no subscriptions. |
| api.bottrunk.com | MCP Manifest | BotTrunk MCP | https://api.bottrunk.com/.well-known/mcp.json | MCP server exposing BotTrunk's x402-paid tools. The agent pays from its own Algorand wallet. |
| api.bottrunk.com | x402 Discovery | BotTrunk | https://api.bottrunk.com/.well-known/x402 | Services an AI agent can buy on its own, paid per call in USDC over x402 on Algorand. Data utilities and work done by real people. No accounts, no API keys, no subscriptions. |
| api.bottrunk.com | llms.txt | BotTrunk | https://api.bottrunk.com/llms.txt | not recorded |
| bottrunk.com | A2A Agent Card | BotTrunk | https://bottrunk.com/.well-known/agent-card.json | Services an AI agent can buy on its own, paid per call in USDC over x402 on Algorand. Data utilities and work done by real people. No accounts, no API keys, no subscriptions. |
| bottrunk.com | Agent Manifest | BotTrunk | https://bottrunk.com/.well-known/agent.json | Services an AI agent can buy on its own, paid per call in USDC over x402 on Algorand. Data utilities and work done by real people. No accounts, no API keys, no subscriptions. |
| bottrunk.com | MCP Manifest | BotTrunk MCP | https://bottrunk.com/.well-known/mcp.json | Free, read-only MCP server for BotTrunk's catalog: what is for sale, what it costs and how to pay. To buy, run the local server (npx -y bottrunk-mcp), which pays from the agent's own Algorand wallet. |
| bottrunk.com | x402 Discovery | BotTrunk | https://bottrunk.com/.well-known/x402 | Services an AI agent can buy on its own, paid per call in USDC over x402 on Algorand. Data utilities and work done by real people. No accounts, no API keys, no subscriptions. |
| bottrunk.com | llms.txt | BotTrunk | https://bottrunk.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 10 |
| Agent document types | ["agent-card", "agent-json", "llms-txt", "mcp", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 6 |
| Description count | 6 |
| Mime type count | 6 |
| Accepts count | 6 |
| Discovery count | 6 |
| Input documentation count | 6 |
| Output documentation count | 6 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11 | 7 | 0.275000 | 2 | 1 | 7 (100.0000%) |
| 2026-09-13 | 5 | 0.170000 | 2 | 0 | 5 (100.0000%) |
| 2026-09-15 | 2 | 41.572957 | 1 | 0 | 2 (100.0000%) |
| 2026-09-26 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-27 | 4 | 0.090000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 4 | 0.090000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |

Last 14 of 14 active days; all in the daily CSV.
