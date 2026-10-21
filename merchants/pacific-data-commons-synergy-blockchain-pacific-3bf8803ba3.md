# Pacific Data Commons — Synergy Blockchain Pacific — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `Q1pMTDJWU0hVVzdOQjY0QVk2SzNRU1lS`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | CZLL2VSHUW7NB64AY6K3QSYR2GFS3YECTKV3HM5LKPYKOAJZ2MVAKO6KFM |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 3 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.030000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 3 (100.0000%) · 0.030000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-23 05:10:41 UTC / 2026-09-28 01:32:57 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/pacific-data-commons-synergy-blockchain-pacific-3bf8803ba3-transactions.csv.gz) · [All endpoints](../evidence/pacific-data-commons-synergy-blockchain-pacific-3bf8803ba3-endpoints.csv) · [Payer evidence](../evidence/pacific-data-commons-synergy-blockchain-pacific-3bf8803ba3-payers.csv) · [Daily metrics](../evidence/pacific-data-commons-synergy-blockchain-pacific-3bf8803ba3-daily.csv) · [Site and catalog data](../evidence/pacific-data-commons-synergy-blockchain-pacific-3bf8803ba3-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 3 (100.0000%) | 0.030000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 2 | 0.020000 (66.6667%) | throwaway wallet; created by vet402; pays 68 merchants |
| 3VFHKZILWFWG6H6AUWMEN3OGAZ2W7YIONWAXLXVQTZSIHQX2MY7CGJSEFQ | NO-LINK-DETECTED | 1 | 0.010000 (33.3333%) |  |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://api.synergybcpacific.com/finance/samoa-cpi | 3 (100.0000%) | 0.030000 (100.0000%) | 2 | 0 | 0 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.synergybcpacific.com.

Custom-domain candidates: api.synergybcpacific.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.synergybcpacific.com | custom_domain_candidate | yes, cached | 2026-10-06T10:40:01.426000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.synergybcpacific.com | Pacific Data Commons — Synergy Blockchain Pacific | not recorded | Sovereign Pacific data directory — x402-gated endpoints for AI agents and researchers | not recorded | https://api.synergybcpacific.com/images/sbp-logo.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| api.synergybcpacific.com | x402 Discovery | not recorded | https://api.synergybcpacific.com/.well-known/x402 | Sovereign Pacific data directory — x402-gated endpoints for AI agents and researchers. Built on Algorand. Data sovereignty enforced — providers control their own infrastructure. |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
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
| Resource count | 1 |
| Description count | 1 |
| Mime type count | 0 |
| Accepts count | 1 |
| Discovery count | 1 |
| Input documentation count | 1 |
| Output documentation count | 1 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-23 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-27 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |

Last 3 of 3 active days; all in the daily CSV.
