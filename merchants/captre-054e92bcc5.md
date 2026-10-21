# Captre — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 17).

## Identity and accounts

Merchant ID: `MjQ3Mk5FT0RHSk1PSlpWVUhKTDRHSTUz`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 2472NEODGJMOJZVUHJL4GI53BPZTFIXRP3ACIKTSKQCKCUNZ4NBZAMGTUQ |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 17 | Captre | Exact submitted wallet 2472NEODGJMOJZVUHJL4GI53BPZTFIXRP3ACIKTSKQCKCUNZ4NBZAMGTUQ is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 8 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.080000 | USDC settled. |
| Unique payer accounts | 4 | Distinct accounts that paid. |
| Synthetic-indicated | 8 (100.0000%) · 0.080000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-02 08:15:44 UTC / 2026-09-02 08:16:42 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/captre-054e92bcc5-transactions.csv.gz) · [All endpoints](../evidence/captre-054e92bcc5-endpoints.csv) · [Payer evidence](../evidence/captre-054e92bcc5-payers.csv) · [Daily metrics](../evidence/captre-054e92bcc5-daily.csv) · [Site and catalog data](../evidence/captre-054e92bcc5-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| FLEET | 8 (100.0000%) | 0.080000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| JSSU236QXDAB5P625I3FZFQ3ENVAERR3UGD6B5FZ7BWT5FYQDUYRQVQDRM | FLEET | 3 | 0.030000 (37.5000%) | fleet of 4 via BHYD7A…OPYM; throwaway wallet |
| 5HYMSH3KAZP7NAAQ4M6WJWX52M7HZ342G7KJGDJWZRMGDQDQBSVZYSGQJE | FLEET | 3 | 0.030000 (37.5000%) | fleet of 4 via BHYD7A…OPYM; throwaway wallet |
| BM2NR3VM7QV42XJNPUOBHGKPDPI7BPCZM2QHNQ6BRIRCW2DRGVXSLXRFCI | FLEET | 1 | 0.010000 (12.5000%) | fleet of 4 via BHYD7A…OPYM; throwaway wallet |
| BRLQ5PR27YEG3QV6LKF42IPOVPNQVMAPG36ZQAOMNUYS5KMGR2UYCAJCRA | FLEET | 1 | 0.010000 (12.5000%) | fleet of 4 via BHYD7A…OPYM; throwaway wallet |

Top 4 of 4 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://captre.onrender.com/attest | 7 (87.5000%) | 0.070000 (87.5000%) | 4 | 0 | 7 |
| POST | https://captre.onrender.com/revoke | 1 (12.5000%) | 0.010000 (12.5000%) | 1 | 0 | 1 |

Top 2 of 2 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: captre.onrender.com.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| captre.onrender.com | hosting_provider_domain | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| captre.onrender.com | Captre — On-Chain Attestation | Captre | First-claim proofs anchored on Algorand via x402. Permanent. Verifiable. Agent-native. | https://captre.onrender.com/static/logo.png | https://captre.onrender.com/static/og-image.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 0 |
| Agent document types | [] |
| Agent readiness evidence | catalog_only |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 2 |
| Description count | 2 |
| Mime type count | 0 |
| Accepts count | 2 |
| Discovery count | 2 |
| Input documentation count | 2 |
| Output documentation count | 2 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02 | 8 | 0.080000 | 4 | 0 | 8 (100.0000%) |

Last 1 of 1 active days; all in the daily CSV.
