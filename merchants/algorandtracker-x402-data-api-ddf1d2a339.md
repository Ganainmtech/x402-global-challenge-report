# AlgorandTracker x402 Data API — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 92).

## Identity and accounts

Merchant ID: `VlRPRU02NTI3V01MSFdQVEtSQlFOUUxP`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | VTOEM6527WMLHWPTKRBQNQLO5XWGFJC5Z6T7E25TFBKMWP5NFPDP73ZD4U |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 92 | AlgorandTracker x402 Data API | Exact submitted wallet VTOEM6527WMLHWPTKRBQNQLO5XWGFJC5Z6T7E25TFBKMWP5NFPDP73ZD4U is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 751 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 31.230000 | USDC settled. |
| Unique payer accounts | 5 | Distinct accounts that paid. |
| Synthetic-indicated | 465 (61.9174%) · 16.640000 USDC (53.2821%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 286 (38.0826%) · 14.590000 USDC (46.7179%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-05 00:16:33 UTC / 2026-10-06 00:05:46 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/algorandtracker-x402-data-api-ddf1d2a339-transactions.csv.gz) · [All endpoints](../evidence/algorandtracker-x402-data-api-ddf1d2a339-endpoints.csv) · [Payer evidence](../evidence/algorandtracker-x402-data-api-ddf1d2a339-payers.csv) · [Daily metrics](../evidence/algorandtracker-x402-data-api-ddf1d2a339-daily.csv) · [Site and catalog data](../evidence/algorandtracker-x402-data-api-ddf1d2a339-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 465 (61.9174%) | 16.640000 (53.2821%) |
| NO-LINK-DETECTED | 286 (38.0826%) | 14.590000 (46.7179%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| VCJOOYPS6PMAFOYW3QCKN34ZGFVJNXLGCPGVWNHJCZJNXRAHHTZ26CJ2GI | MERCHANT-FUNDED | 465 | 16.640000 (53.2821%) | created by merchant; merchant sent 160 ALGO; merchant sent 11.82 USDC ×1 (71% of paid); throwaway wallet |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 250 | 13.300000 (42.5873%) | throwaway wallet; 92% of gaps &lt; 60s; created by vet402; pays 68 merchants |
| XALLOLSAOW5HVPCKK6NSTUTPVFWB3K6MNFKDXHMXULFYGN6GYXT4UU4UXA | NO-LINK-DETECTED | 14 | 0.690000 (2.2094%) | throwaway wallet; 100% of gaps &lt; 60s; pays 9 merchants |
| HFHI5MF4C55AYUSQ2JD2AFYMUHWBNSE3SGU6N2YZ5ET5FUZD5YHZHXSWXU | NO-LINK-DETECTED | 21 | 0.590000 (1.8892%) | throwaway wallet; 100% of gaps &lt; 60s; is Stelar Digital's address; pays 2 merchants |
| RLWICEPDPBNGIWWOACZZ3NPAYX2JIJ6K3QNJX5LXFSLN3MRZV2HJ3JGVUM | NO-LINK-DETECTED | 1 | 0.010000 (0.0320%) | pays 16 merchants |

Top 5 of 5 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://algorandtracker.com/x402/asa/0/activity | 247 (32.8895%) | 4.940000 (15.8181%) | 3 | 0 | 244 |
| GET | https://algorandtracker.com/x402/asa/393537671/monthly-report/months | 14 (1.8642%) | 0.140000 (0.4483%) | 4 | 0 | 2 |
| GET | https://algorandtracker.com/x402/algo/nodes | 8 (1.0652%) | 0.480000 (1.5370%) | 3 | 0 | 5 |
| GET | https://algorandtracker.com/x402/hay/stake | 8 (1.0652%) | 0.640000 (2.0493%) | 2 | 0 | 6 |
| GET | https://algorandtracker.com/x402/tinyman/stake | 8 (1.0652%) | 0.480000 (1.5370%) | 2 | 0 | 6 |
| GET | https://algorandtracker.com/x402/algo/foundation-holders | 7 (0.9321%) | 0.420000 (1.3449%) | 2 | 0 | 5 |
| GET | https://algorandtracker.com/x402/app-unique-senders | 7 (0.9321%) | 0.140000 (0.4483%) | 1 | 0 | 7 |
| GET | https://algorandtracker.com/x402/asa/0/top-holders | 7 (0.9321%) | 0.560000 (1.7931%) | 2 | 0 | 5 |
| GET | https://algorandtracker.com/x402/algo/foundation-total-history | 6 (0.7989%) | 0.280000 (0.8966%) | 3 | 0 | 3 |
| GET | https://algorandtracker.com/x402/gora/stake-wallets | 6 (0.7989%) | 0.480000 (1.5370%) | 2 | 0 | 4 |
| GET | https://algorandtracker.com/x402/gora/validators | 6 (0.7989%) | 0.360000 (1.1527%) | 2 | 0 | 4 |
| GET | https://algorandtracker.com/x402/activity-highlights | 5 (0.6658%) | 0.250000 (0.8005%) | 3 | 0 | 2 |
| GET | https://algorandtracker.com/x402/algo/nodes-history | 5 (0.6658%) | 0.260000 (0.8325%) | 2 | 0 | 3 |
| GET | https://algorandtracker.com/x402/asa/393537671/pool-lp | 5 (0.6658%) | 0.400000 (1.2808%) | 2 | 0 | 3 |
| GET | https://algorandtracker.com/x402/asa/393537671/pool-lp-previously | 5 (0.6658%) | 0.180000 (0.5764%) | 3 | 0 | 2 |
| GET | https://algorandtracker.com/x402/asa/700965019/monthly-report/months | 5 (0.6658%) | 0.050000 (0.1601%) | 3 | 0 | 2 |
| GET | https://algorandtracker.com/x402/algo/nodes-bucket-history | 4 (0.5326%) | 0.080000 (0.2562%) | 1 | 0 | 4 |
| GET | https://algorandtracker.com/x402/algo/nodes-new-entrants | 4 (0.5326%) | 0.140000 (0.4483%) | 2 | 0 | 2 |
| GET | https://algorandtracker.com/x402/algo/nodes-previously | 4 (0.5326%) | 0.140000 (0.4483%) | 2 | 0 | 2 |
| GET | https://algorandtracker.com/x402/algo/nodes-stake-share | 4 (0.5326%) | 0.240000 (0.7685%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/0/supply-distribution | 4 (0.5326%) | 0.120000 (0.3842%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/0/top-holders-new-entrants | 4 (0.5326%) | 0.140000 (0.4483%) | 2 | 0 | 2 |
| GET | https://algorandtracker.com/x402/asa/0/top-holders-previously | 4 (0.5326%) | 0.140000 (0.4483%) | 2 | 0 | 2 |
| GET | https://algorandtracker.com/x402/asa/1138500612/activity | 4 (0.5326%) | 0.080000 (0.2562%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1138500612/monthly-report/months | 4 (0.5326%) | 0.040000 (0.1281%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1138500612/pool-lp-previously | 4 (0.5326%) | 0.160000 (0.5123%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1138500612/supply-distribution | 4 (0.5326%) | 0.120000 (0.3842%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1138500612/top-holders-new-entrants | 4 (0.5326%) | 0.160000 (0.5123%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1138500612/top-holders-previously | 4 (0.5326%) | 0.160000 (0.5123%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1284444444/activity | 4 (0.5326%) | 0.080000 (0.2562%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1284444444/monthly-report/months | 4 (0.5326%) | 0.040000 (0.1281%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1284444444/pool-lp-previously | 4 (0.5326%) | 0.160000 (0.5123%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1284444444/supply-distribution | 4 (0.5326%) | 0.120000 (0.3842%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1284444444/top-holders-new-entrants | 4 (0.5326%) | 0.160000 (0.5123%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1284444444/top-holders-previously | 4 (0.5326%) | 0.160000 (0.5123%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2200000000/pool-lp | 4 (0.5326%) | 0.320000 (1.0247%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2200000000/supply-distribution-history | 4 (0.5326%) | 0.400000 (1.2808%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2200000000/top-holders | 4 (0.5326%) | 0.320000 (1.0247%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2200000000/top-holders-new-entrants | 4 (0.5326%) | 0.160000 (0.5123%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2200000000/top-holders-previously | 4 (0.5326%) | 0.160000 (0.5123%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2994233666/monthly-report/months | 4 (0.5326%) | 0.040000 (0.1281%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2994233666/supply-distribution | 4 (0.5326%) | 0.120000 (0.3842%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/393537671/activity | 4 (0.5326%) | 0.080000 (0.2562%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/393537671/supply-distribution | 4 (0.5326%) | 0.120000 (0.3842%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/393537671/top-holders-new-entrants | 4 (0.5326%) | 0.160000 (0.5123%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/393537671/top-holders-previously | 4 (0.5326%) | 0.160000 (0.5123%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/gora/stake-wallets-previously | 4 (0.5326%) | 0.140000 (0.4483%) | 2 | 0 | 2 |
| GET | https://algorandtracker.com/x402/hay/stake-previously | 4 (0.5326%) | 0.140000 (0.4483%) | 2 | 0 | 2 |
| GET | https://algorandtracker.com/x402/stablecoins/usdc/daily-history | 4 (0.5326%) | 0.240000 (0.7685%) | 3 | 0 | 1 |
| GET | https://algorandtracker.com/x402/algo/nodes-wallet-history | 3 (0.3995%) | 0.060000 (0.1921%) | 1 | 0 | 3 |
| GET | https://algorandtracker.com/x402/asa/0/activity-supply-distribution | 3 (0.3995%) | 0.060000 (0.1921%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/0/pool-lp | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/0/wallet-history | 3 (0.3995%) | 0.060000 (0.1921%) | 1 | 0 | 3 |
| GET | https://algorandtracker.com/x402/asa/1138500612/pool-lp | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1138500612/supply-distribution-history | 3 (0.3995%) | 0.300000 (0.9606%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1138500612/top-holders | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1284444444/pool-lp | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1284444444/supply-distribution-history | 3 (0.3995%) | 0.300000 (0.9606%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/1284444444/top-holders | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2200000000/activity | 3 (0.3995%) | 0.060000 (0.1921%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2200000000/monthly-report/months | 3 (0.3995%) | 0.030000 (0.0961%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2200000000/pool-lp-previously | 3 (0.3995%) | 0.120000 (0.3842%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2200000000/supply-distribution | 3 (0.3995%) | 0.090000 (0.2882%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2726252423/activity | 3 (0.3995%) | 0.060000 (0.1921%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2726252423/monthly-report/months | 3 (0.3995%) | 0.030000 (0.0961%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2726252423/pool-lp | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2726252423/pool-lp-previously | 3 (0.3995%) | 0.120000 (0.3842%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2726252423/supply-distribution | 3 (0.3995%) | 0.090000 (0.2882%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2726252423/supply-distribution-history | 3 (0.3995%) | 0.300000 (0.9606%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2726252423/top-holders | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2994233666/activity | 3 (0.3995%) | 0.060000 (0.1921%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2994233666/pool-lp | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2994233666/supply-distribution-history | 3 (0.3995%) | 0.300000 (0.9606%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/2994233666/top-holders | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3160000000/activity | 3 (0.3995%) | 0.060000 (0.1921%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3160000000/monthly-report/months | 3 (0.3995%) | 0.030000 (0.0961%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3160000000/pool-lp | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3160000000/supply-distribution | 3 (0.3995%) | 0.090000 (0.2882%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3160000000/supply-distribution-history | 3 (0.3995%) | 0.300000 (0.9606%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3160000000/top-holders | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3160000000/top-holders-new-entrants | 3 (0.3995%) | 0.120000 (0.3842%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3160000000/top-holders-previously | 3 (0.3995%) | 0.120000 (0.3842%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3203964481/activity | 3 (0.3995%) | 0.060000 (0.1921%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3203964481/monthly-report/months | 3 (0.3995%) | 0.030000 (0.0961%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3203964481/pool-lp | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3203964481/pool-lp-previously | 3 (0.3995%) | 0.120000 (0.3842%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3203964481/supply-distribution | 3 (0.3995%) | 0.090000 (0.2882%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3203964481/supply-distribution-history | 3 (0.3995%) | 0.300000 (0.9606%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3203964481/top-holders | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3203964481/top-holders-new-entrants | 3 (0.3995%) | 0.120000 (0.3842%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/3203964481/top-holders-previously | 3 (0.3995%) | 0.120000 (0.3842%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/393537671/supply-distribution-history | 3 (0.3995%) | 0.300000 (0.9606%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/393537671/top-holders | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/700965019/pool-lp | 3 (0.3995%) | 0.240000 (0.7685%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/700965019/pool-lp-previously | 3 (0.3995%) | 0.120000 (0.3842%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/700965019/pool-lp-wallet-history | 3 (0.3995%) | 0.060000 (0.1921%) | 1 | 0 | 3 |
| GET | https://algorandtracker.com/x402/asa/700965019/price-history | 3 (0.3995%) | 0.090000 (0.2882%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/700965019/supply-distribution | 3 (0.3995%) | 0.090000 (0.2882%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/asa/700965019/supply-distribution-history | 3 (0.3995%) | 0.300000 (0.9606%) | 2 | 0 | 1 |
| GET | https://algorandtracker.com/x402/hay/stake-new-entrants | 3 (0.3995%) | 0.120000 (0.3842%) | 2 | 0 | 1 |

Top 100 of 163 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: algorandtracker.com.

Custom-domain candidates: algorandtracker.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| algorandtracker.com | custom_domain_candidate | yes, cached | 2026-10-06T07:09:19.706000+00:00 | 2 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| algorandtracker.com | Algorand & ASA Tracker | Algorand & ASA Tracker | Algorand & ASA Tracker: historical holders, activity, LP, supply, nodes, RWA (Exodus, WTR, ebitts, Meld), USDC, and live wallet portfolios. | https://algorandtracker.com/logo.png | https://algorandtracker.com/logo.png | #1a1a2e |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| algorandtracker.com | x402 Discovery | not recorded | https://algorandtracker.com/.well-known/x402 | not recorded |
| algorandtracker.com | llms.txt | Algorand & ASA Tracker | https://algorandtracker.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 2 |
| Agent document types | ["llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 173 |
| Description count | 173 |
| Mime type count | 173 |
| Accepts count | 173 |
| Discovery count | 173 |
| Input documentation count | 173 |
| Output documentation count | 173 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-07 | 5 | 0.100000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-08 | 5 | 0.100000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-09 | 5 | 0.100000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-10 | 5 | 0.100000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-11 | 5 | 0.100000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-12 | 5 | 0.100000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-13 | 5 | 0.100000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-14 | 5 | 0.100000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-15 | 5 | 0.100000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-16 | 5 | 0.100000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-17 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-18 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-19 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-20 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-21 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-22 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-23 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-24 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-25 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-26 | 1 | 0.020000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-27 | 119 | 6.510000 | 2 | 0 | 1 (0.8403%) |
| 2026-09-28 | 125 | 6.750000 | 2 | 0 | 1 (0.8000%) |
| 2026-09-29 | 2 | 0.030000 | 2 | 0 | 1 (50.0000%) |
| 2026-09-30 | 2 | 0.030000 | 2 | 0 | 1 (50.0000%) |
| 2026-10-01 | 16 | 0.720000 | 3 | 0 | 1 (6.2500%) |
| 2026-10-02 | 2 | 0.030000 | 2 | 0 | 1 (50.0000%) |
| 2026-10-03 | 2 | 0.030000 | 2 | 0 | 1 (50.0000%) |
| 2026-10-04 | 2 | 0.030000 | 2 | 0 | 1 (50.0000%) |
| 2026-10-05 | 2 | 0.030000 | 2 | 0 | 1 (50.0000%) |
| 2026-10-06 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |

Last 30 of 63 active days; all in the daily CSV.
