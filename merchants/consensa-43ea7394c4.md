# Consensa — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `UEpPWEZJQktWS0dZR01DVzMzNDZQNU40`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | PJOXFIBKVKGYGMCW3346P5N4OATMODZYM3VQOXDAEUTIGAOGRYGTIO3NME |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 24 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.240000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 24 (100.0000%) · 0.240000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-02 07:44:52 UTC / 2026-10-06 00:07:13 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/consensa-43ea7394c4-transactions.csv.gz) · [All endpoints](../evidence/consensa-43ea7394c4-endpoints.csv) · [Payer evidence](../evidence/consensa-43ea7394c4-payers.csv) · [Daily metrics](../evidence/consensa-43ea7394c4-daily.csv) · [Site and catalog data](../evidence/consensa-43ea7394c4-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 24 (100.0000%) | 0.240000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| S3L2CXXTVPGJ3GQQST63TWYJWN6MY5UGXDEZHEXPEMNU2KIT7VLGUSO35M | NO-LINK-DETECTED | 14 | 0.140000 (58.3333%) | throwaway wallet; 62% of gaps &lt; 60s |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 10 | 0.100000 (41.6667%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | http://consensa-endpoint-production.up.railway.app/v1/clearance | 13 (54.1667%) | 0.130000 (54.1667%) | 1 | 0 | 0 |
| POST | https://consensa-endpoint-production.up.railway.app/v1/clearance | 11 (45.8333%) | 0.110000 (45.8333%) | 2 | 0 | 0 |

Top 2 of 2 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: consensa-endpoint-production.up.railway.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| consensa-endpoint-production.up.railway.app | hosting_provider_domain | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| consensa-endpoint-production.up.railway.app | Consensa | not recorded | Consent, attribution, and fair compensation for knowledge AI agents consume | https://consensa-endpoint-production.up.railway.app/apple-touch-icon.png | https://consensa-endpoint-production.up.railway.app/og-image.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
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
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 2 |
| Description count | 2 |
| Mime type count | 0 |
| Accepts count | 2 |
| Discovery count | 2 |
| Input documentation count | 2 |
| Output documentation count | 2 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-02 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-03 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-06 | 10 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-10 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-20 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-27 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |

Last 15 of 15 active days; all in the daily CSV.
