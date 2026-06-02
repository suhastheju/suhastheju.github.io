<details>
<summary> Click to read more </summary>

In recent months, I have attended several talks on AI ethics, policy, and governance for automated decision-making systems. Many of these discussions focus on applications where the stakes are high: health care, law enforcement, welfare allocation, hiring, military decision support, and other settings where a wrong decision can seriously affect a person's life, as well as society more broadly.

A recurring recommendation in these conversations is: keep a human in the loop.

The recommendation sounds reasonable. If an AI system is only used to provide information such as predictions, risk scores, or recommendations, and if a human expert retains final authority, then perhaps the system is not really making the decision. The human can review the output, correct the system when it is wrong, and remain accountable for the final outcome.

But is human-in-the-loop decision-making actually enough?

I do not think it is, at least not by itself.

The problem is not that human oversight is useless. In many domains, human judgment is necessary. The problem is that simply placing a human after an algorithm does not guarantee meaningful oversight. A human decision-maker who is shown an AI recommendation is not making the same decision they would have made without it. The recommendation changes the decision environment. It changes what information is salient, which options feel natural, what evidence receives attention, and which course of action appears easier to justify.

In other words, the AI system does not need to make the final decision in order to shape the final decision.

### Decision support is also choice architecture

Work by Richard Thaler and Cass Sunstein popularized the idea of choice architecture: the way options are presented can predictably influence what people choose. Defaults, rankings, warnings, labels, and framing effects can all guide behavior without formally removing freedom of choice. This is the central idea behind their work on nudges and decision environments [^1][^2].

A decision-support system is also a form of choice architecture. It may not force the human to accept its recommendation, but it structures the human's attention. It can make one option appear more credible, more urgent, more objective, or simply easier to select.

This matters because high-stakes decisions are often made under uncertainty, time pressure, incomplete information, and institutional constraints. A doctor may not have unlimited time to question every diagnostic suggestion. A judge or caseworker may face a heavy workload. A military analyst may operate under intense pressure. In such settings, an AI-generated recommendation is not merely "additional information." It can become an anchor.

Research in judgment and decision-making has long shown that humans rely on heuristics when reasoning under uncertainty. Daniel Kahneman and Amos Tversky argued that people often use mental shortcuts such as representativeness, availability, and anchoring [^3]. These shortcuts can be useful, but they can also produce systematic errors. The point here is simple: when we give a person an AI recommendation, we are not adding information to a neutral decision-maker. We are adding information to a human decision-maker with limited attention, limited time, and predictable cognitive vulnerabilities.

### The danger of automation bias

One risk is automation bias: the tendency to over-rely on automated systems, especially when they are usually correct. If a system is more accurate than the average human most of the time, it becomes psychologically and institutionally difficult to question it. Over time, the human may stop treating the system as one input among many and begin treating it as the default answer.

This is especially dangerous because many AI systems fail unevenly. They may perform well on average while failing for particular subgroups, rare cases, distribution shifts, or unusual contexts. A human reviewer may not know when they are looking at one of those failure cases. If the system is usually right, why should the human override it now? What evidence would be enough? Who bears responsibility if the override is wrong?

This creates a paradox. The more useful and accurate a decision-support system becomes in ordinary cases, the harder it may become for humans to detect the exceptional cases where they should resist it.

A simple analogy is search. Most people rarely look beyond the first page of search results. This does not mean they are forbidden from doing so. The option is available. But the ranking strongly shapes attention. The first page becomes, in practice, the information environment within which many users make judgments. Similarly, a decision-support system may preserve formal human authority while still strongly shaping the range of decisions that feel reasonable.

### Formal control is not the same as meaningful control

This is why I am skeptical of policy proposals that treat "human-in-the-loop" as a sufficient safeguard. The phrase can hide several very different arrangements.

A human may be asked to approve an AI recommendation without enough time to review it. A human may see a risk score without understanding how it was produced. A human may technically have authority to override the system, but face institutional pressure not to do so. A human may be blamed for accepting a bad recommendation even though the system was designed in a way that made meaningful scrutiny unrealistic.

In such cases, human oversight becomes procedural. The human is present, but not necessarily empowered.

For human oversight to be meaningful, the human decision-maker must be able to answer basic questions such as:

- When is this system likely to fail?
- What kinds of cases are outside its reliable domain?
- What evidence should justify overriding it?
- Will I be penalized for disagreeing with it?
- Do I have enough time, training, and information to evaluate its recommendation?
- Is the system's performance known across relevant subgroups and contexts?
- Are overrides monitored only as individual deviations, or also as signals of possible system failure?

Without answers to these questions, "human-in-the-loop" can become a comforting slogan rather than a real safeguard.

### Humans can improve decisions, but only under the right conditions

The conclusion should not be that humans are always better than machines. That would also be wrong. In many settings, statistical models and automated decision-making systems can outperform unaided human judgment. The issue is not whether either humans or machines are superior in general. The issue is how the combined human-machine system behaves.

Sometimes, AI support may improve decisions. Sometimes, humans may correctly reject bad recommendations. But sometimes, AI may introduce new errors, amplify existing biases, or make human decision-makers less vigilant. The performance of the overall system depends not only on model accuracy, but also on interface design, incentives, training, workload, accountability, and the distribution of errors.

This is the central point: a human-in-the-loop system is not automatically a safer system. It is a new decision-making system, and it must be studied as such.

### What should policy require instead?

If policymakers want to require human oversight in high-stakes AI systems, the requirement should be more specific than "put a human in the loop." A stronger policy framework would ask whether the human has genuine capacity to intervene.

This could include requirements such as:

- Human reviewers should be trained on known failure modes of the system.
- AI recommendations should be accompanied by uncertainty estimates and clear limits of applicability.
- Systems should be evaluated not only for model accuracy, but also for their effect on human decisions.
- Institutions should measure whether humans actually override the system in appropriate cases.
- Decision-makers should not be punished simply for disagreeing with an algorithm.
- High-stakes deployments should be tested under realistic workloads, time pressure, and institutional incentives.
- There should be auditing for subgroup-specific failures and rare but consequential errors.

The key shift is to evaluate the human-AI decision process together, not just the AI model in isolation.

### Where our understanding is still limited

There is still much we do not fully understand. We need better evidence about when human oversight improves outcomes and when it merely creates the appearance of accountability. We need to know how professionals in different domains respond to AI recommendations under real institutional pressures. We need to understand how expertise, training, workload, explanations, uncertainty displays, and liability rules affect the willingness and ability to override automated suggestions.

We also need more domain-specific research. The right form of oversight in medical diagnosis may not be the same as in military targeting, welfare administration, or hiring. A generic human-in-the-loop requirement may be too blunt for the complexity of these settings.

The deeper problem is that high-stakes decision-making is not only a technical problem. It is a problem of human judgment under uncertainty, institutional design, incentives, accountability, and authority. AI systems enter into this already complicated environment and reshape it.

So yes, humans should often remain involved in high-stakes decisions. But we should not mistake human presence for human control.

A human in the loop is not enough unless the loop itself is carefully designed, tested, and governed.

### References

[^1]: Richard H. Thaler and Cass R. Sunstein, Nudge: Improving Decisions About Health, Wealth, and Happiness, Yale University Press, 2008.

[^2]: Richard H. Thaler, Cass R. Sunstein, and John P. Balz, "Choice Architecture," 2010.

[^3]: Daniel Kahneman and Amos Tversky, "Judgment under Uncertainty: Heuristics and Biases," Science, 185(4157), 1124--1131, 1974.

[^4]: Raja Parasuraman and Victor Riley, "Humans and Automation: Use, Misuse, Disuse, Abuse," Human Factors, 39(2), 230--253, 1997.

[^5]: Linda J. Skitka, Kathleen Mosier, and Mark Burdick, "Accountability and Automation Bias," International Journal of Human-Computer Studies, 52(4), 701--717, 2000.

[^6]: Rohan Khera, Michelle A. Simon, and Joseph S. Ross, "Automation Bias and Assistive AI: Risk of Harm From AI-Driven Clinical Decision Support," JAMA, 2023.
