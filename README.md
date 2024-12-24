# ENS Name Fetcher

This project is a simple ENS (Ethereum Name Service) Name Fetcher built using **Next.js**, **RainbowKit**, and **Reown WalletConnect**. The application fetches and displays the ENS name for a given Ethereum address. If no ENS name is associated with the address, it defaults to showing the address itself.

This project was developed as a practice tutorial from [LearnWeb3.io](https://learnweb3.io).

## Features

- Fetches ENS name for a given Ethereum address.
- Displays the Ethereum address if no ENS name is found.
- Integrates with Ethereum wallets via WalletConnect.
- User-friendly interface using RainbowKit.

## Tech Stack

- **Next.js**: Framework for building the frontend.
- **RainbowKit**: For wallet connection UI and interactions.
- **Reown WalletConnect**: For seamless wallet integration.

## Prerequisites

To run this project locally, ensure you have the following:

- **Node.js** (v16 or later)
- **npm** or **yarn** installed on your machine

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/Eth-Name-Service.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Eth-Name-Service
   ```

3. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

## Usage

1. Start the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

2. Open your browser and navigate to `http://localhost:3000`.

3. Connect your Ethereum wallet using the WalletConnect integration.

4. Enter an Ethereum address in the input field to fetch its ENS name.

## Learnings

Through this project, I learned:

- How to integrate RainbowKit and WalletConnect with a Next.js application.
- How to fetch ENS names using web3 libraries.
- Best practices for building Ethereum-connected web apps.

## Acknowledgments

- [LearnWeb3.io](https://learnweb3.io) for the tutorial and guidance.
- The creators of RainbowKit and WalletConnect for their fantastic tools.
