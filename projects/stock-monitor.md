# StockMonitor / Deal Flow Tracker

**Status:** Restart/refactor planned  
**Existing related repo:** [parm2006/Market-Checker](https://github.com/parm2006/Market-Checker)

This project needs a restart or heavy refactor. The local folder contains older stock-monitoring code and generated chart HTML files.

## Current Decision

Before building the next version, audit the existing files and classify each as:

- **Keep idea:** useful signal logic, charting approach, data source, or API pattern worth reimplementing.
- **Reference only:** old code that explains an idea but should not be carried forward directly.
- **Delete/archive:** generated files, stale experiments, broken code, or anything that makes the restart harder.

## Open Direction

Decide whether the next version is:

- A deal-flow tracker for SEC filings, M&A, contracts, and market reactions.
- A stock monitor for breakout detection, charts, and market overview.
- A small hybrid, only if the scope stays finishable.

## Local Files To Review

- `financial_monitor.py`
- `breakout_classifier.py`
- `test_simple.py`
- Generated chart HTML files
