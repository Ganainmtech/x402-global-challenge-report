# Trust402 — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 19).

## Identity and accounts

Merchant ID: `Vk82NlNDV1JPQkpPWE9DV1EySUIzWUFN`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | VO66SCWROBJOXOCWQ2IB3YAM3DIFP4CVKDEB73S2BNLISMVFT4VEQTEPHM |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 19 | Trust402 | Exact submitted wallet VO66SCWROBJOXOCWQ2IB3YAM3DIFP4CVKDEB73S2BNLISMVFT4VEQTEPHM is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 5 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.250000 | USDC settled. |
| Unique payer accounts | 3 | Distinct accounts that paid. |
| Synthetic-indicated | 4 (80.0000%) · 0.200000 USDC (80.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 1 (20.0000%) · 0.050000 USDC (20.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-30 07:52:34 UTC / 2026-10-01 07:10:04 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/trust402-ee6661eb7b-transactions.csv.gz) · [All endpoints](../evidence/trust402-ee6661eb7b-endpoints.csv) · [Payer evidence](../evidence/trust402-ee6661eb7b-payers.csv) · [Daily metrics](../evidence/trust402-ee6661eb7b-daily.csv) · [Site and catalog data](../evidence/trust402-ee6661eb7b-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| FLEET | 2 (40.0000%) | 0.100000 (40.0000%) |
| MERCHANT-FUNDED | 2 (40.0000%) | 0.100000 (40.0000%) |
| NO-LINK-DETECTED | 1 (20.0000%) | 0.050000 (20.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| QPZZ3QBCDQP7B2PMAQVJWTHFQJFLJZVHY24WMWVRWNFQIUS7WMIBYXN7IU | MERCHANT-FUNDED | 2 | 0.100000 (40.0000%) | created by merchant's creator; throwaway wallet |
| JETVNVTSNMBC5LC4HIGIZPIQE67H7ZPFTSLTDUVHTSWO7XUK5NSUXRVIXQ | FLEET | 2 | 0.100000 (40.0000%) | created 1 linked payer |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 1 | 0.050000 (20.0000%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 3 of 3 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://trust402.name-redacted.deno.net/v1/trust | 5 (100.0000%) | 0.250000 (100.0000%) | 3 | 0 | 4 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: trust402.name-redacted.deno.net.

Custom-domain candidates: trust402.name-redacted.deno.net. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| trust402.name-redacted.deno.net | custom_domain_candidate | not established | 2026-10-01T15:51:20.362000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| trust402.name-redacted.deno.net | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
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
| Gaps | ["No cached descriptive homepage evidence on included public domains.", "No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-09-30 | 4 | 0.200000 | 3 | 0 | 3 (75.0000%) |
| 2026-10-01 | 1 | 0.050000 | 1 | 0 | 1 (100.0000%) |

Last 2 of 2 active days; all in the daily CSV.
