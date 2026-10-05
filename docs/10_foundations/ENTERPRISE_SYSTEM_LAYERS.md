# Enterprise System Layers

This is a working model, not a conclusion.

| Layer | Typical examples | Default AI stance |
|---|---|---|
| 1. Record | customer, account, trade, payment | deterministic system of record |
| 2. Transaction | transfer, order, settlement | deterministic execution |
| 3. Rules / calculation | interest, tax, limits, P&L | deterministic rules/calculation |
| 4. Analytics | fraud scoring, forecasting | statistical ML / analytical AI where justified |
| 5. Interpretation | documents, explanations, questions | strong LLM candidate |
| 6. Orchestration | variable multi-step work across systems | agent candidate only if ordinary workflow automation is insufficient |

## Research caution

The existence of a possible AI interface does not justify replacing a simple deterministic interface. Balance lookup, statement retrieval, transaction history and other static authoritative retrievals should remain direct unless a separate cognitive problem is being solved.

## Human-role distinction

A mortgage affordability or financial-planning conversation may involve cognitive work currently performed by an adviser or salesperson. That is a different research question from whether the underlying banking account interface should become agentic.
