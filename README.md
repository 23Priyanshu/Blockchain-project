# Blockchain-project
# NFT Music Player

## Technology Stack & Tools

- Solidity (Writing Smart Contract)
- Javascript (React & Testing)
- [Ethers](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ipfs](https://ipfs.io/) (Metadata storage)
- [React routers](https://v5.reactrouter.com/) (Navigational components)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/), should work with any node version below 16.5.0
- ![Screenshot_2024-05-12_19_13_50](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/aea5344f-fc2b-44b5-9316-a813535ec64a)
- ![Screenshot_2024-05-12_19_19_05 (1)](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/cdbf2477-8761-4a1f-977d-3db6316a8ec1)
- ![Screenshot_2024-05-12_19_44_24](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/441b03a4-85e8-42b7-a373-04e58d5bd250)



- Install [Hardhat](https://hardhat.org/)
![1-](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/b3455be1-a0c9-4a61-ae21-0b86c7b3bc3b)


## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
```
$ cd music_nfts
$ npm install
```
### 3. Boot up local development blockchain
```
$ cd music_nfts
$ npx hardhat node
```

### 4. Connect development blockchain accounts to Metamask
- Copy private key of the addresses and import to Metamask
- Connect your metamask to hardhat blockchain, network 127.0.0.1:8545.
- If you have not added hardhat to the list of networks on your metamask, open up a browser, click the fox icon, then click the top center dropdown button that lists all the available networks then click add networks. A form should pop up. For the "Network Name" field enter "Hardhat". For the "New RPC URL" field enter "http://127.0.0.1:8545". For the chain ID enter "31337". Then click save.  


### 5. Run deploy script to migrate smart contracts
`npm run deploy`

### 6. Run Tests
`$ npx hardhat test`

### 7. Launch Frontend
`$ npm run start`

License
----
MIT


