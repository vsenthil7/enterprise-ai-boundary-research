# Per-Turn Git Protocol

## Purpose

Preserve a durable, auditable trail of substantive research turns without mixing raw session history with polished research conclusions.

## Required per substantive turn

Create a turn artifact containing:

1. user prompt / request
2. assistant response or response summary when exact text is unavailable
3. timestamp
4. research topic
5. claims introduced or changed
6. evidence used
7. decisions
8. open questions
9. corrections / disagreements
10. resulting Git changes

Create a separate context manifest containing:

- prior project context materially used
- files/repositories consulted
- web sources consulted
- external connectors consulted
- assumptions imported from earlier turns
- exclusions / constraints

## Important limitation

The context manifest records the relevant context, sources and assumptions actually used for the answer. It does **not** claim to export hidden chain-of-thought, hidden model state or inaccessible system context.

## Turn pipeline

`prompt -> context/evidence used -> reasoning classification -> response -> claims/evidence -> decisions/open questions -> commit`

## Classification vocabulary

- FACT
- EVIDENCE
- ASSUMPTION
- HYPOTHESIS
- DECISION
- OPEN QUESTION

## Separation rule

- `docs/94_ai_sessions/` = audit/session trail
- charter/foundations/domains/evidence/analysis/conclusions = durable research output

Do not use session transcripts as if they were evidence. Promote claims into research documents only when they have been classified and, where necessary, externally evidenced.

## Multi-AI rule

ChatGPT and Perplexity may contribute independently. Preserve disagreements rather than silently averaging them. Put cross-AI disputes under `docs/94_ai_sessions/cross_ai/disagreements/` and resolved synthesis under `docs/94_ai_sessions/cross_ai/synthesis/`.
