---
name: decision-log-entry
description: Turns meeting notes or a transcript excerpt into structured decision-log entries. Use when someone shares notes from a meeting and asks to log, record, capture, or write up the decisions that were made — not for summarizing a whole meeting, and not for extracting action items (that's notes-to-actions).
---

# Decision Log Entry

## Purpose

Given raw meeting notes or a transcript excerpt, find the decisions that were actually made — not discussed, not proposed, not left open — and write each one as a single structured entry in a running decision log.

## What counts as a decision

A decision is a concrete choice or commitment the group settled on. To qualify, it needs an identifiable owner or group that made the call, and language indicating it's settled ("we're going with X", "agreed:", "decision:", "we'll use Y instead of Z") rather than exploratory ("we could...", "maybe we...", "worth considering...", "let's think about...").

Do not log:
- Open questions or unresolved debates ("still deciding between A and B")
- Action items with no underlying decision ("Sam will follow up with the vendor") — that belongs in notes-to-actions, not here
- Status updates or FYIs ("the build is now passing")
- Tentative leanings that were explicitly left open for revisiting

When it's genuinely ambiguous whether something was decided, don't guess — list it separately under "Possible decisions to confirm" rather than logging it as settled.

## Instructions

1. Read the full notes/transcript excerpt provided before extracting anything — a decision stated early is sometimes reversed later in the same meeting.
2. Pull out each qualifying decision (see above). One entry per decision, even if several were made back-to-back.
3. For each, extract:
   - Date — use the meeting date if given, otherwise ask rather than guessing.
      - Decision — one clear sentence stating what was decided.
         - Owner — who made or is accountable for the call (a person, or the group if it was consensus).
            - Rationale — the reason given, in one sentence. If no rationale was stated, write "not stated" rather than inventing one.
               - Status — Decided, Reversed (link back to the entry it reverses), or Pending confirmation (for the ambiguous cases above).
               4. Format entries consistently (see Output format) and append them to the log — do not reorder or rewrite prior entries.
               5. If the notes contain no qualifying decisions at all, say so explicitly instead of stretching an action item or discussion point into a decision.
               6. Keep entries factual and traceable to the source text. Don't add outside context or opinions about whether the decision was a good one.

               ## Output format

                   ### [YYYY-MM-DD] — [Short decision title]
                       - Decision: one-sentence statement of what was decided
                           - Owner: name or group
                               - Rationale: why, in one sentence, or "not stated"
                                   - Status: Decided, Reversed, or Pending confirmation

                                   Append new entries to the end of the log file, most recent last, so the log reads chronologically.

                                   ## Edge cases

                                   - Multiple decisions in one meeting — log each as its own entry, don't merge them.
                                   - A decision reversed later in the same or a later meeting — log the reversal as its own entry with Status: Reversed, and reference the original entry's title rather than deleting it. The log is a history, not a snapshot.
                                   - Vague or hedged language ("we're probably going to...", "leaning toward...") — do not log as Decided. Use Pending confirmation or omit, and say why.
                                   - Decision made outside the meeting but referenced in it ("as discussed offline, we're doing X") — log it, but note in Rationale that it was made outside this meeting.
