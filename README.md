# PropChain — Real Estate Management DApp
PropChain is a decentralized application (DApp) designed for real estate transactions in smart cities, built on blockchain technology and decentralized storage (IPFS).
It enhances traditional property sale workflows by providing tokenization, escrow automation, property search, and dynamic user-generated listings.

## Technology Stack & Tools
- Solidity – Smart contract development
- Hardhat – Development environment and testing
- Ethers.js – Blockchain interaction library
- React.js – Frontend user interface
- IPFS (via Pinata or NFT.Storage) – Decentralized metadata storage
- MetaMask – Wallet connection

## Requirements For Setup
- Install NodeJS
- Install MetaMask browser extension

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
`$ npm install`

### 3. Compile and Test Smart Contracts
`$ npx hardhat compile`
`$ npx hardhat test`

### 4. Start Local Blockchain Node (Hardhat)
`$ npx hardhat node`

### 5. Deploy Smart Contracts
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`

## Acknowledgements
- Original project inspired by Millow by Dapp University (https://github.com/dappuniversity/millow)

## Final Note
This project is part of a Final Year Project (FYP) initiative at Universiti Tunku Abdul Rahman (UTAR), aimed at demonstrating blockchain applications for intelligent real estate management in smart cities.
