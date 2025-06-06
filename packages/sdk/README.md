<div align="center">
  <h1>STON.fi SDK</h1>
</div>

[![TON](https://img.shields.io/badge/based%20on-TON-blue)](https://ton.org/)
[![License](https://img.shields.io/npm/l/@ston-fi/sdk)](https://img.shields.io/npm/l/@ston-fi/sdk)
[![npm version](https://img.shields.io/npm/v/@ston-fi/sdk/latest.svg)](https://www.npmjs.com/package/@ston-fi/sdk/v/latest)

The SDK is written in TypeScript and designed to be a thin wrapper on top of the [STON.fi](https://ston.fi/) contracts, which will help STON.fi protocol to be used more easily in JS/TS projects

Documentation for the SDK is available at [docs.ston.fi](https://docs.ston.fi/docs/developer-section/sdk)

## Installation

Firstly install the [@ton/ton](https://github.com/ton-org/ton) package following their [installation guide](https://github.com/ton-org/ton?tab=readme-ov-file#install)

Then, add SDK package using the package manager of your choice.

### NPM

```bash
npm install @ston-fi/sdk
```

### Yarn

```bash
yarn add @ston-fi/sdk
```

### PNPM

```bash
pnpm install @ston-fi/sdk
```

## Next steps

### Take a look at the demo app

We are providing a simple but fully functional demo app with the SDK usage in the next.js app to demonstrate the SDK functionality. The source code is open-sourced and can be found [here](https://github.com/ston-fi/sdk/tree/main/examples/next-js-app). Try this app at https://sdk-demo-app.ston.fi

### Dive deep into the documentation

- [DEX guide](https://docs.ston.fi/docs/developer-section/sdk)
- [Swap](https://docs.ston.fi/docs/developer-section/sdk/dex-v2/swap)
- [Provide liquidity](https://docs.ston.fi/docs/developer-section/sdk/dex-v2/lp_provide)
- [Transaction setting guide](https://docs.ston.fi/docs/developer-section/sdk/transaction-sending)
