# Adopt the project templates

[Practical companion](../docs/practical-companion.md) · [White paper](../README.md)

Copy only the templates the project needs. Replace every `{{PLACEHOLDER}}` with a real decision, path, command or responsibility. Review them with the people accountable for the work before treating them as project rules.

| Template | Example destination in an adopting project | Configure first |
| --- | --- | --- |
| [Agent instructions](AGENTS.template.md) | Root `AGENTS.md`, or the equivalent supported by the agent tool | Intent path, contracts, tracker rules, authority and validation commands. |
| [SPDD](spdd.template.md) | `docs/spdd/project-spdd.md` | Current intent, REASONS canvas, owners, budgets, acceptance and superseded decisions. |
| [UX review](ux-review.template.md) | `docs/ux/<work-item>-review.md` | Actual participants, journeys, environments, observations and follow-up. |
| [Delivery evidence](delivery-evidence.template.md) | The work item or `docs/evidence/<work-item>.md` | Revision/artifact, checks performed, observed results and remaining acceptance. |

These filenames deliberately contain `.template`: they are examples until adapted. Verify how the selected agent discovers project instructions; a file's presence alone does not activate it. The instructions template points to the adopting project's configured intent document, rather than making this white paper a substitute for local requirements.

Use the existing tracker and hierarchy. Azure DevOps, GitHub issues, Jira or another agreed mechanism can hold the traceability record. Avoid duplicating the current specification across work items, templates and status reports; link to it and record the decisions specific to the change.

After setup, run the companion's [guidance evaluation](../docs/practical-companion.md#evaluate-the-guidance-itself) through a fresh task. Retain the configured guidance revision, actual behavior and any correction.
