# {{PROJECT_NAME}} product intent

Canonical location: `{{INTENT_PATH}}`  
Accountable person or team: {{INTENT_OWNER}}  
Current revision/date: {{INTENT_REVISION}}  
Applicable work tracking: {{TRACKER_RULES}}

This is the current intent record. Keep historical decisions identifiable and explicitly superseded where necessary.

## Mission and value claim

{{WHOSE_WORK_IMPROVES_AND_HOW}}

Baseline, comparison and observation period: {{VALUE_COMPARISON}}.  
Participants who may gain or bear additional work: {{USER_ECOSYSTEM}}.  
Creation/evolution resource budget: {{DEVELOPMENT_BUDGET}}.  
User/operator resource budget and necessary quality thresholds: {{OPERATING_BUDGET_AND_QUALITY}}.

## REASONS canvas

### Requirements

{{OBSERVABLE_OUTCOMES_SCOPE_AND_NON_GOALS}}

Identify necessary reliability, security, accessibility and performance conditions. Define the evidence required for each relevant condition.

### Entities

{{DOMAIN_ENTITIES_IDENTITIES_RELATIONSHIPS_AND_LIFECYCLES}}

### Approach

{{DESIGN_APPROACH_REUSE_AND_SIGNIFICANT_TRADEOFFS}}

### Structure

{{COMPONENT_BOUNDARIES_AND_LINKED_CONTRACTS}}

### Operations

{{ACTUAL_ENVIRONMENTS_DEPENDENCIES_RELEASE_RECOVERY_AND_SUPPORT}}

### Norms

{{DOMAIN_RULES_AND_WORKFLOW_INVARIANTS}}

### Safeguards

{{PERMISSIONS_PRIVACY_RETENTION_AUDIT_AND_FAILURE_BOUNDARIES}}

## Journeys and acceptance

For each affected journey, identify the actor/scope, entry point, handoffs, prerequisites, success, failure and recovery. Include relationships with other journeys and the operating environment.

| Intent section | Participant/journey | Observable acceptance criterion | Required evidence and environment |
| --- | --- | --- | --- |
| {{SECTION_REFERENCE}} | {{ACTOR_AND_JOURNEY}} | {{EXPECTED_BEHAVIOR_AND_FAILURE_BOUNDARY}} | {{VALIDATION_AND_LIMITS}} |

## Open decisions and assumptions

{{UNCERTAINTIES_CONSEQUENCES_OWNERS_AND_BOUNDED_NEXT_STEPS}}

Separate a confirmed requirement from an inference or proposed decision. Identify what work can proceed independently and what depends on resolution.

## Change protocol

1. Identify applicable current intent and the governing work item before implementation.
2. Record authorized intent changes here before dependent code changes; identify the decision owner and any superseded requirement.
3. Update acceptance criteria, linked contracts, relevant work hierarchy and scenarios affected by that decision.
4. Implement, test and review in increments, preserving existing data and supported behavior.
5. Link implementation and evidence back to the work item and intent sections. Report unverified release or actual-work acceptance explicitly.
6. Correct this model when observations in the customer's work contradict it.

## Decision history

| Date/revision | Decision and rationale | Owner/work item | Supersedes |
| --- | --- | --- | --- |
| {{DECISION_DATE}} | {{DECISION_AND_REASON}} | {{DECISION_OWNER_AND_REFERENCE}} | {{SUPERSEDED_REQUIREMENT_OR_NONE}} |
