# Canix402 — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 95).

## Identity and accounts

Merchant ID: `M1kyVjZPRFVWVUdNNFRYT0VYWTY1WUxN`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 3Y2V6ODUVUGM4TXOEXY65YLMKMVLG4PB3GSOXDCJDE4X5YQA5JA3P2FHAQ |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 95 | Canix402 | Exact submitted wallet 3Y2V6ODUVUGM4TXOEXY65YLMKMVLG4PB3GSOXDCJDE4X5YQA5JA3P2FHAQ is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 2,375 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 52.441000 | USDC settled. |
| Unique payer accounts | 18 | Distinct accounts that paid. |
| Synthetic-indicated | 1,079 (45.4316%) · 22.175000 USDC (42.2856%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 1,296 (54.5684%) · 30.266000 USDC (57.7144%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 655 (27.5789%) · 2.691000 USDC (5.1315%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 405 (17.0526%) · 1.485000 USDC (2.8318%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 71 (2.9895%) · 1.395000 USDC (2.6601%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-21 20:16:36 UTC / 2026-10-06 09:05:08 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/canix402-94af72cdf3-transactions.csv.gz) · [All endpoints](../evidence/canix402-94af72cdf3-endpoints.csv) · [Payer evidence](../evidence/canix402-94af72cdf3-payers.csv) · [Daily metrics](../evidence/canix402-94af72cdf3-daily.csv) · [Site and catalog data](../evidence/canix402-94af72cdf3-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 1,079 (45.4316%) | 22.175000 (42.2856%) |
| NO-LINK-DETECTED | 1,296 (54.5684%) | 30.266000 (57.7144%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| 7F3C3BUPN3WICWMFZTQVBRIFIDWUP4OICUQ3IHT6BP27JG7TPDPV27XHTU | NO-LINK-DETECTED | 887 | 24.025000 (45.8134%) | merchant sent 5.00 USDC ×2 (21% of paid); 93% of gaps &lt; 60s |
| KPEZM2DSFHOOHG7RPDECCBTD6FRN2LPSSRJMMFVCFSIHGES4BXBJHPUBVQ | MERCHANT-FUNDED | 1,074 | 22.004000 (41.9595%) | created by merchant's creator; merchant sent 36.00 USDC ×5 (164% of paid); 67% of gaps &lt; 60s |
| M6JQNJVX32HEN2LS5W2WX2PMSXPDHHKADVUATIQ5KQIVVVHSVILQNOS62A | NO-LINK-DETECTED | 299 | 4.990000 (9.5155%) | throwaway wallet; is AgentMesh's address; pays 5 merchants |
| XALLOLSAOW5HVPCKK6NSTUTPVFWB3K6MNFKDXHMXULFYGN6GYXT4UU4UXA | NO-LINK-DETECTED | 33 | 0.345000 (0.6579%) | throwaway wallet; pays 9 merchants |
| 5YCWR662A5HIOFYYS2CTIHHYBCIXESVLAOVLZ7CL27PK5SKBROCSRFIJMA | NO-LINK-DETECTED | 1 | 0.250000 (0.4767%) | merchant sent 4.00 USDC ×1 (1600% of paid) |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 30 | 0.236000 (0.4500%) | throwaway wallet; 62% of gaps &lt; 60s; created by vet402; pays 68 merchants |
| 65GJKPMEYLR2C2GHFIAUKF2CFDE6IXDB3LUTOVJ424LBMMEWJ6UXCHCBZQ | MERCHANT-FUNDED | 5 | 0.171000 (0.3261%) | created by merchant's creator |
| ZKFACAZATPUUYUXVVVE7QWMMZTSMLGQVA4G4QKW7D2UI7FCIFE3QB2SHRE | NO-LINK-DETECTED | 14 | 0.140000 (0.2670%) | 92% of gaps &lt; 60s; created by Agent402; pays 4 merchants |
| YYLLDAUAUV3QPBFDIZ7HO4NYLAH7V3KMUMSDT6HDJVMFO5DV33ELFG7VRM | NO-LINK-DETECTED | 11 | 0.080000 (0.1526%) |  |
| LP6QRRBRDTDSP4HF7CSPWJV4AG4QWE437OYHGW7K5Y7DETKCSK5H3HCA7Q | NO-LINK-DETECTED | 5 | 0.050000 (0.0953%) | rekeyed → JKFVZM…Z34Y; pays 3 merchants |
| K4HCGHT7IW5QSDUQL2W3UVFPIQI4UELUIKA7PH2XFIINMFSNZG3HQVZSEM | NO-LINK-DETECTED | 4 | 0.040000 (0.0763%) | pays 2 merchants |
| 77VYJXL37J3JXQOI3X72ULXMH75RQUZIS3Q6ADJB2PXGA7AJ4UOUZWQGR4 | NO-LINK-DETECTED | 3 | 0.030000 (0.0572%) | throwaway wallet; pays 2 merchants |
| HFHI5MF4C55AYUSQ2JD2AFYMUHWBNSE3SGU6N2YZ5ET5FUZD5YHZHXSWXU | NO-LINK-DETECTED | 2 | 0.020000 (0.0381%) | throwaway wallet; is Stelar Digital's address; pays 2 merchants |
| 57F2QR2RAI5LYJ2F4ZIC6AJEIINS62WGA7TLSILCAZOZHS7CLTPFU6QQVU | NO-LINK-DETECTED | 2 | 0.020000 (0.0381%) | throwaway wallet; pays 4 merchants |
| OZ3KMLALTO67BZLYLCZOT7IJBGN7JTO5A3MJHI2267EKQDASFKS52KU6VY | NO-LINK-DETECTED | 2 | 0.020000 (0.0381%) | throwaway wallet; created by vet402; pays 3 merchants |
| W4GZHN36X35LGSJTTLNZNFPGSSBLMJKFLCMZK4NBLQGUS6PYPPCDB67UOE | NO-LINK-DETECTED | 1 | 0.010000 (0.0191%) | throwaway wallet; is Agent402's address |
| VPF2BUWTDVT7OKK4NKPIJBIBBQ5PSKYNRE4BGNTLHDJY6WDL4DAGFKWF4Q | NO-LINK-DETECTED | 1 | 0.005000 (0.0095%) | throwaway wallet; pays 4 merchants |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 1 | 0.005000 (0.0095%) | pays 16 merchants |

Top 18 of 18 payers; all in the payer CSV.

## Sub-cent settlements

655 (27.5789%) settlements · 2.691000 (5.1315%) USDC. Paid by synthetic-indicated payers: 405 (17.0526%) settlements · 1.485000 (2.8318%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://canix402-api.compx.io/positions | 446 (18.7789%) | 2.230000 (4.2524%) | 5 | 446 | 245 |
| GET | https://canix402-api.compx.io/opportunities | 306 (12.8842%) | 3.060000 (5.8351%) | 9 | 0 | 28 |
| POST | https://canix402-api.compx.io/execution/quotes | 234 (9.8526%) | 23.400000 (44.6216%) | 3 | 0 | 103 |
| GET | https://canix402-api.compx.io/opportunities/personalized | 204 (8.5895%) | 10.200000 (19.4504%) | 5 | 0 | 117 |
| GET | https://canix402-api.compx.io/opportunities/search | 194 (8.1684%) | 1.940000 (3.6994%) | 6 | 0 | 167 |
| GET | https://canix402-api.compx.io/protocols/folks-finance/opportunities | 156 (6.5684%) | 1.560000 (2.9748%) | 4 | 0 | 81 |
| GET | https://canix402-api.compx.io/positions/claimable | 146 (6.1474%) | 0.146000 (0.2784%) | 4 | 146 | 135 |
| GET | https://canix402-api.compx.io/protocols/tinyman/opportunities | 144 (6.0632%) | 1.440000 (2.7459%) | 5 | 0 | 89 |
| GET | https://canix402-api.compx.io/protocols/compx/opportunities | 82 (3.4526%) | 0.820000 (1.5637%) | 5 | 0 | 5 |
| GET | https://canix402-api.compx.io/protocols/reti/opportunities | 74 (3.1158%) | 0.740000 (1.4111%) | 4 | 0 | 62 |
| (not recorded) | (not recorded) | 71 (2.9895%) | 1.395000 (2.6601%) | 5 | 7 | 0 |
| GET | https://canix402-api.compx.io/protocols/dorkfi/opportunities | 67 (2.8211%) | 0.670000 (1.2776%) | 3 | 0 | 0 |
| GET | https://canix402-api.compx.io/protocols/pact/opportunities | 57 (2.4000%) | 0.570000 (1.0869%) | 4 | 0 | 2 |
| POST | https://canix402-api.compx.io/swaps/transactions | 43 (1.8105%) | 0.215000 (0.4100%) | 2 | 43 | 25 |
| (not recorded) | https://canix402-api.compx.io/execution/quotes | 21 (0.8842%) | 2.100000 (4.0045%) | 1 | 0 | 0 |
| GET | https://canix402-api.compx.io/protocols/haystack/opportunities | 20 (0.8421%) | 0.200000 (0.3814%) | 2 | 0 | 18 |
| (not recorded) | https://canix402-api.compx.io/opportunities | 13 (0.5474%) | 0.130000 (0.2479%) | 2 | 0 | 1 |
| (not recorded) | https://canix402-api.compx.io/positions | 13 (0.5474%) | 0.065000 (0.1239%) | 1 | 13 | 0 |
| (not recorded) | https://canix402-api.compx.io/opportunities/personalized | 12 (0.5053%) | 0.600000 (1.1441%) | 1 | 0 | 0 |
| (not recorded) | https://canix402-api.compx.io/protocols/compx/opportunities | 12 (0.5053%) | 0.120000 (0.2288%) | 1 | 0 | 0 |
| (not recorded) | https://canix402-api.compx.io/protocols/dorkfi/opportunities | 12 (0.5053%) | 0.120000 (0.2288%) | 1 | 0 | 0 |
| (not recorded) | https://canix402-api.compx.io/protocols/folks-finance/opportunities | 12 (0.5053%) | 0.120000 (0.2288%) | 1 | 0 | 0 |
| (not recorded) | https://canix402-api.compx.io/protocols/pact/opportunities | 12 (0.5053%) | 0.120000 (0.2288%) | 1 | 0 | 0 |
| (not recorded) | https://canix402-api.compx.io/protocols/tinyman/opportunities | 12 (0.5053%) | 0.120000 (0.2288%) | 1 | 0 | 0 |
| GET | https://canix402-api.compx.io/protocols/myth-finance/opportunities | 8 (0.3368%) | 0.080000 (0.1526%) | 3 | 0 | 0 |
| GET | https://canix402-api.compx.io/protocols/morpho/opportunities | 3 (0.1263%) | 0.030000 (0.0572%) | 2 | 0 | 1 |
| POST | https://canix402-api.compx.io/sessions | 1 (0.0421%) | 0.250000 (0.4767%) | 1 | 0 | 0 |

Top 27 of 27 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: canix402-api.compx.io.

Custom-domain candidates: canix402-api.compx.io. Registered email on a matching custom domain: **compx.io**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| canix402-api.compx.io | custom_domain_candidate | yes, cached | 2026-10-05T14:43:35.029000+00:00 | 5 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| canix402-api.compx.io | CANIX402 \| Hunting down the best yields | CANIX402 | Canix402 is an x402-paid DeFi opportunity API for autonomous agents. Discover endpoints, pay in USDC, and fetch normalized APY data — including wallet-personalized yield recommendations. | https://canix402-api.compx.io/logo.png | https://canix402-api.compx.io/banner.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| canix402-api.compx.io | A2A Agent Card | canix402 | https://canix402-api.compx.io/.well-known/agent-card.json | x402-gated DeFi data and walletless transaction API for agents. Paid requests settle in Algorand USDC, or Base USDC when that accept is listed, through the public Caddy gateway; no API keys or server-side wallet access. |
| canix402-api.compx.io | Agent Manifest | canix402 | https://canix402-api.compx.io/.well-known/agent.json | x402-gated DeFi data and walletless transaction API for agents. Paid requests settle in Algorand USDC, or Base USDC when that accept is listed, through the public Caddy gateway; no API keys or server-side wallet access. |
| canix402-api.compx.io | AI Plugin | canix402 | https://canix402-api.compx.io/.well-known/ai-plugin.json | DeFi data and walletless transaction API for agents, paid per call with USDC using x402. |
| canix402-api.compx.io | x402 Discovery | not recorded | https://canix402-api.compx.io/.well-known/x402 | not recorded |
| canix402-api.compx.io | llms.txt | CANIX402 | https://canix402-api.compx.io/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 5 |
| Agent document types | ["agent-card", "agent-json", "ai-plugin", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 17 |
| Description count | 17 |
| Mime type count | 17 |
| Accepts count | 17 |
| Discovery count | 17 |
| Input documentation count | 17 |
| Output documentation count | 17 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-04 | 18 | 0.192000 | 2 | 4 | 9 (50.0000%) |
| 2026-09-05 | 20 | 0.212000 | 2 | 4 | 9 (45.0000%) |
| 2026-09-06 | 19 | 0.278000 | 2 | 6 | 12 (63.1579%) |
| 2026-09-07 | 19 | 0.278000 | 2 | 6 | 13 (68.4211%) |
| 2026-09-08 | 21 | 0.298000 | 2 | 6 | 12 (57.1429%) |
| 2026-09-09 | 17 | 0.258000 | 2 | 6 | 11 (64.7059%) |
| 2026-09-10 | 22 | 0.398000 | 2 | 6 | 13 (59.0909%) |
| 2026-09-11 | 15 | 0.238000 | 2 | 6 | 12 (80.0000%) |
| 2026-09-12 | 14 | 0.232000 | 2 | 6 | 12 (85.7143%) |
| 2026-09-13 | 14 | 0.228000 | 2 | 6 | 12 (85.7143%) |
| 2026-09-14 | 21 | 0.182000 | 2 | 4 | 10 (47.6190%) |
| 2026-09-15 | 12 | 0.092000 | 2 | 4 | 4 (33.3333%) |
| 2026-09-16 | 17 | 0.182000 | 2 | 4 | 9 (52.9412%) |
| 2026-09-17 | 19 | 0.368000 | 2 | 6 | 13 (68.4211%) |
| 2026-09-21 | 14 | 0.219000 | 2 | 7 | 14 (100.0000%) |
| 2026-09-22 | 18 | 0.268000 | 3 | 6 | 12 (66.6667%) |
| 2026-09-23 | 17 | 0.258000 | 2 | 6 | 12 (70.5882%) |
| 2026-09-24 | 20 | 0.283000 | 2 | 7 | 13 (65.0000%) |
| 2026-09-25 | 16 | 0.248000 | 2 | 6 | 12 (75.0000%) |
| 2026-09-26 | 14 | 0.152000 | 2 | 4 | 9 (64.2857%) |
| 2026-09-27 | 31 | 0.424000 | 5 | 8 | 14 (45.1613%) |
| 2026-09-28 | 17 | 0.165000 | 2 | 1 | 0 (0.0000%) |
| 2026-09-29 | 34 | 0.520000 | 3 | 10 | 31 (91.1765%) |
| 2026-09-30 | 38 | 0.493000 | 4 | 13 | 12 (31.5789%) |
| 2026-10-01 | 17 | 0.235000 | 4 | 9 | 12 (70.5882%) |
| 2026-10-02 | 13 | 0.142000 | 3 | 4 | 8 (61.5385%) |
| 2026-10-03 | 18 | 0.344000 | 3 | 8 | 15 (83.3333%) |
| 2026-10-04 | 12 | 0.118000 | 4 | 6 | 8 (66.6667%) |
| 2026-10-05 | 15 | 0.153000 | 4 | 5 | 8 (53.3333%) |
| 2026-10-06 | 9 | 0.093000 | 2 | 5 | 8 (88.8889%) |

Last 30 of 72 active days; all in the daily CSV.
