# AuditPay - Payment Logging & Audit Certificates for Algorand x402 — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `M0tPNk8yNktLQU5QM0pER0FYU1hONzJM`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | 3KO6O26KKANP3JDGAXSXN72LZBPF656XGGWUNGAEDJCSVOPC2QHNZR3J5E |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 7 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.600001 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 7 (100.0000%) · 0.600001 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 1 (14.2857%) · 0.000001 USDC (0.0002%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-30 14:39:49 UTC / 2026-10-06 00:01:21 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/auditpay-payment-logging-audit-certificates-for-algorand-x402-0b9f3761ad-transactions.csv.gz) · [All endpoints](../evidence/auditpay-payment-logging-audit-certificates-for-algorand-x402-0b9f3761ad-endpoints.csv) · [Payer evidence](../evidence/auditpay-payment-logging-audit-certificates-for-algorand-x402-0b9f3761ad-payers.csv) · [Daily metrics](../evidence/auditpay-payment-logging-audit-certificates-for-algorand-x402-0b9f3761ad-daily.csv) · [Site and catalog data](../evidence/auditpay-payment-logging-audit-certificates-for-algorand-x402-0b9f3761ad-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 7 (100.0000%) | 0.600001 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 6 | 0.600000 (99.9998%) | throwaway wallet; created by vet402; pays 68 merchants |
| MXRTDXJROPTRU4PMUI4P7PP3OBSAES2TJI6NPNCTY5IFUK7XBQ7CHQWVUE | NO-LINK-DETECTED | 1 | 0.000001 (0.0002%) |  |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

1 (14.2857%) settlements · 0.000001 (0.0002%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://auditpay.appl3s.in/audit/certificate | 7 (100.0000%) | 0.600001 (100.0000%) | 2 | 1 | 0 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: auditpay.appl3s.in.

Custom-domain candidates: auditpay.appl3s.in. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| auditpay.appl3s.in | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| auditpay.appl3s.in | AuditPay - Payment Logging & Audit Certificates for Algorand x402 | not recorded | not recorded | not recorded | not recorded | not recorded |

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
| Agent readiness evidence | not_recorded |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No cached agent discovery documents on included public domains.", "No catalog resources on included public domains."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 0 |
| Description count | 0 |
| Mime type count | 0 |
| Accepts count | 0 |
| Discovery count | 0 |
| Input documentation count | 0 |
| Output documentation count | 0 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-30 | 1 | 0.000001 | 1 | 1 | 0 (0.0000%) |
| 2026-10-01 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.100000 | 1 | 0 | 0 (0.0000%) |

Last 7 of 7 active days; all in the daily CSV.
