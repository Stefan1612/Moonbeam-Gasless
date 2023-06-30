# NFT-Marketplace

## Status

The NFT Marketplace is currently running and fully functional on Goerli at

1. NFT Market:

2. NFT:

The Website is online and running at [Website]()

## Local environment set up

1. git clone

2. npm i

3. npm start

4. npx hardhat console --network goerli

5. npx hardhat run scripts/deploy.js --network goerli

6. const contract = await ethers.getContractFactory("NftMarketPlaceV2")

7. const Contract = await contract.attach("[input address from deploying NftMarketPlaceV2 contract (step 5)]")

8. await Contract.setNftAddress("[input address from NFTV2 contract (step 5)]")

## Video Demo

## Approach

Running currently on Goerli
A NFT Marketplace running currently on Goerli. Let's you mint, sell and buy NFT's. During the minting we store the Metadata on IPFS and only store the TokenURI on-chain.

## Stack

### Blockchain Technologies

1. Environment - [Hardhat](https://hardhat.org/)
2. File Storage - [IPFS](https://github.com/ipfs/js-ipfs/tree/master/packages/ipfs-http-client#install)
3. Client - [ethers.js](https://docs.ethers.io/v5/)

## Moonbeam

### Demo videos:

NFT Marketplace: hhttps://www.youtube.com/watch?v=zYdKS_B3RJo

SKD Hyphen: https://www.youtube.com/watch?v=cViRhJu1qIM

### Hyphen Widget

The Biconomy Hyphen Widget allows for fast and easy cross chain movement of funds. You can easily with a few clicks and seconds transfer your
Tokens from one network to another

Biconomy docs: https://docs.biconomy.io/products/hyphen-instant-cross-chain-transfers/hyphen-widget

Added at: [Code]()

### Gasless Transactions

Moonbeam docs:

Added at: [Code]()

And all contracts modified accordingly: [Code]()

### Frontend

- [React](https://reactjs.org/)
- [ethers.js](https://docs.ethers.io/v5/)
- [MUI: React UI Library](https://mui.com/)
- [Bootstrap]

## Backend

- [Netlify](https://www.netlify.com/): Website host
- [Node.js](https://nodejs.org/en/)

## Challenges

- Handling Allowance
- IPFS upload
