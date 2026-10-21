# AuPM — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 49).

## Identity and accounts

Merchant ID: `SUxHUUxHUUVGQUtPNVVQSkVGVFpYUEtW`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | ILGQLGQEFAKO5UPJEFTZXPKV7NLI6OJHG5NOLYPAOQHGUEG3EUMO6P6WKU |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 49 | AuPM | Exact submitted wallet ILGQLGQEFAKO5UPJEFTZXPKV7NLI6OJHG5NOLYPAOQHGUEG3EUMO6P6WKU is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 17 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.456000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 17 (100.0000%) · 0.456000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 1 (5.8824%) · 0.001000 USDC (0.2193%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 1 (5.8824%) · 0.001000 USDC (0.2193%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-30 16:14:14 UTC / 2026-10-05 11:46:50 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/aupm-606d21cdf6-transactions.csv.gz) · [All endpoints](../evidence/aupm-606d21cdf6-endpoints.csv) · [Payer evidence](../evidence/aupm-606d21cdf6-payers.csv) · [Daily metrics](../evidence/aupm-606d21cdf6-daily.csv) · [Site and catalog data](../evidence/aupm-606d21cdf6-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 17 (100.0000%) | 0.456000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| APMCP2ZG2JPXT72FT2H3YJUSHBFOBB7RHLXFZBC5RNA53WZS5NPLS56EKM | MERCHANT-FUNDED | 17 | 0.456000 (100.0000%) | created by merchant's creator; throwaway wallet |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

1 (5.8824%) settlements · 0.001000 (0.2193%) USDC. Paid by synthetic-indicated payers: 1 (5.8824%) settlements · 0.001000 (0.2193%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://aupm.fyi/v1/attest/lockfile | 16 (94.1176%) | 0.455000 (99.7807%) | 1 | 0 | 16 |
| POST | http://aupm.fyi/v1/attest/lockfile | 1 (5.8824%) | 0.001000 (0.2193%) | 1 | 1 | 1 |

Top 2 of 2 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: aupm.fyi.

Custom-domain candidates: aupm.fyi. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| aupm.fyi | custom_domain_candidate | yes, cached | 2026-10-04T10:01:09.817000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| aupm.fyi | AuPM: human-reviewed npm packages | AuPM | AuPM turns human code review into a paid, verifiable, on-chain-anchored public good on Algorand. $0.001 per reviewed package. Target split 30/10/20/25/10/5. In the MVP: 30% to the auditor, 70% to the operator until the other roles launch. | https://aupm.fyi/.well-known/aupm-apple-touch-icon.png | https://aupm.fyi/.well-known/aupm-og.png | #be8923 |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| aupm.fyi | x402 Discovery | AuPM | https://aupm.fyi/.well-known/x402 | AuPM turns human code review into a paid, verifiable, on-chain-anchored public good on Algorand. $0.001 per reviewed package. Target split 30/10/20/25/10/5. In the MVP: 30% to the auditor, 70% to the operator until the other roles launch. |
| aupm.fyi | llms.txt | AuPM | https://aupm.fyi/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
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
| 2026-09-30 | 1 | 0.001000 | 1 | 1 | 1 (100.0000%) |
| 2026-10-02 | 12 | 0.335000 | 1 | 0 | 12 (100.0000%) |
| 2026-10-04 | 3 | 0.090000 | 1 | 0 | 3 (100.0000%) |
| 2026-10-05 | 1 | 0.030000 | 1 | 0 | 1 (100.0000%) |

Last 4 of 4 active days; all in the daily CSV.
