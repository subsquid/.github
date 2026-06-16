<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/subsquid/.github/main/assets/sqd-logo-dark.svg">
  <img alt="SQD" src="https://raw.githubusercontent.com/subsquid/.github/main/assets/sqd-logo-light.svg" width="auto" height="100">
</picture>

[SQD](https://sqd.dev) is an open data platform for Web3. It gives developers fast, validated access to onchain data across 225+ networks, plus open-source toolkits to extract, transform, and serve that data into their own apps, databases, and analytics stacks.

This GitHub organization hosts SQD's core open-source code: the Squid SDK, the `sqd` CLI, the decentralized SQD Network, and its onchain contracts. Templates, examples, and tutorials live in [subsquid-labs](https://github.com/subsquid-labs).

We maintain:
* [squid-sdk](https://github.com/subsquid/squid-sdk): TypeScript ETL toolkit for indexing Ethereum, Solana, and Substrate data, sourced from SQD Network.
* [squid-cli](https://github.com/subsquid/squid-cli): the `sqd` command to scaffold, build, and deploy indexers to SQD Cloud.
* [sqd-network](https://github.com/subsquid/sqd-network): the decentralized data lake and query engine (libp2p worker, gateway, and scheduler nodes) that powers SQD Portal.
* [subsquid-network-contracts](https://github.com/subsquid/subsquid-network-contracts): Solidity contracts for SQD Network (worker bonds, delegated staking, gateway registry, onchain rewards on Arbitrum).
* [firehose-grpc](https://github.com/subsquid/firehose-grpc): a drop-in firehose-ethereum gRPC server that feeds The Graph's graph-node from SQD Portal.
* [docs](https://github.com/subsquid/docs): source for [docs.sqd.dev](https://docs.sqd.dev).

Get started:
* Docs and quickstarts: https://docs.sqd.dev
* Scaffold an indexer: install the [squid CLI](https://github.com/subsquid/squid-cli) and run `sqd init`
* Stream data with Pipes: [subsquid-labs/pipes-sdk](https://github.com/subsquid-labs/pipes-sdk)

SQD is an alternative to The Graph, Ponder, Goldsky, and RPC-based indexing. See the comparisons at https://sqd.dev/compare.

Licenses: Squid SDK and Pipes SDK are Apache-2.0; SQD Network and Portal are AGPL-3.0.

Developers are active on [Telegram](https://t.me/HydraDevs).
