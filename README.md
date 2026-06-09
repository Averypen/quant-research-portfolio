# Quant Research Portfolio

This repository is the public landing page for the Averypen quant research and systems architecture portfolio.

It links together a set of sanitized public repositories that demonstrate research-to-production quant system design using synthetic data, mock execution, reproducible manifests, public documentation, ML research workflow, and research-bias validation.

## Published Repositories

| Repository | Capability Demonstrated | Status |
|---|---|---|
| [`ares-public-architecture`](https://github.com/Averypen/ares-public-architecture) | Modular US equity quant engine architecture with toy backtest | Published |
| [`vnq-datalake-public-manual`](https://github.com/Averypen/vnq-datalake-public-manual) | Reproducible market data lake design and update manual | Published |
| [`chronos-master-portfolio-demo`](https://github.com/Averypen/chronos-master-portfolio-demo) | Master portfolio governor and multi-sleeve risk control | Published |
| [`quant-execution-audit-toolkit`](https://github.com/Averypen/quant-execution-audit-toolkit) | Dry-run execution and audit lifecycle | Published |
| [`vhedge-risk-allocation-demo`](https://github.com/Averypen/vhedge-risk-allocation-demo) | Defensive multi-asset allocation and volatility targeting | Published |
| [`equity-alpha-research-lab`](https://github.com/Averypen/equity-alpha-research-lab) | Synthetic equity factor research, XGBoost sweep, OOS prediction, and validation | Published |
| [`qinglong-ashare-research-lab`](https://github.com/Averypen/qinglong-ashare-research-lab) | A-share market-structure-aware research workflow | Published |
| [`quant-research-validation-toolkit`](https://github.com/Averypen/quant-research-validation-toolkit) | Look-ahead, leakage, survivorship, purge/embargo, point-in-time universe, and tradability audits | Published |

## Portfolio Narrative

The public repository set is designed to show an end-to-end quant systems view:

1. **Data infrastructure**: universe snapshots, schema design, validation, manifests.
2. **Research engines**: synthetic OHLCV, factor scoring, toy ranking signals, market-structure-aware filters.
3. **Machine-learning research**: XGBoost sweep, leaderboard, feature importance, out-of-sample predictions, prediction-to-portfolio simulation.
4. **Research validation**: look-ahead audit, label leakage guard, survivorship-bias audit, purged and embargoed split, point-in-time universe manifest, tradability audit.
5. **Portfolio construction**: target weights, sleeve allocation, turnover control, cost assumptions.
6. **Risk governance**: drawdown-aware scaling, volatility targeting, defensive allocation, cash spillover.
7. **Execution lifecycle**: target weights to orders, simulated fills, positions, PnL, structured JSONL audit events.
8. **Reproducibility**: config-driven runs, deterministic seeds, manifest output, tests.

## Design Boundary

This public portfolio intentionally excludes:

- Proprietary production signals.
- Private parameters.
- Live platform configuration.
- Real trading logs.
- Paid vendor data.
- Platform-identifier information.
- Private strategy performance records.

## Batch Status

### Batch 1: Published

- `quant-research-portfolio`
- `ares-public-architecture`
- `vnq-datalake-public-manual`

### Batch 2: Published

- `chronos-master-portfolio-demo`
- `quant-execution-audit-toolkit`

### Batch 3: Published

- `vhedge-risk-allocation-demo`
- `equity-alpha-research-lab`
- `qinglong-ashare-research-lab`

### Validation Layer: Published

- `quant-research-validation-toolkit`
- XGBoost sweep PR merged into `equity-alpha-research-lab`

## Review Guide

For a quick review, start with:

1. `equity-alpha-research-lab` for factor research, XGBoost sweep, and OOS prediction workflow.
2. `quant-research-validation-toolkit` for look-ahead, survivorship, leakage, purge, embargo, and point-in-time universe audits.
3. `ares-public-architecture` for the research engine.
4. `chronos-master-portfolio-demo` for portfolio governance.
5. `quant-execution-audit-toolkit` for execution and audit lifecycle.
6. `qinglong-ashare-research-lab` for A-share market-structure-aware research.
7. `vhedge-risk-allocation-demo` for defensive allocation.
8. `vnq-datalake-public-manual` for data infrastructure design.
