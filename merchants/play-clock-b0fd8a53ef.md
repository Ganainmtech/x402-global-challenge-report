# Play Clock — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 41).

## Identity and accounts

Merchant ID: `TURCSk1NNlJKNFRNN1c1RklUWjNNV0pU`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | MDBJMM6RJ4TM7W5FITZ3MWJTGTHMC4SKQJWRWI2JCQUKIR5LA7BPIUTMMM |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 41 | Play Clock | Exact submitted wallet MDBJMM6RJ4TM7W5FITZ3MWJTGTHMC4SKQJWRWI2JCQUKIR5LA7BPIUTMMM is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 34 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 7.100000 | USDC settled. |
| Unique payer accounts | 3 | Distinct accounts that paid. |
| Synthetic-indicated | 32 (94.1176%) · 6.900000 USDC (97.1831%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 2 (5.8824%) · 0.200000 USDC (2.8169%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-01 15:16:26 UTC / 2026-09-30 01:58:29 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/play-clock-b0fd8a53ef-transactions.csv.gz) · [All endpoints](../evidence/play-clock-b0fd8a53ef-endpoints.csv) · [Payer evidence](../evidence/play-clock-b0fd8a53ef-payers.csv) · [Daily metrics](../evidence/play-clock-b0fd8a53ef-daily.csv) · [Site and catalog data](../evidence/play-clock-b0fd8a53ef-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| FLEET | 20 (58.8235%) | 3.800000 (53.5211%) |
| MERCHANT-FUNDED | 12 (35.2941%) | 3.100000 (43.6620%) |
| NO-LINK-DETECTED | 2 (5.8824%) | 0.200000 (2.8169%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HLD4AZ5M6ZCFVHUZ5VSXKMWQZWDR63YSYFICTRGHTKACEA63PW2DDPH5DM | FLEET | 20 | 3.800000 (53.5211%) | created 1 linked payer |
| RCAUDGDLWUQAG64IPLRZPYMXPVQXTR272SZS3GX66DDTLRABRTQ3FRMXT4 | MERCHANT-FUNDED | 12 | 3.100000 (43.6620%) | created by merchant's creator; 64% of gaps &lt; 60s |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 2 | 0.200000 (2.8169%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 3 of 3 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://api.playclock.xyz/v1/matchup | 4 (11.7647%) | 0.800000 (11.2676%) | 2 | 0 | 4 |
| GET | https://api.playclock.xyz/v1/trending | 4 (11.7647%) | 0.400000 (5.6338%) | 3 | 0 | 3 |
| POST | https://api.playclock.xyz/v1/player | 3 (8.8235%) | 0.300000 (4.2254%) | 3 | 0 | 2 |
| (not recorded) | https://api.playclock.xyz/v1/trending | 3 (8.8235%) | 0.300000 (4.2254%) | 1 | 0 | 3 |
| GET | https://api.playclock.xyz/v1/waivers | 3 (8.8235%) | 0.600000 (8.4507%) | 1 | 0 | 3 |
| (not recorded) | https://api.playclock.xyz/v1/draft-board | 2 (5.8824%) | 0.400000 (5.6338%) | 1 | 0 | 2 |
| (not recorded) | https://api.playclock.xyz/v1/player | 2 (5.8824%) | 0.200000 (2.8169%) | 1 | 0 | 2 |
| (not recorded) | https://api.playclock.xyz/v1/sleepers | 2 (5.8824%) | 0.400000 (5.6338%) | 1 | 0 | 2 |
| GET | https://api.playclock.xyz/v1/sleepers | 2 (5.8824%) | 0.400000 (5.6338%) | 2 | 0 | 2 |
| POST | https://api.playclock.xyz/v1/team-report | 2 (5.8824%) | 1.000000 (14.0845%) | 2 | 0 | 2 |
| GET | https://api.playclock.xyz/v1/draft-board | 1 (2.9412%) | 0.200000 (2.8169%) | 1 | 0 | 1 |
| POST | https://api.playclock.xyz/v1/draft-report | 1 (2.9412%) | 0.500000 (7.0423%) | 1 | 0 | 1 |
| (not recorded) | https://api.playclock.xyz/v1/matchup | 1 (2.9412%) | 0.200000 (2.8169%) | 1 | 0 | 1 |
| (not recorded) | https://api.playclock.xyz/v1/report | 1 (2.9412%) | 0.350000 (4.9296%) | 1 | 0 | 1 |
| GET | https://api.playclock.xyz/v1/report | 1 (2.9412%) | 0.350000 (4.9296%) | 1 | 0 | 1 |
| (not recorded) | https://api.playclock.xyz/v1/roster | 1 (2.9412%) | 0.350000 (4.9296%) | 1 | 0 | 1 |
| POST | https://api.playclock.xyz/v1/roster | 1 (2.9412%) | 0.350000 (4.9296%) | 1 | 0 | 1 |

Top 17 of 17 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.playclock.xyz, playclock.xyz.

Custom-domain candidates: api.playclock.xyz, playclock.xyz. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.playclock.xyz | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 1 |
| playclock.xyz | custom_domain_candidate | yes, cached | 2026-09-30T17:27:24.100000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.playclock.xyz | Play Clock | not recorded | Pay-per-answer NFL fantasy football analysis. One question, one USDC micropayment on Algorand, no account and no subscription. | https://api.playclock.xyz/apple-touch-icon.png | not recorded | not recorded |
| playclock.xyz | Play Clock — pay-per-answer fantasy football intelligence | not recorded | One fantasy football answer at a time. Start/sit calls, waiver boards and roster audits grounded in real usage data, paid for in USDC micropayments on Algorand. No subscription, no account. | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| api.playclock.xyz | llms.txt | Play Clock | https://api.playclock.xyz/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 1 |
| Agent document types | ["llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 10 |
| Description count | 10 |
| Mime type count | 10 |
| Accepts count | 10 |
| Discovery count | 10 |
| Input documentation count | 10 |
| Output documentation count | 10 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01 | 2 | 0.200000 | 1 | 0 | 2 (100.0000%) |
| 2026-09-03 | 4 | 0.800000 | 1 | 0 | 4 (100.0000%) |
| 2026-09-04 | 3 | 0.650000 | 1 | 0 | 3 (100.0000%) |
| 2026-09-06 | 3 | 0.550000 | 1 | 0 | 3 (100.0000%) |
| 2026-09-10 | 1 | 0.100000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-21 | 1 | 0.200000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-22 | 10 | 2.700000 | 1 | 0 | 10 (100.0000%) |
| 2026-09-27 | 5 | 0.700000 | 2 | 0 | 3 (60.0000%) |
| 2026-09-30 | 5 | 1.200000 | 2 | 0 | 5 (100.0000%) |

Last 9 of 9 active days; all in the daily CSV.
