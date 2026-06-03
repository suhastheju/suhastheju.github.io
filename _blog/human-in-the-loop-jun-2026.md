<details>
<summary>Click to read more</summary>

<p>
In recent months, I have attended several talks on AI ethics, policy, and governance for automated decision-making systems. Many of these discussions focus on applications where the stakes are high: health care, law enforcement, welfare allocation, hiring, military decision support, and other settings where a wrong decision can seriously affect a person's life, as well as society more broadly.
</p>

<p>
A recurring recommendation in these conversations is: <strong>keep a human in the loop</strong>.
</p>

<p>
The recommendation sounds reasonable, right. If an AI system is only used to provide information such as predictions, risk scores, or recommendations, and if a human expert retains final authority, then perhaps the system is not really making the decision. The human can review the output, correct the system when it is wrong, and remain accountable for the final outcome. So what is the problem here?
</p>

<p>
But is human-in-the-loop decision-making actually enough to address the issue?
</p>

<p>
I do not think it is, at least not by itself.
</p>

<p>
The problem is not that human oversight is useless. In many domains, human judgment is useful and necessary. The problem is that simply placing a human after an algorithmic recommendation does not guarantee meaningful oversight. A human decision-maker who is shown an AI recommendation is not making the same decision they would have made without it. The recommendation changes the decision environment. It changes what information is salient, which options feel natural, what evidence receives attention, and which course of action appears easier to justify.
</p>

<p>
In other words, the AI/algorithmic system does not need to make the final decision in order to influence or shape the final decision.
</p>

<h3>Decision support is also choice architecture</h3>

<p>
Work by Richard Thaler and Cass Sunstein popularized the idea of <strong>choice architecture</strong>: the way options are presented can predictably influence what people choose. Defaults, rankings, warnings, labels, and framing effects can all guide behavior without formally removing freedom of choice. This is the central idea behind their work on nudges and decision environments <sup><a href="#fn1" id="ref1">1</a></sup> <sup><a href="#fn2" id="ref2">2</a></sup>.
</p>

<p>
A decision-support system is also a form of choice architecture. It may not force the human to accept its recommendation, but it structures the human's attention. It can make some options appear more credible, more reliable or simply easier to select.
</p>

<p>
This matters because high-stakes decisions are often made under uncertainty, time pressure, incomplete information, and institutional constraints. A doctor may not have unlimited time to question every diagnostic suggestion. A judge or caseworker may face a heavy workload. A military analyst may operate under intense pressure and need to make decisions in the order of seconds. In such settings, an AI-generated recommendation is not merely "additional information." It can become an anchor.
</p>

<p>
Research in judgment and decision-making has long shown that humans rely on heuristics when reasoning under uncertainty. Daniel Kahneman and Amos Tversky argued that people often use mental shortcuts such as representativeness, availability, and anchoring <sup><a href="#fn3" id="ref3">3</a></sup> <sup><a href="#fn4" id="ref4">4</a></sup>. These shortcuts can be useful, but they can also prompt us make systematic errors that are predictably irrational. The point is, when we give a human an AI recommendation, we are not adding information to a neutral decision-maker. We are adding information to a human decision-maker with limited attention, limited time, and predictable cognitive vulnerabilities.
</p>

<h3>The danger of automation bias</h3>

<p>
One risk is <strong>automation bias</strong>: the tendency to over-rely on automated systems, especially when they are usually correct. If a system is more accurate than the average human most of the time, it becomes psychologically and institutionally difficult to question it. Over time, the human may stop treating the system as an input among many and begin treating it as the default answer.
</p>

<p>
This is especially dangerous because many AI systems fail unevenly. They may perform well on average while failing for particular subgroups, rare cases, distribution shifts, or unusual contexts. A human reviewer may not know when they are looking at one of those failure cases. If the system is usually right, why should the human override it now? What evidence would be enough? Who bears responsibility if the override is wrong?
</p>

<p>
This creates a paradox. The more useful and accurate a decision-support system becomes in ordinary cases, the harder it may become for humans to detect the exceptional cases where they should resist the advice from these systems.
</p>

<p>
A simple analogy is search recommendations. Most people rarely look beyond the first page of search results. This does not mean they are forbidden from doing so. The option is available. But the ranking strongly shapes our attention. The first page (or sometimes even the top results) becomes, in practice, the information environment within which many users make judgments and take decisions. Similarly, a decision-support system may preserve formal human authority while still strongly shaping the range of decisions that feel reasonable.
</p>

<h3>Formal control is not the same as meaningful control</h3>

<p>
This is why I am skeptical of policy proposals that treat "human-in-the-loop" as a sufficient safeguard. The phrase hides several very different arrangements.
</p>

<p>
A human may be asked to approve an AI recommendation without enough time to review it. A human may see a risk score without understanding how it was produced. A human may technically have authority to override the system, but face institutional pressure not to do so. A human may be blamed for accepting a bad recommendation even though the system was designed in a way that made meaningful scrutiny unrealistic.
</p>

<p>
In such cases, human oversight becomes procedural. The human is present, but not necessarily empowered.
</p>

<p>
For human oversight to be meaningful, the human decision-maker must be able to answer basic questions such as:
</p>

<ul>
  <li>When is this system likely to fail?</li>
  <li>What kinds of cases are outside its reliable domain?</li>
  <li>What evidence should justify overriding it?</li>
  <li>Will I be penalized for disagreeing with it?</li>
  <li>Do I have enough time, training, and information to evaluate its recommendation?</li>
  <li>Is the system's performance known across most relevant contexts?</li>
  <li>Are overrides monitored only as individual deviations, or also as signals of possible system failure?</li>
</ul>

<p>
Without answers to these questions, "human-in-the-loop" can become a comforting slogan rather than a real safeguard.
</p>

<h3>Humans can improve decisions, but only under the right conditions</h3>

<p>
The conclusion should not be that humans are always better than machines. That would also be wrong. In many settings, statistical models and automated decision-making systems can outperform unaided human judgment. Indeed, one motivation for introducing automated decision-making systems is that human decisions are often affected by biases, inconsistency, and seemingly irrelevant factors. Kahneman, Sibony, and Sunstein discuss this problem in Noise, where they argue how judgments can vary substantially across decision-makers even when they are evaluating similar cases<sup><a href="#fn5" id="ref5">5</a></sup>. The issue, therefore, is not whether humans or machines are superior in general. The more important question is how the combined human-machine decision-making system behaves.
</p>

<p>
Sometimes, AI support may improve decisions. Sometimes, humans may correctly reject bad recommendations. But sometimes, AI may introduce new errors, amplify existing biases, or make human decision-makers less vigilant. The performance of the overall system depends not only on model accuracy, but also on interface design, incentives, training, workload, accountability, and the distribution of errors.
</p>

<p>
This is the central point: <strong>a human-in-the-loop system is not automatically a safer system. It is a new decision-making system, and it must be studied as such.</strong>
</p>

<h3>What should policy require instead?</h3>

<p>
If policymakers want to require human oversight in high-stakes AI systems, the requirement should be more specific than "put a human in the loop." A stronger policy framework would ask whether the human has genuine capacity to intervene.
</p>

<p>
This could include requirements such as:
</p>

<ul>
  <li>Human reviewers should be trained on known failure modes of the system.</li>
  <li>AI recommendations should be accompanied by uncertainty estimates and clear limits of applicability.</li>
  <li>Systems should be evaluated not only for model accuracy, but also for their effect on human decisions.</li>
  <li>Institutions should measure whether humans actually override the system in appropriate cases.</li>
  <li>Decision-makers should not be punished simply for disagreeing with an algorithm.</li>
  <li>High-stakes deployments should be tested under realistic workloads, time pressure, and institutional incentives.</li>
  <li>There should be auditing for subgroup-specific failures and rare but consequential errors.</li>
</ul>

<p>
The key shift is to evaluate the <strong>human-AI decision process together</strong>, not just the AI model in isolation.
</p>

<h3>Where our understanding is still limited</h3>

<p>
There is still much we do not fully understand. We need better evidence about when human oversight improves outcomes and when it merely creates the appearance of accountability. We need to know how professionals in different domains respond to AI recommendations under real institutional pressures. We need to understand how expertise, training, workload, explanations, uncertainty displays, and liability rules affect the willingness and ability to override automated suggestions.
</p>

<p>
We also need more domain-specific research. The right form of oversight in medical diagnosis may not be the same as in military targeting, welfare administration, or hiring. A generic human-in-the-loop requirement may be too blunt for the complexity of these settings.
</p>

<p>
The deeper problem is that high-stakes decision-making is not only a technical problem. It is a problem of human judgment under uncertainty, institutional design, incentives, accountability, and authority. AI systems enter into this already complicated environment and reshape it.
</p>

<p>
So yes, humans should often remain involved in high-stakes decisions. But we should not mistake human presence for human control.
</p>

<p>
A human-in-the-loop is not enough unless the loop itself is carefully designed, tested, and governed.
</p>

<h3>References</h3>

<ol>
  <li id="fn1">Richard H. Thaler and Cass R. Sunstein, <em>Nudge: Improving Decisions About Health, Wealth, and Happiness</em>, Yale University Press, 2008. <a href="#ref1">↩</a></li>
  <li id="fn2">Richard H. Thaler, Cass R. Sunstein, and John P. Balz, "Choice Architecture," 2010. <a href="#ref2">↩</a></li>
  <li id="fn3">Daniel Kahneman and Amos Tversky, "Judgment under Uncertainty: Heuristics and Biases," <em>Science</em>, 185(4157), 1124--1131, 1974. <a href="#ref3">↩</a></li>
  <li id="fn4">Daniel Kahneman, <em>Thinking, Fast and Slow</em>, Farrar, Straus and Giroux, 2011. <a href="#ref4">↩</a></li>
  <li id="fn5">Daniel Kahneman, Olivier Sibony, and Cass R. Sunstein, <em>Noise: A Flaw in Human Judgment</em>, Little, Brown Spark, 2021. <a href="#ref5">↩</a></li>
</ol>

</details>
