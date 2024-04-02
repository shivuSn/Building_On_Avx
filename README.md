# Buyshoe smart contract 

The **Buyshoe** contract is a decentralized application (DApp) implemented on the Ethereum blockchain using the Solidity programming language. It allows users to purchase virtual shoes using a custom ERC20 token called ShoeCoin (SCC). Each shoe has a specific type (Party Wear, Sports Wear, Regular), and users can redeem their tokens for these shoes according to their preference.

## Features

- **Shoe Purchasing**: Users can redeem their ShoeCoin tokens to purchase virtual shoes of different types: Party Wear, Sports Wear, or Regular.
- **Token Management**: The contract allows for the minting and burning of ShoeCoin tokens. Token holders can also transfer their tokens to other addresses.
- **Ownership Control**: The contract is owned by an Ethereum address, allowing for control over token minting and administrative functions.

## Installation

To interact with the Buyshoe contract, you can deploy it on the Ethereum blockchain using tools like Remix IDE or Truffle Suite. Ensure you have the required dependencies installed, including OpenZeppelin contracts for ERC20 tokens.

## Usage

1. **Token Minting**: The contract owner can mint new ShoeCoin tokens using the `mintTokens` function.
2. **Token Burning**: Token holders can burn their ShoeCoin tokens using the `burnTokens` function.
3. **Shoe Redemption**: Users can redeem their ShoeCoin tokens for virtual shoes of their choice by calling the `RedeemShoe` function and specifying the type of shoe they want.
4. **Token Transfer**: Token holders can transfer their ShoeCoin tokens to other addresses using the `transferShoeTokens` function.

## Security

- The contract implements access control mechanisms, ensuring that only authorized users can perform specific actions such as token minting.
- Input validation is performed to prevent invalid transactions and ensure the integrity of the contract's state.

## License

This project is licensed under the terms of the MIT license. See the `LICENSE` file for more information.

## Author 

Shivaraj

shivun12890@gmail.com
