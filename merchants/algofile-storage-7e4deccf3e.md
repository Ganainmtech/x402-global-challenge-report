# AlgoFile Storage — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `Nkw0TjRVNDNEWEZER0FBUENTRkRKUUhC`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 6L4N4U43DXFDGAAPCSFDJQHBIRQO37W3EX7MHKIHX5DQOAQOME6QWXD57M |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 23 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 114.063876 | USDC settled. |
| Unique payer accounts | 7 | Distinct accounts that paid. |
| Synthetic-indicated | 4 (17.3913%) · 0.048876 USDC (0.0428%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 19 (82.6087%) · 114.015000 USDC (99.9572%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 17 (73.9130%) · 0.017000 USDC (0.0149%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 2 (8.6957%) · 0.002000 USDC (0.0018%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 7 · 24.049876 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-13 08:30:26 UTC / 2026-10-06 00:02:27 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/algofile-storage-7e4deccf3e-transactions.csv.gz) · [All endpoints](../evidence/algofile-storage-7e4deccf3e-endpoints.csv) · [Payer evidence](../evidence/algofile-storage-7e4deccf3e-payers.csv) · [Daily metrics](../evidence/algofile-storage-7e4deccf3e-daily.csv) · [Site and catalog data](../evidence/algofile-storage-7e4deccf3e-site-and-catalog.json)

**Flag — self-payments excluded:** 7 settlements / 24.049876 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 19 (82.6087%) | 114.015000 (99.9572%) |
| SELF | 4 (17.3913%) | 0.048876 (0.0428%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| D7K45MKGWOLFLSDSXM6S2M2IFZZNH37EABQTF2R3ZCCZYMO5ESUJC6KSLY | NO-LINK-DETECTED | 1 | 48.000000 (42.0817%) | merchant sent 24.00 USDC ×1 (50% of paid) |
| M64PFBXTAIML7YKLGXXE2DSDXWQAHGFSP6HKNKVM3QCOENMQDLT2EFOP3E | NO-LINK-DETECTED | 1 | 30.000000 (26.3011%) |  |
| O4L32K7YXFJEYUSB6RZYHFZWOS6VWZDNS5GVSDDPP2HBCEQPJBDRTBDUBA | NO-LINK-DETECTED | 1 | 24.000000 (21.0408%) | merchant sent 3.00 USDC ×1 (13% of paid); rekeyed → DZWLDN…UDMU |
| 4VWG2M2BXOOBKC6DX2YOINRQV3Z53HRG3ZNTRUM33NQPDHNHTQQKRC2QBI | NO-LINK-DETECTED | 1 | 12.000000 (10.5204%) | merchant sent 12.00 USDC ×1 (100% of paid) |
| IYYLWNTA7QNG7SJOBKEGSBHQ3KENT6RKOWH4AMIBYR7Y2WF4B4KCIJ6WQQ | SELF | 4 | 0.048876 (0.0428%) | merchant's own address; created by merchant; merchant sent 110 ALGO; merchant sent 275 USDC ×38 (563059% of paid) |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 14 | 0.014000 (0.0123%) | throwaway wallet; created by vet402; pays 68 merchants |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 1 | 0.001000 (0.0009%) | pays 16 merchants |

Top 7 of 7 payers; all in the payer CSV.

## Sub-cent settlements

17 (73.9130%) settlements · 0.017000 (0.0149%) USDC. Paid by synthetic-indicated payers: 2 (8.6957%) settlements · 0.002000 (0.0018%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://api.algofile.io/api/v3/x402/bazaar/asset-storage-info | 15 (65.2174%) | 0.015000 (0.0132%) | 2 | 15 | 0 |
| POST | https://api.algofile.io/api/v3/purchases/x402-verify | 6 (26.0870%) | 114.046876 (99.9851%) | 5 | 0 | 2 |
| GET | https://api.algofile.io/api/v3/x402/bazaar/asset-info | 2 (8.6957%) | 0.002000 (0.0018%) | 1 | 2 | 2 |

Top 3 of 3 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: algofile.io, api.algofile.io.

Custom-domain candidates: algofile.io, api.algofile.io. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| algofile.io | custom_domain_candidate | yes, cached | 2026-10-05T18:30:19.840000+00:00 | 2 |
| api.algofile.io | custom_domain_candidate | yes, cached | 2026-10-06T06:29:21.483000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| algofile.io | AlgoFile Storage | not recorded | AlgoFile Integrated IPFS Storage Network & x402 Micro-payments | https://algofile.io/logo_mini.png | https://algofile.io/logo_mini.png | not recorded |
| api.algofile.io | AlgoFile Storage | AlgoFile Storage | AlgoFile Integrated IPFS Storage Network & x402 Micro-payment Protocol | https://algofile.io/logo_mini.png | https://algofile.io/logo_mini.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| algofile.io | A2A Agent Card | AlgoFile Storage | https://algofile.io/.well-known/agent-card.json | AlgoFile Integrated IPFS Storage Network & x402 Micro-payment Protocol |
| algofile.io | llms.txt | AlgoFile Storage | https://algofile.io/llms.txt | not recorded |
| api.algofile.io | llms.txt | AlgoFile Storage | https://api.algofile.io/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 3 |
| Agent document types | ["agent-card", "llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 9 |
| Description count | 9 |
| Mime type count | 9 |
| Accepts count | 9 |
| Discovery count | 9 |
| Input documentation count | 9 |
| Output documentation count | 8 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-13 | 4 | 0.048876 | 1 | 2 | 4 (100.0000%) |
| 2026-08-17 | 2 | 24.001000 | 2 | 1 | 0 (0.0000%) |
| 2026-09-10 | 1 | 12.000000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-12 | 1 | 48.000000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-16 | 1 | 30.000000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-27 | 3 | 0.003000 | 1 | 3 | 0 (0.0000%) |
| 2026-09-28 | 3 | 0.003000 | 1 | 3 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.001000 | 1 | 1 | 0 (0.0000%) |

Last 15 of 15 active days; all in the daily CSV.
