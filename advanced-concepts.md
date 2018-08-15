[Table of Contents](index.md)
# Chapter 4: Advanced Concepts
### The Decentralized Payment Network
Blockchain's ability to append data in a tamper proof way means it can be used by a network of servers that are not centrally managed. This decentralized setup allows users to trust the transaction data stored in the blockchain without having to trust the users themselves. The combination of blockhain and  decentralization led to the massive popularity of Bitcoin and other crypto currencies that followed. The Stellar Network facilitates a similar decentralized payment network where anyone can add servers and participate in transaction processing.

### Stellar Consensus Protocol
### The Ledger
### Assets and Anchors
### Exhange and Orderbook
#### Stellar Distributed Exchange
The Stellar network can act as a distributed exchange of any type of asset users have added to the network.  Its ledger stores user's balances as well as offers users make to buy or sell assets.

#### Offers
Offers in Stellar operate the same as limit orders in traditional markets. In order to make an offer, the user must hold the asset it wants to sell.  When a user makes an offer it is checked against existing offers in the orderbook.  If the offer crosses an existing offer it is filled at that price.  If the offer doesn't cross an existing offer, the offer is saved in the orderbook until it is taken by another offer, taken by a payment, cancelled by the user, or invalidated because the user no longer holds the asset for sale.  When multiple offers are filled at the same price, the oldest offer is filled first.

#### Orderbook
The orderbook is a record of all outstanding buy and sell offers on the Stellar network.  The orderbook lists every offer to buy an asset on one side and every offer to sell an asset on the other side.  Depending on the trading volume, some assets will have a very thin or even nonexistent orderbook.  However, Stellar's cross-asset payments can assist in filling thinly traded assets by 'routing' them through more heavily traded assets.

#### Cross-Asset Payments
Using Stellar's cross-asset payment feature, users can trade between assets that may not have their own trading pair or have a thin or nonexistent orderbook.  If a user wants to sell asset A for asset C but can find no offers for such a trade, asset A can be traded for asset B, which can then be traded for asset C, assuming there are offers for such trades. This would be considered a 2-hop trade. Conversion paths can contain up to 6 hops but will either be completed fully or not at all. The user will never be left with unwanted assets.  The process of finding the best possible path is called pathfinding and is handled outside of Stellar Core.
