# PipeForge x402 Infrastructure Inspector — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 93).

## Identity and accounts

Merchant ID: `MlVYTFJGTTZKTFNBSldCVDVRUU9PWVRW`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 6Q7MNZLDJUMRHPPQIV3XPKGWONZQQG4GSFLQMUGG2PDZJHIOCZKVDC3OAU |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 93 | PipeForge x402 Infrastructure Inspector | Exact submitted wallet 6Q7MNZLDJUMRHPPQIV3XPKGWONZQQG4GSFLQMUGG2PDZJHIOCZKVDC3OAU is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 7 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.140000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 7 (100.0000%) · 0.140000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-17 21:34:58 UTC / 2026-10-06 00:10:06 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/pipeforge-x402-infrastructure-inspector-849069d9cc-transactions.csv.gz) · [All endpoints](../evidence/pipeforge-x402-infrastructure-inspector-849069d9cc-endpoints.csv) · [Payer evidence](../evidence/pipeforge-x402-infrastructure-inspector-849069d9cc-payers.csv) · [Daily metrics](../evidence/pipeforge-x402-infrastructure-inspector-849069d9cc-daily.csv) · [Site and catalog data](../evidence/pipeforge-x402-infrastructure-inspector-849069d9cc-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 7 (100.0000%) | 0.140000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 5 | 0.100000 (71.4286%) | throwaway wallet; created by vet402; pays 68 merchants |
| TGRD7KGVCHPFWBONY7ZNN2NFRD75CQOVYISL6WOJV3MKO6T3FVBR3LAZGE | NO-LINK-DETECTED | 2 | 0.040000 (28.5714%) | throwaway wallet |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://x402.pipeforge.tech/api/v1/inspect | 6 (85.7143%) | 0.120000 (85.7143%) | 2 | 0 | 0 |
| GET | https://x402.pipeforge.tech/api/v1/inspect | 1 (14.2857%) | 0.020000 (14.2857%) | 1 | 0 | 0 |

Top 2 of 2 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: x402.pipeforge.tech.

Custom-domain candidates: x402.pipeforge.tech. Registered email on a matching custom domain: **pipeforge.tech**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| x402.pipeforge.tech | custom_domain_candidate | not established | 2026-10-01T15:51:20.362000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| x402.pipeforge.tech | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

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
| Agent readiness evidence | not_recorded |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No cached descriptive homepage evidence on included public domains.", "No cached agent discovery documents on included public domains.", "No catalog resources on included public domains."] |

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
| 2026-09-17 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |

Last 7 of 7 active days; all in the daily CSV.
