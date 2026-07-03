# AUTHOR: Vic Saisan Platon


# 🤖 AI Senior QA Framework

> A production-ready, AI-powered Quality Assurance framework for Claude Code and other AI coding assistants that standardizes repository analysis, test strategy, automated testing, bug investigation, documentation, and QA reporting.

## Overview

The AI Senior QA Framework provides a structured workflow that enables AI assistants to perform quality assurance like an experienced Senior QA Engineer.

Instead of relying on one-off prompts, this framework separates:

* **Persistent project instructions**
* **QA methodology**
* **Project context**
* **Current project state**
* **Reusable prompts**
* **Documentation templates**
* **Generated QA artifacts**

The result is a reusable framework that maintains consistency across projects while allowing AI to resume work across multiple sessions.

---

# Goals

* Standardize AI-assisted QA workflows
* Improve repository understanding before testing
* Separate permanent instructions from project state
* Generate consistent documentation
* Reduce prompt duplication
* Maintain context across multiple AI sessions
* Support long-running QA projects
* Produce production-ready QA reports

---

# Core Concepts

The framework separates responsibilities into dedicated documents.

| File           | Purpose                                                                         |
| -------------- | ------------------------------------------------------------------------------- |
| `CLAUDE.md`    | Defines how the AI should behave throughout the project.                        |
| `PLAYBOOK.md`  | Defines the QA methodology, lifecycle, quality gates, and testing standards.    |
| `BOOTSTRAP.md` | Defines how each AI session is initialized and how the framework is maintained. |
| `MANIFEST.md`  | Lists the expected documentation, prompts, templates, and project structure.    |
| `SESSION.md`   | Maintains the current QA state so work can resume across sessions.              |

---

# Repository Structure

```text
.claude/
│
├── core/
│   ├── CLAUDE.md
│   ├── PLAYBOOK.md
│   ├── BOOTSTRAP.md
│   ├── MANIFEST.md
│   └── SESSION.md
│
├── context/
│   ├── project-overview.md
│   ├── architecture.md
│   ├── tech-stack.md
│   ├── business-rules.md
│   ├── coding-standards.md
│   └── testing-standards.md
│
├── prompts/
│
├── workflow/
│
├── templates/
│
├── standards/
│
├── outputs/
│   ├── analysis/
│   ├── reports/
│   └── generated-tests/
│
└── checklists/
```

---

# QA Lifecycle

```text
Initialize Framework
        │
        ▼
Repository Analysis
        │
        ▼
Architecture Review
        │
        ▼
Risk Assessment
        │
        ▼
Test Strategy
        │
        ▼
Review Existing Tests
        │
        ▼
Generate Tests
        │
        ▼
Execute Tests
        │
        ▼
Bug Investigation
        │
        ▼
Root Cause Analysis
        │
        ▼
Fix Verification
        │
        ▼
Regression Testing
        │
        ▼
Release Readiness
        │
        ▼
QA Report
        │
        ▼
Update SESSION.md
```

---

# Framework Workflow

Every new AI session follows the same initialization process.

```text
Start QA Project
        │
        ▼
Read CLAUDE.md
        │
        ▼
Read MANIFEST.md
        │
        ▼
Read PLAYBOOK.md
        │
        ▼
Read BOOTSTRAP.md
        │
        ▼
Read SESSION.md
        │
        ▼
Load Project Context
        │
        ▼
Review Repository
        │
        ▼
Proceed with Current QA Phase
        │
        ▼
Update SESSION.md
```

---

# Supported QA Activities

The framework supports:

* Repository Analysis
* Architecture Review
* Risk Assessment
* Test Strategy
* Existing Test Review
* Unit Testing
* Functional Testing
* Integration Testing
* End-to-End Testing
* Regression Testing
* Security Testing
* Performance Testing
* Accessibility Testing
* Exploratory Testing
* Bug Investigation
* Root Cause Analysis
* Fix Verification
* Release Readiness Assessment
* QA Report Generation

---

# Documentation Philosophy

The framework follows a strict separation of responsibilities.

* **Persistent instructions** belong in `CLAUDE.md`.
* **QA methodology** belongs in `PLAYBOOK.md`.
* **Framework initialization** belongs in `BOOTSTRAP.md`.
* **Project documentation** belongs in the `context/` directory.
* **Current progress** belongs in `SESSION.md`.
* **Reusable prompts** belong in `prompts/`.
* **Generated artifacts** belong in `outputs/`.

This separation keeps documentation maintainable and reusable across projects.

---

# Typical Workflow

1. Initialize the framework.
2. Analyze the repository.
3. Generate or update project context documentation.
4. Create a QA strategy.
5. Review existing tests.
6. Generate missing tests.
7. Execute QA activities.
8. Investigate defects.
9. Verify fixes.
10. Perform regression testing.
11. Generate QA reports.
12. Update `SESSION.md`.

---

# AI Session Continuity

The framework is designed for long-running projects.

At the beginning of every session, the AI:

1. Loads the framework documentation.
2. Reads the current project state.
3. Determines the active QA phase.
4. Continues from where the previous session ended.

This minimizes repeated prompts and preserves project context.

---

# Guiding Principles

* Understand before testing.
* Evidence over assumptions.
* Prioritize risk-based testing.
* Reuse existing project standards.
* Generate maintainable tests.
* Preserve project documentation.
* Never fabricate findings or metrics.
* Keep `SESSION.md` synchronized with project progress.
* Produce actionable, stakeholder-friendly reports.

---

# Who Is This For?

This framework is intended for:

* QA Engineers
* Software Test Engineers
* SDETs
* Engineering Teams
* AI-assisted development workflows
* Claude Code users
* Teams building repeatable AI QA processes

---

# Contributing

Contributions are welcome.

Suggested improvements include:

* Additional prompt libraries
* Testing standards
* QA templates
* Framework enhancements
* CI/CD integrations
* Support for additional AI coding assistants

Please open an issue or submit a pull request with a clear description of the proposed enhancement.

---

# License

This project is released under the license included in this repository.

---

## Vision

Build a reusable AI-powered QA operating framework that enables AI coding assistants to perform software quality assurance consistently, transparently, and efficiently across projects of any size.
