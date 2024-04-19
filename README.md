
# ERC20 and Vault README

## Overview

This repository contains the implementation of two Ethereum smart contracts: ERC20 token contract and a Vault contract. ERC20 is a widely adopted standard for creating fungible tokens on the Ethereum blockchain, while the Vault contract is designed to securely store and manage these tokens.

## ERC20 Token Contract

The ERC20 token contract defines a standard interface for fungible tokens on the Ethereum blockchain. It includes functions such as `transfer`, `approve`, and `transferFrom` to facilitate token transfers between addresses. This contract also includes events to notify external parties about token transfers.

### Usage

1. **Deployment**: Deploy the ERC20 token contract to the Ethereum blockchain using a compatible Ethereum development framework like Truffle or Hardhat.

2. **Interacting with the Contract**: Once deployed, interact with the ERC20 token contract using Ethereum wallets or through other smart contracts. Users can transfer tokens, approve token allowances, and check balances using the provided functions.

## Vault Contract

The Vault contract is designed to securely store and manage ERC20 tokens. It implements additional features such as locking tokens for a specified period, withdrawing tokens after the lock period expires, and allowing only authorized addresses to withdraw tokens.

### Usage

1. **Deployment**: Deploy the Vault contract to the Ethereum blockchain along with the ERC20 token contract address.

2. **Authorization**: Authorize addresses that are allowed to deposit and withdraw tokens from the Vault contract.

3. **Deposit**: Deposit ERC20 tokens into the Vault contract, specifying the lock period if applicable.

4. **Withdrawal**: Withdraw tokens from the Vault contract after the lock period expires or if authorized.


## License

This project is licensed under the [MIT License](LICENSE).
