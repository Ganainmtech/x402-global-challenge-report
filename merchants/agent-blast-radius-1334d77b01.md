# Agent Blast Radius — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `NEhCTUlUS0lTMzZBU1ZKSkZPTjZYNUZP`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 4HBMITKIS36ASVJJFON6X5FOJ4TGDJBJAPOMLEBXGRAXGWWV74WSB7AO7E |
| Algorand | QVWVG355ZDC3ZP6TVEQEDUOGQJVKGKT53RB4VI3AQWABUUHU7V7WFFTHGY |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 11 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 1.100000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 5 (45.4545%) · 0.500000 USDC (45.4545%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 6 (54.5455%) · 0.600000 USDC (54.5455%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-30 19:10:35 UTC / 2026-10-06 00:11:10 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/agent-blast-radius-1334d77b01-transactions.csv.gz) · [All endpoints](../evidence/agent-blast-radius-1334d77b01-endpoints.csv) · [Payer evidence](../evidence/agent-blast-radius-1334d77b01-payers.csv) · [Daily metrics](../evidence/agent-blast-radius-1334d77b01-daily.csv) · [Site and catalog data](../evidence/agent-blast-radius-1334d77b01-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 6 (54.5455%) | 0.600000 (54.5455%) |
| SELF | 5 (45.4545%) | 0.500000 (45.4545%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| QVWVG355ZDC3ZP6TVEQEDUOGQJVKGKT53RB4VI3AQWABUUHU7V7WFFTHGY | SELF | 5 | 0.500000 (45.4545%) | merchant's own address; created by merchant; merchant sent 1.00 ALGO; throwaway wallet; 50% of gaps &lt; 60s |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 5 | 0.500000 (45.4545%) | throwaway wallet; created by vet402; pays 68 merchants |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 1 | 0.100000 (9.0909%) | throwaway wallet; created by vet402; pays 68 merchants |

Top 3 of 3 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://abr.kloudle.dev/v1/verifier-manifest | 11 (100.0000%) | 1.100000 (100.0000%) | 2 | 0 | 5 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: abr.kloudle.dev.

Custom-domain candidates: abr.kloudle.dev. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| abr.kloudle.dev | custom_domain_candidate | yes, cached | 2026-10-03T16:22:08.754000+00:00 | 3 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| abr.kloudle.dev | Agent Blast Radius · See what an agent running as you can reach. | Agent Blast Radius | Agent Blast Radius inventories the credentials an unsandboxed coding agent could read on your machine, then sells verifier manifests over x402 so the checks run locally. Secrets never leave the machine. | https://abr.kloudle.dev/apple-touch-icon.png | https://abr.kloudle.dev/og-image.png | #7d00ff |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| abr.kloudle.dev | A2A Agent Card | Agent Blast Radius | https://abr.kloudle.dev/.well-known/agent-card.json | Agent Blast Radius inventories the credentials an unsandboxed coding agent could read on your machine, then sells verifier manifests over x402 so the checks run locally. Secrets never leave the machine. The paid route sells a verifier command manifest for a scan shape (class counts only); it never executes checks or receives credentials. |
| abr.kloudle.dev | x402 Discovery | Agent Blast Radius | https://abr.kloudle.dev/.well-known/x402 | ABR CLI buys a local verifier command manifest for eligible secret findings. Secrets, profile names, paths, scan reports, and provider identities stay on the user's machine. |
| abr.kloudle.dev | llms.txt | Agent Blast Radius | https://abr.kloudle.dev/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 3 |
| Agent document types | ["agent-card", "llms-txt", "x402"] |
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
| 2026-09-30 | 4 | 0.400000 | 1 | 0 | 4 (100.0000%) |
| 2026-10-01 | 2 | 0.200000 | 2 | 0 | 1 (50.0000%) |
| 2026-10-02 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |

Last 7 of 7 active days; all in the daily CSV.
