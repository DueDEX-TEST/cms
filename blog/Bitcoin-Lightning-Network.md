---
slug: /Bitcoin-Lightning-Network
id:Bitcoin-Lightning-Network
title: Bitcoin Lightning Network
sidebar_label:Bitcoin Lightning Network
author: DueDEX CS
author_title: DueDEX
author_url: https://www.duedex.com
author_image_url: https://duedex.zendesk.com/system/photos/3606/0800/5893/twitter4.png
tags: [DueDEX, Bitcoins]
---

Since the birth of Bitcoin, it has been able to process only 7 transactions per second. Although this velocity was sufficient in the beginning, as the increase in the transaction volume of the Bitcoin network, this speed is far from meeting the requirements. The Bitcoin system is starting to suffer congestion. Transactions take a long time to be processed, and transaction fees are high.

<!--truncate-->

Over the years, the bitcoin community has made various suggestions on how to improve the scalability of bitcoin, but no consensus has been reached in the end, which has led to the emergence of fork coins like BCH. With the endless efforts of the technical exploration, a possible solution is proposed and widely accepted which is called the Lightning Network.

## What is lightning Network?

Simply put, the main idea of ​​the Lightning Network is to put a large number of bitcoin transactions in bidirectional payment channels outside the Bitcoin blockchain. Bitcoin's blockchain mechanism itself provides good credibility, but it is slow; for a large number of small transactions, such high credibility is overwhelmed.

## How does Lightning Network work?

Suppose there are two people, A and B. They need to send money to each other regularly. How can they send money to each other at a fast speed with the lowest fee? So they established a channel on the Lightning Network.

First, set up a multi-signature wallet. Then deposit a certain amount of bitcoin into their wallet. Save the wallet address to the Bitcoin blockchain, along with the balance information in a smart contract.

After setting up this payment channel once, the two parties can conduct unlimited transactions without storing any information on Bitcoin blockchain. All these transactions are the redistribution of funds within a shared wallet. For example, if A wants to send one BTC to B, then he needs to transfer ownership of the money to him. The two then used their private keys to sign the updated balance sheet.

Whenever a dispute occurs or the payment channel is closed, both parties can use the latest signed balance sheet to pay their share in the multi-signature wallet. If A and B decide to close the channel after a transaction, then A will get 2 BTC and B will get 4 BTC.

Only after the channel is closed, the initial balance and final balance information will be uploaded to the Bitcoin blockchain. Therefore, the way the Lightning Network works is to allow users to make a large number of transactions outside the main chain and record them separately.

Another attractive feature for Lightning Network is cross-chain atomic swaps. Simply put, this is a way to freely exchange any given cryptocurrency with another cryptocurrency without using a cryptocurrency exchange.

In general, Lightning Network has adopted a more reasonable payment network architecture and improved payment efficiency. Transactions can be sent directly without having to broadcast to everyone. Only when the two parties of the transaction are in dispute requires the on-chain consensus process and transactions are recorded on the blockchain.

## Advantages of Lightning Network

**Fast transaction**

Once Lightning Network is online, you don't need to wait for transactions to be confirmed multiple times. No matter how busy the Bitcoin network is, Lightning Network transactions are almost instantaneous. If this is the case, the cryptocurrency market will take a big step towards competing with traditional payment systems such as Visa, MasterCard and PayPal.

**Scalability enhancement**

The Lightning Network is able to increase the transaction speed of Bitcoin and other cryptocurrencies to at least 1 million transactions per second.

**Cross-chain atomic swap**

As long as the two blockchains share the same cryptographic hash function (most blockchains share the same hash function), users can forward funds from one chain to another without trusting third-party intermediaries, such as exchanges.

**Security and anonymity**

Most cryptocurrencies are not completely anonymous. It is still possible to track from one wallet to another based on transactions. However, if the Lightning Network is used, most transactions occur outside the main blockchain, so almost all micropayments made through the Lightning Network channel cannot be tracked.

## Limitations of the Lightning Network

**Complexity of the channel**

The Lightning Network is conceptualized as a network of channels. Once these channels are established, they will theoretically be able to achieve seamless transactions. However, unexpected outcome can take place when there are too many intermediate channels. Of course, the fee will increase dramatically in this situation.

**Maximum channel capacity**

Another disadvantage of Lightning Network is that in its current version, there is an upper limit on channel capacity. In other words, the number of Bitcoins stored in the wallet by two users when establishing a channel is the maximum amount of funds in the channel. This setup creates a situation where some users may need to choose between liquidity in the Lightning Network channel and liquidity in the main blockchain. This is far from ideal, especially for those with rather limited resources.

**Centralization**

In addition, people have been worried about the emergence of "hubs", a type of node with a lot of funds. Most transactions will pass through these nodes. Many Bitcoin enthusiasts believe that this will lead to further centralization of the Bitcoin network.
