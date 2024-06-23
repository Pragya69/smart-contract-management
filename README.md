## ETH_AVAX_MODULE_2_PROJECT

### Interact with your SmartContract through Front-end Application


## Description
For this project, create a simple contract with 2-3 functions. Then show the values of those functions in frontend of the application.
The files index.js, MySmartContract.sol, and deploy.js contain codes to practice interaction with the SmartContract_with_Front_end_interaction smart contract through a website.


## Prerequisites

- Node.js (v14.0.0 or higher)
- MetaMask wallet extension installed in your browser
  

## Starter Next/Hardhat Project

After cloning GitHub, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type:  npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type:  npx hardhat run --network localhost scripts/deploy.js 
5. Back in the first terminal, type:  npm run dev  to launch the front end.

6.Open the application in your browser, the project will be running on your localhost. Typically at:

```bash
http://localhost:3000
```

## Setting up the local host network and a dummy account in your Metamask Wallet


->We need to set up a local network with the MetaMask wallet. otherwise, Metamask will not be able to communicate with the local node. click on the MetaMask extension then click on the top middle button which is the network selection button
<pre>
-> Click on (Add a Network)
-> Click on (Add a Network Manually)
-> Give the (Network name - whatever you want(Local Host)
-> Set the (New RPC URL - [(http://127.0.0.1:8545/) ]
-> Set the (Chain ID - 31337 )
-> Set the (Currency symbol - GO )
->Now set the MetaMask wallet network to the newly created local network</pre>

## Technologies Used

- React - JavaScript library for building user interfaces
- Ethereum - Blockchain network for decentralized applications
- MetaMask - Wallet and gateway to Ethereum blockchain
- ethers.js - Library for interacting with Ethereum smart contracts

## Authors

PRAGYA
[https://www.linkedin.com/in/pragya-299103231/]
21BCS9346@cuchd.in
