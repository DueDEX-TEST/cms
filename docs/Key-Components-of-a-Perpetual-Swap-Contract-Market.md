---
slug: /Key-Components-of-a-Perpetual-Swap-Contract-Market
id: Key-Components-of-a-Perpetual-Swap-Contract-Market
title: Key Components of a Perpetual Swap Contract Market
sidebar_label: # What's a Perpetual Swap Contract?
author: DueDEX
author_title: DueDEX
author_url: https://www.duedex.com
author_image_url: https://duedex.zendesk.com/system/photos/3606/0800/5893/twitter4.png
tags: [DueDEX, Bitcoins]
---

After getting to know the definition and DueDEX's features about a Perpetual Swap Contract, you should be aware of some key components:

1. Position Marking: DueDEX is using  **[Fair Price Marking mechanism](https://duedex.zendesk.com/hc/en-us/articles/360024387254-Fair-Price-Marking-Mechanism)** as position marking. The mark price determines Unrealized PNL and Liquidation Price.

2.  **[Initial and Maintenance Margin](https://duedex.zendesk.com/hc/en-us/articles/360022356653-Initial-Margin-and-Maintenance-Margin)**: These essential margin levels determine how much leverage one can trade with and at what point liquidation occurs.

3.  **[Funding](https://duedex.zendesk.com/hc/en-us/sections/360004060994-Funding)**: The mechanics of Funding ensures the price of Perpetual Swap on DueDEX to track the underlying Index Price closely. Periodic payments exchanged between the buyer and seller every 8 hours. If the rate is positive, the long position holders will pay the short position holders payment, and vice versa if the rate is negative.

4. **Funding Timestamp: 04:00 UTC, 12:00 UTC and 20:00 UTC every day.** You will only pay or receive the funding if you hold a position at that Funding Timestamp. If you close your position before Funding Timestamp, you don’t have to pay/receive funding payment.