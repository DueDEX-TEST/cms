---
slug: /Cross-Margin-and-Isolated-Margin
id: Cross-Margin-and-Isolated-Margin
title: Cross Margin and Isolated Margin
sidebar_label: Cross Margin and Isolated Margin
author: DueDEX
author_title: DueDEX
author_url: https://www.duedex.com
author_image_url: https://duedex.zendesk.com/system/photos/3606/0800/5893/twitter4.png
tags: [DueDEX, Bitcoins]
---

**Cross Margin**

Cross margining is the process that make all of your Available Balance accessible to avoid Liquidation. That’s to say, Margin is shared among your open positions. A position might take more margin from your total account balance to avoid liquidation. The realized PNL from other positions can also help in adding margin on your losing position.

<!--truncate-->

For example, if you have a position of 10BTC, the leverage is 100x, at Cross Margin mode, the initial margin =10/100=0.1BTC, when the market goes down, your Available Balance will be used to maintain the position to avoid the liquidation.

_On DueDEX, Cross Margin mode is the initial default setup for all positions._

**Isolated Margin**

Isolated Margin is the margin accredited to a position which is restricted to a certain amount. If you choose an Isolated Margin, your liability is limited to the initial margin posted. However, you can always add or remove your margin at any time.

When the liquidation happens, any Available Balance you have will  **NOT**  be used to add margin to your position.

For example, if you have a position of 10BTC, leverage is 50x, then the Initial Margin =10/50=0.2BTC. When the market goes south, and your margin for this position falls below the Maintenance Margin level, this position will be liquidated. But your Available Balance will not be touched.

**Setting and adjusting Isolated Margin**

On DueDEX, Cross Margin mode is set as default. You can switch to Isolated Margin by using the leverage slider on the right side of Trade Dashboard. The leftmost mode is Cross Margin mode, then, you can slide to the right to switch to the Isolated Margin mode, the more to the right, the higher leverage. The higher the leverage, the less margin is assigned to that position, then more likely the position gets liquidated.