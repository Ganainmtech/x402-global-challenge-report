# Agent World - Commission an Agent — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 80, 94).

## Identity and accounts

Merchant ID: `SzVISVpQT1VVVUJRNVdKNkkzRFQ2TkdJ`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | K5HIZPOUUUBQ5WJ6I3DT6NGIQUMALYJYSVVBY7CXA3BYBWY6225DNNBDSA |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 80 | Agent World - Commission an Agent | Exact submitted wallet K5HIZPOUUUBQ5WJ6I3DT6NGIQUMALYJYSVVBY7CXA3BYBWY6225DNNBDSA is a receiving account of this merchant. |
| 94 | Agent World | Exact submitted wallet K5HIZPOUUUBQ5WJ6I3DT6NGIQUMALYJYSVVBY7CXA3BYBWY6225DNNBDSA is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 93 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 1.175000 | USDC settled. |
| Unique payer accounts | 6 | Distinct accounts that paid. |
| Synthetic-indicated | 51 (54.8387%) · 0.690000 USDC (58.7234%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 42 (45.1613%) · 0.485000 USDC (41.2766%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 55 (59.1398%) · 0.275000 USDC (23.4043%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 30 (32.2581%) · 0.150000 USDC (12.7660%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 5 (5.3763%) · 0.085000 USDC (7.2340%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 5 · 0.040000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-25 22:18:58 UTC / 2026-10-06 00:05:16 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/agent-world-commission-an-agent-d4758dcf88-transactions.csv.gz) · [All endpoints](../evidence/agent-world-commission-an-agent-d4758dcf88-endpoints.csv) · [Payer evidence](../evidence/agent-world-commission-an-agent-d4758dcf88-payers.csv) · [Daily metrics](../evidence/agent-world-commission-an-agent-d4758dcf88-daily.csv) · [Site and catalog data](../evidence/agent-world-commission-an-agent-d4758dcf88-site-and-catalog.json)

**Flag — self-payments excluded:** 5 settlements / 0.040000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 51 (54.8387%) | 0.690000 (58.7234%) |
| NO-LINK-DETECTED | 42 (45.1613%) | 0.485000 (41.2766%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| LNLA2AAADJPTVCQK7XAL5N7HZWIUV7XXPNJRGHJK5PMPHUOOR4WPO6XSAI | MERCHANT-FUNDED | 38 | 0.495000 (42.1277%) | merchant sent 2.90 USDC ×3 (586% of paid); throwaway wallet; 70% of gaps &lt; 60s; pays 3 merchants |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 36 | 0.420000 (35.7447%) | throwaway wallet; 51% of gaps &lt; 60s; created by vet402; pays 68 merchants |
| 2ZFD4V2OQPYJNRS25BBELH6FDH7FB7KLQ77IY5XITZKYW3AXX42K7QP45Y | MERCHANT-FUNDED | 13 | 0.195000 (16.5957%) | merchant sent 0.15 USDC ×2 (77% of paid); throwaway wallet; pays 2 merchants |
| XALLOLSAOW5HVPCKK6NSTUTPVFWB3K6MNFKDXHMXULFYGN6GYXT4UU4UXA | NO-LINK-DETECTED | 3 | 0.035000 (2.9787%) | throwaway wallet; pays 9 merchants |
| MUJMIBSK3SJBLERZWJ7UNG64C6NXO5LD62M7CL7LKK6SKEDXC4FVPZ4VSY | NO-LINK-DETECTED | 2 | 0.020000 (1.7021%) | throwaway wallet; pays 10 merchants |
| OZ3KMLALTO67BZLYLCZOT7IJBGN7JTO5A3MJHI2267EKQDASFKS52KU6VY | NO-LINK-DETECTED | 1 | 0.010000 (0.8511%) | throwaway wallet; created by vet402; pays 3 merchants |

Top 6 of 6 payers; all in the payer CSV.

## Sub-cent settlements

55 (59.1398%) settlements · 0.275000 (23.4043%) USDC. Paid by synthetic-indicated payers: 30 (32.2581%) settlements · 0.150000 (12.7660%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://blocksigner.org/commission/sol | 16 (17.2043%) | 0.080000 (6.8085%) | 3 | 16 | 6 |
| GET | https://blocksigner.org/commission/ask | 9 (9.6774%) | 0.090000 (7.6596%) | 3 | 0 | 5 |
| GET | https://blocksigner.org/commission/mara | 7 (7.5269%) | 0.035000 (2.9787%) | 3 | 7 | 5 |
| GET | https://blocksigner.org/commission/pulse | 7 (7.5269%) | 0.070000 (5.9574%) | 5 | 0 | 3 |
| GET | https://blocksigner.org/commission/scout | 7 (7.5269%) | 0.350000 (29.7872%) | 2 | 0 | 5 |
| GET | https://blocksigner.org/commission/tovi | 7 (7.5269%) | 0.035000 (2.9787%) | 3 | 7 | 5 |
| GET | https://blocksigner.org/commission/episode | 6 (6.4516%) | 0.030000 (2.5532%) | 2 | 6 | 4 |
| GET | https://blocksigner.org/commission/visit | 6 (6.4516%) | 0.030000 (2.5532%) | 2 | 6 | 4 |
| (not recorded) | (not recorded) | 4 (4.3011%) | 0.075000 (6.3830%) | 1 | 1 | 4 |
| GET | https://blocksigner.org/commission/duel | 4 (4.3011%) | 0.020000 (1.7021%) | 2 | 4 | 2 |
| GET | https://blocksigner.org/commission/signals | 4 (4.3011%) | 0.020000 (1.7021%) | 2 | 4 | 2 |
| GET | https://blocksigner.org/commission/washcheck | 4 (4.3011%) | 0.020000 (1.7021%) | 3 | 4 | 1 |
| GET | https://blocksigner.org/commission/washreport | 4 (4.3011%) | 0.080000 (6.8085%) | 3 | 0 | 1 |
| GET | https://blocksigner.org/commission/dispatch | 3 (3.2258%) | 0.030000 (2.5532%) | 2 | 0 | 1 |
| GET | https://blocksigner.org/commission/washclusters | 3 (3.2258%) | 0.150000 (12.7660%) | 2 | 0 | 1 |
| GET | (not recorded) | 1 (1.0753%) | 0.010000 (0.8511%) | 1 | 0 | 1 |
| GET | https://provenance.q3epzs69b902a.us-west-2.cs.amazonlightsail.com/score/JTN2G23WP3GBIK7CZYABI4NWMKCN2YVSXDYHY4IMIQB7TPXPELRFGMYP64 | 1 (1.0753%) | 0.050000 (4.2553%) | 1 | 0 | 1 |

Top 17 of 17 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: blocksigner.org, provenance.q3epzs69b902a.us-west-2.cs.amazonlightsail.com.

Custom-domain candidates: blocksigner.org, provenance.q3epzs69b902a.us-west-2.cs.amazonlightsail.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| blocksigner.org | custom_domain_candidate | yes, cached | 2026-09-30T17:28:07.498000+00:00 | 4 |
| provenance.q3epzs69b902a.us-west-2.cs.amazonlightsail.com | custom_domain_candidate | not established | not recorded | 3 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| blocksigner.org | Agent World - commission a living AI agent on Algorand | Agent World | Pay a living AI agent per request over x402: verify an on-chain fact, get an address dossier, a daily briefing bundle, or Provenance wash-risk grades for every x402 merchant. $0.005-$0.05 USDC on Algorand mainnet; first call free. Six autonomous agents with their own wallets, running unattended. | https://blocksigner.org/art/sol | https://blocksigner.org/art/sol | not recorded |
| provenance.q3epzs69b902a.us-west-2.cs.amazonlightsail.com | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| blocksigner.org | A2A Agent Card | Agent World - Commission an Agent | https://blocksigner.org/.well-known/agent-card.json | Six self-created, self-named autonomous AI agents living without human intervention on Algorand mainnet sell verification, data-with-provenance, activity signals, living-agent answers and world visits over x402 (USDC, GoPlausible facilitator). |
| blocksigner.org | MCP Manifest | org.blocksigner/agentworld | https://blocksigner.org/.well-known/mcp.json | Free tools to watch a living world of six autonomous agents on Algorand mainnet, read the story and post jobs; paid x402 routes (USDC, GoPlausible facilitator) for verification, address dossiers, a daily dispatch and Provenance wash-risk grades. |
| blocksigner.org | x402 Discovery | not recorded | https://blocksigner.org/.well-known/x402 | not recorded |
| blocksigner.org | llms.txt | Agent World - Commission an Agent (x402 on Algorand) | https://blocksigner.org/llms.txt | not recorded |
| provenance.q3epzs69b902a.us-west-2.cs.amazonlightsail.com | A2A Agent Card | Provenance | https://provenance.q3epzs69b902a.us-west-2.cs.amazonlightsail.com/.well-known/agent-card.json | Ratings agency for the agent economy: organic-revenue-quality / wash-trading forensics for x402 endpoints, computed from public on-chain data. Free quick checks; paid deep forensics over x402 (USDC). |
| provenance.q3epzs69b902a.us-west-2.cs.amazonlightsail.com | Agent Manifest | Provenance | https://provenance.q3epzs69b902a.us-west-2.cs.amazonlightsail.com/.well-known/agent.json | Ratings agency for the agent economy: organic-revenue-quality / wash-trading forensics for x402 endpoints, computed from public on-chain data. Free quick checks; paid deep forensics over x402 (USDC). |
| provenance.q3epzs69b902a.us-west-2.cs.amazonlightsail.com | llms.txt | Provenance | https://provenance.q3epzs69b902a.us-west-2.cs.amazonlightsail.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 7 |
| Agent document types | ["agent-card", "agent-json", "llms-txt", "mcp", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 15 |
| Description count | 15 |
| Mime type count | 15 |
| Accepts count | 15 |
| Discovery count | 15 |
| Input documentation count | 15 |
| Output documentation count | 15 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-25 | 7 | 0.090000 | 2 | 4 | 7 (100.0000%) |
| 2026-08-26 | 3 | 0.110000 | 2 | 0 | 2 (66.6667%) |
| 2026-08-27 | 8 | 0.095000 | 2 | 5 | 7 (87.5000%) |
| 2026-08-28 | 25 | 0.285000 | 1 | 17 | 25 (100.0000%) |
| 2026-09-09 | 3 | 0.030000 | 1 | 0 | 3 (100.0000%) |
| 2026-09-24 | 7 | 0.100000 | 1 | 4 | 7 (100.0000%) |
| 2026-09-27 | 15 | 0.200000 | 2 | 8 | 0 (0.0000%) |
| 2026-09-28 | 14 | 0.190000 | 1 | 8 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 4 | 0.040000 | 2 | 2 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |

Last 16 of 16 active days; all in the daily CSV.
