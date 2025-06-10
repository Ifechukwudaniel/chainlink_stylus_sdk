# Chainlink Stylus SDK

> 🛠️ **Built by the original author of the Pyth Stylus SDK**

This SDK enables consuming Chainlink oracle data in Rust-based [Stylus](https://arbitrum.io/stylus) smart contracts.  
It builds on the experience gained from designing the [Pyth Stylus SDK](https://github.com/pyth-network/pyth-crosschain) and adapts it for the Chainlink ecosystem.

The goal is to make Chainlink feeds easily accessible to Stylus developers with:

- 🦀 Idiomatic Rust interfaces
- ⚙️ Full `no_std` support
- 🧪 Mocking and test utilities
- 📦 ABI integration for end-to-end contract deployment

It is **strongly recommended** to follow [Chainlink's consumer best practices](https://docs.chain.link/data-feeds/using-data-feeds) when using price feeds.

---

## Features

- Interacts with Chainlink oracle contracts from Rust-based Stylus contracts.
- Provides safe and composable interfaces to fetch and use price data.
- Supports local testing and mocking of feed updates.
- Offers a clean developer experience and simplified ABI usage.

---

## Installation

To add the SDK from crates.io (once published), add:

```toml
[dependencies]
chainlink-stylus = "0.1.0"
