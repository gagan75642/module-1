### ERC20 Token and Vault Contract

This repository contains two Solidity smart contracts: ERC20 and Vault. These contracts are designed to facilitate token management on the Ethereum blockchain.

#### ERC20 Contract

The ERC20 contract is a standard implementation of the ERC20 token interface. It includes functionalities such as:

- **Total Supply**: Tracks the total supply of the token.
- **Balances**: Maps addresses to their token balances.
- **Allowances**: Maps owner addresses to spender addresses with corresponding allowed amounts.
- **Name, Symbol, and Decimals**: Metadata about the token.
- **Transfer**: Allows users to transfer tokens to other addresses.
- **Approve**: Allows owners to approve spenders to transfer tokens on their behalf.
- **TransferFrom**: Allows approved spenders to transfer tokens from the owner's address to another address.
- **Mint**: Allows the creation of new tokens.
- **Burn**: Allows the destruction of tokens.

#### Vault Contract

The Vault contract provides a secure way to manage ERC20 tokens. Key features include:

- **Deposit**: Allows users to deposit tokens into the vault, receiving shares equivalent to their contribution.
- **Withdraw**: Allows users to withdraw tokens from the vault by burning shares equivalent to the desired amount.

#### How to Use

1. Deploy the ERC20 contract on the Ethereum blockchain.
2. Deploy the Vault contract, specifying the ERC20 token address in the constructor.
3. Interact with the contracts using Ethereum addresses to manage tokens, deposit, and withdraw funds securely.

