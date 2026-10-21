# Boris Inc — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `R040Sk9MSVdKTUlZMkRFRkJVSkdNVE4y`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | GN4JOLIWJMIY2DEFBUJGMTN2XODXQSETXOKFT2X7ZUCZLEYPDNFZ47SUDE |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 3 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.030000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 3 (100.0000%) · 0.030000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-17 01:11:22 UTC / 2026-08-17 06:01:56 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/boris-inc-782eac513f-transactions.csv.gz) · [All endpoints](../evidence/boris-inc-782eac513f-endpoints.csv) · [Payer evidence](../evidence/boris-inc-782eac513f-payers.csv) · [Daily metrics](../evidence/boris-inc-782eac513f-daily.csv) · [Site and catalog data](../evidence/boris-inc-782eac513f-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 3 (100.0000%) | 0.030000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 3 | 0.030000 (100.0000%) | pays 16 merchants |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://algo.borisinc.com/trust | 3 (100.0000%) | 0.030000 (100.0000%) | 1 | 0 | 0 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: algo.borisinc.com.

Custom-domain candidates: algo.borisinc.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| algo.borisinc.com | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 3 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| algo.borisinc.com | Aegis on Algorand — the trust layer for the x402 agent economy | Boris Inc | Trust checks, free discovery and cross-chain routing for Algorand x402 payments. Gasless USDC settlement on Algorand mainnet via the GoPlausible facilitator, verified by purchase, not by self-report. | https://algo.borisinc.com/favicon.ico | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| algo.borisinc.com | A2A Agent Card | Aegis on Algorand | https://algo.borisinc.com/.well-known/agent-card.json | The trust and marketplace layer for the x402 agent economy, live on Algorand mainnet. Verify whether any x402 service actually delivers before you pay it; discover the Algorand x402 ecosystem; route payments across Algorand and Base; buy LLM cognition. Paid per call in USDC on Algorand (ASA 31566704) via the GoPlausible facilitator. No account, no API key. |
| algo.borisinc.com | x402 Discovery | not recorded | https://algo.borisinc.com/.well-known/x402 | not recorded |
| algo.borisinc.com | llms.txt | Aegis on Algorand (algo.borisinc.com) — trust + marketplace for the x402 agent economy | https://algo.borisinc.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 3 |
| Agent document types | ["agent-card", "llms-txt", "x402"] |
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
| 2026-08-17 | 3 | 0.030000 | 1 | 0 | 0 (0.0000%) |

Last 1 of 1 active days; all in the daily CSV.
