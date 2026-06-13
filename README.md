# Ehsan's Telegram Mini App

A Telegram Mini App built with React and TypeScript, featuring TON wallet integration and full access to Telegram platform data.

## Tech Stack

- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [TON Connect](https://docs.ton.org/develop/dapps/ton-connect/overview)
- [Vite](https://vitejs.dev/)

## Install

```bash
npm install
```

## Scripts

- `dev` — Run in development mode
- `dev:https` — Run with local SSL certificates
- `build` — Build for production
- `lint` — Check code quality
- `deploy` — Deploy to GitHub Pages

```bash
npm run {script}
```

## Run

```bash
npm run dev:https
```

## Deploy

Deploys to GitHub Pages via the `deploy` script or automatically through the included GitHub Actions workflow on every push to `master`.

### Setup

1. Set `homepage` in `package.json` to your GitHub Pages URL
2. Set `base` in `vite.config.ts` to your repository name

```bash
npm run build
npm run deploy
```

## TON Wallet

Supports TON wallet connection so users can link their crypto wallet directly inside the app.
