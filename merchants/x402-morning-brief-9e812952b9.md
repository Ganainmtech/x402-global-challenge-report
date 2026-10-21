# x402-morning-brief — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 7).

## Identity and accounts

Merchant ID: `S1hBRlVRTEZKSkg3U09ZNU1ZU08yUksz`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | KXAFUQLFJJH7SOY5MYSO2RK3A5LDKKFTZJV3GIEIX2HHKJDEYR7MX7KN4Q |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 7 | x402-morning-brief | Exact submitted wallet KXAFUQLFJJH7SOY5MYSO2RK3A5LDKKFTZJV3GIEIX2HHKJDEYR7MX7KN4Q is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 19 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.950000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 19 (100.0000%) · 0.950000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-10-01 06:00:50 UTC / 2026-10-06 00:11:04 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/x402-morning-brief-9e812952b9-transactions.csv.gz) · [All endpoints](../evidence/x402-morning-brief-9e812952b9-endpoints.csv) · [Payer evidence](../evidence/x402-morning-brief-9e812952b9-payers.csv) · [Daily metrics](../evidence/x402-morning-brief-9e812952b9-daily.csv) · [Site and catalog data](../evidence/x402-morning-brief-9e812952b9-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 19 (100.0000%) | 0.950000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| CXKRX6FVTUZ6NXT7A5LODOIWIJMMV7DVGNMNV5IOGQQTW2MMCFD6WS7J3M | NO-LINK-DETECTED | 13 | 0.650000 (68.4211%) | throwaway wallet; 50% of gaps &lt; 60s |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 6 | 0.300000 (31.5789%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://x402.darkhold.dev/v1/brief | 12 (63.1579%) | 0.600000 (63.1579%) | 2 | 0 | 0 |
| (not recorded) | https://x402.darkhold.dev/v1/brief | 7 (36.8421%) | 0.350000 (36.8421%) | 1 | 0 | 0 |

Top 2 of 2 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: x402.darkhold.dev.

Custom-domain candidates: x402.darkhold.dev. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| x402.darkhold.dev | custom_domain_candidate | not established | 2026-10-01T15:51:20.469000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| x402.darkhold.dev | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| x402.darkhold.dev | llms.txt | x402-agent-api | https://x402.darkhold.dev/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 0 |
| Agent document count | 1 |
| Agent document types | ["llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No cached descriptive homepage evidence on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-10-01 | 13 | 0.650000 | 2 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 2 | 0.100000 | 2 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |

Last 6 of 6 active days; all in the daily CSV.
