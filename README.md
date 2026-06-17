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

## Built For
Lepton Agents Hackathon — Canteen × Circle × Arc (June 15–29, 2026)

## Built By
[@msaleh007](https://github.com/msaleh007)