# Earnest — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 53).

## Identity and accounts

Merchant ID: `MklaVkRIMzZRRlBJUUZLT0JLSEFONENS`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 2IZVDH36QFPIQFKOBKHAN4CREL4K77PXU6HQ5RMOF5E47DPE5XZ37Q772I |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 53 | Earnest | Exact submitted wallet 2IZVDH36QFPIQFKOBKHAN4CREL4K77PXU6HQ5RMOF5E47DPE5XZ37Q772I is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 11 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 55.000000 | USDC settled. |
| Unique payer accounts | 9 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 11 (100.0000%) · 55.000000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-20 07:42:37 UTC / 2026-10-05 15:27:23 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/earnest-23b6cd300b-transactions.csv.gz) · [All endpoints](../evidence/earnest-23b6cd300b-endpoints.csv) · [Payer evidence](../evidence/earnest-23b6cd300b-payers.csv) · [Daily metrics](../evidence/earnest-23b6cd300b-daily.csv) · [Site and catalog data](../evidence/earnest-23b6cd300b-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 11 (100.0000%) | 55.000000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| XCDSCS22QC62YZANPQOLWEWDREZMMKPTHJLLLYWWYRJ7VR25TFV23PSZIA | NO-LINK-DETECTED | 2 | 10.000000 (18.1818%) | merchant sent 5.00 USDC ×1 (50% of paid) |
| HDMHEFFRJWI7PCEKYL65OBR326J6O3UE5NXGCSVXG44TIFA6HB37S6HG5A | NO-LINK-DETECTED | 2 | 10.000000 (18.1818%) | merchant sent 5.00 USDC ×1 (50% of paid) |
| HSRJS5CUK76BTQS64YKUKRWETLJOUR6QABLHTLDNLBUQ6GCG4HPJN4JETE | NO-LINK-DETECTED | 1 | 5.000000 (9.0909%) | throwaway wallet |
| 6GU5QDTRQEVIH64R6Q6QQ2XP3FABJQXFUETS6OZ6XT6MN3I7YPNFVSUR3I | NO-LINK-DETECTED | 1 | 5.000000 (9.0909%) | throwaway wallet |
| Z4COI2Z2XCEDUKFQPKQIUKTAVLPNNW5MMT7DJCDS5W2OIXPG34DRLYGKQM | NO-LINK-DETECTED | 1 | 5.000000 (9.0909%) | throwaway wallet |
| L4XYNMUU636VR2XZU6IDNUMZ24OCRYW7BCSHSFSLRXRCJVRVJHJMQVGUCE | NO-LINK-DETECTED | 1 | 5.000000 (9.0909%) | throwaway wallet |
| USDR3YYWMHSV2L574JDELKPBZP7SM44RRFN5HM54XVLPGTWOLKLFOLAJLA | NO-LINK-DETECTED | 1 | 5.000000 (9.0909%) | throwaway wallet |
| W755NF4Z22M5G73J7VVP7MZLMUUAZIXBSFPV7WSLEHC6VFFEDMKOECEHEA | NO-LINK-DETECTED | 1 | 5.000000 (9.0909%) | throwaway wallet |
| 7KUSUVH2A4C7GQWJALJZP6ZY3FZ3WTCMTFLT3Q6FJNGMNUT4WAEBAVYQZE | NO-LINK-DETECTED | 1 | 5.000000 (9.0909%) | throwaway wallet |

Top 9 of 9 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://earnest.lxfoundry.ai/index | 11 (100.0000%) | 55.000000 (100.0000%) | 9 | 0 | 0 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: earnest.lxfoundry.ai.

Custom-domain candidates: earnest.lxfoundry.ai. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| earnest.lxfoundry.ai | custom_domain_candidate | yes, cached | 2026-10-05T18:31:36.550000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| earnest.lxfoundry.ai | Earnest | not recorded | not recorded | https://earnest.lxfoundry.ai/app/favicon.svg | not recorded | #f4efe6 |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
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
| Gaps | ["No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-09-20 | 1 | 5.000000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-21 | 1 | 5.000000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 1 | 5.000000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 2 | 10.000000 | 2 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 5.000000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 5.000000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 5.000000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 3 | 15.000000 | 3 | 0 | 0 (0.0000%) |

Last 8 of 8 active days; all in the daily CSV.
