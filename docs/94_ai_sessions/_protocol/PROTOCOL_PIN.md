# Protocol Pin

Repository: vsenthil7/enterprise-ai-boundary-research (public)
Protocol for AI sessions: **Git Turn Protocol v1.0** (2026-10-12), the owner's single protocol for all his repositories. Its full text is kept privately; AI sessions working for the owner are given it at the start of a page.
Active from: 2026-10-12 10:47 (CLAUDE-T007).

## What v1.0 adds here
- Every turn: pull first, record prompt and reply verbatim, one commit per turn, verify the remote, report Git evidence.
- Every turn record states its token usage, with an honest label (measured / user-stated / estimate / unavailable).
- Secret scan before every commit.

## Local rules (kept from `PER_TURN_GIT_PROTOCOL.md`, which stays unchanged)
- Each turn also has a context manifest (sources, files, connectors and assumptions actually used).
- Session trail (`docs/94_ai_sessions/`) stays separate from research output (charter, foundations, domains, evidence, analysis).
- Classification vocabulary: FACT, EVIDENCE, ASSUMPTION, HYPOTHESIS, DECISION, OPEN QUESTION; evidence levels E0–E4 (README).
- Cross-AI disagreements are kept, not averaged: `docs/94_ai_sessions/cross_ai/`.

## Public-repo rules
- This repository is public. No private working records, private repository names, session identifiers, personal data, employer or internal product names, or secrets.
- Turn records here contain only what is fit to publish.

## Dated decisions
- 2026-10-12 10:47 (CLAUDE-T007, owner-stated "go ahead"): switch to Git Turn Protocol v1.0 as a pointer only; previous protocol file kept unchanged.
