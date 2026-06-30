# AGENTS.md

# AI Learning Repository Agent Instructions

## Purpose

This repository is the long-term knowledge base for an AI learning journey.

Its goals are to:

* document learning progress
* maintain a structured AI knowledge base
* connect concepts across the AI ecosystem
* record historical learning decisions
* minimize repeated work
* remain easy for both humans and AI agents to understand

Agents should treat this repository as a living knowledge system rather than a collection of isolated notes.

---

# Repository Philosophy

The repository should prioritize:

1. clarity over completeness
2. evolution over replacement
3. linked knowledge over duplicated knowledge
4. incremental improvements over large rewrites
5. preserving learning history

Every change should make the repository easier to understand.

---

# Top-Level Structure

The exact folders may evolve over time, but the intended responsibilities are:

## roadmap.md

The authoritative learning roadmap.

It describes:

* current learning priorities
* future topics
* learning sequence
* planned milestones

Agents should update this document when priorities change.

Do not turn it into a journal.

---

## learning-log/

Historical journal.

This directory records:

* completed learning sessions
* summaries
* reflections
* lessons learned
* significant milestones

Entries should be appended.

Do not rewrite previous history unless explicitly requested.

---

## profile/

Contains learning preferences and long-term learner profile.

Examples:

* experience
* strengths
* interests
* preferred teaching style
* constraints

This directory represents stable information rather than daily progress.

---

## glossary/

Definitions of important concepts.

Each concept should have a single authoritative definition.

Avoid duplicate explanations.

---

## courses/

Notes taken from books, courses, papers, videos, or tutorials.

Each course should have its own directory or document.

Summaries should reference glossary terms whenever possible.

---

## patterns/

Reusable AI engineering patterns.

Examples include:

* prompting patterns
* agent architectures
* RAG patterns
* evaluation strategies
* orchestration approaches

These should focus on reusable knowledge rather than chronological notes.

---

## agent-os/

Knowledge related to Agent OS and agent engineering.

Include:

* architecture
* workflows
* implementation notes
* experiments
* design ideas

---

## projects/

(Optional)

Implementation work, prototypes, experiments, and practical applications.

Learning notes belong elsewhere.

---

# Update Strategy

When modifying the repository:

## Prefer updating existing documents

Before creating a new file:

1. search for an existing relevant document
2. extend it if appropriate
3. only create a new document when the topic is genuinely distinct

Avoid fragmented knowledge.

---

## Preserve existing content

Unless explicitly instructed:

* do not delete sections
* do not replace historical notes
* do not rewrite completed learning logs
* do not remove context that may remain useful

Prefer improving structure while preserving information.

---

## Append rather than overwrite

For notes, journals, and learning history:

* append new entries
* preserve chronology
* retain previous observations

Historical context has value.

---

## Refactoring

Only perform structural refactoring when explicitly requested.

Examples include:

* splitting oversized documents
* reorganizing directories
* merging duplicate files
* renaming files

Do not refactor simply because a different structure seems preferable.

---

# Writing Style

Documents should be:

* concise
* factual
* organized
* easy to scan

Prefer:

* headings
* short paragraphs
* bullet lists
* tables where appropriate

Avoid unnecessary verbosity.

---

# Markdown Conventions

Use consistent Markdown.

## Headings

Use:

```text
# Title

## Section

### Subsection
```

Avoid skipping heading levels.

---

## Lists

Use unordered lists unless order matters.

---

## Code

Use fenced code blocks with language identifiers.

Example:

````markdown
```python
print("hello")
```
````

---

## Emphasis

Use:

* **bold** for important concepts
* `inline code` for filenames, commands, classes, and APIs

Avoid excessive formatting.

---

# Cross-Linking

Whenever useful, connect related documents.

Prefer relative Markdown links.

Example:

```markdown
See [roadmap.md](../roadmap.md)

See [Prompt Engineering](../glossary/prompt-engineering.md)
```

Related concepts should reference one another rather than duplicate explanations.

---

# File Naming

Prefer lowercase names.

Use kebab-case.

Examples:

* prompt-engineering.md
* llm-evaluation.md
* agent-memory.md

Avoid:

* spaces
* inconsistent capitalization
* vague names like notes.md or misc.md

---

# Knowledge Organization

Each concept should have a single primary home.

Other documents should link to it.

Avoid maintaining multiple competing definitions.

---

# Consistency

When updating documentation:

* keep terminology consistent
* use existing vocabulary
* follow established directory conventions
* avoid introducing alternative names for the same concept

---

# Learning Roadmap Rules

`roadmap.md` is the authoritative source for planned learning.

Agents may:

* update progress
* reorder future topics
* add milestones
* adjust priorities

Agents should not use it as a journal.

Historical learning belongs in `learning-log/`.

---

# Learning Log Rules

The `learning-log/` directory is append-only by default.

Each entry should capture:

* date
* topic
* summary
* key insights
* next steps (if applicable)

Previous entries should remain intact.

---

# Duplicate Prevention

Before creating new content:

* search the repository
* identify similar documents
* update an existing file whenever reasonable
* create new files only for genuinely new subjects

The repository should evolve toward fewer, richer documents rather than many overlapping ones.

---

# Agent Behavior

When working in this repository, agents should:

1. understand the current repository structure before making changes
2. preserve historical knowledge
3. prefer incremental improvements
4. maintain internal consistency
5. improve navigation
6. keep links valid
7. avoid unnecessary file creation
8. append new learning rather than replacing old learning
9. treat `roadmap.md` as the learning plan
10. treat `learning-log/` as the historical record

The repository should become progressively more coherent over time without losing its history.
