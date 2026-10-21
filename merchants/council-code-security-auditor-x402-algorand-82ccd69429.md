# Council Code Security Auditor (x402 Algorand) — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 14).

## Identity and accounts

Merchant ID: `M1hGRkxORUFKU1JEWUFGREpRTFhWNU5G`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 3XFFLNEAJSRDYAFDJQLXV5NFMBHGVXVHHDHPIQZU7EDOD6FRFWPDLU25PM |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 14 | Council Code Security Auditor (x402 Algorand) | Exact submitted wallet 3XFFLNEAJSRDYAFDJQLXV5NFMBHGVXVHHDHPIQZU7EDOD6FRFWPDLU25PM is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 2 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.020000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 1 (50.0000%) · 0.010000 USDC (50.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 1 (50.0000%) · 0.010000 USDC (50.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-27 23:25:52 UTC / 2026-09-28 01:27:09 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/council-code-security-auditor-x402-algorand-82ccd69429-transactions.csv.gz) · [All endpoints](../evidence/council-code-security-auditor-x402-algorand-82ccd69429-endpoints.csv) · [Payer evidence](../evidence/council-code-security-auditor-x402-algorand-82ccd69429-payers.csv) · [Daily metrics](../evidence/council-code-security-auditor-x402-algorand-82ccd69429-daily.csv) · [Site and catalog data](../evidence/council-code-security-auditor-x402-algorand-82ccd69429-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 1 (50.0000%) | 0.010000 (50.0000%) |
| NO-LINK-DETECTED | 1 (50.0000%) | 0.010000 (50.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| 5Z2W6Q427NXJOBEEEXKTNGPXNDNNJXAAGCW772V7I5NI67IV4TVZMXEJUU | MERCHANT-FUNDED | 1 | 0.010000 (50.0000%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 0.1 USDC ×1 (1000% of paid); throwaway wallet |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 1 | 0.010000 (50.0000%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | [local URL omitted] | 2 (100.0000%) | 0.020000 (100.0000%) | 2 | 0 | 1 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: see observed endpoints.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 0 |
| Cached domain metadata count | 0 |
| Domains with cached descriptive homepage evidence | 0 |
| Agent document count | 0 |
| Agent document types | [] |
| Agent readiness evidence | not_recorded |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "No cached descriptive homepage evidence on included public domains.", "No cached agent discovery documents on included public domains.", "No catalog resources on included public domains."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 0 |
| Description count | 0 |
| Mime type count | 0 |
| Accepts count | 0 |
| Discovery count | 0 |
| Input documentation count | 0 |
| Output documentation count | 0 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-27 | 1 | 0.010000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-28 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |

Last 2 of 2 active days; all in the daily CSV.
