---
name: stop-bullshit
description: Use when the user calls an answer bullshit or signals evasion, empty rhetoric, or unearned certainty. Also use for explicit truthfulness audits and required final checks in reasoning, answers, writing, and reviews. Complements domain workflows; not for style-only rewrites.
---

# Stop Bullshit

Audit whether claims answer the actual question and whether their content,
evidence, claimed knowledge, and reasoning withstand inspection. Repair the
claim and the process that produced it. Success means a supported conclusion or
an explicit unresolved premise with its consequences; changing the tone is
insufficient.

Frankfurt distinguishes disregard for truth from deliberate opposition to it,
and locates bullshit in misrepresentation of the speaker's enterprise. A true
statement can therefore still be phony. See [*On Bullshit*, pp. 33–34 and
47–56](https://legacy.berea.edu/phi/wp-content/uploads/sites/81/2020/09/On-Bullshit.pdf).
The taxonomy and procedure below are engineering adaptations, not Frankfurt's
own classification or a test of an agent's inner motives. Read
[source distinctions](references/source-distinctions.md) when evaluating the
attribution or revising the design.

## 1. Fix the question and identify the claims

Establish the question or decision, constraints, acceptance criteria, available
evidence, and authorized review scope. A claim is material when changing it
would change the answer, decision, recommended action, or trust in reported work.
Keep the central unresolved question visible throughout the audit.

Inspect the **material** and your **response** separately. Split compound claims
at consequential qualifications: a method can be conventional without being
applicable here, a test can run without passing, and a passing test can leave the
user's criterion untested. Include implications and omissions that would cause a
reasonable reader to infer knowledge, validation, causation, or completion.

For each disputed or consequential claim, keep a compact working record:

`exact claim + scope → kind → evidence/provenance → status → implied knowledge
or work → dependent conclusion → repair/check`

Kinds include observation, sourced fact, inference, hypothesis, estimate,
assumption, definition, and value judgment. Status is supported, contradicted,
mixed, or unresolved **within the checked scope**. Record which evidence existed
when the claim was made and which was obtained during review when that difference
matters. A source supports what it actually establishes, not every implication
attached to its citation. Do not require a separate citation for ordinary
reasoning or every sentence; use a visible ledger only when it helps the review.

## 2. Test truth, warrant, and claimed knowledge separately

Ask of each material claim:

- **Content:** What exactly would have to be true? Check names, quantities,
  units, baselines, time, conditions, and quantifiers against the relevant
  artifact, source, calculation, or observation. Is there counterevidence?
  Preserve the reported measurement count; an available number does not imply
  a single run. Instrument resolution alone supplies neither accuracy nor an
  error bound, confidence interval, or run-to-run variation.
- **Warrant:** Does the evidence support this proposition at this scope? Does
  an inference require an unstated premise, a causal mechanism, a representative
  sample, or an applicability condition? A compatible observation is not
  necessarily evidence that distinguishes this explanation from alternatives.
  A test can expose a counterexample; a passing test supports its checked cases,
  not an unrestricted guarantee. State the invariant or additional coverage a
  broader conclusion would require.
- **Knowledge and access:** What supports presenting this as known? Did I
  observe it, inspect a source that establishes it, derive it, recall it, or
  guess? Does my wording imply access, expertise, reading, testing, or firsthand
  experience that the available record does not substantiate? Fluent recall and
  a plausible citation do not establish that a source was inspected.
- **Discriminating check:** What observation would count against an empirical
  claim, and under what conditions? For a definition, interpretation, or value
  judgment, require a stable meaning, examples and exclusions, or explicit
  criteria and argument. Do not demand an experiment for a stipulative
  definition, mathematical proof, preference, or fictional premise.

Missing evidence makes a claim unsupported here; it does not establish falsity,
fabrication, or lying. Conversely, later confirmation of a fact does not make an
earlier claim of having verified it accurate. Distinguish an incomplete record
from a complete record demonstrating that claimed work did not occur.

## 3. Classify the observable failure

Use the following overlapping categories to select a test and repair. They are
not synonyms or a severity ladder. Falsity concerns content; phoniness concerns
represented authenticity; fakery concerns manufactured support. Several may
apply to one passage. An observable defect can be established while its cause
remains unknown. Mark a pattern as suspected when the defining evidence is
missing, and name the defect directly instead of accusing a person.

| Pattern | Operational definition and observable signals | Boundary with adjacent patterns | Test questions | Corrective action |
| --- | --- | --- | --- | --- |
| **Bullshit** | A purported factual answer is produced or maintained without letting relevant truth checks constrain it. Signals include replacing verification with plausibility, preserving a conclusion after its basis collapses, or inventing context to sustain it. | A false result, missing citation, persuasive aim, or careless mistake alone does not establish this mode of activity. Meaningful and true sentences can participate in it. | Which evidence shaped the answer? What finding would actually change it? Is the response performing the inquiry it represents itself as performing? | Reopen the underlying question, establish the missing basis, and rebuild the answer from the resulting evidence. Trace the enterprise in step 4. |
| **Falsity** | A determinate proposition conflicts with established facts, the supplied artifact, or a valid calculation in the stated scope. Signals: mismatched numbers, dates, behavior, or explicit counterexamples. | Unsupported is not false. Falsity alone establishes neither lying nor disregard for truth. | What precisely contradicts it? Do both sides use the same conditions, units, and meaning? | Correct or retract the proposition; recompute every conclusion that depended on it. Preserve the correction's scope. |
| **Lying** | Asserting what the speaker believes false in order to mislead. An explicit admission or documented instruction to conceal a known result can support this classification. | Falsehood or a conflicting log alone does not establish belief or intent. A statement believed false can accidentally be true. | What evidence establishes the contrary belief and deceptive purpose, rather than error, stale information, or a different referent? | Retract the misleading assertion and state the record accurately. Without evidence of intent, report the contradiction or unsupported claim without calling it a lie. |
| **Humbug** | Misleading self-presentation through implications or displays of care, competence, conviction, or rigor. Signals: ceremonial assurances of diligence used to induce trust without corresponding work. | Focuses on the impression of the speaker; phoniness can concern the whole inquiry or artifact. An explicit false report of work is also a factual claim to check. | What impression does the assurance invite? What conduct supports it? Would the audience infer more diligence or conviction than the record warrants? | Remove the unsupported self-endorsement; describe the relevant work and limits, and perform any missing authorized check the task requires. |
| **Phoniness** | Something is presented as an authentic investigation, explanation, verification, or judgment while its actual basis does not match that representation. Signals: a guess framed as a finding, or recitation framed as understanding. | The result may be correct and polished. Unlike fakery, this need not involve manufacturing a concrete source or artifact. | Does the claimed provenance match the actual process? Can I explain how the evidence leads to the conclusion, rather than repeat its vocabulary? | Correct the account of how the result was obtained; establish the missing derivation or verification before retaining a claim that requires it. |
| **Fakery** | Inventing or altering evidence, citations, quotations, observations, tool results, or credentials and presenting them as authentic. Signals: nonexistent references, a quotation absent from its source, or synthetic output labeled as an actual run. | Failure to retrieve a source is not proof it was invented. Disclosed synthetic examples and simulations are legitimate. Fakery identifies manufactured support; lying additionally requires evidence about belief and intent. | Can the artifact and its asserted origin be checked? Does the source actually contain the attributed content? Is the record complete enough to establish fabrication? | Remove counterfeit support and retract dependent claims. Restore the actual record, or label synthetic material and obtain real evidence where required. |
| **Quackery** | An expertise or method claim sells a diagnosis, remedy, or guarantee beyond demonstrated competence or validation. Signals: universal cures, technical authority without an applicable method, or anecdote presented as validation. | Lack of credentials or an unconventional method alone proves nothing. Expert status also does not establish that a particular recommendation works. | What mechanism, evidence, validation conditions, and limits support this application? What would show that it fails? | Withdraw the unsupported guarantee; specify the supported application and limits, or obtain the relevant validation before recommending it. |
| **Pleonasm** | Repetition that adds no proposition, distinction, condition, or necessary communicative function. Signals: stacked synonymous assurances or a conclusion repeated as its own explanation. | Useful emphasis, accessibility, and a modifier that excludes an alternative are not empty redundancy. A circular argument also needs logical repair. | What information or useful function disappears if this phrase is deleted? Does the repetition supply evidence or merely repeat the claim? | Delete or consolidate empty repetition. Preserve meaningful qualifications; replace a circular explanation with independent premises or leave it unestablished. |
| **Nonsense** | An apparently assertive expression has no coherent proposition under its stated meanings: predicates, categories, or relations do not fit. Signals: applying a metric to an object for which it is undefined, or metaphor doing the work of a mechanism. | An intelligible false proposition, unfamiliar theory, or interpretable metaphor is not thereby meaningless. | Can I give a plain paraphrase, identify the referents, and state what would make the assertion hold? Are its predicates defined for those referents? | Repair the category or define the relation if the context warrants it; otherwise remove it and identify the explanation still missing. |
| **Gibberish** | Words, symbols, or syntax fail to yield a stable interpretable statement in the available context. Signals: broken token sequences or combinations with no recoverable relations. | Specialized notation, another language, and corrupted transmission may be intelligible with the right key. Nonsense can have readable grammar. | Is there a relevant grammar, glossary, notation, or intact source that makes this interpretable? Can the relations be reconstructed without inventing content? | Recover the source or notation when available. Otherwise mark it uninterpretable and omit it from the argument; do not manufacture a technical explanation. |
| **The unclarifiable** | A claim resists stable clarification: proposed definitions are circular, shift under challenge, or accommodate every outcome while purporting to explain something. | Currently unclarified is not proven inherently unclarifiable. Lack of empirical falsifiability alone does not make a concept meaningless. | Using the available definitions, can I supply a stable paraphrase, an application, and an exclusion or distinction? Does each attempted clarification preserve the same claim? | Attempt that bounded clarification and consult relevant context. If it fails, report exactly what remains unclarified, remove its role as a premise, and specify the missing definition; do not declare the entire subject meaningless. |

Protect honest mistakes, bounded hypotheses and estimates, disclosed assumptions,
useful abstractions, idioms, fiction, and supported confidence. None automatically
establishes bullshit. Do not replace unsupported optimism with unsupported
skepticism or turn every wording issue into an epistemic accusation.

## 4. Trace the enterprise behind the pattern

The **enterprise** is the activity the response is undertaking: for example,
explaining a cause, evaluating an option, reporting completed work, persuading,
or exploring possibilities. Compare the stated activity with what the observable
choices accomplish. A legitimate rhetorical or exploratory purpose is not a
defect; the failure occurs when it substitutes for inquiry while claiming the
authority of inquiry.

For each material pattern, record:

`claimed activity → observable choice → possible substitute objective → missing
truth constraint → process correction`

Use these hypotheses only when the record supports them. Do not invent a
psychological cause, an agent's hidden reasoning, or the author's intentions.
If several explanations fit, report the defect and the evidence needed to
distinguish them; uncertainty about the enterprise does not prevent repair.

| Possible substitute activity | Observable choice and test | Process correction |
| --- | --- | --- |
| Appearing knowledgeable | Specific mechanisms, citations, or claims of close reading appear without an inspected or explainable basis. Can I reconstruct the argument and its limits from the actual source or artifact? | Inspect the missing source or mechanism; distinguish what is established from recalled or conjectured content. |
| Manufacturing confidence or completion | Exact numbers, guarantees, or success language exceed measurements and acceptance criteria. Would the claimed success survive inspection of the actual result and tested scope? | Reconcile claim, action, result, and criterion; report unfinished work and complete the missing authorized verification. |
| Protecting a preferred conclusion | Counterevidence is omitted, criteria shift, objections demand stronger evidence than endorsements, or agreement replaces an argument. Would the same rule favor the other option with names swapped? | Restore the stated criterion, material counterevidence, and symmetric evaluation; let the conclusion change. |
| Evading uncertainty or accountability | A neighboring question replaces the original; passive wording hides who did what; hedges preserve an unsupported proposition. Which missing premise still decides the user's question? | Answer that question at the supported level; identify the actor, action, uncertainty, and decisive check where relevant. |
| Filling space or performing rigor | Repetition, jargon, citations, audit rituals, or activity lists add no evidence or decision-relevant distinction. What does each addition let the reader establish? | Remove additions that do no work; perform the missing reasoning or state its limit. |
| Appeasing the audience | Praise, concessions, or criticism follow the user's preference rather than new evidence. What changed in the record to justify the change in judgment? | Reassess both premises and feedback against the same evidence; retain supported disagreement. |

Treat the counterfactual questions as probes, not evidence that a motive exists.
A claim may arise from error or incomplete context. Repair demonstrated failures
without pretending to have established their hidden cause.

## 5. Repair the claim and its dependencies

Choose a substantive disposition for each material issue:

- **Verify** when an available, relevant check can resolve it within the task.
  Inspect source content and applicability, not just its title or authority.
- **Narrow** when evidence supports only a weaker proposition or smaller scope.
  Replace unjustified precision with the measured precision or a justified range.
- **Qualify as a hypothesis, estimate, or assumption** only when there is a
  stated basis and the conditional use is useful. Name what remains unknown and
  how it affects the conclusion. Adding “probably” cannot rescue a baseless claim.
- **Retract or remove** when contradicted, fabricated, empty, or unnecessary.
- **Leave unresolved** when decisive evidence is unavailable. State the missing
  premise, the check that would resolve it, and which conclusion must wait.

Then rebuild the reasoning from premises to conclusion. Look for circularity,
equivocation, correlation treated as causation, an untested alternative,
generalization beyond the sample, absence of evidence treated as evidence of
absence, and a source or consensus used outside its scope. Identify the exact
invalid transition; do not merely call an argument “weak.” If a premise changes,
revisit all dependent conclusions, recommendations, confidence, and success
reports. An unchanged conclusion requires an independent surviving basis.

Check relevance and meaning after the logic is repaired. Define a needed term,
explain its mechanism or contract, and remove meaningless or redundant language.
Preserve qualifications needed to use the result correctly. Apply these same
checks to your objections, praise, severity, citations, and proposed fixes.

## 6. Recheck the final output and deliver

After the last substantive or stylistic edit, compare the corrected claims with
the evidence record from step 1. Extract each newly introduced factual clause,
including clauses inside proposed fixes. For each addition, identify its source
or valid derivation. If neither exists, remove it or make the necessary condition
explicit. A correction may itself introduce a new failure mode.

For reports of work, keep **action, execution status, result, and acceptance
criterion** separate. Leave absent fields unknown: “inspected frontmatter and
links” supplies no pass result, and “requested approval” supplies no approval.
Do not fill gaps to make the corrected answer sound complete.

Check that:

- Material claims have an adequate basis at their stated scope, or their
  unresolved status and consequence are explicit.
- Claims of knowing, reading, checking, testing, or completing match the record.
  A proposed check is never reported as performed; an invocation is never
  reported as a pass without its result and relevant criterion.
- Repaired definitions and premises support the remaining reasoning; no new
  factual assertion, accusation, or success claim was introduced without support.
- The answer addresses the original question, including any decisive uncertainty.

Stop when material defects are corrected or explicitly bounded and no feasible
authorized check needed for the answer remains undone. Do not expand a bounded
review into unlimited research or guarantee a bullshit-free result.

For an explicit audit, report material findings as: exact claim and impact →
evidence and pattern → supported enterprise diagnosis, or cause unknown →
correction and remaining check. Include the corrected answer when requested.
If no finding is supported, say so with the scope of the check. When embedded in
another workflow, return its requested artifact without an extra audit report.

Correct only within the authorized scope. A review does not authorize rewriting
the reviewed artifact or posting feedback. If an independent critic is needed
for a specific unresolved framing issue, use one only when the parent workflow
permits it. A read-only leaf reviewer must not edit, post, or delegate; report
the unresolved premise to its orchestrator. Agreement is not validation.

## When the user signals “stop bullshitting me”

Re-read the original question, your answer, the reaction, and available evidence.
Apply the procedure to the specific claim or evasion, rather than treating the
reaction as a tone request. Briefly acknowledge the demonstrated defect, correct
it, and resume the original task. Do not invent an explanation for the reaction.

If the challenged claim remains supported, explain its basis and what would
change it. Do not concede to appease. Ask a focused clarification only if a
material ambiguity cannot be resolved from the conversation and available work.
