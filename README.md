<div align="center">

# Research GPT Skills
<p>

<img src="https://img.shields.io/badge/status-active_development-2ea44f" />
<img src="https://img.shields.io/badge/license-MIT-blue" />
<img src="https://img.shields.io/badge/architecture-modular-orange" />
<img src="https://img.shields.io/badge/focus-engineering_%26_research-6f42c1" />

</p>

<p><em>A growing collection of professional ChatGPT Skills for engineering, scientific research, and publication.</em></p>

</div>

---

## Why this exists

Most AI writing tools solve the wrong problem.

They rewrite everything.

They replace words mechanically.

They optimize for AI detectors instead of good writing.

That approach works until it encounters a technical paper, a petroleum engineering report, or a machine learning manuscript. Then things begin to break.

This project takes a different path.

Every skill is designed around one idea:

> **Make decisions in context—not from a replacement table.**

---

## The approach

Each skill performs **one job exceptionally well**.

Instead of building one enormous prompt that tries to do everything, this repository is organized into independent, reusable modules.

```text
Research GPT
    ├── Academic Humanizer
    ├── Publication Editor
    ├── Citation Manager
    ├── Literature Reviewer
    ├── ...
```

Skills can be used individually or combined into larger research workflows.

---

## Context beats replacement

Consider the word:

```text
leverage
```

A traditional humanizer might always replace it with `use`.

That creates problems.

```text
Use financial
```

```text
Use scores
```

```text
Use advantage
```

None of those make sense.

Instead, this project asks:

> **What does the word mean here?**

If it's a generic verb, it may be revised.

If it's part of a technical concept like `financial leverage`, `leverage scores`, or `mechanical leverage`, it stays exactly as it is.

The same principle applies across the entire project.

---

## Design philosophy

Every skill follows the same principles.

* Preserve scientific meaning.
* Preserve technical terminology.
* Preserve citations.
* Preserve equations, variables, units, and numerical values.
* Edit only what needs editing.
* Verify before returning the result.

The objective isn't to rewrite more.

It's to rewrite better.

---

## What makes these skills different?

Instead of embedding thousands of replacement rules inside prompts, each skill separates **logic** from **knowledge**.

```text
SKILL.md
        │
        ├── decision logic
        ├── workflow
        ├── verification
        │
        ▼
references/
        └── ai_lexicon.md
```

The skill decides **how** to edit.

The lexicon provides **what** to evaluate.

That separation keeps the project modular, maintainable, and easy to expand.

---

## Current focus

This repository is being built around engineering and scientific research.

Current and planned domains include:

* Petroleum Engineering
* Reservoir Engineering
* Production Engineering
* Intelligent Well Engineering
* Geothermal Engineering
* Machine Learning
* Data Science
* Scientific Computing
* Research Methodology
* Academic Publishing

---

## Repository structure

```text
.
├── skills/
│   ├── academic-humanizer/
│   ├── publication-editor/
│   ├── citation-manager/
│   ├── literature-review/
│   └── ...
└── README.md
```

---

## Current status

The project is in active development.

Every skill follows the same lifecycle:

```text
Research
    ↓
Design
    ↓
Implementation
    ↓
Testing
    ↓
Iteration
```

Nothing is added simply because it "sounds good."

Every rule should exist for a reason.

---

## Roadmap

### Core

* [x] Academic Humanizer *(v0.1)*
* [ ] Publication Editor
* [ ] Citation Manager
* [ ] Literature Reviewer
* [ ] Consistency Checker

### Engineering

* [ ] Petroleum Engineering
* [ ] Reservoir Engineering
* [ ] Production Engineering
* [ ] Intelligent Well Engineering
* [ ] Flow Assurance

### AI & Data

* [ ] Machine Learning
* [ ] Data Science
* [ ] Scientific Python
* [ ] Statistics

---

## Contributing

If you'd like to contribute, start by asking a simple question:

> **Does this improve the decision-making ability of the skill, or does it just add another rule?**

Preference is given to contributions that improve:

* Context awareness
* Technical accuracy
* Verification
* Maintainability
* Test coverage

---

## License

Released under the **MIT License**.
