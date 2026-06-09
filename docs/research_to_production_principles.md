# Research-to-Production Principles

## 1. Separation of Concerns

A quant system should keep core responsibilities separate:

- Data loading and validation
- Signal generation
- Portfolio construction
- Risk controls
- Execution planning
- Fill simulation or broker interaction
- Position and PnL ledgering
- Reporting and audit

This reduces hidden coupling and makes failures easier to diagnose.

## 2. Reproducibility

Every run should record:

- Run identifier
- Timestamp
- Config snapshot
- Data source description
- Universe snapshot
- Code version
- Cost assumptions
- Output file locations
- Validation result

## 3. Risk Before Return

Public examples should not optimize for impressive performance. They should explicitly show:

- Gross and net exposure
- Position concentration
- Turnover
- Transaction costs
- Slippage assumptions
- Drawdown
- Failure modes

## 4. No Look-Ahead Discipline

Signals must only use information available at the decision timestamp. Public tests should check that signal outputs do not accidentally rely on future fields.

## 5. Market Structure Awareness

US equities and A-share markets should not be treated as identical. Public A-share research examples should handle:

- Suspension risk
- Limit-up and limit-down mechanics
- ST status
- Board classification
- T+1 execution assumptions
- Liquidity and turnover constraints

## 6. Dry-Run by Default

Any public execution example must default to dry-run or mock execution. Live trading code is intentionally excluded from the public portfolio.
