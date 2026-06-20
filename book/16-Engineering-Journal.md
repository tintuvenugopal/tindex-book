# Engineering Journal

## Purpose

This journal records only significant engineering decisions.

It is **not** a development log.

It is **not** a commit history.

It records decisions that changed the architecture, engineering process, or long-term direction of Tindex.

---

# 2026-06-20

## Decision

Separate the project into three institutional repositories.

### Result

- tindex-book
- tindex-specifications
- tindex-core

Reason

Separate institutional knowledge, canonical language, and executable implementation.

---

# 2026-06-20

## Decision

The Canonical Domain Model consists of six objects.

- Entity
- Property
- Observation
- Evidence
- Claim
- Validation

Result

Version 1 frozen for implementation.

---

# 2026-06-20

## Decision

Begin implementation before expanding specifications.

Reason

Implementation provides stronger evidence than architectural speculation.

---

# 2026-06-20

## Decision

Adopt vertical slices before horizontal expansion.

Result

First working capability:

Markdown

↓

Parser

↓

Canonical Extractor

↓

Entity

↓

Property

↓

Observation

---

# 2026-06-20

## Decision

Shift project focus from CRUD architecture to Knowledge Acquisition.

Reason

CRUD is generic.

Knowledge acquisition is Tindex's competitive advantage.

---

# Future Entries

Every major architectural change should be recorded here.

Routine commits should not.