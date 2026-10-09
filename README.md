### Hi, I'm Adil 👋

**Full-Stack & Web3 Systems Engineer.** I build the rails between regular users and on-chain settlement: smart accounts that don't need seed phrases, contracts that hold real investor capital, and the ledgers, indexers and fiat ramps that keep the off-chain side honest.

4+ years shipping production systems for tokenized private markets, retail token platforms, and DeFi marketplaces. Currently founding engineer at **SphereHub**.

---

#### 🧱 What I build

- **Tokenized private markets:** factory-deployed escrow vaults for private placements with capital thresholds, deadlines, batched refunds and pro-rata distributions. Accredited investors fund $5k+ tickets in two clicks.
- **Account abstraction (ERC-4337):** gasless onboarding with Pimlico and Biconomy paymasters, email/OTP signers, and no seed phrases for non-crypto investors.
- **Exchange & token infrastructure on Base:** AMM with dynamic slippage bounds, on-chain KYC tiers ($10k–$1M/day), fixed-APY staking, and Chainlink FX oracles with Pyth fallback, serving 1,000+ retail users.
- **Money-movement backends:** idempotent financial ledgers, cron reconciliation of on/off-ramp (Transak) events, CDC streams into enterprise SQL, and OIDC/OAuth SSO across Web2 profiles and self-custodial smart accounts.
- **Indexing & data:** cross-chain ETL (Astar, Moonbeam), GraphQL/Subsquid indexers, and real-time portfolio dashboards built from on-chain event streams.
- **Off-chain order books:** EIP-712 signed-order matching that cut user gas spend by ~60%.
- **Solana:** tiered NFT pass platforms on Metaplex Core and Candy Machine, with token-gating APIs and admin tooling.

#### 🛠️ Stack

`Solidity` `Foundry` `viem` `wagmi` `ERC-4337` `EIP-712` `SIWE` `Chainlink` `Pyth` · `TypeScript` `Next.js` `React` `Node.js` `FastAPI` `GraphQL` · `PostgreSQL` `Supabase` `MySQL` `Redis` `Docker` `Azure` · `Base` `Ethereum` `Polygon` `Solana`

#### 📌 Open source

- [**compliant-token-exchange**](https://github.com/yasinadil/compliant-token-exchange): retail token exchange on Base: ERC-4337 gasless accounts, fiat ramps, idempotent ledger, outbox/CDC sync
- [**compliant-amm-contracts**](https://github.com/yasinadil/compliant-amm-contracts): KYC-tiered AMM, slippage policy, fixed-APY staking, timelock; 133 tests, invariant suites
- [**private-placement-escrow**](https://github.com/yasinadil/private-placement-escrow): CREATE2 offering factory, phased pro-rata returns, refunds; audited and fixed
- [**solana-member-passes**](https://github.com/yasinadil/solana-member-passes): tiered Metaplex Core passes, verified paid mints, token-gating API
- [**nox-credentials**](https://github.com/yasinadil/nox-credentials): soulbound (ERC-5192) verifiable credentials with SIWE auth and per-recipient encrypted sharing. Includes a v2 security audit of my own code; 100% contract coverage.
- [**space-marketplace**](https://github.com/yasinadil/space-marketplace): Harberger-style streamed subscription memberships for DAOs. Contract audit and rewrite (5 bugs fixed, each with a regression test), plus fuzz and invariant suites.
- [**dotsama-exchange-contracts**](https://github.com/yasinadil/dotsama-exchange-contracts): EIP-712 NFT order book on Astar and Moonbeam, with protocol fees shared to badge stakers
- [**dotsama-multichain-indexer**](https://github.com/yasinadil/dotsama-multichain-indexer): Subsquid ETL indexing an NFT exchange across Astar and Moonbeam into one GraphQL API
- [**dental-research**](https://github.com/yasinadil/dental-research): Next.js + Supabase intake and analytics app behind a clinical study at three hospitals

> The first four repos are white-label builds of production systems I shipped for clients, each audited and fixed before publishing.

#### 📫 Reach me

[adilyasin.xyz](https://www.adilyasin.xyz) · [LinkedIn](https://linkedin.com/in/adilyasin) · adilyasin205@gmail.com · open to senior full-stack / web3 roles and contracts
