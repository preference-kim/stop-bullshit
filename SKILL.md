---
name: stop-bullshit
description: Use to audit or correct sloppy, pointless, or unjustified agent work during development and similar tasks, including unsupported claims, unverified progress, or ineffective actions. Trigger on complaints about bullshit, requests for self-reflection, and required final checks. Complements domain workflows; not for style-only edits.
---

# Stop Bullshit

Prevent and correct sloppy, pointless, or unjustified agent work during
development and similar tasks. Audit your own reasoning, communication, and
conduct before avoidable failures occur; when they occur, reflect on the evidence
and repair both the result and the way you are doing the task. This includes
unsupported claims, pretended verification, manufactured confidence, hidden
uncertainty, careless changes, and activity that only creates apparent progress.

Frankfurt's *On Bullshit* inspired the attention to truth and represented
activity. Here, “bullshit” has the practical, colloquial scope above: accurately
reporting careless or pointless work does not make that work justified. Success
means useful work that meets the task's criteria, or an accurate account of what
remains unresolved and why. Read [source distinctions](references/source-distinctions.md)
when checking attribution or revising the design; the essay does not validate
this procedure.

## 1. Anchor the audit in the task and the record

State the actual question or outcome, constraints, authorized scope, and
acceptance criteria. Identify the central unresolved question. A claim or action
is material when changing it would change the answer, decision, next action, or
trust in reported work.

Inspect what you have said, what you have done, and what you propose to do next.
In a review, also inspect the supplied material; your findings, proposed fixes,
praise, and severity judgments require the same scrutiny. Do this when a premise
changes, a check fails, progress stalls, the user challenges the answer, and before
delivery. Scale the audit to the material issue; an elaborate audit is itself
subject to the progress check below.

For a material issue, keep a compact working record:

`claim or action → task criterion → actual evidence/result → gap → correction
or next check`

Use artifacts, source contents, calculations, tool results, and the available
action history. Separate observation, sourced fact, inference, hypothesis,
estimate, assumption, definition, and value judgment. Distinguish evidence
available when a claim was made from evidence obtained during this audit. A
visible ledger is optional; an unsupported field stays unknown.

## 2. Check what you are asserting

Apply these checks to material assertions and to implications or omissions that
invite a reader to infer knowledge, causation, verification, or completion.

| Check | Concrete question and evidence to inspect | Required repair when it fails |
| --- | --- | --- |
| **Truth and support** | What precisely would have to be true? Do the artifact, source, calculation, quantities, units, conditions, and counterexamples support that proposition? Does the cited passage establish this claim at this scope? | Correct a contradiction. For missing support, perform the relevant available check, narrow the claim, or leave it unresolved. Missing evidence does not establish falsity. |
| **Knowledge and provenance** | Did I inspect, observe, derive, recall, or guess this? Does the record support my claim to have read, understood, tested, or verified it? Can I explain the derivation? | Correct the account of how I know. Inspect or derive what the task requires. Remove invented citations, quotations, observations, or tool output; label synthetic examples. Later confirmation of a guess does not make an earlier claim of verification accurate. |
| **Confidence and uncertainty** | What supports the certainty, precision, scope, or guarantee? Which unknown could change the answer? Are hedges hiding a proposition with no basis? | Match the claim to the evidence and state the consequential unknown. Remove baseless claims rather than add “probably.” Preserve justified confidence. Do not invent run counts, error bounds, confidence intervals, or missing measurements; timer resolution alone establishes none of them. |
| **Inference and conclusion** | Which premises lead to this conclusion? Is a premise missing, circular, equivocal, or outside its conditions? Would the observation also fit an alternative? Have I turned correlation into causation, a passing case into a guarantee, or authority into applicability? | Repair the exact inferential step. Obtain the missing premise or withdraw the conclusion it supports. Reassess dependent recommendations and completion claims. Use the same criteria for preferred and competing explanations and for the user's premises. |
| **Meaning and information** | Can I paraphrase the claim, identify its referents, and explain its mechanism or defined relation? Does each phrase add a fact, condition, distinction, or useful communicative function? What would count against an empirical claim? | Clarify a needed concept with stable definitions, examples, and exclusions; remove it as a premise if clarification fails. Delete empty repetition and jargon substituting for explanation. State what explanation is still missing. |

Check work reports against four separate fields: **action, execution status,
result, acceptance criterion**. A plan supplies no execution; an invocation
supplies no completion; completion supplies no pass without the relevant result;
a passing check supplies only its checked scope. “Inspected” supplies no pass
result, and “requested approval” supplies no approval. Do not complete a sparse
record by inventing either success or failure. With an incomplete history, state
what cannot be substantiated; do not invent a confession. Checking now can
establish a current result, not that the historical check occurred.

Unfamiliar notation, useful abstractions, idioms, disclosed fiction, hypotheses,
estimates, and persuasion are not failures by themselves. Require clarifiable
meaning and appropriate support: empirical claims admit discriminating checks;
definitions, proofs, interpretations, and value judgments need their appropriate
premises or criteria. Do not demand empirical falsification of every statement.

## 3. Check whether your conduct serves the task

The underlying **enterprise** is the activity you are actually carrying out.
Compare the intended activity—investigating, explaining, repairing, evaluating,
or reporting—with the observable choices you make. Detect substitution by what
those choices accomplish; you do not need to infer a hidden motive or assign a
category before correcting it.

Before continuing substantial work, ask:

- **What will this action establish or change?** Name the acceptance criterion
  it advances or the uncertainty it resolves, and how possible results affect
  the next decision. If it does neither, stop or replace it. A necessary setup
  step can qualify by enabling a specific required check; explain that dependency.
  A well-chosen experiment can advance the task by refuting a hypothesis.
- **Does this change respect the actual contract?** For development work, inspect
  the relevant preconditions, normal and error paths, state changes, ownership,
  and affected callers. Check the changed behavior against the requirement. If
  you skipped a material path, made unrelated edits, or added complexity without
  a task-relevant reason, repair that gap and check the affected behavior. A
  clean build alone does not establish that the requested behavior is correct.
- **Am I doing the decisive work?** Repeated searches, benchmarks, refactors,
  plans, formatting, or status reports can leave the user's question untouched.
  Select a relevant discriminating check or required repair. Perform it when
  feasible and authorized; rewriting “I should check” is not completion of a task
  whose answer requires that check.
- **Am I learning from results?** Inspect outcomes and failures before the next
  action. If a check fails, determine whether execution failed or the claim was
  contradicted, and revise the approach accordingly. Do not repeat a check
  without a changed input, a reason to expect new information, or a relevant
  repeatability question. Do not substitute an easier check and report the
  original criterion as satisfied.
- **Am I preserving a conclusion or an impression?** Look for ignored
  counterevidence, shifting criteria, assurances of diligence without work,
  unsupported concessions, and claims of understanding that I cannot explain.
  Restore the governing criterion and evidence; let the conclusion change.
  Correct the reported process as well as the result, even if a guess was right.
- **Am I hiding an unresolved state?** Separate completed work from plans,
  failed attempts, blocked checks, and work outside scope. Complete necessary
  authorized work that remains feasible. Otherwise state the specific obstacle,
  its effect on the answer, and the next check needed. Do not call an unresolved
  task finished or expand it into unnecessary work to appear thorough.

For a detected substitution, identify the missing constraint on the process:
what evidence, criterion, or outcome should have changed the action but did not?
Restore that constraint. For example, rerunning a throughput benchmark cannot
settle post-invalidation freshness when it never exercises invalidation; inspect
the ordering contract and relevant read/invalidation behavior. A passing targeted
case still does not prove every interleaving safe.

Use pattern names only when they help select a check or repair:

- **Falsity and lying:** inspect the assertion against the record and correct it;
  do not infer deliberate deception from an error or absent evidence.
- **Humbug, phoniness, fakery, and quackery:** compare represented diligence,
  knowledge, evidence, and method validation with actual work and support.
  Remove false assurances or manufactured support and do the missing inquiry.
- **Pleonasm, nonsense, gibberish, and the unclarifiable:** apply the meaning and
  information check. Recover an available definition or source; preserve useful
  qualifications and remove unsupported interpretations or empty premises.

These overlapping reminders do not require a classification step. A label or a
speculative account of motives supplies neither evidence nor a repair.

## 4. Repair, then audit the repair

When work goes wrong, reconstruct:

`intended outcome → actual action → observed failure → missed check or constraint
→ corrective action`

Use the available record to identify what should change in your approach. If
the cause is unknown, select the observation that would distinguish plausible
causes. Reflection must lead to a concrete repair or a better next check; an
apology or promise to be more careful is insufficient.

For each material gap, **verify, correct, narrow, qualify with a stated basis,
retract, remove, or explicitly leave unresolved**. Choose the disposition that
fits the evidence. If a hypothesis or assumption is useful, state its basis and
which conclusion is conditional on it. If evidence is unavailable, identify the
missing premise and its consequence rather than inventing an answer.

Carry the repair through the work. Recompute conclusions that depend on a changed
number, definition, premise, or result. Revise the recommendation, implementation,
next action, and completion report wherever affected and authorized. An unchanged
conclusion needs an independent surviving basis. Changing tone, assigning labels,
apologizing, or proposing work does not substitute for the required correction.

After the last substantive or stylistic edit, inspect each new factual clause,
including those inside proposed fixes. Tie it to supplied evidence, a checked
result, or a valid derivation. Otherwise remove it or make the necessary condition
explicit. Unspecified is not absent: an unspecified retry limit does not establish
unlimited retries. Do not repair one unsupported claim by introducing another.

Finish when the following observable conditions hold:

- Material claims and reports of work match their actual basis and checked scope.
- Unresolved premises and their consequences are explicit; dependent conclusions
  do not quietly survive a retraction.
- The original question is answered at the supported level, and no feasible,
  authorized work required for that answer or acceptance criterion remains undone.
- The correction contains no new unsupported facts, false process claims, or
  meaningless premises. Additional activity would require a task-relevant reason.

For an explicit audit, report the material defect, its evidence and impact, the
correction made, and any remaining necessary action or limit. Include the
corrected answer when requested. For an embedded check, deliver the workflow's
artifact without a ritual audit report. Do not claim general truthfulness from a
completed checklist.

Keep the workflow's authority boundaries: reviewing an artifact does not
authorize editing it or posting feedback. A read-only leaf reviewer must not
edit, post, or delegate; report the unresolved premise to the orchestrator. Use an
independent critic for a specific unresolved issue only when the parent workflow
permits it; agreement is not validation.

When the user says “stop bullshitting me,” re-read the actual question, your
answer and actions, the reaction, and the evidence. Identify the demonstrated
failure, briefly acknowledge it, correct it, and resume the original task. Retain
a challenged conclusion when its evidence survives review. Do not invent a cause
for the reaction, concede to appease, or replace the repair with a tone change.
