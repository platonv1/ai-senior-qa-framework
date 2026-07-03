
# AI QA Bootstrap Instructions

## Purpose

This document explains how to initialize and maintain the AI QA documentation framework.

---

## Startup Procedure

When beginning work in a new repository:

1. Read CLAUDE.md.
2. Read MANIFEST.md.
3. Inspect the repository structure.
4. Compare the repository against MANIFEST.md.
5. Identify missing documentation.
6. Report missing files.
7. Wait for approval before creating new files, unless explicitly instructed to create them automatically.

---

## Documentation Generation

When instructed to generate documentation:

- Create one logical group of files at a time (for example, all context files or all prompt files).
- Produce complete, production-ready Markdown content.
- Follow the behavior defined in CLAUDE.md.
- Follow the structure defined in MANIFEST.md.
- Reuse existing documentation where possible instead of duplicating information.

---

## Updating Existing Files

When updating a file:

- Preserve valuable existing content.
- Improve clarity and organization.
- Avoid unnecessary rewrites.
- Explain significant changes in your response.

---

## Context Refresh

At the start of a new session:

1. Review CLAUDE.md.
2. Review relevant context files.
3. Review previous QA outputs if they exist.
4. Confirm your understanding before continuing.

---

## Quality Gates

Before considering documentation complete:

- All required files exist or are intentionally omitted.
- Cross-references are consistent.
- Markdown formatting is valid.
- Content is technically accurate.
- Instructions are actionable and reusable.

If a quality gate is not met, identify the gap and recommend the next step.


SESSION.md Maintenance Policy
SESSION.md is the authoritative record of the project's current QA state.
Claude is responsible for maintaining this file throughout the QA lifecycle.
Before Starting Any Task
Before beginning a QA task, Claude must:
1.	Read SESSION.md.
2.	Determine the current QA phase.
3.	Review completed activities, open issues, blockers, and pending tasks.
4.	Continue from the appropriate point in the workflow without repeating completed work.
After Completing Any Significant Task
After completing a significant QA activity, Claude must update SESSION.md.
Examples of significant activities include:
•	Repository analysis
•	Architecture review
•	Test strategy creation
•	Existing test review
•	Unit test generation
•	Functional testing
•	Integration testing
•	End-to-end testing
•	Security testing
•	Performance testing
•	Accessibility testing
•	Bug investigation
•	Root cause analysis
•	Fix verification
•	Regression testing
•	QA report generation
Update Requirements
Only update sections that have changed.
Do not overwrite the entire file.
Update, where applicable:
•	Current QA Phase
•	Current Objective
•	Overall Progress
•	Completed Activities
•	Current Findings
•	Open Issues
•	Risks
•	Test Coverage Summary
•	QA Metrics
•	Pending Tasks
•	Recommended Next Prompt
•	Session Summary
•	Handoff Notes
•	Last Updated
All updates must be based on verified results from the current repository or QA activity.
Do not fabricate test results, coverage metrics, or project progress.
