# Ripar — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `M1FBSlhKVkcyWjRJUEVLQzUzU1lWSEw3`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 3QAJXJVG2Z4IPEKC53SYVHL7P5ILE3CT2T3BW6VPJ5WCOY7M7QDJHELWNY |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 20 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.260000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 4 (20.0000%) · 0.060000 USDC (23.0769%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 16 (80.0000%) · 0.200000 USDC (76.9231%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-18 06:12:19 UTC / 2026-10-06 00:06:53 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/ripar-779aa112ff-transactions.csv.gz) · [All endpoints](../evidence/ripar-779aa112ff-endpoints.csv) · [Payer evidence](../evidence/ripar-779aa112ff-payers.csv) · [Daily metrics](../evidence/ripar-779aa112ff-daily.csv) · [Site and catalog data](../evidence/ripar-779aa112ff-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 4 (20.0000%) | 0.060000 (23.0769%) |
| NO-LINK-DETECTED | 16 (80.0000%) | 0.200000 (76.9231%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 16 | 0.200000 (76.9231%) | throwaway wallet; created by vet402; pays 68 merchants |
| HP7LV2WVWY2C4GWHLU6XJDQYDDJOWWATHSIKANYBUJFHKPTUJ4MYSBXO3M | MERCHANT-FUNDED | 4 | 0.060000 (23.0769%) | created by merchant; merchant sent 0.63 ALGO; merchant sent 1.15 USDC ×3 (1917% of paid); throwaway wallet |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://api.ripar.io/api/payee-check | 11 (55.0000%) | 0.110000 (42.3077%) | 2 | 0 | 1 |
| POST | https://api.ripar.io/api/summarize | 3 (15.0000%) | 0.030000 (11.5385%) | 2 | 0 | 1 |
| POST | https://api.ripar.io/api/verify-settlement | 3 (15.0000%) | 0.060000 (23.0769%) | 2 | 0 | 1 |
| POST | https://api.ripar.io/api/x402-check | 3 (15.0000%) | 0.060000 (23.0769%) | 2 | 0 | 1 |

Top 4 of 4 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.ripar.io.

Custom-domain candidates: api.ripar.io. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.ripar.io | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.ripar.io | Ripar | Ripar | Trust and verification for x402 on Algorand. Check an endpoint before you list it, check a payee before you pay it, prove a settlement after it lands. | https://api.ripar.io/icon.png | https://api.ripar.io/opengraph-image | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| api.ripar.io | Agent Manifest | Ripar | https://api.ripar.io/.well-known/agent.json | Text utilities, payable per call over x402 on Algorand MainNet. |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 1 |
| Agent document types | ["agent-json"] |
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
| 2026-09-18 | 4 | 0.060000 | 1 | 0 | 4 (100.0000%) |
| 2026-09-27 | 4 | 0.060000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 4 | 0.060000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |

Last 11 of 11 active days; all in the daily CSV.
