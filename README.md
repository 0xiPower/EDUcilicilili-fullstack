# EDUcilicili  
*Decentralized Education Content Sharing & Incentive Platform*

---

## 1. Core Objectives 🎯
- **Democratize Education**: Enable global access to quality educational content via blockchain.
- **Creator Incentives**: Reward educators with EDU tokens based on student ratings and content sales.
- **Immutable Ownership**: Securely mint courses as NFTs to prove authenticity and ownership.
- **Transparent Economy**: Eliminate middleman fees with direct peer-to-peer transactions on EDU Chain.

---

## 2. Technical Architecture 🛠️
### System Layers
| Layer               | Technology Stack          | Description                          |
|---------------------|---------------------------|--------------------------------------|
| **Smart Contracts** | Solidity, OpenZeppelin     | ERC-1155 NFTs, token reward logic    |
| **Frontend**        | React, Ethers.js, Ant Design | User dashboard & NFT marketplace     |
| **Storage**         | IPFS, web3.storage         | Decentralized course file hosting    |
| **Oracle**          | Chainlink (simulated)      | Off-chain rating data integration    |

### Key Contracts
- **CourseNFT.sol**: Manages course minting/trading (ERC-1155 standard).
- **RewardToken.sol**: Distributes EDU rewards based on ratings.

---

## 3. Highlight Features ✨
- **One-Click NFT Minting**:  
  Educators upload content to IPFS and mint courses as NFTs in <2 minutes.
- **Token-Gated Access**:  
  Students purchase NFTs using MetaMask; ownership unlocks content access.
- **Dynamic Rewards**:  
  Real-time token rewards for creators when ratings exceed a threshold.
- **Anti-Piracy Proof**:  
  All content hashes stored on-chain to verify authenticity.

---

## 4. Future Extensions (Bonus Tracks) 🚀
- **DAO Governance**:  
  Let token holders vote on platform upgrades via Snapshot.
- **AI-Powered Curation**:  
  Integrate OpenAI to auto-generate course summaries and learning paths.
- **Cross-Chain Portability**:  
  Bridge EDU tokens to Ethereum/Polygon for broader accessibility.
- **Gamified Learning**:  
  Issue Soulbound Tokens (SBTs) as achievement badges.

---

## 5. Project Progress 📌
| Phase       | Status     | Milestone                           |
|-------------|------------|-------------------------------------|
| **Phase 1** | Completed  | ERC-1155 contract deployed on EDU Testnet |
| **Phase 2** | In Progress| React frontend + IPFS upload integration |
| **Phase 3** | Planned    | Oracle-based rating simulation      |
| **Phase 4** | Planned    | DAO governance prototype            |

---

## Getting Started 🚀
1. Clone the repo:  
   `git clone https://github.com/0xiPower/EDUcilicili-fullstack.git`
2. Install dependencies:  
   `npm install`
3. Start local node:  
   `npx hardhat node`
4. Deploy contracts:  
   `npx hardhat run scripts/deploy.js --network localhost`

---

## Contribute 🤝  
Open to all contributions! Priority areas:  
- UI/UX improvements for course marketplace  
- Chainlink Oracle integration tutorials  
- Unit test coverage expansion  
