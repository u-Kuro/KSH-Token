# Token Creation Smart Contract

## Objective

The objective of this project is to create a smart contract that allows the creation of a custom token on a local HardHat network. The contract owner can mint tokens to a specified address, and users can burn and transfer tokens.

## Getting Started

To get started with the project, follow these steps:

1. Install HardHat and the necessary dependencies.
2. Configure the `hardhat.config.js` file.
3. Expose hardhat to localhost `npx hardhat node`.
4. Run the `npx hardhat run --network localhost deploy.mjs` script to deploy the smart contract.
4. Interact with the deployed contract using Remix or other tools.

## Smart Contract Overview

The smart contract, `Token.sol`, is an ERC20 token contract that inherits from the OpenZeppelin ERC20 contract and the Ownable contract. It provides the following functionalities:

- Token Initialization: The contract initializes the token with the name "Kanshi" and symbol "KSH".
- Token Minting: The contract owner can mint new tokens to a specified address using the `mint` function.
- Token Burning: Users can burn their tokens using the `burn` function.
- Token Transfer: Users can transfer tokens to other addresses using standard ERC20 transfer functions.

## Deployment

To deploy the smart contract to the local HardHat network, execute the `deploy.js` script. The deployed contract address will be logged to the console.