# DEX Coin Factory 2 Smart Contract

This is the DEX Coin Factory 2 Smart Contract, demonstrating a decentralized approach to creating and managing digital tokens, specifically DEX Coins. The smart contract is built on the Polygon PoS (Proof of Stake) network and utilizes the Mumbai testnet for development and testing.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Functions](#functions)
- [Proof of Concept: Value and Utility](#proof-of-concept-value-and-utility)
- [Setting the Factory Owner](#setting-the-factory-owner)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The DEX Coin Factory 2 Smart Contract showcases a decentralized approach to creating and managing digital tokens, specifically DEX Coins. It is built on the Polygon PoS (Proof of Stake) network, utilizing the Mumbai testnet for development and testing. The smart contract embodies the principle that the value of digital assets, such as tokens, is primarily derived from their utility and functionality within a specific ecosystem.

## Features

- Minting of DEX Coins.
- Royalties mechanism for token holders.
- Controllable inflation to manage token supply.
- Address blocking functionality.
- Token transfer and approval system.

## Usage

To utilize this smart contract, deploy it on the Polygon PoS network, using the Mumbai testnet for development and testing. Interact with the defined functions and customize parameters to create and manage DEX Coins within your decentralized exchange.

## Functions

The smart contract provides several functions for interacting with the DEX Coins, managing addresses, and controlling inflation. Key functions include:
- `transfer`: Transfer DEX Coins to another address.
- `mint`: Mint new DEX Coins to an account.
- `claim`: Claim DEX Coins at specific intervals.
- `setDexCoinPrice`: Set the price of DEX Coin in terms of a given value token, e.g., 1 USDC.

For a complete list of functions and their usage, refer to the smart contract source code.

## Proof of Concept: Value and Utility

The DEX Coin Factory 2 Smart Contract demonstrates the concept that the value of digital assets like DEX Coins is primarily derived from their utility and functionality within a specific ecosystem. In this contract, the utility of DEX Coins is associated with their use within a decentralized exchange. Users can transfer, claim, and trade DEX Coins, underlining their value within the DEX ecosystem. This value is independent of traditional asset backing and is driven by the utility provided within the decentralized exchange.

## Setting the Factory Owner

To set the factory owner, use the `setFactoryOwner` function, providing the new owner's address as an argument.

## Contributing

We welcome contributions! Fork the repository, make your changes, and submit a pull request. Please follow the contribution guidelines provided in the repository.

## License

This smart contract is available under the [GNU General Public License (GPL)](LICENSE).