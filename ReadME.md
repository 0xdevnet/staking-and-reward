# DeFi Project
### This is a Decentralised Finanace Project developed by refering [this](https://youtu.be/CgXQC4dbGUE)

## About the Application
### There are 3 Smart Contract in this project, where 2 sol file is for ERC20 tokens, where one of the token is mock Dai or mDai, which is acting as the colateral for this project. The user will have to Deposit the mDai token to TokenFram SmartContract and for depositing our mDai we will get staking reward in form of Dapp Tokens.

## Technology Used 
- Solidity
- Truffle
- React
- Web3
- Ganache
- Metamask

## How to run the Project
- Start the local Blockchain in Ganache.
- Connect the Local Blockchain with Metamask and import the second account to meta mask
- Run Truffle Commands 
    - `Truffle Compile` to compile the smartcontract
    - `truffle migrate --reset` to migrate your code to blockchain
- Now start the Front End by `npm start` the React will run on `localhost:3000`
- You can start deposit your mDai from the imported account.
- Now you can run `truffle exec scripts/issue-token.js` to distribute the the reward to the investors
