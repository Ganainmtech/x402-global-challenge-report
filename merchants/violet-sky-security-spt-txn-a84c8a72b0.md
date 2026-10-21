# Violet Sky Security · SPT-Txn — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `RjRUTEVaTUJEU1FRVks3WlRERFdaWkw1`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 6QGSTZOH7EIVXKNHKJRJKNTZHQF3O7W6TPUPPLU7NOZYIVFQ5X2D65KGZU |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 1 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.020000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 1 (100.0000%) · 0.020000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-30 04:28:21 UTC / 2026-09-30 04:28:21 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/violet-sky-security-spt-txn-a84c8a72b0-transactions.csv.gz) · [All endpoints](../evidence/violet-sky-security-spt-txn-a84c8a72b0-endpoints.csv) · [Payer evidence](../evidence/violet-sky-security-spt-txn-a84c8a72b0-payers.csv) · [Daily metrics](../evidence/violet-sky-security-spt-txn-a84c8a72b0-daily.csv) · [Site and catalog data](../evidence/violet-sky-security-spt-txn-a84c8a72b0-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 1 (100.0000%) | 0.020000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| FDI3ZHZE442GRHMPV6M7T2BIB7N5PA7JDXSK5SN4OBOUUVNQJK7J4MWFMM | MERCHANT-FUNDED | 1 | 0.020000 (100.0000%) | created by merchant's creator; throwaway wallet |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://foss.violetskysecurity.com/x402/verify | 1 (100.0000%) | 0.020000 (100.0000%) | 1 | 0 | 1 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: foss.violetskysecurity.com.

Custom-domain candidates: foss.violetskysecurity.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| foss.violetskysecurity.com | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| foss.violetskysecurity.com | SPT-Txn: Privacy-Preserving FATF Travel Rule & Agentic Authorization [redacted] | Violet Sky Security · SPT-Txn | Open-source, blockchain-agnostic framework for the FATF Travel Rule (Recommendation 16), accountable AI-agent payments, and privacy-preserving compliance-gated RWA (ERC-3643-aligned, replay-safe). Zero-knowledge scoped disclosure, human-anchor escrow with lawful recovery, post-quantum hybrid (X25519 + ML-KEM-768) cryptography. | not recorded | https://foss.violetskysecurity.com/logo_lion.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| foss.violetskysecurity.com | llms.txt | SPT-Txn — Sovereign Policy Token Transactions | https://foss.violetskysecurity.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 1 |
| Agent document types | ["llms-txt"] |
| Agent readiness evidence | discovered_documents |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No catalog resources on included public domains."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 0 |
| Description count | 0 |
| Mime type count | 0 |
| Accepts count | 0 |
| Discovery count | 0 |
| Input documentation count | 0 |
| Output documentation count | 0 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-30 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |

Last 1 of 1 active days; all in the daily CSV.
