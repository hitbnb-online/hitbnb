# HITBNB Token

**Official Website**: [https://hitbnb.online](https://hitbnb.online)

HITBNB is a BEP20-compliant token on the Binance Smart Chain designed with automated monthly vesting, ROI management, and decentralized wallet controls powered by Chainlink Automation. The token serves to align project stakeholders with long-term value through codified, time-based distributions. **HITBNB** is a decentralized reward-based protocol, designed to deliver sustainable ROI, referral incentives, and stacking plans to its community. With advanced automation, a clear reward structure, and full transparency, HITBNB empowers users to earn, participate, and grow in a 100% decentralized Web3 ecosystem.


---

## 🔢 Token Details

- **Token Name**: HITBNB  
- **Symbol**: HITBNB  
- **Total Supply**: 300,000 HITBNB  
- **Decimals**: 18  
- **Network**: Binance Smart Chain (BEP20)  
- **Contract Version**: v1.0.0  
- **Solidity Version**: ^0.8.20  

---

## 🔐 Locked Wallet Vesting

**Locked Wallet Address**:  
[`0x933AFa970a7e03f87c8e1a495acd3D9fe9ECb523`](https://bscscan.com/address/0x933AFa970a7e03f87c8e1a495acd3D9fe9ECb523)

- 100,000 HITBNB tokens are locked at deployment.
- Every **30 days**, 1,000 HITBNB tokens are automatically released and distributed as follows:
  - `500 HITBNB` → ROI Wallet  
  - `50 HITBNB` → Development Wallet  
  - `350 HITBNB` → Marketing Wallet  
  - `100 HITBNB` → Shareholders Wallet

This is executed autonomously by **Chainlink Automation**.

---

## 🏦 ROI Wallet Cap Management

**ROI Wallet Address**:  
[`0x38fE56b85e3199C1C577C12e6A09532c5892dbaD`](https://bscscan.com/address/0x38fE56b85e3199C1C577C12e6A09532c5892dbaD)

- Initially receives 110,000 HITBNB.
- If this wallet’s balance exceeds **110,000 HITBNB**, the surplus is automatically returned to the Locked Wallet.

---

## 🧩 Supporting Wallets

| Purpose        | Wallet Address                                                                 |
|----------------|----------------------------------------------------------------------------------|
| Development    | [`0xE05faf1cE53715fb476db9c98DBE5b1B245E541D`](https://bscscan.com/address/0xE05faf1cE53715fb476db9c98DBE5b1B245E541D) |
| Marketing      | [`0x802F659C42Be0f713110C4E3C084D2F74bD81b77`](https://bscscan.com/address/0x802F659C42Be0f713110C4E3C084D2F74bD81b77) |
| Shareholders   | [`0x2a86AFC0B25AD1DF42baf70f081F6A6d85eed154`](https://bscscan.com/address/0x2a86AFC0B25AD1DF42baf70f081F6A6d85eed154) |

---

## ⚙️ Chainlink Automation

HITBNB leverages **Chainlink Keepers** (Automation) to:
- Check monthly time intervals
- Execute vesting and distribution
- Rebalance ROI wallet if above cap

This removes the need for manual or centralized control, enforcing full decentralization.

---

## 🛡️ Audit

📄 [Download Audit Report (Coming Soon)](https://hitbnb.online/audit.pdf)

---

## 📚 Documentation

🔗 Full Developer & User Docs: [https://hitbnb.gitbook.io/doc](https://hitbnb.gitbook.io/doc)

## 🧩 Key Components

- **HITBNB Token** – BEP-20 token with built-in reward logic
- **HITBNB Vault** – Manages user claimable rewards and distributions
- **HITBNB Buyer** – Automatically converts USDT to HITBNB for ROI Pool
- **Referral & Staking Engine** – 18-level system with daily ROI and bonus plans
- **Decentralized Node Hosting** – Community can run nodes and earn rewards
- **HITBNB Scan** – Unified explorer for all DApp & contract transactions (upcoming)

## 🏗️ Tech Stack

- Solidity `^0.8.24`
- OpenZeppelin (UUPS Upgradeable)
- PHP 8.3 + node (backend scripts )
- Laravel + React (frontend)
- Chainlink Keepers / VPS Automation
- Bitquery API for off-chain holder data

## 🔐 Smart Contracts

| Contract      | Description                            | Address |
|---------------|----------------------------------------|---------|
| HITBNB Token  | Main BEP-20 token with emission logic  | `0x658310C8219B1a92773523e52ca84b55fb333f43` |
| HITBNB Vault  | Handles pending claims & withdrawals   | `0x7de1d440a20b3fd16658ad619201eee91ac07de8` |
| HITBNB Buyer  | Buys HITBNB via PancakeSwap & routes   | `0x69b2299add358ac8a6c01d85360fe4d476edbe24` |

## 🛠️ Installation (for Devs)

```bash
git clone https://github.com/yourorg/hitbnb.git
cd hitbnb
# Smart contracts
npm install   # or yarn install
# Run tests or compile
npx hardhat compile


## 📜 License

MIT License  
© 2024 HITBNB Project

---

## 🧑‍💻 Author / Maintainers

**HITBNB Team**  
🌐 [https://hitbnb.online](https://hitbnb.online)  
📧 [Contact Us](https://hitbnb.online/contact)

---

## 🧠 Contributions & Feedback

We welcome feedback, audits, and security reviews. Please open an issue or contact the team directly for collaboration or integration ideas.
