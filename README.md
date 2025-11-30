Cosmic Astra Verse

A decentralized application (dApp) built with React + TypeScript + Vite, integrating MetaMask, Ethers.js, and custom smart contracts for token interactions within the Astra ecosystem.

🚀 Features
🔗 Web3 & Wallet Integration

Seamless MetaMask connection

Persistent wallet state

Real-time account & network detection

Optimized for fast connection and low CPU usage

🪙 Astra Token Features

Import Astra token into MetaMask using the contract address

Transfer, mint, or interact with the token (based on your smart-contract logic)

Live balance updates

🎯 UI & UX

Modern, responsive interface

Built with React, TypeScript, Vite

Styled using shadcn/ui, Radix UI components, and Tailwind CSS

📦 Tech Stack
Technology	Purpose
React + TypeScript	Frontend framework
Vite	Lightning-fast build tool
Ethers.js	Blockchain interactions
MetaMask	Wallet connection
Tailwind CSS	UI styling
shadcn/ui + Radix	Component system
🛠️ Installation
1. Clone the repository
git clone <your-repo-url>
cd cosmic-astra-verse

2. Install dependencies
npm install

3. Start development server
npm run dev

4. Build for production
npm run build

5. Preview build
npm run preview

🔧 Environment Setup

Create a .env file with:

VITE_CONTRACT_ADDRESS=<Your Astra Token Address>
VITE_RPC_URL=<Your RPC Provider URL>


You can use any RPC provider: Infura, Alchemy, Ankr, etc.

🧪 Adding Astra Token to MetaMask

Open MetaMask

Go to Import Tokens

Paste:

Token Contract Address: <your token address>

Symbol: ASTRA

Decimals: 18 (or your contract’s configured decimals)

This will make Astra balance visible in your wallet.

⚡ Performance Optimizations Included

The project is written to ensure:

No repeated wallet reconnection

No polling loops that cause high CPU usage

Provider and contract instances are reused

MetaMask connects instantly

Efficient rendering of blockchain data

📂 Project Structure
cosmic-astra-verse/
│── src/
│   ├── components/
│   ├── contracts/
│   ├── hooks/
│   ├── pages/
│   ├── lib/
│   └── main.tsx
│
├── public/
├── package.json
└── vite.config.ts

🛡️ Smart Contract Notes

This project includes:

ABI files inside src/contracts/

Clean contract loader for Ethers.js

Integration ready for any EVM-compatible chain

💬 Support

If you need help integrating your contract, improving performance, or adding new features, you can ask for assistance anytime.

📄 License

This project is released under the MIT License.