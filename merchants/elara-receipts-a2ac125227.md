# Elara Receipts — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 100).

## Identity and accounts

Merchant ID: `MlBXR1VLRTRWV1VYWFozSVBQWDJXNEZV`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 2PWGUKE4VWUXXZ3IPPX2W4FUTVXAW3HQLBO2GZJZFX4UXWFNSUMWEGSSXE |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 100 | Elara Receipts | Exact submitted wallet 2PWGUKE4VWUXXZ3IPPX2W4FUTVXAW3HQLBO2GZJZFX4UXWFNSUMWEGSSXE is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 10 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.050000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 10 (100.0000%) · 0.050000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 10 (100.0000%) · 0.050000 USDC (100.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 3 · 0.030000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-27 04:40:31 UTC / 2026-10-06 00:05:21 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/elara-receipts-a2ac125227-transactions.csv.gz) · [All endpoints](../evidence/elara-receipts-a2ac125227-endpoints.csv) · [Payer evidence](../evidence/elara-receipts-a2ac125227-payers.csv) · [Daily metrics](../evidence/elara-receipts-a2ac125227-daily.csv) · [Site and catalog data](../evidence/elara-receipts-a2ac125227-site-and-catalog.json)

**Flag — self-payments excluded:** 3 settlements / 0.030000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 10 (100.0000%) | 0.050000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 10 | 0.050000 (100.0000%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

10 (100.0000%) settlements · 0.050000 (100.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://elara-verify-x402.name-redacted.workers.dev/verify/record | 10 (100.0000%) | 0.050000 (100.0000%) | 1 | 10 | 0 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: elara-verify-x402.name-redacted.workers.dev.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| elara-verify-x402.name-redacted.workers.dev | hosting_provider_domain | not established | 2026-10-01T15:51:20.362000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| elara-verify-x402.name-redacted.workers.dev | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 0 |
| Agent document count | 0 |
| Agent document types | [] |
| Agent readiness evidence | catalog_only |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "No cached descriptive homepage evidence on included public domains.", "No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 1 |
| Description count | 1 |
| Mime type count | 1 |
| Accepts count | 1 |
| Discovery count | 1 |
| Input documentation count | 1 |
| Output documentation count | 1 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-27 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-28 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |

Last 10 of 10 active days; all in the daily CSV.
