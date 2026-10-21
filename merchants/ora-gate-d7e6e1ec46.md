# ORA GATE — hackathon merchant dossier

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](../README.md#usage-and-attribution).

[Report overview](../README.md) · [Registrants](../registrants.md) · [Methodology](../methodology.md)

**Registration:** registered on the submission form (source rows 86).

## Identity and accounts

Merchant ID: `VFZYWUJSSTZINU01UklQUUVIUzVaWk9Y`.

Registered: **yes**. Hackathon tag: **yes**. Bazaar: **yes**.

| Network | Receiving account |
| --- | --- |
| Algorand | TVXYBRI6H5M5RIPQEHS5ZZOXR7RS3FUVYKIJ3DTV6C6F5ULLQEZM47OKRM |

| Row | Project | Identity evidence |
| --- | --- | --- |
| 86 | ORA GATE | Exact submitted wallet TVXYBRI6H5M5RIPQEHS5ZZOXR7RS3FUVYKIJ3DTV6C6F5ULLQEZM47OKRM is a receiving account of this merchant. |

## Settlements, volume and payers

| Metric | Value | Definition |
| --- | --- | --- |
| Settlements | 13 | Successful hackathon-tagged Algorand mainnet USDC settlements in scope. |
| USDC volume | 0.130000 | USDC settled. |
| Unique payer accounts | 2 | Distinct accounts that paid. |
| Synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers classed SELF, DEV-LOOP, MERCHANT-FUNDED or FLEET. |
| No link detected | 13 (100.0000%) · 0.130000 USDC (100.0000%) | Paid by payers classed AGENT or HUMAN. |
| Inconclusive | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers without available account history. |
| Historical funding link | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Paid by payers outside the synthetic classes with a reviewed historical funding link to the merchant. |
| Sub-cent | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements above 0 and below 0.01 USDC. |
| Sub-cent and synthetic-indicated | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Sub-cent settlements paid by synthetic-indicated payers. |
| No resource host recorded | 0 (0.0000%) · 0.000000 USDC (0.0000%) | Settlements recorded without a resource host. |
| Self-payments (not counted) | 0 · 0.000000 USDC | Payments from a receiving account to itself. |
| First / last settlement | 2026-09-02 05:08:56 UTC / 2026-09-30 13:55:22 UTC | Earliest and latest counted settlement. |

[All transaction records](../evidence/ora-gate-d7e6e1ec46-transactions.csv.gz) · [All endpoints](../evidence/ora-gate-d7e6e1ec46-endpoints.csv) · [Payer evidence](../evidence/ora-gate-d7e6e1ec46-payers.csv) · [Daily metrics](../evidence/ora-gate-d7e6e1ec46-daily.csv) · [Site and catalog data](../evidence/ora-gate-d7e6e1ec46-site-and-catalog.json)

## Synthetic traffic analysis

Classes and patterns: [methodology](../methodology.md#synthetic-traffic-detection).

| Class | Settlements (% of merchant) | USDC (% of merchant) |
| --- | --- | --- |
| NO-LINK-DETECTED | 13 (100.0000%) | 0.130000 (100.0000%) |

| Payer | Class | Settlements | USDC (% of merchant) | Evidence |
| --- | --- | --- | --- | --- |
| N37HMJCB4BAITC2ZU7C4XW7PUMCO4T3TUASHQEL6A4EWMLOTTHOB7IOOKY | NO-LINK-DETECTED | 10 | 0.100000 (76.9231%) | throwaway wallet; 78% of gaps &lt; 60s; is Selo's address |
| LJAUKXC7EVF7V24MDPMK7YOISYOHBH5ZPBZAGIKYB2MBY5YKEPEXOMER54 | NO-LINK-DETECTED | 3 | 0.030000 (23.0769%) | throwaway wallet |

Top 2 of 2 payers; all in the payer CSV.

## Sub-cent settlements

0 (0.0000%) settlements · 0.000000 (0.0000%) USDC. Paid by synthetic-indicated payers: 0 (0.0000%) settlements · 0.000000 (0.0000%) USDC.

## Endpoints

| Method | Endpoint | Settlements (% of merchant) | USDC (% of merchant) | Unique payers | Sub-cent | Synthetic-indicated settlements |
| --- | --- | --- | --- | --- | --- | --- |
| POST | https://ora-gate-mainnet.vercel.app/api/ora-gate/message/ora_agent | 10 (76.9231%) | 0.100000 (76.9231%) | 1 | 0 | 0 |
| POST | https://ora-gate-mainnet.vercel.app/api/ora-gate/impact/contribute | 1 (7.6923%) | 0.010000 (7.6923%) | 1 | 0 | 0 |
| POST | https://ora-gate-mainnet.vercel.app/api/ora-gate/message/mainnetagent | 1 (7.6923%) | 0.010000 (7.6923%) | 1 | 0 | 0 |
| POST | https://ora-gate-testnet.vercel.app/api/ora-gate/message/mainnetagent | 1 (7.6923%) | 0.010000 (7.6923%) | 1 | 0 | 0 |

Top 4 of 4 endpoints; all in the endpoint CSV.

## Website and agent readiness

Public internet domains: ora-gate-mainnet.vercel.app, ora-gate-testnet.vercel.app.

Custom-domain candidates: none. Registered email on a matching custom domain: **none**.

| Domain | Type | Website evidence | Latest fetch attempt | Agent documents |
| --- | --- | --- | --- | --- |
| ora-gate-mainnet.vercel.app | hosting_provider_domain | yes, cached | 2026-10-01T15:51:20.362000+00:00 | 4 |
| ora-gate-testnet.vercel.app | hosting_provider_domain | not established | 2026-08-30T01:16:45.676000+00:00 | 0 |

| Domain | Title | Site name | Description | Logo | Banner | Theme |
| --- | --- | --- | --- | --- | --- | --- |
| ora-gate-mainnet.vercel.app | ORA Gate \| Agent actions, shared impact | not recorded | Discover how every 100 eligible settled agent credits form one tree-request batch for the configured Digital Humani provider workflow. | not recorded | not recorded | not recorded |
| ora-gate-testnet.vercel.app | not recorded | not recorded | not recorded | not recorded | not recorded | not recorded |

| Domain | Agent document | Name | URL | Description |
| --- | --- | --- | --- | --- |
| ora-gate-mainnet.vercel.app | A2A Agent Card | ORA Gate | https://ora-gate-mainnet.vercel.app/.well-known/agent-card.json | Paid x402 messaging and durable impact-credit accounting with a configured Digital Humani provider workflow. |
| ora-gate-mainnet.vercel.app | Agent Manifest | ORA Gate | https://ora-gate-mainnet.vercel.app/.well-known/agent.json | Paid x402 messaging and durable impact-credit accounting with a configured Digital Humani provider workflow. |
| ora-gate-mainnet.vercel.app | x402 Discovery | not recorded | https://ora-gate-mainnet.vercel.app/.well-known/x402 | Capability: deliver exactly one plain-text message to the requested ORA Gate recipient. Price: 0.01 MainNet USDC (10000 atomic units; ASA 31566704; 6 decimals). Payment: x402 v2 exact on Algorand MainNet; payment identifier required; buyer pays the canonical merchant payTo. If accepts.extra.feePayer is present, it is the facilitator-supplied fee-sponsorship account and does not replace payTo. Success: exactly one economic action, one delivery, and a durable receipt containing actionId, messageId |
| ora-gate-mainnet.vercel.app | llms.txt | ORA Gate | https://ora-gate-mainnet.vercel.app/llms.txt | not recorded |

| Quality assessment | Evidence |
| --- | --- |
| Has custom domain candidate | False |
| Declared website | False |
| Linked domain count | 2 |
| Cached domain metadata count | 2 |
| Domains with cached descriptive homepage evidence | 1 |
| Agent document count | 4 |
| Agent document types | ["agent-card", "agent-json", "llms-txt", "x402"] |
| Agent readiness evidence | discovered_documents_and_catalog |
| Runtime agent interoperability | not_tested_local_data_only |
| Current website reachability | not_tested_local_data_only |
| Custom domain ownership | not_verified |
| Gaps | ["No custom-domain candidate among included public domains; public hosting-provider domains remain eligible.", "One or more included catalog endpoints lack an explicit input or output JSON Schema; examples alone are not schemas."] |

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
| 2026-09-02 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-13 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-16 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-27 | 1 | 0.010000 | 1 | 0 | 0 (0.0000%) |
| 2026-09-30 | 9 | 0.090000 | 1 | 0 | 0 (0.0000%) |

Last 5 of 5 active days; all in the daily CSV.
