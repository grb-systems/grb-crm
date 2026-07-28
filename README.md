# CRM

## Constraint–Residue Mapping Protocol

> Look.
> Notice.
> We are still here.

---

## Overview

Constraint–Residue Mapping (CRM) is an open observational framework for identifying, recording, and comparing candidate relationships between interaction constraints and the structural residue that remains after interaction.

CRM does not begin by evaluating response quality.

Instead it asks:

> **What remained because the interaction was structured in a particular way?**

Rather than treating constraints as limitations alone, CRM treats them as experimental variables whose downstream effects may be observed, cataloged, and compared.

---

# Purpose

CRM exists to make interaction constraints empirically inspectable.

For each interaction, CRM records:

- what constraint was introduced;
- what immediate interaction changes were observed;
- what candidate residue emerged;
- whether that residue remained usable later;
- how later measurement instruments characterized the outcome.

CRM therefore provides an observational bridge between interaction design and measurable carry-forward.

---

# Core Definition

Constraint–Residue Mapping (CRM) is an observational protocol that records candidate relationships between:

- interaction constraints;
- observed interaction changes;
- emerging structural residue;
- later interaction outcomes.

CRM does not establish causation.

Instead, it documents repeatable mappings that may later be evaluated through empirical study.

---

# Research Question

CRM asks:

> **Which interaction constraints appear to produce which forms of retained structure?**

This differs from traditional interaction evaluation, which often asks only whether an interaction succeeded.

---

# Core Mapping

Every CRM record follows the same conceptual chain.

```text
Constraint

↓

Observed Interaction

↓

Candidate Residue

↓

Later Outcome
```

This chain becomes the primary mapping object.

---

# Example

Constraint:

> Use non-agentive language.

Observed interaction:

> Reduced persona narration.

Candidate residue:

> Stable distinction between system output and attributed intention.

Later outcome:

> Less corrective reframing required.

Measured by:

> Reduced clarification density.

---

# Constraint Categories

CRM may catalog constraints such as:

## Interaction Constraints

- non-agentive posture
- non-persona posture
- delayed closure
- bounded uncertainty
- explicit interaction rules

## Structural Constraints

- terminology stabilization
- explicit definitions
- hierarchy requirements
- return markers
- vocabulary limits

## Temporal Constraints

- delayed recall
- interruption
- session boundaries
- cross-thread return

## Information Constraints

- staged disclosure
- partial explanation
- reduced examples
- implementation hiding

---

# Residue Categories

CRM distinguishes several residue types.

## Lexical Residue

Stable terminology.

## Relational Residue

Preserved conceptual relationships.

## Procedural Residue

Remembered interaction procedures.

## Structural Residue

Retained interaction architecture.

## Behavioral Residue

Changes in later interaction behavior.

## Transfer Residue

Successful application outside the original context.

---

# Mapping Matrix

| Constraint | Immediate Effect | Candidate Residue | Later Outcome |
|------------|------------------|-------------------|---------------|
| Delayed closure | More exploration | Better relation retention | Higher transfer |
| Non-agentive posture | Reduced persona narration | Stable terminology | Lower clarification density |
| Return markers | Faster recovery | Lower reconstruction burden | Higher return-path fidelity |

CRM records observations.

It does not assume every mapping is universally valid.

---

# Operational Workflow

```text
Constraint

↓

Interaction

↓

Candidate Residue

↓

Residue Validation

↓

LAE-I Measurement

↓

Mapping Database
```

---

# Relationship to Recursive Doctrine

Recursive Doctrine proposes that interaction constraints reshape the interaction medium.

CRM asks:

- Which constraints?
- Under what conditions?
- Producing which observable residue?

CRM operationalizes these questions through structured observation.

---

# Relationship to Residue Validation

Residue Validation asks:

> Is the observed residue genuine?

CRM asks:

> What constraint appears to have produced it?

---

# Relationship to LAE-I

LAE-I measures:

- persistence
- reconstruction cost
- transfer
- clarification density
- compression stability
- retry burden
- human carry-forward

CRM explains where those measurements may have originated.

Simplified:

```text
CRM

"What produced the residue?"

↓

LAE-I

"How well did the residue survive?"
```

---

# Minimal Record

Each CRM observation should minimally contain:

```yaml
constraint:
observed_interaction:
candidate_residue:
later_outcome:
related_LAE_metrics:
confidence:
notes:
```

---

# Candidate Research Questions

Examples include:

- Which interaction constraints consistently improve transfer?
- Do different interaction postures produce distinguishable residue profiles?
- Which constraints reduce reconstruction burden?
- Which combinations of constraints interfere with one another?
- Which mappings remain stable across repeated studies?

---

# Design Principles

CRM follows several guiding principles.

1. Observe before explaining.
2. Record candidate relationships rather than assuming causation.
3. Distinguish immediate interaction from durable residue.
4. Preserve uncertainty where evidence is incomplete.
5. Enable independent replication.

---

# Repository Structure

```text
grb-crm/
│
├── README.md
├── SPECIFICATION.md
├── LICENSE
├── CITATION.cff
│
├── taxonomy/
│   ├── constraint-types.md
│   ├── residue-types.md
│   └── mapping-schema.md
│
├── protocols/
│   ├── observation.md
│   ├── delayed-evaluation.md
│   ├── comparative-study.md
│   └── cross-study.md
│
├── schemas/
│   ├── constraint.schema.json
│   ├── mapping.schema.json
│   └── residue.schema.json
│
├── examples/
│   ├── sample-records.yaml
│   ├── pilot-study-001.md
│   └── mapping-matrix.md
│
└── reference/
    ├── glossary.md
    ├── terminology.md
    └── implementation-notes.md
```

---

# Scope

CRM is an observational protocol.

It does not:

- claim causation;
- measure cognition;
- infer internal model mechanisms;
- evaluate intelligence;
- replace statistical analysis.

Instead, CRM records structured observations that may later support empirical investigation.

---

# Why AGPL

CRM is intended to support a growing public catalog of interaction constraints, observed residue, and comparative mappings.

Reciprocal licensing helps ensure that improvements, expanded taxonomies, mapping databases, and reference implementations remain openly available to the research community.

---

# Repository Philosophy

Interaction constraints are often treated only as restrictions.

CRM explores a complementary possibility:

that constraints may also shape interaction in ways that leave durable, reusable structure.

Rather than asking whether a conversation was merely successful, CRM asks:

> **What remained because the interaction was structured in this particular way?**

---

# Status

Initial conceptual specification.

The protocol defines an observational framework intended for pilot studies, comparative experiments, and future empirical refinement.

Candidate mappings should be regarded as hypotheses until supported through repeated observation and independent evaluation.

---

# License

GNU Affero General Public License v3.0 (AGPL-3.0)

See `LICENSE` for details.
