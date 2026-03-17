# StellarFeedback Frontend

**Decentralized Product Feedback Platform – Verified on Stellar**

Product feedback, verified on-chain. Real reviews from real users. No bots, no fake ratings. Just honest feedback stored permanently on the Stellar blockchain using Soroban smart contracts.

Every review is immutable, earns the reviewer reputation points, and mints a unique NFT as proof of contribution.

Built as an open-source frontend companion to the [StellarFeedback Contract](https://github.com/your-org/stellarfeedback-contract) repo.


## Features

- **Blockchain Verified Reviews** — Every submission is recorded immutably on Stellar testnet/mainnet via Soroban.
- **Reputation System** — Quality reviewers build on-chain reputation scores.
- **NFT Proof** — Mint an NFT for each review you submit — own your contributions forever.
- **Wallet Integration** — Connect via Freighter (Stellar's popular wallet extension).
- **Clean UI** — Inspired by modern decentralized apps, with product listings, submission forms, and personal dashboard.

## Tech Stack

- **Framework**: Next.js 14+ (App Router)
- **Styling**: Tailwind CSS
- **Stellar Integration**:
  - `@stellar/stellar-sdk` (v14.6.1+) — for Soroban RPC, transaction building, and contract interaction
  - `@stellar/freighter-api` — for wallet connection and signing
- **Icons**: lucide-react
- **Deployment**: Vercel

## Prerequisites

- Node.js ≥ 18
- Freighter wallet extension (for testing submissions)
- Access to the deployed Soroban contract ID (from the contract repo)

## Quick Start

1. Clone the repo:
   ```bash
   git clone https://github.com/your-org/stellarfeedback-frontend.git
   cd stellarfeedback-frontend
   npm install
   npm run dev