### Gather the needed details

For this tutorial, we're going to connect to a smart contract called Greeter that's included with a new [Hardhat](https://hardhat.org/)project. It's been deployed to the Ropsten testnet at the address `0xE0282e76237B8eB19A5D08e1741b8b3e2691Dadd`, and you can find details about it on the EtherScan Ropsten block explorer (opens new window)by searching for that address, which should take you to the address detail view (opens new window).

Ethers has a Contract API (opens new window)that abstracts over the details of the blockchain and lets us interact with smart contracts as if they were regular JavaScript objects named Contract.

To wire up a JavaScript object to a deployed smart contract with Ethers, we need two things: the address of the contract, and its Application Binary Interface (ABI).

To get the ABI for a contract, look at the contract source code on the blockchain explorer. Here is [the source code for Greeter](https://ropsten.etherscan.io/address/0xE0282e76237B8eB19A5D08e1741b8b3e2691Dadd#code). You can find the ABI, which is expressed as a condensed chunk of JSON code, by scrolling down

Used Live-server to run the HTML code.

Website followed - [NFTschool](https://nftschool.dev/tutorial/first-steps/#building-our-app)
