---
slug: /What-is-blockchain-consensus-and-how-do-different-consensus-mechanisms-work
id:What-is-blockchain-consensus-and-how-do-different-consensus-mechanisms-work
title: What is blockchain consensus and how do different consensus mechanisms work?
sidebar_label:What is blockchain consensus and how do different consensus mechanisms work?
author: DueDEX CS
author_title: DueDEX
author_url: https://www.duedex.com
author_image_url: https://duedex.zendesk.com/system/photos/3606/0800/5893/twitter4.png
tags: [DueDEX, Bitcoins]
---

The consensus is an important component in a blockchain network. Like the role of a bank in a centralized financial system, consensus mechanism validates all the transactions and make sure the network’s integrity and security. Today we will cover the basics of consensus and major consensus mechanisms that are widely used in the industry.


<!--truncate-->

## What is a consensus?

A consensus algorithm can be defined as a mechanism for reaching consensus in a blockchain network. As a distributed system, the blockchain does not rely on a central institution. It is maintained by all the nodes participating in the network. At the same time, the consensus algorithm acts as the role to guarantee the normal execution of protocol and transactions can be conducted properly without worrying about being spent twice.

## The role of consensus mechanism

**Reaching a consensus**

The consensus mechanism attempts to solve one of the most complex issues regarding decentralized systems - reaching a unified agreement on the authenticity and accuracy of data, especially the Byzantine Generals Problem. Unlike a centralized system, users do not have to trust anyone in the system. The protocol embedded in the network ensures that the state of the public ledger is always updated with the consensus of the public.

**Prevent double-spend attacks**

The consensus mechanism prevents any user from spending their crypto assets more than once, which has been a problem for all digital currencies long before Bitcoin appeared. The "double-spend attack" refers to the possibility of digital currency being spent twice. The protocol rules embedded in the blockchain consensus mechanism ensure that only valid and authentic transactions are recorded in the public ledger. As miners' computing power expands, it becomes increasingly difficult to conduct double-spend attacks by changing the details of any previous transactions.

**Incentive**

Creating a self-regulating trustless system needs to motivate network participants. The consensus mechanism does this by motivating good behavior and, and in some cases, punishing bad participants. The first consensus mechanism used by Bitcoin is Proof-of-Work (PoW).

It rewards Bitcoins to miners for verification of each transaction. The double-spending attack requires a lot of computing power and money, so these resources will be more willing to work for the system rather than against it.

**Fault-tolerance mechanism**

Fault-tolerance refers to the ability of a distributed system to run normally when in the face of threats or failures. The consensus mechanism ensures that the blockchain is fault-tolerant and therefore reliable and consistent.

## Major consensus mechanisms

**Proof of work(PoW)**

As mentioned above, Proof-of-work algorithm is the first consensus algorithm. It is used in Bitcoin and many other major cryptocurrencies. Proof-of-work mining is in fact, a hash collision. More computing power means more times of trying per second. In other words, miners with high hash rates are more likely to find valid values ​​for the next block, so that with the higher possibility to win the block rewards.

The proof-of-work consensus algorithm ensures that only one miner can verify a new block transaction and add it to the blockchain, provided that all nodes agree that the block hash value provided by the miner is a valid Proof of Work.

Proof of work is agreed to be the fairest and transparent consensus. The defect is also quite obvious that it wastes a lot of electric power and IT infrastructure since basically, the hash value collision has no actual meaning except competing for the block reward.

**Proof of Stake (PoS)**

In 2012, someone with a nickname called Sunny King launched Peercoin. This cryptocurrency uses a proof-of-work mechanism to issue new coins and a proof-of-stake mechanism to maintain network security. This is the first application of the proof-of-stake mechanism in the crypto industry.

Different from PoW which requires the validators to perform a certain amount of calculation, the Proof of Stake mechanism requires the validator to provide ownership of a certain amount of cryptocurrency.

Based on the amount of cryptocurrency the miner is owning and the time of each owner's cryptocurrency, the difficulty of mining is determined and speeds up the search for random numbers.

This consensus mechanism can shorten the time required to reach consensus, and reduce the possibility of a 51% attack but at the same time, bring defects such as a high possibility of successful attack when holding a large amount of coin for a long time.

**Delegated Proof of Stake**

DPoS is a new consensus mechanism to ensure network security. While trying to solve the problems of the traditional PoW mechanism and PoS mechanism, it can also offset the negative effects brought by centralization through the implementation of technology-based democracy.

The DPoS mechanism is similar to the voting of the board of directors. The mechanism has a built-in real-time shareholder voting system. The decentralization of the blockchain established based on the DPoS mechanism depends on a certain number of representatives, not all users.

In such a blockchain, all nodes vote to elect a certain number of node representatives, and they will act as agents for all nodes to confirm the block and maintain the normal operation of the system. At the same time, all nodes in the blockchain have the power to recall and appoint representatives at any time. If necessary, all nodes can vote to make the current node representatives disqualified, re-elect new representatives, and achieve real-time democracy.

The DPoS mechanism can greatly improve the efficiency of the network, however, it is also criticized for not decentralized.

## Closing Thoughts

As mentioned earlier, consensus mechanisms are a key factor in maintaining the integrity and security of blockchain networks. They allow distributed nodes to reach consensus.

However, as you can see, there's an impossible triangle existing among efficiency, decentralization, and security. PoW is agreed to have the best decentralization and security but low efficiency. DPoS has the best efficiency which can achieve a TPS around 10k, however, it's easier for nodes to team up and make the centralized. The chaos of what the STEEMIT network is going through might be a proof.

The development of a consensus mechanism will be a key breakthrough in the entire blockchain industry and blockchain technology to explode.
