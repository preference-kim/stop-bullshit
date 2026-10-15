# Stop Bullshit

`stop-bullshit` audits whether an agent's claims follow from evidence and its
actions serve the user's intended outcome. It identifies the exact failure,
traces the supported process cause, executes authorized repairs, and checks their
consequences. An apology or an unexecuted plan does not complete recovery.

A user complaint or a neutral question about the agent's explanation starts the
audit. It does not prove the answer false. The skill preserves warranted claims,
useful uncertainty, and the user's authority boundaries.

Harry G. Frankfurt's *On Bullshit* motivates the distinction between concern for
truth and a statement that merely happens to be true. The task-repair workflow
is an adaptation, described in [source distinctions](references/source-distinctions.md).

The operational objective is supported reasoning and completed authorized repair.
The book supplies background, not a taxonomy to recite or a checklist whose
completion proves truthfulness. A neutral clarification can end with a short
explanation when the original claim remains supported.

## Behavioral examples

| Situation | Expected behavior |
| --- | --- |
| A user asks whether 60 ms versus 30 ms means twice as fast or half the time. | Explain both ratios for the measured case. Do not invent an error or retract a supported statement. |
| An agent claimed to fix a conversion and run checks, but only imported the file. | Correct the record, perform the authorized repair and check, and report their actual results. A later pass does not validate the earlier report. |
| A read-only reviewer finds an unsupported performance claim. | Identify the missing measurement and its effect on the conclusion. Report the finding without editing or publishing. |

## Use

Install this repository as `stop-bullshit` in the runtime's skill directory.
Invoke the skill directly, or load [SKILL.md](SKILL.md) as an embedded audit before
delivery. Operational instructions live there. [Evaluation cases](evals/README.md)
exercise scoped recovery and preservation of supported claims. They do not prove
general truthfulness.

## Reference

Frankfurt, Harry G. 2005. *On Bullshit*. Princeton University Press.
[DOI](https://doi.org/10.2307/j.ctt7t4wr).
