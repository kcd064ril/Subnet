# Vault and ERC20 Contracts

## Overview

The Vault contract is a Solidity smart contract that acts as a vault for storing ERC20 tokens. Users can deposit tokens into the vault and receive shares in return, which represent their ownership of the deposited tokens. The shares can be redeemed for tokens at any time.

The ERC20 contract is a basic implementation of the ERC20 token standard. It provides functionalities for transferring tokens, approving token transfers, and minting/burning tokens.

## License

These smart contracts are released under the MIT License.

## Usage

### Vault Contract Details

- **Name**: Vault
- **Solidity Version**: ^0.8.17
- **Dependencies**: None

#### Functions

- **constructor**: Initializes the vault with the address of the ERC20 token contract.
- **deposit**: Allows users to deposit tokens into the vault and receive shares in return.
- **withdraw**: Allows users to redeem shares for tokens.

### ERC20 Contract Details

- **Name**: ERC20
- **Solidity Version**: ^0.8.17


#### Functions

- **transfer**: Allows users to transfer tokens to another address.
- **approve**: Allows users to approve another address to spend tokens on their behalf.
- **transferFrom**: Allows approved addresses to transfer tokens on behalf of the token owner.
- **mint**: Allows the contract owner to mint new tokens.
- **burn**: Allows the token owner to burn their own tokens.

## Installation

1. Copy the contract code into Solidity files (e.g., `Vault.sol` and `ERC20.sol`).
2. Compile the contracts using a Solidity compiler (e.g., solc).
3. Deploy the compiled contracts to a supported blockchain network (e.g., Ethereum).

## Testing

Unit tests for the Vault and ERC20 contracts can be written using Solidity testing frameworks like Truffle or Hardhat. Test cases should cover various scenarios for depositing, withdrawing, transferring, and minting/burning tokens.

## Support

If you have any questions, issues, or feature requests, please open an issue on the GitHub repository.

## Acknowledgements

These contracts provide basic functionalities for managing and transferring ERC20 tokens on the Ethereum blockchain.


