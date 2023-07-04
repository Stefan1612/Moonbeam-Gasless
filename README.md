# NFT-Marketplace

## Status

The NFT Marketplace is currently running and fully functional on Moonbase Alpha at

1. NFT Market: https://moonbase.moonscan.io/address/0x549A17f51B7911c59E90592190D1001cDA713E4E

2. NFT: https://moonbase.moonscan.io/address/0xE47c76a87b4423eE77da447F7a04f158E7c2a742

The Website is online and running at [Website](https://moonbox-marketplace.netlify.app/)

## Local environment set up

1. git clone

2. npm i

3. npm start

4. npx hardhat run scripts/deploy.js --network moonbaseAlpha

5. npx hardhat console --network moonbaseAlpha

6. const contract = await ethers.getContractFactory("NftMarketPlaceV2")

7. const Contract = await contract.attach("[input address from deploying NftMarketPlaceV2 contract (step 4)]")

8. await Contract.setNftAddress("[input address from NFTV2 contract (step 4)]")

## Moonbeam Hackathon

Submission video: https://www.youtube.com/watch?v=LimnFmKNKWE

Custom Moonbase provider:

https://github.com/Stefan1612/Moonbox/blob/62a9c527fe2457c8d5461b8f56b335363700b27f/src/App.js#L144C2-L146

Generating Calldata for tx Batch:

https://github.com/Stefan1612/Moonbox/blob/62a9c527fe2457c8d5461b8f56b335363700b27f/src/App.js#L684-L707

Sending batchAll with - 1. Approve 2. sellMarketToken - to Batch Precompile inside "sellNFT" function:

https://github.com/Stefan1612/Moonbox/blob/62a9c527fe2457c8d5461b8f56b335363700b27f/src/App.js#L709C1-L755


## Approach

Running currently on Moonbase Alpha
A NFT Marketplace running currently on Moonbase Alpha. Let's you mint, sell and buy NFT's. During the minting we store the Metadata on IPFS and only store the TokenURI on-chain.

## Stack

### Blockchain Technologies

1. Environment - [Hardhat](https://hardhat.org/)
2. File Storage - [IPFS](https://github.com/ipfs/js-ipfs/tree/master/packages/ipfs-http-client#install)
3. Client - [ethers.js](https://docs.ethers.io/v5/)

### Hyphen Widget

SKD Hyphen: https://www.youtube.com/watch?v=cViRhJu1qIM

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
