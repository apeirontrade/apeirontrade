## apeirontrade

On-chain analytics and tooling for agentic payments.

| | |
|---|---|
| [**blocksigner-x402**](https://github.com/apeirontrade/blocksigner-x402) | Agent World — an x402 resource server on Algorand MainNet where persistent autonomous agents are commissioned per request. [Live](https://blocksigner.org) |
| [**provenance-site**](https://github.com/apeirontrade/provenance-site) | The x402 Trust Index — wash-risk grades for machine-payable API endpoints, computed from publicly observable on-chain payments and published as dated snapshots. Open data, CC BY 4.0. [Live](https://apeirontrade.github.io/provenance-site/) |
| [**provenance-mcp**](https://github.com/apeirontrade/provenance-mcp) | MCP server that scores an endpoint's payment history before an agent pays it. Listed in the Model Context Protocol registry. |
| [**provenance-guard**](https://github.com/apeirontrade/provenance-guard) | Pre-payment wash-risk check for x402 clients — one line between a client and its wallet. Fails open by default; can be set to fail closed. |
| [**agentkit**](https://github.com/apeirontrade/agentkit) | Monorepo for three agentic-payments products on a shared x402 foundation. Reorg-safe Base + Algorand indexer, typed facilitator registry. |
| [**entanglement-channel-lab**](https://github.com/apeirontrade/entanglement-channel-lab) | Quantum-information experiments on Amazon Braket, including a published null result. |

Leaderboards for machine-payable APIs rank by claimed volume, which is easy to
inflate — self-dealing loops, fresh-wallet farms, metronomic bots. Provenance
estimates how much of an endpoint's revenue looks organic from public on-chain
payments. In our dated snapshot of the top 24 Coinbase Bazaar merchants (week of
2026-06-29, Base) about a quarter of claimed volume looked non-organic; that is one
operator's estimate for that sample, with the weights, limits and unvalidated parts
[published alongside it](https://apeirontrade.github.io/provenance-site/methodology.html).
