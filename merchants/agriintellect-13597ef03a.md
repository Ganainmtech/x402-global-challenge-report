# AgriIntellect — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 20, 21).

## Identity and accounts

Merchant ID: `QlJTTVdUTldGUlcyNkxVN0ZRN0NHMktZ`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | BRSMWTNWFRW26LU7FQ7CG2KY65P5HTCBXX6QAOIEM35NESQFGWM4KWEYDU |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 20 | AgriIntellect | Exact submitted wallet BRSMWTNWFRW26LU7FQ7CG2KY65P5HTCBXX6QAOIEM35NESQFGWM4KWEYDU is a receiving account of this merchant. |
| 21 | AgriIntellect | Exact submitted wallet BRSMWTNWFRW26LU7FQ7CG2KY65P5HTCBXX6QAOIEM35NESQFGWM4KWEYDU is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 182 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 19.050000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 169 (92.8571%) · 18.300000 USDC (96.0630%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 13 (7.1429%) · 0.750000 USDC (3.9370%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-22 06:57:29 UTC / 2026-10-06 00:09:33 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/agriintellect-13597ef03a-transactions.csv.gz) · [All endpoints](../evidence/agriintellect-13597ef03a-endpoints.csv) · [Payer evidence](../evidence/agriintellect-13597ef03a-payers.csv) · [Daily metrics](../evidence/agriintellect-13597ef03a-daily.csv) · [Site and catalog data](../evidence/agriintellect-13597ef03a-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 169 (92.8571%) | 18.300000 (96.0630%) |
| NO-LINK-DETECTED | 13 (7.1429%) | 0.750000 (3.9370%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| RBW6SBAPCWB6PIRX5Z4GNVZE7EZVOYBDSWA46AE5MUNUAK2PE5H6HSUIJA | MERCHANT-FUNDED | 169 | 18.300000 (96.0630%) | created by merchant's creator; merchant sent 0.5 ALGO; merchant sent 28.29 USDC ×44 (155% of paid) |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 13 | 0.750000 (3.9370%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://agriintellect.site/weather-risk | 79 (43.4066%) | 3.530000 (18.5302%) | 2 | 0 | 69 |
| POST | https://agriintellect.site/fertilizer-info | 71 (39.0110%) | 3.300000 (17.3228%) | 2 | 0 | 70 |
| POST | https://agriintellect.site/mandi-optimize | 20 (10.9890%) | 1.720000 (9.0289%) | 2 | 0 | 18 |
| POST | https://agriintellect.site/credits-topup/pack30 | 9 (4.9451%) | 9.000000 (47.2441%) | 1 | 0 | 9 |
| POST | https://agriintellect.site/credits-topup/pack20 | 2 (1.0989%) | 1.000000 (5.2493%) | 1 | 0 | 2 |
| (not recorded) | https://topupendpoint.onrender.com/credits-topup/pack20 | 1 (0.5495%) | 0.500000 (2.6247%) | 1 | 0 | 1 |

Top 6 of 6 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: agriintellect.site, agrometeorological-api.onrender.com, fertilizer-platform-py.onrender.com, mandi-endpoint.onrender.com, topupendpoint.onrender.com, weather-api-pd94.onrender.com.

Custom-domain candidates: agriintellect.site. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| agriintellect.site | custom_domain_candidate | yes, cached | 2026-10-06T11:27:34.778000+00:00 | 0 |
| agrometeorological-api.onrender.com | hosting_provider_domain | not established | 2026-09-02T12:06:42.886000+00:00 | 0 |
| fertilizer-platform-py.onrender.com | hosting_provider_domain | not established | 2026-08-01T06:13:52.861000+00:00 | 0 |
| mandi-endpoint.onrender.com | hosting_provider_domain | not established | 2026-08-04T04:23:22.475000+00:00 | 0 |
| topupendpoint.onrender.com | hosting_provider_domain | not established | 2026-09-02T12:04:26.508000+00:00 | 0 |
| weather-api-pd94.onrender.com | hosting_provider_domain | not established | 2026-07-24T17:42:41.609000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| agriintellect.site | AgriIntellect — Weather, Mandi & Fertilizer Advisory on WhatsApp | not recorded | AgriIntellect sends Maharashtra farmers real-time weather, nearest mandi rates, and government-registered fertilizer advice — directly on WhatsApp, in Marathi, Hindi or English. | not recorded | not recorded | not recorded |
| agrometeorological-api.onrender.com | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |
| fertilizer-platform-py.onrender.com | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |
| mandi-endpoint.onrender.com | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |
| topupendpoint.onrender.com | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |
| weather-api-pd94.onrender.com | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 6 |
| Cached domain metadata count | 6 |
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
| Output documentation count | 0 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02 | 11 | 2.950000 | 1 | 0 | 11 (100.0000%) |
| 2026-09-03 | 5 | 0.300000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-04 | 2 | 0.100000 | 1 | 0 | 2 (100.0000%) |
| 2026-09-05 | 15 | 0.850000 | 1 | 0 | 15 (100.0000%) |
| 2026-09-06 | 4 | 1.140000 | 1 | 0 | 4 (100.0000%) |
| 2026-09-07 | 4 | 0.200000 | 1 | 0 | 4 (100.0000%) |
| 2026-09-08 | 13 | 4.450000 | 1 | 0 | 13 (100.0000%) |
| 2026-09-09 | 2 | 0.100000 | 1 | 0 | 2 (100.0000%) |
| 2026-09-10 | 9 | 0.500000 | 1 | 0 | 9 (100.0000%) |
| 2026-09-11 | 1 | 0.050000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-12 | 3 | 0.150000 | 1 | 0 | 3 (100.0000%) |
| 2026-09-13 | 2 | 0.100000 | 1 | 0 | 2 (100.0000%) |
| 2026-09-15 | 2 | 0.150000 | 1 | 0 | 2 (100.0000%) |
| 2026-09-18 | 1 | 0.050000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-19 | 3 | 0.200000 | 1 | 0 | 3 (100.0000%) |
| 2026-09-21 | 7 | 0.350000 | 1 | 0 | 7 (100.0000%) |
| 2026-09-23 | 5 | 0.350000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-24 | 4 | 0.200000 | 1 | 0 | 4 (100.0000%) |
| 2026-09-25 | 12 | 0.650000 | 1 | 0 | 12 (100.0000%) |
| 2026-09-26 | 2 | 1.050000 | 1 | 0 | 2 (100.0000%) |
| 2026-09-27 | 5 | 0.300000 | 2 | 0 | 2 (40.0000%) |
| 2026-09-28 | 7 | 1.350000 | 2 | 0 | 5 (71.4286%) |
| 2026-09-29 | 3 | 0.150000 | 2 | 0 | 2 (66.6667%) |
| 2026-09-30 | 4 | 0.650000 | 2 | 0 | 3 (75.0000%) |
| 2026-10-01 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 5 | 0.700000 | 2 | 0 | 4 (80.0000%) |
| 2026-10-03 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 2 | 0.100000 | 2 | 0 | 1 (50.0000%) |
| 2026-10-05 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |

Last 30 of 38 active days; all in the daily CSV.
