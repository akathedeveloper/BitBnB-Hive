# BitBNB - Decentralized Web Hosting Platform
## Overview
Welcome to BitBNB - a decentralized, blockchain-based web hosting platform built on Hive, IPFS, and the MERN stack (MongoDB, Express, React, Node.js). BitBNB provides a secure, fast, and scalable alternative to traditional web hosting, utilizing the power of decentralized storage and blockchain for enhanced data security, user privacy, and seamless scalability.

### Key Features
* Hive Keychain Authorization: BitBNB uses Hive Keychain for secure and decentralized user authentication.
* Decentralized Storage: Project files are stored on IPFS, while metadata is stored on Hive, ensuring immutability and data resilience.
* User Dashboard: Users can upload projects, view project details, and track transaction hashes.
* Wallet Flexibility: Users can register and log in with their preferred wallet (e.g., MetaMask, Hive Wallet).


__Advantages__: Enhanced security, fast content delivery, and easy scalability.

### Technology Stack
- Frontend: React, Hive Keychain
- Backend: Node.js, Express, MongoDB
- Blockchain and Decentralized Storage: __Hive__ Blockchain, IPFS

## Getting Started
### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- IPFS CLI (optional, but recommended)
- Hive Keychain (Chrome/Firefox extension)
- Wallets: Hive Keychain

### Clone the repository
```bash
git clone https://github.com/akathedeveloper/BitBnB-Hive.git
cd BitBnB-Hive
```
### Setup the `.env` file
```bash
// .env file
REACT_APP_PINATA_API_KEY=<API-KEY>
REACT_APP_PINATA_SECRET_API_KEY=<API-SECRET>
REACT_APP_IPFS_BACKEND_URL=http://localhost:8080/upload
```
- Navigate to `client`
```bash
cd client
```

### Install the depdendencies
```bash
npm install
```

### Run the application at `localhost:5173`
```bash
npm run dev
```
