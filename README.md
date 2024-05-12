# Blockchain-project
# NFT Music Player

## Technology Stack & Tools

- Solidity (Writing Smart Contract)
- ![Blog-Solidity-Logo](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/945bf8f0-a0a3-4dfe-a57d-c7ade2b0b27d)

- Javascript (React & Testing)
- [Ethers](https://docs.ethers.io/v5/) (Blockchain Interaction)
- ![download](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/ed273e98-279b-409f-93ae-857a22b28230)


- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ipfs](https://ipfs.io/) (Metadata storage)
- [React routers](https://v5.reactrouter.com/) (Navigational components)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/), should work with any node version below 16.5.0
- ![Screenshot_2024-05-12_19_13_50](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/aea5344f-fc2b-44b5-9316-a813535ec64a)
- ![Screenshot_2024-05-12_19_19_05 (1)](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/cdbf2477-8761-4a1f-977d-3db6316a8ec1)
- ![Screenshot_2024-05-12_19_44_24](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/441b03a4-85e8-42b7-a373-04e58d5bd250)



- Install [Hardhat](https://hardhat.org/)
- Make a new directory using the command mkdir seun-nfts
- ![Screenshot_2024-05-12_19_56_08](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/eedb4838-30a7-41d5-a3a8-ef905b43d28d)


- Open your new directory using this command cd seun-nfts
- ![Screenshot_2024-05-12_19_44_24 (1)](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/f4bede55-86ab-485d-bb54-e5c1c7122c83)
- Generate an empty npm project using npm init -y
- ![Screenshot_2024-05-12_20_30_46](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/6ff153eb-4cac-4cea-93e6-aed4b57b3601)

- install hardhat using npm install --save-dev hardhat
- ![Screenshot_2024-05-12_20_24_38](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/665b00f0-6fb7-4e9e-bbc8-b3a7b39c3bf8)










## Setting Up


### 1. Install Dependencies:
```
$ cd music_nfts
$ npm install
```
### 2. Boot up local development blockchain
```
$ cd music_nfts
$ npx hardhat node
```
- ![Screenshot_2024-05-12_20_09_19](https://github.com/23Priyanshu/FILE_blockchain/assets/145743703/5d7b656a-e5d4-4c3e-b70c-56b97b1b8db8)


### 3. Connect development blockchain accounts to Metamask
- Copy private key of the addresses and import to Metamask
- Connect your metamask to hardhat blockchain, network 127.0.0.1:8545.
- If you have not added hardhat to the list of networks on your metamask, open up a browser, click the fox icon, then click the top center dropdown button that lists all the available networks then click add networks. A form should pop up. For the "Network Name" field enter "Hardhat". For the "New RPC URL" field enter "http://127.0.0.1:8545". For the chain ID enter "31337". Then click save.  


### 4. Run deploy script to migrate smart contracts
`npm run deploy`

### 5. Run Tests
`$ npx hardhat test`

### 6. Launch Frontend
`$ npm run start`



