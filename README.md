# RESA Builder – Constraint Repository

This repository defines the **operational constraints** for the RESA Builder.

It does not describe a standard, framework, or methodology.
It exists solely to **bound and stabilise the behaviour** of the Builder
when preparing artefacts for later evaluation by RESA-10.

The contents of this repository are **not normative for artefacts**.
They are **binding only for the Builder**.

---

## Purpose

The purpose of this repository is to ensure that the RESA Builder:

- works deterministically
- avoids escalation, optimisation, or interpretation
- produces structurally closed, placeable repositories
- stops at the correct point

---

## Canonical Files

The repository consists of exactly six files.
Each file has a single, non-overlapping role.

### 1. `BUILDER_SCOPE.md`
Defines the Builder’s role, permissions, prohibitions, and stopping point.

### 2. `STRUCTURAL_SIGNALS.md`
Lists structural signals the Builder may observe to tighten form.
Signals are descriptive, not evaluative.

### 3. `ANALYSIS_QUESTIONS.md`
Defines the only allowed question forms.
All questions are indirect and non-optimising.

### 4. `PIPELINE_MODEL.md`
Defines the mandatory processing sequence.
The Builder must not deviate from this order.

### 5. `ANTI_PATTERNS.md`
Lists patterns that must be actively removed.
If removal weakens the artefact, it was not structurally closed.

### 6. `MONETIZATION_BOUNDARIES.md`
Defines what the Builder must not design or imply.
All monetisation logic remains structurally external.

---

## Usage

This repository is consumed implicitly by the RESA Builder.

It is:
- not referenced by artefacts
- not cited externally
- not versioned for evolution
- not subject to contribution or discussion

---

## Status

This repository is structurally closed.
No extensions, examples, or explanations are required.
