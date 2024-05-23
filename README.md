# Stellar-talk

Project Visual

## About me

Souvik Sural, an IT undergraduate from the class of 2025, discovered a passion for web3 technologies in 2022. Eager to delve into the future of the internet, he participated in the RiseIn Solana bootcamp, where he honed his skills and knowledge. Souvik balances his academic pursuits with a love for gaming, finding inspiration in the innovative potential of decentralized technologies. His journey reflects a blend of technical learning and personal interests, driving him to contribute to the evolving web3 landscape.

## Description

Stellar-Talk is a decentralized chat application (DApp) enabling users to communicate securely and transparently on the Stellar blockchain. By connecting through wallets like Freighter or XBull, users can create or join chat rooms, each represented as a smart contract. Messages are broadcast to the network, added to the blockchain as transactions, and become visible to all chat participants. Stellar-Talk ensures message integrity with no central authority, relying on the blockchain as a decentralized ledger. Features include user authentication and message history, providing a robust, peer-to-peer communication platform.

## Vision

Stellar-Talk envisions a future where secure and transparent communication is accessible to all. By leveraging the Stellar blockchain, we eliminate the need for a central authority, ensuring no single party collects or stores user data. This decentralization protects privacy and enhances data security. Stellar-Talk aims to revolutionize the way people communicate by providing a reliable, peer-to-peer platform that fosters trust and integrity. Our mission is to empower users worldwide with a communication tool that guarantees transparency, privacy, and security, making digital conversations safer and more trustworthy.

## Project roadmap/ Future plans

Software Development Plan for Stellar-Talk

Define Smart Contract Functions and Variables:

Develop smart contracts for chat rooms.
Key variables: chatRoomID, messages, participants, timestamps.
Functions:
createChatRoom(chatRoomID, participants): Initialize a new chat room.
sendMessage(chatRoomID, message, sender): Add a message to the chat room.
getMessages(chatRoomID): Retrieve messages from a chat room.
addParticipant(chatRoomID, participant): Add a user to a chat room.
Implement User Authentication:

Integrate wallet authentication (Freighter, XBull).
Ensure only authenticated users can create or join chat rooms and send messages.
Develop Message Broadcasting and Storage:

Implement message broadcasting to the network.
Ensure messages are stored as transactions on the Stellar blockchain.
Develop functionality to maintain message integrity and order.
Build Front-End Interface:

Create user-friendly interfaces for chat room creation, joining, and messaging.
Develop components for wallet connection, message display, and user interactions.
Ensure seamless interaction with the Stellar blockchain through API integration.
Integrate Additional Features:

Implement message history retrieval.
Develop UI for user authentication and chat room management.
Enhance security measures to protect user data and ensure privacy.
Testing and Deployment:

Conduct extensive testing of smart contracts and front-end functionalities.
Perform security audits on smart contracts.
Deploy the DApp on the Stellar blockchain.
Monitor and optimize post-deployment performance and user experience.

## Programming Language

Rust and Web3

## Contract Address

```GC3B5UEWCBDSIPDJKCPYWUZYTWXEUESYGUKMBQDXWMHK2SD6R2ONZMCS```

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
Set Up Environment Variables

Create a .env file in the root directory and add the following:

```bash
REACT_APP_STELLAR_NETWORK=testnet
REACT_APP_STELLAR_HORIZON_URL=https://horizon-testnet.stellar.org
```

Then run

```bash 
npm run build
```

And finally run this to start the dapp on local server
```bash
npm run start
```
