# Solana Wallet Tracker with Discord Notifications

This project is a Node.js script that monitors a Solana wallet for new transactions and sends real-time notifications to a Discord channel via webhook. It also provides current SOL and USD wallet balances using the Solana Web3.js library and CoinGecko API.

## Features
- Tracks recent Solana wallet transactions.
- Sends Discord notifications with transaction details, including SOL and USD amounts.
- Retrieves wallet balance in both SOL and USD.
- Automatically updates every minute.

## Technologies
- **Node.js**
- **Solana Web3.js**
- **Axios**
- **Discord Webhooks**

## How to Use
1. Clone the repository.
2. Install dependencies:
    ```bash
    npm install
    ```
3. Update the script with your wallet address and Discord webhook URL.
4. Run the script:
    ```bash
    node your-script-name.js
    ```
