---
slug: /Key-Factors-of-Crypto-Trade-Risk-Management
id:Key-Factors-of-Crypto-Trade-Risk-Management
title: Key Factors of Crypto Trade Risk Management
sidebar_label:  Key Factors of Crypto Trade Risk Management
author: DueDEX CS
author_title: DueDEX
author_url: https://www.duedex.com
author_image_url: https://duedex.zendesk.com/system/photos/3606/0800/5893/twitter4.png
tags: [DueDEX, Bitcoins]
---


DueDEX launched its exclusive risk management solution called Risk Manager. You can have a deeper understanding of settings and how to use Risk Manager in the feature guide in the following link:  [https://duedex.zendesk.com/hc/en-us/articles/360042213134-How-to-use-DueDEX-Risk-Manager-](https://duedex.zendesk.com/hc/en-us/articles/360042213134-How-to-use-DueDEX-Risk-Manager-)
<!--truncate-->
Today, we are going to talk about the key factors behind this risk management tool and elaborate on the details of relevant calculations, so traders can understand why they should start to use this tool to design and optimize their risk management strategies.

## **Profit & Loss Rate**

To all types of trading markets, trailing stop and stop loss are among top factors in the trader's long term and short term strategies. Similar to what we understood of Profit & Loss Rate outside of Crypto markets, in Risk Manager, the Profit and Loss percentage represents the percentage of Profit or Loss of each contract. With the leverage and entry price setup based on the percentage set by the users, the Risk Manager will help traders calculate the Take Profit and Stop Loss Exit Price and execute their trading strategy.

The detailed calculation is quite complicated. However, the Exit Price can be roughly calculated as:

**Exit Price(Take Profit) = Entry Price*(1+%Profit/Leverage)**

**Exit Price(Stop Loss) = Entry Price*(1-%Loss/Leverage)**

Please be reminded that these are only rough calculations. For more accurate numbers, please check directly on the Risk Manager.

![mceclip0.png](https://duedex.zendesk.com/hc/article_attachments/360059483633/mceclip0.png)

Risk/Reward Ratio is also an important figure to review your investment decision. As the billionaire in the hedge fund industry, David Tepper, once said about investment, “_The key is to wait. Sometimes the hardest thing to do is to do nothing”._ If a trader thinks an opportunity is identified with the Risk/Reward Ratio > 1, which means that based on his/her analysis, the order could potentially bring more loss than profit, it is easy to tell that the identified opportunity may not be a real opportunity or at least the current price may not be a good entry point.

![mceclip1.png](https://duedex.zendesk.com/hc/article_attachments/360058584734/mceclip1.png)

## **Position Size**

From the Stop Loss point of view, the total loss should be restricted to a reasonable portion of the total fund in the platform. With limiting the Stop Loss percentage, the risk of each contract is limited. However, the total loss of the position also depends on the quantity of contracts- the position size.

If you wish to limit the total loss of your position within 3% of your total funds on DueDEX, position size can be roughly calculated as:

**The total loss = 3% * Account balance(USD value)**

**Loss of each contract = Loss Rate/Leverage (each contract worth 1 USD)**

**Position size = 3%*Account balance*Leverage/Loss Rate**

Similarly, this is a rough calculation. For an accurate number, please refer to the corresponding section on Risk Manager.

![mceclip3.png](https://duedex.zendesk.com/hc/article_attachments/360058584794/mceclip3.png)

# **Summary**

The core value of Risk Manager is that it lists out the aspects all traders should go through with a trade from the perspective of risk management. Significant figures we have mentioned above include:

-   Profit Rate and Loss Rate
-   Profit/Loss Rate
-   Position Size

They are important indicators to assess your order decision as well as control your risk as explained above.

Besides these, traders are also able to set:

-   Leverage - Only 1 to 25X can be selected for risk management reasons.
-   Entry Price- Either a Market Order with the latest Market Price or a Limit Order.
-   Time In Force - GoodTillCancel, ImmediateOrCancel,FillOrKill
-   Trigger Type - Last Price, Mark Price, Index Price.

These additional functions make Risk Manager a one-stop risk management suite, integrating comprehensive settings in one module.
