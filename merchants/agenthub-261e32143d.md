# AgentHub — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 81).

## Identity and accounts

Merchant ID: `RzNZVlRQVVJLNlZGU001Q1hFSDdRRlRa`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | G3YVTPURK6VFSM5CXEH7QFTZXLCXBJL6UMAIUUYJO4P2XF3MHQ4FUHYYB4 |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 81 | AgentHub | Exact submitted wallet G3YVTPURK6VFSM5CXEH7QFTZXLCXBJL6UMAIUUYJO4P2XF3MHQ4FUHYYB4 is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 33,715 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 3,502.775000 | USDC settled. |
| Unique payer accounts | 48 | Distinct accounts that paid. |
| Synthetic-indicated | 32,447 (96.2391%) · 3,371.705000 USDC (96.2581%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 1,268 (3.7609%) · 131.070000 USDC (3.7419%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-09 18:38:33 UTC / 2026-10-06 00:09:28 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/agenthub-261e32143d-transactions.csv.gz) · [All endpoints](../evidence/agenthub-261e32143d-endpoints.csv) · [Payer evidence](../evidence/agenthub-261e32143d-payers.csv) · [Daily metrics](../evidence/agenthub-261e32143d-daily.csv) · [Site and catalog data](../evidence/agenthub-261e32143d-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| FLEET | 24,880 (73.7950%) | 2,704.530000 (77.2111%) |
| MERCHANT-FUNDED | 7,567 (22.4440%) | 667.175000 (19.0470%) |
| NO-LINK-DETECTED | 1,268 (3.7609%) | 131.070000 (3.7419%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| XCBOQCLPKGO4KRIHSXVWTBULKFYZWKJQJ4SQFB7JS4IJ2FHKPBEBFEKZLU | FLEET | 4,580 | 511.360000 (14.5987%) | fleet of 5 via PT4OJD…UW2Y; 100% of gaps &lt; 60s |
| X6UM63K3UTXEHG2A2YO4SNSIVN2HLDJAMEPXGM4FYXBEXGL6MUHHU7POC4 | FLEET | 3,553 | 396.810000 (11.3284%) | funded by linked payer XCBOQC…KZLU; 100% of gaps &lt; 60s |
| VGNN7ZP6D3ROPCUXQUT4U7E3GLIUZXZZNC562T4NY7GHU2NVDMAASXLOHI | FLEET | 3,219 | 357.950000 (10.2190%) | fleet of 5 via PT4OJD…UW2Y; 100% of gaps &lt; 60s |
| FYFMQL2RMMWHHQSKW3IKO5EZJGOGB7RM4DJRJN2KEL35STU5HJ5O6FNLUI | FLEET | 3,081 | 343.530000 (9.8074%) | fleet of 5 via PT4OJD…UW2Y; 100% of gaps &lt; 60s |
| XXVL44QOVPLEAR7D5B4U7ELP7ZPAPKGW5IURNQWIYAUXM3IXTLR7WYPKRU | FLEET | 3,035 | 341.860000 (9.7597%) | fleet of 5 via PT4OJD…UW2Y; 100% of gaps &lt; 60s |
| MPLIJCDIMUZS7C4IGEXNPLGQN22W2BUHDH5PJ4SXBMDSCNUYHIXZVETGIA | FLEET | 2,527 | 274.620000 (7.8401%) | funded by linked payer OWRILK…QLPA; 100% of gaps &lt; 60s |
| PT4OJDMDLR7GAPGGMJ7X57LS3PK47BRVXT7USQRE3YH6FEQ7L2FXDJUW2Y | MERCHANT-FUNDED | 2,865 | 271.590000 (7.7536%) | merchant sent 315 USDC ×4 (116% of paid); 100% of gaps &lt; 60s |
| VGRBELPP3WIQTXBPQQYSEDXHC3PWYLPZGYZBJUNCBDP5SECXNM2VCZQG3E | FLEET | 1,065 | 117.890000 (3.3656%) | fleet of 5 via PT4OJD…UW2Y; 100% of gaps &lt; 60s |
| MUVW2RFKNVHWX4CNF6YIYNMX5EHK7TW3ERUDPDAQVFG4IRH5CDQINUQVVM | MERCHANT-FUNDED | 924 | 72.390000 (2.0666%) | created by merchant; merchant sent 10.00 ALGO; merchant sent 568 USDC ×15 (785% of paid); fleet of 3 via G3YVTP…YYB4; throwaway wallet; 91% of gaps &lt; 60s |
| PNCUQOLMQV7GMZDSQ2DQCYUITQVYDT3OKD5245FOSJU76KY3FOCXHIU4QU | MERCHANT-FUNDED | 709 | 66.950000 (1.9113%) | merchant sent 4.00 ALGO; merchant sent 679 USDC ×20 (1014% of paid); throwaway wallet; 87% of gaps &lt; 60s |
| TVLQ5NN2BLJNWBLPQNN2S63L6KPI5FHG745OZKPNZY5QWEDCIMPXIXSCYE | MERCHANT-FUNDED | 680 | 62.175000 (1.7750%) | created by merchant; merchant sent 1.50 ALGO; merchant sent 504 USDC ×14 (811% of paid); fleet of 3 via G3YVTP…YYB4; throwaway wallet; 91% of gaps &lt; 60s |
| 76CAH6WPMQDJ42CHR6QI7UJ77R4O3T4RANBQNHFEC457CEN6HE6OIDOBPI | MERCHANT-FUNDED | 613 | 58.640000 (1.6741%) | created by merchant; merchant sent 1.50 ALGO; merchant sent 646 USDC ×16 (1101% of paid); fleet of 3 via G3YVTP…YYB4; 89% of gaps &lt; 60s |
| 5DBZ4CSWGWQWYRRZNUZQUXEUOHN5CUPGSEKDPKUBABUSNKCHP6HJVIZMNE | NO-LINK-DETECTED | 440 | 48.020000 (1.3709%) | 95% of gaps &lt; 60s; same funder as merchant (hub) |
| WEL2AJL5J3GRUJXDTAJAGLOZUUSFVY6PSXRO3D7POVLN6JQPLSNWGNNH2I | FLEET | 431 | 47.580000 (1.3584%) | funded by linked payer EZQXFB…YFYE; 97% of gaps &lt; 60s |
| AW2N5WCCB3IUJHIATLCMFHDMT7SYLTRO5OIHB7PWP5OUHQXDI657BGQDQU | NO-LINK-DETECTED | 379 | 42.270000 (1.2068%) | 99% of gaps &lt; 60s; same funder as merchant (hub) |
| 263ZPT7K6POJTPOM2XBJ2PDJPWCQ54Y7MXU7EH77VS57UJXV7YH5CTT4EM | FLEET | 351 | 37.970000 (1.0840%) | created 1 linked payer; 99% of gaps &lt; 60s |
| XA4LWKAMJUUPSDQIMTIGYNMXXIU6OTJNI4VNNR7YIF3P7TPVGRPGRTYRHQ | FLEET | 321 | 36.410000 (1.0395%) | funded by linked payer TVLQ5N…SCYE; 84% of gaps &lt; 60s |
| YU7U25OAFSRJFFVLB4UYIMXMZNN2OYJKHCY7BYO5UREETDMFEKQJBQXCTU | FLEET | 284 | 32.620000 (0.9313%) | funded by linked payer 76CAH6…OBPI; 78% of gaps &lt; 60s |
| QLJPKHO2SGJS3YTZZOQ5LIGROZFEQAVGOSOH6D4OHB5QCKK6AANVD3SVEI | MERCHANT-FUNDED | 326 | 29.720000 (0.8485%) | created by merchant; merchant sent 1.00 ALGO; merchant sent 29.00 USDC ×7 (98% of paid); throwaway wallet; 98% of gaps &lt; 60s |
| KEBU6EI3ESC2KIDPQYR6BRT2YQLXSBVFXL22DIM6FSSMYEJP7P5SYILK4Q | FLEET | 278 | 29.120000 (0.8313%) | fleet of 7 via WJ7BRI…V7GY; 99% of gaps &lt; 60s |
| FEILXZHHT5WFZOQ7EN7ACWVCMVOLDKQZ3ELZWIPKEVSKZFDLPFBESSGQWU | FLEET | 270 | 28.800000 (0.8222%) | funded by linked payer VPVLI3…O7DY; 96% of gaps &lt; 60s |
| 4VIZ4PGZ6J6R45PKFMUM6FVKHQ62M3YH33RDGLHS5NMEJB2ZGMSIHLQZNY | NO-LINK-DETECTED | 256 | 28.300000 (0.8079%) | throwaway wallet; 86% of gaps &lt; 60s |
| OWRILKHHXI5IAPU7YPELJQ75KLBYECZ4PQOJCDLAXI3KIPNFYMPZPLQLPA | MERCHANT-FUNDED | 384 | 26.830000 (0.7660%) | created by merchant; merchant sent 1.00 ALGO; merchant sent 1.00 USDC ×1 (3.7% of paid); 92% of gaps &lt; 60s |
| A3MK6AK5JUTSNK3CSSOLSOQOSY7YFQHWCUYV43CAH5RAKK24J3CD24YOM4 | MERCHANT-FUNDED | 297 | 24.770000 (0.7072%) | merchant sent 29.45 USDC ×8 (119% of paid); throwaway wallet; 96% of gaps &lt; 60s |
| VPVLI3HF2RBFZZT2UDTFOVZK42233P6XCPKKXFK6XOI5IJOCOEOYKOO7DY | MERCHANT-FUNDED | 363 | 23.980000 (0.6846%) | created by merchant; merchant sent 1.00 ALGO; 91% of gaps &lt; 60s |
| CAMXVUKBXPHI6ZH5OYKI5MSNQWHAXRZVKSNZ7SWGCSHIIUTBAPQIZMXF3I | MERCHANT-FUNDED | 318 | 23.150000 (0.6609%) | created by merchant; merchant sent 1.00 ALGO; merchant sent 126 USDC ×7 (544% of paid); throwaway wallet; 97% of gaps &lt; 60s |
| HAO4JFLCKABK3TC3E2HBTPKEARSE2QYKFJ5CUZNADO2X2NLIXU6DOED6Q4 | FLEET | 470 | 20.970000 (0.5987%) | fleet of 4 via PNCUQO…U4QU; 93% of gaps &lt; 60s |
| 534KR5M5K4EDCGQIP5XBSCOQ5WJMQBAY25OIK5WBNXGYQMDD3JK6WUB2JQ | FLEET | 297 | 20.860000 (0.5955%) | fleet of 4 via PNCUQO…U4QU; 95% of gaps &lt; 60s |
| N5REXWMDSP2JYV7MXEHB4HTUEFW73NKHYD3SNKSJD2JU2A6QFOE2LTV5NQ | FLEET | 171 | 18.570000 (0.5302%) | funded by linked payer VPVLI3…O7DY; 96% of gaps &lt; 60s |
| WCAPU3I2K3IMUC3M4EG3ADA22B5GQGSCFREVZBAKLZ5PVGJMNWVMSELEFI | FLEET | 134 | 12.050000 (0.3440%) | fleet of 4 via PNCUQO…U4QU; 94% of gaps &lt; 60s |
| EZQXFB62PIXHAAE2XFREIATIHPOT3KQIW4FYLWVRDBHEZPCNZNEIOFYFYE | FLEET | 111 | 10.140000 (0.2895%) | funded by linked payer WCAPU3…LEFI; 97% of gaps &lt; 60s |
| NLCXB3BYZEJKS52WGZX2T3KCCGHPV5ENRFLD7W7FMTKQXJ4JWOD25VHIRQ | FLEET | 94 | 9.990000 (0.2852%) | created 1 linked payer; 96% of gaps &lt; 60s; same funder as merchant (hub) |
| QVE6ZADV2OFIMJDCX3EQYLPH7ZX6AEIBGAA3LYQPJC5NQQFMQYSE7GH25I | FLEET | 135 | 8.340000 (0.2381%) | fleet of 4 via PNCUQO…U4QU; 92% of gaps &lt; 60s |
| HAV26QVC22AJNHJEHR6CXRPRHJBFEOI6F3W4LDMSGMH3BCOEXSWFX6SBKM | NO-LINK-DETECTED | 80 | 7.990000 (0.2281%) | throwaway wallet; 91% of gaps &lt; 60s |
| 6YWJAZHKQOIK43ZGWM53DYGSGIYE4TGTOQELWOUETLGY3S7LTHPVAGNJ6M | FLEET | 78 | 7.460000 (0.2130%) | fleet of 7 via WJ7BRI…V7GY; 96% of gaps &lt; 60s |
| R5EUGK4I2RCREBVKEMVVYJSDO7I2D3EY2CXYGYZJS4LVVGJZK5QJHB2D6E | MERCHANT-FUNDED | 88 | 6.980000 (0.1993%) | merchant sent 5.00 USDC ×1 (72% of paid); throwaway wallet; 82% of gaps &lt; 60s |
| IYWDFXVVRQQEPE2Y3OGOUHWF34FZPLZSOQPSIMWWZOXG75AM4AVQ77XXMI | FLEET | 66 | 6.900000 (0.1970%) | fleet of 7 via WJ7BRI…V7GY; 95% of gaps &lt; 60s |
| WJ7BRIVG326PBYIP6NZSTWPC6ZEEX2AXB72GRCWO74QKL4Q535526JV7GY | FLEET | 74 | 6.700000 (0.1913%) | created 7 linked payers; 89% of gaps &lt; 60s; same funder as merchant (hub) |
| N672LSPK6PE35N5DXJQF4OLQ3B446SJ62RSOVUNNOJER7ZEOLKAQGJ345Q | FLEET | 49 | 5.000000 (0.1427%) | fleet of 7 via WJ7BRI…V7GY; 96% of gaps &lt; 60s |
| SWO4VMVUIOHZDBOU57PJ4IZVX5N22O3WXMQ7OMNB4EFNVUKO6YBYLUIFBE | FLEET | 49 | 4.970000 (0.1419%) | fleet of 7 via WJ7BRI…V7GY; 90% of gaps &lt; 60s |
| SC44YGUASW5J45APRWCZCYMORZHK5A2Y4C7ZUDPVT3224UZKGCXOD6GIVA | FLEET | 45 | 4.840000 (0.1382%) | fleet of 7 via WJ7BRI…V7GY; 86% of gaps &lt; 60s |
| XTGQA7GHT4U3YHM55OFU7E43XP3XT7AVMZX6CTR6GQAXQ4Z2YI5SX7O5WE | FLEET | 44 | 4.750000 (0.1356%) | funded by linked payer PNCUQO…U4QU; throwaway wallet; 100% of gaps &lt; 60s |
| ESZUW2SP6IEE6UGZQHSBFS3CT43HCK6RVTKKPG57YDPL5HYJZZF57D2T7A | FLEET | 40 | 3.470000 (0.0991%) | funded by linked payer A3MK6A…YOM4; throwaway wallet; 95% of gaps &lt; 60s |
| VR22PUROECZ35R5IP4ZHT7IBU6S5BMN3MKECSALNW5RTGEMXYA5PQICXXA | FLEET | 28 | 3.000000 (0.0856%) | fleet of 7 via WJ7BRI…V7GY; 100% of gaps &lt; 60s |
| MUJMIBSK3SJBLERZWJ7UNG64C6NXO5LD62M7CL7LKK6SKEDXC4FVPZ4VSY | NO-LINK-DETECTED | 82 | 2.190000 (0.0625%) | throwaway wallet; pays 10 merchants |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 25 | 2.120000 (0.0605%) | throwaway wallet; created by vet402; pays 68 merchants |
| LNLA2AAADJPTVCQK7XAL5N7HZWIUV7XXPNJRGHJK5PMPHUOOR4WPO6XSAI | NO-LINK-DETECTED | 5 | 0.150000 (0.0043%) | throwaway wallet; pays 3 merchants |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 1 | 0.030000 (0.0009%) | pays 16 merchants |

Top 48 of 48 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://agenthub-production-8c75.up.railway.app/api/asset/31566704 | 3,377 (10.0163%) | 163.360000 (4.6637%) | 46 | 0 | 3246 |
| GET | https://agenthub-production-8c75.up.railway.app/api/explain-tx/U6RNSGSAWJ3AINV4WGKGELVJC5SGHN2MS3HGJEQTOBOHKHMX7HYA | 3,189 (9.4587%) | 246.230000 (7.0296%) | 46 | 0 | 3026 |
| GET | https://agenthub-production-8c75.up.railway.app/api/relationship | 3,125 (9.2689%) | 300.600000 (8.5818%) | 44 | 0 | 3006 |
| GET | https://agenthub-production-8c75.up.railway.app/api/wallet-risk/G3YVTPURK6VFSM5CXEH7QFTZXLCXBJL6UMAIUUYJO4P2XF3MHQ4FUHYYB4 | 3,111 (9.2273%) | 298.355000 (8.5177%) | 47 | 0 | 2988 |
| GET | https://agenthub-production-8c75.up.railway.app/api/app/1002541853 | 2,990 (8.8685%) | 299.000000 (8.5361%) | 45 | 0 | 2891 |
| GET | https://agenthub-production-8c75.up.railway.app/api/asset-risk/31566704 | 2,936 (8.7083%) | 281.000000 (8.0222%) | 46 | 0 | 2833 |
| POST | https://agenthub-production-8c75.up.railway.app/api/verify-payment | 2,929 (8.6875%) | 169.140000 (4.8287%) | 44 | 0 | 2796 |
| GET | https://agenthub-production-8c75.up.railway.app/api/app-risk/1002541853 | 2,776 (8.2337%) | 499.680000 (14.2653%) | 44 | 0 | 2673 |
| GET | https://agenthub-production-8c75.up.railway.app/api/cluster/G3YVTPURK6VFSM5CXEH7QFTZXLCXBJL6UMAIUUYJO4P2XF3MHQ4FUHYYB4 | 2,672 (7.9253%) | 534.400000 (15.2565%) | 44 | 0 | 2561 |
| GET | https://agenthub-production-8c75.up.railway.app/api/trace/G3YVTPURK6VFSM5CXEH7QFTZXLCXBJL6UMAIUUYJO4P2XF3MHQ4FUHYYB4 | 2,639 (7.8274%) | 395.850000 (11.3010%) | 42 | 0 | 2524 |
| POST | https://agenthub-production-8c75.up.railway.app/api/inference | 1,107 (3.2834%) | 49.350000 (1.4089%) | 36 | 0 | 1078 |
| POST | https://agenthub-production-8c75.up.railway.app/api/nl-to-sql | 1,034 (3.0669%) | 73.520000 (2.0989%) | 35 | 0 | 1031 |
| POST | https://agenthub-production-8c75.up.railway.app/api/summarize | 1,009 (2.9927%) | 87.170000 (2.4886%) | 36 | 0 | 1001 |
| POST | https://agenthub-production-8c75.up.railway.app/api/code-review | 769 (2.2809%) | 103.660000 (2.9594%) | 34 | 0 | 766 |
| GET | http://agenthub-x1jx.onrender.com/api/wallet-risk/G3YVTPURK6VFSM5CXEH7QFTZXLCXBJL6UMAIUUYJO4P2XF3MHQ4FUHYYB4 | 15 (0.0445%) | 0.225000 (0.0064%) | 2 | 0 | 14 |
| POST | http://agenthub-x1jx.onrender.com/api/inference | 5 (0.0148%) | 0.050000 (0.0014%) | 2 | 0 | 4 |
| POST | http://agenthub-x1jx.onrender.com/api/summarize | 5 (0.0148%) | 0.100000 (0.0029%) | 2 | 0 | 4 |
| GET | https://agenthub-production-8c75.up.railway.app/api/explain-tx/TTQNSTNRWK3NIN45SP4MJYIGRD7QLICPAKIMNMMNBOKJXYTHJT2A | 5 (0.0148%) | 0.220000 (0.0063%) | 3 | 0 | 2 |
| GET | https://agenthub-production-8c75.up.railway.app/api/wallet-risk/K5HIZPOUUUBQ5WJ6I3DT6NGIQUMALYJYSVVBY7CXA3BYBWY6225DNNBDSA | 5 (0.0148%) | 0.220000 (0.0063%) | 2 | 0 | 0 |
| GET | https://agenthub-production-8c75.up.railway.app/api/explain-tx/X3GU7R3VBLF5RZQZZD7K4AIC5XPX2TN7HYPVNCBGBM4V5VAVGSTQ | 4 (0.0119%) | 0.190000 (0.0054%) | 3 | 0 | 1 |
| GET | https://agenthub-production-8c75.up.railway.app/api/wallet-risk/PNCUQOLMQV7GMZDSQ2DQCYUITQVYDT3OKD5245FOSJU76KY3FOCXHIU4QU | 4 (0.0119%) | 0.230000 (0.0066%) | 3 | 0 | 1 |
| GET | https://agenthub-x1jx.onrender.com/api/explain-tx/U6RNSGSAWJ3AINV4WGKGELVJC5SGHN2MS3HGJEQTOBOHKHMX7HYA | 3 (0.0089%) | 0.045000 (0.0013%) | 2 | 0 | 1 |
| POST | https://agenthub-x1jx.onrender.com/api/inference | 3 (0.0089%) | 0.030000 (0.0009%) | 1 | 0 | 0 |
| GET | https://agenthub-production-8c75.up.railway.app/api/wallet-risk/JTN2G23WP3GBIK7CZYABI4NWMKCN2YVSXDYHY4IMIQB7TPXPELRFGMYP64 | 2 (0.0059%) | 0.130000 (0.0037%) | 2 | 0 | 0 |
| POST | https://agenthub-x1jx.onrender.com/api/summarize | 1 (0.0030%) | 0.020000 (0.0006%) | 1 | 0 | 0 |

Top 25 of 25 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: agenthub-production-8c75.up.railway.app, agenthub-x1jx.onrender.com.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| agenthub-production-8c75.up.railway.app | hosting_provider_domain | yes, cached | 2026-10-06T02:51:33.533000+00:00 | 1 |
| agenthub-x1jx.onrender.com | hosting_provider_domain | yes, cached | 2026-10-05T12:13:44.851000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| agenthub-production-8c75.up.railway.app | AgentHub — Algorand wallet risk scoring & transaction decoding for AI agents, pay-per-call | not recorded | 15 x402 pay-per-call APIs for AI agents: Algorand wallet risk scoring, transaction decoding, Algorand token risk screening, Algorand portfolio lookup, Algorand smart contract lookup, and Algorand smart contract risk, plus 9 more. No accounts, no API keys, no subscriptions — agents pay per request in USDC on Algorand mainnet. One is free to call. | https://agenthub-production-8c75.up.railway.app/favicon.ico | not recorded | not recorded |
| agenthub-x1jx.onrender.com | AgentHub — pay-per-call tools for AI agents on Algorand | not recorded | Three x402 micropayment APIs for AI agents: Algorand wallet risk scoring, LLM text generation, and text summarization. No accounts, no API keys, no subscriptions — agents pay per request in USDC on Algorand mainnet. | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| agenthub-production-8c75.up.railway.app | llms.txt | AgentHub | https://agenthub-production-8c75.up.railway.app/llms.txt | not recorded |
| agenthub-x1jx.onrender.com | llms.txt | AgentHub | http://agenthub-x1jx.onrender.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 2 |
| Agent document types | ["llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 25 |
| Description count | 25 |
| Mime type count | 0 |
| Accepts count | 25 |
| Discovery count | 25 |
| Input documentation count | 25 |
| Output documentation count | 25 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-25 | 178 | 5.620000 | 6 | 0 | 174 (97.7528%) |
| 2026-08-26 | 288 | 9.150000 | 8 | 0 | 284 (98.6111%) |
| 2026-08-27 | 388 | 12.410000 | 9 | 0 | 384 (98.9691%) |
| 2026-08-28 | 682 | 21.680000 | 12 | 0 | 675 (98.9736%) |
| 2026-08-29 | 87 | 7.610000 | 4 | 0 | 83 (95.4023%) |
| 2026-08-30 | 147 | 13.490000 | 7 | 0 | 146 (99.3197%) |
| 2026-08-31 | 263 | 23.350000 | 7 | 0 | 261 (99.2395%) |
| 2026-09-01 | 1,087 | 95.170000 | 19 | 0 | 1,085 (99.8160%) |
| 2026-09-02 | 818 | 84.800000 | 21 | 0 | 816 (99.7555%) |
| 2026-09-03 | 560 | 58.560000 | 11 | 0 | 558 (99.6429%) |
| 2026-09-04 | 447 | 48.060000 | 3 | 0 | 445 (99.5526%) |
| 2026-09-05 | 2 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-06 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-07 | 1 | 0.050000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-08 | 986 | 107.110000 | 9 | 0 | 986 (100.0000%) |
| 2026-09-09 | 1,279 | 140.820000 | 4 | 0 | 460 (35.9656%) |
| 2026-09-14 | 4,962 | 501.700000 | 3 | 0 | 4,962 (100.0000%) |
| 2026-09-15 | 8,099 | 899.870000 | 3 | 0 | 8,099 (100.0000%) |
| 2026-09-16 | 6,254 | 699.810000 | 2 | 0 | 6,254 (100.0000%) |
| 2026-09-17 | 4,618 | 514.700000 | 2 | 0 | 4,618 (100.0000%) |
| 2026-09-27 | 7 | 0.590000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-28 | 10 | 0.890000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-29 | 1 | 0.080000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 1 | 0.080000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-01 | 32 | 3.490000 | 2 | 0 | 31 (96.8750%) |
| 2026-10-02 | 896 | 99.840000 | 8 | 0 | 804 (89.7321%) |
| 2026-10-03 | 818 | 89.900000 | 8 | 0 | 702 (85.8191%) |
| 2026-10-04 | 498 | 55.300000 | 9 | 0 | 367 (73.6948%) |
| 2026-10-05 | 1 | 0.080000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.080000 | 1 | 0 | 0 (0.0000%) |

Last 30 of 43 active days; all in the daily CSV.

## Historical funding links

| Payer | Link | Settlements | USDC (% of merchant) | Source |
| --- | --- | --- | --- | --- |
| PT4OJDMDLR7GAPGGMJ7X57LS3PK47BRVXT7USQRE3YH6FEQ7L2FXDJUW2Y | agenthub-funding-link | 2,865 | 271.590000 (7.7536%) | manual funding trace |
| XCBOQCLPKGO4KRIHSXVWTBULKFYZWKJQJ4SQFB7JS4IJ2FHKPBEBFEKZLU | agenthub-funding-link | 4,580 | 511.360000 (14.5987%) | manual funding trace |
| FYFMQL2RMMWHHQSKW3IKO5EZJGOGB7RM4DJRJN2KEL35STU5HJ5O6FNLUI | agenthub-funding-link | 3,081 | 343.530000 (9.8074%) | manual funding trace |
| VGNN7ZP6D3ROPCUXQUT4U7E3GLIUZXZZNC562T4NY7GHU2NVDMAASXLOHI | agenthub-funding-link | 3,219 | 357.950000 (10.2190%) | manual funding trace |
| XXVL44QOVPLEAR7D5B4U7ELP7ZPAPKGW5IURNQWIYAUXM3IXTLR7WYPKRU | agenthub-funding-link | 3,035 | 341.860000 (9.7597%) | manual funding trace |
| VGRBELPP3WIQTXBPQQYSEDXHC3PWYLPZGYZBJUNCBDP5SECXNM2VCZQG3E | agenthub-funding-link | 1,065 | 117.890000 (3.3656%) | manual funding trace |

[Machine-readable historical links](../evidence/historical-corrections.json).
