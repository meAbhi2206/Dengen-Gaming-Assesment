# Project Title

DegenToken - ERC20 Token for Degen Gaming

## Description

DegenToken is an ERC20 token contract designed for Degen Gaming. It provides functionalities such as minting new tokens, transferring tokens, redeeming tokens for in-game items, checking token balances, and burning tokens. The contract is built using Solidity and leverages the OpenZeppelin library for standard ERC20 functionality and security features.

## Getting Started

### Installing

To use the DegenToken contract, you need to follow these steps:

1. Clone the repository to your local machine using the following command:

   ```
   git clone https://github.com/your-username/DegenToken.git
   ```

2. Install the required dependencies by running the following command:

   ```
   npm install
   ```

### Executing Program

To deploy and interact with the DegenToken contract, you need to:

1. Compile the contract using the following command:

   ```
   npx hardhat compile
   ```

2. Deploy the contract to the Avalanche network by running:

   ```
   npx hardhat run scripts/deploy.js --network avalanche
   ```

   Note: Make sure to configure your network settings in the `hardhat.config.js` file.

3. Once the contract is deployed, you can use the provided functions to mint new tokens, transfer tokens, redeem tokens for in-game items, check token balances, and burn tokens.

## Authors

- Abhishek Ranjan

## License

This project is licensed under the [MIT License](LICENSE.md).
