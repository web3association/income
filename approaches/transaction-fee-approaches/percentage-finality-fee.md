---
description: >-
  An optional proportional fee increase for people that want to increase their
  transactions speed of finality
---

# Percentage finality fee

<div align="left">

<figure><img src="../../.gitbook/assets/transaction-fee-finality.png" alt="" width="180"><figcaption></figcaption></figure>

</div>

A finality fee could be useful for enabling users to indicate how important the speed of finality is for their transaction. If a transaction needs to be finalised quickly then the user would be able to increase the fee they’re willing to pay to achieve that outcome. If the user didn’t mind when the transaction was finalised they could set the fees to be the cheapest possible and let the network finalise their transaction whenever it was able to do so in the future. Percentage finality fees are recommended over fixed finality fees due to this approach being fairer for all users involved in the network as the value of the assets are treated equally. Fixed finality fees would mean that the richest individuals in the network could always get the fastest finality without being as concerned about the price, with fixed fees the richest individuals would proportionally pay less than what smaller transactions would be paying due to the value of their transactions. A percentage finality fee would be used in combination with either or both the fixed fee and percentage fee approaches.



**High taxation fairness (Score - 4)**

Everyone's assets are treated equally as fees would be proportional to the assets they are transacting with. A larger transaction would pay a larger fee amount to increase their finality based on the same increase in fee percentage they are willing to spend. One main area of concern around this approach is it can introduce added complexity to using the network where someone's transaction could be delayed due to someone else submitting a higher finality transaction fee after viewing the existing fees. This behaviour could be considered less fair for users that just want a simple experience and don’t want to be concerned with suddenly reordered transactions due to other users suddenly prioritising transactions due to an increased fee.



**High incentive complexity (Score - 2)**

A finality fee approach introduces the opportunity for front running where someone could add in a transaction with a higher fee to more quickly get their transaction confirmed and finalised. The network's overall complexity could be increased if every protocol being built on the network needs to consider that users will be able to front run the current pending transactions. This ability to change the prioritisation of transactions then also becomes a complexity that the end users of the network need to consider. If front running creates opportunities to generate more income and profit than someone else then there is an incentive for people to exploit these opportunities.



**High network risks (Score - 2)**

This approach enables the network to generate more income when there is moderate to high demand and a user wants to increase the speed of finality for their transaction. Without a minimum fixed fee approach there is still a high risk that the network becomes bloated with small transactions that have a higher finality fee to be finalised more quickly. However this issue would be at least slightly less severe as the user would be paying a premium for these transactions to finalise more quickly than others. This premium in the fee paid could be sufficient enough as a deterrent to prevent people from spamming the network. However for wealthier individuals this higher fee could likely not have a very high influence on their ability to spam the network.



**High game theory risks (Score - 2)**

Wealthy individuals would have a larger opportunity to exploit the network and other users by using large amounts of smaller transactions with a high finality fee attached to ensure they are prioritised. This could slow down or impact the pending transactions that other users have submitted. It could also potentially give the wealthy individuals some financial advantage or ability to harm the network in some way.



**Total score = 12 / 20**
