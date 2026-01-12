# TrustFund: Decentralized Crowdfunding Platform 🏦💸

TrustFund is a decentralized crowdfunding (fundraising) platform built on **blockchain technology** that ensures transparency, trust, and fairness between project owners and contributors.  
It uses **smart contracts** to manage funds, deadlines, and withdrawal approvals, eliminating the need for intermediaries.

---

## 📌 Project Overview

Traditional crowdfunding platforms rely on centralized authorities, which can lead to misuse of funds and lack of transparency.  
**TrustFund** solves this by leveraging **Ethereum smart contracts**, ensuring that:

- Funds are only withdrawn with contributor approval
- Contributors are protected if a project fails
- All transactions are verifiable on-chain

---

## 🚀 Project Demo / Preview

https://github.com/user-attachments/assets/63855945-949c-4aac-9169-76db2e7f1abb

---

## 📌 Project Overview

Traditional crowdfunding platforms rely on centralized authorities, which can lead to misuse of funds and lack of transparency.  
**TrustFund** solves this by leveraging **Ethereum smart contracts**, ensuring that:

- Funds are only withdrawn with contributor approval
- Contributors are protected if a project fails
- All transactions are verifiable on-chain

---

## ✨ Features

- ✅ Create a fundraising campaign
- ✅ Anyone can contribute using a crypto wallet
- ✅ Campaign ends automatically when the target is reached
- ✅ Campaign expires if the target is not met before the deadline
- ✅ Contributors can withdraw their funds if the campaign fails
- ✅ Campaign owner must request withdrawal approval
- ✅ Owner can withdraw funds only if **50% of contributors approve**
- ✅ Secure wallet connection (MetaMask)
- ✅ Fully decentralized and transparent

---

## 🛠️ Tech Stack

### Blockchain
- **Solidity** – Smart contract development
- **Hardhat** – Development & testing framework
- **Ethereum** – Blockchain network

### Frontend
- **Next.js** – React framework
- **JavaScript**
- **Web3 / Ethers.js** – Blockchain interaction

### Tools
- **MetaMask** – Wallet integration
- **Node.js & npm**

---

### How to run :runner: :

- Run hardhat node
    ```
    npx hardhat node
    ```
- Run test cases
    ```
    npx hardhat test
    ```
- Connect HardHat Account to Metamask
    - Import one of the Hardhat private keys into MetaMask
    - Set network to Localhost 8545
  

- Deploy contract in local hardhat node
    ```
    npx hardhat run scripts/deploy.js --network localhost
    ```
- Run Next.js frontend
    ```
    cd client
    npm run dev
    ```
- Connect account to  website

### Hardhat commands
```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/deploy.js
npx hardhat help
npx hardhat run scripts/deploy.js --network <network name>
```
