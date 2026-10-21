# NEURAL_MESH — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `RjIyVVdNNEhENDVRS0RMTkdUNjZDUjZY`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | F22UWM4HD45QKDLNGT66CR6XJEANNRXUF2WKBF42VV333INY3O3YJMF55U |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 43 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.750000 | USDC settled. |
| Unique payer accounts | 3 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 43 (100.0000%) · 0.750000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-09 19:13:34 UTC / 2026-10-06 00:06:13 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/neural-mesh-5128718a7b-transactions.csv.gz) · [All endpoints](../evidence/neural-mesh-5128718a7b-endpoints.csv) · [Payer evidence](../evidence/neural-mesh-5128718a7b-payers.csv) · [Daily metrics](../evidence/neural-mesh-5128718a7b-daily.csv) · [Site and catalog data](../evidence/neural-mesh-5128718a7b-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 43 (100.0000%) | 0.750000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| FYWMW5GLCK6K2HJK4GY5IDVJ5GO2WC3QU5U77XPJC6HJILTBRF3LEXUPW4 | NO-LINK-DETECTED | 30 | 0.600000 (80.0000%) | throwaway wallet |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 12 | 0.140000 (18.6667%) | throwaway wallet; created by vet402; pays 68 merchants |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 1 | 0.010000 (1.3333%) | pays 16 merchants |

Top 3 of 3 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://api.d0xeddev.com/algorand-x402/mesh/tokens | 28 (65.1163%) | 0.560000 (74.6667%) | 2 | 0 | 0 |
| GET | https://api.d0xeddev.com/algorand-x402/trading-signals | 12 (27.9070%) | 0.120000 (16.0000%) | 3 | 0 | 0 |
| GET | http://api.d0xeddev.com/agent-intel | 1 (2.3256%) | 0.050000 (6.6667%) | 1 | 0 | 0 |
| POST | http://api.d0xeddev.com/scam-score | 1 (2.3256%) | 0.010000 (1.3333%) | 1 | 0 | 0 |
| GET | http://api.d0xeddev.com/trading-signals | 1 (2.3256%) | 0.010000 (1.3333%) | 1 | 0 | 0 |

Top 5 of 5 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.d0xeddev.com.

Custom-domain candidates: api.d0xeddev.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.d0xeddev.com | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.d0xeddev.com | NEURAL_MESH — Brain & Spine | NEURAL_MESH | A self-organizing, self-forgetting memory mesh. Firing-synapse brain + the Spine: D0xed Devs' agentic pipeline in a humanoid body. | https://api.d0xeddev.com/apple-touch-icon.png | https://api.d0xeddev.com/brain/og.png | #000818 |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 0 |
| Agent document types | [] |
| Agent readiness evidence | catalog_only |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 5 |
| Description count | 5 |
| Mime type count | 5 |
| Accepts count | 5 |
| Discovery count | 5 |
| Input documentation count | 5 |
| Output documentation count | 5 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-09 | 4 | 0.080000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-17 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-29 | 10 | 0.200000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-30 | 3 | 0.060000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-31 | 3 | 0.060000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-01 | 3 | 0.060000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-02 | 3 | 0.060000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-03 | 3 | 0.060000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-04 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-27 | 2 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 2 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |

Last 19 of 19 active days; all in the daily CSV.
