<h1 align="center">Ethereum Development Guide</h1>

<p align="center">Welcome to Ethereum world !</p>

<br><br><br><br><br>


# Overview

![image]()

<br><br><br><br><br>

# Prerequisite

 - This project is based on ... 
     - Linux(`Ubuntu 18.04`)
     - `Node.js` version 16 (`NPM` version 8)
     - `Geth` version 1.10.xx
     - `Solidity` version 0.8.xx

 - Install `Git` to use `bash` if your OS platform is Window > [download](https://git-scm.com/downloads)
    - Please use `bash` terminal.

 - Install `Node.js` over 16 ver. > [website](https://nodejs.org/en/)
 
 - Install `Geth` > [download](https://geth.ethereum.org/docs/install-and-build/installing-geth)
 
 - Install `Metamask`(Wallet) as Google Chrome's extensions program (you need to install `Chrome Browser` before).
 
 - Make an account for `infura.io` > [sign up](https://infura.io/)

 - I’ll assume that you have some familiarity with `Solidity` and `JavaScript`.
   - If you need to review `Solidity`, this [Solidity guide](https://solidity-by-example.org/) is recommended. It will be helpful to understand about `Solidity`.
   - [Remix](https://remix.ethereum.org/) IDE helps you learn faster.

 - We recommend [Visual Studio Code](https://code.visualstudio.com/) as your IDE.
   - Install `solidity` extensions
   - Install `REST Client` extensions

<br><br><br><br><br>

# Getting Started

| Part | Dev. Options to Starter |
|:---:|:---:|
|[Blockchain Network](#Blockchain-Network)| `Main Network`, `Test Network` |
|[Connect to Network](#Connect-to-Network)|`Geth`, `infura.io`|
|[Mining](#Mining)|`Geth`|
|[Account](#Account)|`RPC`, `Geth`, `Metamask`, `Web3.js`, `Ethers.js`|
|[Sending ETH](#Sending-ETH)|`RPC`, `Geth`, `Metamask`, `Web3.js`, `Ethers.js`|
|[Compiling Smart Contract](#Compiling-Smart-Contract)|`solc`, `Truffle`, `Hardhat`|
|[Deploying Smart Contract](#Deploying-Smart-Contract)|`RPC`, `Truffle`, `Hardhat`, `Web3.js`, `Ethers.js`|
|[Using Smart Contract](#Using-Smart-Contract)|`RPC`, `Web3.js`, `Ethers.js`|

<br><br><br><br><br>

# Blockchain Network 

Before you begin, it is recommended that you understand the concept of `nodes` and `clients` that are components of the Ethereum network. [This article](https://www.coindesk.com/learn/ethereum-nodes-and-clients-a-complete-guide/) is well described about it.


For development, Ethereum network must be selected. To test and operate "smart contracts" and dApps, typically follow these development procedures:

1. First, configure a blockchain network in a developer local computer environment, then develop `smart contracts`, `dApps`.

2. Develop `smart contracts`, `dApps` over test networks such as "Rinkeby" and "Ropsten" before moving to production level.

3. Connect with the main network(production).


There are [more blockchain networks](https://chainlist.org/).

The status of the blockchain network can be checked through `Ethereum Blockchain Explorer` of each network.

 - [mainnet](https://etherscan.io/)
 - [rinkeby](https://rinkeby.etherscan.io/)
 - [ropsten](https://ropsten.etherscan.io/)

<hr>

###### [Go to Top : `Getting Started`](#Getting-Started)


<br><br><br><br><br>

# Connect to Network

Blockchain requires everyone to have the same ledger. In other words, you, a developer, should also synchronize the ledger through participation in the blockchain network. This means that you become one of the blockchain `nodes`. And blockchain `clients` help with the role of blockchain network nodes such as holding a ledger or participating in consensus algorithms. The most famous blockchain client is the `Go-Ethereum(Geth)` based on [Golang](https://go.dev/). 

Working with the `mainnet` from the early stages of development is expensive and time consuming. Therefore, Ethereum networks provide test networks such as "Rinkeby" and "Ropsten". In addition, `Ethereum Coin` can be received through the `faucet` of the test network, so it can be developed with significant cost savings.

But still there is a problem. This is because both the main network and the test network are large and time consuming ledgers that need to be synchronized. It can also be configured as a `light node` via the `sync mode` option in the Ethereum client, but it has functional limitations and its size is still not negligible.

For this reason, services such as `infura.io` emerged. These services can significantly reduce development time and administrative costs. Therefore, the process of participating in the Ethereum network through an Ethereum client such as `Geth` is excluded from this guide due to the practical issues presented above. Instead, it replaces the Ethereum client role with the `infura.io` service.

<br><br>

## Development Local Network Configuration Options

 - [Geth]()
 - [Truffle]()
 - [Hardhat]()

<hr>

###### [Go to Top : `Getting Started`](#Getting-Started)

<br><br><br><br><br>

# Mining

 - [Geth]()
 - It is done automatically on the `Truffle` local network provided for development.
 - It is done automatically on the `Hardhat` local network provided for development.

<hr>

###### [Go to Top : `Getting Started`](#Getting-Started)


<br><br><br><br><br>

# Account

 - [RPC]()
 - [Geth]()
 - [Metamask]()
 - [Web3.js]()
 - [Ethers.js]()
 - Wallets and coins are automatically generated on the `Truffle` local network provided for development.
 - Wallets and coins are automatically generated on the `Hardhat` local network provided for development.

<hr>

###### [Go to Top : `Getting Started`](#Getting-Started)

<br><br><br><br><br>

# Sending ETH

 - [RPC]()
 - [Geth]()
 - [Metamask]()
 - [Web3.js]()
 - [Ethers.js]()

<hr>

###### [Go to Top : `Getting Started`](#Getting-Started)

<br><br><br><br><br>

# Compiling Smart Contract

 - [solc]()
 - [Truffle]()
 - [Hardhat]()

<hr>

###### [Go to Top : `Getting Started`](#Getting-Started)

<br><br><br><br><br>

# Deploying Smart Contract

 - [RPC]()
 - [Truffle]()
 - [Hardhat]()
 - [Web3.js]()
 - [Ethers.js]()

<hr>

###### [Go to Top : `Getting Started`](#Getting-Started)

<br><br><br><br><br>


# Using Smart Contract

 - [RPC]()
 - [Web3.js]()
 - [Ethers.js]()

<hr>

###### [Go to Top : `Getting Started`](#Getting-Started)

<br><br><br><br><br>

# End of tutorial

We hope this tutorial will help developers who first started Ethereum development.

[Go to Home](../../README.md)