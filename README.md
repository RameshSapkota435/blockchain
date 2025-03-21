# Decentralized Chat Application

A blockchain-based chat application that enables secure, decentralized messaging between users using Ethereum smart contracts. The application provides a user-friendly interface for sending messages, managing contacts, and interacting with the blockchain.

## Features

- **Decentralized Messaging**: Send and receive messages securely through Ethereum smart contracts
- **User Authentication**: Connect with MetaMask wallet for secure authentication
- **Contact Management**: Add and manage friends using their Ethereum addresses
- **Real-time Updates**: Refresh functionality to get the latest messages
- **User-friendly Interface**: Clean and intuitive UI with a beautiful gradient background

## Tech Stack

- **Frontend**: React.js with React Bootstrap for UI components
- **Blockchain Integration**: Ethers.js for Ethereum interaction
- **Smart Contract**: Solidity (Database.sol)
- **Authentication**: MetaMask wallet integration

## Prerequisites

- Node.js and npm installed
- MetaMask browser extension installed
- An Ethereum account with some test ETH (for testnet deployment)

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/RameshSapkota435/blockchain.git
   cd Decentralised-chatting-app-main
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Connect your MetaMask wallet when prompted

## Usage

1. **Connect Wallet**:
   - Click the "Connect" button in the navbar
   - Approve the MetaMask connection

2. **Add New Chat**:
   - Click the "+ NewChat" button
   - Enter friend's Ethereum address and name
   - Click "Add Friend"

3. **Send Messages**:
   - Select a friend from the chat list
   - Type your message in the input field
   - Click "Send" or press Enter

4. **Refresh Messages**:
   - Click the "Refresh" button to get latest messages

## Smart Contract

The chat application uses a smart contract (Database.sol) deployed on the Ethereum network. The contract handles:
- User registration and existence checks
- Friend list management
- Message storage and retrieval

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.