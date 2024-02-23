This repository hosts two Solidity smart contracts: ERC20 and Vault, designed to streamline token management on the Ethereum blockchain.

**ERC20 Contract:**
The ERC20 contract is a standard implementation of the ERC20 token interface, encompassing essential functionalities:

- **Total Supply:** Keeps track of the overall token supply.
- **Balances:** Associates addresses with their respective token balances.
- **Allowances:** Links owner addresses with spender addresses along with permitted transfer amounts.
- **Name, Symbol, and Decimals:** Provides metadata regarding the token.
- **Transfer:** Enables users to transfer tokens to other addresses.
- **Approve:** Allows owners to authorize spenders to transfer tokens on their behalf.
- **TransferFrom:** Permits approved spenders to transfer tokens from the owner's address to another address.
- **Mint:** Facilitates the creation of new tokens.
- **Burn:** Enables the destruction of tokens.

**Vault Contract:**
The Vault contract offers a secure mechanism for handling ERC20 tokens, featuring the following functionalities:

- **Deposit:** Empowers users to deposit tokens into the vault, acquiring shares equivalent to their contribution.
- **Withdraw:** Allows users to retrieve tokens from the vault by burning shares corresponding to the desired amount.
