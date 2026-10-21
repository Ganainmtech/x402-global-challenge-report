# Authen — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 98).

## Identity and accounts

Merchant ID: `RTY0QlFJT1hLVFQ0QlZNSUZZMlM1V1gz`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | E64BQIOXKTT4BVMIFY2S5WX337FT6MLF66UPZEUPDYAKT4QIFOXXQCR24Q |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 98 | Authen | Exact submitted wallet E64BQIOXKTT4BVMIFY2S5WX337FT6MLF66UPZEUPDYAKT4QIFOXXQCR24Q is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 9 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 1.050000 | USDC settled. |
| Unique payer accounts | 8 | Distinct accounts that paid. |
| Synthetic-indicated | 7 (77.7778%) · 0.550000 USDC (52.3810%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 2 (22.2222%) · 0.500000 USDC (47.6190%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-13 23:27:38 UTC / 2026-09-16 11:19:40 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/authen-a2b8f65e8e-transactions.csv.gz) · [All endpoints](../evidence/authen-a2b8f65e8e-endpoints.csv) · [Payer evidence](../evidence/authen-a2b8f65e8e-payers.csv) · [Daily metrics](../evidence/authen-a2b8f65e8e-daily.csv) · [Site and catalog data](../evidence/authen-a2b8f65e8e-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| FLEET | 7 (77.7778%) | 0.550000 (52.3810%) |
| NO-LINK-DETECTED | 2 (22.2222%) | 0.500000 (47.6190%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| RMQUVK4QHYVUGSYDEAHOEV6PPVOZTEP6543I35QIVBBHRQ3PQ3E5ECBVH4 | NO-LINK-DETECTED | 1 | 0.250000 (23.8095%) | throwaway wallet |
| FIO4JQAXRZL3XVSZOA7OZZSID4A572WCEJESNN5LEJBJE5V4M6CZRWR33U | NO-LINK-DETECTED | 1 | 0.250000 (23.8095%) | throwaway wallet |
| HR4GEKYBAK64JSQHH3YV5AHYWTE7WP4XYBYXRXDBBU6FXELUHAU7ILZEHU | FLEET | 2 | 0.200000 (19.0476%) | fleet of 6 via CYRMW3…R5EQ; throwaway wallet |
| 5X5GWGC4EZV5ETQASSEYD3M3E6EAG62T255QHF4YAQBV67QJUA5TELVF5I | FLEET | 1 | 0.150000 (14.2857%) | fleet of 6 via CYRMW3…R5EQ; throwaway wallet |
| IBDY7UHBYETD5AEDF4OUGSEXMTOHGBA7SI5XHC6VDSHBGUQL3PE7HIE55A | FLEET | 1 | 0.050000 (4.7619%) | fleet of 6 via CYRMW3…R5EQ; throwaway wallet |
| MWQZ2EOR2FBTVG5OELDGJGGAZUSLUB2BPLCROVODXT43WJLZOUDIZLVC6M | FLEET | 1 | 0.050000 (4.7619%) | fleet of 6 via CYRMW3…R5EQ; throwaway wallet |
| VY45NWGUWV6EM73TUQ5MSLH5ZRFT6CVGLFUMOYASTTKQAMWNRELQW64HRA | FLEET | 1 | 0.050000 (4.7619%) | fleet of 6 via CYRMW3…R5EQ; throwaway wallet |
| IXXR7AQFR46DNI7U6HCO5YFQPORPMG7ORQRJMZWMFEG7X6V2DNSNF3UTIE | FLEET | 1 | 0.050000 (4.7619%) | fleet of 6 via CYRMW3…R5EQ; throwaway wallet |

Top 8 of 8 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://authen.hvym.link/api/v1/notarize | 5 (55.5556%) | 0.250000 (23.8095%) | 5 | 0 | 5 |
| POST | https://authen.hvym.link/api/v1/c2pa/sign | 2 (22.2222%) | 0.300000 (28.5714%) | 2 | 0 | 2 |
| POST | https://authen.hvym.link/api/v1/manifest | 2 (22.2222%) | 0.500000 (47.6190%) | 2 | 0 | 0 |

Top 3 of 3 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: authen.hvym.link.

Custom-domain candidates: authen.hvym.link. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| authen.hvym.link | custom_domain_candidate | yes, cached | 2026-10-05T06:05:13.182000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| authen.hvym.link | Authen — verifiable provenance for agents | Authen | Notarize any bytes over x402 on Algorand mainnet and get a signed, timestamped attestation checkable offline by anyone. Verification is free, forever. | https://authen.hvym.link/logo.png | https://authen.hvym.link/og-image.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | True |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 0 |
| Agent document types | [] |
| Agent readiness evidence | catalog_only |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-08-13 | 1 | 0.050000 | 1 | 0 | 1 (100.0000%) |
| 2026-08-14 | 5 | 0.450000 | 4 | 0 | 5 (100.0000%) |
| 2026-08-15 | 1 | 0.050000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-01 | 1 | 0.250000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-16 | 1 | 0.250000 | 1 | 0 | 0 (0.0000%) |

Last 5 of 5 active days; all in the daily CSV.
