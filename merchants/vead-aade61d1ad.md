# VEAD — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `TFEzNklCVTJFRExITjJaM01RQ0hOMlBF`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | LQ36IBU2EDLHN2Z3MQCHN2PETQMCMHTICRWB4WNYHNOGQNLVXRYJXEHDZU |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 276 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 13.760000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 276 (100.0000%) · 13.760000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 1 · 0.010000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-04 22:25:18 UTC / 2026-09-22 13:48:42 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/vead-aade61d1ad-transactions.csv.gz) · [All endpoints](../evidence/vead-aade61d1ad-endpoints.csv) · [Payer evidence](../evidence/vead-aade61d1ad-payers.csv) · [Daily metrics](../evidence/vead-aade61d1ad-daily.csv) · [Site and catalog data](../evidence/vead-aade61d1ad-site-and-catalog.json)

**Flag — self-payments excluded:** 1 settlements / 0.010000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 276 (100.0000%) | 13.760000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| AAW4X3RYP5ZSUU2T7TXIKWYW2WRHA3B4AQE3IM3PJ5REWBFOGTEUCTEQ24 | MERCHANT-FUNDED | 140 | 6.960000 (50.5814%) | created by merchant; merchant sent 12.00 ALGO; merchant sent 7.10 USDC ×8 (102% of paid); throwaway wallet; 72% of gaps &lt; 60s |
| RMPKG7IFMKGA5RIFEKXIXGU5PADRNETUGVV5TWRLFV4UIB4KNAUCPOHLMU | MERCHANT-FUNDED | 136 | 6.800000 (49.4186%) | created by merchant; merchant sent 11.00 ALGO; merchant sent 6.00 USDC ×6 (88% of paid); throwaway wallet |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://vead.app/v1/transaction/x402/verify/6a70945d6d0fd1327aeb3a86 | 3 (1.0870%) | 0.150000 (1.0901%) | 2 | 0 | 3 |
| GET | https://vead.app/v1/transaction/x402/verify/68eff7de46e2f270f57c7527 | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/691892a046e2f270f57c7b1e | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/691893a646e2f270f57c7b4e | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/6924deb4ddeb0e516853467b | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/692991ad03680cdabc080dd1 | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/69299f0a03680cdabc0810cb | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/69303c118cc3c5a6c50c6175 | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/6939793b8cc3c5a6c50c64e7 | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/6939aaaa8cc3c5a6c50c6aa3 | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/6939baeb8cc3c5a6c50c6c8d | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/6a79f13d1c9945adc09de29e | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/6a7a30d65a692c5ba851ca3c | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/6a7a472290007d88d473bf10 | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/6a7a4a2590007d88d4743186 | 2 (0.7246%) | 0.100000 (0.7267%) | 1 | 0 | 2 |
| GET | https://vead.app/v1/transaction/x402/verify/689e25b0065f5a500a9bed09 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/689e26d3065f5a500a9bed31 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/689f2664065f5a500a9bef8d | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/689f278b065f5a500a9befcf | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/689f465d065f5a500a9bf01b | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68a474b2d5e1fac2c2d604bf | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68af06aed5e1fac2c2d606ca | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68af08b1d5e1fac2c2d606f2 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68c19ac0d5e1fac2c2d60884 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68c19c79d5e1fac2c2d608b5 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68c2ee9cd5e1fac2c2d608cf | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68c85931d5e1fac2c2d608fe | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68c85a4fd5e1fac2c2d60918 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68cc7597d5e1fac2c2d60963 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68cc78bbd5e1fac2c2d609a6 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68d35927d5e1fac2c2d60a0e | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68d359f3d5e1fac2c2d60a36 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68d35a75d5e1fac2c2d60a5e | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68dc03dcd5e1fac2c2d60aca | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68e831af46e2f270f57c74d9 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68f10e8a46e2f270f57c7565 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/68f1546146e2f270f57c757f | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690ab04346e2f270f57c7605 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d0cf546e2f270f57c7776 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d0e5b46e2f270f57c77a5 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d0faa46e2f270f57c77d5 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d113246e2f270f57c780f | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d124a46e2f270f57c7841 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d136046e2f270f57c787a | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d142f46e2f270f57c78ae | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d153846e2f270f57c78fe | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d161046e2f270f57c7934 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d16ab46e2f270f57c7962 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d1a7946e2f270f57c79a4 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d1b7346e2f270f57c79e0 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/690d1c1246e2f270f57c7a0e | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6924be48e3734823b52283dc | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6924bf7ce3734823b522840b | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6924de10ddeb0e5168534638 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69298db303680cdabc080d31 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69298fd003680cdabc080d59 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6929908703680cdabc080d81 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6929910303680cdabc080da9 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6929935e03680cdabc080e21 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/692993f003680cdabc080e49 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/692994fd03680cdabc080e71 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69299c4203680cdabc081001 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69299ce303680cdabc081029 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69299d7d03680cdabc08105f | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69299e5503680cdabc081087 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69299fb103680cdabc081117 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6929a09003680cdabc08113f | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6929a1e003680cdabc0811b9 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6929a2ac03680cdabc0811f3 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6929a39103680cdabc08125a | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6929a4d303680cdabc0812a2 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6929a58b03680cdabc0812d8 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6929a67003680cdabc081300 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6929a71c03680cdabc081328 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6929a7ac03680cdabc081350 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/693032b58cc3c5a6c50c5ff5 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/693034508cc3c5a6c50c601d | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/693035a88cc3c5a6c50c6045 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/693038388cc3c5a6c50c60d5 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6930391f8cc3c5a6c50c60fd | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69303b1b8cc3c5a6c50c614d | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69303d798cc3c5a6c50c61c1 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69319ee18cc3c5a6c50c6223 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69319fe18cc3c5a6c50c624f | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6931a1bb8cc3c5a6c50c6277 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6931b6b68cc3c5a6c50c62bb | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/6931b85c8cc3c5a6c50c634b | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69323a2c8cc3c5a6c50c6371 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/693317668cc3c5a6c50c63b8 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/693318ff8cc3c5a6c50c63e4 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/693978738cc3c5a6c50c64bf | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/693979bc8cc3c5a6c50c650f | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69397b338cc3c5a6c50c65c7 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69397e3f8cc3c5a6c50c660a | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69397eea8cc3c5a6c50c6632 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/69397fa28cc3c5a6c50c667f | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/693981998cc3c5a6c50c66a7 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/693982468cc3c5a6c50c66cf | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/693982e78cc3c5a6c50c66f7 | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |
| GET | https://vead.app/v1/transaction/x402/verify/693983898cc3c5a6c50c671f | 1 (0.3623%) | 0.050000 (0.3634%) | 1 | 0 | 1 |

Top 100 of 260 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: vead.app.

Custom-domain candidates: vead.app. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| vead.app | custom_domain_candidate | yes, cached | 2026-10-05T17:33:05.073000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| vead.app | VEAD - Verificación de Activos Digitales en Blockchain | VEAD | Verifica documentos, certificados y productos en blockchain. Validez legal internacional, autenticidad garantizada. Prueba gratis con 10 créditos. | https://vead.app/assets/Logo_Color.png | https://vead.app/assets/Logo_Color.png | #2b0acc |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
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
| Gaps | ["No cached agent discovery documents on included public domains.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 197 |
| Description count | 197 |
| Mime type count | 197 |
| Accepts count | 197 |
| Discovery count | 197 |
| Input documentation count | 197 |
| Output documentation count | 197 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-04 | 1 | 0.010000 | 1 | 0 | 1 (100.0000%) |
| 2026-08-11 | 20 | 1.000000 | 2 | 0 | 20 (100.0000%) |
| 2026-08-12 | 2 | 0.100000 | 1 | 0 | 2 (100.0000%) |
| 2026-08-13 | 15 | 0.750000 | 2 | 0 | 15 (100.0000%) |
| 2026-08-14 | 16 | 0.800000 | 2 | 0 | 16 (100.0000%) |
| 2026-08-15 | 8 | 0.400000 | 1 | 0 | 8 (100.0000%) |
| 2026-08-18 | 13 | 0.650000 | 1 | 0 | 13 (100.0000%) |
| 2026-08-19 | 25 | 1.250000 | 2 | 0 | 25 (100.0000%) |
| 2026-08-20 | 3 | 0.150000 | 1 | 0 | 3 (100.0000%) |
| 2026-08-21 | 28 | 1.400000 | 2 | 0 | 28 (100.0000%) |
| 2026-08-22 | 11 | 0.550000 | 1 | 0 | 11 (100.0000%) |
| 2026-08-25 | 22 | 1.100000 | 2 | 0 | 22 (100.0000%) |
| 2026-08-26 | 1 | 0.050000 | 1 | 0 | 1 (100.0000%) |
| 2026-08-28 | 11 | 0.550000 | 1 | 0 | 11 (100.0000%) |
| 2026-08-29 | 3 | 0.150000 | 1 | 0 | 3 (100.0000%) |
| 2026-08-30 | 1 | 0.050000 | 1 | 0 | 1 (100.0000%) |
| 2026-08-31 | 3 | 0.150000 | 1 | 0 | 3 (100.0000%) |
| 2026-09-01 | 29 | 1.450000 | 2 | 0 | 29 (100.0000%) |
| 2026-09-02 | 28 | 1.400000 | 2 | 0 | 28 (100.0000%) |
| 2026-09-03 | 1 | 0.050000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-04 | 13 | 0.650000 | 1 | 0 | 13 (100.0000%) |
| 2026-09-05 | 1 | 0.050000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-08 | 7 | 0.350000 | 1 | 0 | 7 (100.0000%) |
| 2026-09-09 | 1 | 0.050000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-10 | 3 | 0.150000 | 1 | 0 | 3 (100.0000%) |
| 2026-09-11 | 1 | 0.050000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-21 | 5 | 0.250000 | 1 | 0 | 5 (100.0000%) |
| 2026-09-22 | 4 | 0.200000 | 1 | 0 | 4 (100.0000%) |

Last 28 of 28 active days; all in the daily CSV.
