# Great Software in the Age of AI

*Taste, intent, domain understanding, and the discipline of creating net value*

## Abstract

Great software is a net creator of value. It solves a real problem, fits the work of the people involved, uses their resources well, and remains reliable and easy to change as it evolves. Meeting the stated requirements is an inadequate definition of greatness, especially when requirements, in all their forms, are so often understated.

AI changes the economics of implementation. It makes it increasingly practical to delegate engineering responsibilities, explore alternatives, construct tests, and replace implementations. That abundance makes the questions of intent and judgment more consequential. What is worth building? Whose work will improve? What resources will the solution consume? What evidence will establish that the dream has become useful in the customer's world?

This paper argues for people who understand the work, care about the whole solution, and take responsibility for realizing its intended value. They bring taste, intent, judgment, and humility to that responsibility, whether working individually or as a team. Engineering work can be delegated within explicit constraints and resource budgets, with validation grounded in the whole user ecosystem. Increasingly rich simulations of that ecosystem offer an environment for developing and evaluating software. The simulation gives the artifact its form. The artifact must then work in the customer's actual environment.

Research supports many elements of this position. It also leaves important questions open about how design authority should be organized, the sufficiency of simulated users, and the relationship between development speed and realized value. Those boundaries are part of the argument.

## 1. Greatness begins in the customer's actual work

Great software solves a real user problem, is easy to use, and stays reliable and maintainable as it evolves. Each part of that sentence contains more than it first appears to contain.

The user is an ecosystem. There is the person using the interface, but there are also administrators, process participants, operations staff, support staff, and people working upstream and downstream of the application. All are involved in the work. A system that makes one person's task easier can make another person's task harder. The assessment has to follow the work far enough to see that.

The customer buys an improvement in their world. They may be trying to complete a reconciliation, approve a claim, coordinate a delivery, understand a case, or make a decision. The software occupies a place in that activity. Its quality ultimately relates to how well it enables the customer to extract value from the targeted domain.

Adequate software meets the requirements. Great software makes the work better, including the needs that nobody adequately articulated in a requirements document. This is why requirements are necessary but cannot be the final account of value.

The standard is demanding: the customer's actual work should show better outcomes for the resources spent. The benefit must exceed the total cost of adopting, using, operating, and evolving the software across the whole user ecosystem. Those resources include money, time, attention, learning, coordination, and the effort needed to recover when something goes wrong.

Research on the economic value of IT supports this wider accounting. Brynjolfsson and Hitt showed why organizational investments and changes in work practices belong alongside the technology when assessing its value. Their research also emphasizes that important benefits can be intangible and difficult to measure. A license fee and an infrastructure bill are therefore incomplete accounts of the investment. [Brynjolfsson and Hitt, 2000][brynjolfsson-hitt]

The costs can also be hidden inside apparently successful operation. Gasser's field research documented people sustaining computer systems through manual workarounds and duplicate systems. Successful outputs did not mean that the software itself had removed the underlying burden. [Gasser, 1986][gasser]

Net value should consequently be examined by participant before it is aggregated. A gain for the buyer does not settle what happened to the administrator, the end user, or the person now correcting the data. The qualities required for those people to do their work remain constraints on the solution.

## 2. People must carry the dream

Great software depends on people who understand the work, care about the whole solution, and take responsibility for realizing its intended value.

Design carries responsibility for the intent of the whole solution. This responsibility extends beyond the appearance of an interface. It concerns what the software is for, how its parts fit together, which tradeoffs are acceptable, and whether the result deserves a place in the customer's world. An individual can carry this responsibility. A pair or a small team can also develop and exercise it together.

Shared understanding gives people and agents a basis for making decisions. It becomes consequential when people use it to develop intent, exercise judgment, and make commitments. A team can discover a possibility that none of its members initially conceived, challenge one another's assumptions, and give that possibility a coherent form. Decisions still need to be made and owned. User input informs those choices; it is not a vote on the solution.

> The designer's voice is an echo from the future. What is created is a shadow of what eventually worked.

That is an account of the imaginative work of design. People see a possible future in which the customer's work is better and develop that possibility into a coherent solution. The vision may originate with one person or emerge through collaboration. Taste is the judgment involved in deciding what belongs, what is unnecessary, and how the whole should feel and function.

Brooks describes one way to preserve coherence. He connects conceptual integrity with ease of learning, use, maintenance, and extension, and recommends giving a chief designer authority over the design. This is experienced practitioner reasoning for a particular arrangement of responsibility, rather than a controlled demonstration that one designer always produces the greatest customer value. [Brooks and Woods, 2010][brooks]

Curtis and colleagues identified exceptional designers who integrated domain knowledge with computational structure and carried a project's vision. They also observed design direction emerging from small groups and teams broadening exploration through alternatives and challenges to assumptions. Their findings support integrating judgment and collaborative inquiry, while leaving a universally superior allocation of authority unresolved. [Curtis, Krasner, and Iscoe, 1988][curtis]

A meta-analysis covering 42 independent samples found a positive relationship between shared leadership and team effectiveness, including a contribution beyond vertical leadership. Shared leadership is a broader construct than shared final design authority, and the outcomes were not the full lifecycle customer value proposed here. The findings support taking collaborative leadership seriously while leaving the arrangement appropriate to a particular software team open to investigation. [Wang, Waldman, and Zhang, 2014][shared-leadership]

Software field research also documents ways to distribute authority while preserving alignment. A study of two large Ericsson projects examined combinations of team autonomy, centralized decisions, and communities involving teams and experts. It identifies workable coordination mechanisms; it does not establish which arrangement maximizes net customer value under matched budgets. [Moe and colleagues, 2021][moe]

Different arrangements should be judged by the net customer value they produce within comparable constraints and resource budgets, while preserving coherence and accountability. The assessment should include the costs of coordination, delayed decisions, and mistakes in each arrangement. Responsibility for the whole needs to remain clear as people collaborate and make decisions.

The purpose of authority is to realize value. Its organization is itself a design choice that must answer to that purpose.

## 3. Become sufficiently part of the customer's world

People earn an understanding of the domain by investing time and emotion in it. They make the connection between the problems users get paid to solve and the way software might help solve them. They observe actual work across the user ecosystem and validate their interpretation through user assent.

Developers have to become the customer in a way that lets them experience the value dream from the customer's perspective. They need to locate themselves in the customer's world: the interruptions, the handoffs, the constraints, the consequences of an error, and the reasons a seemingly awkward practice exists. That understanding empowers a vision of how the software can fit into the milieu.

This is more than collecting a list of requested features. Users reveal problems and constraints. The people developing the vision use taste and judgment to determine where software can create the most value.

There is an important distinction between user *input* and user *feedback*. At the design stage, we need input about the work before a proposed interface or solution frames the conversation. Feedback on an existing proposal is useful too, but it answers a different set of questions. The people responsible for design retain authority over the solution while allowing users to correct misunderstandings about their work and its constraints.

The distinction has methodological support. Holtzblatt and Beyer's Contextual Design describes work through roles, communication, actions, artifacts, physical surroundings, and social and emotional context. These representations ground invention in observed work. The method supports deep user involvement; it does not determine who should have final design authority. [Holtzblatt and Beyer, 1996][contextual-design]

A field study of 17 large software projects similarly identified scarce application-domain knowledge, conflicting requirements, and communication breakdowns as important influences on productivity and quality. It supports treating domain understanding as engineering substance. Its historical, qualitative findings do not establish the performance of today's AI systems. [Curtis, Krasner, and Iscoe, 1988][curtis]

Becoming the customer is an investment in understanding, not a claim to have acquired every customer's experience. User assent and observation remain necessary to correct our model.

The same applies to the engineer. Taste, domain understanding, and ownership matter. A great engineer translates intent into clear, changeable software and cares about the user's resources and the value created. And there is another quality: humility. The engineer must remain willing to discover that their understanding, implementation, or preferred technique is wrong.

## 4. UX spends the customer's resources

Establish a resource budget. In some cases the scarce resource is time; in others it is money; in still others it is attention.

Great UX enables users to make efficient use of those resources while accomplishing their work. If users must spend more resources than necessary to use the software, the excess represents the quantum of work left to improve the UX.

An unnecessary decision consumes attention. A confusing handoff consumes coordination. An error that requires a support call consumes resources across several roles. A redesign that makes a familiar task temporarily difficult consumes learning time even if the eventual interaction is better. These expenditures belong in the assessment of the experience.

Relevant, appropriate UX preserves the judgment, control, and verification that the work requires. Efficiency concerns avoidable expenditure in achieving the intended outcome. A short interaction that produces an incorrect or unusable result has not met that standard.

There are two connected budgets to establish: the resources available to create and evolve the solution, and the resources the solution may require from its users and operators. A cheap implementation can be expensive to live with. A demanding implementation may be justified if it produces a sufficiently valuable improvement in the customer's work.

### Quality belongs inside the definition of complete

Reliability is multi-pronged. It includes successful operation, graceful failure, resilience, security, adequate testing, and performance appropriate to the work. Accessibility determines whether people in the intended user ecosystem can participate at all. Maintainability determines whether the solution can continue to serve that ecosystem as circumstances change.

These qualities are conditions of delivering the capability. The domain and the user ecosystem determine what is non-negotiable. Designers weigh tradeoffs by their effect on customer value. If the necessary conditions exceed the resource budget, revisit the scope or the budget.

The questions should be direct. Will we knowingly release software that does not work well enough for its intended use? Will we omit security we understand it to need? Will we miss the accessibility mark for a group of users we intend to serve? Will we establish a necessary performance threshold and then disregard it?

For established requirements necessary to the intended use, the answer is no. A narrower release must still provide complete, usable journeys for the people it serves.

| Concern | What the commitment needs to establish |
| --- | --- |
| Reliability | Required behavior, acceptable failure conditions, recovery expectations, and the circumstances under which these apply. |
| Security | The protections required by the understood threats and operating context, with evidence that those protections are implemented. |
| Accessibility | Complete journeys usable by the relevant users, including their assistive technologies and conditions of use. |
| Performance | Measurable thresholds under representative workloads, data volumes, and environments. |

There are established practices for making such commitments explicit. Google's example error-budget policy suspends ordinary releases after the service exceeds its agreed error budget, while allowing urgent repairs and security fixes. NIST's SSDF calls for defined security requirements and verification during development. W3C recommends combining accessibility standards evaluation with evaluation involving disabled users. These are engineering policies and guidance, rather than experiments proving a universal release rule. [Google SRE, 2018][error-budget]; [NIST, 2022][ssdf]; [W3C WAI, 2024][wai]

A requirement can acknowledge bounded risk and still be firm. An agreed reliability level need not promise that failure is impossible. The important discipline is to establish justified conditions and evaluate the implementation against them.

## 5. If development is so much faster, where is the software?

Introducing agentic resources can dramatically increase the rate of output. Going from words to code becomes fast. We can produce more tests, explore more implementations, and automate more of the path to deployment.

That raises a reasonable question: if we obtain a tenfold improvement in development speed, why do we not see ten times more software emerge into the world?

The question exposes what we are counting. Ten times more code, test cases, or deployments is a different observation from ten times more complete solutions. The result we care about is more customer value realized within the available resources.

Current evidence supports gains in particular activities, with considerable variation. Three randomized field experiments involving 4,867 developers found a pooled increase of about 26% in completed tasks with access to a coding assistant; the individual experimental estimates were noisy. These experiments studied code-completion assistance and task outcomes. They do not establish a tenfold improvement across the entire lifecycle, nor do they impose a ceiling on subsequent agents. [Cui and colleagues, 2025][cui]

DORA's later analysis describes higher AI adoption as associated with both greater delivery throughput and greater instability. Its qualitative work also reports time moving from creation into auditing and verification. These findings challenge a simple conversion from faster generation to proportionately more finished, valuable software; they do not establish that AI cannot improve the complete process. [DORA, 2026][dora-ai]

In simple contexts, the customer is becoming the developer. The person with the problem can increasingly express an idea and obtain a working implementation. Yet the ways in which that person's imagined value can reliably land in production remain uneven. Construction is one part of realizing a solution in an environment with data, other systems, operational obligations, and other people.

The development practices worth prioritizing are those that directly improve the customer's ability to extract value from the domain. Faster engineering is valuable when it helps us realize that value dream more completely, explore it more intelligently, or use fewer resources in doing so.

## 6. People and agentic resources

In the age of AI, the team question becomes interesting again. One possible arrangement is *1+*: one human carrying intent and accountability, with agentic resources applied as the work requires. A pair or a small team can also develop intent and exercise judgment together, supported by agents. The work and the resource budget should inform the arrangement.

People retain intent, taste, and accountability. They decide what is worth building, which tradeoffs are acceptable, and whether the result creates value across the user ecosystem. Engineering work can be delegated. The degree of delegation justified in a particular workflow has to be established through its results.

Conway's law remains a useful prompt. If the structure of communication influences the structure of the system, then an agentic workflow needs communication and context appropriate to the desired solution. Conway's original argument concerned organizations; extending it to agents is a design inference. It is not evidence that naming agents after human departments will produce the right architecture. [Conway, 1968][conway]

The responsibilities we used to articulate as roles can also appear as stages along feature development. Domain analysis, architecture, implementation, testing, review, performance work, deployment, and observation are concerns the workflow must cover. They need not each imply a permanent person or agent.

| Stage | Responsibility | Evidence carried forward |
| --- | --- | --- |
| Understand the work | Identify the user ecosystem, its problems, constraints, and current resource expenditure. | Observations and a domain model corrected through user assent. |
| Establish intent | Choose the improvement worth realizing and define scope, budgets, and necessary qualities. | A clear value claim and conditions for an acceptable solution. |
| Explore and design | Develop the proposed experience and architecture; investigate significant uncertainties. | A credible path to completion, scenarios, alternatives, and feasibility evidence. |
| Build | Translate intent into a complete implementation. | Integrated behavior, changeable code, and the artifacts needed to operate it. |
| Verify and review | Evaluate behavior, architectural fit, required qualities, and evidence of value. | Tests, simulation results, measurements, review findings, and stated uncertainties. |
| Release and observe | Introduce the solution into the customer's environment and assess actual work. | Operational evidence, outcomes, resource costs, and corrections to the model. |

These stages describe responsibilities, not a requirement to finish learning before building. Work can loop, overlap, and proceed in small increments. Build in small changes, test and review continuously, and check the complete feature against intent, constraints, and resource budgets. Each stage should produce evidence that its concerns have been addressed.

### Autonomy needs a credible path

The agent can decide within agreed intent, constraints, and resource budgets. It seeks clarification from the responsible person or team when those boundaries need to change, or when it is unsure whether a consequential decision respects them.

In building, we are flowing forward in time, from nothing to a fully realized solution. The goal is to reach that solution, covering all of its concerns: architecture, testing, performance, operation, and the rest. A fast implementation of one visible part is insufficient evidence of completion.

The starting position needs enough domain understanding, intent, constraints, and resource information to reveal a credible path to completion. Details can emerge during construction. When uncertainty threatens the path, the agent should investigate and clarify the steps until there is a reasonable basis for proceeding.

Reasonable certainty must be supported by evidence. Sometimes the next justified step is a small experiment, a prototype, or a question about an observed constraint. The agent should make the uncertainty and its consequence specific. Changes to intent or budgets return to the people authorized to make those commitments.

Boehm and colleagues' Incremental Commitment Spiral Model provides a close methodological precedent: commitments grow alongside evidence about feasibility, stakeholder outcomes, risks, budgets, and schedules. This supports progressive clarification. It is a process framework, rather than experimental proof that this precise agent workflow will succeed. [Boehm and colleagues, 2014][icsm]

### Review is an engineering stage an agent can perform

Code review should check that the implementation expresses design intent, respects constraints and resource budgets, and remains easy to change. Its usefulness depends on what it establishes about the solution.

Research on human review found that understanding the code and its changes was central, and that review contributed knowledge transfer and alternative solutions as well as defect discovery. An agent performing this stage needs the context that makes those judgments meaningful. [Bacchelli and Bird, 2013][code-review]

The reviewer also needs to earn trust. A 2026 benchmark study found that models sometimes rejected correct implementations by misreading specifications or adding unstated requirements; more elaborate requests for criticism could increase those errors. The study used short programming tasks and specific models, so its results are a warning about demonstrated failure modes, not a universal limit on agentic review. [Jin and Chen, 2026][review-conformance]

A useful finding identifies the intent, constraint, budget, or plausible future change affected; supplies evidence connecting the implementation to the concern; and proposes a correction whose benefit justifies its cost. The reviewer should distinguish a demonstrated defect from a reasoned concern or an uncertainty needing investigation.

### Delegation leaves accountability with people

When an agent makes a mistake, own the mistake, contain its impact, understand why it happened, and correct the result. Improve the workflow so recurrence becomes less likely. The people delegating engineering work retain accountability. The team needs clear responsibility for containing the impact and correcting the result.

Google's postmortem practice supports investigating contributing conditions and following through on improvements. The practical implication for agentic work is to examine the instructions, context, tools, checks, and decisions that allowed the mistake, then change the process and verify the correction. [Google SRE, 2016][postmortems]

### Put these responsibilities into practice

The [practical companion](docs/practical-companion.md) shows how to carry intent into project instructions, work items, implementation, UX review and delivery evidence. It includes a Grid worked example, a way to evaluate whether agents apply the guidance, and [adaptable project templates](templates/README.md).

## 7. Architecture should be observed in the world it serves

Good architecture expresses the domain and the design intent, respects constraints and resource budgets, and makes the software easy to change. Complexity should earn its place by enabling customer value.

The developer's increasing presence in the customer's world suggests a further architectural premise. We can represent more of the world in which a solution operates, then observe how the proposed architecture fits its intended purpose across many dimensions.

Each user's journey in each feature is a dimension of that observation. Together they reveal how the software sits inside the user's experience, what outcomes it enables, and where it consumes resources. Operations and maintenance journeys belong in this world too. So do the interactions between journeys: shared state, concurrent work, delayed handoffs, exceptional conditions, and recovery.

The dimensions are perspectives on the solution, rather than independent axes in a mathematical proof. A journey can succeed alone and fail when it interacts with another. Capturing more journeys improves the model only if their relationships and consequential constraints are represented adequately.

Tests have long given us selective ways to observe software. They are shortcuts through a much larger space of possible conditions. The proposal is to expand what those observations can encompass: an executable account of the work, its participants, its environment, and the consequences of the software's behavior.

Architecture evaluation has never depended on executable tests alone. The Architecture Tradeoff Analysis Method, for example, evaluates architectural decisions against quality attributes and scenarios. It provides a methodological precursor for examining architecture across concerns before every behavior is implemented. [Kazman, Klein, and Clements, 2000][atam]

### The ambition and its research boundary

AI makes increasingly rich world models worth pursuing. The ambition is comprehensive observation of the solution in its domain. The proposition that we can faithfully simulate the entirety of an arbitrary customer's world remains a research direction, not an established capability.

There is strong industrial precedent for bounded simulation. FoundationDB runs the database in a deterministic simulation of machines, networks, storage, and failures. Its engineering documentation describes combining simulation with live performance testing and hardware failure testing. This shows how powerful a deliberately constructed environment can become while retaining checks outside that environment. [FoundationDB, 2026][foundationdb]

Simulating people raises additional questions. UXAgent demonstrates a system for generating simulated web users and examining their interactions, but its stated purpose is to help researchers refine usability-study designs before conducting real human studies. It does not establish that simulated journeys reproduce the needs, behavior, or value judgments of actual customers. [Lu and colleagues, 2025][uxagent]

The useful intuition in the universe analogy is to represent enough of the surrounding world to understand consequential interactions. This paper does not rely on a physics principle that understanding any system requires simulating the entire universe.

A simulation and an implementation can also share a misunderstanding. Their agreement then establishes internal consistency while leaving the customer's actual problem unresolved. A credible simulation needs calibration through observed work, identified limits, and correction when reality disagrees with it.

### The clay mold and the porcelain artifact

> The simulation is the clay mold for the porcelain artifact.

The simulation should show that each modeled journey produces the intended value within agreed constraints and resource budgets. That should be the standard for any implementation developed within it.

Before the software is trusted in the customer's environment, the mold must be dropped and the artifact must stand in that environment. The solution has to work with the customer's actual data, systems, circumstances, and people. Success inside the model is a prediction to substantiate.

Google's canary-release practice provides a practical account of this transition. Some defects become visible only under real production traffic; limited deployments produce evidence before exposure expands. This is operational evidence about controlled introduction, rather than proof of customer value by itself. [Google SRE, 2018][canarying]

The value claims should remain observable across that boundary. Differences discovered in actual work should then correct the model used for future changes and replacements.

## 8. Whither goest technical debt?

Teams now need to ask: whither goest technical debt in an age where we can reasonably build everything?

Take that premise seriously. If we can reliably reconstruct a solution within its resource budget, some implementations become much more replaceable. The economics of maintaining them change.

Fowler frames technical debt through the extra effort that deficiencies in internal quality impose on future changes. That framing makes debt an economic concern. If AI reduces the cost of understanding, repairing, or replacing an implementation, the burden associated with it can fall. Some inelegance may become inexpensive to tolerate; some repairs may become inexpensive to perform. [Fowler, 2019][technical-debt]

There is industrial evidence of cheaper bounded transformation. Amazon reports using AI to migrate tens of thousands of production applications from Java 8 or 11 to Java 17. This is a company-reported modernization case, not a controlled demonstration that complete business systems can be regenerated cheaply. [AWS, 2024][aws-migration]

Current AI use also leaves persistent problems. A 2026 preprint analyzing 302,600 verified AI-authored commits across 6,299 repositories found that 22.7% of tracked introduced static-analysis issues remained at the latest observed revision. Most findings were code smells. The study measures persistence of flagged issues, not their actual financial cost, and does not establish that every flag deserves remediation. [Liu and colleagues, 2026][ai-debt]

The future claim therefore needs its full economics. Rebuilding includes recovering the intended behavior, preserving necessary data and integrations, producing credible validation, and making the transition in the customer's environment. If those activities also become cheap and reliable, replacement becomes a stronger option.

| Choice | Economic justification |
| --- | --- |
| Keep | The implementation satisfies necessary requirements and imposes little expected future burden. |
| Refactor | Repair reduces expected friction and risk enough to justify its cost. |
| Replace | Rebuilding, validation, and transition together offer better value than continued repair or operation. |

In that future, the durable investment may increasingly be the domain understanding, design intent, constraints, data, external commitments, and trustworthy means of evaluating an implementation. Code can be regenerated. A missing understanding of the work can be regenerated into the next codebase as well.

Maintainability still means easy change. Its expression may increasingly include the ability to regenerate, verify, and transition a solution within budget. This is a proposed consequence of cheaper complete replacement, rather than a result already established for software generally.

## 9. Release at the pace the customer can land

A reasonable starting rule is to release when a change demonstrates intended value within agreed constraints and resource budgets. The pace must also respect the customer's ability to absorb change.

Customers at their core are trying to arrive at a steady state in which their work goes well. Software introduces change. The rate of that change needs to fit the customer, their environment, and their goals. Training, revised procedures, altered integrations, support work, and regained fluency all consume resources.

This invites scrutiny of a familiar interpretation of *Accelerate*: high release frequency equals high quality. Forsgren's research is more specific. High-performing teams combined speed and stability; failure rates and recovery time were measured separately from deployment frequency. Her explanation includes delivery when the business demands it. Frequent deployment alone does not demonstrate that each change creates customer value. [Forsgren, 2018][forsgren]

DORA explicitly distinguishes continuous delivery—the ability to release on demand—from deploying every change immediately. It also warns that increasing deployment frequency without improving the underlying practices and architecture can increase failures and burnout. That supports building a responsive delivery capability while choosing the timing of customer-facing change deliberately. [DORA, continuous delivery][continuous-delivery]

There is empirical support for the cost of disruption. In a laboratory study with 19 participants and a smartphone field study with 18, people became faster and more accurate as interface habits formed; disrupting the habits eliminated those measured gains. These were narrow interaction tasks, so they establish an adaptation cost rather than an optimal cadence for all products. [Garaialde and colleagues, 2020][interface-habits]

Deployment, exposure to new behavior, and adoption into the customer's work can occur at different times. Feature flags are an established mechanism for separating deployment from feature release. [Hodgson, 2017][feature-toggles]

The transition between versions should therefore appear in the value assessment and in the simulation. A system should be evaluated with people learning the change and coordinating its consequences, as well as after they become fluent.

Steady state is an aim for dependable work, not a demand that the world stop changing. Sometimes substantial change removes a greater burden. The decision should include both the cost of adoption and the cost of making the customer wait.

## 10. Let actual value decide what happens next

The customer's actual work is the final place to establish whether the vision was right. Better outcomes should justify the resources consumed across adoption, use, operation, and evolution.

Activity is an imperfect proxy. More clicks, more time in the application, more test cases, or more deployments can each be compatible with a worse experience. Microsoft's research on metric interpretation documented, for example, a changed mail button receiving 28% more clicks; investigation suggested that confused users were clicking repeatedly. The team stopped the experiment. [Dmitriev and colleagues, 2017][metric-pitfalls]

Evaluation needs a credible comparison, an appropriate time horizon, and results across the user ecosystem. A change in observed outcomes after adoption does not by itself establish how much improvement the software caused. Controlled experiments can help where practical; other settings require a comparison appropriate to their circumstances. Microsoft's experimentation work demonstrates the value of testing ideas against actual customer behavior. [Kohavi and colleagues, 2009][experimentation]

This does not require forcing every outcome into a monetary score. Time, attention, accessibility, decision quality, and the ability to complete the work can remain distinct observations. Necessary quality conditions continue to apply when the results are aggregated.

When value fails to materialize, go back to the customer's actual work:

1. Improve the implementation if the intent still holds.
2. Change direction if our understanding was wrong.
3. Stop if there is no credible path to net value within the resource budget.

The diagnosis matters. Disappointing results alone do not tell us whether the implementation failed, the proposed improvement addressed the wrong problem, or the surrounding conditions changed. The intent itself must remain open to disconfirmation. Otherwise, each failure can be assigned to implementation while the vision is protected indefinitely.

Research on entrepreneurial decisions supports explicit hypotheses and disciplined revision. Four randomized trials involving 759 firms found that teaching a scientific approach increased idea termination and encouraged a limited number of substantial changes in direction. Applying this evidence to software is an inference: the studies concerned entrepreneurial decisions across varied settings. [Camuffo and colleagues, 2024][camuffo]

The next investment should answer a specific uncertainty within a defined budget. Sometimes there is a credible path to learning whether the solution can create value before there is a credible path to delivering the entire solution. That investigation needs its own intended result and resource limit.

Taste supplies direction. Authority makes coherent action possible. Domain understanding grounds the dream in the work. Ownership carries the consequences. Humility allows the dream to be corrected.

Great software earns its place by the value customers can actually realize from it, for everything they must spend to make that value real.

## References and evidence notes

The sources below distinguish empirical findings from engineering practice and proposed future capabilities. Observational associations are not treated as causal proof; vendor cases and preprints are identified explicitly. The claims about full engineering delegation, comprehensive customer-world simulation, and inexpensive complete regeneration remain propositions to evaluate as capabilities develop.

1. Brynjolfsson, E., and Hitt, L. M. (2000). [Beyond Computation: Information Technology, Organizational Transformation and Business Performance][brynjolfsson-hitt]. *Journal of Economic Perspectives*, 14(4), 23–48. Research synthesis with firm-level evidence; emphasizes organizational complements and difficult-to-measure benefits.

2. Gasser, L. (1986). [The Integration of Computing and Routine Work][gasser]. *ACM Transactions on Information Systems*, 4(3), 205–225. Qualitative organizational field research; documents workarounds and compensating work.

3. Brooks, F. P., and Woods, E. (2010). [Interview with Fred Brooks on the Publication of The Design of Design][brooks]. InformIT. Practitioner argument for conceptual integrity, an empowered chief designer, iterative discovery, and early investigation of actual use.

4. Wang, D., Waldman, D. A., and Zhang, Z. (2014). [A Meta-Analysis of Shared Leadership and Team Effectiveness][shared-leadership]. *Journal of Applied Psychology*, 99(2), 181–198. Forty-two independent samples; positive associations concern broader leadership constructs and do not establish the best allocation of final design authority for a particular software team.

5. Moe, N. B., Šmite, D., Paasivaara, M., and Lassenius, C. (2021). [Finding the Sweet Spot for Organizational Control and Team Autonomy in Large-Scale Agile Software Development][moe]. *Empirical Software Engineering*, 26, 101. Two industrial cases at Ericsson; describes mechanisms and tensions rather than causal superiority.

6. Holtzblatt, K., and Beyer, H. (1996). [Contextual Design: Using Customer Work Models to Drive Systems Design][contextual-design]. CHI tutorial. A design methodology grounded in field observations and representations of work.

7. Curtis, B., Krasner, H., and Iscoe, N. (1988). [A Field Study of the Software Design Process for Large Systems][curtis]. *Communications of the ACM*, 31(11), 1268–1287. Interviews concerning 17 large projects; historical qualitative evidence about domain knowledge, requirements, and communication.

8. Google SRE (2018). [Example Error Budget Policy][error-budget]. *The Site Reliability Workbook*, Appendix B. A published operational policy illustrating how agreed reliability conditions affect releases.

9. NIST (2022). [Secure Software Development Framework, Version 1.1][ssdf]. SP 800-218. Engineering guidance on security requirements, verification, and vulnerability risk; not an empirical guarantee of security.

10. W3C WAI (updated 2024). [Involving Users in Evaluating Web Accessibility][wai]. Guidance on combining conformance evaluation with evaluation involving disabled users and on the limits of small samples.

11. Cui, Z., Demirer, M., Jaffe, S., Musolff, L., Peng, S., and Salz, T. (2025). [The Effects of Generative AI on High-Skilled Work: Evidence from Three Field Experiments with Software Developers][cui]. Randomized access to code-completion assistance across 4,867 developers; task completion is not a measure of complete product value.

12. Baolin, J., and Harvey, N. (2026). [Balancing AI Tensions: Moving from AI Adoption to Effective SDLC Use][dora-ai]. DORA. Includes qualitative analysis of 1,110 Google engineer responses and discussion of survey associations; does not identify a universal causal effect.

13. Conway, M. E. (1968). [How Do Committees Invent?][conway]. *Datamation*. Foundational organizational argument; applying it to agent workflows is an extension proposed in this paper.

14. Boehm, B., Lane, J. A., Koolmanojwong, S., and Turner, R. (2014). [The Incremental Commitment Spiral Model: Principles and Practices for Successful Systems and Software][icsm]. Methodological framework, summarized by the Boehm Center for Systems and Software Engineering.

15. Bacchelli, A., and Bird, C. (2013). [Expectations, Outcomes, and Challenges of Modern Code Review][code-review]. ICSE. Industrial observations, interviews, surveys, and review-comment analysis at Microsoft.

16. Jin, H., and Chen, H. (2026). [Are LLMs Reliable Code Reviewers? Systematic Overcorrection in Requirement Conformance Judgement][review-conformance]. *Automated Software Engineering*, 33, 90. Benchmark evaluation of five models; short programs and tested configurations limit generalization.

17. Google SRE (2016). [Postmortem Culture: Learning from Failure][postmortems]. *Site Reliability Engineering*, Chapter 15. Practitioner account of investigation and follow-through after incidents.

18. Kazman, R., Klein, M., and Clements, P. (2000). [ATAM: Method for Architecture Evaluation][atam]. CMU/SEI-2000-TR-004. Scenario-based architectural evaluation methodology developed and refined in practice.

19. FoundationDB project (documentation updated 2026). [Simulation and Testing][foundationdb]. Primary engineering documentation describing deterministic simulation alongside live performance and hardware failure testing.

20. Lu, Y., and colleagues (2025). [UXAgent: An LLM-Agent-Based Usability Testing Framework for Web Design][uxagent]. Research framework supporting preparation for human usability studies; does not establish equivalence between simulated and actual users.

21. Google SRE (2018). [Canarying Releases][canarying]. *The Site Reliability Workbook*, Chapter 16. Engineering practice for evaluating limited production deployments and expanding exposure based on evidence.

22. Fowler, M. (2019). [Technical Debt][technical-debt]. Practitioner explanation of future change effort, remediation cost, and the economics of internal quality.

23. Arisoy Cholkar, A. (2024). [Amazon Q Developer Just Reached a $260 Million Dollar Milestone][aws-migration]. AWS engineering blog. Company-reported Java migration case; savings are estimates, and the transformation is bounded.

24. Liu, Y., and colleagues (2026). [Debt Behind the AI Boom: A Large-Scale Empirical Study of AI-Generated Code in the Wild][ai-debt]. arXiv preprint, version 3. Static-analysis issue persistence is a proxy, not a direct measure of lifecycle costs.

25. Forsgren, N. (2018). [The Data Behind DevOps: Becoming a High Performer][forsgren]. Author presentation explaining the research summarized in *Accelerate*. Distinguishes delivery speed from separately measured stability.

26. DORA (accessed 2026). [Capabilities: Continuous Delivery][continuous-delivery]. Research-informed practice guidance; distinguishes releasability on demand from immediate deployment of every change.

27. Garaialde, D., and colleagues (2020). [Quantifying the Impact of Making and Breaking Interface Habits][interface-habits]. Controlled laboratory and smartphone field studies, with 19 and 18 participants respectively; narrow tasks limit conclusions about product-wide release cadence.

28. Hodgson, P. (2017). [Feature Toggles (aka Feature Flags)][feature-toggles]. Practitioner guidance on separating deployment from feature exposure and managing the resulting complexity.

29. Dmitriev, P., Gupta, S., Kim, D. W., and Vaz, G. (2017). [A Dirty Dozen: Twelve Common Metric Interpretation Pitfalls in Online Controlled Experiments][metric-pitfalls]. KDD. Cases from Microsoft experimentation illustrate why metric movements require interpretation.

30. Kohavi, R., and colleagues (2009). [Online Experimentation at Microsoft][experimentation]. Primary account of controlled experiments used to evaluate ideas against actual customer behavior.

31. Camuffo, A., Gambardella, A., Messinese, D., Novelli, E., Paolucci, E., and Spina, C. (2024). [A Scientific Approach to Entrepreneurial Decision-Making: Large-Scale Replication and Extension][camuffo]. *Strategic Management Journal*, 45(6), 1209–1237. Four randomized trials involving 759 firms; relevance to software decisions is an explicit inference.

[brynjolfsson-hitt]: https://www.aeaweb.org/articles?id=10.1257/jep.14.4.23
[gasser]: https://doi.org/10.1145/214427.214429
[brooks]: https://www.informit.com/articles/article.aspx?ns=18574&p=1600886
[shared-leadership]: https://www.researchwithrutgers.org/en/publications/a-meta-analysis-of-shared-leadership-and-team-effectiveness/
[moe]: https://link.springer.com/article/10.1007/s10664-021-09967-3
[contextual-design]: https://chi1996.acm.org/proceedings/tutorial/Holtzblatt/Kah_txt.html
[curtis]: https://www2.unifap.br/furtado/files/2015/03/Artigo-3.pdf
[error-budget]: https://sre.google/workbook/error-budget-policy/
[ssdf]: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-218.pdf
[wai]: https://www.w3.org/WAI/test-evaluate/involving-users/
[cui]: https://www.microsoft.com/en-us/research/publication/the-effects-of-generative-ai-on-high-skilled-work-evidence-from-three-field-experiments-with-software-developers/
[dora-ai]: https://dora.dev/insights/balancing-ai-tensions/
[conway]: https://melconway.com/Home/Committees_Paper.html
[icsm]: https://boehmcsse.org/tools/icsm/
[code-review]: https://www.microsoft.com/en-us/research/publication/expectations-outcomes-and-challenges-of-modern-code-review/
[review-conformance]: https://link.springer.com/article/10.1007/s10515-026-00638-5
[postmortems]: https://sre.google/sre-book/postmortem-culture/
[atam]: https://www.sei.cmu.edu/library/atam-method-for-architecture-evaluation/
[foundationdb]: https://apple.github.io/foundationdb/testing.html
[uxagent]: https://www.amazon.science/publications/uxagent-an-llm-agent-based-usability-testing-framework-for-web-design
[canarying]: https://sre.google/workbook/canarying-releases/
[technical-debt]: https://martinfowler.com/bliki/TechnicalDebt.html
[aws-migration]: https://aws.amazon.com/blogs/devops/amazon-q-developer-just-reached-a-260-million-dollar-milestone/
[ai-debt]: https://arxiv.org/abs/2603.28592v3
[forsgren]: https://videos.itrevolution.com/watch/524024367/
[continuous-delivery]: https://dora.dev/capabilities/continuous-delivery/
[interface-habits]: https://arxiv.org/abs/2005.06842
[feature-toggles]: https://martinfowler.com/articles/feature-toggles.html
[metric-pitfalls]: https://www.microsoft.com/en-us/research/wp-content/uploads/2020/08/2017-08-KDDMetricInterpretationPitfalls.pdf
[experimentation]: https://www.microsoft.com/en-us/research/publication/online-experimentation-at-microsoft/
[camuffo]: https://sms.onlinelibrary.wiley.com/doi/full/10.1002/smj.3580
