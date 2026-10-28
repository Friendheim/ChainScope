# ChainScope

React + TypeScript + Vite + ethers.js Web3 portfolio dashboard.

## Features
- Responsive dark dashboard with explicitly fictional demo assets and chart.
- Connect EIP-1193 wallet (e.g. MetaMask).
- Read native network token balance and manually tracked ERC-20 balances.
- Refresh balances and handle network mismatch.
- Read-only; never asks for seed phrases or private keys.

## Development
```bash
npm install
npm run dev
npm run build
```

## GitHub Pages
Vite base is `/ChainScope/`. The included GitHub Actions workflow builds and publishes `dist/`. Enable Pages with **Settings → Pages → Build and deployment → Source: GitHub Actions**.

## Limitations
Demo portfolio data is fictional. Real mode does not calculate USD valuations, price history, or transaction history. Those require reliable indexed price/transaction APIs. Token tracking is in-memory for the session. This is a prototype, not audited financial software.
