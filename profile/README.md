<img width="2940" height="770" alt="banner" src="https://github.com/user-attachments/assets/b094f921-6242-4ecd-8034-cb4e9d0ce267" />

---

Neko Protocol is a DeFi lending and borrowing system that unlocks
liquidity from real-world assets. Neko turns tokenized
RWAs, starting with stocks and expanding to bonds, treasuries, and
other financial instruments, into active, yield-generating collateral.

Neko's mission is simple: **Make illiquid real-world assets liquid,
programmable, and usable across DeFi.**

## Why Neko Exists

Most RWAs sit trapped inside traditional systems. They may rise or fall
in price, but they don't generate yield and they can't be used as
collateral on-chain. Liquidity is limited, transferability is slow, and
composability is basically nonexistent.

Neko fixes that by becoming **the liquidity layer for RWAs**. Users can
lock their tokenized assets, borrow liquid assets like USDC or XLM, and
keep exposure to the underlying asset. Liquidity providers earn yield
backed by real-world collateral instead of pure crypto volatility.

## How It Works

### 1. RWA-Backed Borrowing

Users deposit tokenized RWAs as collateral. In return, they can borrow
assets such as USDC or XLM. Collateral ratios and liquidation rules
ensure system solvency.

### 2. On-Chain Lending

Liquidity providers lend assets to the protocol and earn yield from
interest payments. All positions are over-collateralized and backed by
real-world assets.

### 3. Zero-Knowledge-Verified Price Oracle

Neko built the **first RWA oracle on the Stellar network**.

It aggregates prices from multiple off-chain APIs and verifies them
using **zero-knowledge proofs**, ensuring:

-   Multi-source price integrity
-   No leaking of API keys or internal logic
-   Trust-minimized price feeds
-   Safe and verifiable collateral valuations

### 4. Full-Stack UX + API Layer

Neko includes:

-   A working frontend for borrowing, lending, and portfolio management
-   A developing (next milestone) **public API** for external integrations

## Architecture (High-Level)

-   Smart Contracts: Soroban on Stellar\
-   Oracle System: Noir/Barretenberg ZK proofs (sent on-chain)
-   Frontend: React + Stellar Wallet Kit (Stellar Scaffold)
-   Backend/API: Node.js services
-   RWA Tokens: Stocks today, Bonds/Treasuries soon

## Current Features

-   Borrow USDC/XLM against tokenized stocks
-   Lend liquidity and earn RWA-backed yield
-   Live ZK-verified oracle pipeline
-   Real-time portfolio dashboard
-   Liquidation engine
-   Frontend live

## Roadmap

### Q4 2025

-   Public API (REST + SDK)
-   Additional RWA support
-   ZK circuit optimizations (waiting for Protocol 25)

### 2026

-   Institutional RWA onboarding
-   Smart contract audits
-   Cross-chain liquidity expansion


## Documents
- [Whitepaper](https://docs.google.com/document/d/1a0oLaen3oTCVS3Ir9NitemQVNZ5T42euSKetHcweOGM/edit?usp=sharing)
- [Day 1 - Project Initialization](https://www.notion.so/Day-1-Project-Initialization-2b007cea0302803082baef18395afb83)
- [Day 2 - Technical Foundation](https://www.notion.so/Day-2-Technical-Foundation-from-Neko-Protocol-2b007cea03028046ab83eef7dd5c8167)
- [Day 3 - Functional Progress](https://www.notion.so/Day-3-Functional-Progress-for-Neko-Protocol-2b007cea0302803292e3d6737f19ada2?source=copy_link)
- [Empathy Map](https://www.notion.so/Empathy-Map-Neko-Protocol-2b107cea03028073a062dce30998c2bb)


## Repositories

-   Neko-DApp
-   Neko-Oracle-RWA
-   Neko-Landing

## License

We work by the MIT License.
