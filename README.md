# Luma Lina

**Luma Lina** is an original constructed language designed to be **simple, consistent, predictable, useful, and expandable**.

The project aims to create a language that is easy to learn and use while remaining expressive enough for normal communication. Its grammar favors regular, compositional structures instead of unnecessary exceptions, irregular forms, and complicated word changes.

The language is being developed step by step. Existing systems are tested through practical sentences before new complexity is introduced.

---

# Name

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

Plural pronouns are formed by using the existing plural marker `di`:

```text
Ei di
Ao di
Sa di
Nu di
```

**we / us**

**you all**

**they**

**they / those things**

**File:** [grammar/01-pronouns.md](grammar/01-pronouns.md)

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

The same marker is reused with different types of words.

Examples:

```text
Ei di

Ao di

maimai di
```

**we / us**

**you all**

**goats**

This is an important part of the compositional design of Luma Lina. Plurality does not require separate plural forms for different grammatical categories.

**File:** [grammar/02-pluralization.md](grammar/02-pluralization.md)

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

The system uses one reusable relationship marker rather than separate possessive forms for different pronouns.

**File:** [grammar/03-possession.md](grammar/03-possession.md)

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

The placeholder is therefore not part of the official vocabulary.

**File:** [grammar/04-copula.md](grammar/04-copula.md)

---

## Negation

`na` is the general negation marker.

It appears before the predicate.

Example:

```text
Ei na yum buff.
```

**I do not eat meat.**

`na` is also the official negative answer to a yes/no question.

For example:

```text
Ao yum buff ma?

Na.
```

**Do you eat meat?**

**No.**

The same marker therefore handles both general negation and negative Boolean answers.

**File:** [grammar/05-negation.md](grammar/05-negation.md)

---

# Questions

Luma Lina currently has two main question systems.

## Yes/No Questions

`ma` marks a yes/no question.

```text
Ao yum buff ma?
```

**Do you eat meat?**

The basic sentence structure remains intact, with `ma` added as the question marker.

## Information Questions

`Sao` replaces the missing information in an information question.

```text
Ei yum Sao?
```

**What do I eat?**

The question structure keeps the missing information in the position where the answer would normally occur.

For example:

```text
Sao yum buff?
```

**Who eats meat?**

Here, `Sao` occupies the subject position because the unknown information is the subject.

## Boolean Answers

Luma Lina uses:

* `yah` = yes
* `na` = no

Both are **Official**.

`yah` is the positive Boolean answer.

`na` is the negative Boolean answer and also functions as the general negation marker.

**File:** [grammar/06-questions.md](grammar/06-questions.md)

---

# Demonstratives

Luma Lina uses two basic demonstratives:

* `ti` = this, near
* `ta` = that, distant

## Demonstrative Structure

The demonstrative directly modifies the noun.

The noun carries the plural marker `di` when it is plural.

The structure is:

```text
Demonstrative + Noun

Demonstrative + Noun + di
```

Examples:

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

This follows the general principle that `di` comes after the word it pluralizes.

The demonstrative does not take the plural marker directly in a demonstrative+noun phrase. Instead, the noun is pluralized.

## Copular Examples

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

## Possessive Examples

```text
ta maimai la Ei de maimai.

ta maimai di la Ei di de maimai di.
```

**That goat is my goat.**

**Those goats are our goats.**

## Questions

```text
ta la maimai ma?

ta la maimai di ma?
```

**Is that a goat?**

**Are those goats?**

## Negation

```text
ta na la maimai.

ta na la maimai di.
```

**That is not a goat.**

**Those are not goats.**

### Rule Status

This demonstrative system is **Official**.

It supersedes the earlier structure:

```text
ti di maimai di

ta di maimai di
```

The earlier structure is no longer the current demonstrative+noun construction.

**File:** [grammar/07-demonstratives.md](grammar/07-demonstratives.md)

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

This means that changes in the subject do not require changes to the verb.

Tense and aspect systems may be developed separately as the language grows.

**File:** [grammar/08-verbs.md](grammar/08-verbs.md)

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

Word order is kept as regular as possible so that individual grammatical systems can be combined without creating unnecessary sentence patterns.

**File:** [grammar/09-word-order.md](grammar/09-word-order.md)

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

The capitalization rules are documented separately so that written Luma Lina remains consistent across examples, documentation, and future language resources.

**File:** [writing/capitalization.md](writing/capitalization.md)

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

All words listed above are currently **Official**.

**Complete vocabulary:** [vocabulary/vocabulary.md](vocabulary/vocabulary.md)

**Core vocabulary:** [vocabulary/core-words.md](vocabulary/core-words.md)

The vocabulary system is intended to remain practical and expandable. New words should be easy to pronounce, easy to remember, distinct from existing words, and compatible with the developing sound system.

---

# Syntax

The syntax documentation explains how individual grammatical systems work together.

## Sentence Structure

[syntax/sentence-structure.md](syntax/sentence-structure.md) documents sentence construction and the combination of grammatical elements.

## Placeholder Convention

[syntax/placeholder-convention.md](syntax/placeholder-convention.md) explains how English words and other temporary labels are represented when a Luma Lina word has not yet been established.

For example:

```text
Ei la [teacher].
```

Here, `[teacher]` is explicitly a placeholder and is **not** part of the Luma Lina vocabulary.

---

# Examples

Actual language examples are collected in:

[examples/example-sentences.md](examples/example-sentences.md)

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

This distinction is important because the language is developed through testing. An example can demonstrate how a structure works without independently creating a new grammatical rule.

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

## Development Files

* [development/proposals.md](development/proposals.md)
* [development/experiments.md](development/experiments.md)
* [development/rejected.md](development/rejected.md)

These files document development history. They do not override the Official grammar.

---

# Repository Structure

````text
```text
LumaLina/
├── README.md
├── LICENSE.md
├── repo-structure.md
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
├── vocabulary/
│   ├── vocabulary.md
│   └── core-words.md
├── syntax/
│   ├── sentence-structure.md
│   └── placeholder-convention.md
├── writing/
│   └── capitalization.md
├── examples/
│   └── example-sentences.md
└── development/
    ├── proposals.md
    ├── experiments.md
    └── rejected.md
```

Detailed repository structure: repo-structure.md
````

**License:** [LICENSE.md](LICENSE.md)

The repository is divided by function so that grammar, vocabulary, syntax, writing conventions, examples, and development history can be maintained separately.

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

The same principle applies to possession, negation, questions, demonstratives, and other grammatical functions.

The purpose is not to eliminate every distinction. The purpose is to make each distinction earn its place in the language.

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

The current Official systems provide the foundation for further development.

Practical sentence testing remains an important part of development. Before adding new grammatical complexity, existing structures should be used across multiple ordinary sentences to identify limitations or contradictions.

The current development priority is to **use and test the existing system before adding unnecessary complexity**.

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

New systems should also remain compatible with the existing grammar whenever possible.

---

# Guiding Principle

> **Simple. Consistent. Compositional. Predictable. Original. Useful. Expandable.**

Luma Lina is intended to grow into a complete, organized language with a clear grammar, vocabulary, syntax, examples, documentation, and eventually a substantial corpus suitable for both human learners and computational applications.
