# 🦍 APE ID — EthGlobal Bangkok 2024

> A phygital Web3 passport linking ENS subdomains to NFC wristbands for on-chain identity at real-world events.

Built at **EthGlobal Bangkok 2024** on the Base (L2) network.

## 💡 The Idea

What if your wristband at a conference *was* your crypto wallet?

APE ID lets you tap an NFC wristband to verify your on-chain identity — no app needed, no seed phrase exposed. The wristband acts as a **burner signer** tied to your ENS subdomain.

```
NFC Wristband tap → Burner wallet signs → ENS subdomain verified → Event access granted
```

## 🚀 Features

- **Phygital identity** — physical NFC tag linked to a blockchain identity
- **ENS subdomains** — human-readable names (`you.apeid.eth`)
- **Burner wallets** — NFC tag acts as hardware signer, no exposed keys
- **Event gating** — verify IRL event access and Discord community membership
- **Base L2** — cheap, fast transactions on Coinbase's L2

## 🛠 Tech Stack

| | |
|--|--|
| Framework | Next.js 15 |
| Blockchain | Base (Coinbase L2) |
| Identity | ENS subdomains |
| Wallet libs | Wagmi, Viem, Dynamic SDK |
| Hardware | NFC Tags / Wristbands |

## 🏃 Quick Start

```bash
git clone https://github.com/Min0laa/EthGlobal-Bangkok-2024
cd EthGlobal-Bangkok-2024
npm install --legacy-peer-deps
npm run dev
```

## 🧠 What I learned

- How NFC hardware can act as a cryptographic signer
- ENS subdomain registration and resolution on Base
- Building with Wagmi/Viem for wallet interactions
- Deploying to Base L2 and managing gas costs

## 👤 Author

**Sacha Morin** — [LinkedIn](https://linkedin.com/in/sacha-morin60) · [GitHub](https://github.com/Min0laa)

*Built at EthGlobal Bangkok 2024 🇹🇭*
