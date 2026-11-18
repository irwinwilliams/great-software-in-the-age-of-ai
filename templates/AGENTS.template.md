# {{PROJECT_NAME}} operating instructions

Template: copy to the instruction location supported by the project's agent tool, replace every placeholder, and resolve all referenced documents before use.

## Required project context

- Canonical intent: `{{INTENT_PATH}}`.
- Applicable architecture and contracts: `{{CONTRACT_PATHS}}`.
- Person or team accountable for intent, scope and budgets: {{INTENT_OWNER}}.
- Work tracking and hierarchy: {{TRACKER_RULES}}.
- Engineering validation commands and required environments: {{VALIDATION_COMMANDS}}.
- UX review guidance and evidence destination: `{{UX_REVIEW_PATH}}`.

## Before implementation

- Read the canonical intent's mission, constraints, change protocol and sections relevant to the request, including applicable linked contracts. Inspect existing behavior and code before choosing an implementation.
- Identify or create the governing work item using the agreed tracker. Cite applicable intent sections and record the requested outcome, scope, acceptance criteria and important uncertainties before changing implementation files.
- Apply current authorized direction. When it changes intent, update the canonical record before dependent implementation and identify superseded decisions. When intent is preserved, record alignment in the work item.
- Resolve missing, ambiguous or conflicting product decisions before dependent work. Clarify consequential changes to intent, scope, constraints or budgets with the accountable person or team while continuing independent authorized work.

## While implementing

- Complete the affected journey and reuse the established architecture. Preserve existing records, contracts and supported behavior.
- Test and review during construction. Select checks appropriate to the change's mechanisms and consequences, using realistic infrastructure when persistence or integration behavior matters.
- For user-facing work, follow the configured UX guidance and inspect implemented journeys, permissions, related features, accessibility and relevant desktop/mobile states.
- Make failures observable and recoverable. Keep test fixtures explicit and actual failed operations visibly failed.
- Use the project's approved secret mechanism. Keep credentials out of source control, client code and logs.
- Act within the task's authorization and established environment controls. The instruction file itself does not grant permission to contact people, publish data or change external systems.

## Before completion

- Compare the actual changes and relevant validation with the cited intent and acceptance criteria. Correct discrepancies and reconcile documentation with verified behavior.
- Record actual results, environments, revisions/artifacts, review findings, corrections and remaining uncertainties. Link commits and pull requests when present.
- Report implementation, local checks, running instances, deployment, actual-work verification and observed value separately. Mark a claim unverified when its evidence is absent.
- Carry authorized work through the agreed scope. Keep unresolved operational acceptance visible and make the next responsible action clear.
