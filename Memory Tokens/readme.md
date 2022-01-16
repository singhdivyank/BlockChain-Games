A blockchain based memory game wherein the user attempts to find matches by clicking tiles, each tile represents a [Non-Fungible Token](https://en.wikipedia.org/wiki/Non-fungible_token). A match is found when two tiles show the same icon. As soon as a match is found it is kept forever on the blockchain.

For every correct match the user is provided tokens which are cryptocurrencies and can be transfered over the exchange.

# Technical Stack

1. **Frontend**: game logic implented on a client side web application written in **React**
2. **Backend**: the **blockchain** serves as a backend database

**The development standards are in accordance with [ERC721](http://erc721.org/)**

# Architecture

1. A web browsr will talk to a client side website
2. The game logic is written on the client side website
3. Tokens are created and saved on the blockchain
4. Business logic of the blockchain component is written on an Ethereum smart contract

# Requirements

1. **Node.js**: install all the dependencies and interacts with the client side application
2. **[Truffle](https://trufflesuite.com/)**: a framework used for writing, testing Ethereum smart contracts and deploying them on a blockchain. For installation- <code> npm install --g truffle@5.1.39 </code>
3. **Ganache**: a personal blockchain for Ethereum development that can be used to deploy contracts, develop the applications and run tests. Available as both a desktop application and command line interface
