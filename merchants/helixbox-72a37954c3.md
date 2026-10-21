# HelixBox — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 52).

## Identity and accounts

Merchant ID: `QVFZV05ITzZRV0I0QUI0U0hJVk1OWkwy`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 7LO7JTJT4DJU5N2KF5Y2HB4WATGPPSOB2O3BFAR32DC3YMA5PMZ6TYEBDQ |
| Algorand | AQYWNHO6QWB4AB4SHIVMNZL2QN2ZQIYYO3Z27DJCUOILZ43YGGZUIPAURY |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 52 | HelixBox | Exact submitted wallet AQYWNHO6QWB4AB4SHIVMNZL2QN2ZQIYYO3Z27DJCUOILZ43YGGZUIPAURY is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 3,919 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 993.750000 | USDC settled. |
| Unique payer accounts | 46 | Distinct accounts that paid. |
| Synthetic-indicated | 3,900 (99.5152%) · 987.250000 USDC (99.3459%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 19 (0.4848%) · 6.500000 USDC (0.6541%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 102 · 27.250000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-24 18:22:21 UTC / 2026-10-06 11:38:22 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/helixbox-72a37954c3-transactions.csv.gz) · [All endpoints](../evidence/helixbox-72a37954c3-endpoints.csv) · [Payer evidence](../evidence/helixbox-72a37954c3-payers.csv) · [Daily metrics](../evidence/helixbox-72a37954c3-daily.csv) · [Site and catalog data](../evidence/helixbox-72a37954c3-site-and-catalog.json)

**Flag — self-payments excluded:** 102 settlements / 27.250000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| FLEET | 40 (1.0207%) | 22.250000 (2.2390%) |
| MERCHANT-FUNDED | 3,797 (96.8870%) | 949.250000 (95.5220%) |
| NO-LINK-DETECTED | 19 (0.4848%) | 6.500000 (0.6541%) |
| SELF | 63 (1.6076%) | 15.750000 (1.5849%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| O4T77GRKCMFCWO4KXTORZXI3LHUSA4Z7NK5L5LTZZ4M3CWYBWROTA5WTFE | MERCHANT-FUNDED | 3,479 | 869.750000 (87.5220%) | merchant sent 878 USDC ×26 (101% of paid); throwaway wallet; 24/7 over 24d; same funder as merchant (hub) |
| MSMMPCPYQ5QBJQ7C3WZ2GTBQXJ222Z3ZOL6YZ5BCQWLQA6MGHKVJJDBDDE | MERCHANT-FUNDED | 100 | 25.000000 (2.5157%) | merchant sent 20.00 USDC ×1 (80% of paid); throwaway wallet |
| SS36HWY3YYFF424HCFKN4EFYBOGUNCADGIVJJYNSCGYAGC5QWVFHX3TRGE | MERCHANT-FUNDED | 94 | 23.500000 (2.3648%) | merchant sent 23.40 USDC ×2 (100% of paid); throwaway wallet |
| AQYWNHO6QWB4AB4SHIVMNZL2QN2ZQIYYO3Z27DJCUOILZ43YGGZUIPAURY | SELF | 49 | 12.250000 (1.2327%) | merchant's own address; merchant sent 14.25 USDC ×18 (116% of paid); same funder as merchant (hub) |
| WDK4RQ24NBIYHNGQA34JOH6QOBXLEM535H3DHBALSRHENYR3QEYBSBEPMI | MERCHANT-FUNDED | 16 | 4.000000 (0.4025%) | merchant sent 5.00 USDC ×1 (125% of paid); fleet of 9 via O4T77G…WTFE; throwaway wallet |
| ZYXMHYKHKJUREDAEXADVUZMPP26WMSYNZOVHKBZ63I7G7EIR2JK545GCIY | MERCHANT-FUNDED | 16 | 4.000000 (0.4025%) | merchant sent 5.00 USDC ×1 (125% of paid); fleet of 9 via O4T77G…WTFE; throwaway wallet |
| F44LNIKTRSM7FEP7RSYSUVNONXX3JUSHCXSWYUUXOC7ETKAH7OVVMAFDWI | MERCHANT-FUNDED | 15 | 3.750000 (0.3774%) | merchant sent 5.00 USDC ×1 (133% of paid); fleet of 9 via O4T77G…WTFE; throwaway wallet |
| 7LO7JTJT4DJU5N2KF5Y2HB4WATGPPSOB2O3BFAR32DC3YMA5PMZ6TYEBDQ | SELF | 14 | 3.500000 (0.3522%) | merchant's own address; merchant sent 39.25 USDC ×52 (1121% of paid); throwaway wallet; same funder as merchant (hub) |
| PSHPWQMMSM5NFSJMNJ635LAJ4U3UI6UQ3WSK3E6HV4MWQIF7TTG4KV3P4A | FLEET | 5 | 3.000000 (0.3019%) | fleet of 8 via O4T77G…WTFE; throwaway wallet |
| 35FUAFPD7Q37FZRADUCYFOS42GJ2RWQU5AAKIYKNOTI7SSLLYOTQDI4L4E | FLEET | 5 | 3.000000 (0.3019%) | fleet of 8 via O4T77G…WTFE; throwaway wallet |
| ML2LATOSQ7CE36ICWX2WRCP5OUJAQ3K4Z7LSWLCO6OKLJHCBXYIWV37BDA | FLEET | 5 | 3.000000 (0.3019%) | fleet of 8 via O4T77G…WTFE; throwaway wallet; 50% of gaps &lt; 60s |
| YCWFQXYDDFEGYISSK2ACYRIXKQXPHPUVQYBRB3P5B4CMJCPNLZFVBC3CLE | FLEET | 5 | 3.000000 (0.3019%) | fleet of 8 via O4T77G…WTFE; throwaway wallet |
| LT675THEUM2ZKP3SDFWB5BCFE5YPLLDTEXYPRNGVTAYQK6TFDII3RYA2VY | NO-LINK-DETECTED | 10 | 2.500000 (0.2516%) | throwaway wallet; same funder as merchant (hub) |
| CSGNQCBEKLMKWYCCUQ3CHG4H6OORBF5DQ5QEY3BWCLF6XKVRTDGEQTQK5E | NO-LINK-DETECTED | 3 | 2.500000 (0.2516%) |  |
| SEBYJ6ZBCV5LDL5EELGY6OXHRDIXVF2SOCMLNRRTSZEXLKXOK6VZN62DFQ | FLEET | 3 | 2.500000 (0.2516%) | fleet of 8 via O4T77G…WTFE; throwaway wallet |
| NNJVYNGVHFUF4DGFXVJ3HIN5XGTZZHE774K6MBPPLXSL24RMWXBTIZOM6M | FLEET | 2 | 2.250000 (0.2264%) | fleet of 8 via O4T77G…WTFE; throwaway wallet |
| P6PRD53PLYPGZO4K6GNS5WPCZFMCEXJMSP4KYR4OPWCTTGKJEYQX7EUMDY | FLEET | 1 | 2.000000 (0.2013%) | fleet of 8 via O4T77G…WTFE; throwaway wallet |
| TFGNEPI7N6K2BBGKV64UM2UXYOABBHXQDGBOBBGPM2EKVZ5I27PIE2BXSY | MERCHANT-FUNDED | 7 | 1.750000 (0.1761%) | merchant sent 2.00 USDC ×1 (114% of paid); fleet of 9 via O4T77G…WTFE; throwaway wallet |
| M6JQNJVX32HEN2LS5W2WX2PMSXPDHHKADVUATIQ5KQIVVVHSVILQNOS62A | NO-LINK-DETECTED | 6 | 1.500000 (0.1509%) | throwaway wallet; is AgentMesh's address; pays 5 merchants |
| LCF4AGK7LOOOCYK7ULOCQETRDHOVU5URBZY62WOWLCVGJARNWASFI766RA | MERCHANT-FUNDED | 6 | 1.500000 (0.1509%) | created by merchant; merchant sent 1.00 ALGO; merchant sent 17.00 USDC ×2 (1133% of paid) |
| E3YWHZI33DPPGNDRMLYX4C7BXAJ4TRC2O5THHBAIX7HLVSGBH7VMXQNZX4 | MERCHANT-FUNDED | 4 | 1.000000 (0.1006%) | merchant sent 1.00 USDC ×1 (100% of paid); fleet of 9 via O4T77G…WTFE; throwaway wallet |
| W4BZOZE3WLVP6DUWEOAQTQXIJMQ3G627U6SOGPMLJRI2VS7CNNGBYNIOJA | FLEET | 4 | 1.000000 (0.1006%) | fleet of 9 via O4T77G…WTFE; throwaway wallet |
| P2BLMNJHH3QOUN5H6KSCZ6ADC2EWHR2AXQ42B4U2IKRXMAKMGYPW5FNU7Y | FLEET | 4 | 1.000000 (0.1006%) | fleet of 9 via O4T77G…WTFE; throwaway wallet |
| 75LL7LDO5HZAFU6A6Y6HVPOKQ7ES3QQXXUPKPGY6DFOHTEEO7N4MGQTQ7M | FLEET | 4 | 1.000000 (0.1006%) | fleet of 9 via O4T77G…WTFE; throwaway wallet |
| KSEODRXGPTMMIBDEWFVR3U53L6FMOPAJ5MKXOMUDOJZPNYQTG3CDFIP6XU | MERCHANT-FUNDED | 4 | 1.000000 (0.1006%) | merchant sent 1.00 USDC ×1 (100% of paid); fleet of 9 via O4T77G…WTFE; throwaway wallet |
| LE73AAYQNIUONEJ7NROZVJV733LWYN6N7PLOZOSCXYMBMFJGNMMHBJNULQ | MERCHANT-FUNDED | 4 | 1.000000 (0.1006%) | created by merchant; merchant sent 0.6 ALGO; merchant sent 1.00 USDC ×1 (100% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| LSFDMXABOERNKGCJPQVCRXYB5BZ5P4NNCCWSLP72DMM4RWRLV6PHYA4U5A | MERCHANT-FUNDED | 4 | 1.000000 (0.1006%) | created by merchant; merchant sent 0.6 ALGO; merchant sent 1.00 USDC ×1 (100% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| ISE3ZOC72FPQ6JCJTXW5ZWZ2UV2JAWUSLAH6WIY3ZH7CBNMLYWJIEOMUCY | MERCHANT-FUNDED | 4 | 1.000000 (0.1006%) | created by merchant; merchant sent 0.6 ALGO; merchant sent 1.00 USDC ×1 (100% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| CNKWCVTLZE7YIGF4L36SCTIB55QIK67X3K3HT3JDHPCMZD3BCVBWML6L5M | MERCHANT-FUNDED | 4 | 1.000000 (0.1006%) | created by merchant; merchant sent 0.6 ALGO; merchant sent 1.00 USDC ×1 (100% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| FJD44USSVHDJ3OXHN6T4MOKTZOJHT2G5XSC5Q46CGNKNH5NYNMOG5TQFT4 | MERCHANT-FUNDED | 4 | 1.000000 (0.1006%) | created by merchant; merchant sent 0.6 ALGO; merchant sent 1.00 USDC ×1 (100% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| YOBSFRGAQJ7FZSG3PMF7TA325M55WNORF3JJ4PMO3BNMH3X6I42GNP4AGA | MERCHANT-FUNDED | 4 | 1.000000 (0.1006%) | created by merchant; merchant sent 0.6 ALGO; merchant sent 1.00 USDC ×1 (100% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| H73NRDS3MCYRJZC4OW2GRK4RLB7TDJ4O6RA5XK3OECVLYF6BUW3STKJN7U | MERCHANT-FUNDED | 4 | 1.000000 (0.1006%) | created by merchant; merchant sent 0.6 ALGO; merchant sent 1.00 USDC ×1 (100% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| EQJ3PLEON2OQ7FKP7MBB6SR7Z6NJY4AA3GNXWMCCNY3QOE23VF7YHZ3JRM | MERCHANT-FUNDED | 4 | 1.000000 (0.1006%) | created by merchant; merchant sent 0.6 ALGO; merchant sent 1.00 USDC ×1 (100% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| OEWY4GDW3IAPY5UQPRPEQHLRYSKEJVT2TSLUNMWN5QUGTNLJA67JMP6R5U | MERCHANT-FUNDED | 4 | 1.000000 (0.1006%) | created by merchant; merchant sent 0.6 ALGO; merchant sent 1.00 USDC ×1 (100% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| O43S6NLJE66CY53D7TNKDHNKLWIMWWNQVW3UI5T2QXZJERRE3KKV7QV72A | FLEET | 2 | 0.500000 (0.0503%) | fleet of 8 via O4T77G…WTFE; throwaway wallet |
| USCFUOIICXAT2FTHTUSK5IIII2ITW6QJ24SLT6LTOLE7XD2CDUL6BGNOWA | MERCHANT-FUNDED | 2 | 0.500000 (0.0503%) | merchant sent 0.5 USDC ×1 (100% of paid); throwaway wallet; pays 3 merchants |
| LDKTBVEIVGJXYKNWSC7M6ATII6IZ2YERDQ6XJDLXI7AVULRHOY4BT3WDFA | MERCHANT-FUNDED | 2 | 0.500000 (0.0503%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 1.00 USDC ×1 (200% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| KJQJLZPCAB5PQTLJIEOFWXEHBPG365QTAIL46FVQ2HQDSUOWQVPMUHZL4A | MERCHANT-FUNDED | 2 | 0.500000 (0.0503%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 2.00 USDC ×1 (400% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| LKFYJG4GHVGVAPGEUOLYBMMMI5STIUUN3G7NR6AXP3ODFQVXSWSN23XJPA | MERCHANT-FUNDED | 2 | 0.500000 (0.0503%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 1.00 USDC ×1 (200% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| TMFUXXR2LXQE22T2ZIGNDPWUPWTYNDFG2JHT5NEJQXIDAL76VDG4V6VVHY | MERCHANT-FUNDED | 2 | 0.500000 (0.0503%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 1.00 USDC ×1 (200% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| CYZHKZPLFTD5OYJXTP7Z7L34BUDJMDONZZ5ONIB73BHJL5TRFSUEE657KI | MERCHANT-FUNDED | 2 | 0.500000 (0.0503%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 1.00 USDC ×1 (200% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| GPRX6DJQWONDCFIT2SMTPZJMOV3XSL3VS7NRN6DBVTG3G7YI5VF56LA32Y | MERCHANT-FUNDED | 2 | 0.500000 (0.0503%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 1.00 USDC ×1 (200% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| U5UXB5XMIEFM7DPJFOY7EZDO6A2U6QOU5YVIVAZHPIYJ6GHIDDIPZ22NDA | MERCHANT-FUNDED | 2 | 0.500000 (0.0503%) | created by merchant; merchant sent 0.6 ALGO; merchant sent 1.25 USDC ×1 (250% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| 6XRCRKZBRRC6BR3SQNRJRCEI3U73DGBDYTNS7FVBYAJ3FDR23CMFFCGFV4 | MERCHANT-FUNDED | 2 | 0.500000 (0.0503%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 1.00 USDC ×1 (200% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |
| XVX6UFO7MFFQPOYVVDNBQ3ZHRYNGJ6YTXYX654JUSAZHII6JZCAXKLEVAA | MERCHANT-FUNDED | 1 | 0.250000 (0.0252%) | created by merchant; merchant sent 5.00 ALGO; throwaway wallet |
| CQIO7W2JWKJRFFYK2J4UMLOQYCUB4UNM5UNOMG2L4YCIGHNCBHNX6EOFN4 | MERCHANT-FUNDED | 1 | 0.250000 (0.0252%) | created by merchant; merchant sent 0.3 ALGO; merchant sent 1.00 USDC ×1 (400% of paid); fleet of 18 via AQYWNH…AURY; throwaway wallet |

Top 46 of 46 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://helixbox-manager.onrender.com/v2/x402/agent-session-1hour | 2,015 (51.4162%) | 503.750000 (50.6918%) | 3 | 0 | 2013 |
| POST | https://helixbox-manager.onrender.com/v2/x402/cli/hour | 1,861 (47.4866%) | 465.250000 (46.8176%) | 44 | 0 | 1845 |
| POST | https://helixbox-manager.onrender.com/v2/x402/codex-agent | 34 (0.8676%) | 8.500000 (0.8553%) | 1 | 0 | 34 |
| POST | https://helixbox-manager.onrender.com/v2/x402/premium/week | 8 (0.2041%) | 16.000000 (1.6101%) | 8 | 0 | 7 |
| POST | https://helixbox-manager.onrender.com:10000/v2/x402/cli/hour | 1 (0.0255%) | 0.250000 (0.0252%) | 1 | 0 | 1 |

Top 5 of 5 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: helix-box.vercel.app, helixbox-manager.onrender.com, helixbox-manager.onrender.com:10000.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| helix-box.vercel.app | hosting_provider_domain | yes, cached | 2026-10-05T23:57:42.264000+00:00 | 0 |
| helixbox-manager.onrender.com | hosting_provider_domain | yes, cached | 2026-10-06T01:41:10.250000+00:00 | 2 |
| helixbox-manager.onrender.com:10000 | hosting_provider_domain | not established | not recorded | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| helix-box.vercel.app | HelixBox \| Your development environment, in your pocket | HelixBox | Your laptop does the work. Keep building from your phone. Coding agents, editor, browser, terminal, and Git in one app. | https://helix-box.vercel.app/assets/images/helixbox-splash.png | https://helix-box.vercel.app/assets/images/helixbox-splash.png | not recorded |
| helixbox-manager.onrender.com | HelixBox \| Your development environment, in your pocket | HelixBox | Your laptop does the work. Keep building from your phone. Coding agents, editor, browser, terminal, and Git in one app. | https://helix-box.vercel.app/assets/images/helixbox-splash.png | https://helix-box.vercel.app/assets/images/helixbox-splash.png | not recorded |
| helixbox-manager.onrender.com:10000 | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| helixbox-manager.onrender.com | x402 Discovery | HelixBox | https://helixbox-manager.onrender.com/.well-known/x402 | Use your full development environment from your phone with time-bound, micro-billed agent sessions. |
| helixbox-manager.onrender.com | llms.txt | HelixBox | https://helixbox-manager.onrender.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | True |
| Linked domain count | 3 |
| Cached domain metadata count | 3 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 2 |
| Agent document types | ["llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 7 |
| Description count | 7 |
| Mime type count | 7 |
| Accepts count | 7 |
| Discovery count | 7 |
| Input documentation count | 7 |
| Output documentation count | 2 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02 | 90 | 22.500000 | 1 | 0 | 90 (100.0000%) |
| 2026-09-03 | 71 | 17.750000 | 1 | 0 | 71 (100.0000%) |
| 2026-09-04 | 67 | 16.750000 | 1 | 0 | 67 (100.0000%) |
| 2026-09-05 | 218 | 54.500000 | 1 | 0 | 218 (100.0000%) |
| 2026-09-06 | 569 | 142.250000 | 2 | 0 | 569 (100.0000%) |
| 2026-09-07 | 600 | 150.000000 | 1 | 0 | 600 (100.0000%) |
| 2026-09-08 | 198 | 49.500000 | 3 | 0 | 192 (96.9697%) |
| 2026-09-11 | 270 | 67.500000 | 1 | 0 | 270 (100.0000%) |
| 2026-09-13 | 218 | 54.500000 | 1 | 0 | 218 (100.0000%) |
| 2026-09-15 | 152 | 38.000000 | 1 | 0 | 152 (100.0000%) |
| 2026-09-16 | 80 | 20.000000 | 1 | 0 | 80 (100.0000%) |
| 2026-09-17 | 170 | 42.500000 | 2 | 0 | 160 (94.1176%) |
| 2026-09-18 | 135 | 33.750000 | 1 | 0 | 135 (100.0000%) |
| 2026-09-19 | 105 | 26.250000 | 1 | 0 | 105 (100.0000%) |
| 2026-09-20 | 3 | 2.500000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-21 | 28 | 19.250000 | 8 | 0 | 28 (100.0000%) |
| 2026-09-23 | 240 | 60.000000 | 2 | 0 | 240 (100.0000%) |
| 2026-09-24 | 1 | 0.250000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-25 | 12 | 3.000000 | 2 | 0 | 12 (100.0000%) |
| 2026-09-26 | 7 | 1.750000 | 1 | 0 | 7 (100.0000%) |
| 2026-09-27 | 5 | 1.250000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-28 | 22 | 5.500000 | 1 | 0 | 22 (100.0000%) |
| 2026-09-29 | 41 | 10.250000 | 4 | 0 | 41 (100.0000%) |
| 2026-09-30 | 34 | 8.500000 | 3 | 0 | 34 (100.0000%) |
| 2026-10-01 | 158 | 39.500000 | 3 | 0 | 158 (100.0000%) |
| 2026-10-02 | 20 | 5.000000 | 1 | 0 | 20 (100.0000%) |
| 2026-10-03 | 20 | 5.000000 | 1 | 0 | 20 (100.0000%) |
| 2026-10-04 | 45 | 11.250000 | 9 | 0 | 45 (100.0000%) |
| 2026-10-05 | 51 | 12.750000 | 14 | 0 | 51 (100.0000%) |
| 2026-10-06 | 38 | 9.500000 | 19 | 0 | 38 (100.0000%) |

Last 30 of 35 active days; all in the daily CSV.
