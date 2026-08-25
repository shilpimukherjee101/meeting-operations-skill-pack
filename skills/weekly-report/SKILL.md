---

name: weekly-report
description: Turn multiple meeting notes and weekly updates into one concise weekly report with consistent sections, clear language, and no invented information.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------

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
5. If a number or update is required by the report context but is not provided in the source notes, write **"Not provided"**. Do not create or estimate missing information.
6. Use plain, professional language.
7. Keep the report concise and factual.
8. Do not add praise, celebration, unnecessary adjectives, or filler.
9. Do not change the meaning of the source information.
10. When information conflicts, do not choose one version yourself. Flag the conflict as **"Needs clarification"**.

## Output Format

Always use these sections in this exact order:

### 1. Overall Progress

Summarise the main progress made during the week.

### 2. Completed

List the important tasks or activities completed.

### 3. In Progress

List work that is currently ongoing.

### 4. Blockers

List only problems or dependencies that are explicitly stated as blocking or preventing progress. Do not assume that an issue is a blocker unless the source notes say so.

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

## Quality Checks

Before producing the final report, check that:

* All relevant input has been considered.
* Duplicate information has been removed.
* The seven sections appear in the required order.
* No information has been invented.
* Missing numbers are identified as **"Not provided"**.
* Conflicting information is marked **"Needs clarification"**.
* The language is concise and factual.
* There is no unnecessary praise, celebration, or filler.

