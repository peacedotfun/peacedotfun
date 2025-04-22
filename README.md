# PeaceDotFun

A Solana MCP protocol implementation for creating SPL tokens with metadata and initial supply minting.

## Features
- Create SPL tokens on Solana with name, symbol, decimals, and metadata URI.
- Mint initial supply to a specified recipient.
- Secure MCP protocol with API key authentication.
- Docker support for easy deployment.
- CI/CD with GitHub Actions.

## Prerequisites
- [Node.js](https://nodejs.org/) 18+ (recommended: 20.x LTS)
- [Solana CLI](https://docs.solana.com/cli/install) (`solana --version`)
- A Solana wallet with SOL on Devnet (use `solana airdrop 2`)

## Setup
1. **Clone the repository**:
   ```bash
git clone https://github.com/your-username/peacedotfun.git
   cd peacedotfun
   
## Install dependencies:
npm install
## Configure environment:
cp .env.example .env
SOLANA_PRIVATE_KEY=your_solana_wallet_private_key_base58
SOLANA_RPC_URL=https://api.devnet.solana.com
MCP_PORT=8000
MCP_API_KEY=your_secure_api_key_123

## Start the MCP server:
npm run dev

## Run the test client:
Update src/client.ts with a valid recipient public key (e.g., solana address).
Run:
npm run test


