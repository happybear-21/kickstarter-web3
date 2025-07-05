# Kickstarter Web3

A decentralized crowdfunding platform built on Ethereum blockchain using React and Solidity smart contracts. This project allows users to create and fund campaigns using cryptocurrency.

## Features

- **Create Campaigns**: Users can create crowdfunding campaigns with title, description, funding goal, deadline, and image
- **Fund Campaigns**: Support campaigns by donating ETH directly through the platform
- **Campaign Management**: View all campaigns, campaign details, and track funding progress
- **User Profiles**: Manage your created campaigns and donation history
- **Real-time Updates**: Live updates of campaign funding status and donations
- **Web3 Integration**: Seamless blockchain integration using ThirdWeb SDK

## Technology Stack

### Frontend
- **React 18** - Modern React with hooks
- **Vite** - Fast build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **React Router** - Client-side routing
- **Ethers.js** - Ethereum library for interacting with smart contracts

### Blockchain
- **Solidity** - Smart contract development
- **Hardhat** - Ethereum development environment
- **ThirdWeb** - Web3 development framework
- **Ethereum** - Blockchain platform

## Project Structure

```
kickstarter-web3/
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/         # Application pages
│   │   ├── context/       # React context for state management
│   │   ├── assets/        # Static assets and images
│   │   └── utils/         # Utility functions
│   └── package.json
├── web3/                   # Smart contract and blockchain code
│   ├── contracts/         # Solidity smart contracts
│   │   └── CrowdFunding.sol
│   └── package.json
└── README.md
```

## Smart Contract Features

The `CrowdFunding.sol` smart contract provides:

- **Campaign Creation**: Create new crowdfunding campaigns with metadata
- **Donation System**: Accept ETH donations for campaigns
- **Campaign Management**: Track campaign details, funding progress, and donors
- **Data Retrieval**: Get campaign lists and donation information

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- MetaMask wallet extension
- ThirdWeb account

## Usage

1. **Connect Wallet**: Click "Connect Wallet" to connect your MetaMask wallet
2. **Browse Campaigns**: View all available crowdfunding campaigns on the home page
3. **Create Campaign**: Click "Create Campaign" to start your own fundraising campaign
4. **Fund Campaigns**: Click on any campaign to view details and donate ETH
5. **Manage Profile**: View your created campaigns and donation history

## Configuration

- Update the contract address in `client/src/context/index.jsx` if you deploy your own smart contract
- Configure ThirdWeb settings in the client application
- Set up environment variables for production deployment


