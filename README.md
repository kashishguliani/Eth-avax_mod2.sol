# Starter Next/Hardhat Project

After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/


# Crypto Bank App

Welcome to Kashish's Crypto Bank, a decentralized application (dApp) that interacts with Ethereum's blockchain. This dApp allows users to perform basic banking operations like depositing, withdrawing, transferring funds, and viewing transaction history.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Features

- Connect your MetaMask wallet to the dApp.
- Deposit and withdraw funds.
- Transfer funds to another Ethereum address.
- View transaction history.

## Getting Started

1. Clone this repository to your local machine.
2. Install project dependencies using the command: `npm install`.

## Usage

1. Deploy the Smart Contract:
   - Deploy the smart contract using your preferred Ethereum development environment.
   - Update the `contractAddress` and `atmABI` in the `CryptoBankPage.js` file.

2. Start the Application:
   - Run the application locally with the command: `npm start`.
   - Make sure your MetaMask wallet is installed and connected to the Ethereum network.

3. Interact with the dApp:
   - Deposit funds using the "Deposit 1 ETH" button.
   - Withdraw funds using the "Withdraw 1 ETH" button.
   - Transfer funds to another address using the "Transfer 1 ETH" button.
   - Access transaction history via the "Transaction History" button.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- Ethereum: A decentralized blockchain platform.
- ethers.js: A library for interacting with Ethereum.

## Acknowledgements

This project is for educational purposes and demonstrates basic interaction with a smart contract on the Ethereum blockchain.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
