---
slug: /Risk-control-solutions-for-Perpetual-Swap-Contracts
id:Risk-control-solutions-for-Perpetual-Swap-Contracts
title:Risk control solutions for Perpetual Swap Contracts
sidebar_label:Risk control solutions for Perpetual Swap Contracts
author: DueDEX CS
author_title: DueDEX
author_url: https://www.duedex.com
author_image_url: https://duedex.zendesk.com/system/photos/3606/0800/5893/twitter4.png
tags: [DueDEX, Bitcoins]
---


The priority of risk control mechanism in Contract product design is quite high. A good risk control mechanism needs to take interests of different parties into consideration.
<!--truncate-->
1) Reduce the probability of traders' liquidation and liquidation losses;

2) The liquidation system can complete liquidation process with minimum losses;

3) The system can accumulate sufficient risk reserves to cover the losses caused by liquidation and reduce the risk of over loss.

4) In the event of a position break-through, the fairest possible allocation takes place.

Practically speaking, the risk management solution of the major trading platforms are generally similar, and the difference lies mainly in the details. In addition, the risk can be reduced, but it cannot be completely avoided. In the design of contracts, risk is balanced between traders, platforms and counterparties. We believe that a good risk control mechanism should be that the platform can take more risks by itself under the premise of controllable risks, and let trading customers take as little risk as possible.

**1. Trigger Condition**

The contract's risk control is designed around forced liquidation, so the first protection measure is to reduce the possibility of liquidation.

Margin rate= (account equity / margin used) * 100% -adjustment factor

Adjustment factor = maintenance margin rate* leverage

When the margin ≤ 0, the force liquidation is triggered. According to the formula above, the margin rate must be as high as possible to avoid liquidation. In the calculation of the margin rate, there are only two variables of "account equity" and "maintenance margin", so that the optimization of the liquidation trigger conditions must start from these two perspectives.

"Account equity" is calculated from the current asset price combined with the user's position. We know that the crypto market fluctuates violently. When extreme changes occur in the market, the price fluctuations may cause the user's "account equity" to change severely. An extreme low value may cause unnecessary liquidation. In this regard, each platform introduces some special risk control mechanisms. For example, DueDEX introduces the concept of Mark Price, which integrates prices of different major crypto exchanges. The contract requires that the margin rate calculated based on the Mark Price and the market price satisfy ≤ 0 in order to trigger a forced liquidation.

"Adjustment factor" is another optimization direction, and its conversion formula for "maintaining margin rate" is same as above. In short, the adjustment factor setting is a risk balance between the user and the platform. The higher the maintenance margin rate is set, the easier it is for users to liquidate positions, the smaller the platform risk. Therefore, the setting of "Maintenance margin rate" shows the sincerity of the platform to protect the interests of traders. For users, the simplest way is to compare the flat price of each platform through the calculator embedded in the trading platform, so as to be able to quickly select the trading platform that is optimal for their trading.

**2. Liquidation protection mechanism**

When the liquidation condition is triggered, most platforms have designed a relatively complicated second risk control mechanism compared to the previous direct takeover of liquidated positions. The core of each exchange mechanism here is roughly the same. Let’s use DueDEX as an example:

Liquidation protection measures include four stages:

1. Keeping the active orders and open positions while reducing the user's risk limit.

2. Cancelling active orders while keeping open positions, and reducing the risk limit.

3. A Fill or Kill/FOK (full execution or immediate cancellation) will be submitted, the value of which equals to the difference between the value of current open positions and the value of the lower risk limit that meets the margin requirement.

4. If the position still needs to be liquidated, the entire position will be taken over by the liquidation engine at its bankrupt price.

In simple terms, the purpose of the first two measures is to check whether the account has extra margin to finally confirm whether a liquidation must be triggered. The last two measures are to close the position step by step on the premise that the liquidation must be triggered to achieve.

For users, DueDEX perpetual contract's liquidation protection measures not only reduce the probability of liquidation triggering of user's positions, but also protect the user's positions as much as possible when the liquidation is triggered.

**3. Insurance Fund**

DueDEX uses Insurance Fund to further protect users’ positions. The Insurance Fund grows from liquidations that were able to be executed in the market at a price better than the Bankruptcy Price of that particular position.

Every position has Liquidation Price and Bankruptcy Price. A Liquidation Price is the price at which a position’s margin level reaches its maintenance margin level, thus triggering liquidation. A Bankruptcy price is the price at which a position has lost all its initial margin. Bankruptcy price is a price even lower than Liquidation Price.

Therefore, during Liquidation, if DueDEX is able to liquidate the position at better than the bankruptcy price, the additional funds will be added to the Insurance Fund.

**4. Protection for over loss**

A mechanism called Auto-Deleveraging is used among major perpetual contracts platform to limit the risk of over loss conditions. When there is an extreme market condition, the liquidation system cannot close the position in time, causing the market price to seriously deviate from the takeover price. If the insurance cannot compensate for the loss of liquidation, an auto-deleveraging will occur.

DueDEX caps the percentage of Insurance Fund be used to a single liquidation position. Once a trader is deleveraged, a notification will be sent. His or her active orders will be canceled.

On DueDEX, the deleveraging priority is calculated by profit and leverage. The more profitable and/or the higher leveraged positions are going to be deleveraged first.

**Closing thoughts**

High returns are often accompanied by high risks. Therefore, when choosing a trading platform, instead of paying attention to its promotion of high earnings, it is better to focus on their risk control measures. This is the important information that reflects the reliability of the platform.
