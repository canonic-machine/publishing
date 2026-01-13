# PUBLISHING

## Preamble (Non-normative)

PUBLISHING packages CANONIC evidence for external dissemination without
altering that evidence.

---

## 1. Purpose

Define the PUBLISHING scope as the dissemination layer for CANONIC papers.

---

## 2. Scope

- Applies to `/canonic/machine/os/writing/paper/publishing/`.
- Inherits from `/canonic/machine/os/writing/paper/`.
- Packages PAPER outputs for publication.

---

## 3. Normative language

The key words **MUST**, **MUST NOT**, **SHOULD**, **SHOULD NOT**, and **MAY** are
interpreted as described in RFC 2119.

---

## 4. Principles

### 4.1 Dissemination only

PUBLISHING exists to distribute evidence-bearing artifacts.

It does not reinterpret or alter the evidence.

---

### 4.2 Evidence anchoring

Published artifacts must reference the freeze tag and evidence window used to
produce them.

---

## 5. Outputs

PUBLISHING output **SHOULD** include:

- the manuscript
- the evidence window disclosure
- the publication artifact identifier (e.g., arXiv ID)

---

## 6. Time-to-publication

Each publication **MUST** report:

- freeze timestamp and commit
- publication timestamp and artifact identifier
- elapsed time between freeze and publication

---

## 7. Validation

A PUBLISHING scope is valid if and only if:

- the triad (`CANON.md`, `VOCAB.md`, `README.md`) is present
- published artifacts preserve evidence references
- no governance or enforcement is introduced

---

**This file is the PUBLISHING spec.**
**It carries no governance beyond CANON.**

---
