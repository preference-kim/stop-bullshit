# Stop Bullshit

*Agents bullshit too much.*

As we ask AI agents for deeper analysis and more productive work, fluent
responses can conceal that the agent never answered the actual question.

`stop-bullshit` is a self-reflection mechanism: step back, locate where the
response lost its connection to truth and the task, explain what went wrong,
and repair the work.

1. **User trigger:** The user asks what the agent meant—even neutrally—or
   replies, *“Bullshit.”* The agent revisits the request, its response and actions,
   and the evidence. Asking for clarification does not establish that the answer
   was false.
2. **Identification:** The agent pinpoints the claim, omission, or action that
   failed and its effect on the intended outcome.
3. **Root cause analysis:** The agent defines the failure precisely and traces
   it to the evidence or constraint that should have governed the failed step.
   An unknown cause stays unknown.
4. **Remediation plan and execution:** The agent states the underlying issue,
   executes the necessary authorized corrections, checks their consequences,
   and returns to the task. An apology or an unexecuted plan is insufficient.

The core distinction comes from Harry G. Frankfurt's *On Bullshit*: concern for
truth differs from merely producing a statement that happens to be true.
Frankfurt's reading of Wittgenstein's indignation at Fania Pascal's remark
motivates the skill's focus on speech that presents knowledge without submitting
to its constraints.

Here, restoring that connection also means returning to the user's **authentic
intent and expected outcome**, established by the request and context. Evidence
governs factual claims; the user's purpose governs relevance and completion.
Agreement cannot make a false claim true, and a true but irrelevant answer can
still fail the task. A complaint initiates an audit without proving a defect.

The agent must establish a **recovery enterprise**: a bounded inquiry into what
severed that connection, with corrective actions and completion criteria.
Compare the work the agent represented itself as doing with what its actions
actually established; restore the missing constraint on that work.

The audit also covers lying, humbug, pleonasm, falsity, phoniness, fakery,
quackery, nonsense, gibberish, and the unclarifiable. These are related prompts
for investigation, not interchangeable diagnoses or a taxonomy supplied by
Frankfurt. [Source distinctions](references/source-distinctions.md) separate the
essay's concepts from this skill's adaptations. Use labels only to help select a
check or repair.

[SKILL.md](SKILL.md) contains the operational checks and completion criteria.
[Evaluation cases](evals/README.md) exercise recovery and preservation of warranted claims.

## Use

Install this repository as a directory named `stop-bullshit` in your runtime's
configured skill location. Invoke `stop-bullshit`, or have a workflow load
[SKILL.md](SKILL.md) before delivery. Keep claims tied to evidence and actions
tied to the task in always-loaded instructions for continuous vigilance.

## References

Frankfurt, Harry G. 2005. *On Bullshit*. Princeton University Press.
[https://doi.org/10.2307/j.ctt7t4wr](https://doi.org/10.2307/j.ctt7t4wr).
