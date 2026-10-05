# Enterprise AI Boundary Research

Evidence-led research into where deterministic software, analytical ML, LLMs and agentic systems genuinely belong in enterprise technology.

## Core question

For every major activity inside a modern enterprise:

1. What must remain deterministic?
2. What benefits from analytical ML?
3. What benefits from LLMs?
4. What genuinely benefits from autonomous or semi-autonomous agents?
5. Does AI improve the activity, remove human labour, collapse an existing software layer, or create a genuinely new capability?

## Mandatory challenge

Every proposed LLM or agent use case must answer:

> **WHY NOT ORDINARY SOFTWARE?**

If deterministic software, SQL, rules, schedulers, conventional automation or existing workflow engines are superior, the default decision is **do not add an LLM or agent**.

## Evidence discipline

Claims must be separated into:

- FACT
- EVIDENCE
- ASSUMPTION
- HYPOTHESIS
- DECISION
- OPEN QUESTION

Evidence levels:

- E0 — speculation
- E1 — plausible inference
- E2 — vendor / consultancy claim
- E3 — named deployment
- E4 — measured production evidence

Each material claim should also carry a confidence score (0–100%).

## Repository structure

- `docs/00_charter/` — problem statement, questions, evidence rules
- `docs/10_foundations/` — deterministic vs probabilistic, ML/LLM/agent boundaries
- `docs/20_domains/` — banking, trading, DWH/BI, insurance, telecom, etc.
- `docs/30_cross_domain/` — recurring patterns across industries
- `docs/40_evidence/` — deployments, outcomes, failures and counterexamples
- `docs/50_analysis/` — capability, displacement and economics matrices
- `docs/90_conclusions/` — conclusions only when evidence supports them
- `docs/94_ai_sessions/` — auditable AI-session trail, protocols and handovers

## Research stance

This project does **not** begin with the assumption that agentic AI replaces enterprise software. It explicitly tests where deterministic systems remain superior and where AI adds genuine economic or operational value.
