# Lesson 1 - Introduction

## WALLETS & TRANSACTIONS

<b>* What is a wallet</b><br>
  Wallets are tools that create accounts, manage keys, and help users transact on the Celo network.
  It's important to be careful when choosing a wallet because they manage your secret account keys. You should only use reputable wallets that are    well maintained by organizations/people that you trust.
  
<b>* Finding wallet applications</b><br>
  There are currently some compatible wallets for Celo and other EVM compatible networks.<br>
  Metamask <a href="https://metamask.io/download/" target='_blank'>Click Here To Download Metamask</a><br>
  Trustwallet <a href="https://trustwallet.com/download" target='_blank'>Click Here To Download Trustwallet</a><br>

<b>* Connecting to Celo Alfajores testnet</b><br>
* <a href="http://alfajores.celoscan.io" rel="noreferrer">Celo's Alfajores Testnet Explorer</a>
* <a href="http://faucet.celo.org/alfajores" rel="noreferrer">Funding Your Wallet With Testnet Tokens</a>

## CELO, ETHEREUM & THE EVM (Ethereum Virtual Machine).

Ethereum is characterised by Turing completeness, as the EVM allows any computation to be performed if adequate resources are provided.
In simple terms  it is able to use its code base to perform virtually any task, as long as it has the correct instructions, enough time and processing power.

Ethereum started as a way to make a general-purpose blockchain that could be programmed for a variety of uses. But very quickly, Ethereum’s vision expanded to become a platform for programming DApps. DApps represent a broader perspective than smart contracts. A DApp is, at the very least, a smart contract and a web user interface. More broadly, a DApp is a web application that is built on top of open, decentralized, peer-to-peer infrastructure services.

In terms of programmability, Celo is similar to Ethereum. Both networks run the Ethereum Virtual Machine (EVM) to support smart contract functionality. This means that all programming languages, developer tooling and standards that target the EVM are relevant for both Celo and Ethereum.

A DApp is composed of at least:

* Smart contracts on a blockchain
* A web frontend user interface
  
## COMMON TERMS USED IN WEB3

* Blockchain (A database maintained by a distributed set of computers that do not share a trust relationship or common ownership. This arrangement     is referred to as decentralized. The content of a blockchain's database, or ledger, is authenticated using cryptographic techniques, preventing     its contents being edited or removed except according to a protocol's consensus mechanism)
  
* Smart Contract (Smart contracts are intructions embeded within code which are executed automatically by a computer program or a transaction          protocol. They make actions such as transferring cryptocurrencies or other tokens possible.)
  
* Transactions (Ethereum transactions are network messages that include (among other things) a sender, recipient, value, and data payload.)
  
* Data Structures (Ethereum’s state is stored locally on each node as a database, which contains the transactions and system state in a serialized     hashed data structure called a Merkle Patricia Tree.)
  
* Gas (A step of execution of a smart contract. Different operations consume different amounts of gas. To prevent denial-of-service attacks,           transactions specify a maximum gas which bounds the steps of execution before a transaction is reverted.)
  
* Blocks (The unit of update to the blockchain. A block consists of a header identifying its position in the chain and other metadata, and a body      that contains a list of transactions, and data structures that describe the new state after executing those transactions.)
  
* Consensus and finality (Ethereum’s consensus rules are defined in the reference specification, the Yellow Paper <a       href="https://ethereum.github.io/yellowpaper/paper.pdf" rel="noreferrer">(see Further Reading)</a>

* Private Key (A private key is a long, randomly generated number that serves as a cryptographic key in blockchain networks. It is used to sign         transactions and prove ownership of blockchain addresses and the assets within them.)
  
* Public Key (A public key is a cryptographic code used to facilitate secure transactions and interactions on a blockchain network. It is derived       from a private key and can be openly shared without compromising the security of the associated assets.)
  
* Node (A node is a computer that runs the Ethereum client software and is connected to other nodes on the network. These nodes work together to       verify transactions )
  
* JSON-RPC (JSON-RPC is used to communicate with the node through a Web3 provider, a software component that exposes a JSON-RPC API to the client     application)
  
* Web3 Provider (Providers take JSON-RPC requests and return the response.)

## INTRODUCTION TO SOLIDITY

Solidity is an EVM compatible language which supports a variety of data types that can be categorized mainly into value types and reference types. Other types such as function types and Tuples also exist.

<b>*Value Types</b>-
Boolean, Integers, Fixed Point Numbers, Address, Bytes, String, Enums.

<b>*Reference Types</b>-
Arrays, Structs, Mappings.

<b>*Other Types</b>-
Function types- Can be internal or external (e.g., function (uint) external returns (bool))<br>
Tuples- Group multiple values (e.g., (uint, string, address)).

<img src="https://github.com/eben619/Celo_Africa_Dao-Ghana_University_Tour/blob/main/function.avif" width="500px">



## HANDS ON CODING - Remix IDE
* REQUIREMENTS
  * Web Browser (Chrome)
  * Internet Connection
  * Web3 Wallet (MetaMask)
  
## REMIX INTERFACE (overview)
  

  <img src="https://github.com/eben619/Celo_Africa_Dao-Ghana_University_Tour/blob/main/Remix.png">

  The Remix interface can be broken down into 3 main sections-
* Sidebar
    * File explorer - This is where you can create, open, and save files.
    * Search - This is where you can search in your files.
    * Solidity Compiler - This is where you can compile your smart contract.
    * Deploy & Run Transactions - This is where you can deploy and interact with your smart contract.
    * Solidity Unit Testing - This is where you can run unit tests for your smart contract.

  * Editor - This is where you can write your smart contract code.
  * Terminal - This is where you will see outputs from different actions like compiling, deploying, and running tests.

### References for Remix

<https://remix-ide.readthedocs.io/en/latest/>

## Coding HelloWorld.sol contract with Solidity

* Solidity philosophy
* OOP basics of Solidity
* Contract Structure
  * SPDX License Identifier
  * Pragmas
  * Imports
  * Comments
  * Contract definition
* State Variables
* Contract Storage
* Constructor function
* Functions
* Return values

### Code Reference

```solidity
// SPDX-License-Identifier: GPL-3.0
pragma solidity >=0.7.0 <0.9.0;

contract HelloWorld {

    constructor() {}

    function helloWorld() public view returns (string memory) {}

}
```

### References for Solidity

<https://docs.soliditylang.org/en/latest/>

## Compiling and deploying

* Compilation parameters
  * Compiler version
  * EVM Version
  * Optimization
* Bytecode
* ABI
* Deployment parameters
  * Environment
  * Account
  * Gas
  * Contract
* Deploying
* Attaching

## Homework

* Create Github Issues with your questions about this lesson
* Read introduction and topics table from references

<!-- GETTING STARTED -->

## 🔭 Learning Solidity

📕 Read the docs: <https://docs.soliditylang.org>

- [Primitive Data Types](https://solidity-by-example.org/primitives/)
- [Mappings](https://solidity-by-example.org/mapping/)
- [Structs](https://solidity-by-example.org/structs/)
- [Modifiers](https://solidity-by-example.org/function-modifier/)
- [Events](https://solidity-by-example.org/events/)
- [Inheritance](https://solidity-by-example.org/inheritance/)
- [Payable](https://solidity-by-example.org/payable/)
- [Fallback](https://solidity-by-example.org/fallback/)

📧 Learn the [Solidity globals and units](https://solidity.readthedocs.io/en/v0.8.19/units-and-global-variables.html)

## Support

Join the Celo Ghana Developers Community

<img width="350px" src="https://github.com/eben619/Celo_Africa_Dao-Ghana_University_Tour/blob/main/CeloGhanaCommunity.jpg" align="center" alt="Celo Ghana WhatsApp"/>


## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- CONTACT -->
## Contact
Ernest Akakpo ( Community Manager [Ghana] )<br>
email: korkuernest@gmail.com

Ebenezer Agyenim-Boateng ( Blockchain Developer )<br>
email: ebenyawboateng72@gmail.com


<p align="right">(<a href="#top">back to top</a>)</p>
