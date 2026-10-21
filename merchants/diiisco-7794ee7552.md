# DIIISCO — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 44).

## Identity and accounts

Merchant ID: `RElJSVNDT0dUM09UWUJLVUJWSk5XN1lP`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | DIIISCOGT3OTYBKUBVJNW7YOC36N3UAXOK4QTWW46PGBWE24YXFMAX5YDU |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 44 | DIIISCO | Exact submitted wallet DIIISCOGT3OTYBKUBVJNW7YOC36N3UAXOK4QTWW46PGBWE24YXFMAX5YDU is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 210 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.143554 | USDC settled. |
| Unique payer accounts | 4 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 210 (100.0000%) · 0.143554 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 202 (96.1905%) · 0.063554 USDC (44.2718%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 6 · 0.001898 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-27 05:34:39 UTC / 2026-10-05 10:13:33 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/diiisco-7794ee7552-transactions.csv.gz) · [All endpoints](../evidence/diiisco-7794ee7552-endpoints.csv) · [Payer evidence](../evidence/diiisco-7794ee7552-payers.csv) · [Daily metrics](../evidence/diiisco-7794ee7552-daily.csv) · [Site and catalog data](../evidence/diiisco-7794ee7552-site-and-catalog.json)

**Flag — self-payments excluded:** 6 settlements / 0.001898 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 210 (100.0000%) | 0.143554 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| ULXEUXYTVTT7IJLU6XQ5FXKZ5CEENXF5VG7CSUGYWKUHCSKIZLCAKJEBWY | NO-LINK-DETECTED | 143 | 0.069567 (48.4605%) | 79% of gaps &lt; 60s |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 6 | 0.060000 (41.7961%) | throwaway wallet; created by vet402; pays 68 merchants |
| ZVQS5FEG56U37JSOKS52ZEJZLCFWQX3ONFFJZ4GF72FZWUIQXFJOVZLATQ | NO-LINK-DETECTED | 60 | 0.013986 (9.7427%) | 71% of gaps &lt; 60s |
| ZBDTJC4CY47KMXAM6SR3XLDT7T3DVIWK7DTP5OJRCIOE4MSCGAJCKYAV2Y | NO-LINK-DETECTED | 1 | 0.000001 (0.0007%) |  |

Top 4 of 4 payers; all in the payer CSV.

## Sub-cent settlements

202 (96.1905%) settlements · 0.063554 (44.2718%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| (not recorded) | https://diiisco.com/x402 | 139 (66.1905%) | 0.049562 (34.5250%) | 1 | 139 | 0 |
| (not recorded) | https://x402.diiisco.com/v1/chat/completions | 63 (30.0000%) | 0.013992 (9.7469%) | 3 | 63 | 0 |
| POST | https://x402.diiisco.com/v1/chat/completions | 8 (3.8095%) | 0.080000 (55.7282%) | 2 | 0 | 0 |

Top 3 of 3 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: diiisco.com, x402.diiisco.com.

Custom-domain candidates: diiisco.com, x402.diiisco.com. Registered email on a matching custom domain: **diiisco.com**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| diiisco.com | custom_domain_candidate | yes, cached | 2026-10-04T20:43:48.678000+00:00 | 0 |
| x402.diiisco.com | custom_domain_candidate | not established | 2026-10-02T19:12:08.529000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| diiisco.com | DIIISCO | not recorded | A decentralized AI compute network. Chat Locally, Earn Globally. Powered by Algorand. | https://diiisco.com/apple-touch-icon.png | https://diiisco.com/og-image.png | not recorded |
| x402.diiisco.com | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
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
| 2026-08-27 | 2 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-28 | 3 | 0.000076 | 1 | 3 | 0 (0.0000%) |
| 2026-08-29 | 189 | 0.063451 | 2 | 189 | 0 (0.0000%) |
| 2026-08-31 | 2 | 0.000005 | 1 | 2 | 0 (0.0000%) |
| 2026-09-27 | 2 | 0.010003 | 2 | 1 | 0 (0.0000%) |
| 2026-09-30 | 2 | 0.010003 | 2 | 1 | 0 (0.0000%) |
| 2026-10-01 | 2 | 0.010003 | 2 | 1 | 0 (0.0000%) |
| 2026-10-02 | 2 | 0.000004 | 2 | 2 | 0 (0.0000%) |
| 2026-10-03 | 2 | 0.010003 | 2 | 1 | 0 (0.0000%) |
| 2026-10-04 | 2 | 0.010003 | 2 | 1 | 0 (0.0000%) |
| 2026-10-05 | 2 | 0.010003 | 2 | 1 | 0 (0.0000%) |

Last 11 of 11 active days; all in the daily CSV.
