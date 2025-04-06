# Cardano Slot Game – On-Chain Slot Machine Built on Plutus

A fully decentralized **Slot Machine Game on the Cardano blockchain** built using **Plutus Smart Contracts**. This repo showcases how to create a provably fair, fully on-chain gambling DApp using Haskell and Cardano's UTxO model.

---

## Features

- Fully on-chain slot game logic
- Provably fair random outcomes (pseudo-randomness via oracle or entropy tricks)
- ADA betting and payout system
- Frontend-ready endpoints for wallet integration (Nami, Eternl, Flint)
- Secure smart contract interactions using Plutus V2

---

## Tech Stack

- **Cardano Blockchain**
- **Plutus V2 Smart Contracts** (Haskell)
- **Cardano-CLI & cardano-node**
- **Nami Wallet / CIP-30 Wallets**
- **Frontend (Optional)**: React + TypeScript + Lucid or Mesh

---

## How It Works
- User connects wallet and places a bet in ADA.

- The smart contract locks the bet and generates a spin.

- Outcome is determined (off-chain or with future oracle).

- User wins based on symbol match — contract releases ADA prize.

- Results and transaction details are logged on-chain.

## Security Notes
- Ensure you validate all inputs and wallet connections.

- Use randomness carefully — consider Chainlink VRF (when supported) or oracle-based entropy.

- Always test on Cardano preview/testnet before mainnet deployment.

## Contact
-Twitter [@defai_maxi](https://x.com/defai_maxi)
-Telegram [@rhettjel](https://t.me/rhettjel)
