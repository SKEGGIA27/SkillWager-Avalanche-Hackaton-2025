# 🏆 SkillWager - Avalanche Hackathon

**SkillWager** is a decentralized platform that allows users to bet on their own skills. This project was developed during the Avalanche Hackathon.

### 🥈 Achievement
The project won **2nd Place** in the Avalanche Hackathon!

---

## 👥 The Team

The project was built by:
* **[@SKEGGIA27](https://github.com/SKEGGIA27)**
* **[@alesandu](https://github.com/alesandu)**
* **[@leleventii](https://github.com/leleventii)**
* **[@m4tteo6](https://github.com/m4tteo6)**

---

## 📂 Project Structure

The repository is organized as a monorepo containing the three main components of the application: Smart Contracts (managed with Foundry), Frontend (Next.js), and Backend (Node.js).

```text
.
├── src/                  # Smart Contracts (Solidity)
│   └── SkillWager.sol    # Main contract logic
├── script/               # Deployment and automation scripts
│   └── DeploySkillWager.s.sol
├── frontend/             # Web Application (Next.js 14+)
│   ├── src/app/          # Pages (Home, Create Match, Jury, etc.)
│   ├── src/components/   # UI Components (ChatBox, MatchList, etc.)
│   └── public/           # Static assets
├── backend/              # Backend Server
│   └── server.js         # Node.js server entry point
├── foundry.toml          # Foundry configuration
└── package.json          # Root dependencies
