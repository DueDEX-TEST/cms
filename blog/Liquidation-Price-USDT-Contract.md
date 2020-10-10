---
slug: /
id: Liquidation-Price-USDT-Contract
title: Liquidation Price USDT Contract
sidebar_label: Liquidation Price (USDT Contract)
author: DueDEX
author_title: DueDEX
author_url: https://www.duedex.com
author_image_url: https://duedex.zendesk.com/system/photos/3606/0800/5893/twitter4.png
tags: [DueDEX, Bitcoins]
---


DueDEX offers leverage to most of its contracts. To keep a position open, the trader needs to keep the minimum amount of value of the position on the exchange platform, known as the Maintenance Margin.
<!--truncate-->

In general, Liquidation occurs when the position margin level falls below its maintenance margin level; when it happens, all the Initial Margin of a position will be lost. It is triggered when  [Mark Price](https://duedex.zendesk.com/hc/en-us/articles/360024387254-Fair-Price-Marking-Mechanism) hits the Liquidation Price.

You can always check the liquidation price of your position under the Open Position Tab. You can also change your liquidation price by adding extra margin and/or adjusting Leverage Sliders.

Example:

**Isolated Margin**

**Buy/Long:**

_Liquidation Price = Entry Price * (1 - Initial Margin Rate + Maintenance Margin Rate) - Extra Margin Added/ Contract Size_

Trader placed a long entry of 1,000 contracts at 10,000 USDT with 50x leverage. Assuming no extra margin added.

_Liquidation Price = 10,000 USDT * (1 - 2% + 0.5%) = 9,850 USDT_

**Sell/Short:**

_Liquidation Price = Entry Price * (1 + Initial Margin Rate - Maintenance Margin Rate) + Extra Margin Added/ Contract Size_

Trader placed a short entry of 1,000 contracts at 10,000USDT with 50x leverage. Assuming no extra margin added.

_Liquidation Price = 10,000 USDT * (1 + 2% - 0.5%) = 10,150 USDT_

**Cross Margin**

Comparing to Isolated Margin, Liquidation Price under Cross Margin mode might keep changing as the available balance will be affected by the other trading pairs. Liquidation only happens when the available balance is 0 and each position does not have enough maintenance margin.

Assuming trader A holding a 10,000 contracts Long position at 10,000 USDT.

The current available balance is 1,000 USDT, current mark price = 10,500USDT, unrealized profit is 500 USDT.

_Initial Margin = 10,000*0.0001*10,000*1% = 200USDT_

_Maintenance Margin = 10,000 *0.0001*10,000*0.5% = 100USDT_

_Available Balance = 1,000USDT_

_Total Sustainable Loss = Available Balance + Initial Margin - Maintenance Margin = 1,000 + 200 -100 USDT = 1,100 USDT_

With 1,100USDT, the position can sustain a price loss of 550USDT (1100/2). Therefore, the liquidation price of this position would be 9,950USDT (10,500-550).
