# Tendril — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 42).

## Identity and accounts

Merchant ID: `WklLN1FRRTdaWDQ0NlRXM1BON1BRNVVE`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | ZIK7QQE7ZX446TW3PN7PQ5UDZNTY7JI5RYNTIU3LPEYBOSTVWI6PTNSWKI |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 42 | Tendril | Exact submitted wallet ZIK7QQE7ZX446TW3PN7PQ5UDZNTY7JI5RYNTIU3LPEYBOSTVWI6PTNSWKI is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 1,340 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 1,642.400000 | USDC settled. |
| Unique payer accounts | 51 | Distinct accounts that paid. |
| Synthetic-indicated | 704 (52.5373%) · 831.750000 USDC (50.6424%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 636 (47.4627%) · 810.650000 USDC (49.3576%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-02 21:48:35 UTC / 2026-10-06 05:31:07 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/tendril-20e65f182f-transactions.csv.gz) · [All endpoints](../evidence/tendril-20e65f182f-endpoints.csv) · [Payer evidence](../evidence/tendril-20e65f182f-payers.csv) · [Daily metrics](../evidence/tendril-20e65f182f-daily.csv) · [Site and catalog data](../evidence/tendril-20e65f182f-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| FLEET | 6 (0.4478%) | 15.030000 (0.9151%) |
| MERCHANT-FUNDED | 698 (52.0896%) | 816.720000 (49.7272%) |
| NO-LINK-DETECTED | 636 (47.4627%) | 810.650000 (49.3576%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| M6JQNJVX32HEN2LS5W2WX2PMSXPDHHKADVUATIQ5KQIVVVHSVILQNOS62A | NO-LINK-DETECTED | 626 | 804.650000 (48.9923%) | throwaway wallet; is AgentMesh's address; pays 5 merchants |
| 53MY3OWBMUMYLSSVKJPIMOHRDAUK32SCM46W436VC64NLQZS6RUO55SCEY | MERCHANT-FUNDED | 2 | 89.100000 (5.4250%) | created by merchant; merchant sent 0.2 ALGO; fleet of 11 via ZIK7QQ…SWKI; throwaway wallet |
| 522WJHMLRPCHWOW2U35OA346NALBKJGV6KRACBBE5YZFTAKEVPGGDBP7FY | MERCHANT-FUNDED | 2 | 80.000000 (4.8709%) | created by merchant; merchant sent 0.2 ALGO; fleet of 11 via ZIK7QQ…SWKI; throwaway wallet |
| MPVEK3M7C5YH3LGHLCDLXP6S4NG4YP2HDMSGKFI5UI3PD2IUFDHWY64GLQ | MERCHANT-FUNDED | 2 | 60.000000 (3.6532%) | created by merchant; merchant sent 0.2 ALGO; fleet of 11 via ZIK7QQ…SWKI; throwaway wallet |
| 3YWOTPXFNOHCGZPKGXMNRHMD457JEOL5CAHWGI2W7XARDJM6TCQCIJH2G4 | MERCHANT-FUNDED | 19 | 55.800000 (3.3975%) | created by merchant; merchant sent 0.2 ALGO; merchant sent 20.00 USDC ×1 (36% of paid); fleet of 3 via ZIK7QQ…SWKI; throwaway wallet |
| 3UQDPRQ2FTLNGBMY4FPXE2NO63DCWVKH32CIBXVBSEHIS24XQJYFZXX2PE | MERCHANT-FUNDED | 1 | 50.000000 (3.0443%) | created by merchant; merchant sent 0.2 ALGO; fleet of 3 via ZIK7QQ…SWKI; throwaway wallet |
| RORRUIP44PLVNLFFFZ62IZ45NWPZ7NP45IAH3CA6XBQWRDTCZKHKLBD6CU | MERCHANT-FUNDED | 13 | 40.000000 (2.4355%) | created by merchant; merchant sent 0.2 ALGO; fleet of 11 via ZIK7QQ…SWKI; throwaway wallet |
| CYLKXTP32JUHJO53375MSA2CJ4KRLU6SP6C7NNUV7YVFZBXQ4SRZKKPMV4 | MERCHANT-FUNDED | 29 | 38.500000 (2.3441%) | created by merchant; merchant sent 0.2 ALGO; throwaway wallet; 54% of gaps &lt; 60s |
| GNFGSI452O2KVWOT5K6WVR4IEMPMXPTOA756U3NQWZBE7P3XJAHO6GQMJY | MERCHANT-FUNDED | 29 | 34.000000 (2.0701%) | created by merchant; merchant sent 0.2 ALGO |
| ITLW7WWTZOV4MZKEV7HY33EVLYENOPW2BYDLG6N4S6ZSTM2DLLXKJRZQKU | MERCHANT-FUNDED | 16 | 30.000000 (1.8266%) | created by merchant; merchant sent 0.2 ALGO; fleet of 11 via ZIK7QQ…SWKI; throwaway wallet |
| RWBHMHDPXNA2EFQEZORJIWWZQ5OLOHDBRUK5VSXOLFSOI4SNFH34WQ45MY | MERCHANT-FUNDED | 24 | 29.090000 (1.7712%) | created by merchant; merchant sent 1.00 ALGO; merchant sent 307 USDC ×7 (1055% of paid); throwaway wallet |
| 53AA4M77BJOL7KGQ63NJCY2UDZFWYK7PSKF2WU5YF3ABHSZ6GTSUJZB3O4 | MERCHANT-FUNDED | 12 | 29.000000 (1.7657%) | created by merchant; merchant sent 0.2 ALGO; fleet of 18 via ZIK7QQ…SWKI; throwaway wallet; 64% of gaps &lt; 60s |
| JPM2IXHDZKFCH3A67ELMP4FEUVKIT6YZMJ2RM5Q6GNB224JKKEJBYSNS6Y | MERCHANT-FUNDED | 3 | 27.700000 (1.6866%) | created by merchant; merchant sent 0.2 ALGO; fleet of 11 via ZIK7QQ…SWKI; throwaway wallet |
| WBGN6Y3FX55XSQGNXQ2XFK7IDTLXAQM2VW7LLBFSGHN45MITFDOM3TYDLQ | MERCHANT-FUNDED | 97 | 27.660000 (1.6841%) | created by merchant; merchant sent 0.35 ALGO; merchant sent 6.27 USDC ×3 (23% of paid); fleet of 18 via ZIK7QQ…SWKI; throwaway wallet; 50% of gaps &lt; 60s; rekeyed → 4CL3VB…CN7E |
| F32WVAGAYTRSWXC36Q3RQ7DHJPAQ4N6PZFYCD4D2VBJTJHVXWUIJHK7TC4 | MERCHANT-FUNDED | 2 | 27.100000 (1.6500%) | created by merchant; merchant sent 0.2 ALGO; fleet of 11 via ZIK7QQ…SWKI; throwaway wallet |
| S52XGVK7QX3R42F7UA73ZH2XWDWZMRNONKP47O5NJBFQHMNPHHFPDC7DNI | MERCHANT-FUNDED | 4 | 27.000000 (1.6439%) | created by merchant; merchant sent 5.00 ALGO; fleet of 18 via ZIK7QQ…SWKI |
| 345YTHGTHSIJHKOSPABNT6BP6BU3G6YB44U6B5KSJQFBS34GVTSEKY7JTY | MERCHANT-FUNDED | 20 | 20.000000 (1.2177%) | created by merchant; merchant sent 0.2 ALGO; fleet of 3 via ZIK7QQ…SWKI; throwaway wallet |
| SSQMJQ246IFVWKXMU3GWULSU7VC366T4L26JCUXQORDKM3JPRUWADAYAP4 | MERCHANT-FUNDED | 4 | 19.200000 (1.1690%) | created by merchant; merchant sent 0.2 ALGO; fleet of 11 via ZIK7QQ…SWKI; throwaway wallet |
| BL5M5LOUSJZ77LEKGWW4L5R665T4EV33MPQGRKWZWKTYC3PUPSTK7IWVRE | FLEET | 6 | 15.030000 (0.9151%) | funded by linked payer RWBHMH…45MY; throwaway wallet |
| 5R2PSXLYZ6D4YP5Z7DWLEKN4BNQXILQXVALKGKRNRXPVQ2XQI53VKOI3CA | MERCHANT-FUNDED | 18 | 15.000000 (0.9133%) | created by merchant; merchant sent 0.2 ALGO; fleet of 11 via ZIK7QQ…SWKI; throwaway wallet |
| OGYMSXGHXMUJNUZX6AJGOM2Q3IP2LE6MVGGXWIUUDVHF4VNBVM2ORRQYNY | MERCHANT-FUNDED | 52 | 14.900000 (0.9072%) | created by merchant; merchant sent 0.2 ALGO; throwaway wallet |
| OZ2KV5DJ3WGE2U4RNNDOUILH2HEPWXDIF4C6MH3PRIRFZCTTI56GVSLCPU | MERCHANT-FUNDED | 15 | 11.500000 (0.7002%) | created by merchant; merchant sent 0.2 ALGO; fleet of 3 via ZIK7QQ…SWKI; throwaway wallet |
| 27TAHRSDEKPNJPKXAMYFRTBWBQTYO6KTXBQJZWZWDJN7NO3AGIJD5INWHU | MERCHANT-FUNDED | 10 | 10.800000 (0.6576%) | created by merchant; merchant sent 0.2 ALGO; fleet of 3 via ZIK7QQ…SWKI; throwaway wallet |
| WZCHECOCHJF7BYGF433CRWJA2DOQD4A6AD7QWKRQPJTSKO2TP737ZOAQTQ | MERCHANT-FUNDED | 24 | 10.000000 (0.6089%) | created by merchant; merchant sent 0.2 ALGO; fleet of 11 via ZIK7QQ…SWKI; throwaway wallet |
| A72HTL5KAYN64DS6BSKJRDTT7O36E3NIOMRJ4QSN7ANX3MZURKPQJIXB6E | MERCHANT-FUNDED | 13 | 9.700000 (0.5906%) | created by merchant; merchant sent 0.2 ALGO; throwaway wallet |
| W5XC56YLYZSFES5BTYNDQROIDG5SM6HVF52BXVJXPUVORFWHJLCIOMEX7A | MERCHANT-FUNDED | 6 | 9.200000 (0.5602%) | created by merchant; merchant sent 0.2 ALGO; throwaway wallet |
| UGWTJUAR3VS2YDAATOPNTLA4KTNDYVS5INVSU76IAX365EAHHC2ML66TVM | NO-LINK-DETECTED | 10 | 6.000000 (0.3653%) |  |
| JRBAKVDSXZBLKLEIFEP2PSAVHGJIHQVJL73LMGVKD3CDQALT4KJFFS5R24 | MERCHANT-FUNDED | 30 | 4.990000 (0.3038%) | created by merchant; merchant sent 0.26 ALGO; fleet of 18 via ZIK7QQ…SWKI; throwaway wallet; 86% of gaps &lt; 60s |
| B74YZ432XAHHV7YUPOZUKEZJCHTV3RJ3APTDD4XY5FRWNVE3QHVZHN4MRI | MERCHANT-FUNDED | 21 | 4.000000 (0.2435%) | created by merchant; merchant sent 0.26 ALGO; fleet of 18 via ZIK7QQ…SWKI; throwaway wallet; 60% of gaps &lt; 60s |
| UAYIPNW6GKVPCPU53SROTNWBJMR26UI6UHJBTC5F4QJA5P52WMFTILZWDI | MERCHANT-FUNDED | 4 | 4.000000 (0.2435%) | created by merchant; merchant sent 0.26 ALGO; fleet of 18 via ZIK7QQ…SWKI; throwaway wallet |
| SU2KRM2DEEXUTS6JXJLNNJWJJC4JHKOJSHHGJH665K6XJ45HMJXY4HUDUE | MERCHANT-FUNDED | 18 | 4.000000 (0.2435%) | created by merchant; merchant sent 0.2 ALGO; fleet of 11 via ZIK7QQ…SWKI; throwaway wallet |
| UO67GTBKY6IVUVJW6HEAHFETPOVCSDUEPHZCMEVZH36CCH3STKFBTYY2SA | MERCHANT-FUNDED | 22 | 3.950000 (0.2405%) | created by merchant; merchant sent 0.26 ALGO; fleet of 18 via ZIK7QQ…SWKI; throwaway wallet; 67% of gaps &lt; 60s |
| XVPRXW5V24IPVF425PARWFU37NRZW5NPVHDXSL3AYHPC2QDGMV3DSCJZ4E | MERCHANT-FUNDED | 16 | 3.050000 (0.1857%) | created by merchant; merchant sent 0.2 ALGO; fleet of 3 via ZIK7QQ…SWKI; throwaway wallet; 60% of gaps &lt; 60s |
| X4KJS7Y2J2M2URJXCQVJXFIOK46GBYSVQ2TQ3CT6A3JPM5MDTB5FBMYD4E | MERCHANT-FUNDED | 17 | 2.800000 (0.1705%) | created by merchant; merchant sent 0.2 ALGO; fleet of 18 via ZIK7QQ…SWKI; throwaway wallet; 63% of gaps &lt; 60s |
| EN6UOSSZ2PTRL466PP76KJLTMNMBC63KODPFJVWNRKXNM3GZWUSEMKMTQY | MERCHANT-FUNDED | 6 | 2.700000 (0.1644%) | merchant sent 489 USDC ×18 (18096% of paid); throwaway wallet |
| X2MF3NU77CEQ7424YSEO6YLX7JJXF6VWM5VBDGZGH5OSMCW7XYFZIMIT7Q | MERCHANT-FUNDED | 7 | 2.600000 (0.1583%) | created by merchant; merchant sent 0.2 ALGO; throwaway wallet |
| L7IYI6AAWRH6XAGL4JBH7CL7S2FDEB2B7BCLOCZKBA2UVONPLIKC7LOMQY | MERCHANT-FUNDED | 25 | 2.500000 (0.1522%) | created by merchant; merchant sent 0.26 ALGO; fleet of 18 via ZIK7QQ…SWKI; throwaway wallet |
| 5AV4ZSHEAFMWAAHAPM7OGKJUKZJ3KHNUPDT3LKT3GHSYNEUNXZNPYXNP3A | MERCHANT-FUNDED | 20 | 2.000000 (0.1218%) | created by merchant; merchant sent 0.26 ALGO; merchant sent 2.00 USDC ×1 (100% of paid); fleet of 18 via ZIK7QQ…SWKI; throwaway wallet; 84% of gaps &lt; 60s |
| GAZGR2ADGFS3ZI3QEYVQSPJJGVBRHMR5EEPQZCLETO6RFUNGXGY6QVPJ24 | MERCHANT-FUNDED | 21 | 2.000000 (0.1218%) | created by merchant; merchant sent 0.25 ALGO; fleet of 18 via ZIK7QQ…SWKI; throwaway wallet; 90% of gaps &lt; 60s |
| OKHJXZPASMBPLBDU4GZKTAK27PMLPSNFRFVA33ZZNYOWSYFH3OEQ7XZMXA | MERCHANT-FUNDED | 21 | 2.000000 (0.1218%) | created by merchant; merchant sent 0.2 ALGO; fleet of 3 via ZIK7QQ…SWKI; throwaway wallet; 95% of gaps &lt; 60s |
| KERHJADEWAEW4JJDE43VYRWYQHOX25FNUKLHQ4AOSFAZ7LBTCM6CWJ4PKU | MERCHANT-FUNDED | 11 | 1.500000 (0.0913%) | created by merchant; merchant sent 0.2 ALGO; throwaway wallet; 70% of gaps &lt; 60s |
| JGMIUR5GDSWFIJEAT6WDLWTHXDHVPGMIHBWJ3IRTIZY3MPGAHFKIGYBX54 | MERCHANT-FUNDED | 6 | 1.140000 (0.0694%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 1.20 USDC ×1 (105% of paid); fleet of 18 via ZIK7QQ…SWKI; throwaway wallet; 60% of gaps &lt; 60s |
| NGANPKME7GJZ5UTIV3X7DS5WXBFWMYKSZZ67OBNQE4R3YT7FZ6MPENQEXA | MERCHANT-FUNDED | 3 | 1.100000 (0.0670%) | created by merchant; merchant sent 0.2 ALGO; fleet of 3 via ZIK7QQ…SWKI; throwaway wallet |
| YOEVV65IDSUHFWTLWVYAMMK7Y3UN2A4YKFT52P5YKAQ7OPB36UAQQJFUVY | MERCHANT-FUNDED | 6 | 1.050000 (0.0639%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.05 USDC ×1 (4.8% of paid); fleet of 18 via ZIK7QQ…SWKI; throwaway wallet |
| R3UCJVBHQQCKHTCLRCMPZELM5FG4WLGIEURS6SFTBHD26ADAXPYLIDU534 | MERCHANT-FUNDED | 5 | 1.040000 (0.0633%) | created by merchant; merchant sent 0.25 ALGO; fleet of 18 via ZIK7QQ…SWKI; throwaway wallet |
| LZJX3H7M3DBBANJAHZ4QK3NUK4BLHB2DZKC4KWVTB2FKYRO66U7IEDRZBQ | MERCHANT-FUNDED | 1 | 1.000000 (0.0609%) | created by merchant; merchant sent 0.26 ALGO; fleet of 18 via ZIK7QQ…SWKI; throwaway wallet |
| 35YQ7RDAKSMRXZBJO4HYOXVYKBWHLVXHHDU4I3EY2T7QCXRK6TDF7QTGAQ | MERCHANT-FUNDED | 1 | 1.000000 (0.0609%) | created by merchant; merchant sent 0.2 ALGO; fleet of 18 via ZIK7QQ…SWKI; throwaway wallet |
| SCI6OBXB326RUY5N7S2KPMSNX6QWMT4RTTMGDDKKL3OZB7TSPSV73Z7OGE | MERCHANT-FUNDED | 1 | 1.000000 (0.0609%) | merchant sent 778 USDC ×7 (77837% of paid); throwaway wallet; pays 2 merchants |
| BVVJ6U6MQJKAPIKKS6RWC45X6HX2KXSB4KNJZ4CNY2LVUODKKCQ3IY4RJA | MERCHANT-FUNDED | 1 | 1.000000 (0.0609%) | created by merchant; merchant sent 0.2 ALGO; fleet of 3 via ZIK7QQ…SWKI; throwaway wallet |
| GWIQ5VL47GAMTXALB67BKSTIRV2DJ32XVX3JW3NLFYNUYBKGGT4KPGFYFY | MERCHANT-FUNDED | 6 | 0.550000 (0.0335%) | created by merchant; merchant sent 0.35 ALGO; merchant sent 0.55 USDC ×1 (100% of paid); fleet of 18 via ZIK7QQ…SWKI; throwaway wallet |
| 4JHRPVLPGEH2YZ7YNQME54HNDVT5DPUXBPAYDJPFY4OWNIFBMT6W3OK5X4 | MERCHANT-FUNDED | 12 | 0.500000 (0.0304%) | created by merchant; merchant sent 0.26 ALGO; merchant sent 0.5 USDC ×1 (100% of paid); fleet of 18 via ZIK7QQ…SWKI; throwaway wallet; 100% of gaps &lt; 60s |

Top 51 of 51 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://tendrilhq.com/x402/rent | 573 (42.7612%) | 39.780000 (2.4221%) | 45 | 0 | 505 |
| POST | https://tendrilhq.com/x402/run | 529 (39.4776%) | 701.250000 (42.6967%) | 6 | 0 | 16 |
| POST | https://tendrilhq.com/x402/topup | 144 (10.7463%) | 820.230000 (49.9409%) | 46 | 0 | 104 |
| POST | https://tendrilhq.com/x402/keys | 65 (4.8507%) | 42.500000 (2.5877%) | 20 | 0 | 65 |
| POST | https://tendril.007575.xyz/x402/topup | 16 (1.1940%) | 38.510000 (2.3447%) | 4 | 0 | 8 |
| POST | https://tendril.007575.xyz/x402/rent | 10 (0.7463%) | 0.100000 (0.0061%) | 3 | 0 | 6 |
| POST | https://tendril.007575.xyz/x402/run | 3 (0.2239%) | 0.030000 (0.0018%) | 1 | 0 | 0 |

Top 7 of 7 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: tendril.007575.xyz, tendrilhq.com.

Custom-domain candidates: tendril.007575.xyz, tendrilhq.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| tendril.007575.xyz | custom_domain_candidate | yes, cached | 2026-10-02T19:20:35.960000+00:00 | 0 |
| tendrilhq.com | custom_domain_candidate | yes, cached | 2026-10-05T18:23:00.935000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| tendril.007575.xyz | TENDRIL | TENDRIL | Rent a sandboxed SSH machine by the hour. Pay per call with x402 on Algorand, in USDC. | https://tendrilhq.com/favicon.svg | https://tendrilhq.com/og.png | #fbfbf9 |
| tendrilhq.com | Tendril — Rent Real Compute by the Second | TENDRIL | Rent and contribute sandboxed compute with x402 on Algorand. | https://tendrilhq.com/favicon.svg | https://tendrilhq.com/og.png | #fbfbf9 |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 0 |
| Agent document types | [] |
| Agent readiness evidence | catalog_only |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 4 |
| Description count | 4 |
| Mime type count | 4 |
| Accepts count | 4 |
| Discovery count | 4 |
| Input documentation count | 4 |
| Output documentation count | 4 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-04 | 71 | 70.100000 | 2 | 0 | 1 (1.4085%) |
| 2026-09-05 | 65 | 99.600000 | 3 | 0 | 17 (26.1538%) |
| 2026-09-06 | 9 | 4.500000 | 2 | 0 | 5 (55.5556%) |
| 2026-09-07 | 3 | 0.300000 | 1 | 0 | 3 (100.0000%) |
| 2026-09-10 | 2 | 0.200000 | 1 | 0 | 2 (100.0000%) |
| 2026-09-11 | 1 | 0.100000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-12 | 3 | 5.200000 | 1 | 0 | 3 (100.0000%) |
| 2026-09-14 | 154 | 225.400000 | 11 | 0 | 130 (84.4156%) |
| 2026-09-15 | 22 | 166.400000 | 4 | 0 | 7 (31.8182%) |
| 2026-09-16 | 13 | 96.500000 | 2 | 0 | 2 (15.3846%) |
| 2026-09-17 | 11 | 16.500000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-18 | 19 | 70.200000 | 3 | 0 | 8 (42.1053%) |
| 2026-09-19 | 11 | 16.500000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-20 | 10 | 15.000000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-21 | 17 | 16.500000 | 2 | 0 | 0 (0.0000%) |
| 2026-09-22 | 6 | 9.000000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-23 | 11 | 16.500000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-24 | 36 | 55.400000 | 4 | 0 | 20 (55.5556%) |
| 2026-09-25 | 17 | 74.100000 | 2 | 0 | 1 (5.8824%) |
| 2026-09-26 | 18 | 24.800000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-27 | 16 | 20.500000 | 2 | 0 | 4 (25.0000%) |
| 2026-09-28 | 49 | 85.000000 | 3 | 0 | 19 (38.7755%) |
| 2026-09-29 | 37 | 48.100000 | 3 | 0 | 14 (37.8378%) |
| 2026-09-30 | 57 | 62.900000 | 5 | 0 | 33 (57.8947%) |
| 2026-10-01 | 23 | 21.400000 | 4 | 0 | 7 (30.4348%) |
| 2026-10-02 | 30 | 30.100000 | 2 | 0 | 4 (13.3333%) |
| 2026-10-03 | 31 | 36.300000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 22 | 22.700000 | 2 | 0 | 4 (18.1818%) |
| 2026-10-05 | 29 | 31.700000 | 3 | 0 | 9 (31.0345%) |
| 2026-10-06 | 3 | 4.500000 | 1 | 0 | 0 (0.0000%) |

Last 30 of 49 active days; all in the daily CSV.
