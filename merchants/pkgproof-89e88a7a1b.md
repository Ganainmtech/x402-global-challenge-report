# pkgproof — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 69).

## Identity and accounts

Merchant ID: `TkUzSEJTSDRNWkxDSjNHNVVQWUJUSUhH`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | NE3HBSH4MZLCJ3G5UPYBTIHGRCQ5M7K5N2ROWCBK6EQFR62FEROLBVQTTQ |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 69 | pkgproof | Exact submitted wallet NE3HBSH4MZLCJ3G5UPYBTIHGRCQ5M7K5N2ROWCBK6EQFR62FEROLBVQTTQ is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 36 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 1.800000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 36 (100.0000%) · 1.800000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-27 12:56:57 UTC / 2026-10-06 00:10:59 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/pkgproof-89e88a7a1b-transactions.csv.gz) · [All endpoints](../evidence/pkgproof-89e88a7a1b-endpoints.csv) · [Payer evidence](../evidence/pkgproof-89e88a7a1b-payers.csv) · [Daily metrics](../evidence/pkgproof-89e88a7a1b-daily.csv) · [Site and catalog data](../evidence/pkgproof-89e88a7a1b-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 36 (100.0000%) | 1.800000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| FUVVWN4M3RXBV2HDW5OWGXVPYZUOVNREIPGCWE2ORT57KPZF6MWXRRWRB4 | NO-LINK-DETECTED | 26 | 1.300000 (72.2222%) | throwaway wallet; same funder as merchant (hub) |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 10 | 0.500000 (27.7778%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://x402-algo.pkgproof.net/v1/verify | 36 (100.0000%) | 1.800000 (100.0000%) | 2 | 0 | 0 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: pkgproof.net, x402-algo.pkgproof.net.

Custom-domain candidates: pkgproof.net, x402-algo.pkgproof.net. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| pkgproof.net | custom_domain_candidate | yes, cached | 2026-10-04T20:43:35.458000+00:00 | 2 |
| x402-algo.pkgproof.net | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| pkgproof.net | pkgproof: check an npm package before it gets installed | pkgproof | Stolen publish tokens, install scripts that fire the moment you add a package, names one keystroke off the real thing. pkgproof reads an npm package before you install it and answers in one word: safe, caution, or block. $0.05 a check. | https://pkgproof.net/apple-touch-icon.png | not recorded | #f2f0e7 |
| x402-algo.pkgproof.net | pkgproof: check an npm package before it gets installed | pkgproof | Stolen publish tokens, install scripts that fire the moment you add a package, names one keystroke off the real thing. pkgproof reads an npm package before you install it and answers in one word: safe, caution, or block. $0.05 a check. | https://pkgproof.net/apple-touch-icon.png | not recorded | #f2f0e7 |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| pkgproof.net | x402 Discovery | not recorded | https://pkgproof.net/.well-known/x402 | not recorded |
| pkgproof.net | llms.txt | pkgproof | https://pkgproof.net/llms.txt | not recorded |
| x402-algo.pkgproof.net | x402 Discovery | not recorded | https://x402-algo.pkgproof.net/.well-known/x402 | not recorded |
| x402-algo.pkgproof.net | llms.txt | pkgproof | https://x402-algo.pkgproof.net/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 4 |
| Agent document types | ["llms-txt", "x402"] |
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
| 2026-08-27 | 4 | 0.200000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-29 | 2 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-08 | 3 | 0.150000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-19 | 2 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-24 | 2 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-25 | 13 | 0.650000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-27 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |

Last 16 of 16 active days; all in the daily CSV.
