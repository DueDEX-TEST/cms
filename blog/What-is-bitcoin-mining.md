---
slug: /What-is-bitcoin-mining
id:What-is-bitcoin-mining
title: What is bitcoin mining
sidebar_label:What is bitcoin mining
author: DueDEX CS
author_title: DueDEX
author_url: https://www.duedex.com
author_image_url: https://duedex.zendesk.com/system/photos/3606/0800/5893/twitter4.png
tags: [DueDEX, Bitcoins]
---


The most fascinating thing about Bitcoin is mining. Why is mining so fascinating? Because mining can get bitcoin. If you can successfully mine a block, you can get 12.5 bitcoin(approximately $75,000) and extra transaction fees. Isn’t this great?
<!--truncate-->

So what exactly is mining? How do miners get Bitcoin through mining? This needs to start with the PoW (Proof of Work) consensus mechanism adopted by the Bitcoin blockchain system.

**Consensus Mechanism**

The blockchain system can keep everyone's ledger consistent. This mechanism for keeping the data of all nodes consistent is called the consensus mechanism. The use of different consensus algorithms can help achieve the consensus of the blockchain and the ultimate goal is to maintain data consistency.

To achieve that goal, the Bitcoin network is using Proof of Work, which means that the system will prize and reward the participants based on how much work and effort they are willing to contribute to the network.

**What’s in a block?**

In the Bitcoin system, recording transactions is the fundamental function of the network. In the Bitcoin blockchain system, blocks are the most basic container for recording transactions. The current block size limit in Bitcoin (BTC) is 1MB. Since the size of the block is limited, the number of transactions that each block can accommodate is also limited. The current Bitcoin system stipulates that an average block is generated every 10 minutes. Therefore, the way a miner works is to collect all transactions generated online within 10 minutes and then record these transactions into a block. The block looks like this:

Amount

Transaction-out address

Transaction-to address

12.5

Miner Mike

10

Tom

Alice

7

Bob

Charlie5，Jason2

Please pay attention to the first record. In any block, the first one has no transfer-out address, which is called CoinBase. No one paid the miner the money, the miner just stated that he had obtained 12.5 bitcoins. All nodes agree that it could be written this way.

The data that each miner fill in must be different, because the first record of each miner is different. The miner Michael's CoinBase is "Michael got 12.5 BTC", and the miner Nancy's CoinBase is "Nancy got 12.5 BTC".

**Compete for the right of recording**

Every miner fills in the transactions he has collected and the income he deserves, but whose record will be accepted by everyone? Bitcoin uses a proof-of-work mechanism to allow miners to compete with each other to solve a mathematical problem. Whoever solves it first will be accepted and recognized by everyone. All the miners will then make a copy of that transaction list of that record, add it to the end of their own ledger, and then start a new cycle of mining process. From beginning to end, the ledger keeps growing, and the ledger grows thicker as number of transactions increases.

Satoshi Nakamoto decided to adopt the proof-of-work mechanism, the purpose was to prevent the system from being attacked. Satoshi Nakamoto believes that if an attacker wants to attack the network by destroying the ledger, he needs sufficient computing power. In other words, he is more powerful than the rest of the participants in the network, which means that he needs to pay a huge cost. If the return is not enough to offset the cost, the attacker has no economic incentive to attack the Bitcoin system.

In Bitcoin, everyone solves a math problem by trying different answers. Therefore it is not that people with big computing power will win every time, because someone may be lucky and find the answer with a few tries. But from a probabilistic point of view, the number of times to find the answer is the same as the ratio of his computing power in the entire Bitcoin network, that is, if a miner has 30% of the computing power of the entire network, then basically in 1000 minutes (100 blocks are generated), 30 blocks will be owned by him and he will receive 30% mining reward

**Closing Words**

In Satoshi Nakamoto’s original design, one CPU can be treated one vote. Computing power will decide which miner's ledger becomes the final ledger. With the increase in the price of Bitcoin, GPU mining took place. People were not satisfied with the speed of GPU and began to manufacture special chip for mining. The dedicated chip's ability to solve the Bitcoin hash problem is tens of thousands of times that of the ordinary CPU, so now Bitcoin is no longer "one CPU, one vote". It was monopolized by several large mining pools, deviating Bitcoin from the original intention of decentralized currency.
