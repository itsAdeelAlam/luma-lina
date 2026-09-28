# Luma Lina

**Luma Lina** is an original constructed language designed to be **simple, consistent, predictable, useful, and expandable**.

The project aims to create a language that is easy to learn and use while remaining expressive enough for normal communication. Its grammar favors regular, compositional structures instead of unnecessary exceptions, irregular forms, and complicated word changes.

---

## Name

The name **Luma Lina** is formed from two Luma Lina words:

* `luma` = beautiful
* `lina` = language

Therefore:

> **Luma Lina = Beautiful Language**

The name reflects the project's goal of creating a language that is simple, clear, consistent, and pleasant to use.

---

# Project Goals

Luma Lina is built around the following principles:

* **Simple** — grammar should be easy to understand.
* **Consistent** — the same rules should work across different situations.
* **Predictable** — speakers should not need to memorize many exceptions.
* **Compositional** — existing grammatical markers should be reused to express related meanings.
* **Original** — the language should develop its own vocabulary and grammatical identity.
* **Useful** — the language should support practical communication.
* **Expandable** — new grammar and vocabulary should be possible without unnecessarily breaking existing systems.

The goal is **not** to make the language as small as possible.

The goal is to create the **simplest system that remains clear, expressive, natural, and expandable**.

---

# Core Grammar

## Word Order

Luma Lina uses **SVO (Subject–Verb–Object)** as its basic word order.

Example:

```text
Ei yum buff.
```

**I eat meat.**

The language does not use grammatical gender.

Verbs do not change according to the person, number, or gender of the subject. Grammatical information is normally expressed through separate particles.

For example:

```text
Ei yum buff.
Ei di yum buff.
```

**I eat meat.**
**We eat meat.**

The verb `yum` remains unchanged.

---

## Pronouns

Luma Lina uses simple personal pronouns:

| Word | Meaning  |
| ---- | -------- |
| `Ei` | I / me   |
| `Ao` | you      |
| `Sa` | he / she |
| `Nu` | it       |

There is no grammatical gender distinction.

**File:** [grammar/01-pronouns.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/grammar/01-pronouns.md?utm_source=chatgpt.com)

---

## Pluralization

`di` is the plural marker.

It follows the word it pluralizes.

```text
maimai
maimai di
```

**goat**
**goats**

The same marker can be reused with different types of words.

Examples:

```text
Ei di
Ao di
maimai di
```

**we / us**
**you all**
**goats**

**File:** [grammar/02-pluralization.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/grammar/02-pluralization.md?utm_source=chatgpt.com)

---

## Possession and Relationships

`de` expresses possession or a relationship between two words.

The basic structure is:

```text
Possessor + de + Related Word
```

Examples:

```text
Ei de maimai
Ei di de maimai di
Ao de maimai
Sa de maimai
```

**my goat**
**our goats**
**your goat**
**his/her goat**

The same structure can be used for other relationships when appropriate.

**File:** [grammar/03-possession.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/grammar/03-possession.md?utm_source=chatgpt.com)

---

## Copula

`la` expresses **be / am / is / are**.

It does not change according to the subject.

The basic structure is:

```text
Subject + la + Complement
```

Example:

```text
Ei la [teacher].
```

**I am a teacher.**

Here, `[teacher]` is a placeholder because the Luma Lina word for this concept has not been established.

**File:** [grammar/04-copula.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/grammar/04-copula.md?utm_source=chatgpt.com)

---

## Negation

`na` is the general negation marker.

It appears before the predicate.

Example:

```text
Ei na yum buff.
```

**I do not eat meat.**

`na` can also be used as a negative response to a yes/no question.

**File:** [grammar/05-negation.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/grammar/05-negation.md?utm_source=chatgpt.com)

---

## Questions

Luma Lina currently has two main question systems.

### Yes/No Questions

`ma` marks a yes/no question.

```text
Ao yum buff ma?
```

**Do you eat meat?**

### Information Questions

`Sao` replaces the missing information in an information question.

```text
Ei yum Sao?
```

**What do I eat?**

The question structure keeps the missing information in the position where the answer would normally occur.

### Boolean Answers

The current vocabulary includes:

* `yah` = yes
* `na` = no

The status of `yah` is **Proposed**, not Official, until explicitly accepted.

**File:** [grammar/06-questions.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/grammar/06-questions.md?utm_source=chatgpt.com)

---

# Demonstratives

Luma Lina uses two basic demonstratives:

* `ti` = this, near
* `ta` = that, distant

## Proposed Plural Structure

The current **Proposed** system places the demonstrative directly before the noun. The noun carries the plural marker `di`.

```text
ti maimai
ti maimai di

ta maimai
ta maimai di
```

**this goat**
**these goats**

**that goat**
**those goats**

The structure is:

```text
Demonstrative + Noun
Demonstrative + Noun + di
```

Examples with the copula:

```text
ti la maimai.
ti la maimai di.

ta la maimai.
ta la maimai di.
```

**This is a goat.**
**These are goats.**

**That is a goat.**
**Those are goats.**

This follows the general principle that `di` comes after the word it pluralizes.

### Rule Status

This demonstrative structure is currently **Proposed**.

It replaces the earlier structure:

```text
ti di maimai di
ta di maimai di
```

but it should not be treated as an Official rule until explicitly accepted.

**File:** [grammar/07-demonstratives.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/grammar/07-demonstratives.md?utm_source=chatgpt.com)

---

## Verbs

Verbs do not conjugate for person, number, or gender.

The current established verb `yum` means **eat**.

```text
Ei yum buff.
Sa yum buff.
Ei di yum buff.
```

**I eat meat.**
**He/she eats meat.**
**We eat meat.**

The verb remains `yum` in every case.

Tense and aspect systems may be developed separately as the language grows.

**File:** [grammar/08-verbs.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/grammar/08-verbs.md?utm_source=chatgpt.com)

---

## Word Order

The default sentence structure is **SVO**.

The grammar documentation also explains how word order interacts with:

* negation;
* questions;
* possession;
* pluralization;
* demonstratives;
* the copula;
* other grammatical structures.

**File:** [grammar/09-word-order.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/grammar/09-word-order.md?utm_source=chatgpt.com)

---

# Writing System

Luma Lina currently uses a capitalization system for its Latin-script documentation.

Personal pronouns are normally capitalized:

```text
Ei
Ao
Sa
Nu
```

Grammatical markers are normally lowercase:

```text
di
de
la
na
ma
```

Common vocabulary is also normally lowercase.

The language name is written:

```text
Luma Lina
```

**File:** [writing/capitalization.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/writing/capitalization.md?utm_source=chatgpt.com)

---

# Vocabulary

The current vocabulary is intentionally small while the grammatical foundation is being developed.

| Word     | Meaning                          |
| -------- | -------------------------------- |
| `Ei`     | I / me                           |
| `Ao`     | you                              |
| `Sa`     | he / she                         |
| `Nu`     | it                               |
| `di`     | plural marker                    |
| `de`     | possession / relationship        |
| `la`     | be / am / is / are               |
| `na`     | negation / no                    |
| `ma`     | yes/no question marker           |
| `Sao`    | information-question placeholder |
| `yah`    | yes                              |
| `ti`     | this                             |
| `ta`     | that                             |
| `yum`    | eat                              |
| `maimai` | goat                             |
| `buff`   | meat / mutton / chicken meat     |
| `luma`   | beautiful                        |
| `lina`   | language                         |

`yah` is currently **Proposed**.

**Complete vocabulary:** [vocabulary/vocabulary.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/vocabulary/vocabulary.md?utm_source=chatgpt.com)

**Core vocabulary:** [vocabulary/core-words.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/vocabulary/core-words.md?utm_source=chatgpt.com)

---

# Syntax

The syntax documentation explains how individual grammatical systems work together.

### Sentence Structure

`syntax/sentence-structure.md` documents sentence construction and the combination of grammatical elements.

**File:** [syntax/sentence-structure.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/syntax/sentence-structure.md?utm_source=chatgpt.com)

### Placeholder Convention

`syntax/placeholder-convention.md` explains how English words and other temporary labels are represented when a Luma Lina word has not yet been established.

For example:

```text
Ei la [teacher].
```

Here, `[teacher]` is explicitly a placeholder and is **not** part of the Luma Lina vocabulary.

**File:** [syntax/placeholder-convention.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/syntax/placeholder-convention.md?utm_source=chatgpt.com)

---

# Examples

Actual language examples are collected in:

**File:** [examples/example-sentences.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/examples/example-sentences.md?utm_source=chatgpt.com)

The examples demonstrate the current grammar, including:

* basic sentences;
* plural sentences;
* copular sentences;
* negation;
* possession;
* demonstratives;
* yes/no questions;
* information questions;
* Boolean answers;
* combinations of existing grammatical systems.

Examples demonstrate how the language works, but **an example does not automatically create a new grammatical rule**.

---

# Development Status

Luma Lina uses four rule-status categories.

## Official

An accepted part of the language.

Official grammar and vocabulary represent the current standard.

## Proposed

An idea that has been suggested but has not yet been accepted.

A Proposed feature does not change the Official language.

## Experimental

A feature that is actively being tested.

An Experimental feature may be changed, replaced, or removed after testing.

## Rejected

An idea that was considered and intentionally discarded.

Rejected ideas are recorded so that previously explored solutions do not need to be rediscovered.

### Development Files

* [development/proposals.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/development/proposals.md?utm_source=chatgpt.com)
* [development/experiments.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/development/experiments.md?utm_source=chatgpt.com)
* [development/rejected.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/development/rejected.md?utm_source=chatgpt.com)

These files document development history. They do not override the Official grammar.

---

# Repository Structure

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

**Detailed repository structure:** [repo-structure.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/repo-structure.md?utm_source=chatgpt.com)

**License:** [LICENSE.md](https://github.com/itsAdeelAlam/Luma-Lina/blob/main/LICENSE.md?utm_source=chatgpt.com)

---

# Design Philosophy

Luma Lina is developed by solving problems with the smallest workable grammatical system.

When a new grammatical problem appears, the preferred process is:

1. **Identify the problem.**
2. **Check whether existing grammar can solve it.**
3. **Try the simplest workable solution.**
4. **Test the solution with several sentences.**
5. **Check compatibility with existing rules.**
6. **Look for unnecessary exceptions or complexity.**
7. **Accept the feature only after deliberate review.**

This process helps prevent the language from accumulating rules simply because they seem useful in isolation.

Existing grammatical markers should be reused whenever possible.

For example, if `di` already expresses plurality, the preferred approach is to reuse `di` rather than create another plural system for a new grammatical category.

---

# Current Stage

Luma Lina is an actively developing language.

Its basic grammatical foundation currently includes:

* pronouns;
* pluralization;
* possession and relationships;
* copula;
* negation;
* questions;
* demonstratives;
* basic verb structure;
* word order;
* capitalization;
* core vocabulary.

Some systems are still being tested and refined. In particular, Proposed features must remain clearly separated from Official grammar.

The current development priority is to **use and test the existing system before adding unnecessary complexity**.

Practical sentence testing is an important part of development. A rule should work across multiple ordinary sentences before becoming part of the Official language.

---

# Future Development

As the language grows, the project may develop:

* additional vocabulary;
* tense and aspect systems;
* additional syntax;
* expanded writing systems;
* dictionaries;
* educational materials;
* example corpora;
* machine-readable language resources;
* computational tools;
* language-learning tools;
* resources for linguistic and computational research.

Future additions should follow the same principles of simplicity, consistency, compositionality, and deliberate testing.

---

# Guiding Principle

> **Simple. Consistent. Compositional. Predictable. Original. Useful. Expandable.**

Luma Lina is intended to grow into a complete, organized language with a clear grammar, vocabulary, syntax, examples, documentation, and eventually a substantial corpus suitable for both human learners and computational applications.
