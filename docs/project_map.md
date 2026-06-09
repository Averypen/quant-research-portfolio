# Project Map

## Published Repositories

| Repo | Role in System | Public Demonstration |
|---|---|---|
| `ares-public-architecture` | US equity research engine | Synthetic OHLCV, toy signal, target portfolio, risk controls, dry-run lifecycle |
| `vnq-datalake-public-manual` | Data infrastructure | Schema, universe snapshots, update workflow, validation, manifest design |
| `chronos-master-portfolio-demo` | Master portfolio governor | Multi-sleeve allocation, drawdown governor, volatility-aware scaling |
| `quant-execution-audit-toolkit` | Execution and audit | Orders, simulated fills, positions, PnL, JSONL audit events |
| `vhedge-risk-allocation-demo` | Defensive allocation | Multi-asset synthetic allocation, volatility targeting, drawdown-aware scaling |
| `equity-alpha-research-lab` | US equity factor research | Toy factors, composite score, walk-forward split, cost-aware toy backtest |
| `qinglong-ashare-research-lab` | A-share research | Tradability filters, suspension flags, limit-state handling, pattern score workflow |

## System View

```text
Data infrastructure
  -> research engines
  -> portfolio construction
  -> risk governance
  -> execution lifecycle
  -> audit and manifest reporting
```
