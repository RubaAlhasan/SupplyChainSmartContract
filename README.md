# Supply Chain Smart Contract

## Overview

This repository contains a smart contract designed to manage and track supply chain processes using blockchain technology. The contract is written in Solidity and provides a decentralized and secure way to track the journey of products from manufacturers to end consumers.

## Features

- **Product Registration**: Allows manufacturers to register new products with unique identifiers.
- **Ownership Transfer**: Facilitates the transfer of ownership of products between different parties (manufacturers, suppliers, retailers, and consumers).
- **Product Tracking**: Enables tracking of the product's journey through the supply chain.
- **Tamper-Proof Records**: Ensures that all transactions and records are immutable and verifiable on the blockchain.
- **Transparency**: Provides transparent access to product history for all stakeholders involved in the supply chain.

## Technology Stack

- **Solidity**: The smart contract is developed using Solidity, the most popular programming language for writing Ethereum smart contracts.
- **Truffle Framework**: Used for smart contract development, testing, and deployment.
- **Ganache**: A personal Ethereum blockchain used for development and testing.
- **MetaMask**: For interacting with the smart contract through a web browser.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RubaAlhasan/SupplyChainSmartContract.git
   cd SupplyChainSmartContract
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Compile the smart contract:**
   ```bash
   truffle compile
   ```

4. **Migrate the smart contract to the local blockchain:**
   ```bash
   truffle migrate
   ```

5. **Run tests:**
   ```bash
   truffle test
   ```

## Usage

1. **Start Ganache:**
   ```bash
   ganache-cli
   ```

2. **Deploy the smart contract:**
   ```bash
   truffle migrate
   ```

3. **Interact with the smart contract:**
   Use MetaMask to interact with the deployed smart contract through a web interface or Truffle console.

## Contributing

We welcome contributions to improve the supply chain smart contract. Please fork the repository and create a pull request with your changes. Ensure that your code follows the existing coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any questions or inquiries, please contact eng.rubaal7asan@gmail.com .
