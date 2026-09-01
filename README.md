# AEGIS // Autonomous Execution OS

**Quant Risk Core · v3.2.1 · Mainnet**

A high-fidelity, real-time crypto trading command dashboard featuring deterministic risk envelopes, multi-agent LLM cognitive core, SafeRL, TreeSHAP XAI, and live telemetry.

## Live Dashboard

Open `index.html` locally or view the deployed version on Vercel / Netlify.

## Architecture (4 Layers)

1. **Data Foundation** — CEX/DEX/on-chain ETL, Kafka, BigQuery, Glassnode, Kaiko
2. **Cognitive Core** — TFT + multi-agent LLM mesh (Crypto / News / Sentiment / Risk / Orchestrator)
3. **Operational Engine** — Pre-trade gate → SafeRL CMDP envelope → TWAP/VWAP / CoW / Flashbots
4. **Performance Monitoring** — Live KPIs, equity/drawdown, circuit breaker, audit trail, drift governance

## Key Features

- Fractional Kelly + VaR/CVaR gating
- Deterministic circuit breaker (`DD_t > θ_max ⇒ 𝒜_halt()`)
- Blue/Green model deployment + automated retrain on KS/Wasserstein/Page-Hinkley drift
- Immutable KYT-aware audit trail
- MiCA / HSM key isolation ready

## Tech

Pure HTML/CSS/JS + Chart.js. No build step. Fully responsive dark quant aesthetic.

## Roadmap

- ✅ Phase 1 — Foundation & Backtesting
- ✅ Phase 2 — Agentic Synthesis · Paper
- 🔴 Phase 3 — Full Autonomy & Oversight (Live)

Built for human-auditable autonomy.
