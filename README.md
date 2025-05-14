# Buy Me A Coffee DApp

A decentralized application built on VeChain that allows users to support content creators by sending them VET tokens as tips.

## Features

- Connect wallet using VeChain Sync2
- Send VET tokens as tips
- View transaction history
- Support for both testnet and mainnet

## Project Structure

```
buy-me-coffee-example/
├── apps/
│   ├── frontend/         # React frontend application
│   └── contracts/        # Smart contracts and deployment scripts
```

## Prerequisites

- Node.js v16 or later
- Yarn or npm
- VeChain Sync2 Wallet

## Setup

1. Install dependencies:
   ```bash
   yarn install
   ```

2. Deploy smart contracts:
   ```bash
   cd apps/contracts
   yarn compile
   yarn deploy-testnet  # For testnet deployment
   ```

3. Start the frontend:
   ```bash
   cd apps/frontend
   yarn dev
   ```

## Smart Contract

The smart contract is deployed on VeChain testnet at: `0xf97e8eb1902331810f2beeed99a096dac746528e`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
