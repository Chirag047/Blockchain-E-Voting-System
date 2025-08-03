# 🗳️ Blockchain-Based E-Voting System

A secure and cost-effective electronic voting system built using **Blockchain**, **ReactJS**, **MongoDB**, and **Twilio**, designed to ensure tamper-proof voting with reduced gas costs and enhanced voter authentication.

---
> 📄 **Note:** This project is part of a larger research work **currently under review** for publication in an international SCIE-indexed journal. Due to publication ethics, the complete source code cannot be made public at this time.

## 📌 Project Highlights

- 🔐 **Two-Factor Authentication** using **MongoDB** (user database) and **SMS API** for OTP verification.
- ⛓️ **Blockchain Integration** using **Ethereum Smart Contracts** hosted via **Remix IDE** and tested on **Ganache** local blockchain.
- 💻 **Web Application** developed with **ReactJS** for a clean, responsive user interface.
- ⚙️ **Smart Contract Optimization** using the **SOPES** tool for lower gas fees and improved execution.

---

## ⚙️ Architecture Overview

### Step 1: User Authentication

- The system uses a **Two-Factor Authentication (2FA)** mechanism:
  - First, the user credentials are validated via a **MongoDB**-based login system.
  - Then, an OTP is sent to the user's registered mobile number via **SMS API** for SMS-based verification.

### Step 2: Vote Casting via Blockchain

- After authentication, voters can cast their votes through a **ReactJS** frontend.
- The vote is recorded as a hashed transaction on the **Ethereum blockchain** (via **Ganache** local Ethereum chain).
- The smart contracts responsible for vote casting and verification are deployed and tested using **Remix IDE**.

### Step 3: Vote Hash Storage and Tally

- Votes are hashed and stored immutably on the blockchain.
- Smart contracts ensure:
  - One vote per user.
  - Tallying without revealing voter identity.
  - Prevention of data manipulation or replay attacks.

---

## 📈 Key Contributions & Results

- 🛡️ Developed a secure **Blockchain-based E-Voting System**, enabling **cost-optimized** voting by reducing gas fees through analysis of **50 smart contract datasets**.
- 📚 Published (under review) in a **SCIE-indexed journal**, focusing on **gas optimization** and **tamper-proof architecture**, with recognition from **IIT Indore**.
- 🧠 Reduced **voting tampering by 90%** and **gas costs by 45%** using smart contract optimization via the **SOPES tool**, as proposed in my **16th ICCCNT 2025 International Conference** paper.

---

## 🧪 Technologies Used

| Tech Stack          | Description                                      |
|---------------------|--------------------------------------------------|
| ReactJS             | Frontend web interface                           |
| Node.js + Express   | Backend and API endpoints                        |
| MongoDB             | Voter credentials and OTP tracking               |
| Twilio API          | OTP SMS verification                             |
| Solidity            | Smart contracts for voting logic                 |
| Ganache             | Local Ethereum blockchain network for testing    |
| Remix IDE           | Smart contract development and deployment        |
| SOPES               | Smart contract optimization tool                 |

---

> 🚀 Stay tuned! The full codebase, along with deployment scripts and detailed documentation, will be released here upon publication acceptance.

