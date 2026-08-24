# Contributing to Manifest

Thank you for your interest in contributing! This document covers the basics.

## Getting started

1. Fork or clone the repository:
   ```bash
   git clone https://github.com/dimasd18/manifest.git
   ```
2. Open `app.html` in a browser (no build step required).
3. Get testnet USDC from the [Circle faucet](https://faucet.circle.com) (select Arc Testnet).

## Development workflow

- Create a feature branch: `git checkout -b feat/my-feature`
- Keep commits small and descriptive.
- Open a Pull Request against `main` with a clear description of the change.

## Code style

- Plain HTML/JS, no build step — keep it that way.
- Prefer readable, intention-revealing names over clever one-liners.

## Reporting bugs

Open an issue with steps to reproduce, expected behavior, and screenshots if applicable.

## Network configuration

Arc Testnet details live in `README.md`. Always use the official RPC endpoint
(`https://rpc.testnet.arc.io`) when testing locally.
