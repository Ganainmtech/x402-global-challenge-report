# ProofMesh — Pay-per-request evidence API — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `UFlWTTVNVFFXUUQzUkFKV0U2RTZER1RN`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | PYVM5MTQWQD3RAJWE6E6DGTMNL4NP5SWLXCPMUS7GV4POAEMUPWI52F3ZA |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 7 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.070000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 7 (100.0000%) · 0.070000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 1 · 0.010000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-14 09:27:04 UTC / 2026-08-15 14:15:20 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/proofmesh-pay-per-request-evidence-api-31ec07c128-transactions.csv.gz) · [All endpoints](../evidence/proofmesh-pay-per-request-evidence-api-31ec07c128-endpoints.csv) · [Payer evidence](../evidence/proofmesh-pay-per-request-evidence-api-31ec07c128-payers.csv) · [Daily metrics](../evidence/proofmesh-pay-per-request-evidence-api-31ec07c128-daily.csv) · [Site and catalog data](../evidence/proofmesh-pay-per-request-evidence-api-31ec07c128-site-and-catalog.json)

**Flag — self-payments excluded:** 1 settlements / 0.010000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 7 (100.0000%) | 0.070000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| I2XDPHLJDOSHCZ2YBBNHPQYKOXYICOZENK7AYO3NEGZZKGJAGZI5IGQDZ4 | NO-LINK-DETECTED | 7 | 0.070000 (100.0000%) | merchant sent 4.40 ALGO |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://proofmesh-x402.onrender.com/v1/evidence-packs | 5 (71.4286%) | 0.050000 (71.4286%) | 1 | 0 | 0 |
| POST | http://proofmesh-x402.onrender.com/v1/evidence-packs | 2 (28.5714%) | 0.020000 (28.5714%) | 1 | 0 | 0 |

Top 2 of 2 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: 3000-ilp13k626gz07n0oeamr2-9e46597e.us1.manus.computer, proofmesh-x402.onrender.com.

Custom-domain candidates: 3000-ilp13k626gz07n0oeamr2-9e46597e.us1.manus.computer. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| 3000-ilp13k626gz07n0oeamr2-9e46597e.us1.manus.computer | custom_domain_candidate | yes, cached | 2026-08-14T02:35:40.454000+00:00 | 2 |
| proofmesh-x402.onrender.com | hosting_provider_domain | yes, cached | 2026-10-06T00:39:18.871000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| 3000-ilp13k626gz07n0oeamr2-9e46597e.us1.manus.computer | ProofMesh — Pay-per-request evidence API | not recorded | Structured evidence packs, paid per query in USDC through x402 on Algorand. | not recorded | not recorded | not recorded |
| proofmesh-x402.onrender.com | ProofMesh — Pay-per-request evidence API | not recorded | Structured evidence packs, paid per query in USDC through x402 on Algorand. | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| 3000-ilp13k626gz07n0oeamr2-9e46597e.us1.manus.computer | AI Plugin | ProofMesh Evidence API | http://3000-ilp13k626gz07n0oeamr2-9e46597e.us1.manus.computer/.well-known/ai-plugin.json | Pay per structured evidence pack using x402. |
| 3000-ilp13k626gz07n0oeamr2-9e46597e.us1.manus.computer | llms.txt | ProofMesh Evidence API | http://3000-ilp13k626gz07n0oeamr2-9e46597e.us1.manus.computer/llms.txt | not recorded |
| proofmesh-x402.onrender.com | AI Plugin | ProofMesh Evidence API | https://proofmesh-x402.onrender.com/.well-known/ai-plugin.json | Pay per structured evidence pack using x402. |
| proofmesh-x402.onrender.com | llms.txt | ProofMesh Evidence API | https://proofmesh-x402.onrender.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 4 |
| Agent document types | ["ai-plugin", "llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 3 |
| Description count | 3 |
| Mime type count | 3 |
| Accepts count | 3 |
| Discovery count | 3 |
| Input documentation count | 3 |
| Output documentation count | 3 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-14 | 5 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-08-15 | 2 | 0.020000 | 1 | 0 | 0 (0.0000%) |

Last 2 of 2 active days; all in the daily CSV.
