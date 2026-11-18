# Delivery evidence: {{CHANGE_NAME}}

Work item: {{WORK_ITEM_REFERENCE}}  
Applicable intent: {{INTENT_SECTIONS_AND_REVISION}}  
Owner/reviewer and date: {{OWNER_REVIEWER_AND_DATE}}  
Commit/PR and artifact: {{SOURCE_AND_ARTIFACT_REFERENCES}}

## Intended outcome and scope

{{REQUESTED_OUTCOME_ACCEPTANCE_CRITERIA_AND_AUTHORIZED_SCOPE}}

Record whether current intent was preserved or revised, with references to any superseded decisions.

## Evidence against acceptance

| Acceptance criterion | Method and environment | Actual result and evidence | Limits or next action |
| --- | --- | --- | --- |
| {{CRITERION_REFERENCE}} | {{CHECK_ENVIRONMENT_REVISION_AND_DATA}} | {{OBSERVED_RESULT_AND_REFERENCE}} | {{LIMIT_AND_RESPONSIBLE_ACTION}} |

Include only checks actually performed. Explain a relevant omitted check or inapplicable concern. Keep failures, uncertainty and synthetic fixtures explicit.

## Current delivery state

Use established, failed, unverified or inapplicable, with evidence appropriate to each claim.

| Claim | State | Supporting evidence or remaining acceptance |
| --- | --- | --- |
| Implemented | {{IMPLEMENTATION_STATE}} | {{CHANGE_EVIDENCE}} |
| Checked locally | {{LOCAL_CHECK_STATE}} | {{ACTUAL_CHECK_RESULTS}} |
| Running locally | {{LOCAL_RUNTIME_STATE}} | {{INSTANCE_ARTIFACT_AND_DATA_EVIDENCE}} |
| Deployed | {{DEPLOYMENT_STATE}} | {{TARGET_ARTIFACT_CONFIGURATION_AND_MIGRATIONS}} |
| Verified in actual work | {{ACTUAL_WORK_STATE}} | {{PARTICIPANTS_DEPENDENCIES_AND_OBSERVATIONS}} |
| Value observed | {{VALUE_STATE}} | {{COMPARISON_PERIOD_OUTCOMES_AND_RESOURCE_COSTS}} |

## Compatibility, operations and review

{{EXISTING_DATA_CONTRACTS_PERMISSIONS_RECOVERY_AND_REVIEW_RESULTS}}

For relevant changes, record migration/restart/concurrency/recovery observations, rendered UX review and the exact running version. Match the detail to the scope.

## Remaining work and learning

{{OPEN_ACCEPTANCE_OWNER_NEXT_ACTION_AND_BUDGET}}

State which claims remain unverified, the evidence needed to resolve them, and any correction to intent, scenarios or instructions. Separate completed work from operational acceptance or value observation that remains open.
