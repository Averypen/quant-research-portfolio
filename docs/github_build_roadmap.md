# GitHub Build Roadmap

## Completed

### Batch 1

- `quant-research-portfolio`: public landing repository.
- `ares-public-architecture`: synthetic research engine demo with toy backtest.
- `vnq-datalake-public-manual`: public data lake manual.

### Batch 2

- `chronos-master-portfolio-demo`: master portfolio governor demo.
- `quant-execution-audit-toolkit`: dry-run execution and audit lifecycle demo.

### Batch 3

- `vhedge-risk-allocation-demo`: defensive multi-asset allocation and volatility targeting demo.
- `equity-alpha-research-lab`: synthetic equity factor research, XGBoost sweep, and validation workflow demo.
- `qinglong-ashare-research-lab`: A-share market-structure-aware research workflow demo.

### Validation Layer

- `quant-research-validation-toolkit`: synthetic research-bias validation toolkit.
- PR workflow used for `equity-alpha-research-lab` XGBoost enhancement.

## Public Release Rules

Before any public push:

1. Confirm git status is clean.
2. Run strict private-path scan.
3. Run broad sensitive keyword review.
4. Run tests for code repositories.
5. Run toy demo when available.
6. Confirm generated `runs/` output is ignored.
7. Confirm public docs contain no proprietary production parameters.
8. Confirm validation demos explicitly discuss look-ahead, leakage, survivorship, purge/embargo, and point-in-time universe assumptions.
