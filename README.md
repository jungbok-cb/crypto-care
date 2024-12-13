<h1 align="center">Crypto Care</h1>

<p align="center">A decentralized donation platform that enables users to support charitable organizations using cryptocurrency.</p>

## Overview

Crypto Care is a web3 application built with OnchainKit that allows users to make cryptocurrency donations to various charitable organizations. The platform can support organizations like Red Cross, UNICEF, and others, enabling transparent and direct crypto donations.

## Features

- Connect cryptocurrency wallets (Coinbase Wallet, MetaMask, Rainbow)
- View charitable organization profiles and their causes
- Make direct cryptocurrency donations
- Track donation transactions and balances
- Built on Base blockchain for lower transaction fees
- Real-time transaction status updates

## Setup

To run this project locally, you'll need to set up the following environment variables in your `.env` file:

```sh
# See https://portal.cdp.coinbase.com/products/onchainkit
NEXT_PUBLIC_CDP_API_KEY="GET_FROM_COINBASE_DEVELOPER_PLATFORM"

# See https://cloud.walletconnect.com
NEXT_PUBLIC_WC_PROJECT_ID="GET_FROM_WALLET_CONNECT"
```

## Local Development

```sh
# Install bun if you haven't already
curl -fsSL https://bun.sh/install | bash

# Install dependencies
bun install

# Start the development server
bun run dev
```

## Technology Stack

- Next.js for the frontend framework
- TailwindCSS for styling
- Wagmi for Ethereum interactions
- OnchainKit for wallet connections
- Base blockchain (Coinbase's L2)
- RainbowKit for wallet management
- Framer Motion for animations

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
