# Inbox-SoliditySmartContract
This repository contains a Solidity smart contract developed for a simple Inbox project. 

## Features
- Uses the `truffle-hdwallet-provider` to sign transactions and deploy the contract.
- Utilizes the `web3` library to interact with the Ethereum blockchain.
- Deploys a sample smart contract named `Inbox` with an initial message "Hi there!".

## Prerequisites
- Node.js and npm installed
- An Ethereum account mnemonic
- Infura API key

## Instructions

1. Replace `"12-word mnemonic"` with your actual Ethereum account mnemonic.
2. Replace `"https://sepolia.infura.io/v3/INFURA_API_KEY"` with your Infura API key.

## Usage

1. Clone the repository and navigate to the project directory:
    ```bash
    git clone https://github.com/yourusername/Inbox-SoliditySmartContract.git
    cd Inbox-SoliditySmartContract
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Run the deployment script:
    ```bash
    node deploy.js
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

