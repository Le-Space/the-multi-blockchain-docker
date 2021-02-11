# the-multi-blockchain-docker
  
  - Ethermint node
  - Ethereum Rinkeby
  - RSK node
  - Moonbeam 
  - Namecoin
  - Doichain

## Installation

1. Install Docker and Docker Compose
2. Run ```npm install``` to install the dependencies
3. ```cd``` to one of the blockchains folder and run 
```docker-compose up -d``` to start the node

4. Back in the root folder, deploy the smart contracts using:

```
truffle migrate --network development
```
Make sure to enable the correct configuration in ```truffle-config.js```
