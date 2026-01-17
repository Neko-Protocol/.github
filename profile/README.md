<img width="2940" height="770" alt="banner" src="https://github.com/user-attachments/assets/b094f921-6242-4ecd-8034-cb4e9d0ce267" />

---

Neko Protocol is a platform that unlocks
liquidity from real-world assets. Neko turns tokenized
RWAs, starting with stocks and expanding to bonds, treasuries, and
other financial instruments, into active, yield-generating collateral.

We do this by having a DeFi lending and borrowing system, liquidity layer
market and perpetual futures for RWAs.

Neko's mission is simple: **Make illiquid real-world assets liquid,
programmable, and usable.**

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

### 3. Perpetual futures

Users can trade perpetual contracts based on the real-world assets available
on the platform.

### 4. Full-Stack UX + API Layer

Neko includes:

-   A working frontend for borrowing, lending, perps and portfolio management
-   A developing (next milestone) **public API** for external integrations

## Architecture (High-Level)

-   Smart Contracts: Soroban on Stellar
-   Frontend: React + Stellar Wallet Kit (Stellar Scaffold)
-   Backend/API: Node.js services
-   RWA Tokens: Stocks today, Bonds/Treasuries soon

## Current Features

-   Borrow USDC/XLM against tokenized stocks
-   Lend liquidity and earn RWA-backed yield
-   Real-time portfolio dashboard
-   Liquidation engine
-   Frontend live

## Roadmap

### 2026

-   Institutional RWA onboarding
-   Smart contract audits
-   Cross-chain liquidity expansion

## Repositories

-   Neko-DApp
-   Neko-Landing

## License

We work by the MIT License.
