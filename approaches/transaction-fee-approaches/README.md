---
description: >-
  Comparing the different transaction fee approaches that a network could use
  for their fee model
---

# Transaction fee approaches

Each transaction submitted and stored on a distributed ledger will generate a certain amount of processing and storage costs. Transaction fees are commonly used to pay for node operators that are responsible for verifying transactions and storing the ledger's state.



## Percentage transaction fees are not necessary

A percentage based wealth tax is one of the most reliable and predictable ways that a Web3 treasury could be funded over the long term. This tax would mean that the users with the most amount of coins would pay proportionally the most in tax.

If an ecosystem didn’t want to adopt a wealth tax it would have a problematic situation for generating meaningful income for the treasury over the long term.

Fixed fee transactions are inherently unfair for the users with the least amount of coins. Those with less coins would proportionally pay the most in fees to the network. Those with the most coins would pay proportionally the least. A fixed fee model makes it easier for the wealthier users to remain wealthy whilst punishing the poorest users with higher proportional fees.

Combining a minimum fixed fee (to protect the network from spam) and a percentage transaction fee would be a fairer approach for generating income for the treasury. However this approach still faces the transaction deadweight loss problem. The larger the fees are the larger the incentive there is for people to use and migrate to other networks for daily transactions.

Percentage transaction fees would also mean that the most active and valuable users in the network would be the only ones that would be contributing towards the treasury. The least active and least valuable users that buy and hold the network coin would contribute the least. The incentives are not fairly aligned with a transaction fee approach for generating treasury income as these inactive users are gaining all the benefits from the contributions that get made by active users.

Percentage fee transactions will therefore be omitted from the transaction fee comparison due to the fact that a wealth tax is a far more effective and egalitarian approach for generating treasury income.



## Handling transaction spam

Transaction fees could be considered a necessity for Web3 networks. Paying node operators with a wealth tax would not mean that transactions can then be free. If transactions were free it would create an easy attack vector for malicious actors as they could spam the network with transactions and make it unusable for other people. This type of attack is known as a denial of service attack.

Fees that are too low create a risk of inviting these denial of service attacks. Fees that are too high creates the risk that users migrate to other networks that are cheaper to use. Transaction fees will influence the overall usage and emergent behaviours across the networks due to the fact that transaction fees determine the actual cost of using the network on a daily basis.

Web3 ecosystems need to consider how they can keep the fees as low as possible whilst also not creating opportunities for the network to be attacked.

The simplest approach for handling the denial of service attack vector is ensuring that all transactions have a minimum fixed fee. This fixed fee will be used to help pay for the node operator costs for handling the transaction that was submitted. Providing the transaction fee model is profitable for the node operator there would be a lower risk of a prolonged denial of service attack due to the fact that it would be profitable for node operators to continue processing the spammed transactions. The problem with a minimum fixed fee solution is it has the most negative impact on the poorest users in the network, as every transaction they submit will need to pay this fee.



## **Approaches for transaction fees**

The following are some example transaction fee approaches that could be adopted:

* [**Fixed fee**](fixed-fee.md) - A fixed fee amount is charged to process and store a transaction, the fee amount stays the same regardless of how big or small the transaction is in terms of the value of assets being used.
* [**Finality fee**](percentage-finality-fee.md) - Transactions could be prioritised when users are willing to pay a higher fee than the other transactions that have been submitted.
* [**Demand fee**](percentage-demand-fee.md) - The fee to submit transactions on the network gets increased when the network experiences a high or excessive amount of user demand.



To compare these decision approaches a number of [factors have been considered](transaction-fee-factors-for-consideration.md) and then applied to each approach to try and determine the strengths and weaknesses of each one.

<figure><img src="../../.gitbook/assets/transaction-fee-approaches.png" alt=""><figcaption></figcaption></figure>



**Key takeaways**

* **Unfairness of fixed fees -** The wealth that exists in any ecosystem will likely not be split equally between its users. It will often be the case that there are some individuals that are far wealthier than others and there will also be individuals who are far poorer than everyone else. Similar to existing fiat systems this factor translates into different user behaviours and spending habits due to the wealth that each user has available to them. Fixed fees would simply mean that the wealthier individuals that can make larger transactions would be paying less tax proportionally with their transaction fees than the poorest individuals in the ecosystem. The wealthiest individuals would pay the least in fees proportionally and the poorest users would pay the most. This is inherently unfair as the poorest individuals would now be paying the most in fees proportional to their wealth. The richest individuals would be receiving the same security and safety benefits from the network but would receive those benefits, security and protection for a much larger amount of assets. The poorer individuals would be paying proportionally more in fees to the network to secure the assets of wealthier people who have paid less than others proportionally. A fixed fee approach could represent a contributing factor towards an increasing wealth gap between the wealthy and poor over the long term.
* **Necessity of fixed fees -** Although fixed fees are inherently unfair to the poorest individuals in a network the need to use a fixed fee approach is not easily avoided. If transaction fees are percentage based and proportional to the value of the transaction the easy attack vector that emerges is that people can flood the network with extremely small transactions that have a tiny fee. The network will only be able to handle a certain amount of transaction volume and also will require a certain level of income to pay for the processing and storage costs. Fixed fees are currently a necessary part of the solution for preventing the network from being spammed. There must be a cost and deterrent to the creator of the transaction to prevent them from being able to act maliciously without penalty. This necessity for fixed fees helps to highlight the paramount importance of making highly scalable networks that can support a low minimum fixed fee. Highly scalable networks can use a much smaller fee to pay for the operational costs of verifying and storing a large number of transactions. The lower the minimum fixed fee is the more egalitarian the network becomes due to the reduced impact of the fixed fee on poorer individuals.
* **Finality fees and demand fees are not inherently required or desirable** - The ideal outcome for a Web3 network is it is able to handle a growing amount of transaction volume and can respond to these changes in demand dynamically and without the need for a finality or demand based fee. Sharded ledgers that are horizontally scalable could represent the solution for achieving this outcome of not needing additional fee structures. If finality or demand fees are introduced there is a concern around how wealthy individuals could exploit those fee structures to try and benefit themselves. Due to this it would likely make sense to introduce a combination of percentage fees and fixed fees into either of these fee models if they needed to be introduced.



**Transaction fee approaches analysis**

{% content-ref url="transaction-fee-factors-for-consideration.md" %}
[transaction-fee-factors-for-consideration.md](transaction-fee-factors-for-consideration.md)
{% endcontent-ref %}

{% content-ref url="fixed-fee.md" %}
[fixed-fee.md](fixed-fee.md)
{% endcontent-ref %}

{% content-ref url="percentage-finality-fee.md" %}
[percentage-finality-fee.md](percentage-finality-fee.md)
{% endcontent-ref %}

{% content-ref url="percentage-demand-fee.md" %}
[percentage-demand-fee.md](percentage-demand-fee.md)
{% endcontent-ref %}
