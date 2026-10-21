# IoMarkets.app — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 103).

## Identity and accounts

Merchant ID: `RlZFSkRDUUZDSFZHNFk2TTJKVkFENEw0`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | FVEJDCQFCHVG4Y6M2JVAD4L447E2R2OHJKT5APXV7AZI7XXOQU6RUVSKCA |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 103 | IoMarkets.app | Exact submitted wallet FVEJDCQFCHVG4Y6M2JVAD4L447E2R2OHJKT5APXV7AZI7XXOQU6RUVSKCA is a receiving account of this merchant.; Project name and submitted domain independently corroborate the selected account identity. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 4 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 16.950000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 4 (100.0000%) · 16.950000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 1 · 0.630000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-08-29 21:48:21 UTC / 2026-09-30 21:41:57 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/iomarkets-app-762a059cc6-transactions.csv.gz) · [All endpoints](../evidence/iomarkets-app-762a059cc6-endpoints.csv) · [Payer evidence](../evidence/iomarkets-app-762a059cc6-payers.csv) · [Daily metrics](../evidence/iomarkets-app-762a059cc6-daily.csv) · [Site and catalog data](../evidence/iomarkets-app-762a059cc6-site-and-catalog.json)

**Flag — self-payments excluded:** 1 settlements / 0.630000 USDC paid by a receiving account to itself. Not counted.

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 4 (100.0000%) | 16.950000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| WGBOYG6QTMXDJ5N7EHOBZ7OI4367G7IAKAOHE5GGLAR6XHFLGT5PBFXOQE | MERCHANT-FUNDED | 4 | 16.950000 (100.0000%) | created by merchant's creator; throwaway wallet |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://iomarkets.app/v1/orders | 4 (100.0000%) | 16.950000 (100.0000%) | 1 | 0 | 4 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: iomarkets.app.

Custom-domain candidates: iomarkets.app. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| iomarkets.app | custom_domain_candidate | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 3 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| iomarkets.app | IoMarkets Topup — real-world checkout for AI agents | IoMarkets.app | IoMarkets Topup: real-world checkout for AI agents. Mobile airtime & data top-ups and travel eSIMs in 150+ countries, paid per order in USDC on Algorand via x402. Settle first, deliver second, refund on-chain, signed receipts, public ledger. Part of the IoMarkets® ecosystem. | https://iomarkets.app/apple-touch-icon.png | https://iomarkets.app/brand/logo-og.png | #0F2557 |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| iomarkets.app | A2A Agent Card | IoMarkets Topup | https://iomarkets.app/.well-known/agent-card.json | Real-world checkout for AI agents. Buys physical-world goods and services for an agent's principal in 150+ countries — currently mobile airtime and data top-ups and travel eSIMs — paid per order in USDC on Algorand (mainnet) over x402. No account, no API key, no card. Money settles on-chain before anything is bought; a failed delivery is refunded to the paying address on-chain automatically; every terminal order carries an ed25519-signed receipt naming both transaction ids, and the full order le |
| iomarkets.app | Agent Manifest | IoMarkets Topup | https://iomarkets.app/.well-known/agent.json | Real-world checkout for AI agents. Buys physical-world goods and services for an agent's principal in 150+ countries — currently mobile airtime and data top-ups and travel eSIMs — paid per order in USDC on Algorand (mainnet) over x402. No account, no API key, no card. Money settles on-chain before anything is bought; a failed delivery is refunded to the paying address on-chain automatically; every terminal order carries an ed25519-signed receipt naming both transaction ids, and the full order le |
| iomarkets.app | llms.txt | IoMarkets Topup — real-world checkout for AI agents (x402 on Algorand) | https://iomarkets.app/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 1 |
| Cached domain metadata count | 1 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 3 |
| Agent document types | ["agent-card", "agent-json", "llms-txt"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

| Catalog field | Resources |
| --- | --- |
| Resource count | 1 |
| Description count | 1 |
| Mime type count | 0 |
| Accepts count | 1 |
| Discovery count | 1 |
| Input documentation count | 1 |
| Output documentation count | 1 |
| Input schema count | 0 |
| Output schema count | 0 |

## Daily activity

| UTC day | Settlements | USDC | Unique payers | Sub-cent | Synthetic-indicated settlements (% of day) |
| --- | --- | --- | --- | --- | --- |
| 2026-08-29 | 1 | 15.310000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-02 | 1 | 0.500000 | 1 | 0 | 1 (100.0000%) |
| 2026-09-30 | 2 | 1.140000 | 1 | 0 | 2 (100.0000%) |

Last 3 of 3 active days; all in the daily CSV.
