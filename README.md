# Truffle_Petshop

![Image of Yaktocat](box-img-lg.png?raw=true "Petshop")

## Ethereum Petshop Tutorial

Following the ETH pet shop tutorial to customize our own dapp. 

You can combine the hello world example and this one to make your own dapp.


### Directory Structure 

After unpack the petshop, we will have the structure as shown in this repo"

* contracts/
    * Contains the Solidity source files for our smart contracts, like `Migrations.sol`
* migrations/
    * Truffle uses a migration system to handle smart contract deployments. 
    * A migration is an additional special smart contract that keeps track of changes
* test/
    * Contains both JS and Solidity tests for smart contracst
* truffle-config.js
    * Truffle configuration file



## Using the dapp

start the local web server by running"

```
npm run dev
```

![Image of dapp](assets/dapp.png?raw=true "Petshop")

the dev server will launch and automatically open a new browser tab containing your dapp, and a prompt asking for permission from metamask will pop out. 

Allow the permission and try adopt pets by clicking buttons. The transaction details can be found on metamask.