# Repository Structure

**Status:** Official

## Purpose

This document defines the current organization of the **Luma Lina** repository.

The structure keeps grammar, vocabulary, syntax, examples, writing conventions, and development notes separate and easy to maintain.

The repository structure is **not permanent**. It may change as Luma Lina develops and new documentation needs appear.

---

## Current Structure

```text
Luma-Lina/

│
├── README.md
├── LICENSE.md
├── repo-structure.md
│
├── grammar/
│   ├── 01-pronouns.md
│   ├── 02-pluralization.md
│   ├── 03-possession.md
│   ├── 04-copula.md
│   ├── 05-negation.md
│   ├── 06-questions.md
│   ├── 07-demonstratives.md
│   ├── 08-verbs.md
│   └── 09-word-order.md
│
├── vocabulary/
│   ├── vocabulary.md
│   └── core-words.md
│
├── syntax/
│   ├── sentence-structure.md
│   └── placeholder-convention.md
│
├── writing/
│   └── capitalization.md
│
├── examples/
│   └── example-sentences.md
│
└── development/
    ├── proposals.md
    ├── experiments.md
    └── rejected.md
```

---

## Root Files

### [`README.md`](README.md)

The main overview of the entire Luma Lina language.

It should summarize the established language system and link to the detailed documentation.

This file should be developed after the individual documentation becomes stable.

### [`LICENSE.md`](LICENSE.md)

Contains the official **Luma-Lina Language License 1.0 (LLL-1.0)**.

The license defines how Luma Lina and its project materials may be used, copied, modified, shared, and distributed. This includes the language rules, vocabulary, documentation, examples, and other materials included in the project.

It also defines the rights, permissions, conditions, and restrictions that apply to the project. `LICENSE.md` serves as the main legal reference for the Luma Lina repository.

### [`repo-structure.md`](repo-structure.md)

Describes the organization of the repository and the purpose of each directory and major file.

This document explains **where information belongs**, rather than defining the language itself.

---

## [`grammar/`](grammar/)

Contains the official grammatical rules of Luma Lina.

Each major grammatical system has its own document so that rules can be developed, reviewed, and updated independently.

### Files

* [`01-pronouns.md`](grammar/01-pronouns.md) — pronoun system
* [`02-pluralization.md`](grammar/02-pluralization.md) — plural marker and plural formation
* [`03-possession.md`](grammar/03-possession.md) — possession and relationship structure
* [`04-copula.md`](grammar/04-copula.md) — `la` and copular sentences
* [`05-negation.md`](grammar/05-negation.md) — `na` and negation
* [`06-questions.md`](grammar/06-questions.md) — yes/no and information questions
* [`07-demonstratives.md`](grammar/07-demonstratives.md) — demonstrative system
* [`08-verbs.md`](grammar/08-verbs.md) — verb structure
* [`09-word-order.md`](grammar/09-word-order.md) — basic sentence order and related ordering rules

Only accepted grammatical rules should be treated as **Official** in these documents.

---

## [`vocabulary/`](vocabulary/)

Contains the vocabulary of Luma Lina.

### [`vocabulary.md`](vocabulary/vocabulary.md)

The main vocabulary reference.

It should contain established words and their meanings.

### [`core-words.md`](vocabulary/core-words.md)

Contains important foundational vocabulary used frequently throughout the language.

This file may be useful for tracking the core vocabulary separately from the complete vocabulary.

---

## [`syntax/`](syntax/)

Contains rules about how words and grammatical structures are arranged.

### [`sentence-structure.md`](syntax/sentence-structure.md)

Documents general sentence construction, including the basic SVO structure and how established grammatical elements combine.

### [`placeholder-convention.md`](syntax/placeholder-convention.md)

Documents the use of square brackets for temporary words, names, and expressions that have not yet been officially established.

Example:

```text
Ei la [teacher].
```

The brackets indicate that `[teacher]` is a temporary placeholder, not official Luma Lina vocabulary.

---

## [`writing/`](writing/)

Contains rules related to the written representation of Luma Lina.

### [`capitalization.md`](writing/capitalization.md)

Documents capitalization rules and conventions.

Writing conventions should be kept separate from grammatical rules unless they directly affect grammar.

---

## [`examples/`](examples/)

Contains practical examples of Luma Lina sentences and structures.

### [`example-sentences.md`](examples/example-sentences.md)

A collection of tested examples demonstrating official grammar and vocabulary.

Examples should preferably use established rules rather than introducing undocumented grammar.

When an example requires a temporary word, the placeholder convention should be followed.

---

## [`development/`](development/)

Contains material related to the ongoing development of the language.

This directory separates unfinished ideas from official language rules.

### [`proposals.md`](development/proposals.md)

Contains proposed grammatical, vocabulary, or structural ideas that have **not yet been accepted**.

A proposal must not be treated as an official rule.

### [`experiments.md`](development/experiments.md)

Contains structures currently being tested.

Experimental structures may be used for testing clarity, simplicity, pronunciation, or compatibility with existing grammar.

They are not automatically official.

### [`rejected.md`](development/rejected.md)

Records ideas that were intentionally rejected.

Rejected ideas may be documented so that the same proposal does not need to be reconsidered without knowing why it was previously discarded.

---

## Rule Status

Documentation should clearly distinguish between four statuses:

* **Official** — accepted and currently part of Luma Lina.
* **Proposed** — suggested but not accepted.
* **Experimental** — currently being tested.
* **Rejected** — intentionally discarded.

A proposed or experimental structure must not silently become an official rule through repeated use.

Official status requires explicit acceptance.

---

## Structure Changes

The repository structure may change as Luma Lina develops.

Directories or files may be:

* added when new documentation needs appear
* renamed when clearer organization is needed
* divided when a document becomes too large
* combined when separate documents are no longer useful
* removed when their purpose is no longer needed

Changes to the repository structure should preserve clear organization and avoid unnecessary complexity.

The goal is not to create a large number of files.

The goal is to make Luma Lina easy to understand, maintain, expand, and eventually use as a structured grammar, vocabulary, corpus, or computational resource.
