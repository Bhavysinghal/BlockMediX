# 🎮 BlockMediX

> **Blockchain-based Discord bot system for selling gamer merchandise securely and easily**

BlockMediX is a smart-agent-based system that allows **online gamers and digital creators** to sell their **custom merchandise directly on Discord** using **secure blockchain transactions**.

Built using `uAgents`, `Cosmos blockchain`, and the `Discord API`, it features three intelligent agents that handle the entire buying and selling process — from listing items to confirming payments.

---

## 🧠 Core Components

### 🧾 `bot_agent.py`
- A Discord bot that:
  - Shows the catalog
  - Lets buyers place orders
  - Communicates with agents to process payments

### 👤 `buyer_agent.py`
- Buyer’s payment agent
- Sends tokens to seller securely on blockchain

### 🏪 `seller_agent.py`
- Verifies transaction success
- Confirms delivery using smart rules

---

## ⚙️ How It Works

1. **Seller** adds items using the bot in a Discord server.
2. **Buyer** uses simple `$buy` commands to place an order.
3. Agents securely handle payment verification over blockchain.
4. Once payment is verified, the order is placed and confirmed!

---

## 📦 Use Case

🎯 Perfect for **gamers, streamers, and Discord community owners** who want to:
- Sell digital/physical merchandise
- Handle payments securely
- Automate the process with no middlemen

---

## 🚀 Tech Stack

- **Python 3.10+**
- **Discord.py (commands API)**
- **uAgents (Autonomous Agent Framework)**
- **Cosmos Blockchain** (for token transfers)
- **VS Code / GitHub**

---
