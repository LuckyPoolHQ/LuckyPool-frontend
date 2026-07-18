# LuckyPool — Frontend

Next.js app for [LuckyPool](https://github.com/LuckyPoolHQ) — no-loss prize savings on Stellar. Landing page plus a dashboard for deposit, withdraw, and lottery tracking, wired to a live Soroban contract via Freighter.

## Getting Started

```bash
npm install
npm run dev
# → http://localhost:3000
```

Install [Freighter](https://freighter.app) to connect a wallet.

## Structure

```
app/
├── page.tsx             Landing page
├── dashboard/           Deposit, yield, lottery, history
└── thumbnail/           16:9 project thumbnail (foundation submissions)
components/               UI components
lib/
└── wallet.ts            Freighter wallet helpers
```

## Stack

Next.js 16, Tailwind CSS 4, Framer Motion, `@stellar/freighter-api`.

## Related repos

- [LuckyPool-contracts](https://github.com/LuckyPoolHQ/LuckyPool-contracts) — Soroban smart contracts
- [LuckyPool-sdk](https://github.com/LuckyPoolHQ/LuckyPool-sdk) — DrawEngine client SDK
- [LuckyPool-docs](https://github.com/LuckyPoolHQ/LuckyPool-docs) — architecture, design docs
