[Table of Contents](index.md)
# Chapter 5: The Developer Guide
### The Stellar Laboratory
The Stellar Foundation maintains a web interface to Stellar called [Stellar Laboratory](https://www.stellar.org/laboratory/). If you are a developer new to Stellar, this is the best place to start. It allows you to do common operations like creating an account and viewing transactions. It shows the responses as JSON objects.

### Stellar Testnet
The **testnet** provides a safe way to experiment with various Stellar operations. The Stellar Laboratory introduced above also provides the option to connect to the testnet instead of the Public network.

### Stellar Architecture
Stellar is built on the following modular components that work together to facilitate a robust network.
#### Stellar Core
This is the fundamental building block of the Stellar network. Each node on the network runs a copy of stellar-core that supports core operations like submitting and querying transactions. For more details, refer to the [stellar-core project on Github](https://github.com/stellar/stellar-core)
#### Horizon API
Horizon is the primary API used by client applications to talk to stellar-core. It lets you make HTTP requests to perform all common operations like managing accounts, transactions and assets. For simple operations you can use the Horizon endpoint maintained by the Stellar Foundation. To reliably support your custom application, you would want to run your own Horizon API server. For more details, refer to the [Horizon API project on Github](https://github.com/stellar/horizon)
#### Bridge server
The Bridge server simplifies things even further for special use cases involving payments by allowing you to use HTTP requests for sending and receiving payments.
For more details, refer to the [bridge-server project on Github](https://github.com/stellar/bridge-server)
### Supporting the Stellar Network
The health and viability of the Stellar Network depends on diverse participation from various nodes around the world. You can support this mission by running your own stellar core servers. In addition to that, you stellar core server can function as a **validator** and participate in consensus. Ultimately, you can help other nodes come up to speed by running as an **archiver** that publishes transactions to an archive. This archive can then be used by new servers to catch up on historical transactions. This is summarized well on the official developer documentation page under [Level of participation to the network](https://www.stellar.org/developers/stellar-core/software/admin.html#level-of-participation-to-the-network)
