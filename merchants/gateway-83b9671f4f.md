# GATEWAY — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 6).

## Identity and accounts

Merchant ID: `TFhQQzRHUVBZSDJFWlFYMlFEWU1IQ1Ay`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | LXPC4GQPYH2EZQX2QDYMHCP2I7MXIZMVRPIYTQ3D7R7HXJ4SIHCSYLF5YA |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 6 | GATEWAY | Exact submitted wallet LXPC4GQPYH2EZQX2QDYMHCP2I7MXIZMVRPIYTQ3D7R7HXJ4SIHCSYLF5YA is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 43 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 3.787000 | USDC settled. |
| Unique payer accounts | 5 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 43 (100.0000%) · 3.787000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 14 (32.5581%) · 0.037000 USDC (0.9770%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 1 (2.3256%) · 0.001000 USDC (0.0264%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-07 19:50:51 UTC / 2026-10-06 00:03:47 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/gateway-83b9671f4f-transactions.csv.gz) · [All endpoints](../evidence/gateway-83b9671f4f-endpoints.csv) · [Payer evidence](../evidence/gateway-83b9671f4f-payers.csv) · [Daily metrics](../evidence/gateway-83b9671f4f-daily.csv) · [Site and catalog data](../evidence/gateway-83b9671f4f-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 43 (100.0000%) | 3.787000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| A7EWRCWXWTQWETT7AMHXQFT6U44JYOAEWB4J6XEZY64PKKOATCVE4FKG6I | NO-LINK-DETECTED | 7 | 2.200000 (58.0935%) | merchant sent 0.14 USDC ×2 (6.4% of paid); throwaway wallet; 50% of gaps &lt; 60s; same funder as merchant (hub) |
| YWNGQUX52GXKC4BHS6GA5VZ5JLKG6LB7PACLDXWYGLWPNZ234U5W5KVWP4 | NO-LINK-DETECTED | 16 | 1.345000 (35.5162%) | merchant sent 0.25 USDC ×4 (19% of paid); throwaway wallet; same funder as merchant (hub) |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 18 | 0.240000 (6.3375%) | throwaway wallet; created by vet402; pays 68 merchants |
| K4HCGHT7IW5QSDUQL2W3UVFPIQI4UELUIKA7PH2XFIINMFSNZG3HQVZSEM | NO-LINK-DETECTED | 1 | 0.001000 (0.0264%) | pays 2 merchants |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 1 | 0.001000 (0.0264%) | pays 16 merchants |

Top 5 of 5 payers; all in the payer CSV.

## Sub-cent settlements

14 (32.5581%) settlements · 0.037000 (0.9770%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://gateway-x402.vercel.app/discover | 19 (44.1860%) | 0.225000 (5.9414%) | 3 | 9 | 0 |
| GET | https://gateway-x402.vercel.app/signals | 4 (9.3023%) | 1.000000 (26.4061%) | 2 | 0 | 0 |
| GET | https://gateway-x402.vercel.app/diff | 3 (6.9767%) | 0.022000 (0.5809%) | 2 | 1 | 0 |
| GET | https://gateway-x402.vercel.app/discover/batch | 3 (6.9767%) | 0.045000 (1.1883%) | 2 | 1 | 0 |
| GET | https://gateway-x402.vercel.app/news | 3 (6.9767%) | 0.600000 (15.8437%) | 1 | 0 | 0 |
| GET | https://gateway-x402.vercel.app/probe | 3 (6.9767%) | 0.022000 (0.5809%) | 2 | 1 | 0 |
| POST | https://gateway-x402.vercel.app/probe | 3 (6.9767%) | 0.022000 (0.5809%) | 2 | 1 | 0 |
| (not recorded) | https://gateway-x402.vercel.app/swap | 3 (6.9767%) | 1.500000 (39.6092%) | 2 | 0 | 0 |
| (not recorded) | (not recorded) | 1 (2.3256%) | 0.001000 (0.0264%) | 1 | 1 | 0 |
| GET | https://gateway-x402.vercel.app/markets | 1 (2.3256%) | 0.350000 (9.2421%) | 1 | 0 | 0 |

Top 10 of 10 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: gateway-x402.vercel.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| gateway-x402.vercel.app | hosting_provider_domain | yes, cached | 2026-10-06T09:08:06.176000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| gateway-x402.vercel.app | GATEWAY — Algorand x402 discovery router | GATEWAY | Ranked alive x402 endpoints on Algorand. Free /registry · paid Exact AVM /discover · /orchestrate. | https://gateway-sand-two.vercel.app/og.svg | https://gateway-sand-two.vercel.app/og.svg | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| gateway-x402.vercel.app | AI Plugin | GATEWAY | https://gateway-x402.vercel.app/.well-known/ai-plugin.json | Algorand x402 discovery router — ranked alive endpoints, probes, orchestrator. |
| gateway-x402.vercel.app | llms.txt | GATEWAY | https://gateway-x402.vercel.app/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 2 |
| Agent document types | ["ai-plugin", "llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 9 |
| Description count | 9 |
| Mime type count | 9 |
| Accepts count | 9 |
| Discovery count | 9 |
| Input documentation count | 9 |
| Output documentation count | 9 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-07 | 8 | 0.015000 | 1 | 8 | 0 (0.0000%) |
| 2026-08-08 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-08-17 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-27 | 5 | 0.055000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-28 | 5 | 0.055000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 11 | 2.050000 | 3 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 6 | 1.520000 | 2 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |

Last 13 of 13 active days; all in the daily CSV.
