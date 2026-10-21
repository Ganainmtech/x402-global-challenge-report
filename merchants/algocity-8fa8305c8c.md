# AlgoCity — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration: NOT REGISTERED.** No submission-form row matches this merchant.

## Identity and accounts

Merchant ID: `RFFHNVZJVjNPVzRQRlg2QzdWUEI1TzRL`.

Registered: **NO**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | DQG5VIV3OW4PFX6C7VPB5O4KQPRWKUMOQYGP2G2W75SNKVTYAR7PIW26KM |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 1 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 3.000000 | USDC settled. |
| Unique payer accounts | 1 | Distinct accounts that paid. |
| Synthetic-indicated | 1 (100.0000%) · 3.000000 USDC (100.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-30 14:04:54 UTC / 2026-09-30 14:04:54 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/algocity-8fa8305c8c-transactions.csv.gz) · [All endpoints](../evidence/algocity-8fa8305c8c-endpoints.csv) · [Payer evidence](../evidence/algocity-8fa8305c8c-payers.csv) · [Daily metrics](../evidence/algocity-8fa8305c8c-daily.csv) · [Site and catalog data](../evidence/algocity-8fa8305c8c-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| MERCHANT-FUNDED | 1 (100.0000%) | 3.000000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| TYNA2HMEUO4DEGYUENI6WWHWRAOSC2ELX64V5DWBFP4UDTMPBIFH5GULZU | MERCHANT-FUNDED | 1 | 3.000000 (100.0000%) | created by merchant's creator; throwaway wallet |

Top 1 of 1 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://algocity.pentacostai.com/api/x402/tables | 1 (100.0000%) | 3.000000 (100.0000%) | 1 | 0 | 1 |

Top 1 of 1 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: algocity-nine.vercel.app, algocity.pentacostai.com.

Custom-domain candidates: algocity.pentacostai.com. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| algocity-nine.vercel.app | hosting_provider_domain | yes, cached | not recorded | 3 |
| algocity.pentacostai.com | custom_domain_candidate | yes, cached | 2026-10-02T19:55:54.693000+00:00 | 3 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| algocity-nine.vercel.app | AlgoCity · The Agent-Native City on Algorand | AlgoCity | A sandboxed, agent-native city where autonomous agents participate, transact, compete, and build economic activity on Algorand. | https://algocity.pentacostai.com/apple-touch-icon.png | https://algocity.pentacostai.com/og-image.png | oklch(0.965 0.008 85) |
| algocity.pentacostai.com | AlgoCity \| The Agent-Native City on Algorand | AlgoCity | A sandboxed, agent-native city where autonomous agents participate, transact, compete, and build economic activity on Algorand. | https://algocity.pentacostai.com/apple-touch-icon.png | https://algocity.pentacostai.com/og-image.png | oklch(0.965 0.008 85) |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| algocity-nine.vercel.app | A2A Agent Card | AlgoCity Table Service | https://algocity-nine.vercel.app/.well-known/agent-card.json | A sandboxed, agent-native city where autonomous agents participate, transact, compete, and build economic activity on Algorand. This service opens its tables: one x402 payment creates a new on-chain Game with its own 28 deed NFTs, where agents and people register seats, roll with the Algorand randomness beacon, buy, auction, build and trade. The payment settles only after the table exists, and one payment opens exactly one table. |
| algocity-nine.vercel.app | x402 Discovery | AlgoCity | https://algocity-nine.vercel.app/.well-known/x402 | A sandboxed, agent-native city where autonomous agents participate, transact, compete, and build economic activity on Algorand. One x402 payment of $3.00 in USDC opens a four-seat table: a new on-chain Game with its own 28 deed NFTs. |
| algocity-nine.vercel.app | llms.txt | AlgoCity | https://algocity-nine.vercel.app/llms.txt | not recorded |
| algocity.pentacostai.com | A2A Agent Card | AlgoCity Table Service | https://algocity.pentacostai.com/.well-known/agent-card.json | A sandboxed, agent-native city where autonomous agents participate, transact, compete, and build economic activity on Algorand. This service opens its tables: one x402 payment creates a new on-chain Game with its own 28 deed NFTs, where agents and people register seats, roll dice drawn from the block seed of a round committed in advance, buy, auction, build and trade. The payment covers four seats and every move fee, so seat keys need no ALGO. The payment settles only after the table exists, and |
| algocity.pentacostai.com | x402 Discovery | AlgoCity | https://algocity.pentacostai.com/.well-known/x402 | A sandboxed, agent-native city where autonomous agents participate, transact, compete, and build economic activity on Algorand. One x402 payment of $2.99 in USDC opens a four-seat table: a new on-chain Game with its own 28 deed NFTs. One payment of $0.99 buys an agent one seat at an open table. |
| algocity.pentacostai.com | llms.txt | AlgoCity | https://algocity.pentacostai.com/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | True |
| Declared website | False |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 2 |
| Agent document count | 6 |
| Agent document types | ["agent-card", "llms-txt", "x402"] |
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
| 2026-09-30 | 1 | 3.000000 | 1 | 0 | 1 (100.0000%) |

Last 1 of 1 active days; all in the daily CSV.
