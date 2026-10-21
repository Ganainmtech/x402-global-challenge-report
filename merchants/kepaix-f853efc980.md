# KepAIx — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 97).

## Identity and accounts

Merchant ID: `MlUzUVlUUU9IUDRTTURVR1dORkxORlFQ`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 2U3QYTQOHP4SMDUGWNFLNFQPRK2DFTZPFV7P76GV6ENXITYVXOMRAGDVEE |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 97 | KepAIx | Exact submitted wallet 2U3QYTQOHP4SMDUGWNFLNFQPRK2DFTZPFV7P76GV6ENXITYVXOMRAGDVEE is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 77 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 21.380000 | USDC settled. |
| Unique payer accounts | 5 | Distinct accounts that paid. |
| Synthetic-indicated | 65 (84.4156%) · 1.180000 USDC (5.5192%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 12 (15.5844%) · 20.200000 USDC (94.4808%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 7 · 0.380000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-22 14:00:50 UTC / 2026-10-06 00:09:58 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/kepaix-f853efc980-transactions.csv.gz) · [All endpoints](../evidence/kepaix-f853efc980-endpoints.csv) · [Payer evidence](../evidence/kepaix-f853efc980-payers.csv) · [Daily metrics](../evidence/kepaix-f853efc980-daily.csv) · [Site and catalog data](../evidence/kepaix-f853efc980-site-and-catalog.json)

**Flag — self-payments excluded:** 7 settlements / 0.380000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| FLEET | 33 (42.8571%) | 0.500000 (2.3386%) |
| MERCHANT-FUNDED | 32 (41.5584%) | 0.680000 (3.1805%) |
| NO-LINK-DETECTED | 12 (15.5844%) | 20.200000 (94.4808%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| 67TOJOIU72VPBVOI4RYLE7OESBGEWS7UTCY32FQDPM76BT5LAFOSIXJSBQ | NO-LINK-DETECTED | 2 | 20.000000 (93.5454%) | merchant sent 0.6 USDC ×6 (3.0% of paid); throwaway wallet; rekeyed → DSJQTJ…T6FQ |
| 4CJ2S3IAQJN7IIPP2TMBHDROXHNN3IPI6ANC76IRPAQZPITZLZWN4JF7C4 | MERCHANT-FUNDED | 30 | 0.650000 (3.0402%) | created by merchant's creator |
| P7SH6M65RYJ2FYL3YND4O27BPKRETF53OQZK4KLMAP5LR6UWVMEROUJCB4 | FLEET | 33 | 0.500000 (2.3386%) | funded by linked payer YLTZFD…TKQA |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 10 | 0.200000 (0.9355%) | throwaway wallet; created by vet402; pays 68 merchants |
| YLTZFDK7L5BNKNSVZKIQ3RX7AO4VJXD6JRRM5FZHI3WO4D45FUXZDJTKQA | MERCHANT-FUNDED | 2 | 0.030000 (0.1403%) | created by merchant's creator |

Top 5 of 5 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://kepaix.com/api/x402-atlas.php | 45 (58.4416%) | 0.900000 (4.2095%) | 4 | 0 | 35 |
| GET | https://kepaix.com/api/x402-market-regime.php | 20 (25.9740%) | 0.200000 (0.9355%) | 2 | 0 | 20 |
| GET | https://kepaix.com/api/x402-main-brain.php | 6 (7.7922%) | 0.060000 (0.2806%) | 3 | 0 | 6 |
| GET | https://kepaix.com/api/x402-atlas-human-report.php | 2 (2.5974%) | 0.200000 (0.9355%) | 1 | 0 | 2 |
| (not recorded) | https://kepaix.com/api/x402-publisher-credits.php | 2 (2.5974%) | 10.010000 (46.8195%) | 2 | 0 | 1 |
| (not recorded) | https://kepaix.com/api/x402-publisher-widget.php | 2 (2.5974%) | 10.010000 (46.8195%) | 2 | 0 | 1 |

Top 6 of 6 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: kepaix.com.

Custom-domain candidates: kepaix.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| kepaix.com | custom_domain_candidate | yes, cached | 2026-10-06T00:16:08.867000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| kepaix.com | x402 Market Intelligence APIs For AI Agents & Publishers \| KepAIx | KepAIx | KepAIx provides x402-enabled educational market intelligence APIs and publisher infrastructure for developers, AI agents, website owners, and machine-to-machine applications on Algorand. | https://kepaix.com/images/apple-touch-icon.png | https://kepaix.com/images/kepaix_share_1200x630_v3.png | #020406 |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| kepaix.com | llms.txt | KepAIx | https://kepaix.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 1 |
| Agent document types | ["llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-07-22 | 10 | 0.150000 | 1 | 0 | 10 (100.0000%) |
| 2026-07-23 | 8 | 0.090000 | 1 | 0 | 8 (100.0000%) |
| 2026-07-26 | 1 | 0.010000 | 1 | 0 | 1 (100.0000%) |
| 2026-07-27 | 33 | 0.560000 | 3 | 0 | 33 (100.0000%) |
| 2026-07-28 | 7 | 0.120000 | 1 | 0 | 7 (100.0000%) |
| 2026-08-01 | 4 | 0.050000 | 1 | 0 | 4 (100.0000%) |
| 2026-08-04 | 2 | 20.000000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-11 | 2 | 0.200000 | 1 | 0 | 2 (100.0000%) |
| 2026-09-27 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |

Last 18 of 18 active days; all in the daily CSV.
