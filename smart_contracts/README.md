# Smart Contracts - MetaGladiators

## Overview
The smart contract module manages **blockchain-based assets, AI Gladiator NFTs, and battle economy** for MetaGladiators.  
It ensures **transparent transactions, NFT ownership, and reward distribution** on Ethereum L2 (Base).  

## Features
- **$GLAD Token**: ERC-20 token that powers the in-game economy.
- **AI Gladiator NFTs**: ERC-721 smart contracts for unique AI fighters.
- **Battle Arena Smart Contract**: Handles PvP wagers and on-chain match outcomes.
- **Secure & Verifiable**: All transactions are recorded on the blockchain.

## Directory Structure
📂 `smart_contracts/` - Blockchain integration module  
 ├── 📂 `contracts/` - Solidity smart contracts  
 │   ├── `GladiatorToken.sol` - ERC-20 token contract ($GLAD)  
 │   ├── `NFTGladiator.sol` - ERC-721 NFT contract for AI fighters  
 │   ├── `BattleArena.sol` - On-chain battle wagering and reward distribution  
 ├── 📂 `deploy/` - Deployment scripts  
 │   ├── `deploy.js` - Deployment script for deploying contracts  
 ├── 📂 `tests/` - Smart contract testing framework  
 ├── `README.md` - Smart contract documentation  

## Installation
1. Install dependencies:
   ```bash
   npm install
   ```

2. Compile smart contracts:
   ```bash
   npx hardhat compile
   ```

3. Run tests:
   ```bash
   npx hardhat test
   ```

4. Deploy contracts:
   ```bash
   npx hardhat run scripts/deploy.js --network goerli
   ```

## Smart Contract Functions
- **GladiatorToken.sol**
  - `mint()` - Mints new $GLAD tokens.
  - `transfer()` - Transfers tokens between users.
  - `approve()` - Authorizes spending of tokens by another account.

- **NFTGladiator.sol**
  - `mintGladiator()` - Creates a new AI Gladiator NFT.
  - `trainGladiator()` - Upgrades AI Gladiator attributes.
  - `transferNFT()` - Transfers Gladiator ownership.

- **BattleArena.sol**
  - `enterBattle()` - Registers AI Gladiators for PvP battles.
  - `resolveBattle()` - Determines winners and distributes rewards.
  - `withdrawWinnings()` - Allows players to claim their earnings.

## Contribution Guide
- Submit new smart contract features in `contracts/`.
- Ensure tests cover new functionalities before PR submission.
- Document major changes in `README.md`.

## License
This project is licensed under the MIT License.

---

**For Japanese documentation, refer to `MetaGladiators-Japanese/smart_contracts/README.md`**  
