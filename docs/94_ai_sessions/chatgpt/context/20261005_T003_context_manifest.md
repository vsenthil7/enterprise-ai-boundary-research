# Context Manifest — T003

## Material context used

- User had already granted GitHub broad access and expected AI-managed Git.
- The research requires per-turn audit artifacts and durable separation between research outputs and session history.

## Connector evidence

- GitHub repository write actions were available.
- GitHub app-specific permission was verified as `Allow all actions`.
- No repository-creation action was exposed in the available action set.

## Constraints

- Do not ask the user to repeatedly change permissions when permission is already sufficient.
- Do not claim mobile caused the issue without evidence.
- Record the manual bootstrap accurately.

## Limitation

This manifest records the operational evidence used for the answer, not hidden chain-of-thought.
