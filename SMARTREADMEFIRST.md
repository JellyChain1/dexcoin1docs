# DEXCoin1 README

## Introduction

Welcome to the README for DEXCoin1, a Solidity smart contract developed on the Ethereum blockchain. This README provides a detailed explanation of the contract's functionality, purpose, and usage.

**Disclaimer**: This README is for educational purposes only and should not be considered as financial or legal advice. Please consult with experts and conduct thorough due diligence before using or modifying this contract.

## Table of Contents

1. [Contract Overview](#contract-overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Maintenance and Management](#maintenance-and-management)
6. [Security Considerations](#security-considerations)
7. [License](#license)

## 1. Contract Overview

### Contract Name
- **Name:** DEX Coin 1

### Purpose
- DEXCoin1 is a decentralized smart contract designed to manage a cryptocurrency called "DEX Coin 1" (DEX1). It allows users to perform various operations such as transferring tokens, claiming rewards, buying and selling tokens, and more.

### Key Components
- The contract includes various mappings, state variables, and functions to enable its functionality.
- Some of the core components include:
  - Token management functions (transfer, mint, burn).
  - Royalty distribution and control.
  - Inflation management.
  - User address blacklisting.
  - Purchasing DEX Coins with USDC and vice versa.

## 2. Features

### Token Management
- Users can transfer DEX1 tokens to other addresses.
- Minting and burning functions allow for token creation and removal.

### Royalty System
- Users can claim royalty tokens at regular intervals.
- Royalty payments are minted based on a set rate and provided to eligible users.

### Inflation Control
- The contract monitors and controls inflation by periodically checking the total supply.
- Excess tokens are burned to maintain a predefined inflation cap.

### Address Management
- Contract owner can blacklist and unblock user addresses.

### DEX Coin Transactions
- Users can purchase DEX Coins with USDC.
- Users can sell DEX Coins to receive USDC.

## 3. Installation

To interact with the DEXCoin1 contract, you'll need an Metamask wallet and access to an Ethereum network (mainnet or testnet). You can use tools like Remix, Truffle, or web3.js to deploy and interact with smart contracts.

## 4. Usage

### Token Transfers
- Use the `transfer` function to send DEX1 tokens to other addresses.

### Claiming Royalties
- Users can claim royalty tokens using the `claim` function.

### Minting and Burning
- The contract owner can mint new tokens using `mintFreshDexCoins` and `mintFreshDEXCoinsToAccount`.
- Burning tokens can be done using the `burn` and `burnFrom` functions.

### DEX Coin Transactions
- Users can purchase DEX Coins with USDC using `buyDexCoinsWithUSDC`.
- Selling DEX Coins for USDC can be done with `buyUSDCWithDEXCoins`.

## 5. Maintenance and Management

### Pause and Resume Royalties
- The contract owner can pause and resume royalty distributions using the `pauseRoyalties` and `resumeRoyalties` functions.

### Pause and Resume Minting
- Minting can be paused and resumed by the contract owner with the `pauseMinting` and `resumeMinting` functions.

### Inflation Control
- The contract owner can manually control inflation with the `controlInflationIfNeeded` function.

### Address Blacklisting
- The contract owner can blacklist and unblacklist user addresses with `blockAddress` and `unblockAddress`.

### Emergency Contract Disable
- The contract owner has the ability to disable the contract using the `emergencyKill` function.

## 6. Security Considerations

- Carefully manage and protect the contract owner's private key as it has significant control over the contract.
- Review and understand the contract's code thoroughly, and consider performing security audits before deploying it to a live network.
- Ensure the contract is deployed on a secure and reputable Ethereum network.
- Be cautious when blacklisting user addresses to avoid potential disputes.

## 7. License

This contract is released under the GNU General Public License (GNU GPL). SPDX-License-Identifier: GNU

Please refer to the contract's source code for detailed licensing information.

---

**Note:** This README provides an overview of the DEXCoin1 contract's functionality and usage. It is crucial to thoroughly understand the contract's code, conduct testing, and consider security best practices before deploying it to a production environment.