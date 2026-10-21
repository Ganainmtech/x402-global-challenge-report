# Scope and methodology

> **Usage and attribution:** this report is a build and product of [GoPlausible](https://goplausible.com). Using, reproducing or referencing it, in whole or in part, requires crediting GoPlausible: link to [goplausible.com](https://goplausible.com) on web content and mention @GoPlausible on social media. [Usage and attribution](README.md#usage-and-attribution).

[Overview](README.md)

## Scope

Counted: successful Algorand mainnet USDC settlements carrying the `x402-global-challenge` tag, at Bazaar-listed merchants. Not counted: developer-flagged settlements, localhost-hosted resources, self-payments and merchants on the active blocklist. Registration is a flag, not a filter.

Each tagged settlement is excluded at the first step that applies:

1. Developer-flagged settlements.
2. Settlements for localhost-hosted resources.
3. Merchants on the active blocklist, by receiving account or resource host.
4. Self-payments: a receiving account paying itself. The facilitator flags these as developer traffic since 2026-10-03; earlier ones are excluded here the same way.
5. Merchants without a Bazaar listing.

Registration is a flag. Merchants without a matching submission row are included and flagged **NOT REGISTERED**. Submission rows without counted settlements are listed under [Registrations](registrants.md) with the step that excludes them.

Settlements without a public resource host are counted; their resource locator is published as `(not recorded)`, `(no host recorded)` or `[local URL omitted]`.

The report covers every counted settlement up to the data cutoff, 2026-10-06 11:40:37 UTC.

## Definitions

- **Merchant**: a merchant identity on the facilitator: its registered receiving accounts, its Bazaar catalog entry, or a single receiving account. Its name is the Bazaar name, else the registered project name, else its site name, else its busiest public host, else its masked receiving account.
- **Settlement**: a successful USDC payment settled through the facilitator on Algorand mainnet.
- **Unique payer accounts**: distinct accounts that paid; accounts, not people.
- **Sub-cent**: a settlement above 0 and below 0.01 USDC.
- **Synthetic-indicated, no link detected, inconclusive**: payer classes, defined below.

## Synthetic traffic detection

Synthetic traffic means payments a merchant makes to itself through wallets it creates, funds or controls. Every payer wallet of every merchant is tested separately against the eight patterns below, using the merchant's counted settlements and a read-only history of the payer account on Algorand. The report applies no cut-off to merchants and draws no verdict: it reports how much of each merchant's traffic comes from payers that match. A matched pattern indicates a link between payer and merchant; it does not establish intent, and an unmatched payer is not proven independent.

### The eight patterns

**P1 · Origin — created by the merchant.** The account that created the payer wallet is one of the merchant's own receiving accounts, or the account that created the merchant's own receiving wallet (unless that account is an exchange or onboarding hub). A customer's wallet is funded by the customer; a wallet the merchant brought into existence is the merchant's.

**P2 · Money back — the merchant sends the money back.** The merchant's accounts sent the payer gas (ALGO), or returned a large share of the USDC the payer paid. It decides only for automated (P7) or brand-new (P6) wallets that do not pay many merchants: refunds to established wallets are ordinary business.

**P3 · Self — the merchant pays itself.** The payer is one of the merchant's own receiving accounts. Exact self-payments to the same account are excluded by policy before classification, so in this report P3 means paying from another of the merchant's own addresses.

**P4 · Dev loop — localhost resources on mainnet.** A material share of the wallet's payments went to resources on the merchant's localhost server, which a customer cannot reach. Localhost settlements are excluded by policy, so P4 cannot match in this report.

**P5 · Fleet — wallet fleets and linked wallets.** Several payers of one merchant were created by the same non-hub account within days of each other, or are rekeyed to one controller; and wallets that funded, were funded by, or share a controller with a wallet already classed as synthetic. Links are followed until no new wallet joins, so funding chains resolve fully. One operator, many wallets.

**P6 · Throwaway — brand-new wallet with no other life.** The wallet was created shortly before its first payment and has no footprint beyond paying x402 merchants (no other assets, applications or creations). Not decisive alone, since first-time users exist; it removes the "established customer" explanation from P2 and P5.

**P7 · Cadence — machine timing.** *Burst*: most gaps between payments under a minute. *Timer*: near-identical gaps. *24/7*: active in nearly every UTC hour with no day/night shape, over several days. Cadence separates automation from people, not merchant-run automation from an independent agent, so it never marks a wallet synthetic on its own.

**P8 · Customers — who else is paying.** Once every payer is classified, the USDC paid by wallets with no detected link to the merchant: the *No-link-detected USDC* column in the overview, merchant index and dossiers. The report states this figure; it draws no verdict from it.

### From patterns to payer classes

Each payer receives the first class that applies, in this order:

| Class | Patterns | Report label |
| --- | --- | --- |
| SELF | P3 | synthetic-indicated |
| DEV-LOOP | P4 | synthetic-indicated |
| MERCHANT-FUNDED | P1; or P2 on an automated (P7) or brand-new (P6) wallet | synthetic-indicated |
| FLEET | P5 on an automated (P7) or brand-new (P6) wallet; or a P5 link to a synthetic payer | synthetic-indicated |
| AGENT | P7 only, no link to the merchant | NO-LINK-DETECTED |
| HUMAN | none | NO-LINK-DETECTED |
| INCONCLUSIVE | no account history available (none in the current build) | INCONCLUSIVE |

A merchant's synthetic share is the share of its counted settlements and USDC paid by synthetic-indicated payers; its P8 figure is the USDC paid by NO-LINK-DETECTED payers.

In each dossier's payer table the *Evidence* column names the patterns observed for that payer: *merchant's own address* (P3); *localhost* (P4); *created by merchant* or *created by merchant's creator* (P1); *merchant sent … ALGO* or *merchant sent … USDC* (P2); *fleet of … via …*, *controller of … via …*, *funded by linked payer*, *created … linked payers* or *same controller as linked payers* (P5); *throwaway wallet* (P6); *… of gaps < 60s*, *timer …* or *24/7 over …* (P7). Other phrases are context, not patterns: *same funder as merchant* (with *(hub)* when that funder is a hub), *created by* or *is … address* naming another merchant, *pays … merchants*, *also receives x402*, *rekeyed → …*, *same pair on testnet*, *inflows capped*.

### Not treated as evidence

- **Shared exchange funders.** An account that funds many new accounts every day, mostly accounts that are not x402 payers or merchants, is a hub (exchange withdrawals, wallet onboarding). Two wallets funded by the same hub are not linked.
- **Automation by itself** (P7). Autonomous agents are legitimate x402 payers.
- **Refunds to established wallets** (P2) or to broad multi-merchant clients: refunds, payouts and prizes are ordinary service behaviour.
- **Sub-cent pricing, high volume, single endpoints.** None of these say anything about who the payer is; they are reported, not classified.

### Evidence base

Funding and control evidence comes from the Algorand histories of 13,026 payer accounts; 138 of them were looked up after the data cutoff (2026-10-08) with transaction history bounded to the cutoff. Patterns are evaluated on counted settlements only. Wallet footprint (P6) reflects the time each account was looked up.

Historical funding links come from manual funding traces of exact payer–merchant pairs. They are reported separately and are not part of the synthetic-indicated total.

## Website evidence and privacy

Website and agent-document evidence is cached site metadata; it does not show current availability or tested interoperability. Registrant names and emails are masked; URL credentials, queries and fragments are removed; non-public hosts are redacted.
