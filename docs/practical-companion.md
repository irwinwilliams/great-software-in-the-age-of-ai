# Practical companion: carrying intent into working software

[Return to the white paper](../README.md) · [Start with the templates](../templates/README.md)

The white paper describes software that creates value in the customer's world. This companion provides a way to carry its intent through delegated engineering, review, release and observation. It develops the responsibilities and evidence in [section 6](../README.md#6-people-and-agentic-resources).

Use the method in small increments. Choose artifacts and checks proportionate to the work. A document, a completed work item and a passing test each establish something specific; the customer's actual work establishes whether the intended improvement landed.

## Start in an existing project

1. Identify the person or team accountable for product intent and the decisions agents may make within it.
2. Copy and adapt the [SPDD template](../templates/spdd.template.md) into the project's agreed intent location. Record what is known, what remains uncertain and which earlier decisions have been superseded.
3. Adapt the [agent instructions](../templates/AGENTS.template.md) to the tool's supported project-instruction location. Replace every placeholder with real paths, tracking rules and commands. Keep one authoritative record for each concern.
4. Put the applicable intent sections, requested outcome and acceptance criteria in the work item before implementation.
5. Use the [UX review](../templates/ux-review.template.md) for affected journeys and the [delivery evidence](../templates/delivery-evidence.template.md) to report what was established.
6. Run a fresh task to check whether the instructions lead to the expected decisions. Correct discovery or interpretation problems before expanding delegation.

The [adoption instructions](../templates/README.md) show example destinations. The templates are starting points: copying them without resolving their placeholders does not establish a working process.

## Make authoritative inputs discoverable

People retain authority over intended value, scope, necessary qualities and resource budgets. Agents can make routine engineering decisions within that authority. Clarification belongs at a consequential missing decision or a change to those boundaries; routine authorized work should continue.

Agree where each kind of guidance lives:

| Artifact | Question it answers | Responsibility |
| --- | --- | --- |
| Product intent | Whose work improves, what outcome matters, and which constraints hold? | The accountable person or team establishes and revises it. |
| Project instructions | Which sources must an agent consult, and what workflow must it follow? | The project maintainer makes them discoverable by the tools in use. |
| Contracts and architecture | How do identities, data, components and dependencies fit together? | Engineering maintains them against the implemented system. |
| Work item | What change is authorized, why, and how will acceptance be assessed? | The owner connects the request, applicable intent, decisions and evidence. |
| Review and delivery evidence | What was checked, in which environment, and what remains uncertain? | The implementer and reviewers record results; responsible people own release and acceptance decisions. |

SPDD means Structured Prompt-Driven Development here. Its REASONS canvas records Requirements, Entities, Approach, Structure, Operations, Norms and Safeguards. It is one concrete way to maintain intent; equivalent project artifacts can serve the same purpose.

Give sections stable references. Separate current requirements from historical decisions and execution logs. When a decision changes, identify what it supersedes and reconcile the current requirement. Current authorized direction should be reflected in the record before dependent implementation. Resolve conflicts that could change the result rather than silently choosing whichever statement is convenient.

## Carry intent through a change

The stages below can overlap and repeat. Each carries enough context forward for the next decision.

| Stage | Authoritative inputs | Required output and evidence |
| --- | --- | --- |
| Understand the work | Observed work, participant input, existing behavior and operational constraints | A domain account corrected through user assent; an explicit uncertainty or value claim. |
| Establish intent | Domain account, accountable people's decisions and resource budgets | Current intent sections, scope, necessary qualities and acceptance criteria. |
| Explore and design | Intent, contracts, architecture and affected journeys | Alternatives and tradeoffs where consequential, a coherent journey, and feasibility evidence for significant uncertainty. |
| Build | Applicable intent sections and authorized work item | Integrated behavior, relevant tests and preserved data/contracts. Link commits and pull requests when they exist. |
| Verify and review | The same intent, actual changes and acceptance criteria | Engineering and rendered UX observations, exceptions, corrections and remaining limits. |
| Release and observe | Verified artifact, operating procedures and agreed exposure | Exact running version, migration/recovery evidence, actual-work observations and a decision about the next investment. |

A useful record connects **intent → acceptance criterion → implementation → evidence → observed outcome**. A single work item can hold this for a small change. Larger work can use the project's hierarchy, such as Epic → Feature → Product Backlog Item → Task in Azure DevOps. This method does not require a particular tracker.

Review findings should identify the affected intent or constraint, connect it to observed behavior, and justify a correction. Distinguish a demonstrated defect from an inference or an unanswered question. A separate reviewer can help challenge shared assumptions; the review responsibility also exists when one person or agent covers several stages.

## Match quality promises to evidence

Choose checks for the failure modes and consequences of the change.

- For durable data, exercise the relevant database technology, migrations, concurrent updates, retries and restart behavior. Confirm that existing records and consumers remain usable.
- For permissions, exercise authorized and unauthorized actors, including the scope of reads, writes and exports. Establish the required security protections from the actual operating context.
- For user-facing work, inspect complete affected journeys: entry points, vocabulary, navigation, related features, handoffs, help, accessibility and loading, empty, error and recovery states. Inspect implemented screens at relevant widths and with appropriate interaction methods. Involve actual users where their experience is needed to establish usability or accessibility.
- For performance or operating cost, use representative data, workloads and environments against an explicit threshold or budget.
- For release, identify the exact artifact and environment, retain the recovery path and check the running behavior.

A bounded documentation change may need source, link and reading-flow checks. A persistence or permission change needs evidence about those mechanisms. Repeating checks that establish no additional confidence consumes the same resources the software is meant to conserve.

Simulations and browser fixtures help expose problems. Their agreement with an implementation can also preserve a shared misunderstanding. Calibrate them against observed work and independent examples, and record what they omit. The boundary between modeled success and actual operation remains the concern described in [section 7](../README.md#7-architecture-should-be-observed-in-the-world-it-serves).

## Report completion precisely

Record a baseline or revision, environment, method, result and limitation for each material claim.

| Claim | Evidence it needs |
| --- | --- |
| Implemented | The identified change exists and implements the stated behavior. |
| Checked locally | Relevant checks ran against an identified revision or artifact, with actual results. |
| Running locally | The identified application instance was exercised; retained data and configuration were accounted for. |
| Deployed | The target environment runs the identified artifact with required configuration and migrations. |
| Verified in actual work | Intended participants completed relevant journeys with actual dependencies and operating conditions. |
| Value observed | Outcomes and resource costs across affected participants were assessed against a credible comparison over an appropriate period. |

These claims can occur at different times. A documentation publication, for example, can establish that guidance is available while its effect on later engineering remains unmeasured. Keep remaining operational acceptance visible.

## Worked example: an intent document that agents could miss

In the Grid attendance project, a versioned SPDD described product intent and a protocol for changing it. Root project instructions required work items to align with SPDD, but did not name the document or explicitly require agents to read it.

The omission became visible when the user asked what forced agents to consult the specification. The project had a documented expectation without a sufficiently explicit route from instruction discovery to its application.

The correction added rules to the project's root instructions:

1. Read the canonical SPDD and relevant contracts before implementation.
2. Cite applicable sections, the requested outcome and acceptance criteria in the governing work item.
3. Update changed intent before code; record alignment when the existing intent remains valid.
4. Resolve consequential missing or conflicting intent before dependent work.
5. Compare implementation and validation with the cited intent before completion.
6. Distinguish implementation, checks, runtime changes, deployment and actual-work verification.

The observed result was an explicit instruction change, with document references and the source diff checked. It did not establish that every later agent would comply or that customer outcomes improved. No automated merge gate was added by that correction. This is a bounded project observation, not experimental validation of the wider method.

## Evaluate the guidance itself

Treat project instructions as part of the system being developed.

Start a fresh task through the agent's normal project entry point, without reminding it about SPDD. Use a bounded representative change and retain the instruction/specification revision and resulting work record. Check whether the agent:

- Finds the correct current sources and cites the applicable sections.
- Converts the request into observable acceptance criteria.
- Recognizes a deliberate mismatch between a proposed change and current intent.
- Resolves stale or superseded guidance consistently with current authorized direction.
- Selects relevant evidence and reports its limits accurately.

Use synthetic or otherwise approved scenarios for deliberate mismatches. Inspect the resulting behavior and artifacts. An assertion that a file was read is weak evidence of correct application.

Keep an authorized maintenance change and an intent-changing request as separate cases. Record omissions, unnecessary clarification, contradictory decisions and unsupported completion claims. Repeat after material changes to instructions, tooling or context, then assess the cost and benefit of the workflow.

Instructions establish obligations. Automated checks can require resolvable references, acceptance records, evidence fields or successful relevant checks. Those checks establish observable conditions; they cannot prove that an agent understood intent or that the result creates customer value. Add a blocking check when the failure it prevents justifies its maintenance cost.

## Close the loop in the customer's world

Use actual operation to correct both the software and the model guiding it. Investigate whether a disappointing result came from implementation, misunderstood work, changed conditions or an ineffective value claim. Update the relevant intent, scenarios, instructions and checks so the lesson reaches future work.

Assess outcomes by participant: completion time, errors, recovery, attention, accessibility, support effort and coordination can reveal improvements or transferred burdens. Choose a credible comparison and time horizon, and decide whether to improve, change direction or stop within the available budget, as discussed in [section 10](../README.md#10-let-actual-value-decide-what-happens-next).

The first adoption increment can be small: one current intent record, one configured instruction file, one tracked change, one coherent review and an honest evidence record.
