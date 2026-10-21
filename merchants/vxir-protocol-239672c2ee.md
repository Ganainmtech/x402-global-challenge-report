# VXIR Protocol — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 8).

## Identity and accounts

Merchant ID: `SVZIQkM2Q0pXSElNVERFS05BRUgyQklJ`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | IVHBC6CJWHIMTDEKNAEH2BIIDVA6UOHVT75M2GYVDB3GNENESDQSJYEWHY |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 8 | VXIR Protocol | Exact submitted wallet IVHBC6CJWHIMTDEKNAEH2BIIDVA6UOHVT75M2GYVDB3GNENESDQSJYEWHY is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 1 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.002000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 1 (100.0000%) · 0.002000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 1 (100.0000%) · 0.002000 USDC (100.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 1 (100.0000%) · 0.002000 USDC (100.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-30 23:45:39 UTC / 2026-09-30 23:45:39 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/vxir-protocol-239672c2ee-transactions.csv.gz) · [All endpoints](../evidence/vxir-protocol-239672c2ee-endpoints.csv) · [Payer evidence](../evidence/vxir-protocol-239672c2ee-payers.csv) · [Daily metrics](../evidence/vxir-protocol-239672c2ee-daily.csv) · [Site and catalog data](../evidence/vxir-protocol-239672c2ee-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 1 (100.0000%) | 0.002000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| JLF5PKCOBY3IBDRCHZ3TIM4IEKR5PZ7F45U5UICK3DRJD4J5NTJNYOJ5Q4 | MERCHANT-FUNDED | 1 | 0.002000 (100.0000%) | created by merchant; merchant sent 30.00 ALGO; throwaway wallet |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

1 (100.0000%) settlements · 0.002000 (100.0000%) USDC. Paid by synthetic-indicated payers: 1 (100.0000%) settlements · 0.002000 (100.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | http://vxir-x402-production.up.railway.app/compile | 1 (100.0000%) | 0.002000 (100.0000%) | 1 | 1 | 1 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: vxir-x402-production.up.railway.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| vxir-x402-production.up.railway.app | hosting_provider_domain | not established | 2026-10-01T15:51:20.362000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| vxir-x402-production.up.railway.app | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

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
| 2026-09-30 | 1 | 0.002000 | 1 | 1 | 1 (100.0000%) |

Last 1 of 1 active days; all in the daily CSV.
