# UX review: {{CHANGE_NAME}}

Work item: {{WORK_ITEM_REFERENCE}}  
Applicable intent: {{INTENT_SECTIONS_AND_REVISION}}  
Reviewer and date: {{REVIEWER_AND_DATE}}  
Implementation/artifact: {{REVIEWED_REVISION}}  
Evidence location: {{SCREENSHOTS_RECORDINGS_AND_NOTES}}

## Before implementation

Describe the actual task and participants, actor permissions/scope, entry point, vocabulary, steps, handoffs, related features and help. Identify the user's resource costs and relevant operating conditions.

{{JOURNEY_AND_CURRENT_BURDEN}}

Record significant design choices and their rationale. Distinguish decisions from assumptions or pending operating policy. Routine decisions within authorized intent should proceed without an extra approval step.

{{DESIGN_DECISIONS_AND_OPEN_QUESTIONS}}

## Inspect the implemented journey

Record the environments and interactions actually inspected. Use relevant desktop/mobile widths, keyboard and assistive technology checks, and actual-user involvement where needed to assess the intended experience.

| Concern | Observation and evidence | Correction or remaining uncertainty |
| --- | --- | --- |
| Entry points, labels and navigation | {{NAVIGATION_OBSERVATION}} | {{NAVIGATION_ACTION}} |
| Task steps, local context and related features | {{JOURNEY_OBSERVATION}} | {{JOURNEY_ACTION}} |
| Permissions and information scope | {{SCOPE_OBSERVATION}} | {{SCOPE_ACTION}} |
| Loading, empty, error, success and recovery | {{STATE_OBSERVATION}} | {{STATE_ACTION}} |
| Keyboard, focus, announcements and accessibility | {{ACCESSIBILITY_OBSERVATION}} | {{ACCESSIBILITY_ACTION}} |
| Responsive layout and operating conditions | {{LAYOUT_OBSERVATION}} | {{LAYOUT_ACTION}} |
| Handoffs, help and learning effort | {{HANDOFF_OBSERVATION}} | {{HANDOFF_ACTION}} |

A concern may be inapplicable; state why. Distinguish rendered observations from source inspection and simulated behavior from actual-user evidence.

## Acceptance

{{WHAT_WAS_OBSERVED_WHAT_CHANGED_AND_WHAT_REMAINS}}

Record whether the affected journey satisfies its criteria, any blockers, the next responsible action and the evidence location in the work item. A passing visual check alone does not establish domain correctness, accessibility conformance or actual customer value.
