---
name: stop-bullshit
description: Use when users question what the agent meant, including neutral clarification of its own answer; call it bullshit, evasive, empty, or overconfident; request self-reflection; or require a final audit. Audit and repair the response and work. Not for standalone concept explanations, translation, style-only edits, or philosophy discussion.
---

# Stop Bullshit

Restore the connection between evidence, the user's intended outcome, and the
work actually performed. Evidence governs factual claims. The request and context
govern relevance and completion. Accurate reporting does not excuse irrelevant
work, and agreement with the user does not establish truth.

A complaint or question about your explanation starts an audit, not a verdict.
Revisit the actual request, response, actions, and evidence. Preserve a challenged
conclusion when its support survives. A short clarification is sufficient when
the only defect is a missing explanation. Standalone concept questions,
translation, and style edits do not trigger this audit by themselves.

Frankfurt's *On Bullshit* motivates the concern for truth and represented activity.
This workflow is an adaptation. Read [source distinctions](references/source-distinctions.md)
when checking attribution or revising the skill's design.

## Establish what needs repair

Identify the intended outcome, constraints, authority, and acceptance criteria.
Locate the exact claim, omission, inference, or action that could change the
answer, decision, next action, or trust in the work. Connect it to the unmet
criterion. Inspect supplied material and your findings, praise, severity judgments,
and proposed fixes under the same standard.

For each material issue, keep this compact working record. Showing it is optional:

`claim/action → task criterion → actual evidence/result → gap → correction/check`

Resolve ambiguity from available context first. Ask only about a gap that changes
the repair, and defer dependent action. Scale the audit to the issue. Its next
action must advance an acceptance criterion or resolve a relevant uncertainty.

## Check claims and reported work

- Establish what supports each proposition at its stated scope: source passage,
  artifact, calculation, observation, or derivation. Include relevant conditions,
  quantities, units, and counterevidence. Distinguish observation, sourced fact,
  inference, hypothesis, estimate, assumption, definition, and value judgment.
- Check provenance as well as the result. Separate what was inspected, observed,
  derived, recalled, or guessed, and what was known then from what was checked
  now. Later confirmation cannot turn an earlier guess into an earlier test.
  Remove invented sources, quotations, results, or tool output. Label synthetic
  examples. An incomplete record establishes neither success nor failure, nor
  whether an earlier inspection occurred.
- Match confidence, precision, and scope to the support. Remove a baseless claim
  instead of hiding it under a hedge. State consequential unknowns and preserve
  warranted confidence. Do not invent run counts, uncertainty bounds, or missing
  measurements. Timer resolution alone establishes no accuracy bound.
- Test the inference against its premises and alternatives. A passing case does
  not establish a universal guarantee. Correlation does not establish cause, and
  authority does not establish applicability. Apply the same criteria to the
  user's premise, your preferred conclusion, and competing explanations.
- Require a clear meaning and relation for every premise. Paraphrase it, identify
  its referents, and explain the mechanism or definition. Remove circular,
  shifting, or unclarifiable premises and empty repetition. Use appropriate
  support: empirical claims need discriminating evidence, while definitions,
  proofs, and preferences need their own premises or criteria. Defined notation,
  useful qualifications, disclosed hypotheses, fiction, and persuasion are not
  defects by themselves.

Separate **action, execution status, result, and acceptance criterion** in work
reports. A plan is not execution, invocation is not completion, and completion is
not a pass without a relevant result. Inspection alone is not validation. A pass
supports only its checked scope. Requested approval is not granted approval.
Unavailable or uninspected evidence does not establish absence, falsity, or deceit.

## Repair the conduct and its consequences

Compare the intended activity with what the actions actually established. Locate
the evidence or constraint that should have changed the failed step. Explain that
observable process failure without inventing a motive. An apology, a diagnostic
label, or a claim of carelessness does not establish a cause. If the deeper cause
is unknown, state the limit and the observation needed to distinguish explanations.
Repair a demonstrated defect even when that deeper cause remains unknown.

Choose the decisive authorized action. For implementation work, inspect the
relevant contract, normal and error paths, state changes, ownership, and callers.
Correct skipped requirements and unrelated complexity, then check the affected
behavior. A clean build alone does not establish required runtime behavior.
Necessary setup qualifies when it enables a required check, and an experiment
that refutes a hypothesis can be useful progress.

Inspect results before repeating an action. Distinguish execution failure from
evidence against a claim. Repeat only with a changed input, a reason to expect
new information, or a relevant repeatability question. Do not substitute an easier
check, extra prose, or a status report for the required repair.

For each gap, verify, correct, narrow, qualify with a stated basis, retract, remove,
or leave it explicitly unresolved. Carry changed premises through dependent
recommendations, implementation, next actions, and completion reports. An unchanged
conclusion needs surviving support. Complete feasible, authorized work required
by the task. Otherwise state the blocker, its impact, and the next necessary check.

Keep the workflow's authority boundaries. Review does not authorize edits or
publication. A read-only leaf reviewer must not edit, post, or delegate. Report
unresolved premises to the orchestrator. Use an independent critic only when the
parent workflow permits it, and assess its evidence rather than treating agreement
as validation.

## Verify and deliver

After the last substantive or prose edit, check every new factual clause and
reported action, including proposed fixes and your own review comments. Preserve
source qualifications. A check that can help distinguish causes is not guaranteed
to settle them. Correct or remove unsupported claims introduced during the repair.

Finish when the original question is answered at the supported scope, material
claims match evidence, and consequential unknowns remain explicit. No feasible,
authorized work required by the acceptance criteria can remain undone. Stop
unrelated activity once those criteria are satisfied.

For an explicit audit or user-triggered recovery, briefly report the exact defect,
evidence and impact, supported process cause or unknown cause, correction, and
remaining limit. Deliver the corrected answer or artifact and resume the original
task. For an embedded check, deliver the workflow's artifact without an audit
ceremony. A completed checklist does not establish general truthfulness.
