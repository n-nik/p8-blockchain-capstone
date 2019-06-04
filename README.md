# Udacity Blockchain Capstone

The capstone is a decentralized housing product. 

## Launch Ganache:
Run this command in separate terminal window

`npx ganache-cli -m "candy maple cake sugar pudding cream honey rich smooth crumble sweet treat"`

## Run truffle tests:

`npm install`

`cd eth-contracts`

`npx truffle test ./test/TestERC721Mintable.js`

`npx truffle test ./test/TestSquareVerifier.js`

`npx truffle test ./test/TestSolnSquareVerifier.js`

## Deploy contracts to Rinkeby network
Commands:

`export INFURA_KEY="<your_infura_key>"`

`export MNEMONIC="<metamask>"`

`export NETWORK="rinkeby"`

`truffle deploy --network rinkeby`

Result: 
```
  Verifier: 0x5a2fa4d64dc035ab2a401c63f6b07e74dd4a6672
  SolnSquareVerifier: 0x77e97bea4ae2bec2a77b025dfeb75925ea4ab644
```

## SolnSquareVerifier ABI

SolnSquareVerifier Contract ABI place  [here](https://github.com/n-nik/p8-blockchain-capstone/blob/master/eth-contracts/build/contracts/SolnSquareVerifier.json)


Tokens minted with [myetherwallet tool](https://www.myetherwallet.com/interface/interact-with-contract)


OpenSea Rinkeby marketplace [link](https://rinkeby.opensea.io/assets/niktokenname)


# Project Resources

* [Remix - Solidity IDE](https://remix.ethereum.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Truffle Framework](https://truffleframework.com/)
* [Ganache - One Click Blockchain](https://truffleframework.com/ganache)
* [Open Zeppelin ](https://openzeppelin.org/)
* [Interactive zero knowledge 3-colorability demonstration](http://web.mit.edu/~ezyang/Public/graph/svg.html)
* [Docker](https://docs.docker.com/install/)
* [ZoKrates](https://github.com/Zokrates/ZoKrates)
