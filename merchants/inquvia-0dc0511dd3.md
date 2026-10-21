# Inquvia — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 34).

## Identity and accounts

Merchant ID: `T0xSQTMyWUNaMkJaNVo3UUlLU0FMWFNI`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | OLRA32YCZ2BZ5Z7QIKSALXSHLKEABXHDOP2ATUTUORTCLKW725AIOQ542M |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 34 | Inquvia | Exact submitted wallet OLRA32YCZ2BZ5Z7QIKSALXSHLKEABXHDOP2ATUTUORTCLKW725AIOQ542M is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 387 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 218.500000 | USDC settled. |
| Unique payer accounts | 16 | Distinct accounts that paid. |
| Synthetic-indicated | 367 (94.8320%) · 208.500000 USDC (95.4233%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 20 (5.1680%) · 10.000000 USDC (4.5767%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-12 14:05:52 UTC / 2026-10-06 06:03:00 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/inquvia-0dc0511dd3-transactions.csv.gz) · [All endpoints](../evidence/inquvia-0dc0511dd3-endpoints.csv) · [Payer evidence](../evidence/inquvia-0dc0511dd3-payers.csv) · [Daily metrics](../evidence/inquvia-0dc0511dd3-daily.csv) · [Site and catalog data](../evidence/inquvia-0dc0511dd3-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| FLEET | 198 (51.1628%) | 113.000000 (51.7162%) |
| MERCHANT-FUNDED | 169 (43.6693%) | 95.500000 (43.7071%) |
| NO-LINK-DETECTED | 20 (5.1680%) | 10.000000 (4.5767%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| KOAKC2TQU5F2TPFHHJAFR5CJDAH4ZGKUHC5RPX7ZMYMA3VGAXZXMHY6URY | FLEET | 52 | 30.000000 (13.7300%) | funded by linked payer 622RJ2…PKGI; merchant sent 10.50 USDC ×2 (35% of paid); throwaway wallet |
| AEFOL5TVU7M6FZJZQUPUUTAM3NZPVKPHG6RK2FB7JOFWSUQFU22HIACE2Y | FLEET | 49 | 25.500000 (11.6705%) | funded by linked payer 622RJ2…PKGI; merchant sent 1.00 USDC ×1 (3.9% of paid); throwaway wallet |
| TVSGWFK32LA43MBBZ7N4LFCZUJ4BW62WIWOZFBR5DJ4W3D3CHQP3WVB7PU | MERCHANT-FUNDED | 43 | 25.500000 (11.6705%) | merchant sent 17.00 USDC ×2 (67% of paid); throwaway wallet |
| IG5LS2A2GMYXYYFHDLJNWYAF6OGXHMKWK2TNO3KBG2T2MNQBJCSWEXWLPU | MERCHANT-FUNDED | 30 | 22.000000 (10.0686%) | created by merchant; merchant sent 0.12 ALGO; merchant sent 10.00 USDC ×1 (45% of paid); throwaway wallet |
| PJZGBAO4GVOQYJJY24EK2U6QM2YWGJ3RFCSXDKTHTI62TSGFHV5H56XBXU | FLEET | 34 | 20.000000 (9.1533%) | funded by linked payer 622RJ2…PKGI; merchant sent 8.00 USDC ×1 (40% of paid); throwaway wallet |
| 622RJ2OK3ZMSCFJO7EEVFB7WPNKFGKWY5O2JBDDBMIPM5R6EHHGHFIPKGI | FLEET | 26 | 15.000000 (6.8650%) | merchant sent 6.00 USDC ×1 (40% of paid); fleet of 3 via 2RIRIX…ROQY; throwaway wallet; created by Sikho AI |
| J4KMPQNQFMWRBJ6QKFY6U3G2KCU2XK6DWSCNITX3XEKLKWFQBZM3SPVX4U | MERCHANT-FUNDED | 24 | 12.000000 (5.4920%) | merchant sent 10.00 USDC ×1 (83% of paid); throwaway wallet; 61% of gaps &lt; 60s; pays 3 merchants |
| HPWSBY5ERWOVZR3Y5IOAULG6X2W36WAEKNHEFDHQQKLVOPK7E5DDWJLBOI | FLEET | 14 | 11.000000 (5.0343%) | funded by linked payer 622RJ2…PKGI; merchant sent 5.00 USDC ×1 (45% of paid); throwaway wallet |
| XGNZBDR6FNRC3XGARA3QTOJGKEVBA6KFRN3NMMA4ZPUBRCZE27KQ4R54IE | MERCHANT-FUNDED | 22 | 11.000000 (5.0343%) | merchant sent 10.00 USDC ×1 (91% of paid); throwaway wallet; 86% of gaps &lt; 60s; created by Sikho AI; pays 2 merchants |
| BE4IBKJSLUN2JHA7AWKZ5KRIIOMRZBQX4ROJGROW3VKXG7QNCLYGMUYWQM | NO-LINK-DETECTED | 20 | 10.000000 (4.5767%) | throwaway wallet; created by PRISM; is Sikho AI's address; pays 3 merchants |
| V3YRJVWEKTJLQNPM3PV6DVBMIMRGGDGMA4EBRUPMZFQMW4OANYOWAEAL74 | MERCHANT-FUNDED | 20 | 10.000000 (4.5767%) | merchant sent 10.00 USDC ×1 (100% of paid); throwaway wallet; 74% of gaps &lt; 60s; created by Sikho AI; pays 2 merchants |
| 7X62CT43O5AZ4SX5NGVZBOOAERAHPPXJURF3I3OC7Y53LS6HNC5WWUKH3E | MERCHANT-FUNDED | 15 | 7.500000 (3.4325%) | merchant sent 6.00 USDC ×1 (80% of paid); throwaway wallet |
| USCFUOIICXAT2FTHTUSK5IIII2ITW6QJ24SLT6LTOLE7XD2CDUL6BGNOWA | FLEET | 14 | 7.000000 (3.2037%) | funded by linked payer IG5LS2…WLPU; throwaway wallet; 77% of gaps &lt; 60s; pays 3 merchants |
| EOIJSW5UMIGIU5B3XFYUY5FUGSJ3DHS6SKNQVQBXHYHGKCNPIZQQ6OHKCI | MERCHANT-FUNDED | 14 | 7.000000 (3.2037%) | merchant sent 7.00 USDC ×1 (100% of paid); fleet of 3 via 2RIRIX…ROQY; throwaway wallet; 54% of gaps &lt; 60s; created by Sikho AI; pays 2 merchants |
| TFD7C6NWSCKZT5XOZBYA5PWVYYDIIR6QE2GALTBEFDLCDZLZZGMKURGXOA | FLEET | 9 | 4.500000 (2.0595%) | funded by linked payer 622RJ2…PKGI |
| VZCOPN4DJKNUPNRCIGYFATIW3VBGU2HUDW5HJUN3Q44JXAHWP3FKPMXDTY | MERCHANT-FUNDED | 1 | 0.500000 (0.2288%) | merchant sent 7.00 USDC ×1 (1400% of paid); fleet of 3 via 2RIRIX…ROQY; throwaway wallet; created by Sikho AI; pays 2 merchants |

Top 16 of 16 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://inquvia.onrender.com/api/x402/document-investigation | 159 (41.0853%) | 79.500000 (36.3844%) | 15 | 0 | 139 |
| POST | https://inquvia.onrender.com/api/x402/image-investigation | 47 (12.1447%) | 23.500000 (10.7551%) | 8 | 0 | 47 |
| POST | https://inquvia.onrender.com/api/x402/claim-investigation | 34 (8.7855%) | 17.000000 (7.7803%) | 10 | 0 | 34 |
| POST | https://inquvia.onrender.com/api/x402/source-investigation | 29 (7.4935%) | 14.500000 (6.6362%) | 7 | 0 | 29 |
| POST | https://inquvia.onrender.com/api/x402/video-investigation | 29 (7.4935%) | 39.500000 (18.0778%) | 7 | 0 | 29 |
| POST | https://inquvia.onrender.com/api/x402/data-investigation | 21 (5.4264%) | 10.500000 (4.8055%) | 6 | 0 | 21 |
| POST | https://inquvia.onrender.com/api/evidence/assess | 15 (3.8760%) | 7.500000 (3.4325%) | 4 | 0 | 15 |
| POST | https://inquvia.onrender.com/api/evidence/contradictions | 14 (3.6176%) | 7.000000 (3.2037%) | 5 | 0 | 14 |
| POST | https://inquvia.onrender.com/api/x402/audio-investigation | 12 (3.1008%) | 6.000000 (2.7460%) | 5 | 0 | 12 |
| POST | https://inquvia.onrender.com/api/evidence/timeline | 10 (2.5840%) | 5.000000 (2.2883%) | 5 | 0 | 10 |
| POST | https://inquvia.onrender.com/api/evidence/duplicates | 9 (2.3256%) | 4.500000 (2.0595%) | 3 | 0 | 9 |
| POST | https://inquvia.onrender.com/api/evidence/gaps | 8 (2.0672%) | 4.000000 (1.8307%) | 5 | 0 | 8 |

Top 12 of 12 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: inquvia.onrender.com.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| inquvia.onrender.com | hosting_provider_domain | yes, cached | 2026-10-06T08:18:39.588000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| inquvia.onrender.com | Inquvia | Inquvia | Evidence-backed investigations paid per request with x402 on Algorand. | not recorded | https://inquvia.onrender.com/logo.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| inquvia.onrender.com | x402 Discovery | Inquvia | https://inquvia.onrender.com/.well-known/x402 | Evidence-backed investigations paid per request with x402 on Algorand. |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
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
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 12 |
| Description count | 12 |
| Mime type count | 12 |
| Accepts count | 12 |
| Discovery count | 12 |
| Input documentation count | 12 |
| Output documentation count | 12 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-12 | 18 | 9.000000 | 2 | 0 | 18 (100.0000%) |
| 2026-09-13 | 21 | 13.500000 | 3 | 0 | 21 (100.0000%) |
| 2026-09-14 | 25 | 17.500000 | 3 | 0 | 25 (100.0000%) |
| 2026-09-15 | 1 | 0.500000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-16 | 7 | 3.500000 | 1 | 0 | 7 (100.0000%) |
| 2026-09-17 | 14 | 7.000000 | 1 | 0 | 14 (100.0000%) |
| 2026-09-18 | 14 | 7.000000 | 1 | 0 | 14 (100.0000%) |
| 2026-09-24 | 27 | 14.500000 | 2 | 0 | 7 (25.9259%) |
| 2026-09-25 | 22 | 13.000000 | 2 | 0 | 22 (100.0000%) |
| 2026-09-26 | 20 | 10.000000 | 3 | 0 | 20 (100.0000%) |
| 2026-09-28 | 12 | 6.000000 | 2 | 0 | 12 (100.0000%) |
| 2026-09-29 | 12 | 6.000000 | 3 | 0 | 12 (100.0000%) |
| 2026-10-01 | 26 | 13.000000 | 2 | 0 | 26 (100.0000%) |
| 2026-10-02 | 20 | 13.000000 | 3 | 0 | 20 (100.0000%) |
| 2026-10-03 | 75 | 41.500000 | 4 | 0 | 75 (100.0000%) |
| 2026-10-04 | 40 | 24.000000 | 2 | 0 | 40 (100.0000%) |
| 2026-10-05 | 20 | 12.000000 | 1 | 0 | 20 (100.0000%) |
| 2026-10-06 | 13 | 7.500000 | 1 | 0 | 13 (100.0000%) |

Last 18 of 18 active days; all in the daily CSV.
