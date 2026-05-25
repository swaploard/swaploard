<div align="center">
  <h1>👋 Hello, I'm Nikhil</h1>
  <h3>FullStack Blockchain Developer</h3>
</div>

## Tech Stack

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

## Featured Projects

### Solana Staking Platform
A comprehensive staking platform built on the Solana blockchain, enabling users to stake SOL tokens, earn rewards, and manage staking positions through a modern web interface

**Key Features:**
- **Multiple Staking Pools** - Support for different staking pools with varying APY rates and terms
- **Real-time Data** - Indexed blockchain state for instant data queries
- **Position Management** - Track and manage active staking positions
- **Reward Tracking** - Monitor pending and claimed rewards
- **Responsive UI** - Desktop and mobile optimized interface
- **Wallet Integration** - Support for popular Solana wallets (Phantom, Solflare, etc.)
- **Exactly-Once Processing** - Guaranteed reliable transaction ingestion with recovery mechanisms

## Tech Stack

### Frontend
- **Framework**: Next.js 16+ with React 19+
- **UI Components**: Radix UI
- **Styling**: TailwindCSS with PostCSS
- **Web3**: Coral-xyz Anchor SDK, Solana Web3.js
- **Wallet Adapter**: Solana Wallet Adapter React

### Backend/Indexer
- **Language**: TypeScript with Node.js
- **Runtime**: tsx for development
- **Database**: PostgreSQL with Prisma ORM
- **Blockchain Interaction**: Coral-xyz Anchor, Solana Web3.js
- **Logging**: Pino logger
- **Architecture**: Background job-based with RPC failover and retry mechanisms

### Smart Contracts
- **Language**: Rust
- **Framework**: Anchor (Solana program development framework)
- **SPL Tokens**: Solana Program Library for token operations
- **Compilation**: Solana BPF (sBPF)

### Build & Tooling
- **Package Manager**: Yarn/pnpm
- **Rust Toolchain**: Managed via `rust-toolchain.toml`
- **Testing**: Mocha + TypeScript, ts-mocha
- **Code Quality**: Prettier for formatting

---

## NFT Marketplace
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

## LSD-Collateralized Stablecoin Borrowing App

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

### Tech Stack:

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

---

## Open Source & Protocol Contributions

I actively contribute to open-source blockchain infrastructure and Rust-based distributed systems, with a focus on protocol correctness, performance optimization, and developer tooling.

My contributions typically involve:

* Low-level protocol logic improvements
* State transition & execution layer enhancements
* Testing infrastructure & simulation environments
* zk-proof verification integrations
* Runtime / VM level optimizations
* Documentation for complex protocol components

---

### Public Contribution Activity

| Type                    | Link                                                                                                                                           |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
|  All Contributions    | [https://github.com/swaploard](https://github.com/swaploard)                                                                                   |
|  Pull Requests        | [https://github.com/pulls?q=is%3Apr+author%3Aswaploard](https://github.com/pulls?q=is%3Apr+author%3Aswaploard)                                 |
|  Issues & Discussions | [https://github.com/issues?q=is%3Aissue+author%3Aswaploard](https://github.com/issues?q=is%3Aissue+author%3Aswaploard)                         |
|  Code Reviews         | [https://github.com/search?q=reviewed-by%3Aswaploard&type=pullrequests](https://github.com/search?q=reviewed-by%3Aswaploard&type=pullrequests) |

---

### Contribution Domains

* Blockchain Execution Engines
* Zero-Knowledge Proof Systems
* Actor-based Runtime Architectures
* Storage & State Management
* WASM-based Cloud Components
* Cryptographic Verification Pipelines
* Developer Experience (DX) Tooling

---

### Engineering Focus

My open-source work reflects a strong inclination toward:

* Deterministic system design
* Fault-tolerant distributed architectures
* High-performance Rust services
* Protocol-level testing methodologies
* Modular runtime composition
* Secure contract execution environments

## Connect With Me
<div align="left">
  [Portfolio](https://portfolio-swaploards-projects.vercel.app/)
  [Calendly](https://calendly.com/nikhil876706/new-meeting)
</div>
