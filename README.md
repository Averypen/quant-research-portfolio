# Averypen Quant Research & Systems Portfolio

A public, sanitized portfolio of quant research and quant systems architecture work.

This portfolio is designed to demonstrate how systematic research can be organized into production-style components: data infrastructure, signal research, portfolio construction, risk governance, dry-run execution, audit trails, and reproducible run manifests.

The public repositories intentionally use synthetic data, mock execution, and simplified examples. They do not disclose proprietary signals, private parameters, live broker configuration, real trading logs, paid vendor data, or broker-identifier information.

## Portfolio Thesis

Most public quant repositories focus on isolated notebooks or single backtests. This portfolio focuses on the full research-to-production lifecycle:

```text
data -> signal -> portfolio -> risk -> execution -> audit -> reporting -> iteration
```

The objective is to show system design discipline rather than advertise a trading result.

## Batch 1 Public Repositories

| Repository | Status | Purpose |
|---|---:|---|
| `ares-public-architecture` | Built locally | Synthetic-data demonstration of a US single-name equity profit engine architecture |
| `vnq-datalake-public-manual` | Built locally | Public manual for reproducible equity research data lake design |
| `quant-research-portfolio` | Current repo | Portfolio entry point and project map |

## Planned Repository Roadmap

| Repository | Purpose | Public Boundary |
|---|---|---|
| `chronos-master-portfolio-demo` | Master portfolio governor combining defensive and return sleeves | Toy sleeves, synthetic equity curves, no production allocations |
| `vhedge-risk-allocation-demo` | Defensive multi-asset allocation engine with volatility targeting | Synthetic ETF-style data, no live weights |
| `equity-alpha-research-lab` | Generic US equity factor research framework | Toy factors and OOS validation, no proprietary ranking formula |
| `qinglong-ashare-research-lab` | A-share market-structure-aware research framework | Synthetic A-share data with tradability flags, no real picks or frozen production patterns |
| `quant-execution-audit-toolkit` | Dry-run order, fill, position, PnL, and manifest lifecycle | Mock broker only, no live broker settings |

## Core Capabilities Demonstrated

- Modular system architecture
- Reproducible research runs
- Config snapshots and run manifests
- Cost-aware and turnover-aware backtesting
- Drawdown and exposure controls
- Dry-run execution by default
- Order-to-fill-to-position-to-PnL lifecycle design
- Data lake schema and validation design
- Market-structure-aware research planning for US and A-share markets

## Public Safety Rules

This portfolio follows a strict public boundary:

- No proprietary alpha logic
- No production parameters
- No live broker configuration
- No broker identifiers
- No real trading logs
- No private market data cache
- No paid vendor data
- No investment advice
- Synthetic data and mock execution only

## How to Read This Portfolio

Start with:

1. `ares-public-architecture` for a runnable toy quant lifecycle.
2. `vnq-datalake-public-manual` for data lake engineering and validation design.
3. This repository for the overall project map and future roadmap.

## Current Local Build State

Batch 1 has been scaffolded and validated locally. Public GitHub push should only happen after the final security scan and repository review.
