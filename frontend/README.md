# Frontend - MetaGladiators

## Overview
The frontend module is responsible for the **user interface and interaction** with the MetaGladiators ecosystem.  
Built with **React and Web3.js**, it allows players to **train AI Gladiators, enter battles, and manage blockchain assets**.

## Features
- **AI Gladiator Management**: Train, upgrade, and deploy AI fighters.
- **Battle Interface**: View and track AI PvP battles in real-time.
- **Blockchain Integration**: Manage $GLAD transactions and NFT Gladiators.
- **Web3 Authentication**: Connects with MetaMask and other wallets.

## Directory Structure
📂 `frontend/` - Web-based UI for MetaGladiators  
 ├── 📂 `src/` - Source code  
 │   ├── 📂 `components/` - Reusable UI components  
 │   ├── 📂 `pages/` - Game UI pages  
 ├── 📂 `public/` - Static assets  
 ├── `package.json` - Dependencies  
 ├── `README.md` - Frontend documentation  

## Installation
1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   ```

3. Build the frontend for production:
   ```bash
   npm run build
   ```

## Web3 Integration & Wallet Setup
- Connects with MetaMask for blockchain interactions.
- Fetches and displays player assets from smart contracts.
- Supports $GLAD transactions and NFT Gladiator interactions.

## Environment Variables
Create a `.env` file in the `frontend/` directory and add:
```plaintext
REACT_APP_INFURA_API_KEY=your_infura_api_key
REACT_APP_CONTRACT_ADDRESS=your_smart_contract_address
```

## Contribution Guide
- Follow React and Web3 best practices for UI and blockchain interactions.
- Submit UI improvements as feature branches.
- Ensure responsive design and accessibility for all screens.

## License
This project is licensed under the MIT License.

---

**For Japanese documentation, refer to `MetaGladiators-Japanese/frontend/README.md`**  
