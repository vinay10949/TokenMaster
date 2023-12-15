# Tokenmaster

## Overview

Tokenmaster is a decentralized application (dApp) that facilitates token creation, management, and interaction through smart contracts on the Ethereum blockchain.

## Technology Stack & Tools

Tokenmaster is built using various technologies and tools:

- **Solidity:** Used for writing smart contracts and associated tests.
- **Javascript:** Utilized for developing the React-based frontend and testing.
- **Hardhat:** Primary development framework for smart contract development, testing, and deployment.
- **Ethers.js:** Facilitates interaction with the Ethereum blockchain.
- **React.js:** Frontend framework for creating an intuitive user interface.
- **MetaMask:** Enables users to interact securely with Ethereum-based dApps.

## Requirements For Initial Setup

Ensure the following prerequisites are installed:

- **NodeJS:** Install NodeJS (preferably the LTS version).
- **MetaMask:** Install the MetaMask browser extension.

## Getting Started

Follow these steps to set up Tokenmaster locally:

### 1. Clone/Download the Repository

Clone the Tokenmaster repository or download the source files.

### 2. Install Dependencies

Run the following command to install project dependencies:

```bash
$ npm install
```

### 3. Run Tests

Execute the provided tests to ensure codebase integrity:

```bash
$ npx hardhat test
```

### 4. Start Hardhat Node

Initiate a local blockchain network with Hardhat:

```bash
$ npx hardhat node
```

### 5. Deploy Contracts

Deploy smart contracts to your local network using the deployment script:

```bash
$ npx hardhat run ./scripts/deploy.js --network localhost
```

### 6. Start Frontend

Launch the Tokenmaster frontend:

```bash
$ npm run start
```

## Usage

Access the Tokenmaster application through your browser. Ensure MetaMask is connected to the local network to interact with the dApp. Manage tokens, create new ones, and explore the functionalities provided by Tokenmaster.