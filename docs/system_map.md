# Quant Systems Public Map

The public portfolio is organized around separate system capabilities rather than a single strategy.

## System Capability Layers

```text
Data Layer
  -> market data ingestion design
  -> schema contracts
  -> validation reports
  -> universe snapshots

Signal Layer
  -> synthetic toy signals
  -> public factor examples
  -> no proprietary alpha disclosure

Portfolio Layer
  -> target weights
  -> position caps
  -> turnover constraints
  -> sleeve allocation concepts

Risk Layer
  -> drawdown guards
  -> exposure limits
  -> cost and slippage assumptions
  -> scenario and regime notes

Execution Layer
  -> dry-run orders
  -> simulated fills
  -> position ledger
  -> PnL ledger

Audit Layer
  -> structured logs
  -> run manifest
  -> reproducibility record
  -> validation checks
```

## Model Family Mapping

| Private System Family | Public Repository | Public Form |
|---|---|---|
| Ares / vProfit Pure | `ares-public-architecture` | Synthetic US single-name equity engine demo |
| VNQ market data layer | `vnq-datalake-public-manual` | Public data lake manual and examples |
| Chronos master system | `chronos-master-portfolio-demo` | Planned master portfolio governor demo |
| vHedge / Aegis | `vhedge-risk-allocation-demo` | Planned defensive allocation demo |
| vProfit / Hermes | `equity-alpha-research-lab` | Planned US equity alpha research framework |
| Tianshu / QingLong | `qinglong-ashare-research-lab` | Planned A-share market-structure research demo |
| Orchestrator / execution | `quant-execution-audit-toolkit` | Planned mock execution and audit toolkit |

## Design Principle

Public repositories are clean-room demonstrations. They explain architecture and engineering discipline without revealing production trading logic.
