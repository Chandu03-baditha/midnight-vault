# 🌙 Midnight Vault

> **Privacy-first decentralized note storage on Midnight.**

![Midnight](https://img.shields.io/badge/Midnight-Network-blue)
![Compact](https://img.shields.io/badge/Compact-Smart%20Contracts-success)
![Node.js](https://img.shields.io/badge/Node.js-22+-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 📖 Overview

Midnight Vault is a privacy-first decentralized application built on the Midnight Network using Compact smart contracts.

The project demonstrates how developers can build applications that protect user privacy while still leveraging blockchain technology. Instead of exposing user information by default, Midnight Vault uses Compact's privacy-first programming model to securely handle user data and explicitly control what is disclosed.

This project was developed as part of the **New Moon to Full: Monthly Moonshots on Midnight** builder program.

---

# 🎯 Problem Statement

Traditional public blockchains expose application data to everyone. This creates challenges for applications that require user privacy, such as personal notes, confidential records, or sensitive information.

Users should not have to sacrifice privacy simply to benefit from blockchain technology.

---

# 💡 Solution

Midnight Vault demonstrates a privacy-first approach using the Midnight Network.

The application allows users to store personal notes using Compact smart contracts while showcasing Midnight's privacy features such as:

- Opaque data types
- Privacy-preserving circuits
- Explicit disclosure through `disclose()`
- Secure ledger state management

---

# ✨ Current Features

- Store private notes using a Compact smart contract
- Read stored notes from the blockchain
- Interactive CLI for contract interaction
- Wallet integration
- Local Midnight Devnet deployment
- Docker-based development environment
- Compact contract compilation and deployment

---

# 🛠 Technology Stack

| Technology | Purpose |
|------------|---------|
| Midnight Network | Privacy-first blockchain |
| Compact | Smart contract language |
| TypeScript | CLI and deployment scripts |
| Node.js 22 | Runtime environment |
| Docker | Local Midnight Devnet |
| WSL2 | Development environment |
| Git | Version control |
| GitHub | Source code hosting |

---

# 📂 Project Structure

```
midnight-vault/
│
├── contracts/
│   ├── hello-world.compact
│   └── managed/
│
├── src/
│   ├── cli.ts
│   ├── deploy.ts
│   ├── setup.ts
│   ├── wallet.ts
│   └── network.ts
│
├── docker-compose.yml
├── package.json
├── README.md
└── .midnight-state.json
```

---

# ⚙️ Installation

Clone the repository.

```bash
git clone https://github.com/Chandu03-baditha/midnight-vault.git

cd midnight-vault
```

Install dependencies.

```bash
npm install
```

---

# 🚀 Compile the Smart Contract

```bash
npm run compile
```

---

# 🚀 Deploy the Smart Contract

```bash
npm run setup
```

This command will:

- Start the Midnight Local Devnet
- Start Docker services
- Compile the Compact contract
- Create a wallet
- Deploy the smart contract

---

# 💻 Run the Application

```bash
npm run cli
```

Available operations:

```
1. Store a private note
2. Read current note
3. Check wallet balance
4. Exit
```

---

# 🔒 Privacy Model

Midnight Vault demonstrates the core privacy concepts of the Midnight Network.

## Opaque

Sensitive user input is represented using the `Opaque` type, preventing accidental exposure during execution.

## Ledger

The ledger stores contract state on the Midnight blockchain.

## Circuit

Business logic is implemented using Compact circuits, enabling secure and privacy-aware execution.

## disclose()

The `disclose()` function explicitly controls which values become public ledger data, giving developers precise control over information visibility.

---

# 🧠 Smart Contract

The current contract supports:

- Storing a private note
- Reading stored note data
- Deploying on Midnight Local Devnet
- Wallet interaction through the CLI

---

# 🚧 Roadmap

## ✅ Level 1

- Environment setup
- Compact compiler installation
- Smart contract development
- Local deployment
- CLI interaction
- GitHub repository

## 🔜 Level 2

- React frontend
- Smart contract integration
- Improved user experience

## 🔜 Future Vision

Midnight Vault will evolve into a complete privacy-first decentralized notes application featuring:

- Multiple note management
- User-friendly interface
- Wallet-based authentication
- Mainnet deployment
- Production-ready architecture

---

# 🌍 Why Midnight?

Midnight was chosen because it provides:

- Privacy-first blockchain architecture
- Compact smart contract language
- Zero-knowledge proof support
- Developer-friendly privacy model

These capabilities make Midnight well suited for building decentralized applications that require confidentiality without sacrificing blockchain security.

---

# 👨‍💻 Author

**Baditha Chandu**

GitHub:

https://github.com/Chandu03-baditha

---

# 🙏 Acknowledgements

- Midnight Network
- Compact Language
- Midnight Developer Documentation
- New Moon to Full: Monthly Moonshots on Midnight Builder Program

---

# 📄 License

This project is licensed under the MIT License.