# Blockchain-based Crowdfunding Platform

A decentralized crowdfunding platform built on blockchain technology, providing transparency, security, and trust for fundraisers and contributors.

## Features

- **Smart Contracts**: Ensures transparency and automates the funding process.
- **Decentralized**: Operates on a blockchain network, eliminating intermediaries.
- **Secure Transactions**: All transactions are encrypted and immutable.
- **Milestone-based Funding**: Funds are released incrementally based on predefined goals.
- **Contributor Voting**: Contributors can vote on the legitimacy of fund withdrawals.

## Tech Stack

- **Blockchain**: Ethereum (Solidity for smart contracts)
- **Frontend**: React.js
- **Backend**: Node.js, Express
- **Storage**: IPFS (for storing project details)
- **Wallet Integration**: MetaMask

## Installation

### Prerequisites
- Node.js and npm
- Truffle or Hardhat (for smart contract deployment)
- MetaMask browser extension
- Ganache (for local blockchain testing)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blockchain-crowdfunding.git
   cd blockchain-crowdfunding
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Compile and deploy smart contracts:
   ```bash
   truffle migrate --network development
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open the app in your browser at `http://localhost:3000`.
