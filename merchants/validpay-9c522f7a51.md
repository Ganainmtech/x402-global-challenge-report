# ValidPay — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `Q0lMMlROUzdaN0xaREs2WDNPVVlEQUlN`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | CIL2TNS7Z7LZDK6X3OUYDAIMYLR7HXV3273UDC5N4UHEVAAY3F5CYFTSZQ |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 13 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.013000 | USDC settled. |
| Unique payer accounts | 4 | Distinct accounts that paid. |
| Synthetic-indicated | 7 (53.8462%) · 0.007000 USDC (53.8462%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 6 (46.1538%) · 0.006000 USDC (46.1538%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 13 (100.0000%) · 0.013000 USDC (100.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 7 (53.8462%) · 0.007000 USDC (53.8462%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 2 (15.3846%) · 0.002000 USDC (15.3846%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-29 02:19:14 UTC / 2026-08-23 09:22:45 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/validpay-9c522f7a51-transactions.csv.gz) · [All endpoints](../evidence/validpay-9c522f7a51-endpoints.csv) · [Payer evidence](../evidence/validpay-9c522f7a51-payers.csv) · [Daily metrics](../evidence/validpay-9c522f7a51-daily.csv) · [Site and catalog data](../evidence/validpay-9c522f7a51-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 7 (53.8462%) | 0.007000 (53.8462%) |
| NO-LINK-DETECTED | 6 (46.1538%) | 0.006000 (46.1538%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| NRWHBVQSDUFMHBFMLLHEPWIMJTVCSYECDEBXAAAXHBWNNYRFBYAXDKPSIA | MERCHANT-FUNDED | 7 | 0.007000 (53.8462%) | created by merchant; merchant sent 1.00 ALGO; merchant sent 0.1 USDC ×1 (1429% of paid); throwaway wallet |
| X5WI2JSLU3UEXVOVCC426SL5QFFW3W2HX2I43VIS2FPJOKJ6S2LIZ2AA6A | NO-LINK-DETECTED | 2 | 0.002000 (15.3846%) | throwaway wallet |
| VPF2BUWTDVT7OKK4NKPIJBIBBQ5PSKYNRE4BGNTLHDJY6WDL4DAGFKWF4Q | NO-LINK-DETECTED | 2 | 0.002000 (15.3846%) | throwaway wallet; pays 4 merchants |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 2 | 0.002000 (15.3846%) | pays 16 merchants |

Top 4 of 4 payers; all in the payer CSV.

## Sub-cent settlements

13 (100.0000%) settlements · 0.013000 (100.0000%) USDC. Paid by synthetic-indicated payers: 7 (53.8462%) settlements · 0.007000 (53.8462%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://validpay.uk/v1/weather | 8 (61.5385%) | 0.008000 (61.5385%) | 3 | 8 | 5 |
| GET | https://validpay-production.up.railway.app/v1/weather | 3 (23.0769%) | 0.003000 (23.0769%) | 2 | 3 | 2 |
| (not recorded) | (not recorded) | 2 (15.3846%) | 0.002000 (15.3846%) | 1 | 2 | 0 |

Top 3 of 3 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: validpay-production.up.railway.app, validpay.uk.

Custom-domain candidates: validpay.uk. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| validpay-production.up.railway.app | hosting_provider_domain | yes, cached | 2026-07-29T02:21:17.275000+00:00 | 0 |
| validpay.uk | custom_domain_candidate | yes, cached | 2026-10-05T21:39:15.849000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| validpay-production.up.railway.app | ValidPay | not recorded | Valid response → valid payment. x402 gateway with response contracts. | not recorded | not recorded | not recorded |
| validpay.uk | ValidPay | not recorded | Valid response → valid payment. x402 gateway with response contracts. | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 0 |
| Agent document types | [] |
| Agent readiness evidence | catalog_only |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 2 |
| Description count | 2 |
| Mime type count | 2 |
| Accepts count | 2 |
| Discovery count | 2 |
| Input documentation count | 2 |
| Output documentation count | 2 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-07-29 | 7 | 0.007000 | 1 | 7 | 7 (100.0000%) |
| 2026-07-30 | 2 | 0.002000 | 1 | 2 | 0 (0.0000%) |
| 2026-08-07 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-08-17 | 2 | 0.002000 | 1 | 2 | 0 (0.0000%) |
| 2026-08-23 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |

Last 5 of 5 active days; all in the daily CSV.
