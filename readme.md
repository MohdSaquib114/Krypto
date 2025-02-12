# Ethereum Exchange DApp

## Overview
This project is a **Decentralized Application (DApp)** that enables secure and seamless **Ethereum transfers** between users. The application consists of two main components:

- **Client**: The frontend built using **React.js and Next.js** for an intuitive user experience.
- **Smart Contracts**: Ethereum **Solidity-based smart contracts** deployed on the blockchain to handle transactions securely.

## Features
- Secure and decentralized **peer-to-peer Ethereum exchange**.
- **MetaMask wallet integration** for seamless transactions.
- **Smart contracts** deployed on the Ethereum blockchain.
- **Real-time transaction tracking**.
- **Responsive UI** for an optimal user experience.



## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- **Node.js** (Latest LTS version)
- **Hardhat** (For smart contract development)
- **MetaMask** (For Ethereum transactions)
- **Alchemy API** (Optional for deploying contracts)

### Setup Steps
1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/ethereum-exchange-dapp.git
   cd krypto
   ```
2. **Install dependencies**
   ```sh
   cd client && npm install
   cd ../smart-contract && npm install
   ```
3. **Run the development server**
   ```sh
   cd client
   npm run dev
   ```
4. **Deploy smart contracts**
   ```sh
   cd smart-contract
   npx hardhat run scripts/deploy.js --network goerli
   ```
5. **Connect MetaMask & Start Transacting!**

## Smart Contract Deployment
- Uses **Hardhat** for local blockchain testing and deployments.
- **Ethereum Testnets Supported**: Goerli, Sepolia.
- Deploy contracts using:
  ```sh
  npx hardhat run scripts/deploy.js --network goerli
  ```

## Contributing
1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a **Pull Request**.

## License
This project is licensed under the **MIT License**.



