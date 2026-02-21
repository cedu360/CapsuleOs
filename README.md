# Capsula Core — MVP

**Capsula Core** is an experimental operating system layer designed for decentralized storage, cryptographic file binding, and peer-to-peer networking. This MVP (Minimum Viable Product) demonstrates the core pillars of the Capsula ecosystem.

## 🚀 Key Features

- **Storage Node**: Run this repository to contribute storage capacity to the Capsula network. It allows storing and serving encrypted shards via the `/shard/` API.
- **Micro-Marketplace**: A decentralized market for BIDs (shards) with SEDUCOIN integration.
- **Advanced Frontend**: Premium HTML5 dashboard for real-time network status monitoring.

> [!IMPORTANT]
> This public repository contains the **Node Client** and **Storage API**. The core technology for shard construction (Bifrost) and the Reactive Cube Engine are proprietary and not included in this release.

## 🛠 Tech Stack

- **Backend**: Python 3.10+, FastAPI, Uvicorn.
- **Networking**: Custom P2P implementation (DHT-based locator).
- **Storage**: Binary FS ledger, SQLite index.
- **Frontend**: Vanilla HTML5, CSS3 (Glassmorphism), JavaScript (ES6+).

## 🏃 Getting Started

1. **Install dependencies**:
   ```bash
   cd
   pip install -e .
   ```

2. **Access the Dashboard**:
   Open `http:www.capsuleos.com in your browser.

## 📄 License

Experimental / Proprietary (Check terms before use).
