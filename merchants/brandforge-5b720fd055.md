# BrandForge — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 16).

## Identity and accounts

Merchant ID: `TkQ2Q0ZBRDdFN1FUR1dCRVhMSjdNSlBZ`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | ND6CFAD7E7QTGWBEXLJ7MJPYI3GNF7IF2TDVEGNQX3Z5TFOYLQT252THJI |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 16 | BrandForge | Exact submitted wallet ND6CFAD7E7QTGWBEXLJ7MJPYI3GNF7IF2TDVEGNQX3Z5TFOYLQT252THJI is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 7 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.210000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 1 (14.2857%) · 0.030000 USDC (14.2857%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 6 (85.7143%) · 0.180000 USDC (85.7143%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-30 20:56:31 UTC / 2026-10-06 00:10:20 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/brandforge-5b720fd055-transactions.csv.gz) · [All endpoints](../evidence/brandforge-5b720fd055-endpoints.csv) · [Payer evidence](../evidence/brandforge-5b720fd055-payers.csv) · [Daily metrics](../evidence/brandforge-5b720fd055-daily.csv) · [Site and catalog data](../evidence/brandforge-5b720fd055-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 1 (14.2857%) | 0.030000 (14.2857%) |
| NO-LINK-DETECTED | 6 (85.7143%) | 0.180000 (85.7143%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| HVRJUKO2QDZW6UKADE7LYWQFMTT75537OPMYEWOTYIUFO4BB25TFL5IQMQ | NO-LINK-DETECTED | 6 | 0.180000 (85.7143%) | throwaway wallet; created by vet402; pays 68 merchants |
| BXEBO5KH4QPQNJR5VU2FIBEMBOSFI5472TIHQNXBMFKSONRUMWSH32DTVU | MERCHANT-FUNDED | 1 | 0.030000 (14.2857%) | created by merchant; merchant sent 1.20 ALGO; throwaway wallet |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| GET | https://brandforge-cyan.vercel.app/v1/brand-kit | 7 (100.0000%) | 0.210000 (100.0000%) | 2 | 0 | 1 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: brandforge-cyan.vercel.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| brandforge-cyan.vercel.app | hosting_provider_domain | yes, cached | 2026-10-04T09:32:54.662000+00:00 | 1 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| brandforge-cyan.vercel.app | BrandForge — pay-per-kit brand identity on x402 | BrandForge | Pay a few cents in USDC over x402 on Algorand and get a complete brand kit: strategy, logo, colour system, typography, UI, voice, and marketing templates. | https://brandforge-cyan.vercel.app/og.svg | https://brandforge-cyan.vercel.app/og.svg | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| brandforge-cyan.vercel.app | A2A Agent Card | BrandForge | https://brandforge-cyan.vercel.app/.well-known/agent-card.json | Pay-per-kit brand identity generator on Algorand. Send a name, an industry, and a few vibe words; get a complete kit — strategy, logo, colour system, typography, visual language, UI, voice, social & marketing templates, and guidelines. Settled per kit in USDC over x402 — no API key, no account. |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 1 |
| Agent document types | ["agent-card"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 1 |
| Description count | 1 |
| Mime type count | 1 |
| Accepts count | 1 |
| Discovery count | 1 |
| Input documentation count | 1 |
| Output documentation count | 1 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-09-30 | 1 | 0.030000 | 1 | 0 | 1 (100.0000%) |
| 2026-10-01 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-02 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-03 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-04 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-05 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |
| 2026-10-06 | 1 | 0.030000 | 1 | 0 | 0 (0.0000%) |

Last 7 of 7 active days; all in the daily CSV.
