[Table of Contents](index.md)
# Chapter 4: Advanced Concepts
### The Decentralized Payment Network
Blockchain's ability to append data in a tamper proof way means it can be used by a network of servers that are not centrally managed. This decentralized setup allows users to trust the transaction data stored in the blockchain without having to trust the users themselves. The combination of blockhain and  decentralization led to the massive popularity of Bitcoin and other crypto currencies that followed. The Stellar Network facilitates a similar decentralized payment network where anyone can add servers and participate in transaction processing.

### Stellar Consensus Protocol
### The Ledger
### Assets and Anchors
### Exchange and Orderbook
#### Stellar Distributed Exchange
In addition to handling payments, the Stellar network can act as a distributed exchange that allows trading of any type of asset users have added to the network.  These offers are stored in the Ledger.

#### Offers
You can make an offer to buy or sell an asset that you hold in your account.    Your offer can either be **filled** by previously made offers or be added to the **orderbook** and wait for matching orders.

#### Orderbook
The orderbook holds all active offers on the Stellar network with the bid and ask offers listed separately. This orderbook is independent of the orderbooks run by Cryptocurrency exchanges. You can see a screenshot of the [orderbook on the Kraken exchange](https://www.kraken.com/charts) for the XLM/USD pair.
![Kraken XLM orderbook](/assets/Kraken-xlm-orderbook.jpg)

#### Cross-Asset Payments
Using Stellar's cross-asset payment feature, users can trade between assets that may not have their own trading pair or have a thin or nonexistent orderbook.  If a user wants to sell asset A for asset C but can find no offers for such a trade, asset A can be traded for asset B, which can then be traded for asset C, assuming there are offers for such trades. This would be considered a 2-hop trade. Conversion paths can contain up to 6 hops but will either be completed fully or not at all. The user will never be left with unwanted assets.  The process of finding the best possible path is called pathfinding and is handled outside of Stellar Core.
