---
description: >-
  An optional proportional fee increase for people that want to increase their
  transactions speed of finality
---

# Finality fee

<div align="left"><figure><img src="../../.gitbook/assets/transaction-fee-finality.png" alt="" width="270"><figcaption></figcaption></figure></div>

A finality fee is an additive fee model that can be used alongside the fixed transaction fee approach that is used for the majority of transactions. Instead of having a single transaction fee approach, a finality fee would mean that users are able to pay a higher fee to increase the speed of finality for their transactions to get processed.

A finality fee could be useful for users that want to have their transactions processed quickly. A user could increase the fee they’re willing to pay to achieve this outcome. If the user didn’t mind when the transaction was finalised they could just pay the minimum fixed fee and let the network finalise their transaction whenever it was able to do so.

A finality fee likely needs to combine a fixed cost increase with a percentage cost into the finality fee. The fixed cost would help with preventing smaller transactions from being able to easily spam the network with transactions that have a small finality fee as this would mean they were prioritised over all other existing transactions for a fractional amount more. The percentage fee would help to prevent the individuals with the most money having priority access to fast finality transactions as they would need to pay proportionally based on the value they are transacting with. This helps to prevent them from having an advantage due to the amount of money they have over poorer individuals.

A finality fee is not an inherently desirable fee model to introduce into a network. Finality fees are not necessarily required for networks that are able to scale and handle a growing amount of transaction volume. Sharded ledgers that are horizontally scalable could provide a scalability solution that means finality fees might not be necessary.



**High taxation fairness (Score - 4)**

Everyone's assets are treated equally as fees would be proportional based on the amount of coins they are transacting with. A larger transaction would pay a larger fee amount to increase their transaction finality. One main area of concern around this approach is it can introduce added complexity when using the network as someone's transaction could be delayed due to someone else submitting a higher finality fee after viewing the existing transactions and fees. This behaviour could be annoying for users that just want a simple experience and don’t want to be concerned with suddenly reordered transactions that could impact them due to other users suddenly being able to prioritise their transactions with an increased fee.



**High incentive complexity (Score - 2)**

A finality fee approach introduces more opportunities for front running where someone could add in a transaction with a higher fee to quickly get their transaction confirmed and finalised. The network's overall complexity could be increased if every protocol being built on the network needs to consider that now any user will be able to front run the current pending transactions. This ability to change the prioritisation of transactions would become a complexity that the end users of the network need to be familiar with and consider when submitting their own transactions. Front running could create opportunities to generate more income and profit, if this is the case it should be expected that someone would look to exploit those opportunities. There is incentive complexity around how wealthier individuals could easily create multiple smaller transactions that have the fast finality fee applied. If this gives them an advantage in any way by doing this it should be expected that this type of behaviour would eventually be exploited.



**Moderate network risks (Score - 3)**

A finality fee approach would mean the network is able to generate more income when there is moderate to higher demand and when there are users that need to finalise their transactions as quickly as possible. A combination of fixed fees and percentage fees within a finality fee can help with preventing spam and with preventing wealthier individuals from having an advantage over others. Being able to front-run existing transactions with finality fees does introduce some risks around people constantly trying to exploit different usage patterns and behaviours in the network. There is also a risk that individuals with more money are able to sustain an attack on the network using a large amount of smaller transactions that apply the finality fee.



**Total score = 9 / 15**
