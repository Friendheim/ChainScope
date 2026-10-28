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

## 中文项目说明
ChainScope 是面向前端/Web3 求职展示的响应式资产看板原型，技术栈包括 React、TypeScript、Vite、ethers.js 和 GitHub Actions。

**已实现**：演示仪表盘、移动端资产卡片、注入式钱包连接、原生代币余额查询、手动添加 ERC-20 合约并查询余额、网络变化检查、自动部署。

**未实现**：真实价格/K 线、历史交易、WalletConnect 跨应用连接、自动发现代币、持久化数据存储。页面演示资产和收益率均为虚构数据，不应作为投资依据。

线上体验：https://friendheim.github.io/ChainScope/
