# Solana Token Freezing Script

This project includes scripts designed to manage and freeze token accounts on the Solana blockchain. The scripts connect to the Solana network, fetch token holder information, and freeze accounts based on pre-configured rules and settings.

## Key Features

- **Automated Freezing**: Automatically freeze token accounts that are not on the whitelist.
- **Real-Time Monitoring**: Continuously monitor token holders and adjust account statuses based on updated information.
- **Configurable**: Easily adjust settings such as freeze authority, token mint address, and more.
- **Dry Run Mode**: Test the scripts without making actual changes to ensure everything works as expected.

## Prerequisites

- **Node.js**: Ensure Node.js is installed on your system to run the scripts.
- **Solana Wallet**: A wallet private key in base58 format is required for generating the freeze authority keypair.
- **QuickNode API**: A valid QuickNode API URL for connecting to the Solana mainnet.

## What You Need

- **QuickNode Account**: Access to a QuickNode API endpoint to connect to the Solana blockchain.
- **Token Mint Address**: The specific token mint address you want to manage.
- **Freeze Authority Keypair**: A keypair file generated from your wallet private key to authorize freezing actions.
- **Whitelist Addresses**: Addresses that should be excluded from freezing actions, typically trusted or essential accounts.

## Contact

For detailed setup instructions, troubleshooting, or further information, please contact us on Telegram: [https://t.me/mooooh42](https://t.me/mooooh42).

---

**Disclaimer**: Ensure you have the proper authorization before freezing any token accounts. Use this tool responsibly to avoid unintended disruptions.
