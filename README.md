# GiwaRemit Agent 🤖

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

## Roadmap
- Pyth Network price feeds for real-time FX rates (USD/PKR, USD/INR, USD/PHP)
- KRW-backed stablecoin corridor (Upbit ecosystem integration)
- Email login - no MetaMask required
- Mobile app - iOS + Android
- GIWA Mainnet launch - production USDC transfers

## Proof of Working
Real on-chain transfer: TX 0xddb6592ffb404da6cd8c4556e6fb16b0034ca7ce85a26320270ae10b5d9018cb, Block 29680679

## Built For
GASOK MVP Build Phase - Upbit x Optimism x GIWA

## Built By
@msaleh007