# MediTrust - Blockchain Medical Records Platform

MediTrust is a secure blockchain-based application for managing medical records. Patients control their health data while providers access information with permission.

## Features

- **Blockchain Security**: Store medical records securely on the blockchain
- **Patient Control**: Patients decide who can access their records
- **Dual Interfaces**: Separate dashboards for patients and healthcare providers
- **MetaMask Integration**: Connect with MetaMask wallet or use demo mode
- **Responsive Design**: Modern interface that works on all devices

## Technology Stack

- Next.js 15
- React 19
- Tailwind CSS
- Ethers.js
- MetaMask SDK

## Getting Started

### Prerequisites

- Node.js 18+ and npm
- MetaMask wallet extension (optional for testing)

### Installation



1. Install dependencies
```bash
npm install --legacy-peer-deps
```

2. Run the development server
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

## Usage

- **Connect Wallet**: Click "Connect Wallet" to authenticate using MetaMask or demo mode
- **Select Role**: Choose between patient or healthcare provider
- **Dashboard**: Access your personalized dashboard based on role
- **Upload Records**: (Patient) Add medical documents securely
- **View Records**: (Doctor) Browse authorized patient records
