# PrivacyBuddy — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 15).

## Identity and accounts

Merchant ID: `RUE3V0FTWlFZWEdHUlNNR1lRTFJJNlRS`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | EA7WASZQYXGGRSMGYQLRI6TR2PQCVDC42QULUT5N62UMYO4A6ADCJ6464M |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 15 | PrivacyBuddy | Exact submitted wallet EA7WASZQYXGGRSMGYQLRI6TR2PQCVDC42QULUT5N62UMYO4A6ADCJ6464M is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 72 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 1.800000 | USDC settled. |
| Unique payer accounts | 7 | Distinct accounts that paid. |
| Synthetic-indicated | 50 (69.4444%) · 0.780000 USDC (43.3333%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 22 (30.5556%) · 1.020000 USDC (56.6667%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-10-02 18:56:05 UTC / 2026-10-06 10:46:16 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/privacybuddy-0912832958-transactions.csv.gz) · [All endpoints](../evidence/privacybuddy-0912832958-endpoints.csv) · [Payer evidence](../evidence/privacybuddy-0912832958-payers.csv) · [Daily metrics](../evidence/privacybuddy-0912832958-daily.csv) · [Site and catalog data](../evidence/privacybuddy-0912832958-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| FLEET | 17 (23.6111%) | 0.170000 (9.4444%) |
| MERCHANT-FUNDED | 33 (45.8333%) | 0.610000 (33.8889%) |
| NO-LINK-DETECTED | 22 (30.5556%) | 1.020000 (56.6667%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| SY2OBNJ7SZH4IEG5EDHJSJFOJKIFLUO475R4LVPKMNIJ7CXD6TIZL4SBZQ | NO-LINK-DETECTED | 10 | 0.500000 (27.7778%) | throwaway wallet |
| KP3ZEMMN7AN4QRVEHDLN5EEGA27VM2TCQ2JKFHA3FNI4ECBBP73U7C3YTU | MERCHANT-FUNDED | 8 | 0.320000 (17.7778%) | created by merchant's creator; throwaway wallet |
| 7Q6NGB6PODIB3KUW3HHIXQKWRSXCG76OUP7WEFYMGTVYNU5SOCKN7URAZU | MERCHANT-FUNDED | 25 | 0.290000 (16.1111%) | created by merchant's creator; throwaway wallet; 54% of gaps &lt; 60s |
| Z3TEC77NIVQSHOYQTB4LY5XPLIV4ZJ2HU6BQAN3BNG3POON4ND3WO3BVAA | NO-LINK-DETECTED | 6 | 0.260000 (14.4444%) | throwaway wallet |
| FFPFJQ3WIBBESD2MFYLDS37WVP3U26RID54EB4UAWEWA7FVZ5EMEQ2CLEI | NO-LINK-DETECTED | 4 | 0.200000 (11.1111%) | throwaway wallet |
| DTYROQS3GZAA7PNFR4QAJVDN42MHJMA7GHVIZODV7WOK2PRCEXK275L5NI | FLEET | 17 | 0.170000 (9.4444%) | created 2 linked payers; throwaway wallet |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 2 | 0.060000 (3.3333%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 7 of 7 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://privacybuddy.up.railway.app/v1/chat/completions | 72 (100.0000%) | 1.800000 (100.0000%) | 7 | 0 | 50 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: privacybuddy.up.railway.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| privacybuddy.up.railway.app | hosting_provider_domain | yes, cached | 2026-10-04T15:50:02.359000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| privacybuddy.up.railway.app | PrivacyBuddy | PrivacyBuddy | Private AI chat. Sensitive details are masked before any model sees them, and every answer is paid per call in USDC on Algorand with x402. | not recorded | not recorded | not recorded |

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
| 2026-10-02 | 3 | 0.030000 | 1 | 0 | 3 (100.0000%) |
| 2026-10-03 | 11 | 0.110000 | 3 | 0 | 10 (90.9091%) |
| 2026-10-04 | 29 | 0.290000 | 2 | 0 | 29 (100.0000%) |
| 2026-10-05 | 11 | 0.470000 | 5 | 0 | 2 (18.1818%) |
| 2026-10-06 | 18 | 0.900000 | 4 | 0 | 6 (33.3333%) |

Last 5 of 5 active days; all in the daily CSV.
