# scrape402 — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 78).

## Identity and accounts

Merchant ID: `NVQ2R1RFTU1RV1lRTlpEVVoyRUlEVzYy`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 5T6GTEMMQWYQNZDUZ2EIDW62HVUJ7IGMQQNJXSW23CHMZKQJ2Z3YB3JFTU |
| Algorand | CWJ5TEHVHBCUJLOK6JD7R7XKT3YVYWTGV7567PSVLKXQAYLS2XJN4M3ZPY |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 78 | scrape402 | Exact submitted wallet 5T6GTEMMQWYQNZDUZ2EIDW62HVUJ7IGMQQNJXSW23CHMZKQJ2Z3YB3JFTU is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 876 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 87.600000 | USDC settled. |
| Unique payer accounts | 874 | Distinct accounts that paid. |
| Synthetic-indicated | 873 (99.6575%) · 87.300000 USDC (99.6575%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 3 (0.3425%) · 0.300000 USDC (0.3425%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 7 · 0.700000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-07-22 16:47:02 UTC / 2026-09-26 10:17:37 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/scrape402-d9e87e0c71-transactions.csv.gz) · [All endpoints](../evidence/scrape402-d9e87e0c71-endpoints.csv) · [Payer evidence](../evidence/scrape402-d9e87e0c71-payers.csv) · [Daily metrics](../evidence/scrape402-d9e87e0c71-daily.csv) · [Site and catalog data](../evidence/scrape402-d9e87e0c71-site-and-catalog.json)

**Flag — self-payments excluded:** 7 settlements / 0.700000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 871 (99.4292%) | 87.100000 (99.4292%) |
| NO-LINK-DETECTED | 3 (0.3425%) | 0.300000 (0.3425%) |
| SELF | 2 (0.2283%) | 0.200000 (0.2283%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| CWJ5TEHVHBCUJLOK6JD7R7XKT3YVYWTGV7567PSVLKXQAYLS2XJN4M3ZPY | SELF | 2 | 0.200000 (0.2283%) | merchant's own address; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (50% of paid); throwaway wallet |
| 77VYJXL37J3JXQOI3X72ULXMH75RQUZIS3Q6ADJB2PXGA7AJ4UOUZWQGR4 | NO-LINK-DETECTED | 2 | 0.200000 (0.2283%) | throwaway wallet; pays 2 merchants |
| 2Y7HPBYX5HNMNMUGJDNSW5UAE5T3CAFAA5N6HPOV3OTN2Y3K6HENFFWPNE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); throwaway wallet |
| 7KRPXYZQ5UFNPANPWYRBQR427DF2B3XR3FTFSB7C35LPLFOVP36L6FMOXQ | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| C6C3ALBF54NCNHOF276S3MWI563AULNX7HPQQ4IW56R6JZIKYU3L43E2KM | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 3YBGTU2LF33V6MS77QC2DEUL54IFGDW2FFPV2QFPE6RMR4MRP47HIXS54Y | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 7FY6FTLL4ZY7ZTIGUNVLUR3GANZKRSMMT3YQZFA7QN3D72B2HL4KLPOMXI | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| GE5C6ODYUXZGRHEAMNYFSPMOD27WSMGSXNRIDKUJBRROXXX3ZO2I7QWA74 | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| MVU2VTGQOZU52NOEXVRJ2G466I3XH5KPL2TSA5N46U432F3RVY73WGV5YM | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| QFN6TPNM4P5YEIX2M6Z5AI32UOJNFDOYAEK66DUI5ZX772ZEJNC3YJUPXA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| FJVQJHEN7OAOCC4RUBAKSYBV4PVREVLVQI3KY7KVMWBISXR7XVSTBCXE2Q | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 3OCG632TTBR7ZHJSTYGT65JUY7ENTGTDTVKJVSSV5UISNUPEY7OXYTB2LI | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| TDSTFL4R6GP6ZPPYAA4MS4USM3BVFC7N2LKKXQ5UXPX4YGJ4HV22EPEVAA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 7BPPAMP7PQU4RKN6C3PZTG4R74Z4CZQD5XDDB4VSFYSQHSHJC2MBYF3BKY | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| K6ZSR6LJAKYSSGFNVGHNXNRATIS4XFKJV62QP2FN7JKZVBJIXRONI7ZFUQ | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| NLVRG24XZXYATY52V5GVWIFVWOXQTB3SX4IVETTKRLSQZFVCGE74L4H6XE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| UMRPWYHOSNYLQS5XBLFCHI3L5EZ6HNJZW25YGQ7BNM52TYV6KEBVRTONKU | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| XDWSP62WBOIJ4KJBIHJ2CXNBRMKRLQ4YGRYALD26DXISU6UHIC7P5XWXNE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| JMWURRMQZPCX5IPJE6PPTWJQCTHTXANB63O5KRCEMIDUHJS3SARFIZCFNQ | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| GLMWHQ24UXHTEATALQCMUGON7TMYHVGBOMAG5W3CVFTBD5ISUPV2NJBW4M | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| NXDQDI35QAK2DUELFLX5EM4JNYVNG6UEQDMGNNZD4QHOBN76AAR4ESOZDE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| D7DW5ZLFDPH7RLRGAUZ73R7DVZA6IY67S7BQACX5C6DIA3L5OXSXT65ZYA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| LM57ICPMDL5DTTBPQJMS36EKKEHVWDWEHZ2B2NL2EHGYDNY6VFPWFORX3Q | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 76VE7JB2BJNT4FWYREL3JLTLBEKGYJDLLWUU3NBWKTEPUNHZHGQMW3XJJU | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| XQKWLL26NELXXZRPIERWWAEWAULSH6B27ATNGGWAYMCX7D72KPBNRNM4Z4 | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| H2JIUECPJWYGXJU7INXKNL6W4TB553N5IZ2U54DZCHOLS3EJKAXXNO6HTQ | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 6E7BH63AGC3ISVYCYH2KLMDHVWBOWH42XKYJHJVST5CGDLMPMLJKVHU6UA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| UWOGJVRQSQXTA3CZNAQDMZYKPBDSPAID24AM5VKSABSCRLNR6T5ZGFZSNY | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| X6XGI7N5TQERK6XZGR2SSPLJ6NOWR2OO2RRIANSBUUQCD4J7QZLUIYD7YU | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 6MBLKQFWKEC4DISTIEC3VVF54JIUYS53DF2AZXR4OV4JD3N2KHHAAHRKAE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| POVMSS44VYIUFUTMUHGVWE6QITHHAPCPGXAR35X3SHRZ26XNGL2VVO7TRA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| ZENNEFKWWWD4EPXOUISCHZ4WAEA6OCOKYHO6XJMSNKW2CKEYO55SRCHGOI | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| RDOUHKOYGBVLFZLNUYSRZEXDIQNYA2UYLO754KBLROFGTWZX27TUCJG6KA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| FXD5JVVR7CSL5JFB7AR3TBVCGN6SKT33E7QXWYBMTPOHMKG52RHTAAEEOM | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| XUVB4IED2EVH4V6A6PQAHVFVG4CS5KVBZS7TBXMMI46UO6N3WTFVQIWZ4E | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 7JEQLV753FZ5MX6LD4QAKFUWY3FYYSVMZDJSGA4WAV62V6DKKSUTJQX6YA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| MDTQGGQLNPLKFBSF5D76R4436HSQW6HXMNGY6EEPSSJCTVYOC4Z3DLJBQQ | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| RTWPW2XN6YFOX4IOV2T3IHNSV3CKDK2IMHIVQF5PQIUXXDF7WUX3L77XOM | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 7RQPUFT2MURBSXUJDPI6KLBC3ETHM5RJALH4CBJ5XAQX3QFUNYPUPUA4GY | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| CYICM5HKBJ3XW75ROONEQLWIA2FWFFPAPG3FWO5WKGHJSGLH254WSFZVLA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| PJNM2X6RSOSUMX5H2CZT4XF47EPWYZ6ZSMOVFPOVU6LUI3YNYXTX5Z6MOY | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| VI4Y6RKSYPGET77257ZLFFX6YZIDJ5WJPC6CM54AYKVRNC4TYUEXQZEB6I | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| IBSY2VULCTARQ5IFPAKQGRBP3XJPFT76KD6NS4SKLCPSVCTYIATQXXZGFU | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| ZJXEOGXZP2MP43MALZYKNJ325MO77O3ZLDZQ6N2PFILYW5KEEMWT7DWZFE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| LOJOWFEBM5PXRPAXF4QFYELYGUYNP6SJZGWTMRFYVBEXN6TMPOQZ5QIRUE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| GQ3BDSGY6TAW3EDJJU3QECVMHSJCTJPSUENYAQWFGRHJOC5AWH3BPNMFJY | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| XRYPH52NECAWHQFTBC44CT4M3EPVDM5CEZ3I43DNQ6FV2NYMTN5T3HHO6Y | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| BGROHKGINDSBIOQL5ZW3ERTLOKFRUGA26AE4VZ6HSJ2KXHQFQO35TF6VSI | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 2EPEAQLNMIUW5Z7HUTWXJKXGDTIQQENZKNTLJMXJPJLYCL43NCUGPEGF7E | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| OZSKRYSC2OV5DDXHVDV62LI2DLRMMU6CXFC65SX5KZSDGS75AL2SAJXE3A | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| QRVHENCXAMGMNOUWZCTNMMS4JSDIEOUMJEKFDFLJPI3WKIP7EIA57LGI7I | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| LM5RWJQEUAQ4JUOQV4Y2H2EUIJUUHAAZO6KOU7JDXUZZMAGJW7AZEPF76Q | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| D7DHB7BRCATROAFLU3ZYDMJEODJQQF3HPMAGBFPUYP56CKOS627HN6TMBA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| OCBVEGO3LWO5WU4GTHVGINCUDJPC47SNN7EFNGOOI6XOAJ3YUUDA4553DQ | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| X5Q3RAJNGQVOLAPQRZGONLVW2IDIXPA4RV5TF7RQ53PPAPSKSR5QJX2CV4 | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| X3FUIZDKEARUPUV3ZXFJSDDGMT3NHRW3KRNHWF5I2IIWCXG7YLXDH2BOYQ | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| AEYWAZQSOAKZG6EMIUCKR3CVWACB2YV4KBL6CHHEG6FVLYCRHGPMW74RWE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| IKC6MQM5AXYP7DOUCOOYYG6IFGRLCTYFA3APZQISTZVA2CERR6HG5XDB2E | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| C4C7AQ7L3VHM3JSO4GV2DM2IGXBO3PESLZHLBT6H52VBWG67EEWSI7XCME | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| ZMAKLI52XAMI6LHOZBEBGIMH5NFDMN4KAIVWMHBJPKCLJ3IEPTYTP2VIBQ | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| RI57M5OWAYFVN656HOXUOLIS3R7UQUZBKA537ZWFJ3WA626NJRCPP4YUQ4 | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| QHQUK6OW7J6ZSDEW7HEUA3BVO6DAYB6AK7COY4PO4TA656D6Z3ZMXLPIF4 | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| GZBB2XPOJEOSI2XTPB44A44GNAMZVXZZGMTZA7ZBIBJGLBQXKVUV6QV6QU | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| G2O23E5GOULIMPPLL3SIBHVJ4EELHSUEYXXHUMFGYDKIXQQ72YLFWWM5AI | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| NTSBDDCIRAFSX7SZ24L3MTRIXHSBWZD2YSVMYIBWNEZRK6ZHT5SLDDH2DE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| XLJ6X4QDTTVPI2Q7BZYNKFLPHQEQSKFY32K22KSVAJOPS7YX6HS5YV7UKE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| GS2C54CPDSFW5SCX2Q7JUNTBTF7E4M3S2QW4T3NW2OGFPUGETLDUQK2VPA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| VMU7RW3K4XASYI2QOCQGW5BFCGOBZSF3J7ER6HEJ6FTECBIWLGYVP5AMCA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| PTU66JYXM6S5RHN4BWBAXKJS2WZHPYYU6XFGP7RUCJ4W3I7ORJOREY4WB4 | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 3FFV6H4QOGQ3TGVXL5BCFD7LLASGIV6BGFJWCLO2UYAGOCDF44VLMOESRE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| LHLFEJM7IFQMASJLPOZWLHT6FASHDELZJRJMOMBC43QMV23XEB5Z3D64ZI | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| WSRHR3GGSGFJF23LGHPRKY7Q5FADJVG2Q4YKVDF4DAJKOAH7P2H25SNHXI | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| H6QSRBMNX4A4R5NN5OOGJNWLPY4SZJYST5NFGFRG2SIKGMGYNGH32J6TSY | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| QDVPYRI7JL34UPOGABLWONHN3HEV4U32IXF2EDLMNZZHG2HRZ657HA3NOI | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| ZKQX6HWAVLW6DUK6U7COANUD5436N4ZKTIVDYHTVI3HPXI3JJIJNY2RUFQ | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| IS6UC3DYWIUHCAXI7NN7NV5GKHTWC6RBIIBBUQOKAZ5AVBPI4F7VYHPNZM | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 336TZA4OLFHZC3QARVYBD3UITMQUOWK3TYAIGADZASYWBBJKJ2ONRLX27E | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| Z5JDLZD4OPHBB3FSLRJBABJOXQF2KGMMPSFIVJG7F5OODX6NQH753CX65E | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| F5AYER4PGDDXO76YSPUM62PUC2F4ZM5K5YNVUK2FJ64IG2OH3NGGWXMPGE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 3FAIO76OJYZJ43DAATSY7BVRADHOXI5J3F5WLGRS4BL6JH6YYV75YPGSOE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| R5NPVNJ73ACTFQEXWTZ5UCFN2JIUVXIS3WIMTXHE3OT5GIJWB6LJSDSAFY | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| ZIFOIQHYZOD3WVC4JWZYIIANL2OXP5BJS7OBKA2LVWZI654VXYIRTJYXOY | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| E3ESZSCIY3K33V67QYT24FZ2WD4EVD4LXE6BV3ES4GV6DLPNIXUC2FVHFY | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| G4L6HCA75ZC36AU5TVLWEEVSUYH2WFLC3D6NGDZYUINTEGNXCKZGHGZH4M | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| BRH564X343CIDF6IIB3IKBOKH5HCQDDEAVXYBUNIPEY5VOZL3LVW5VJBUI | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| HU6HN5L52WCNU3CVO5NMLNNDRPMOBNWFRLZCRXKE7PNBT4LSMIMRLKYRPY | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| VL6PMBBEPE7UCII5G3N2FSPJWL7TM23P4E3O4RRGGLL4QGUYNEHE3E5NRE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 7QIZNQUL2EGDXSVJLAMH7CHZ5GJSJEFWIYVMNQ43ATIKTFNUKZBSHIU5M4 | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| S2JSGHK4H2DPKRNG3B5MYNGS3TH2GOSZ3KW55P6QSB4ZM3MXLQ6LHKJ7G4 | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| WIMSLREUGYI7FOBNKRAKYXVLJLKRSKNAMTGCGGSLP2DOV7PUKNJEOVXZFA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| DPZJT33TF2PNBVW7GLECNJGE3YJ3YK42XWAE4L7RX7NPMBANPWD37RTVZ4 | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| VXBTFGTYY2GFA7FLPD37LNSCIWVDJYLBFHUQBS5ECXZ7SRKHF7KKBBEPOQ | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| IGCUVHDMLN3L53E55OZ23MOORUNHHWCFXSSUYN2FGKRPVHKATIBBKJ77DA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| NPJWVHTMS5MCW7N2OANLFTCOHDTFDTDY4NKCU6A73NQQK2KO6J55P6RJNI | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| MVDMOZAMYT5I4AKCA7B74B4EXOFF3FNJVR3XPEZS6W3755B2N33WKC5CSM | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| ZR2ROZJTCZT5WD2W3HBCZRWJBPNNH56B2PZWNH5EHKPFTBYA37CMRECDS4 | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| 5CX2QE2A4TV6J43SLWVTZ2VPARMSHQ5DA7YQ2NTYDCYJVVSZSGJPRT6KDA | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| KPGUBH4WGIGLGHUVWVIXHPI5KSTYL23TKKQQXJXJ6FH54KJBJGTRQYBEJM | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| SHQ5SOGOSMNW4UQRBIVPEYOWWH3R7DU26WXLUG7SDEAPZMC3E5M2PQF4KI | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |
| SGVHD46EF2DCAFTPEFTFLKWHIFGH2LTJ732ULSDX5RMYLABWLALF5LM2RE | MERCHANT-FUNDED | 1 | 0.100000 (0.1142%) | created by merchant; merchant sent 0.25 ALGO; merchant sent 0.1 USDC ×1 (100% of paid); fleet of 634 via 5T6GTE…JFTU; throwaway wallet |

Top 100 of 874 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | http://api.scrape402.site/scrape | 876 (100.0000%) | 87.600000 (100.0000%) | 874 | 0 | 873 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: api.scrape402.site, scrape402.vercel.app.

Custom-domain candidates: api.scrape402.site. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| api.scrape402.site | custom_domain_candidate | yes, cached | 2026-10-05T18:32:10.079000+00:00 | 3 |
| scrape402.vercel.app | hosting_provider_domain | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| api.scrape402.site | Scrape402 \| Pay-per-request web scraping API for AI agents | Scrape402 | Scrape402 is a pay-per-request web scraping API for autonomous AI agents. Send any URL, bypass Cloudflare and anti-bot protections, get clean markdown — paid via x402 USDC micro-payments on Algorand. | https://api.scrape402.site/public/logo.png | https://api.scrape402.site/public/logo.png | not recorded |
| scrape402.vercel.app | Scrape402 | not recorded | Scrape402 is a pay-per-request infrastructure API that solves one of the biggest bottlenecks in the AI industry: giving autonomous agents reliable access to the internet. | not recorded | https://api.scrape402.site/public/logo.png | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| api.scrape402.site | A2A Agent Card | scrape402 | http://api.scrape402.site/.well-known/agent-card.json | Pay-per-request web scraping API for autonomous AI agents. Send a URL, get clean markdown. Paid natively via x402 USDC micro-payments on Algorand. |
| api.scrape402.site | AI Plugin | scrape402 | http://api.scrape402.site/.well-known/ai-plugin.json | Pay-per-request web scraping API for AI agents. Send any URL, bypass anti-bot protections, and get clean markdown — paid via x402 USDC on Algorand. |
| api.scrape402.site | x402 Discovery | scrape402 | http://api.scrape402.site/.well-known/x402 | x402-gated web scraping API. Extract clean markdown from any URL, paid per request with USDC on Algorand. |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 3 |
| Agent document types | ["agent-card", "ai-plugin", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 2 |
| Description count | 2 |
| Mime type count | 2 |
| Accepts count | 2 |
| Discovery count | 2 |
| Input documentation count | 2 |
| Output documentation count | 2 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-09 | 22 | 2.200000 | 22 | 0 | 22 (100.0000%) |
| 2026-08-10 | 17 | 1.700000 | 17 | 0 | 17 (100.0000%) |
| 2026-08-11 | 19 | 1.900000 | 19 | 0 | 19 (100.0000%) |
| 2026-08-12 | 19 | 1.900000 | 19 | 0 | 19 (100.0000%) |
| 2026-08-13 | 16 | 1.600000 | 16 | 0 | 16 (100.0000%) |
| 2026-08-14 | 15 | 1.500000 | 15 | 0 | 15 (100.0000%) |
| 2026-08-15 | 11 | 1.100000 | 11 | 0 | 11 (100.0000%) |
| 2026-08-16 | 35 | 3.500000 | 35 | 0 | 35 (100.0000%) |
| 2026-08-17 | 29 | 2.900000 | 29 | 0 | 29 (100.0000%) |
| 2026-08-18 | 28 | 2.800000 | 28 | 0 | 28 (100.0000%) |
| 2026-08-19 | 29 | 2.900000 | 29 | 0 | 29 (100.0000%) |
| 2026-08-20 | 23 | 2.300000 | 23 | 0 | 23 (100.0000%) |
| 2026-08-21 | 31 | 3.100000 | 30 | 0 | 29 (93.5484%) |
| 2026-08-22 | 31 | 3.100000 | 31 | 0 | 31 (100.0000%) |
| 2026-08-23 | 33 | 3.300000 | 33 | 0 | 33 (100.0000%) |
| 2026-08-24 | 23 | 2.300000 | 23 | 0 | 23 (100.0000%) |
| 2026-08-25 | 23 | 2.300000 | 23 | 0 | 23 (100.0000%) |
| 2026-08-26 | 17 | 1.700000 | 17 | 0 | 17 (100.0000%) |
| 2026-08-27 | 2 | 0.200000 | 2 | 0 | 2 (100.0000%) |
| 2026-08-28 | 3 | 0.300000 | 3 | 0 | 3 (100.0000%) |
| 2026-08-29 | 5 | 0.500000 | 5 | 0 | 5 (100.0000%) |
| 2026-08-30 | 6 | 0.600000 | 6 | 0 | 6 (100.0000%) |
| 2026-08-31 | 3 | 0.300000 | 3 | 0 | 3 (100.0000%) |
| 2026-09-20 | 3 | 0.300000 | 3 | 0 | 3 (100.0000%) |
| 2026-09-21 | 5 | 0.500000 | 5 | 0 | 5 (100.0000%) |
| 2026-09-22 | 6 | 0.600000 | 6 | 0 | 6 (100.0000%) |
| 2026-09-23 | 6 | 0.600000 | 6 | 0 | 6 (100.0000%) |
| 2026-09-24 | 208 | 20.800000 | 208 | 0 | 208 (100.0000%) |
| 2026-09-25 | 5 | 0.500000 | 5 | 0 | 5 (100.0000%) |
| 2026-09-26 | 3 | 0.300000 | 3 | 0 | 3 (100.0000%) |

Last 30 of 48 active days; all in the daily CSV.
