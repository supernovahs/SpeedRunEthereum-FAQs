# SpeedRunEthereum - FAQs & More..

## Introduction: 

Welcome to the comprehensive Guide to help you while you are tackling all the Challenges. This guide is aimed to help new builders solve their common queries which the old Buidlers had went through, this is not a cheatsheet. But a booster to all those who get stuck in some common issues and increase your level of understanding of the scaffoldEth code and help you become a great buidler. 

LFG!

## Yarn

Yarn is a package manager which is introduced to make life of developers easier. In a project, there are many dependencies that need to be managed and installed to be able to run the project. Yarn helps us navigate them. 
If you want to start a local host server to test out the front end code, Yarn wil do this in like this:
```
yarn start
``` 
And if you wish the long way , then you may type this:
```
  yarn workspace @scaffold-eth/react-app start
```

So Now lets learn what are the most common Yarn command you will need while developing on ScaffoldEth

### Yarn Start
Starts a local host for testing out the front end. 

### Yarn chain

It deploys a local Blockchain for you to deploy your contracts easily and fast to test your code. It is like Ganache, except we use Hardhat(We'll talk about it later.)

### Yarn deploy

This deploys your contract to the local blockchain 

### Yarn deploy --reset
If you want to reset the contract , this command will do it.

### Yarn run generate
This generates a new wallet using a mnemonic(A seed phrase) for the user to deploy the contract to a testnet like Rinkeby, Kovan etc for testing . 
Beware: Don't use this for actual funds. These wallets are public . Only for testing purposes.

### Yarn account
Once you have a wallet , this command will show you a Qrcode of the wallet for you to send it Fund, and will check for balances on different Blockchains.


