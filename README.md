# SWIRL Contracts

Shared-vault Solidity contracts, native gateway, circuits and deployment scripts.

## Source layout

- `packages/contracts/contracts`: vault, verifier, gateway and test assets.
- `packages/contracts/circuits`: transfer and POI circuit sources.
- `packages/contracts/test`: contract and disaster-recovery tests.
- `packages/contracts/scripts`: local, testnet and production deployment.

This is the component source snapshot of the tested SWIRL Protocol workspace. For the root dependency lockfile, integrated build and complete cross-component test flow, use [swirl-protocol](https://github.com/swirl-cash/swirl-protocol).

Never commit real private keys, recovery phrases, API credentials, server environment files or local service state. Public contract addresses, verification keys and proving artifacts are not account credentials.
