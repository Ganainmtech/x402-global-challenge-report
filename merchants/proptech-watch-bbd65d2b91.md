# proptech.watch — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `T0NGVU9FNDRLVjZPUTQzWFdMREtOUkJQ`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | OCFUOE44KV6OQ43XWLDKNRBPSMIMPB6QETX3JXU5J36VKUK6ON5G4FSEMM |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 71 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.700000 | USDC settled. |
| Unique payer accounts | 4 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 71 (100.0000%) · 0.700000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 2 (2.8169%) · 0.010000 USDC (1.4286%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-22 14:16:39 UTC / 2026-10-06 00:06:35 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/proptech-watch-bbd65d2b91-transactions.csv.gz) · [All endpoints](../evidence/proptech-watch-bbd65d2b91-endpoints.csv) · [Payer evidence](../evidence/proptech-watch-bbd65d2b91-payers.csv) · [Daily metrics](../evidence/proptech-watch-bbd65d2b91-daily.csv) · [Site and catalog data](../evidence/proptech-watch-bbd65d2b91-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 71 (100.0000%) | 0.700000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| UJ6N6ZWLS4MH5324C5J6TAWRXXXVJNS7HVURGLEZ3QRV7ONGIV5ZZSUGWI | NO-LINK-DETECTED | 45 | 0.440000 (62.8571%) | 55% of gaps &lt; 60s; same funder as merchant (hub) |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 16 | 0.160000 (22.8571%) | throwaway wallet; created by vet402; pays 68 merchants |
| HJGLJBUHZ2HNORJK7UXYSD62NYTMJANYOUHC352OFU77JFQSUATNSNJI5A | NO-LINK-DETECTED | 8 | 0.080000 (11.4286%) |  |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 2 | 0.020000 (2.8571%) | pays 16 merchants |

Top 4 of 4 payers; all in the payer CSV.

## Sub-cent settlements

2 (2.8169%) settlements · 0.010000 (1.4286%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| (not recorded) | https://api.proptech.watch/stats | 13 (18.3099%) | 0.120000 (17.1429%) | 1 | 2 | 0 |
| GET | https://api.proptech.watch/hot-zones | 12 (16.9014%) | 0.120000 (17.1429%) | 2 | 0 | 0 |
| (not recorded) | https://api.proptech.watch/transfers | 12 (16.9014%) | 0.120000 (17.1429%) | 1 | 0 | 0 |
| (not recorded) | https://api.proptech.watch/peers | 6 (8.4507%) | 0.060000 (8.5714%) | 1 | 0 | 0 |
| GET | https://api.proptech.watch/peers | 6 (8.4507%) | 0.060000 (8.5714%) | 3 | 0 | 0 |
| GET | https://api.proptech.watch/volume-leaders | 5 (7.0423%) | 0.050000 (7.1429%) | 2 | 0 | 0 |
| (not recorded) | https://api.proptech.watch/volume-leaders | 4 (5.6338%) | 0.040000 (5.7143%) | 1 | 0 | 0 |
| (not recorded) | https://api.proptech.watch/hot-zones | 3 (4.2254%) | 0.030000 (4.2857%) | 1 | 0 | 0 |
| GET | https://api.proptech.watch/transfers | 3 (4.2254%) | 0.030000 (4.2857%) | 2 | 0 | 0 |
| (not recorded) | https://api.proptech.watch/transfers/6423232 | 3 (4.2254%) | 0.030000 (4.2857%) | 1 | 0 | 0 |
| (not recorded) | https://api.proptech.watch/transfers/6416228 | 1 (1.4085%) | 0.010000 (1.4286%) | 1 | 0 | 0 |
| (not recorded) | https://api.proptech.watch/transfers/6423270 | 1 (1.4085%) | 0.010000 (1.4286%) | 1 | 0 | 0 |
| (not recorded) | https://api.proptech.watch/transfers/6423465 | 1 (1.4085%) | 0.010000 (1.4286%) | 1 | 0 | 0 |
| (not recorded) | https://api.proptech.watch/transfers/6423538 | 1 (1.4085%) | 0.010000 (1.4286%) | 1 | 0 | 0 |

Top 14 of 14 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.proptech.watch, proptech.watch.

Custom-domain candidates: api.proptech.watch, proptech.watch. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.proptech.watch | custom_domain_candidate | yes, cached | 2026-10-04T16:22:01.727000+00:00 | 5 |
| proptech.watch | custom_domain_candidate | yes, cached | 2026-10-02T19:01:45.437000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.proptech.watch | proptech.watch - DVF market API | proptech.watch | French DVF ownership-transfer and market analytics API. Paid comps, peers, rankings, and transfers via x402 on Algorand. | https://api.proptech.watch/favicon.ico | https://api.proptech.watch/banner.png | not recorded |
| proptech.watch | proptech.watch | not recorded | not recorded | https://proptech.watch/icon-192.png | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| api.proptech.watch | A2A Agent Card | proptech.watch | https://api.proptech.watch/.well-known/agent-card.json | French DVF ownership-transfer and market analytics API. Paid comps, peers, rankings, and transfers via x402 on Algorand. |
| api.proptech.watch | Agent Manifest | proptech.watch | https://api.proptech.watch/.well-known/agent.json | French DVF ownership-transfer and market analytics API. Paid comps, peers, rankings, and transfers via x402 on Algorand. |
| api.proptech.watch | AI Plugin | proptech.watch | https://api.proptech.watch/.well-known/ai-plugin.json | French DVF ownership-transfer and market analytics API. Paid comps, peers, rankings, and transfers via x402 on Algorand. |
| api.proptech.watch | x402 Discovery | proptech.watch | https://api.proptech.watch/.well-known/x402 | French DVF ownership-transfer and market analytics API. Paid comps, peers, rankings, and transfers via x402 on Algorand. |
| api.proptech.watch | llms.txt | proptech.watch | https://api.proptech.watch/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 5 |
| Agent document types | ["agent-card", "agent-json", "ai-plugin", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 4 |
| Description count | 4 |
| Mime type count | 4 |
| Accepts count | 4 |
| Discovery count | 4 |
| Input documentation count | 4 |
| Output documentation count | 4 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-07-22 | 2 | 0.010000 | 1 | 2 | 0 (0.0000%) |
| 2026-08-08 | 15 | 0.150000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-09 | 10 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-11 | 15 | 0.150000 | 2 | 0 | 0 (0.0000%) |
| 2026-08-13 | 11 | 0.110000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-17 | 2 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-27 | 4 | 0.040000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 4 | 0.040000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |

Last 16 of 16 active days; all in the daily CSV.
