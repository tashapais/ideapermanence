First, we setup our coding environment with the help of Truffle, after that we wrote smart contracts in solidity. After writing smart contracts, to build the front-end of our DApp we used React.js Javascript library plus some HTML5, CSS3 & JavaScript.
We used IPFS (InterPlanetary File System) to store the hashes of our videos to the blockchain and later we'll be able to play those videos by calling those video hashes.
To connect our Smart Contracts with front-end we used Web3.js and then we deployed our Smart Contracts on the Mumbai testnet. In the final step, we hosted this DApp on IPFS by using the Fleek platform. We deployed on SKALE and used Livepeer for decentralized video streaming.

Install dependancies

```
npm install
```

Deploy the smart contracts to the blockchain.

```
truffle migrate
```

Start react app.

```
npm start
```

