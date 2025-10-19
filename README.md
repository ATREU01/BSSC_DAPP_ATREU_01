# BSSC Dapp — Enterprise Starter

Contest-ready React + Vite + TypeScript dapp for Binance Super Smart Chain (BSSC).
- EVM JSON-RPC (ethers v6 / MetaMask): strict chain gating (default `16979`), latency p50/p95, timeouts, sample tx.
- Solana JSON-RPC (@solana/web3.js / Phantom): health/slot checks, faucet + balance refresh, timeouts.

## Quickstart
```bash
npm install
npm run dev
```
Paste your **EVM** and **Solana** RPCs in the UI → Apply → Connect.

## Environment (.env example)
```
VITE_EVM_RPC=http://localhost:8545
VITE_SOL_RPC=http://localhost:8899
VITE_EXPECTED_EVM_CHAIN_ID=16979
```

## Scripts
- `npm run dev` — Vite dev server
- `npm run build` — production build
- `npm run preview` — preview dist

License: ATR3U
