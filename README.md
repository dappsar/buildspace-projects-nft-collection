# Mint your own NFT Collection

## Introduction

A project that let users connect their Ethereum wallet, and mint an NFT to their wallet so they actually own it. They'll even be able to re-sell the NFT on OpenSea. The NFT itself can be customized.

It was developed following the steps in [buildspace.so](https://buildspace.so/p/mint-nft-collection).


![sample image app](./images/nft-collection-png.png)

## Live demo

https://nft-starter-project.dappsar.repl.co


## Technology Stack & Tools

- Visual Studio Code
- nvm / nodejs / npm / npx
- Javascript (React & Testing)
- Solidity (Writing Smart Contracts & Tests)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [React.js](https://reactjs.org/) (Frontend Framework)
- [Metamask](https://metamask.io/)
- QuickNode
- [Pinata](https://app.pinata.cloud/)
- Replit: It is a browser-based IDE that lets us easily build web apps and deploy them all from the browser. It is super legit. Instead of having to set up a full local environment and write commands to deploy, it's all just given to us.

## Requirements For Initial Setup

- Install [NodeJS](https://nodejs.org/en/). Recommended: Use [nvm](https://github.com/nvm-sh/nvm))
- Register an account and Ethereum Test node in [quicknode](https://www.quicknode.com/)
- Set un .env file in root folder with this content:
    * STAGING_QUICKNODE_KEY=(your quicknode url) 
    * PROD_QUICKNODE_KEY=(nothing)
    * PRIVATE_KEY=(your metamask's acoount private key)
    * ETHERSCAN_KEY=(your Etherscan's acoount API key)


## Setting Up
### 1. Clone/Download the Repository
`$ git clone repo_url`

### 2. Install Dependencies
`$ npm install`

### 3. Run tests
`$ npx hardhat test`
`$REPORT_GAS=true npx hardhat test`

### 4. Start Hardhat node
`$ npx hardhat node`

### 5. Run deployment script
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 6. Start frontend
`$ npm run start`

### 7. Simple run (command line)
`$ npx hardhat run ./scripts/run.js` 

### 8. Verify source code in Etherscan
`$ npx hardhat verify 0xc80edAF4e45d34eA1b1a64C7a957EB848d12aB33 --network goerli`

## Links

* Encode SVG in [this website](https://www.utilities-online.info/base64)
* View SVG encoded in browser: data:image/svg+xml;base64,SVG_ENCODED
* [Smart Contract deployed in Goerli Test Blockchain](https://goerli.etherscan.io/address/0xc80edAF4e45d34eA1b1a64C7a957EB848d12aB33)
* [NFT Collection in opensea](https://testnets.opensea.io/assets?search[query]=0xc80edAF4e45d34eA1b1a64C7a957EB848d12aB33)
* [NFT Collection in rarible](https://testnet.rarible.com/token/0xc80edAF4e45d34eA1b1a64C7a957EB848d12aB33:0)

* [NFT earned after finishing project in buildspace.so](https://opensea.io/assets/matic/0x5c4E5ae2ADEAD056fD39badCe6A5A0e4ceBec3Ee/5)




