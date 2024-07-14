# Lesson 1 - Introduction

## Wallets and transactions

<b>* What is a wallet</b><br>
  Wallets are tools that create accounts, manage keys, and help users transact on the Celo network.
  It's important to be careful when choosing a wallet because they manage your secret account keys. You should only use reputable wallets that are    well maintained by organizations/people that you trust.
  
<b>* Finding wallet applications</b><br>
  There are currently some compatible wallets for Celo and other EVM compatible networks.<br>
  *Metamask <a href="https://metamask.io/download/" target='_blank'>Click Here To Download Metamask</a><br>
  *Trustwallet <a href="https://trustwallet.com/download" target='_blank'>Click Here To Download Trustwallet</a><br>

<b>* Connecting to Celo Alfajores testnet</b><br>
* <a href="http://alfajores.celoscan.io" rel="noreferrer">Celo's Alfajores Testnet Explorer</a>
* <a href="http://faucet.celo.org/alfajores" rel="noreferrer">Funding Your Wallet With Testnet Tokens</a>

## ETHEREUM & THE EVM (Ethereum Virtual Machine)

* Transactions (Ethereum transactions are network messages that include (among other things) a sender, recipient, value, and data payload.)
* Data Structures (Ethereum’s state is stored locally on each node as a database (usually Google’s LevelDB), which contains the transactions and       system state in a serialized hashed data structure called a Merkle Patricia Tree.)
* Gas 
* Blocks
* Consensus and finality (Ethereum’s consensus rules are defined in the reference specification, the Yellow Paper <a       href="https://ethereum.github.io/yellowpaper/paper.pdf" rel="noreferrer">(see Further Reading)</a> .
* Deterministic
* State changes
* The EVM
* Accounts

## Trying it out

* Using Uniswap as an example
* What is a dApp
* Swap transaction example

## Contract interaction: Token Swap

* What is a state change inside a smart contract operation

## Hands on coding - Remix

* Remix interface (overview)

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
