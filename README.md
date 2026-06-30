# GiwaRemit Agent 🤖

AI-powered USDC remittance agent on Arc Testnet — built for the Lepton Agents Hackathon (Canteen × Circle × Arc).

## Live Demo
[giwaremit-agent.vercel.app](https://giwaremit-agent.vercel.app)

## What It Does
Talk to the agent in plain English — "Send 1 USDC to Pakistan" — and it parses the request, sets up the transfer, and executes a **real on-chain USDC transaction** on Arc Testnet.

## Features
- Natural language parsing (amount, destination, memo)
- Real USDC transfers on Arc Testnet (not simulated)
- Auto network switching to Arc Testnet via MetaMask
- On-chain transaction memos (Arc v0.7.2)
- Live balance tracking
- TX hash linked to Arc Explorer (testnet.arcscan.app)
- Multi-currency support: PKR, INR, PHP, NGN, BDT
- Transfer history with confirmed status

## Tech Stack
- HTML5, CSS3, Vanilla JavaScript
- ethers.js v6 for blockchain interaction
- Arc Testnet (Chain ID: 5042002)
- USDC contract: `0x3600000000000000000000000000000000000000`

## 🚀 Built on Latest Arc Infrastructure

GiwaRemit Agent is built to evolve with Arc's expanding ecosystem:

- ✅ **Arc v0.7.2 Transaction Memos** — every remittance carries structured payment references (invoice IDs, recipient notes) at the protocol level
- ✅ **USDC + EURC native support** — real cross-border transfers, live on testnet

### Roadmap — Powered by Arc Ecosystem Growth
- 🔜 **Chainlink Data Streams** — real-time FX rate feeds for accurate cross-currency remittance pricing
- 🔜 **Chainlink CCIP** — cross-chain settlement beyond Arc (Ethereum Sepolia and beyond)
- 🔜 **Unified Balance Kit** — simplified multi-chain USDC balance management for users sending across corridors
- 🔜 **Circle Passkey Wallet** — biometric login, no browser extension needed
- 🔜 **Regional stablecoin corridors** — BRLA (Brazil), MXNB (Mexico), PHPC (Philippines), JPYC (Japan) as Circle onboards regional issuers

## Built For
Lepton Agents Hackathon — Canteen × Circle × Arc (June 15–29, 2026)

## Built By
[@msaleh007](https://github.com/msaleh007)