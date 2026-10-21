# Pacific Data Commons — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 61).

## Identity and accounts

Merchant ID: `TE43NDVVQ0RRTkZJQkRZNkpGVzdGTksz`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | LN745UCDQNFIBDY6JFW7FNK333MADQZQVQFMCVR3GXXUTB52O2NYPZN3YY |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 61 | Pacific Data Commons | Exact submitted wallet LN745UCDQNFIBDY6JFW7FNK333MADQZQVQFMCVR3GXXUTB52O2NYPZN3YY is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 6,329 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 89.181000 | USDC settled. |
| Unique payer accounts | 4 | Distinct accounts that paid. |
| Synthetic-indicated | 6,291 (99.3996%) · 88.334000 USDC (99.0502%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 38 (0.6004%) · 0.847000 USDC (0.9498%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 1,906 (30.1153%) · 4.691000 USDC (5.2601%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 1,893 (29.9099%) · 4.674000 USDC (5.2410%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 695 (10.9812%) · 6.950000 USDC (7.7931%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-03 04:01:13 UTC / 2026-10-06 04:57:03 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/pacific-data-commons-b1507b3c4b-transactions.csv.gz) · [All endpoints](../evidence/pacific-data-commons-b1507b3c4b-endpoints.csv) · [Payer evidence](../evidence/pacific-data-commons-b1507b3c4b-payers.csv) · [Daily metrics](../evidence/pacific-data-commons-b1507b3c4b-daily.csv) · [Site and catalog data](../evidence/pacific-data-commons-b1507b3c4b-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 6,291 (99.3996%) | 88.334000 (99.0502%) |
| NO-LINK-DETECTED | 38 (0.6004%) | 0.847000 (0.9498%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| Q5XTALN45D32I572OZAVZ4FW6UYSW6A4FFAX4YOY6PP3YCD4JJJ3JQRYKI | MERCHANT-FUNDED | 6,291 | 88.334000 (99.0502%) | merchant sent 40.00 ALGO; merchant sent 87.52 USDC ×14 (99% of paid); throwaway wallet; 86% of gaps &lt; 60s |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 29 | 0.437000 (0.4900%) | throwaway wallet; created by vet402; pays 68 merchants |
| MUJMIBSK3SJBLERZWJ7UNG64C6NXO5LD62M7CL7LKK6SKEDXC4FVPZ4VSY | NO-LINK-DETECTED | 8 | 0.400000 (0.4485%) | throwaway wallet; pays 10 merchants |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 1 | 0.010000 (0.0112%) | pays 16 merchants |

Top 4 of 4 payers; all in the payer CSV.

## Sub-cent settlements

1,906 (30.1153%) settlements · 4.691000 (5.2601%) USDC. Paid by synthetic-indicated payers: 1,893 (29.9099%) settlements · 4.674000 (5.2410%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://pdc-pilot-endpoint.synergyblockchaintf.workers.dev/summary | 977 (15.4369%) | 9.770000 (10.9552%) | 2 | 0 | 967 |
| GET | https://pdcpilot-endpoint-production.up.railway.app/summary | 904 (14.2835%) | 9.040000 (10.1367%) | 2 | 0 | 903 |
| GET | https://pdcdirectory-api-production.up.railway.app/search | 580 (9.1642%) | 5.800000 (6.5036%) | 1 | 0 | 580 |
| GET | https://api.synergybcpacific.com/search | 574 (9.0694%) | 5.740000 (6.4363%) | 2 | 0 | 572 |
| GET | https://pdcdirectory-api-production.up.railway.app/finance/fx | 411 (6.4939%) | 0.411000 (0.4609%) | 1 | 411 | 411 |
| (not recorded) | (no host recorded) | 355 (5.6091%) | 3.550000 (3.9807%) | 1 | 0 | 355 |
| GET | (no host recorded) | 340 (5.3721%) | 3.400000 (3.8125%) | 1 | 0 | 340 |
| GET | https://pdcdirectory-api-production.up.railway.app/algorand/wallet-balance | 311 (4.9139%) | 1.555000 (1.7436%) | 1 | 311 | 311 |
| GET | https://api.synergybcpacific.com/pacific/weather | 207 (3.2707%) | 0.414000 (0.4642%) | 2 | 207 | 205 |
| GET | https://api.synergybcpacific.com/pacific/events | 203 (3.2075%) | 0.406000 (0.4553%) | 2 | 203 | 201 |
| GET | https://api.synergybcpacific.com/intelligence/pacific-travel | 202 (3.1917%) | 20.200000 (22.6506%) | 2 | 0 | 200 |
| GET | https://api.synergybcpacific.com/finance/fx | 201 (3.1759%) | 0.201000 (0.2254%) | 2 | 201 | 192 |
| GET | https://api.synergybcpacific.com/intelligence/pacific-brief | 197 (3.1127%) | 9.850000 (11.0450%) | 3 | 0 | 193 |
| GET | https://pdcdirectory-api-production.up.railway.app/pacific/weather | 194 (3.0653%) | 0.388000 (0.4351%) | 1 | 194 | 194 |
| GET | https://pdcdirectory-api-production.up.railway.app/pacific/events | 193 (3.0495%) | 0.386000 (0.4328%) | 1 | 193 | 193 |
| GET | https://api.synergybcpacific.com/algorand/wallet-balance | 186 (2.9389%) | 0.930000 (1.0428%) | 1 | 186 | 186 |
| GET | https://pdcdirectory-api-production.up.railway.app/intelligence/pacific-brief | 139 (2.1962%) | 6.950000 (7.7931%) | 2 | 0 | 133 |
| GET | https://pdcdirectory-api-production.up.railway.app/intelligence/pacific-travel | 96 (1.5168%) | 9.600000 (10.7646%) | 1 | 0 | 96 |
| (not recorded) | https://pdcdirectory-api-production.up.railway.app/search | 59 (0.9322%) | 0.590000 (0.6616%) | 1 | 0 | 59 |

Top 19 of 19 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.synergybcpacific.com, pdc-pilot-endpoint.synergyblockchaintf.workers.dev, pdcdirectory-api-production.up.railway.app, pdcpilot-endpoint-production.up.railway.app.

Custom-domain candidates: api.synergybcpacific.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.synergybcpacific.com | custom_domain_candidate | yes, cached | 2026-10-06T10:40:01.426000+00:00 | 1 |
| pdc-pilot-endpoint.synergyblockchaintf.workers.dev | hosting_provider_domain | not established | 2026-10-05T15:58:33.403000+00:00 | 0 |
| pdcdirectory-api-production.up.railway.app | hosting_provider_domain | not established | 2026-10-05T17:14:37.976000+00:00 | 0 |
| pdcpilot-endpoint-production.up.railway.app | hosting_provider_domain | not established | 2026-09-14T05:09:27.355000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.synergybcpacific.com | Pacific Data Commons — Synergy Blockchain Pacific | not recorded | Sovereign Pacific data directory — x402-gated endpoints for AI agents and researchers | not recorded | https://api.synergybcpacific.com/images/sbp-logo.png | not recorded |
| pdc-pilot-endpoint.synergyblockchaintf.workers.dev | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |
| pdcdirectory-api-production.up.railway.app | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |
| pdcpilot-endpoint-production.up.railway.app | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| api.synergybcpacific.com | x402 Discovery | not recorded | https://api.synergybcpacific.com/.well-known/x402 | Sovereign Pacific data directory — x402-gated endpoints for AI agents and researchers. Built on Algorand. Data sovereignty enforced — providers control their own infrastructure. |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 4 |
| Cached domain metadata count | 4 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 1 |
| Agent document types | ["x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 16 |
| Description count | 16 |
| Mime type count | 0 |
| Accepts count | 16 |
| Discovery count | 16 |
| Input documentation count | 16 |
| Output documentation count | 16 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-28 | 413 | 5.356000 | 2 | 222 | 412 (99.7579%) |
| 2026-08-29 | 411 | 5.564000 | 2 | 218 | 410 (99.7567%) |
| 2026-08-30 | 416 | 5.542000 | 2 | 222 | 415 (99.7596%) |
| 2026-08-31 | 33 | 0.412000 | 1 | 18 | 33 (100.0000%) |
| 2026-09-05 | 61 | 0.990000 | 1 | 24 | 61 (100.0000%) |
| 2026-09-06 | 195 | 3.412000 | 2 | 53 | 194 (99.4872%) |
| 2026-09-07 | 249 | 4.538000 | 2 | 79 | 248 (99.5984%) |
| 2026-09-08 | 233 | 4.127000 | 1 | 72 | 233 (100.0000%) |
| 2026-09-09 | 203 | 3.522000 | 1 | 61 | 203 (100.0000%) |
| 2026-09-10 | 206 | 3.648000 | 1 | 60 | 206 (100.0000%) |
| 2026-09-11 | 190 | 3.200000 | 1 | 52 | 190 (100.0000%) |
| 2026-09-12 | 171 | 3.037000 | 1 | 48 | 171 (100.0000%) |
| 2026-09-13 | 138 | 2.208000 | 1 | 28 | 138 (100.0000%) |
| 2026-09-14 | 145 | 2.332000 | 1 | 33 | 145 (100.0000%) |
| 2026-09-15 | 215 | 3.799000 | 1 | 69 | 215 (100.0000%) |
| 2026-09-16 | 203 | 3.535000 | 1 | 59 | 203 (100.0000%) |
| 2026-09-17 | 168 | 2.780000 | 1 | 44 | 168 (100.0000%) |
| 2026-09-18 | 138 | 2.428000 | 1 | 40 | 138 (100.0000%) |
| 2026-09-20 | 60 | 1.100000 | 1 | 20 | 60 (100.0000%) |
| 2026-09-21 | 70 | 1.100000 | 1 | 16 | 70 (100.0000%) |
| 2026-09-27 | 9 | 0.195000 | 2 | 3 | 2 (22.2222%) |
| 2026-09-28 | 9 | 0.195000 | 2 | 3 | 2 (22.2222%) |
| 2026-09-29 | 2 | 0.011000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 2 | 0.011000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 2 | 0.011000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-02 | 2 | 0.011000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 8 | 0.131000 | 2 | 5 | 6 (75.0000%) |
| 2026-10-04 | 30 | 0.452000 | 2 | 9 | 29 (96.6667%) |
| 2026-10-05 | 34 | 0.707000 | 2 | 14 | 32 (94.1176%) |
| 2026-10-06 | 4 | 0.031000 | 2 | 1 | 2 (50.0000%) |

Last 30 of 52 active days; all in the daily CSV.
