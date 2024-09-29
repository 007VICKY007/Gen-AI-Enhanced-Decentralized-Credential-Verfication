
# Generative AI-Enhanced Decentralized Credential Verification System

This project aims to provide a decentralized, secure, and efficient platform for managing, verifying, and sharing academic and professional credentials using cutting-edge technologies like blockchain, NFTs, and generative AI.

## Problem Statement

Traditional credential verification is often time-consuming, prone to manipulation, and lacks transparency. Our system addresses these issues by using a decentralized approach, enabling secure storage, issuance, and verification of credentials while offering personalized career insights through AI recommendations.

## System Architecture

### Frontend:
- **Framework**: React.js
- **State Management**: Redux
- **API Handling**: Axios

### Backend:
- **Framework**: Node.js with Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)

### Blockchain Integration:
- **Smart Contracts**: Written in Solidity and deployed on the Polygon network
- **Interaction Library**: Web3.js

### AI Integration:
- **Model**: OpenAI’s GPT
  

## Key Features
- **Decentralized Credential Issuance and Verification**: Using smart contracts on the Polygon network.
- **NFT-Based Credentials**: Representing credentials as NFTs for secure and verifiable ownership.
- **Generative AI for Personalized Career Recommendations**: Analyzes user profiles to offer career guidance.
- **User Dashboard**: Real-time updates on the status of credentials.
- **Secure Authentication**: Role-based access control for secure platform interaction.

## Tech Stack
- **Frontend**: React.js, Redux, Material-UI
- **Backend**: Node.js, Express.js, MongoDB, JWT
- **Blockchain**: Polygon Network, Solidity, Web3.js
- **AI Integration**: OpenAI's GPT model
- **Workflow Orchestration**: Orkes Conductor

# Team Members 
  ## Akshayaa S | Dharshini R | Naresh Raja M L | Vignesh Pandiya G | Vimal Srinivasan R

## Prerequisites
- [Node.js (v14+)](https://nodejs.org/)
- [MongoDB (v4.4+)](https://www.mongodb.com/)
- [MetaMask Extension](https://metamask.io/)
- [Ganache](https://trufflesuite.com/ganache/)
- [Verbwire API Key](https://verbwire.com/)
- [Truffle](https://www.trufflesuite.com/truffle) or [Hardhat](https://hardhat.org/) for smart contract deployment

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/credential-verification-system.git
cd credential-verification-system
```

### 2. Install Dependencies

#### Frontend
```bash
cd frontend
npm install
```

#### Backend
```bash
cd ../backend
npm install
```

### 3. Environment Variables
Create an `.env` file in both `frontend` and `backend` directories with the following variables:

#### Backend `.env`:
```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
VERBWIRE_API_KEY=your_verbwire_api_key
POLYGON_RPC_URL=your_polygon_rpc_url
CONDUCTOR_API_URL=your_orkes_conductor_api_url
CONDUCTOR_API_KEY=your_orkes_conductor_api_key
```

#### Frontend `.env`:
```bash
REACT_APP_BACKEND_URL=http://localhost:5000
REACT_APP_WEB3_PROVIDER_URL=your_web3_provider_url
```

### 4. Smart Contract Deployment
Deploy the smart contracts using Truffle or Hardhat:

```bash
# Install Truffle globally
npm install -g truffle

# Navigate to the smart-contracts directory
cd ../smart-contracts

# Compile and deploy contracts to local blockchain (Ganache)
truffle compile
truffle migrate --network development
```

### 5. Initialize MongoDB Database
Start MongoDB on your local machine or connect to a remote MongoDB server:

```bash
# Start MongoDB
mongod --dbpath /path_to_your_database_folder
```

### 6. Verbwire Configuration
Ensure you have set up the `VERBWIRE_API_KEY` in your backend `.env` file for NFT creation and handling.

## Running the Project

### Start Backend Server
```bash
cd backend
npm start
```

### Start Frontend Server
```bash
cd ../frontend
npm start
```

## Directory Structure
```bash
credential-verification-system/
├── backend/                 # Backend server code
│   ├── controllers/         # Controller logic for handling API routes
│   ├── models/              # MongoDB schemas
│   ├── routes/              # API routes
│   ├── middleware/          # Custom middleware (auth, error handling)
│   └── server.js            # Main server entry point
├── frontend/                # Frontend React application
│   ├── src/
│   │   ├── components/      # React components
│   │   ├── pages/           # Page components
│   │   ├── services/        # API service calls
│   │   └── App.js           # Main React entry point
├── smart-contracts/         # Smart contract code (Solidity)
│   ├── contracts/           # Solidity contracts
│   ├── migrations/          # Deployment scripts
│   └── truffle-config.js    # Truffle configuration file
└── README.md                # Project documentation
```

## Troubleshooting
- **MetaMask Issues**: Ensure MetaMask is connected to the correct network.
- **Smart Contract Errors**: Recompile and redeploy the contracts if there are ABI changes.
- **API Endpoint Errors**: Verify that environment variables are correctly configured.

## Contributing
Contributions are welcome! Please feel free to open issues or submit pull requests for any suggestions or improvements.

## License
This project is licensed under the [Team Martians License](LICENSE.md).

## Important Note
The project cannot run without proper installation of dependencies. If any required package is missing, the project will not function as expected. Ensure all the prerequisites and configurations are correctly set up before running the project.

# screen shots of the project

![Screenshot 2024-09-29 141030](https://github.com/user-attachments/assets/e08bafdf-41dd-45a3-96f1-1ba93e03b2ae)
![Screenshot 2024-09-29 141046](https://github.com/user-attachments/assets/2b7bd214-c589-4f74-ae37-0ad9b1a2cf69)
![Screenshot 2024-09-29 141109](https://github.com/user-attachments/assets/ce6f3142-02e7-4ef7-a04b-7a5c1be06d5a)
![Screenshot 2024-09-29 140800](https://github.com/user-attachments/assets/99a6d2b5-2899-4861-881c-e877a8fea67c)

---![Screenshot 2024-09-29 140923](https://github.com/user-attachments/assets/e507320e-6779-4d53-aa5d-09e6db038d42)
![Screenshot 2024-09-29 140936](https://github.com/user-attachments/assets/39c43603-5739-4676-8bee-ca7ff3def56a)
![Screenshot 2024-09-29 141001](https://github.com/user-attachments/assets/1b75c042-3c69-47d2-90dd-98c3fd781f27)
![Screenshot 2024-09-29 141012](https://github.com/user-attachments/assets/1a0b599c-a9f5-4618-bc9c-5d7b76506f6e)
![Screenshot 2024-09-29 141020](https://github.com/user-attachments/assets/e20f9eba-8ceb-4c96-a2b7-e5662cdb959a)

