# ChatGPT Turn T002 — Static Retrieval and DWH Challenge

**Date:** 05/10/2026
**Approx. time:** 17:45–18:07 UK time
**Status:** Reconstructed from retained conversation context; exact wording preserved only where available.

## User challenge

The user rejected the idea that static banking information needs an AI interface or agent. Examples: balance, statement, transaction history and other exact individual information. Adding an LLM/agent there was described as unnecessary and wasteful.

The user also challenged an over-broad DWH/BI framing. Enterprise reporting is dominated by deterministic BAU, regulatory, financial, compliance, operational and scheduled outputs. The warehouse and its SQL/ETL still need to exist. AI being good at writing SQL does not imply that the DWH/reporting layer disappears.

The user suggested that unknown ETL/production failures may be a more credible agentic area than fixed orchestration.

## Accepted correction

For a statement download, balance lookup, transaction history, scheduled regulatory report, fixed ETL dependency, fixed calculation or known workflow, default position:

> **No LLM. No agent. Prove why ordinary deterministic software is insufficient before introducing either.**

## Mortgage/advice distinction

The mortgage/university-fees example is not proof that static banking interfaces should become agentic. The cognitive work is currently performed by a financial adviser/salesperson/suitably authorised human. Research should test whether AI replaces or augments that cognitive role while deterministic systems continue to provide authoritative facts/calculations.

## DWH correction

The research must distinguish:

- deterministic production execution,
- AI-assisted design/build,
- AI-assisted testing/reconciliation,
- AI-assisted incident diagnosis,
- AI-generated commentary/explanation,
- genuinely agentic exception handling.

## Decisions

- **DECISION:** add mandatory `WHY NOT ORDINARY SOFTWARE?` test to every proposed LLM/agent use case.
- **DECISION:** do not infer that an AI-accessible interface should replace a deterministic one.
- **DECISION:** re-test earlier displacement hypotheses around fixed reporting instead of repeating them.
