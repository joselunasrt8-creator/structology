# Structology

> **Status:** Structology Candidate Model v0.1  
> **Validation status:** Provisional and not empirically validated

The canonical candidate model is defined in [CANON.md](CANON.md). The README introduces the repository boundary; the canon contains the normative candidate definitions, contracts, distinctions, limitations, and unresolved assumptions.

## Purpose

Structology investigates whether a small domain-neutral vocabulary can describe the structure and change of designed systems without importing domain-specific semantics or authority.

Its governing question is:

> **What minimum structural concepts are needed to distinguish what exists, how it may change, what concretely happened, and how the result is evaluated?**

Candidate Model v0.1 currently proposes concepts for objects, relationships, state, lifecycle, transformation contracts and events, methodology, execution, verification, provenance, failure, and version relations.

The repository does **not** assume that this vocabulary is complete, minimal, independent, universal, or necessary to Continufy. Those are research questions.

```text
Structural vocabulary
        ≠
Domain semantics
        ≠
Methodology
        ≠
Authority
        ≠
Execution legitimacy
```

## Candidate Separation

```text
Structural description
        ↓ possible specialization
Domain methodology
        ↓ possible application
Concrete transformation
        ↓ possible evaluation
Verification
```

The arrows indicate possible specialization and use, not a mandatory architecture or authority chain.

- **Structology** proposes provisional general concepts for describing structure and change.
- **A domain methodology** may specialize those concepts with domain meanings, admissibility rules, evidence requirements, and decision rules.
- **An execution** may apply one declared transformation contract to particular instances.
- **Verification** evaluates declared conditions without itself granting permission, legitimacy, or authority.

A domain may use only part of the candidate vocabulary, require additional primitives, or reject the model entirely.

## Candidate Concepts

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
- failure semantics;
- versioning, supersession, withdrawal, and invalidation.

The precise candidate definitions and classifications are maintained in [CANON.md](CANON.md).

These concepts are candidates, not established primitives. Their completeness, independence, transferability, and usefulness remain unresolved.

## Core Distinctions

```text
Object Type ≠ Object Instance
Object ≠ Execution
Methodology ≠ Execution
Transformation Contract ≠ Transformation Event
Transformation ≠ Verification
Verification ≠ Authority
```

These are candidate analytical distinctions. Their usefulness and transferability remain subject to independent testing.

## Domain Specialization Boundary

Structology supplies no domain meaning by itself.

A domain specialization owns its own:

- terminology;
- semantics;
- object and relationship meanings;
- admissibility rules;
- evidence requirements;
- verification thresholds;
- uncertainty treatment;
- decision rules; and
- authority model, when applicable.

A domain specialization must not be treated as evidence that the candidate model is universal. It is one possible application to be examined.

### Research example

A research methodology could choose to specialize some Structology concepts as research requests, protocols, observations, evidence records, analyses, findings, replications, and publication artifacts. Concrete investigations could then create and transform instances of those research-specific types.

Structology does not define those research objects or procedures, and research methodology does not need Structology merely because such a mapping can be constructed.

## Relationship to Continufy

Structology is a **candidate primitive-definition research repository**, not a required layer of the Continufy runtime or research topology.

Other repositories may reference, specialize, test, reject, or ignore its candidate concepts within their own boundaries. Membership in the same ecosystem does not create a dependency.

```text
Research relationship ≠ runtime dependency
Vocabulary compatibility ≠ architectural necessity
Structural description ≠ authority
Verification ≠ legitimacy
```

Possible evidence-supported outcomes include:

- a small subset of Structology concepts proves reusable across multiple domains;
- different domains require incompatible specializations;
- some candidate concepts collapse into simpler primitives;
- additional primitives are required;
- the model is useful only for methodology/research work;
- another existing formalism already solves the problem better; or
- Structology provides no measurable value and should remain archival or be retired.

The ecosystem therefore must not be organized around Structology unless evidence warrants that relationship.

## Current Scope

Candidate Model v0.1 is limited to documentation of:

- provisional domain-neutral concepts;
- the Object–Methodology–Execution–Verification separation;
- a candidate methodology object;
- a candidate transformation contract;
- a distinction ledger;
- domain-specialization boundaries;
- known limitations and unresolved assumptions.

## Non-Scope

Structology does not currently:

- perform cross-domain validation;
- define or run an audit protocol;
- select an audit cohort;
- define natural-transfer, partial-fit, forced-fit, or failure criteria;
- define research-specific evidence thresholds;
- define engineering, audit, clinical, manufacturing, or other domain procedures;
- execute domain workflows;
- authorize scientific claims;
- authorize operational execution;
- prove domain-specific theories;
- implement structural-analysis engines;
- build schemas, validators, compilers, registries, or runtime behavior;
- mutate external systems;
- claim universal applicability.

## Evidence Boundary

Internal coherence of Candidate Model v0.1 does not establish that Structology:

- contains the minimum necessary primitives;
- contains mutually independent primitives;
- transfers naturally across domains;
- improves methodology design;
- improves software architecture or engineering decisions;
- is required by another Continufy repository;
- should become software;
- has external adoption value; or
- has commercial value.

Those require independent evidence.

A useful falsification question is:

> **Does the Structology candidate vocabulary explain or improve work across independent domains better than simpler existing representations, without forcing domain-specific meaning into generic concepts?**

## Next Research Boundary

The next legitimate stage belongs outside this repository: design an independent transfer test that can expose both usefulness and failure.

```text
Candidate Model v0.1
        ↓
Independent transfer instrument
        ↓
Multiple unrelated domains
        ↓
Fit / partial fit / forced fit / failure / indeterminate
        ↓
Retain / simplify / extend / reject candidate concepts
```

The test should compare Structology against a strong simpler baseline rather than merely asking whether a domain can be translated into Structology terminology.

Evidence from such testing may motivate revisions, but it does not automatically mutate this repository or establish universal validity.

## Completion Boundary

This repository currently stops at **Structology Candidate Model v0.1**.

The model is explicit enough for independent testing, but it remains provisional, unvalidated, and open to simplification, rejection, or retirement.
