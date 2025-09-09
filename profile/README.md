# 🌐 Auctra

> **Redefine DeFi with RWA DomainFi — Auction, Rent, Borrow, All with Your Domain.**

Auctra is a decentralized protocol on the **Doma Network** that transforms domain names into on-chain financial assets.  
With Auctra, domains are more than digital identities. They become assets that can be collateralized, rented, and auctioned.

---
<img width="1920" height="1080" alt="Screenshot 2025-09-09 at 22 15 23" src="https://github.com/user-attachments/assets/cfaf9673-8f51-45fb-ac35-31cd9afbe37b" />
<img width="1906" height="995" alt="image" src="https://github.com/user-attachments/assets/2cce6961-6658-4154-bcf2-cd4dc4b69d57" />


---

## 🧩 Hackathon Contribution

### How We Used **Doma**

Auctra leverages the **Doma Testnet Network** and its **Subgraph documentation** to fetch on-chain metadata such as domain names, token IDs, and expiration dates of domains tokenized by Doma into NFTs.  
These tokenized assets serve as the foundation for the protocol’s financial ecosystem, enabling domains to be:

- Auctioned in **English, Dutch, or Sealed Bid formats**  
- Rented out to other users  
- Supplied as collateral to **borrow USDC**  
- Actively traded and integrated with the Auctra marketplace  

By building directly on Doma’s infrastructure, we ensure **seamless integration with domain NFTs as RWA (Real-World Assets)** in DeFi.

---

### How Our Submission Addresses the Track Goals

**Selected Track:** *Track 1: On-Chain Auctions & Price Discovery*

Auctra directly advances the goals of this track by:

- **Innovating Auction Mechanisms**: Supporting **Dutch and Sealed Bid auctions** in addition to traditional English auctions, offering multiple price discovery strategies for premium and expiring domains.  
- **Transparent Price Discovery**: All auctions are executed on-chain with **smart contracts**, ensuring fairness, verifiability, and eliminating asymmetry between sellers and buyers.  
- **Boosting Participation & Fees**: By gamifying the auction process (descending prices in Dutch, hidden commitments in Sealed Bid), the protocol encourages higher engagement, more transactions, and greater fee generation for the ecosystem.  
- **RWA Integration**: Domains tokenized by Doma become usable financial assets — bridging traditional web assets (domains) with DeFi-native mechanics.  

This submission demonstrates how **on-chain auctions can unlock new financial use cases for tokenized domains**, perfectly aligned with the hackathon’s focus on price discovery and participation.

## 🔑 Key Features

- **Domain Auctions**: English, Dutch, and Sealed Bid  
- **Domain Collateralization**: Borrow USDC against tokenized domains  
- **Domain Renting**: List and rent domains with flexible terms  
- **Alert System**: Domain expiration and auction notifications  
- **History Tracking**: Full record of bids, rentals, and collateral usage  
- **Dashboard**: Unified user interface for managing all domain activities  

---

## 🛠️ Tech Stack

- **Blockchain**: Solidity, Doma Testnet  
- **Frontend**: Next.js 14, TypeScript, Tailwind, shadcn/ui  
- **State Management**: Jotai  
- **Indexer**: Ponder, GraphQL, PostgreSQL/SQLite  
- **Testing**: Hardhat

---

## 📜 Deployed Contracts on Doma Testnet

| Contract           | Address                                      | Explorer Link                                                                                |
| ------------------ | -------------------------------------------- | -------------------------------------------------------------------------------------------- |
| FeeManager         | `0xec709b51F24801243313F0931525fcAecFE30cEC` | [View](https://explorer-testnet.doma.xyz/address/0xec709b51F24801243313F0931525fcAecFE30cEC) |
| RegistrarBridge    | `0x964B0d2eA0896F694710b9f4a20290F470B7801D` | [View](https://explorer-testnet.doma.xyz/address/0x964B0d2eA0896F694710b9f4a20290F470B7801D) |
| EnglishAuction     | `0xA8083D094cCD8a4B0843C014Dc11AF7b97283906` | [View](https://explorer-testnet.doma.xyz/address/0xA8083D094cCD8a4B0843C014Dc11AF7b97283906) |
| DutchAuction       | `0xCB0c653f110e469B9d74DBCC3aD632e7B58454b0` | [View](https://explorer-testnet.doma.xyz/address/0xCB0c653f110e469B9d74DBCC3aD632e7B58454b0) |
| SealedBidAuction   | `0xDcD92889cDf7C0D56AD02da1e99bc9Dc022E033a` | [View](https://explorer-testnet.doma.xyz/address/0xDcD92889cDf7C0D56AD02da1e99bc9Dc022E033a) |
| DomainAuctionHouse | `0xCD6DD013877570678449E788ab4fb221d37d6f88` | [View](https://explorer-testnet.doma.xyz/address/0xCD6DD013877570678449E788ab4fb221d37d6f88) |
| MockUSDC           | `0xdA340408191fb16ab4FD83A28C3D344ab308b090` | [View](https://explorer-testnet.doma.xyz/address/0xdA340408191fb16ab4FD83A28C3D344ab308b090) |
| MockDomainOracle   | `0xDd868480112DcADb32364d933755eecb71D9262C` | [View](https://explorer-testnet.doma.xyz/address/0xDd868480112DcADb32364d933755eecb71D9262C) |
| LinearIRM          | `0x8Da107637428A1D4E5FACD84cB93225EFEc78108` | [View](https://explorer-testnet.doma.xyz/address/0x8Da107637428A1D4E5FACD84cB93225EFEc78108) |
| DomainLendingPool  | `0x133272720610d669Fa4C5891Ab62a302455585Dd` | [View](https://explorer-testnet.doma.xyz/address/0x133272720610d669Fa4C5891Ab62a302455585Dd) |
| DomainRentalVault  | `0x57Cf6d83589Da81DBB8fD99bcA48B64f52f89eA7` | [View](https://explorer-testnet.doma.xyz/address/0x57Cf6d83589Da81DBB8fD99bcA48B64f52f89eA7) |

---

## 🛠️ Technical Stack

- **Smart Contracts**: Solidity (Hardhat, Foundry)  
- **Network**: Doma Testnet (Chain ID: 97476)  
- **Frontend**: Next.js 14, TypeScript, Tailwind CSS, shadcn/ui  
- **State Management**: Jotai  
- **Indexing**: Ponder, GraphQL, PostgreSQL/SQLite  
- **Testing**: Vitest, Hardhat, Forge  
- **Infrastructure**: RPC via `https://rpc-testnet.doma.xyz`  

---

## 📂 Repositories

- [Frontend App](https://github.com/Auctra-DomaFi-Hackathon/auctra-frontend)  
- [Smart Contracts](https://github.com/Auctra-DomaFi-Hackathon/auctra-smart-contracts)  
- [Indexer](https://github.com/Auctra-DomaFi-Hackathon/auctra-indexer)  

---

## 🔗 Official Links

- **GitBook Documentation**: [Coming Soon]()  
- **Presentation Slides**: [Coming Soon]()  
- **Website**: [Coming Soon]()  
- **Demo Video**: [Coming Soon]()  
- **X (Twitter) Account**: [Coming Soon]()  

---

## 📜 License

All repositories are licensed under **MIT**.

---

✨ Join us in building the future of **RWA-powered DeFi with domains**.
