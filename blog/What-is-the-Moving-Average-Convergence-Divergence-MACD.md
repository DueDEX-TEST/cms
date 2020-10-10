---
slug: /What-is-the-Moving-Average-Convergence-Divergence-MACD
id:What-is-the-Moving-Average-Convergence-Divergence-MACD
title: What is the Moving Average Convergence/Divergence (MACD)?
sidebar_label: What is the Moving Average Convergence/Divergence (MACD)?
author: DueDEX CS
author_title: DueDEX
author_url: https://www.duedex.com
author_image_url: https://duedex.zendesk.com/system/photos/3606/0800/5893/twitter4.png
tags: [DueDEX, Bitcoins]
---


The moving average convergence/divergence (MACD) is an indicator that being used to analyze the market trend. The MACD integrates market data of different periods to help traders identify possible opportunities around support and resistance levels.

The MACD indicator is made up of three components:
<!--truncate-->

The **MACD line**, which measures the distance between two moving averages

The **signal line**, which identifies changes in the price

The **histogram**, which represents the difference between the MACD and the signal line

![](https://miro.medium.com/max/831/1*A-45qzIHMtdkbUNTi-csSw.png)

# How to Calculate?

**_DIF_**

1. Calculate the SHORT moving average and LONG moving average, respectively, and record them as EMA (SHORT) and EMA (LONG). SHORT = 12, LONG = 26.  
Smoothing factor: S(12)= 2/(12+1)=0.1538 S(26) = 2/(26+1) = 0.0741  
EMA(SHORT) = EMA yesterday+0.1538(Closing price today — EMA yesterday)

EMA(LONG) = EMA yesterday+0.0741(Closing price today — EMA yesterday)

Find the difference between these two similar moving averages, that is: DIF = EMA (SHORT)-EMA (LONG)

The DIF line is called the MACD line.

**_DEA_**

2. Calculate the M-day moving average of DIF and record it as DEA. M=9

The DEA line is called the Signal line.

**_Histogram_**

3. Finally, subtract DEA from DIF to get Histogram, which is usually drawn as a bar chart.

# How to use MACD?

Two different types of signals can be given by analyzing MACD, 1) the strength of the trend and 2) the turning points of the trend.

The first signal that the MACD indicator gives is whether the trend is rising or falling. When the MACD rises, it signals that the trend is powerful. When MACD stops rising or the degree of the rise is decreasing, it means that the strength of the trend declines and possibly hints a change in trend.

The second signal that the MACD indicator gives is when the MACD signal line crosses the MACD. When the MACD signal line crosses the MACD and gets above it, or what is called a Bearish MACD Crossover, a sell-signal is suggested. When the MACD signal line crosses the MACD and ends up below the MACD, and a so-called bullish MCAD Crossover, a buy-signal is sent.

# Limitations of MACD

MACD is a short-term indicator. The time period that takes into account is 26 days which is not long enough for the analysis of the market trend for a longer duration.

It is also a trend-following or a lagging indicator, which means that the trend has occurred before traders could identify them via MACD. It’s not a good method to recognize an upcoming trend.
