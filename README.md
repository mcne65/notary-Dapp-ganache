# README
App: http://bit.ly/36DWMbW

Rinkeby contract deployed: https://rinkeby.etherscan.io/address/0x9414edDe4295484ceb3836B8fce48f796FCDB9c4/  
## What does this project do? 

This is a final project for Consensys Academy Blockchain Developer Bootcamp. It allows users to upload a file to IPFS and notarize it with their MetaMask Local Ganache Ethereum Account and post it on Rinkeby Testnet with the simple click of a single deploy button. Complete with toast messages for user status updates. 

## How to I Set It Up Locally? 

### Pre-Requisites

<em>Required:</em> MetaMask, Truffle, Node.js, Npm/yarn, Internet Connection (for IPFS uploads)<br/>

### 1st
Update .secret file with your Mnemonic for your MetaMask account and set your MetaMask extension to custom network `localhost` at port `8545`. 

### 2nd
Run `ganache-cli -m 'yourMnemonichere'` and `truffle compile && truffle migrate --network development` to deploy your ProofOfExistence contract to your local blockchain. 

### 3rd
Start the app from `client/` directory with `npm start`

### 4th
Navigate to `localhost:3000` and upload and notarize documents with one click of a button!
 
#### Credits
Made with <3 from <a href="https://github.com/ConsenSys/rimble-app-demo">Rimble App Demo</a>.

#### License 
MIT License, Max Goodman, January 2020. 

