# Web-3
# LearnWeb3 First dApp

This repository contains the code for a basic decentralized application (dApp) built using web3 technologies. It allows users to set and retrieve their mood by interacting with a smart contract deployed on the Ethereum blockchain.

## Getting Started

To run the dApp locally, follow these steps:

1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser that supports the required web3 technologies (e.g., MetaMask).
3. Make sure you have a compatible Ethereum wallet installed (e.g., MetaMask) and are connected to the Ethereum network.
4. The dApp will prompt you to connect your wallet if not already connected. Click on the appropriate button to connect.
5. Once connected, you can set or retrieve your mood by entering the desired mood in the text input field and clicking the respective buttons.

## Prerequisites

To run the dApp, you need the following:

- A web browser (e.g., Chrome, Firefox) with MetaMask extension installed.
- An Ethereum wallet (e.g., MetaMask) with some ETH for gas fees.

## Functionality

The dApp provides the following functionality:

- **Set Mood**: Enter a mood in the text input field and click the "Set Mood" button to set your mood. This will update the mood value stored in the smart contract on the Ethereum blockchain.

- **Get Mood**: Click the "Get Mood" button to retrieve and display your current mood from the smart contract.

## Smart Contract

The dApp interacts with a smart contract deployed on the Ethereum blockchain. The smart contract has the following functions:

- **setMood**: Accepts a string parameter representing the mood and updates the stored mood value.

- **getMood**: Returns the current mood stored in the contract.

## Dependencies

The dApp relies on the following dependencies:

- **Ethers.js**: A JavaScript library for interacting with Ethereum. The dApp uses version 5.7.2, which is loaded from a remote CDN.

## Notes

- Make sure you have an active internet connection when running the dApp as it relies on external libraries and web3 providers.
- Ensure that your Ethereum wallet (e.g., MetaMask) is properly set up and connected to the correct network (e.g., Ethereum mainnet, Ropsten, etc.).
- This is a basic dApp intended for learning purposes and does not include error handling or advanced features commonly found in production-ready applications.

Feel free to explore and modify the code to enhance your understanding of web3 development and smart contract interactions.

Happy coding!
