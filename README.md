# HerNet 💖

**The first fully decentralized blockchain built by girls, for girls.**

HerNet is a Layer-1 blockchain protocol designed to empower women and girls through a secure, scalable, and inclusive decentralized infrastructure. Built with accessibility and transparency in mind, HerNet leverages modern consensus mechanisms and lightweight client support to enable anyone — from creators to coders — to build, transact, and thrive.

---

## ✨ Features

- ✅ Fully decentralized consensus (PoS + zkRollup support)
- ✅ Gas-optimized smart contracts
- ✅ Integrated NFT & identity layer
- ✅ Mobile-first lightweight clients
- ✅ Community-first governance (DAO)
- ✅ HerNode — run a node with 1-click UX
- ✅ HerWallet — secure wallet with gender-inclusive UX

---

## ⚙️ Architecture


---

## 📦 Installation

### Prerequisites

- Node.js >= 18.x
- Docker
- Git

### 1. Clone the repo

```bash
git clone https://github.com/herset/hernet.git
cd hernet


docker-compose up --build


// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract HerMessage {
    string public message = "Slay on-chain.";

    function setMessage(string calldata _msg) external {
        message = _msg;
    }
}
