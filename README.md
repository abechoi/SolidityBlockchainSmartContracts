<div align="center">
<h1>Solidity, Blockchain, and Smart Contract Course</h1>
<h2>Beginner to Expert Python Tutorial</h2>
<p>by Patrick Collins and freeCodeCamp</p>
</div>

## Table of Contents
1. [Blockchains](#blockchain)


## Blockchains

A blockchain is made of blocks with an index, nonce, data, prev, and hash fields.

Blocks are ordered by index, and the prev field points of the previous block's hash.

If the data changes, the nonce changes, then the hash changes, which will break the chain since the prev and hash no longer match.

Mining is the process of finding the solution to the blockchain problem.

### Consensus

Consensus is the mechanism used to agree on the state of a blockchain. If data is mutated on a blockchain, the consensus will match it against other blockchains on the network, and mark it invalid at the hash address.

Proof of Work is a consensus system that finds the author, miner of the block, to prevent others from creating fake blocks. When mining, if a node mines a block which is then added to the blockchain, and the newly added block can be validated by tracing it to the author who mined it.

Proof of Stake is a consensus system that has validators, instead of miners. Validators put up collateral (stake) as a sybil resistance mechanism, and if validators try to create false transactions, they will lose their stake.

Sharding and Rollups are scalability solutions for layer 1 systems, base block chain implementations such as Bitcoin and Ethereum.

### Transactions

Gas is the measure of computation use, gas price is the price per unit of gas, gas limit is the max amount of gas in a transaction.

note: Gas prices fluctuate depending on the frequency of use.

Transaction Fee = gas used * gas price
21,000 gas @ 1 GWEI per gas = 21,000 GWEI
(21,000 = $0.0868~)
(1 Ether = 1,000,000,000 GWEI)

### Gas Stations

A gas station is an application to view recommended gas prices in GWEI.

   - Go to [ethgasstation.info](https://ethgasstation.info) to view recommended gas prices in GWEI.

Private keys is for the owner, while public keys are for everyone else to see.

Wallet addresses is made up of the last 20 bytes of the private and public key, hashed together.

### Hash

Hash is a unique fixed length string that decrypts data, by using a hash function.

Ethereum utilizes Keccak-256 for hashing.

   - Go to [andersbrownworth.com](https://andersbrownworth.com/blockchain/block) to generate a hash.
   - Fill out the fields: Block, Nonce, Data and hit the "Mine" button.

### Rinkeby Test Network

Rinkeby Test Network is a clone of the Ethereum Network, that does not use real money.

Etherscan is a Block Explorer, an application that displays transactions within the blockchain.

A Faucet is an application that provides free test tokens.

   - To get test tokens, create a Metamask wallet.
   - Go to [faucet.rinkeby.io](https://faucet.rinkeby.io), and make a tweet to request the funds, be sure to insert your address.
   - Copy the link to tweet, paste it on faucet.rinkeby.io, and clicn the "Give me Ether" button.
   - In a short time, the requested Ether should be displayed in the wallet.


