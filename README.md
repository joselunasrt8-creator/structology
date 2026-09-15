# Structology

> **Status:** Structology Candidate Model v0.1  
> **Validation status:** Provisional and not empirically validated

The canonical candidate model is defined in [CANON.md](CANON.md). This README states why the repository exists, what problem the model is trying to solve, and what evidence would be required before stronger claims are justified.

## Purpose

Structology investigates whether designed systems can be described using a small, reusable set of structural concepts without collapsing important distinctions between **what exists**, **rules for change**, **a concrete change**, and **evaluation of that change**.

Its governing question is:

> **What minimum structural concepts are necessary and sufficient to represent objects, relationships, states, transformations, provenance, verification, and failure across more than one designed-system domain without forcing domain-specific meaning into the general model?**

Candidate Model v0.1 proposes an answer. It does not establish that the answer is complete, minimal, independent, natural, or transferable.

```text
Candidate vocabulary ≠ discovered universal structure
Conceptual coherence ≠ empirical validity
Cross-domain resemblance ≠ natural transfer
Formal separation ≠ practical usefulness
```

## Why this repository exists

Many systems mix several different things into the same records or language: an object and an action on that object, a rule and an execution of the rule, or verification and authority. Structology proposes explicit distinctions so those categories can be examined separately.

The candidate separation is:

```text
Structology
Describes what exists
        ↓
Methodology
Declares how objects may validly evolve
        ↓
Execution
Performs one concrete transformation
        ↓
Verification
Evaluates the event or resulting artifact
```

The arrows indicate specialization and use, not authority or causal necessity.

This separation is currently a **candidate analytical model**. Its value must be tested by asking whether independent domains can use it without semantic distortion and whether it improves analysis compared with simpler or domain-native representations.

## Candidate concepts

Candidate Model v0.1 currently includes:

- object types and object instances;
- relationships;
- state and lifecycle;
- methodology definitions;
- transformation contracts and transformation events;
- preconditions, postconditions, constraints, and invariants;
- execution;
- verification requirements and verification results;
- provenance;
- failure semantics; and
- versioning, supersession, withdrawal, and invalidation.

The precise definitions and classifications are normative only within Candidate Model v0.1 and are maintained in [CANON.md](CANON.md).

## Core distinctions

```text
Object Type ≠ Object Instance
Object ≠ Execution
Methodology ≠ Execution
Transformation Contract ≠ Transformation Event
Transformation ≠ Verification
Verification ≠ Authority
```

These distinctions are hypotheses about useful structural separation. Their usefulness, independence, completeness, and transferability remain open empirical questions.

## What Structology does not yet know

Candidate Model v0.1 has not established:

- that the proposed concepts are the minimum set required;
- that the concepts are mutually independent;
- that every relevant designed-system domain maps naturally to them;
- that every admissible transformation fits the proposed contract;
- that the distinctions improve reasoning or engineering outcomes;
- that provenance can remain domain-neutral while remaining useful;
- that methodology composition requires no additional primitives;
- that domains will agree on stable object/state boundaries; or
- that the framework adds value beyond existing modeling approaches.

These are research questions, not implementation backlog items.

## Domain specialization boundary

Structology supplies provisional general concepts. A domain methodology supplies the domain-specific semantics, admissibility rules, evidence requirements, verification thresholds, uncertainty treatment, decision rules, and authority model where applicable.

```text
Structology Candidate Model
        ↓ specialization
Domain Methodology
        ↓ instantiation
Domain Execution
```

A successful mapping from one domain is not evidence of universality. A mapping can also be partial, forced, ambiguous, or failed.

The model should not be modified during an evaluation merely to make a chosen domain fit unless that modification is recorded as an outcome that invalidates the frozen candidate for that test.

## Relationship to SYNAPSE

Structology and SYNAPSE have different roles.

```text
Structology
Candidate structural vocabulary / theory
        ↓ may motivate
Formal structural questions
        ↓ may be implemented by
SYNAPSE
Deterministic structural analysis / evidence
```

SYNAPSE implementing a structural analysis does not validate Structology. Structology does not require SYNAPSE, and SYNAPSE does not inherit the validity of a broader structural theory.

## Relationship to the Continufy R&D repositories

Continufy repositories may reference, specialize, test, reject, or refine Structology concepts, but ecosystem membership does not validate the candidate model or create mandatory dependencies.

A useful responsibility separation is:

```text
MindShift              candidate cognition / research questions
Research Methodology   research contracts and instruments
ABR                    empirical investigation
Structural Foundations bounded formal theory
SYNAPSE                deterministic structural analysis
ContinuityOS           legitimacy / execution-boundary mechanisms
```

Structology sits beside these as a candidate general structural model. It does not control their artifacts, grant authority to them, or become true because they use its vocabulary.

## Validation program

The next stage belongs outside this repository and should use a prospectively frozen audit instrument.

The strongest first test is a **cross-domain transfer audit**:

1. freeze Candidate Model v0.1 and its definitions;
2. select independent domains prospectively rather than because they obviously fit;
3. obtain domain-native descriptions before mapping them to Structology;
4. map each domain without altering the candidate model;
5. classify each concept as natural fit, partial fit, forced fit, absent, ambiguous, or requiring a new primitive;
6. compare against a simpler/domain-native representation;
7. use independent adjudication where practical; and
8. preserve negative and indeterminate outcomes.

The audit should measure more than whether a mapping can be written. It should test whether the mapping preserves domain meaning and whether the distinctions provide measurable analytical value.

## Evidence ladder

Structology should earn stronger claims in stages:

```text
Candidate model explicit
        ↓
Independent domains can be mapped
        ↓
Mappings preserve native meaning
        ↓
Concepts transfer without forced fit
        ↓
Model beats or complements strong baselines
        ↓
Results replicate across domains
        ↓
Bounded claim of general usefulness
```

No stage implies the next.

## Falsification boundary

Candidate Model v0.1 should be revised, narrowed, or rejected if evidence shows that:

- important domains require incompatible foundational meanings;
- mappings repeatedly require forced fit;
- supposedly distinct concepts collapse into one another in practice;
- required primitives are systematically missing;
- the minimum transformation contract fails on common domain changes;
- domain-native models preserve meaning more accurately with less complexity;
- the model adds no measurable analytical benefit; or
- results do not replicate under independent mapping/adjudication.

Negative results are valid outcomes and should remain visible in provenance.

## Non-scope

Structology does not currently:

- execute domain workflows;
- authorize scientific or operational claims;
- grant authority or permission;
- define domain-specific procedures or evidence thresholds;
- implement structural-analysis engines;
- build schemas, validators, compilers, registries, or runtime behavior;
- mutate external systems;
- perform the cross-domain validation itself; or
- claim universal applicability.

## Current boundary

This repository currently stops at **Structology Candidate Model v0.1**.

The model is explicit enough to be frozen and tested independently. Its strongest present claim is therefore not that it describes designed systems generally, but that it provides a concrete candidate vocabulary and set of distinctions for testing that hypothesis.

The next legitimate artifact is empirical evidence from an independent cross-domain transfer audit—not additional expansion of the candidate vocabulary before that test.
