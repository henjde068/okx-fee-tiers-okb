# OKX Fee Discount Guide: What Actually Lowers Your Rate, Whether Holding OKB Still Helps, and What the 0.1%–0.5% DEX Fee Covers

Your OKX trading fee comes down to one number: the fee tier your account is in. OKX derives that tier from your 30-day trading volume and your asset balance, recalculates it every day, and applies it to spot, futures and options orders. The complication is that OKX currently runs at least two official fee pages with different base rates, and a third-party tracker publishes a third set, so the percentage you read somewhere may have nothing to do with your account.

Three things can genuinely move your rate: climbing into a higher VIP tier, whatever an invitation link attaches to your account when you register, and a referral link if you trade through OKX's DEX interface. The rest of this guide covers how each one works, including the places where OKX's own documentation disagrees with itself.

> **The short version for most readers.** If your 30-day volume stays under 100,000 USD, you are a Regular user and no discount hunt changes that. The lever you control is order type: on the fee page served to en-us visitors, a maker order costs **0.2000%** and a taker order **0.3500%**. Cross 100,000 USD of 30-day volume and you reach VIP1, where those become **0.1000%** and **0.2000%**.
>
> 👉 [Create your OKX account through this invitation link and check the tier shown in your own Fee page](https://okx.com/join/CASH20)

## The full tier table (the en-us fee schedule)

This is the complete ladder from the fee page OKX shows to en-us visitors, unchanged:

| Tier | Assets (USD) | 30-day volume (USD) | Maker | Taker | 24h withdrawal limit (USD) |
| --- | --- | --- | --- | --- | --- |
| Regular | 0 – 100,000 | 0 – 100,000 | 0.2000% | 0.3500% | 10,000,000 |
| VIP 1 | 100,001 – 200,000 | 100,001 – 250,000 | 0.1000% | 0.2000% | 24,000,000 |
| VIP 2 | 200,001 – 2,000,000 | 250,001 – 500,000 | 0.0750% | 0.1500% | 32,000,000 |
| VIP 3 | 2,000,001 – 5,000,000 | 500,001 – 1,000,000 | 0.0600% | 0.1250% | 40,000,000 |
| VIP 4 | 5,000,001 – 20,000,000 | 1,000,001 – 2,500,000 | 0.0500% | 0.1000% | 48,000,000 |
| VIP 5 | 20,000,001 – 50,000,000 | 2,500,001 – 5,000,000 | 0.0450% | 0.0800% | 60,000,000 |
| VIP 6 | 50,000,001 – 100,000,000 | 5,000,001 – 50,000,000 | 0.0400% | 0.0700% | 72,000,000 |
| VIP 7 | 100,000,001 – 250,000,000 | 50,000,001 – 75,000,000 | -0.0020% | 0.0250% | 80,000,000 |
| VIP 8 | 250,000,001 – 500,000,000 | 75,000,001 – 125,000,000 | -0.0050% | 0.0200% | Not published |
| VIP 9 | 500,000,001+ | 125,000,001+ | -0.0075% | 0.0175% | Not published |

You qualify on either column: assets **or** 30-day volume. VIP8 and VIP9 sit inside the table with no withdrawal limit listed against them, so treat those two cells as blank rather than as a number someone forgot to copy.

One detail from the same page is easy to miss: your 24-hour crypto withdrawal limit is set by your fee level, recalculated daily at 16:00 UTC, with every coin you hold converted to USD and counted against the cap. A higher tier buys you a bigger daily exit, not just a cheaper fill.

## Why the same exchange shows you three different fee schedules

Here is where the searching gets frustrating. The en-us page opens Regular users at 0.2000% maker and 0.3500% taker. OKX's other official fee page opens Regular users at 0.080% maker and 0.100% taker, and sorts them into Lv1 to Lv5 by **OKB holdings** rather than by volume. A 1,000 USD taker order costs 3.50 USD on the first page and 1.00 USD on the second.

| Source | Regular spot maker / taker | How regular tiers are set | Highest tier |
| --- | --- | --- | --- |
| OKX fee page, en-us version | 0.2000% / 0.3500% | Assets or 30-day volume | VIP 9 |
| OKX fee page with Spot / Futures / Options tabs | 0.080% / 0.100% | OKB holdings, Lv1 – Lv5 | VIP 8 |
| Third-party fee tracker (page timestamped 17 Nov 2026) | 0.1% / 0.15% | VIP0 – VIP9, volume plus OKB | VIP 9 |

Neither official page carries a publication date, so there is no honest way to declare one of them newer. The only explanation OKX itself offers sits in a disclaimer at the foot of the en-us page:

> "OKX's fees may vary depending on your region. Find out the fees applicable to you here."

That one sentence does a lot of work. It means the schedule is regional, which is also why the second page can quote 0.08% / 0.10% while the en-us one quotes 0.20% / 0.35% without either being a mistake. The differences go past the headline rate: the two pages stop at VIP9 and VIP8 respectively, quote the withdrawal limit in USD on one and in BTC on the other (500 BTC at Lv1), and update fee levels in different windows, 20:00–22:00 UTC on the en-us page against 21:00–23:00 UTC on the other.

The third set of numbers is the least useful for your decision. That tracker states plainly that its calculator "uses base fees without taking VIP levels and personal discounts into account." Its 0.1% / 0.15% is a starting point for a comparison table, not a rate any specific account is guaranteed to pay.

So when you see 0.08%, 0.10%, 0.15% or 0.35% attached to OKX in the same week, all four can be real and none of them tells you your own cost.

👉 [Open an OKX account through this invitation link, then read the actual maker and taker rate on your Fee page](https://okx.com/join/CASH20)

## Does holding OKB still lower your trading fee?

The two official pages split on this, and so do OKX's own help pages.

The page with the Spot / Futures / Options tabs is explicit: regular users are tiered by total OKB holdings, from under 500 OKB up to 2,000 OKB or more, with maker fees falling from 0.080% to 0.060% and taker from 0.100% to 0.080% across those five levels. It also defines what counts: OKB in your funding and trading accounts is included, OKB sitting in Savings is not.

The en-us page never mentions OKB. Not in the tier table, not in the tier criteria, not in the worked examples.

Then there are two OKX help documents pointing in opposite directions. One, dated 18 May 2025, states that OKB cannot be used to offset exchange trading fees and that holding OKB does not affect fee discount tiers. Another, dated 5 December 2025, still recommends holding more OKB among the ways to lower your costs. Third-party guides repeat both claims with equal confidence, some describing an extra 20% to 25% off for paying fees in OKB, which none of the official fee pages in front of me confirm.

My read: do not buy OKB to save on trading fees. The evidence for a discount is one page that may describe a different region, and the clearest official statement on the question says the holding does nothing to your tier. If you already hold OKB for other reasons, open your Fee page and see whether an Lv tier is actually applied to your account. That takes ten seconds and settles it for your jurisdiction, which is the only jurisdiction that matters here.

## How OKX actually calculates your tier

Four inputs decide where you land, and each has a rule that catches people out.

**30-day trading volume.** Crypto pairs are recorded in BTC equivalents at the moment of each trade, then converted to USD once a day at 16:00 UTC using the BTC/USD midpoint, calculated as (opening price + closing price) / 2. USD pairs are simply recorded in dollars at trade time. Spot pairs where both maker and taker fees are 0% are excluded from your 30-day spot volume, and excluded again from market-maker tier assessment, so volume farming on zero-fee pairs does not move you up.

**Asset balance.** OKX snapshots your assets daily at 16:00 UTC and uses the **higher** of two figures: your 30-day average asset amount and that day's snapshot. If your average is 1,000 USD and today's snapshot is 500 USD, you are assessed at 1,000 USD. Fiat balances count. The other fee page adds that assets borrowed for leverage or loans are excluded.

**Multiple markets.** If you qualify for different tiers in different markets, you get the best one everywhere. OKX's own example: 20,000,000 USD of 30-day spot volume (VIP2), 200,000,000 USD of futures and perpetual volume (VIP3), 5,000,000 USD of options volume (VIP1) and 5,000,000 USD of assets (VIP4) means you trade every market at VIP4 rates.

**Main and sub-accounts.** The main account's tier is calculated from the combined volume and balances of all accounts. Sub-accounts inherit it after creation, at 16:00 UTC on the en-us page and 10:00 UTC on the other one, another small contradiction you cannot resolve from the outside.

## The DEX fee is a separate charge, and your VIP tier does not touch it

Everything above applies to orders on OKX's exchange. Swapping through OKX DEX, which routes your trade to third-party DEXs, triggers an interface fee with its own logic. It does not read your VIP level, your 30-day volume or your OKB balance.

| Fee rate | Token pair | Which token is charged |
| --- | --- | --- |
| 0% | Others <> Others | No charge |
| 0.1% | Group 1 <> Group 1 | Target token |
| 0.25% | Group 1 <> Group 2 | Group 1 |
| 0.25% | Group 2 <> Group 2 | Target token |
| 0.5% | Group 1 <> Others | Group 1 |
| 0.5% | Group 2 <> Others | Group 2 |

Two rules are worth memorising before a large swap. Every tokenized stock on every chain OKX DEX supports is classified as Group 2 and pays the standard Group 2 rate, so a tokenized-equity swap is never a 0.1% trade. And the token groupings are updated regularly, which means a pair that cost you 0.1% last month can cost 0.25% now without any announcement reaching you.

The exemption list is short and specific: native-token wrap and unwrap, liquid staking, deposits and withdrawals through the Aave protocol, and pre-launch or pre-graduation tokens from Aspecta, Xdock.meme and Four.meme. Those carry no interface fee. Everything else does.

Referral links do apply here. OKX states that users can receive discounts on interface fees by accessing OKX DEX through a referral link, which makes the entry path one of the few things that changes DEX costs at all.

👉 [Register through this OKX invitation link so the referral is attached before your first DEX swap](https://okx.com/join/CASH20)

## FAQ

**Which currency is the trading fee taken in?**
For spot and margin, the fee is settled in the crypto you bought and charged when the buy order fills. Buy 1 BTC at 20,000 USDT as a taker at 0.1% and you pay 0.001 BTC, receiving 0.999 BTC. Maker rebates are paid in the same crypto the taker pays: a maker at a 0.002% tier who sells 1 BTC receives 0.00002 BTC.

**What does a negative maker fee mean?**
That the exchange pays you for resting an order in the book instead of taking liquidity. The en-us page runs from -0.0020% at VIP7 to -0.0075% at VIP9. The third-party tracker shows -0.02% at VIP9 on spot. The magnitudes disagree; the direction does not.

**Is my withdrawal limit tied to my fee tier?**
On the en-us page, yes. The limit is recalculated daily at 16:00 UTC from your fee level, every coin you hold is converted to USD, and the total must stay under the cap for your tier. The other fee page quotes the same limit in BTC and layers KYC levels on top, at 200 BTC for KYC Level 1 and 500 BTC for Level 2.

**Does an invitation or referral code lower the fee itself?**
Neither published fee ladder lists referral codes as an input; they list volume, assets, and on one page OKB. What a code attaches to your account is shown on the sign-up page for your region, and the field can only be set during registration. You will find third-party pages advertising a flat 20% rebate for their own specific codes, and at least one of those pages ties the rebate to EEA accounts and says it is not offered in every country. That is that code's arrangement in that region, not an OKX-wide rate.

**Is the DEX interface fee the same charge as the trading fee?**
No. The trading fee applies to orders matching on OKX's own order book and follows your VIP tier. The interface fee applies to swaps routed through OKX DEX to third-party DEXs and follows the token-group table above. A single trader can pay both in the same week, on different trades.

## What to do with this

Match your situation to one line:

- **Under 100,000 USD of 30-day volume, buying spot occasionally.** You are a Regular user. Stop looking for a code that halves your fee and start using limit orders: on the en-us schedule the gap between maker (0.2000%) and taker (0.3500%) is the largest discount available to you.
- **Volume pushing past 100,000 USD in 30 days.** On the en-us thresholds that is VIP1 territory, and the taker rate halves. On the other page's thresholds VIP1 starts at 10,000,000 USD, so confirm which schedule your account follows before you count on it.
- **Trading futures or perpetuals regularly.** Fees there are set on separate tabs from spot, with their own rate card. Check that tab, not the spot table.
- **Swapping on-chain more than occasionally.** Look up the token group before the trade. Group 2 pairs are where the 0.25% and 0.5% rates live, and tokenized stocks always sit there.

Two checks before you place an order. First, open the Fee page inside your account and write down your tier, your maker rate and your taker rate as displayed there, because that page is the only version of this article that is guaranteed to be current for you. Second, if you want an invitation attached to the account, do it during registration, since the join page carries the code in its path and the referral field cannot be filled in afterwards.

👉 [Start on OKX through this invitation link and confirm your fee tier before your first trade](https://okx.com/join/CASH20)
