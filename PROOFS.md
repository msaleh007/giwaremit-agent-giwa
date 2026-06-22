# Proofs of Real On-Chain Activity

GiwaRemit Agent executes real transactions on **Arc Testnet** (Chain ID `5042002`) — nothing in the transfer flow is simulated. This document tracks verifiable on-chain proof.

## Contract details

| | |
|---|---|
| Network | Arc Testnet |
| Chain ID | 5042002 (`0x4CEF52`) |
| RPC | https://rpc.testnet.arc.network |
| USDC contract | `0x3600000000000000000000000000000000000000` |
| Memo Contract | `0x5294E9927c3306DcBaDb03fe70b92e01cCede505` |
| Explorer | https://testnet.arcscan.app |

## How to verify independently

1. Open https://giwaremit-agent.vercel.app
2. Connect a wallet holding Arc Testnet USDC
3. Execute any transfer through the agent
4. Copy the resulting transaction hash
5. Paste it into https://testnet.arcscan.app/tx/[hash]
6. Confirm: `From` = your wallet, `To` = the USDC contract above, `Method` = `transfer`, and the appended calldata bytes decode to the memo text shown in the app

## Transaction log

| Date | Amount | Corridor | Memo | TX Hash | Explorer Link |
|---|---|---|---|---|---|
| June 18, 2026 | 3 USDC | India (INR) | GiwaRemit transfer | `0x711a7703259852ba4faacfcaee645c0ff751cd85f3191c6eb930e12eb08e755d` | [View on Arcscan](https://testnet.arcscan.app/tx/0x711a7703259852ba4faacfcaee645c0ff751cd85f3191c6eb930e12eb08e755d) |
| June 18, 2026 | 2 USDC | India (INR) | GiwaRemit transfer | `0x50ae770104b3942b9041d85d92af35aef5fb67021e46728ca8f7c5140b3c4014` | [View on Arcscan](https://testnet.arcscan.app/tx/0x50ae770104b3942b9041d85d92af35aef5fb67021e46728ca8f7c5140b3c4014) |
| June 22, 2026 | 1 USDC | Pakistan (PKR) | GiwaRemit transfer | `0xfeec746f98ca79f50a019a5c154b928280742338768ba9a1d61f37d620e12a8c` | [View on Arcscan](https://testnet.arcscan.app/tx/0xfeec746f98ca79f50a019a5c154b928280742338768ba9a1d61f37d620e12a8c) |

## Arc v0.7.2 Memo Contract Proof

Latest transaction uses the official Arc Memo Contract `0x5294E9927c3306DcBaDb03fe70b92e01cCede505`:

- **TX:** `0xfeec746f98ca79f50a019a5c154b928280742338768ba9a1d61f37d620e12a8c`
- **Block:** 48192072
- **Confirmed within:** 0.78 seconds
- **Date:** June 22, 2026
- **Protocol:** Arc v0.7.2

## Builder's note

This is a solo build by [@msaleh007](https://github.com/msaleh007), an active Arc Testnet builder with 400+ prior transactions across Arc, GIWA, and Robinhood testnets (see [arc-project](https://github.com/msaleh007/arc-project)), and a GASOK Pioneer for a companion remittance app, [GiwaRemit](https://giwaremit.vercel.app).