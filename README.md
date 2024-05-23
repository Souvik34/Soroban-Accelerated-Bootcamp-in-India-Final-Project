# Stellar-talk

Project Visual

## Individual

Souvik Sural, an IT undergraduate from the class of 2025, discovered a passion for web3 technologies in 2022. Eager to delve into the future of the internet, he participated in the RiseIn Solana bootcamp, where he honed his skills and knowledge. Souvik balances his academic pursuits with a love for gaming, finding inspiration in the innovative potential of decentralized technologies. His journey reflects a blend of technical learning and personal interests, driving him to contribute to the evolving web3 landscape.

## Description

Stellar-Talk is a decentralized chat application (DApp) enabling users to communicate securely and transparently on the Stellar blockchain. By connecting through wallets like Freighter or XBull, users can create or join chat rooms, each represented as a smart contract. Messages are broadcast to the network, added to the blockchain as transactions, and become visible to all chat participants. Stellar-Talk ensures message integrity with no central authority, relying on the blockchain as a decentralized ledger. Features include user authentication and message history, providing a robust, peer-to-peer communication platform.

## Vision

Stellar-Talk envisions a future where secure and transparent communication is accessible to all. By leveraging the Stellar blockchain, we eliminate the need for a central authority, ensuring no single party collects or stores user data. This decentralization protects privacy and enhances data security. Stellar-Talk aims to revolutionize the way people communicate by providing a reliable, peer-to-peer platform that fosters trust and integrity. Our mission is to empower users worldwide with a communication tool that guarantees transparency, privacy, and security, making digital conversations safer and more trustworthy.

## Programming Language

Rust and Web3

## Setup Environment

Install Dependencies

1. `rustc` >= 1.71.0 with the `wasm32-unknown-unknown` target installed. 
2. `soroban-cli`. 
3. If you want to run everything locally: `docker` (you can run both Standalone and Futurenet backends with it)
4. Node.js v18
5. [Freighter Wallet](https://www.freighter.app/) 


To build the dapp first clone the repo

```bash
git clone https://github.com/Souvik34/Soroban-Accelerated-Bootcamp-in-India-Final-Project
```

Then install dependencies using pnpm (or the equivalent commands with your favorite package manager)
```bash
npm install
```

Then run

```bash 
npm run build
```

And finally run this to start the dapp on local server
```bash
npm run start
```
