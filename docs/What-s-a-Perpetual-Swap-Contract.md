---
slug: /What-s-a-Perpetual-Swap-Contract
id: What-s-a-Perpetual-Swap-Contract
title: # What's a Perpetual Swap Contract?
sidebar_label: # What's a Perpetual Swap Contract?
author: DueDEX
author_title: DueDEX
author_url: https://www.duedex.com
author_image_url: https://duedex.zendesk.com/system/photos/3606/0800/5893/twitter4.png
tags: [DueDEX, Bitcoins]
---



A Perpetual Swap Contract is an innovative derivative product. It trades like spot, tracking the underlying Index Price closely. It is also very similar to traditional Futures, but it doesn’t have an expiry date, so there is no settlement. 7x24 trading allows traders to open a position or close a position whenever they like to. With some margin deposit, traders can sell or short a position.

Perpetual Swap Contracts trade close to the underlying reference Index Price. The primary mechanism to track spot price is  [Funding](https://duedex.zendesk.com/hc/en-us/articles/360022173294).

**What does DueDEX's Perpetual Swap look like?**

At the beginning of DueDEX platform launch, we will offer  _BTCUSD Perpetual Swap contract_  for our users. Many more trading pairs and products will be launched gradually.

**Up to 100x Leverage**

DueDEX fully understands different risk tolerance and preference of trading experience of our valued users. We offer up to 100x leverage Perpetual Swap Contracts.

[**Fair Pricing Marking Mechanism**](https://duedex.zendesk.com/hc/en-us/articles/360024387254)

Designed to be fully aware of the possibility of malicious market manipulation, DueDEX will use a unique  _Fair Price Marking mechanism_ to prevent users from falling victim to the manipulations, and to ensure a fair trading ecosystem for all our valued users.

Fair Price, which is calculated based on the weighted average of latest prices (Index Price) from mainstream spot exchanges, like  _Bitstamp, Coinbase Pro and Kraken_, and is used as Mark Price to calculate the unrealized PNL (Profit and Loss) and to decide when to trigger liquidation.

The Fair Price is equal to the underlying Index Price plus a decaying Funding basis rate.

[**Funding**](https://duedex.zendesk.com/hc/en-us/articles/360022173294)

The mechanics of Funding ensure that the price of Perpetual Contract on DueDEX will  _track the underlying Index Price_  closely. Periodic payments are exchanged between the buyer and seller every 8 hours.

If the rate is positive, the long position holders will pay the short position holders, and vice versa if the rate is negative. You will only pay or receive the funding if you hold a position at that Funding Timestamp, which stands at 04:00 UTC, 12:00 UTC and 20:00 UTC every day.

**[Insurance Fund](https://duedex.zendesk.com/hc/en-us/articles/360024446734)  +  [Auto-Deleveraging (ADL)](https://duedex.zendesk.com/hc/en-us/articles/360024532873)**

In time of liquidation, if DueDEX is unable to liquidate the position at the bankruptcy price, DueDEX will first spend some Insurance Funds on aggregating the position in the market in an attempt to close it. If this still does not close the liquidated order, it will then lead to an Auto-Deleveraging event, which will automatically deleverage the positions owned by opposing traders according to profit and leverage priority.