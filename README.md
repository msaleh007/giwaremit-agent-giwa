# GiwaRemit Agent

AI-powered USDC remittance agent on **GIWA Testnet** - built for the GASOK MVP Build Phase (Upbit x Optimism x GIWA).

## Live Demo
https://giwaremit-agent-giwa.vercel.app

## Verified Smart Contract
GiwaRemitUSDC (grUSDC): 0x91DdFaB2caD6D8dC9a4476E196d58bC26eAfd0F6
Explorer: https://sepolia-explorer.giwa.io/address/0x91DdFaB2caD6D8dC9a4476E196d58bC26eAfd0F6

## What It Does
Talk to the agent in plain English - "Send 1 USDC to Pakistan" - and it executes a real on-chain USDC transaction on GIWA Testnet.

## Features
- Natural language parsing (amount, destination, memo)
- Real USDC transfers on GIWA Testnet (not simulated)
- Auto network switching to GIWA Testnet via MetaMask
- On-chain transaction memos
- Multi-currency support: PKR, INR, PHP, NGN, BDT

## Tech Stack
- HTML5, CSS3, Vanilla JavaScript, ethers.js v6
- GIWA Testnet (Chain ID: 91342, OP Stack / Optimism)
- GiwaRemitUSDC: 0x91DdFaB2caD6D8dC9a4476E196d58bC26eAfd0F6
- Karst Hardfork compatible (Osaka EVM features)

## Roadmap

### Phase 2 - Ecosystem Integration
- KRW-backed stablecoin corridor (Upbit ecosystem integration)
- Pyth Network price feeds for real-time FX rates (USD/PKR, USD/INR, USD/PHP)
- OP Stack Superchain interoperability - cross-chain remittance to Base, Optimism, and other OP Stack L2s
- Native GIWA Wallet integration
- Email login - no MetaMask required
- Revenue model - 0.5% transaction fee for platform sustainability

### Phase 3 - Scale
- Mobile app - iOS + Android
- On-ramp integration for Korea market via Upbit
- Multi-currency stablecoin corridors
- GIWA Mainnet launch - production USDC transfers
- Institutional-grade compliance tools

## Proof of Working
Real on-chain transfer: TX 0xddb6592ffb404da6cd8c4556e6fb16b0034ca7ce85a26320270ae10b5d9018cb, Block 29680679

## Built For
GASOK MVP Build Phase - Upbit x Optimism x GIWA

## Built By
@msaleh007