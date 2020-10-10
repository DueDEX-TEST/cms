---
slug: /Initial-Margin-and-Maintenance-Margin-USDT-Contract
id: Initial-Margin-and-Maintenance-Margin-USDT-Contract
title: Initial Margin Maintenance Margin USDT Contract
sidebar_label: Initial Margin Maintenance Margin (USDT Contract)
author: DueDEX
author_title: DueDEX
author_url: https://www.duedex.com
author_image_url: https://duedex.zendesk.com/system/photos/3606/0800/5893/twitter4.png
tags: [DueDEX, Bitcoins]
---


**Initial Margin**

You can use leverage to open a Perpetual Contract position, which means you only need to put some margin to start.

For example, if you would like to open a position of 1,000USDT, the leverage is 100x, the initial margin =1,000USDT/100x=10 USDT._
<!--truncate-->

To calculate the initial margin required for USDT Contracts, multiply the order value with the initial margin rate. The initial margin rate depends on the leverage used.

_Initial Margin = Contract size x contract value x Entry Price / Leverage_

_Example: Trader place a long entry of 1,000 contracts at USDT 10,000 with 50x leverage. Initial Margin=(1,000x0.0001x10,000)/50 =20 USDT_

**Maintenance Margin**

Maintenance Margin is the minimum amount required to continue holding a position from getting liquidated. For example, if you hold a position of 1000 USDT and the Maintenance Margin rate is 0.5%, then you should keep 1000USDT*0.5%=5 USDT to avoid getting liquidated.