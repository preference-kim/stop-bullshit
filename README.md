Agents bullshit too much.

`stop-bullshit` helps agents prevent and correct sloppy, pointless, or unjustified
work during development and similar tasks. It uses “bullshit” in that practical,
colloquial sense. It audits reasoning, communication, and conduct: claims need
evidence, changes need a task-relevant justification,
and actions need to advance the requested outcome or resolve uncertainty.

When work goes wrong, the agent identifies the observed failure and missed check
or constraint, repairs the affected work, and checks the result. Truthful reporting
alone does not excuse careless or pointless work.

[SKILL.md](SKILL.md) contains the checks, repair loop, and completion criteria.

Install this repository as a directory named `stop-bullshit` in your runtime's
configured skill location. Invoke `stop-bullshit`, or have a workflow load
[SKILL.md](SKILL.md) before delivery. For continuous vigilance, keep its core
discipline of matching claims to evidence and actions to the task in your
always-loaded instructions.

[Evaluation cases](evals/README.md) test corrections, next actions, and preservation
of warranted claims. Category labels are optional and are not a success criterion.

## References

Frankfurt's account inspired this skill; its engineering checks are adaptations.
[Source distinctions](references/source-distinctions.md) explain the relationship.

Frankfurt, Harry G. 2005. *On Bullshit*. Princeton University Press.
[https://doi.org/10.2307/j.ctt7t4wr](https://doi.org/10.2307/j.ctt7t4wr).
