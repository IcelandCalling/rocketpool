## CLI Commands

# Hardhat
npx hardhat run - Deploys scripts to testnet using .env file for varable parameters 

```bash
cd rocketpool
npx hardhat run scripts/deploy.js --network testnet
```
## ethers and bip39
installs two npm packages, ethers and bip39,
```bash
npm install ethers bip39
```
1. ethers:
Description: A powerful and user-friendly library for interacting with Ethereum and other blockchain networks.
2. bip39:
Description: A library for working with BIP-39 mnemonic phrases, which are used to generate deterministic wallets.

## hardhat-toolbox
The Hardhat Toolbox bundles several commonly used plugins and tools for writing, testing, debugging, and deploying smart contracts. 
Instead of installing these plugins individually, the toolbox provides them all in one convenient package.

```bash
npm install @nomicfoundation/hardhat-toolbox
```

The toolbox includes several key tools that enhance the Hardhat experience:

Hardhat Waffle:
Enables integration with the Waffle testing library, useful for writing tests for smart contracts.

Hardhat Ethers:
Integrates the ethers.js library for interacting with Ethereum in tests, scripts, and deployments.

Hardhat Chai Matchers:
Adds Chai matchers for Ethereum-specific assertions, such as expect(...).to.be.revertedWith(...).

Hardhat Gas Reporter:
Provides gas usage and cost analysis for transactions and functions in your tests.

Solidity Coverage:
Generates code coverage reports for your Solidity smart contracts.

TypeScript Support:
Provides TypeScript boilerplate and configuration for projects using TypeScript.

## npm list hardhat
displays a hierarchical list of the installed Hardhat package and its dependencies in your project.

```bash
npm list hardhat

example
project-directory
├─ hardhat@2.17.0
├─ ethers@6.6.1
├─ chai@4.3.7
├─ ...
```

Other commands
npx hardhat clean - 
delete the artifacts and cache directories in a Hardhat project

npm run compile   -  
Used in a Hardhat project to compile your smart contracts. However, the behavior of this command depends on how it is defined in the scripts section of your project's package.json file.

npm install --save-dev @nomiclabs/hardhat-truffle5  
plugin allows you to use Truffle's testing and contract abstractions within a Hardhat environment.

git clone https://github.com/rocket-pool/rocketpool



 
