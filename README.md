# scratch-wallet
Decentralized P2P payments via mesh networks - Banking for everyone
# 🔸 Scratch Wallet

**Decentralized P2P payments via mesh networks - Banking for everyone, controlled by no one.**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Status: Prototype](https://img.shields.io/badge/Status-Prototype-yellow.svg)]()
[![Platform: Mobile + Linux](https://img.shields.io/badge/Platform-Mobile%20%2B%20Linux-blue.svg)]()

## 🌟 Vision

Scratch Wallet enables **cash-like digital payments** that work even when the internet doesn't. Using Bluetooth mesh networking and a custom blockchain, it puts financial freedom directly in people's hands - no banks, no intermediaries, no gatekeepers.

**Why this matters**: 2.5 billion people globally lack access to traditional banking. Even in developed countries, people pay hefty fees for basic financial services. Scratch Wallet changes that.

## ✨ Key Features

- 📱 **Offline-First**: Payments work via Bluetooth mesh, no internet required
- 🔒 **True Privacy**: Anonymous transactions with encrypted purpose notes
- 💚 **Inclusive**: 100 SCRATCH signup bonus + referral rewards get everyone started
- 🌐 **Mesh Network**: Your phone becomes part of the payment infrastructure
- ₿ **BTC Bridge**: Optional Bitcoin savings for long-term value storage
- 🐧 **Linux Support**: Run on PCs, Raspberry Pi, or shop terminals
- 🎯 **Simple UX**: As easy as sending a text message

## 🚀 How It Works

```
User A wants to pay User B for bananas
    ↓
Opens Scratch Wallet → Enter "20 SCRATCH" → Purpose: "bananas"
    ↓
Bluetooth finds User B nearby → Encrypted payment sent
    ↓
User B receives payment + sees "bananas" note → Transaction complete
    ↓
Both wallets sync with blockchain when network available
```

## 🛠 Technical Architecture

### Core Components
- **Mobile Apps**: iOS/Android (React Native or Flutter)
- **Linux App**: Desktop/embedded (Qt or Electron)
- **Mesh Layer**: Bluetooth Low Energy primary, WiFi Direct fallback
- **Blockchain**: Custom lightweight chain for mobile devices
- **Crypto**: End-to-end encryption for all transaction data

### Mesh Networking
- **Primary**: Bluetooth LE (10-100m range)
- **Extended**: Multi-hop routing through other Scratch devices
- **Fallback**: WiFi Direct, radio protocols
- **Sync**: Opportunistic blockchain updates when online

### Privacy by Design
- **Anonymous**: No real names, no KYC, no identity linking
- **Encrypted**: Purpose notes only visible to sender/receiver
- **Cash-like**: No central authority can freeze or track payments
- **Open Source**: Community-auditable code

## 💰 Tokenomics

| Metric | Value |
|--------|--------|
| **Max Supply** | 21 billion SCRATCH |
| **Signup Bonus** | 100 SCRATCH per new user |
| **Referral Reward** | 50 SCRATCH each (halves every 4 years) |
| **Distribution** | Gradual release, no pre-mine |
| **Utility** | P2P payments, BTC savings gateway |

## 🎯 Target Users

- **Individuals**: Anyone who wants financial privacy and freedom
- **Small Businesses**: Shop owners in areas with poor internet
- **Unbanked Populations**: People excluded from traditional finance
- **Privacy Advocates**: Those seeking alternatives to surveillance capitalism
- **Tech Communities**: Linux users, mesh networking enthusiasts

## 📱 Current Status

- ✅ **Complete SDD**: Full technical specification ready
- ✅ **Working Prototype**: HTML/JS demo with core features
- 🔄 **In Progress**: Adalo no-code mobile app
- ⏳ **Next**: Real Bluetooth mesh networking implementation
- ⏳ **Future**: App store releases, Linux desktop app

## 🤝 Contributing

We believe financial tools should be built by and for the community. Contributions welcome:

- **Developers**: Mobile, blockchain, mesh networking expertise
- **Designers**: UX/UI for financial apps
- **Testers**: Help us make it bulletproof
- **Advocates**: Spread the word about financial freedom

### Development Setup
```bash
git clone https://github.com/yourusername/scratch-wallet
cd scratch-wallet
npm install
npm run dev
```

## 🔗 Links

- **Live Prototype**: [View Demo](your-demo-link)
- **Technical SDD**: [Full Specification](./docs/sdd.md)
- **Adalo Progress**: [Mobile App Preview](your-adalo-link)
- **Discussion**: [Community Forum](your-forum-link)

## 📄 License

MIT License - Built for the people, owned by no one.

## 🌍 Why This Matters

*"The current financial system excludes billions while enriching a few. Scratch Wallet returns money to its roots - a tool for everyone, controlled by everyone. When your phone becomes your bank, you become your own financial institution."*

---

**⭐ Star this repo if you believe in financial freedom for all**

## 🚧 Disclaimer

This is experimental software. Use with caution. Not financial advice.

---

### 📊 Project Stats

- **Created**: September 2025
- **Language**: JavaScript, React Native, Qt/C++
- **Contributors**: Community-driven
- **Philosophy**: Open source, privacy-first, people-powered
