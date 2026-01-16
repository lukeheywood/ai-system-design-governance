# Governance Patterns

This directory contains a library of **system-level governance patterns**.

Each pattern describes a recurring **class of governance absence or misalignment**
that can arise in complex systems where authority, responsibility, boundaries,
or enforcement are implicit, fragmented, or unstable under pressure.

These patterns are not case studies.
They are not incident reports.
They are not assessments of specific organisations.

They are **abstracted governance shapes** intended to make implicit assumptions
visible and inspectable.

---

## How to read these patterns

Each governance pattern follows a fixed structure defined in
[`_pattern_template.md`](./_pattern_template.md).

That structure is intentional.
It enforces abstraction and prevents drift into attribution, operational detail,
or reproducible failure sequences.

Patterns should be read as answers to the question:

> *“What governance condition must exist for this class of failure to be structurally prevented?”*

Not:
- what happened
- where it happened
- who caused it
- or how to recreate it

---

## Interpretive posture

All patterns in this directory represent **interpretive governance analysis**.

They are derived from repeated exposure to complex socio-technical systems and
reflect disciplined reasoning about structure, not claims of factual truth.

Interpretations are provisional by design and may evolve as:
- system boundaries shift
- governing intent changes
- new constraints emerge
- alternative readings are surfaced

Disagreement with a pattern is expected.
The appropriate response to disagreement is inspection, not deference.

---

## Responsible disclosure boundary

Only **abstracted governance patterns** are published here.

This directory does not contain:
- operational sequences
- timing or load thresholds
- system-specific vulnerabilities
- attribution of fault or intent
- recommendations tied to named organisations or systems

Concrete failures and live system risks are addressed privately.

This boundary is deliberate and non-negotiable.

---

## Purpose of this library

This pattern library exists to:

- raise the baseline of governance literacy
- provide a shared vocabulary for discussing authority and enforcement
- support early identification of governance gaps
- enable safer system design before failure forces clarity

It does not function as:
- an audit
- a certification
- a compliance checklist
- or a verdict engine

---

## Using these patterns

Patterns may be used as:
- analytical lenses during system review
- prompts for governance design conversations
- inputs to risk, safety, or integrity work
- reference material for governance-first system design

They should not be used to:
- judge specific organisations
- infer negligence
- or extract leverage

---

## Relationship to the broader framework

This pattern library sits downstream of the framework’s
**constitutional grounding phases** and upstream of system design and operation.

Patterns make visible the governance conditions that must be addressed
*before* technical or organisational solutions are attempted.

For the epistemic foundations of this work, see [`truth.md`](../truth.md).
