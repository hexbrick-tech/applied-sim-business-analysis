# Applied SIM for Business Analysis

**Draft 0.2 — Trial Candidate**

## 1. Purpose

Applied SIM for Business Analysis explores how the Semantic Isolation Method (SIM) can be applied to Business Analysis without silently importing software-development stages, artifacts, or implementation assumptions into the business-analysis domain.

This document is not a generic Applied SIM specification.

It is a domain-specific application artifact derived from SIM Foundation and tested against Business Analysis practice.

Its purpose is to preserve useful semantic distinctions while allowing Business Analysis to expose its own structures through application and observation.

The working principle is:

> Explore broadly, commit conservatively.

Applied structures should therefore be treated as Derived or provisional unless the Foundation directly establishes them.

---

## 2. Foundation

Applied SIM for Business Analysis is grounded in SIM Foundation.

The following Foundation concepts are directly relevant to this application:

- Observation
- Interpretation
- Evaluation
- Difference
- Unknown
- Undefined
- Observer
- Semantic Boundary
- Semantic Authority
- Semantic Probe
- Reflexive Observation Principle

The Applied structures introduced later in this document are not automatically Foundation Canon.

In particular, terms such as **Reasoning Boundary**, **External Evaluation**, **Provenance Scaffold**, **Metacognitive Guidance**, and **Recognition Capability** are Applied structures or working hypotheses unless explicitly stated otherwise.

The distinction matters because an Applied artifact must not silently redefine its Foundation.

---

## 3. Business Analysis Context

Business Analysis frequently operates on subjects whose meaning is not already available as a complete set of business rules.

The analyst may encounter:

- partially documented work,
- implicit operating practices,
- inconsistent terminology,
- incomplete decision criteria,
- local conventions,
- stakeholder assumptions,
- unresolved distinctions,
- and activities whose completion conditions are not explicit.

The analytical subject may therefore need to be observed before it can be described precisely.

A recurring pattern is:

```text
Observe work
    ↓
Ask questions
    ↓
Expose Undefined areas
    ↓
Return to earlier observation
    ↓
Stabilize meaning incrementally
```

Applied SIM for Business Analysis treats this incompleteness as observable information rather than as a defect that must be immediately filled.

---

## 4. Reasoning Cycle

A provisional Applied reasoning cycle emerged from historical replay of Business Analysis activity:

```text
Observe
   ↓
Preserve
   ↓
Evaluate
   ├── sufficient
   └── unresolved / uncertain
              ↓
          Re-observe
```

This is an Applied structure.

It does **not** imply that Observation flows directly into Evaluation without Interpretation.

SIM Foundation distinguishes:

```text
Observation ≠ Interpretation ≠ Evaluation
```

The exact placement of Interpretation within the Applied reasoning structure has not yet been established.

It must therefore not be silently absorbed into either Observation or Evaluation.

### 4.1 Observe

Observe what can actually be established about the analytical subject.

Observation should remain distinguishable from meaning assigned to what was observed.

Example:

```text
[O] A stakeholder did not speak during the meeting.
[I] The stakeholder did not agree with the proposal.
```

The first statement records an observation.

The second assigns meaning to that observation.

They may both be useful, but they are not the same epistemic act.

### 4.2 Preserve

Preserve observations, distinctions, unresolved matters, sources, and relevant context so that later reasoning does not silently replace them.

Preserve is a **Derived** Applied operation.

It is motivated by SIM's preservation of semantic distinctions, observability, Difference, uncertainty, and traceability, but it is not asserted here as a named Foundation stage.

Preservation may include:

- observed facts,
- source references,
- unresolved questions,
- explicit assumptions,
- interpretations,
- model-derived content,
- and distinctions discovered during analysis.

### 4.3 Evaluate

Evaluation applies a concern, objective, criterion, policy, or model to material already available to the analysis.

For example:

```text
[O] A stakeholder did not speak during the meeting.

[I] The stakeholder's position on the proposal was not established.

Concern:
Is stakeholder alignment sufficiently understood for the decision?

[E]
Stakeholder alignment has not yet been sufficiently confirmed.
```

Evaluation does not create the Interpretation by definition.

Observation, Interpretation, and Evaluation remain distinguishable.

Evaluation may conclude that the current understanding is sufficient for the present purpose, or that further observation is required.

### 4.4 Re-observation

When evaluation exposes unresolved or insufficiently understood areas, the cycle may return to observation.

This return should not be treated as failure.

It is a normal consequence of discovering a Difference, Unknown, Undefined state, or other unresolved distinction.

A return may involve:

- another stakeholder question,
- examination of another artifact,
- observation of actual work,
- a Semantic Probe,
- or a change in the current reasoning boundary.

---

## 5. Reasoning Boundary

**Reasoning Boundary** is an Applied-derived concept in this document.

It is not used as a synonym for SIM Foundation's **Semantic Boundary**.

The concept emerged from applying several Foundation concerns together:

- semantic isolation,
- Semantic Boundary,
- Semantic Authority,
- Observer,
- and preservation of explicit reasoning context.

A Reasoning Boundary identifies what is currently allowed to influence the analysis.

It may constrain:

- the subject currently being analyzed,
- accepted sources,
- assumptions,
- observer roles,
- questions currently in scope,
- downstream artifacts,
- and information that must not yet become authoritative.

A provisional function called **Constrain** can be observed here.

At present, Constrain is treated as a property or function of the reasoning environment rather than as a step inside the reasoning cycle.

Its generic status remains open.

The purpose of the boundary is not to prevent information from crossing it permanently.

The purpose is to make crossings observable.

---

## 6. Unknown and Undefined State

SIM Foundation directly recognizes **Unknown** and **Undefined**.

Applied SIM for Business Analysis preserves these states rather than silently completing them.

**Unknown** indicates that something relevant is not currently known.

**Undefined** indicates that something cannot currently be placed within the established semantic structure.

Undefined is therefore a directional signal.

It may indicate that further observation, distinction, interpretation, or inquiry is required.

It is not automatically an error and does not automatically require immediate resolution.

An analysis may also encounter unresolved conditions such as ambiguity, conflict, or insufficient distinction.

This document does not attempt to create a complete Applied uncertainty taxonomy.

The important requirement for the current trial is that unresolved states remain observable rather than being silently converted into confident conclusions.

---

## 7. External Evaluation

The Business Analysis replay exposed a second kind of evaluation.

The inner reasoning cycle evaluates the analytical subject.

**External Evaluation** evaluates the state of the analysis itself.

Example:

```text
Inner Evaluation:
What does the observed business activity imply?

External Evaluation:
Is the current analysis sufficiently understood
to support the next analytical activity?
```

External Evaluation sits outside the provisional cycle:

```text
            External Evaluation
                    │
                    ▼
        ┌───────────────────┐
        │ Reasoning Boundary│
        │                   │
        │ Observe           │
        │   ↓               │
        │ Preserve          │
        │   ↓               │
        │ Evaluate          │
        │   │               │
        │   └→ unresolved   │
        │        │          │
        │        └→ Observe │
        └───────────────────┘
```

External Evaluation is **Derived**.

Its Foundation basis includes:

- Observer,
- Reflexive Observation Principle,
- Semantic Authority,
- and convergence-related reasoning.

External Evaluation does not create missing answers.

If the analysis is insufficient, its appropriate result may simply be to return to observation, change the boundary, or preserve the unresolved state.

---

## 8. Lightweight Provenance Scaffold

During Applied exploration, a lightweight provenance notation emerged:

- `[O]` — **Observation**: directly observed or confirmed material.
- `[I]` — **Interpretation**: meaning assigned to Observation.
- `[A]` — **Authored**: premise, definition, requirement, or constraint explicitly introduced by a human or designer.
- `[M]` — **Model-derived**: content derived from explicit premises or a model.
- `[U]` — **Unknown**: provenance, causality, or meaning cannot currently be determined.

These tags are a **Derived scaffold**, not a replacement for Foundation terminology.

In particular, `[U]` must not collapse more precise Foundation distinctions such as Unknown, Undefined, Ambiguous, or Conflicting when those distinctions matter.

The purpose of the scaffold is metacognitive:

> Keep different cognitive and provenance states from silently collapsing into one another.

### 8.1 Model-derived content and feedback

`[M]` is not itself a Feedback operation.

Model-derived content can, however, act as a **Feedback Carrier** when it is returned to observation.

```text
Model
  ↓ derive
[M] derived content
  ↓
Question / Probe
  ↓
Subject
  ↓
[O]
  ↓
Difference detection
  ↓
Model reconsideration
```

The important movement is:

```text
Derived content
    ↓
Question / Probe
    ↓
Observation
    ↓
Difference
    ↓
Re-evaluation
```

This prevents a model's own output from becoming self-confirming evidence.

AI-generated content is not automatically Observation.

Depending on how it was produced, AI-assisted material may contain Observation, Interpretation, Authored premises, Model-derived conclusions, or unresolved provenance.

---

## 9. Metacognitive Guidance

Applied use may include explicit prompts that help the Observer recognize the cognitive status of a statement.

Examples:

> Is that confirmed as [O], or is it an [I] assigned to what was observed?

> Is that value directly present in the source [O], or was it derived from the source [M]?

> Is this second opinion providing new [O], or another model's [M]?

This guidance does not determine what the Observer should believe.

It guides the procedure used to recognize how a statement entered the reasoning context.

Metacognitive Guidance is **Derived**, primarily from the Foundation's treatment of Observer and the Reflexive Observation Principle.

The notation itself is expected to be lightweight.

As recognition becomes stable, explicit tagging may become less necessary.

---

## 10. Observer Recognition

A working hypothesis emerged from the Business Analysis exploration:

> Preserving Semantic Structure may not be sufficient by itself. The Observer may also need the capability to recognize that structure reliably.

This is currently called **Recognition Capability**.

Recognition Capability may include the ability to notice distinctions such as:

- Observation versus Interpretation,
- Interpretation versus Evaluation,
- explicit premise versus derived conclusion,
- model output versus external evidence,
- resolved meaning versus Undefined structure,
- and current reasoning context versus information outside the boundary.

Recognition Capability is a **Working hypothesis**.

It is not yet asserted as a generic Applied SIM requirement.

The Business Analysis trial should help determine whether this capability is actually required, naturally emerges from use, or should be represented differently.

---

## 11. Worked Example — Research Pickup Activity

The following example is based on historical replay of a Business Analysis activity.

A research workflow contains an activity called `pickup`.

At the beginning of analysis, the meaning and completion conditions of pickup are not fully established.

### 11.1 Initial observation

Observed behavior includes:

- a researcher searches the web for information,
- discovered information may become a new pickup registration,
- metadata needed for later longlist research is registered,
- metadata may include technology overview, era or year, country, and similar attributes,
- the source is preserved,
- non-metadata information may be retained as a researcher memo,
- AI may assist with metadata extraction,
- acquisition is not automatic,
- AI interaction occurs through predefined chat prompts,
- no further action occurs until the item becomes a longlist candidate,
- and the current activity checks whether its own work is complete.

These can be preserved as `[O]` where directly confirmed.

### 11.2 Interpretation and distinction

Analysis exposes several distinctions.

For example:

```text
metadata ≠ researcher memo ≠ source
```

and:

```text
pickup completion ≠ longlist qualification
```

Assigning meaning to these observations is Interpretation.

Judging whether they are sufficient for the analytical purpose is Evaluation.

The two acts should not be collapsed.

### 11.3 Undefined areas

At this point, some aspects of pickup may remain Undefined.

The method does not require the analyst to invent missing business rules merely to complete the model.

Undefined areas are preserved and may guide further questions.

### 11.4 Historical return

In the historical process, analysis moved forward into a later feedback activity.

Questioning there exposed that the earlier pickup activity had not been understood sufficiently.

External Evaluation therefore effectively produced:

```text
Is the current understanding sufficient
to support the next analysis?

No.
```

The analysis returned to pickup.

The boundary moved back to the earlier activity, and additional observation, interpretation, and evaluation occurred as required.

The resulting pattern was:

```text
Observe
  ↓
Preserve
  ↓
Interpret / Evaluate as required
  ↓
Undefined remains visible
  ↓
Proceed provisionally
  ↓
External Evaluation
  ↓
Insufficient
  ↓
Return to Observe
```

This historical description does not establish `Interpret` as a mandatory operation in the provisional cycle.

Its placement remains open.

The important observation is that Interpretation remained distinguishable from Observation and Evaluation.

---

## 12. Foundation Traceability

| Applied element | Foundation relationship | Status |
|---|---|---|
| Observe | Observation | Direct |
| Preserve | Preservation of semantic distinctions, observability, Difference, uncertainty, traceability | Derived |
| Evaluate | Evaluation | Direct |
| Reasoning Boundary / Constrain | Semantic isolation, Semantic Boundary, Semantic Authority, Observer | Derived |
| Unknown | Unknown | Direct |
| Undefined | Undefined | Direct |
| External Evaluation | Observer, Reflexive Observation Principle, Semantic Authority, convergence-related reasoning | Derived |
| Provenance tags | Observation / Interpretation distinction and provenance-preserving reasoning | Derived |
| Metacognitive Guidance | Observer, Reflexive Observation Principle | Derived |
| Recognition Capability | Observer-facing recognition of preserved distinctions | Working hypothesis |

This table records traceability, not equivalence.

A Derived element must not be treated as Foundation Canon merely because it can be traced to Foundation concepts.

---

## 13. Current Boundary

This Draft intentionally does **not** define:

- a complete Business Analysis methodology,
- a complete taxonomy of analytical states,
- a mandatory artifact set,
- a certification or conformance model,
- a generic Applied SIM specification,
- a universal stopping rule,
- a mandatory position for Interpretation inside the Applied cycle,
- or a requirement that every Undefined area be resolved.

The following questions remain open for observation during trial:

1. Does Reasoning Boundary provide practical value as a distinct Applied concept?
2. Does Constrain need to exist as an explicit concept?
3. Does `insufficient distinction` require a defined state, or can existing distinctions represent the observed need?
4. Where does Interpretation naturally appear in actual use?
5. Are provenance tags useful scaffolding or unnecessary overhead?
6. Does Metacognitive Guidance materially improve recognition?
7. Does Recognition Capability emerge as a genuine requirement?
8. Does `[M]` reliably function as a Feedback Carrier in broader cases?
9. Which of these structures generalize beyond Business Analysis?

These questions are observation targets, not requirements to force into resolution.

---

## 14. Status

**Draft 0.2 — Review PASS / Trial Candidate**

Draft 0.2 incorporates corrections identified during external review of Draft 0.1.

The blocking corrections were:

1. Foundation terminology was corrected so that Applied-derived concepts are not presented as Foundation Canon.
2. Observation, Interpretation, and Evaluation were explicitly separated.

Traceability was also corrected so that:

- Observe is Direct,
- Preserve is Derived,
- Evaluate is Direct,
- Reasoning Boundary / Constrain is Derived,
- Unknown is Direct,
- Undefined is Direct,
- External Evaluation is Derived,
- provenance tags are Derived,
- Metacognitive Guidance is Derived,
- and Recognition Capability remains a Working hypothesis.

External re-review found no blocking issue preventing a Business Analysis trial.

Two non-blocking loose ends remain intentionally observable during trial:

- whether `insufficient distinction` requires explicit definition,
- and whether `Constrain` requires explicit definition.

They are not resolved in advance because doing so would risk creating structure before practical use demonstrates that the structure is needed.

The next step is to freeze this Draft for trial use, apply it to Business Analysis, observe its behavior, and use the resulting evidence to evaluate the artifact itself.
