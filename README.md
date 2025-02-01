# Non-Custodial ETH Staking with ERC20 & ERC721 Tokens | Vault-based Staking System

## Overview

This **open-source** project allows users to stake **ERC20 tokens** (fungible tokens such as stablecoins or governance tokens) and **ERC721 tokens** (NFTs) in a **non-custodial** manner using a vault-based staking mechanism. Users can earn rewards while retaining full control over their assets at all times, ensuring a secure, decentralized staking experience on the Ethereum blockchain.

### Key Features:
- **Non-Custodial Staking**: Users maintain full ownership of their assets during the entire staking process.
- **ERC20 & ERC721 Support**: Stake both fungible ERC20 tokens and unique ERC721 NFTs in one unified staking platform.
- **Vault-based System**: Tokens and NFTs are locked in a vault during staking, ensuring transparency and immutability.
- **Earning Rewards**: Stakeholders earn rewards based on the value and duration of their staked assets.
- **Secure and Decentralized**: Built on **Ethereum** with **Solidity** smart contracts, providing a transparent and secure staking solution.

---

## How It Works

1. **Stake ERC721 Tokens**: Users can deposit ERC20 tokens (like stablecoins, utility tokens, etc.) or ERC721 NFTs into the vault.
2. **Earn Staking Rewards**: Users earn rewards based on the amount of tokens or NFTs they stake and the duration of their staking.
3. **Claim Rewards**: Rewards can be claimed by users at any time.
4. **Withdraw Assets**: Users can withdraw their staked tokens or NFTs from the vault at any point, retaining full control over their assets.
5. **Vault Mechanism**: The staking logic is secured in a vault contract, ensuring that users' assets are safely locked while generating rewards.

---

## Features

- **Multi-Token Support**: Allows staking of both **ERC20** fungible tokens and **ERC721** NFTs for diverse staking options.
- **User-Friendly Interface**: Easy-to-use platform to stake tokens and claim rewards.
- **Flexible Reward Distribution**: Rewards can be distributed periodically, providing passive income for stakers.
- **Secure Withdrawals**: Tokens and NFTs can be withdrawn at any time without restrictions.
- **Upgradeable**: Easily upgradeable smart contracts to accommodate future features.

---

## Technologies Used
- **Solidity**: Smart contracts for the staking mechanism and vault logic.
- **Ethereum Blockchain**: The platform's core network for decentralized transactions.
- **ERC20**: Standard for fungible tokens used in staking rewards.
- **ERC721**: Standard for non-fungible tokens (NFTs) that can be staked.
- **Web3.js / Ethers.js**: Libraries for interacting with Ethereum from the frontend.
- **Truffle / Hardhat**: Frameworks for deploying and testing smart contracts.

---

## Installation

### Requirements
- **Node.js** (for frontend interaction)
- **Metamask** or another Ethereum wallet
- **Solidity**: Ethereum smart contracts deployed to the network

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/rhettbu/eth-nft-staking.git
   cd eth-nft-staking
