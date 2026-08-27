---
name: weekly-report
description: Turn multiple meeting notes and weekly updates into one concise weekly report with consistent sections, clear language, and no invented information.
---

# Weekly Report

## Purpose

Create one concise weekly report from multiple meeting notes, updates, and progress information.

## Input

The input may contain:

* Meeting notes
* Progress updates
* Completed tasks
* In-progress tasks
* Blockers
* Decisions
* Numbers or metrics

Information may come from several meetings or people during the same week.

## Instructions

1. Read all provided notes and updates before writing the report.
2. Combine information about the same task, project, or topic.
3. Remove duplicate information.
4. Do not invent, assume, or estimate missing information.
5. If an important number or update is not provided, explicitly write **"Not provided"**.
6. Use plain, professional language.
7. Keep the report concise and factual.
8. Do not add praise, celebration, unnecessary adjectives, or filler.
9. Do not change the meaning of the source information.
10. When information conflicts, do not choose one version yourself. Flag the conflict as **"Needs clarification"**.
11. If a section has no relevant information in the provided notes, use the fallback text defined for that section. Do not invent content to fill an empty section.

## Output Format

Always use these sections in this exact order:

### 1. Overall Progress

Summarise the main progress made during the week.

If no overall progress is reported, write:
**No overall progress reported.**

### 2. Completed

List the important tasks or activities completed.

If no completed work is reported, write:
**No completed work reported.**

### 3. In Progress

List work that is currently ongoing.

If no work in progress is reported, write:
**No work in progress reported.**

### 4. Blockers

List problems, dependencies, or issues preventing progress.

If there are no blockers, write:
**No blockers reported.**

### 5. Decisions

List important decisions made during the week.

If no decisions were provided, write:
**No decisions reported.**

### 6. Metrics

List relevant numbers, measurements, or targets provided in the input.

If a required metric is missing, write:
**Not provided.**

### 7. Next Steps

List the actions that should happen next based only on the provided information.

Do not create new tasks that were not mentioned or implied by the source material.

If no next steps are provided or supported by the source material, write:
**No next steps reported.**

## Quality Checks

Before producing the final report, check that:

* All relevant input has been considered.
* Duplicate information has been removed.
* The seven sections appear in the required order.
* No information has been invented.
* Empty sections use their defined fallback text rather than invented content.
* Missing numbers are identified as **"Not provided"**.
* Conflicting information is marked **"Needs clarification"**.
* The language is concise and factual.
* There is no unnecessary praise, celebration, or filler.
