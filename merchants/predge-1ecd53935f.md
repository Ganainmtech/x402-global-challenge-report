# Predge — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 4).

## Identity and accounts

Merchant ID: `NUJOSURNSjZZU01aTkZYWDNFWVJQSEZa`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 5BNIDMJ6YSMZNFXX3EYRPHFZYCV6HWWI2L2CC5A6HXMHHDQERGVFRL3LK4 |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 4 | Predge | Exact submitted wallet 5BNIDMJ6YSMZNFXX3EYRPHFZYCV6HWWI2L2CC5A6HXMHHDQERGVFRL3LK4 is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 5 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.025000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 1 (20.0000%) · 0.005000 USDC (20.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 4 (80.0000%) · 0.020000 USDC (80.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 5 (100.0000%) · 0.025000 USDC (100.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 1 (20.0000%) · 0.005000 USDC (20.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-10-02 18:07:32 UTC / 2026-10-06 00:05:11 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/predge-1ecd53935f-transactions.csv.gz) · [All endpoints](../evidence/predge-1ecd53935f-endpoints.csv) · [Payer evidence](../evidence/predge-1ecd53935f-payers.csv) · [Daily metrics](../evidence/predge-1ecd53935f-daily.csv) · [Site and catalog data](../evidence/predge-1ecd53935f-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 1 (20.0000%) | 0.005000 (20.0000%) |
| NO-LINK-DETECTED | 4 (80.0000%) | 0.020000 (80.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 4 | 0.020000 (80.0000%) | throwaway wallet; created by vet402; pays 68 merchants |
| NZDID7KMZGUQYTUZ7JNV6HNMBVVDFE66RU2VYQ6Y2DG3A3XBVVVRZH7QWI | MERCHANT-FUNDED | 1 | 0.005000 (20.0000%) | created by merchant; merchant sent 0.5 ALGO; throwaway wallet |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

5 (100.0000%) settlements · 0.025000 (100.0000%) USDC. Paid by synthetic-indicated payers: 1 (20.0000%) settlements · 0.005000 (20.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://api.predge.io/v1/whales/latest | 5 (100.0000%) | 0.025000 (100.0000%) | 2 | 5 | 1 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.predge.io.

Custom-domain candidates: api.predge.io. Registered email on a matching custom domain: **predge.io**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.predge.io | custom_domain_candidate | not established | 2026-10-02T18:23:48.052000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.predge.io | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| api.predge.io | Agent Manifest | Predge | https://api.predge.io/.well-known/agent.json | A verification and dispute layer for agent payments. The acceptance test is hashed and chain-timestamped before the work exists; the verdict is written once, reverts on any rewrite, and carries an ed25519 attestation that anyone verifies offline against a published key without calling Predge. Because the test is deterministic, the verdict is backed by a slashable stablecoin bond: the contract recomputes the hash itself, so anyone can take the bond by proving a dishonest verdict on-chain. No arbi |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 0 |
| Agent document count | 1 |
| Agent document types | ["agent-json"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No cached descriptive homepage evidence on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-10-02 | 1 | 0.005000 | 1 | 1 | 1 (100.0000%) |
| 2026-10-03 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.005000 | 1 | 1 | 0 (0.0000%) |

Last 5 of 5 active days; all in the daily CSV.
