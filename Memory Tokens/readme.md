A blockchain based memory game wherein the user attempts to find matches by clicking tiles, each tile represents a [Non-Fungible Token](https://en.wikipedia.org/wiki/Non-fungible_token). A match is found when two tiles show the same icon. As soon as a match is found it is kept forever on the blockchain.

For every correct match the user is provided tokens which are cryptocurrencies and can be transfered over the exchange.

# Technical Stack

1. **Frontend**: game logic implented on a client side web application written in **React**
2. **Backend**: the **blockchain** serves as a backend database

# Architecture

1. A web browsr will talk to a client side website
2. The game logic is written on the client side website
3. Tokens are created and saved on the blockchain
4. Business logic of the blockchain component is written on an Ethereum smart contract
