# meeting-operations-skill-pack


## Overview

This Skill Pack contains three Skills designed to turn messy meeting information into structured, useful outputs.

The Skills cover three different stages of working with meeting notes:

1. Extracting action items and next steps- Owner: Oluwatosin_Ajayi
2. Creating a concise weekly report- Owner: Mukherjee_Shilpi
3. Creating a structured decision-log entry- Owner: Kenzy_Maafi

The Skills are designed to work with real-world meeting notes, where information may be incomplete, duplicated, informal, or unclear.

## Skills

### 1. Notes to Actions

**Purpose:**  
Turn raw meeting notes, call transcripts, or messy bullet points into a clear list of genuine action items.

**The Skill identifies:**
- What needs to be done
- Who owns the task
- When it is due
- Items that were discussed but not actioned
- Actions where an owner or deadline is missing

**Key principle:**  
The Skill must not invent owners, deadlines, or commitments.

---

### 2. Weekly Report 

**Purpose:**  
Combine multiple meeting notes and weekly updates into one concise weekly report.

**The report contains:**
- Overall Progress
- Completed
- In Progress
- Blockers
- Decisions
- Metrics
- Next Steps

**Key principle:**  
The Skill combines duplicate updates, handles missing information explicitly, and flags conflicting information rather than choosing a version itself.

---

### 3. Decision Log Entry

**Purpose:**  
Turn meeting discussions and decisions into structured decision-log entries.

**The Skill captures:**
- The decision made
- Relevant context or reason
- People involved, when provided
- Date, when provided
- Any follow-up or implications

**Key principle:**  
Only record decisions that are actually supported by the meeting notes. Discussions, suggestions, or possibilities must not be presented as confirmed decisions.

---

## How the Skills Differ

| Skill | Main Output |
|---|---|
| Notes to Actions | Action items and follow-ups |
| Weekly Report | Weekly progress summary |
| Decision Log Entry | Structured record of decisions |

The Skills have different purposes and should not be treated as interchangeable.

## Reliability Principles

All three Skills follow these principles:

- Do not invent information.
- Preserve the meaning of the source notes.
- Distinguish confirmed information from discussion or uncertainty.
- Handle missing information explicitly.
- Keep outputs clear and concise.
- Review the complete input before producing the final output.

## Review Process

Each Skill is reviewed by another team member.

The review process checks whether the Skill:

- Follows its intended purpose
- Handles incomplete information correctly
- Avoids hallucinating information
- Produces the required output structure
- Handles ambiguous or conflicting information appropriately
- Works across different types of meeting notes

Changes are made to the Skills based on review feedback.

## Repository Structure

```text
meeting-notes-skill-pack/
│
├── README.md
│
├── notes-to-actions/
│   └── SKILL.md
│
├── weekly-report/
│   └── SKILL.md
│
└── decision-log-entry/
    └── SKILL.md
