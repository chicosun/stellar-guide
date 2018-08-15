[Table of Contents](index.md)
# Chapter 4: Advanced Concepts
### The Decentralized Payment Network
Blockchain's ability to append data in a tamper proof way means it can be used by a network of servers that are not centrally managed. This decentralized setup allows users to trust the transaction data stored in the blockchain without having to trust the users themselves. The combination of blockchain and  decentralization led to the massive popularity of Bitcoin and other crypto currencies that followed. The Stellar Network facilitates a similar decentralized payment network where anyone can add servers and participate in transaction processing.

### Stellar Consensus Protocol
The mechanism by which the decentralized network of servers around the world arrive at a consensus is called the Stellar Consensus Protocol. In traditional  systems like banks, transactions are trusted implicitly. The activities happen within the bank's own servers. But in a decentralized network distributed worldwide, not all servers can implicitly trust each other. This requires an explicit mechanism by which consensus can be established. In the case of Bitcoin, mining is the primary mechanism that drives the network towards consensus. The Stellar Network doesn't rely on mining. Instead, it uses the Stellar Consensus Protocol in which participating servers vote on the correct state of the transactions. To avoid requiring the entire global network to agree on each transaction, it requires each server to trust a subset of servers in the network which in turn can be combined with the votes to arrive at a consensus.

### Distributed Ledger
When the Stellar Network achieves consensus on the last set of transactions, it stores them in a **Ledger**. Typically, a new ledger is created every 5 seconds on the network. Each Ledger also stores a reference to the ledger that was closed previously. Once a ledger is closed it cannot be modified but you can traverse the chain of ledgers all the way back and read the transactions stored in each ledger.

### Assets and Anchors
While Lumens are the native currency on Stellar, the Network allows you to hold other assets that are not native to Stellar. This way, you can issue a tradable asset (e.g. Tokens) on Stellar and take advantage of the distributed blockchain network. The assets are backed by issuers known as **Anchors** who vouch for the assets held by an account. 

### Exchange and Orderbook
#### Stellar Distributed Exchange
In addition to handling payments, the Stellar network can act as a distributed exchange that allows trading of any type of asset users have added to the network.  These offers are stored in the Ledger.

#### Offers
You can make an offer to buy or sell an asset that you hold in your account.    Your offer can either be **filled** by previously made offers or be added to the **orderbook** and wait for matching orders.

#### Orderbook
The orderbook holds all active offers on the Stellar network with the bid and ask offers listed separately. This orderbook is independent of the orderbooks run by cryptocurrency exchanges. Here is a screenshot of the [orderbook on the Kraken exchange](https://www.kraken.com/charts) for the XLM/USD pair.
![Kraken XLM orderbook](/assets/Kraken-xlm-orderbook.jpg)
