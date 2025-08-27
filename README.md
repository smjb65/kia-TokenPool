⚡ Kia TokenPool

A simple decentralized exchange (DEX) simulator where you can deploy your own ERC-20 tokens on the Sepolia Testnet, list them in a token table, and experiment with trading-like features.

https://kia-token-pool-psi.vercel.app/

✨ Features

🔗 Connect with MetaMask or Trust Wallet

🪙 Deploy custom ERC-20 tokens (name, symbol, supply, decimals)

📊 Auto-generated token list table with price, liquidity, and volume

🔍 Search and sort tokens by liquidity, price, volume, or creation date

🛠️ Tech Stack

React – Frontend framework

TailwindCSS – Styling

Ethers.js – Blockchain interaction

MetaMask / Trust Wallet – Wallet connection

📦 Blockchain / Smart Contracts

All smart contract code and blockchain interactions are located in the hardhat-token folder. You can find:
https://github.com/smjb65/hardhat-token.git 

ERC-20 token contract

Deployment scripts

Hardhat configuration for Sepolia Testnet

🚀 Installation & Setup

Clone the repository:

git clone https://github.com/smjb65/kia-dex.git
cd kia-dex


Install dependencies:

npm install


Start development server:

npm start


The app runs at http://localhost:3000
.

🚦 Usage
Connect Wallet

Click Connect Wallet and choose MetaMask or Trust Wallet.

Switch to Sepolia Testnet in your wallet.

Create a Token

Fill out the form with token Name, Symbol, Total Supply, and Decimals.

Deploy Token

Click Deploy and confirm the transaction in your wallet.

Wait a few seconds for confirmation.

View Token in the Table

Your new token will appear in the table with:

Contract address

Creation date

Simulated price, liquidity, and volume

(Optional) Import Token to Wallet

Copy the token contract address from the table.

In MetaMask → Import Token → Paste address.

Your token will now show in your wallet.

🤝 Contributing

Fork the repo

Create your feature branch (git checkout -b feature/new-idea)

Commit changes (git commit -m "Add new idea")

Push to branch (git push origin feature/new-idea)

Open a Pull Request

📜 License

This project is for educational and testing purposes on the Sepolia Testnet. Not intended for production or real trading use.
