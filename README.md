<div align="center">
  <h1>👋 Hello, I'm Nikhil</h1>
  <h3>FullStack Blockchain Developer</h3>
</div>

## 🛠️ Tech Stack

### Frontend Development
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

### Blockchain Development
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=flat-square&logo=rust&logoColor=white)
![Solana](https://img.shields.io/badge/solana-%236C2DC7.svg?style=flat-square&logo=solana&logoColor=white)
![Anchor](https://img.shields.io/badge/Anchor-0077FF?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNzIiIGhlaWdodD0iNzIiIHZpZXdCb3g9IjAgMCA3MiA3MiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48Y2lyY2xlIGN4PSIzNiIgY3k9IjM2IiByPSIzNiIgZmlsbD0iI0ZGRiIvPjxwYXRoIGQ9Ik0zNiAxNUM0Ni41MDQgMTUgNTUgMjMuNDk2IDU1IDM0QzU1IDQ0LjUwNCA0Ni41MDQgNTMgMzYgNTNDMjUuNDk2IDUzIDE3IDQ0LjUwNCAxNyAzNEMxNyAyMy40OTYgMjUuNDk2IDE1IDM2IDE1Wk0zNiAxOUMyNy4xNjIgMTkgMjEgMjUuMTYyIDIxIDM0QzIxIDQyLjgzOCAyNy4xNjIgNDkgMzYgNDlDNDUuODM4IDQ5IDUyIDQyLjgzOCA1MiAzNEM1MiAyNS4xNjIgNDUuODM4IDE5IDM2IDE5WiIgZmlsbD0iIzAwN0ZGRiIvPjwvc3ZnPg==)

### Development Tools
- Foundry
- OpenZeppelin
- Wagmi
- Ethers.js
- Next js
- Typescript

## 🌟 Featured Projects

### 🌉 Cross-Chain Bridge
A decentralized marketplace that enables seamless trading of NFTs across multiple blockchain networks.

**Key Features:**
- Cross-chain NFT transfers and trading
- Multi-wallet support
- Automated price conversion
- Gas fee optimization
- Real-time transaction tracking

**Tech Stack:**
- Smart Contracts: Solidity, OpenZeppelin
- Frontend: Next.js, TypeScript, Tailwind CSS
- Blockchain Integration: Wagmi, Ethers.js
- Testing: Foundry

🔗 [Live Demo](https://blockchain-bridge-kappa.vercel.app/)
📱 [GitHub Repo](https://github.com/swaploard/zk-marketplace)

### 🎨 NFT Marketplace
A decentralized NFT marketplace enabling users to mint, buy, sell, and trade unique digital assets.

**Key Features:**
- NFT Minting with Metadata Support
- Buy/Sell NFTs with Multiple Payment Options
- Advanced Search & Filter System
- Real-time Price Updates
- Collection Management
- Royalty System for Creators
- Auction Mechanism

**Tech Stack:**
- Smart Contracts: Solidity, OpenZeppelin (ERC1155)
- Frontend: React, Next.js, TypeScript, Tailwind CSS
- Web3 Integration: Wagmi, Ethers.js
- Testing & Deployment: Foundry
- IPFS for Metadata Storage

🔗 [Live Demo](https://zk-marketplace.vercel.app/)
📱 [GitHub Repo](https://github.com/swaploard/Blockchain-bridge/tree/main)

**Contract Features:**
- Secure escrow system
- Gas-optimized transactions
- Multi-token support
- Emergency pause functionality

## 🏦 LSD-Collateralized Stablecoin Borrowing App

A decentralized protocol that lets users deposit LSD tokens like stETH, rETH, and bETH to borrow DAI or USDC on optimized terms.

Real-time Data Streaming: Live blockchain data ingestion via Yellowstone gRPC

* LSD token collateral support (stETH, rETH, bETH)
* Real-time health factor tracking to avoid liquidation
* Borrow stablecoins (DAI or USDC) while holding ETH exposure
* Dynamic borrow limit based on live LSD-ETH prices and LTV ratios
* Safe withdrawal logic that respects debt and liquidation thresholds
* Liquidation engine to protect against undercollateralization
* Fully testable on Goerli or Holesky with mock LSD tokens
* Simulated price feed oracles for realistic testnet behavior

### 🧰 Tech Stack:

* **Smart Contracts**: Solidity, OpenZeppelin, mock Chainlink oracles
* **Frontend**: React, Next.js, TypeScript, Tailwind CSS
* **Web3 Integration**: Wagmi, Viem, Ethers.js
* **State Management**: Zustand
* **Testing & Deployment**: Foundry
* **Wallet Connection**: RainbowKit or ConnectKit
* **UI Components**: Shadcn/ui
* **Collateral Tokens (testnet)**: Sepolia versions of stETH, rETH, bETH
* **Optional Indexing**: The Graph (custom subgraph for vault & debt positions)
* **Dev Tools**: Etherscan APIs (testnet)

🔗 [Live Demo](https://liquid-staking-derivatives.vercel.app/)
📱 [GitHub Repo](https://github.com/swaploard/Liquid-Staking-Derivatives)

## 🔎📡 Solana Indexer

Solana indexer for historical and real-time data

* Real-time Data Streaming: Live blockchain data ingestion via Yellowstone gRPC
* Scalable Processing: Redis-based message queuing for reliable data processing
* High-Performance Storage: ScyllaDB for fast, distributed data storage
* DeFi Focus: Specialized subscriptions for DeFi-related transactions
* Type Safety: Comprehensive Rust type system with automatic serialization/deserialization
* Error Resilience: Robust error handling and logging throughout the pipeline

### 🧰 Tech Stack: 

* Rust, Redis server, Scylla DB, Yellowstone gRPC

## 🌊💸 Automated Market Maker (AMM)

Automated Market Maker (AMM) decentralized exchange (DEX) that uses liquidity pools to facilitate trading of digital assets, such as SOL. Users can deposit their Solana ecosystem tokens into these liquidity pools, enabling others to swap tokens without requiring a middleman or institutional intervention.

* Pool Initialization: Create new trading pairs between any two SPL tokens
* Liquidity Provision: Add liquidity to pools and receive LP tokens representing ownership share
* Token Swapping: Exchange tokens using the constant product AMM formula with automatic price calculation
* Liquidity Removal: Withdraw provided liquidity and earned trading fees by burning LP tokens
* Wallet Integration: Full Solana wallet support with transaction signing
* Real-time Updates: Interface updates with transaction confirmations and balance changes

### 🧰 Tech Stack:

* **Smart Contracts**: Solana, Anchor, SPL tokens.
* **Frontend**: React, Next.js, TypeScript, Tailwind CSS
* **Web3 Integration**: Next.js 15, solana/web3.js, coral-xyz/anchor, codama/renderers-js.
* **State Management**: tanstack/react-query

## 📫 Connect With Me
<div align="left">
  [Portfolio](https://portfolio-swaploards-projects.vercel.app/)
</div>
