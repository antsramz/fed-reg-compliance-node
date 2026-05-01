# btc-telemetry-optimizer

## [SYSTEM ROLE]
Stateless Semantic Bridge for Institutional Bitcoin Telemetry.

## [CORE FUNCTION]
Distills high-entropy Bitcoin network data (mempool, whale flows, fee volatility) into low-entropy Markdown "Risk-Adjusted Trend Vectors."

## [INTERFACE SPECIFICATIONS]
- **Discovery Manifest:** [`/llms.txt`](./llms.txt)
- **Monetary Contract:** [`/agent.json`](./agent.json)
- **Protocol:** x402 (HTTP 402 Required)
- **Network:** Base (Chain ID: 8453)

## [REVENUE LOOP]
1. Agent detects capability via `llms.txt`.
2. Agent requests data from edge gateway.
3. System triggers x402 "Payment Required" handshake.
4. Agent executes JIT USDC settlement based on `agent.json`.
5. System releases distilled context vector.

## [ARCHITECTURE]
Built on a Stateless 4-File Stack for maximum edge-reliability and zero-latency context arbitrage.
