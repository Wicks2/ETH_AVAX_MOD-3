# MyToken Solidity Contract

This is a simple Solidity contract named `MyToken` that implements a basic ERC20 token with additional functionalities. The contract is deployed on the Ethereum blockchain and is intended to be used as a sample or starting point for building more complex tokens and projects.

## Features

1. **Name:** Abhay Token
2. **Symbol:** ABH
3. **Decimals:** 18
4. **Total Supply:** 1,000,000 ABH

## Functionality

The `MyToken` contract extends the OpenZeppelin `ERC20` and `Ownable` contracts. It includes the following functions:

1. **Constructor:** Initializes the token with the name "Abhay" and symbol "ABH". It also mints 1,000,000 ABH tokens to the contract deployer.

2. **Mint:** Allows the contract owner to mint new ABH tokens and assign them to a specified address. Only the contract owner can call this function.

3. **Burn:** Allows any token holder to burn a specified amount of their ABH tokens, reducing the total supply. This function can be used to destroy tokens irreversibly.

4. **Approve and Transfer:** Approves a specified amount of ABH tokens to be spent by the `spender` and then transfers the same amount of tokens from the caller's account to the `spender`. Returns `true` upon successful approval and transfer.

## Usage

To deploy and interact with this contract, you can use Remix IDE or other Ethereum development tools. Make sure to follow best practices for security, testing, and auditing when deploying this contract to a production environment.

## License

This contract is released under the MIT License. You can find the full license text in the SPDX-License-Identifier comment at the beginning of the Solidity file.

## Credits

This contract uses the OpenZeppelin library to implement ERC20 functionality and access control through the Ownable contract.
