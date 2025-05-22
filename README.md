## 📄 Overview
VeriLedger is a decentralized platform designed to securely issue, manage, and verify academic documents using blockchain technology. By leveraging the immutability and transparency of blockchain, VeriLedger ensures that academic credentials are tamper-proof and easily verifiable by authorized parties.

## 🚀 Features
- Immutable Record Keeping: Stores academic documents on the blockchain, ensuring data integrity and preventing unauthorized modifications.

- Decentralized Verification: Allows employers, institutions, and other stakeholders to verify academic credentials without intermediaries.

- User-Friendly Interface: Provides an intuitive UI for students, institutions, and verifiers to interact with the system seamlessly.

- Smart Contract Integration: Utilizes Ethereum smart contracts to automate the issuance and verification processes.

- Secure Access Control: Implements role-based access to ensure that only authorized users can perform specific actions.

## 🛠️ Technology Stack

- Frontend: React.js

- Backend: Node.js with Express.js

- Blockchain Platform: Ethereum

- Smart Contracts: Solidity

- Development Framework: Hardhat

- Database: MongoDB

- Authentication: JSON Web Tokens (JWT)

- Storage: IPFS for decentralized file storage

## 🧰 Prerequisites
Before setting up the project, ensure you have the following installed:

- Node.js (v14 or above)

- npm

- Hardhat

- MongoDB

- MetaMask browser extension

## ⚙️ Installation & Setup

### Clone the Repository

```
git clone https://github.com/your-username/VeriLedger-Blockchain-Enabled-Academic-Document-Validation-Platform.git
cd VeriLedger-Blockchain-Enabled-Academic-Document-Validation-Platform
```

### Install Dependencies

```
npm install
```

### Configure Environment Variables
Create a .env file in the root directory and add the following:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

### Deploy Smart Contracts to Local Blockchain
Start a local Hardhat node:
```
npx hardhat node
```

### Start the Backend Server
```
npm run server
```

### Start the Frontend Application
```
npm start
```

### Access the Application
[Visit the local application](http://localhost:3000)



## 👥 User Roles
- Administrator: Manages institutions and oversees the platform.

- Institution: Issues academic documents to students.

- Student: Receives and shares academic credentials.

- Verifier: Validates the authenticity of academic documents.

## 📂 Project Structure
```
├── contracts          # Solidity smart contracts
├── scripts            # Deployment scripts for smart contracts
├── client             # React frontend application
├── server             # Express backend server
├── models             # Mongoose schemas for MongoDB
├── routes             # API route handlers
├── middleware         # Authentication and authorization middleware
├── utils              # Utility functions
├── .env               # Environment variables
├── package.json       # Project metadata and dependencies
└── README.md          # Project documentation
```
 ![image](https://github.com/user-attachments/assets/f003d5f7-d8e0-49a2-bb51-534bc4481e51)
## 📄 License
This project is licensed under the MIT License.
