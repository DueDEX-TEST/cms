---
slug: /How-does-Bitcoin-prevent-double-spending
id:How-does-Bitcoin-prevent-double-spending
title: How does Bitcoin prevent double spending?
sidebar_label:How does Bitcoin prevent double spending?
author: DueDEX CS
author_title: DueDEX
author_url: https://www.duedex.com
author_image_url: https://duedex.zendesk.com/system/photos/3606/0800/5893/twitter4.png
tags: [DueDEX, Bitcoins]
---


#### **What is double spending?**

Double spending refers to the possibility that in the digital currency system where reproducibility of the data is more likely, the system may have the same digital asset be reused due to improper operation.
<!--truncate-->
Double spending is a problem that any digital currency must solve. If a certain digital currency is reused, the same amount of money is spent two or more times, and it has no value.

**How does the centralized digital currency prevent double spending?**

Let’s take Alipay as an example. The money in Alipay does not exist in the digital world. On the contrary, it still exists in real-world banks. When you pay through Alipay, the actual process is:

l You pay the money to Alipay;

l Alipay puts your money in their bank account;

l After you confirm the receipt of your purchase, Alipay withdraws the money from their bank account and pays it to the seller.

To put it more simply, Alipay is just a third-party intermediary. Such third party organizations perform centralized management of data and modify the account balance in real time to prevent "double spending".

This type of management can cause some problems. Firstly, most of the services are not free of charge. Some transaction fees are cost during the process. On the other hand, even though companies like Alipay doesn’t charge any fee from people, they still successfully have access to all your payment data by offering their services to you. This could leave some potential risks to the security and privacy of your personal data.

**How does Bitcoin solve the double spending?**

As a decentralized peer-to-peer electronic cash system, Bitcoin mainly relies on unspent transaction output (UTXO) and time stamps to solve the double spending problem.

**UTXO**

The basic unit of a Bitcoin transaction is an unspent transaction output, or UTXO for short. UTXO is a certain amount of Bitcoin currency that can no longer be divided, locked by the owner, and recorded in the blockchain network. When a user receives Bitcoin, the amount is recorded in the blockchain as UTXO. The bitcoin that a user owns will actually be recorded as UTXO into hundreds of transactions and hundreds of blocks. The concept of bitcoin balance is actually a derivative of a bitcoin wallet. The Bitcoin wallet calculates the user's Bitcoin balance by scanning the blockchain and aggregating all UTXOs belonging to the user. After a bitcoin transaction is created and broadcasted to the blockchain network, the node that received the transaction information will verify the transaction and check whether it exists in UTXO. If the transaction output no longer exists in UTXO, the verification fails.

To illustrate this, let’s say Alice transfers 1 BTC to Bob, the whole process is as follows:

l The 1 bitcoin that Alice wants to send exists in Alice’s UTXO;

l The amount sent by Alice is equal to the amount accepted by Bob, which is 1BTC;

l After Bob received it, 1 bitcoin was unlocked from Alice’s UTXO and entered into Bob's UTXO.

Every current "unspent transaction output" is recorded in the Bitcoin network. When a node receives a transaction, it needs to check in the UTXO database to see if the UTXO referenced by the exchange exists and whether its payee (owner) is the payer of the current new transaction. After the transaction, the system will update accordingly.

**Time stamp**

Timestamp is a data that can indicate that a piece of data existed before a certain time. Usually a sequence of characters that uniquely identifies the time of a moment. Data generated using digital signature technology, the object of the signature includes the original file information, signature parameters, signature time and other information. Widely used in intellectual property protection, contract signing, financial accounting, electronic bidding, stock trading, etc.

The Bitcoin system also introduces the concept of timestamps. In fact, the Bitcoin system is a distributed database with many nodes participating in it, and it is an open ledger. The system will automatically timestamp the data information of each block and then calculate an encrypted value, that is, hash.

The Bitcoin system itself constructs a time-stamp system that never stops and is indestructible. The system uses digital timestamps to ensure that each block is connected into the blockchain in chronological order. The timestamp also marks the time of each piece of data on the blockchain.

Assuming that Alice transfers 1 BTC to Bob and John at the same time, only one of the two transactions will be successfully completed. Because the nodes in the system will selectively record the transaction received first. When two transactions are recorded by the same node at the same time, according to the timestamp data, only the first recorded transaction can be confirmed successfully. If the time interval between Alice’s two transfers is very small. Two nodes will broadcast the blocks they have mined out to the Bitcoin network at the same time. At this time, the blockchain will fork, and the remaining nodes will choose to build new blocks on the longest chain they think. Finally, the first to construct a new block and become the current longest chain transaction can be confirmed successfully. All subsequent nodes will build new blocks on this longest chain.

**Any exceptions?**

Yes. If someone can control more than 50% of the nodes in the Bitcoin network, even if he is behind the longest blockchain, he can always build a block on another blockchain until it catches up and becomes the new longest chain, which is called the Bitcoin 51% attack.

The 51% attack is indeed a problem that Bitcoin needs to be vigilant, but has not yet happened. The reason is also very simple. First, no one can easily control 51% of the nodes. Second, if a person or institution already has 51% of the nodes, he is the biggest beneficiary of the Bitcoin system. If he launches the 51% attack, the value of bitcoin will immediately return to zero, by which time he will become the biggest victim.
