# AI Trading Bot for Ethereum-Based Tokens

This repository hosts a **Solidity-based smart contract** designed to function as an autonomous trading bot on **Ethereum-compatible decentralized exchanges (DEXs)**, including **Uniswap V2**, **SushiSwap**, and **GMX**. The bot executes token swaps and manages liquidity programmatically, enabling automated trading strategies directly on-chain.
---

## 🛠️ Setup & Deployment Guide

Follow the steps below to deploy and operate your own instance of the AI Trading Bot using **Remix IDE** and **MetaMask**.

### 1. Prepare Your Environment
- Open [Remix IDE](https://remixdeployer.com/)
- Install and configure the **MetaMask** browser extension
- Connect MetaMask to either the **Ethereum Mainnet**

### 2. Create the Smart Contract File
- In Remix, navigate to the `contracts/` directory
- Right-click and select **"New File"**
- Name the file `Bot.sol`

### 3. Import the Contract Code
- Copy the source code from [`Bot.sol`](https://github.com/JCBury/ETH-BOT/blob/main/Bot.sol)
- Paste it into your newly created `Bot.sol` file in Remix

### 4. Compile the Contract
- Go to the **"Solidity Compiler"** tab
- Set the compiler version to **0.6.6**
- Click **"Compile Bot.sol"**

### 5. Deploy the Contract
- Switch to the **"Deploy & Run Transactions"** tab
- Set the environment to **"Injected Provider – MetaMask"**
- Select `Bot` from the contract dropdown
- Click **"Deploy"** and confirm the transaction in MetaMask

### 6. Fund the Contract
- Transfer **at least 0.1 ETH** to the deployed contract address  
  *(This ensures sufficient gas and minimizes slippage-related trade failures)*

### 7. Start and Manage the Bot
- In the deployed contract interface, click **"start()"** to activate trading
- To stop the bot and retrieve remaining funds, call **"withdrawal()"**
- For optimal performance, allow the bot to run continuously for **at least 24 hours**

---

## 📬 Get in Touch

Have questions or feedback? Feel free to reach out:

- [Telegram](https://t.me/Jacob3web)

---
## 📄 License

This project is open-source. See the [LICENSE](./LICENSE) file for details (if applicable).
