# OyaPicks — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 64).

## Identity and accounts

Merchant ID: `Tk1WTE9OV1ZSWlVUVVNIT1ZKTFBRWlRL`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | NMVLONWVRZUTUSHOVJLPQZTKII4RNCHA33R5HRRWHBCHGMU4BLIKIJAVA4 |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 64 | OyaPicks | Exact submitted wallet NMVLONWVRZUTUSHOVJLPQZTKII4RNCHA33R5HRRWHBCHGMU4BLIKIJAVA4 is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 35 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.940000 | USDC settled. |
| Unique payer accounts | 4 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 35 (100.0000%) · 0.940000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-25 02:52:47 UTC / 2026-10-01 15:07:45 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/oyapicks-943f66c5ce-transactions.csv.gz) · [All endpoints](../evidence/oyapicks-943f66c5ce-endpoints.csv) · [Payer evidence](../evidence/oyapicks-943f66c5ce-payers.csv) · [Daily metrics](../evidence/oyapicks-943f66c5ce-daily.csv) · [Site and catalog data](../evidence/oyapicks-943f66c5ce-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 35 (100.0000%) | 0.940000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 17 | 0.480000 (51.0638%) | throwaway wallet; created by vet402; pays 68 merchants |
| ZKFACAZATPUUYUXVVVE7QWMMZTSMLGQVA4G4QKW7D2UI7FCIFE3QB2SHRE | NO-LINK-DETECTED | 6 | 0.160000 (17.0213%) | created by Agent402; pays 4 merchants |
| GJHN3ARMWCNGZ5KTRJPBN44SUD2ASEE2A4PL6ZYTOGBWTZV2QK75RCNZUM | NO-LINK-DETECTED | 6 | 0.160000 (17.0213%) | merchant sent 1.00 ALGO; merchant sent 3.00 USDC ×2 (1875% of paid) |
| XALLOLSAOW5HVPCKK6NSTUTPVFWB3K6MNFKDXHMXULFYGN6GYXT4UU4UXA | NO-LINK-DETECTED | 6 | 0.140000 (14.8936%) | throwaway wallet; 100% of gaps &lt; 60s; pays 9 merchants |

Top 4 of 4 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://oyapicks.app/api/x402/closing-soon-algo | 8 (22.8571%) | 0.160000 (17.0213%) | 3 | 0 | 0 |
| GET | https://oyapicks.app/api/x402/new-markets-algo | 5 (14.2857%) | 0.150000 (15.9574%) | 3 | 0 | 0 |
| GET | https://oyapicks.app/api/x402/arbitrage-algo | 4 (11.4286%) | 0.200000 (21.2766%) | 2 | 0 | 0 |
| GET | https://oyapicks.app/api/x402/single-market-algo | 4 (11.4286%) | 0.040000 (4.2553%) | 2 | 0 | 0 |
| GET | https://oyapicks.app/api/x402/alpha-book | 3 (8.5714%) | 0.090000 (9.5745%) | 2 | 0 | 0 |
| GET | https://oyapicks.app/api/x402/movers-algo | 3 (8.5714%) | 0.090000 (9.5745%) | 2 | 0 | 0 |
| GET | https://oyapicks.app/api/x402/resolutions-algo | 3 (8.5714%) | 0.090000 (9.5745%) | 2 | 0 | 0 |
| GET | https://oyapicks.app/api/x402/search-algo | 3 (8.5714%) | 0.060000 (6.3830%) | 2 | 0 | 0 |
| GET | https://oyapicks.app/api/x402/probability-history-algo | 1 (2.8571%) | 0.030000 (3.1915%) | 1 | 0 | 0 |
| GET | https://oyapicks.app/api/x402/volume-spikes-algo | 1 (2.8571%) | 0.030000 (3.1915%) | 1 | 0 | 0 |

Top 10 of 10 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: oyapicks.app.

Custom-domain candidates: oyapicks.app. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| oyapicks.app | custom_domain_candidate | yes, cached | 2026-10-04T13:58:04.154000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| oyapicks.app | OyaPicks · Verified Track Record | OyaPicks | An AI that bets prediction markets in public, every call logged before the outcome. Its live market data is payable per call over x402. | https://oyapicks.app/apple-icon.png | https://oyapicks.app/opengraph-image.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| oyapicks.app | x402 Discovery | OyaPicks | https://oyapicks.app/.well-known/x402 | Cross-venue prediction-market data for AI agents, payable per request over x402. Normalized market data from Polymarket and Alpha Arcade, backed by a public verifiable track record at https://oyapicks.app/track. |
| oyapicks.app | llms.txt | OyaPicks | https://oyapicks.app/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 2 |
| Agent document types | ["llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 11 |
| Description count | 11 |
| Mime type count | 11 |
| Accepts count | 11 |
| Discovery count | 11 |
| Input documentation count | 11 |
| Output documentation count | 11 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-07-25 | 6 | 0.160000 | 1 | 0 | 0 (0.0000%) |
| 2026-07-28 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-10 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-22 | 3 | 0.070000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-27 | 7 | 0.210000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 8 | 0.260000 | 2 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.020000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 7 | 0.160000 | 2 | 0 | 0 (0.0000%) |

Last 9 of 9 active days; all in the daily CSV.
