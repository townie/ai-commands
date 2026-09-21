---
name: AI Commands
description: >-
  Use when the user types an AI Commands mode phrase such as QUESTIONS FIRST,
  EXECUTE, JUST DO IT, KEEP SIMPLE, ASSUMPTION AUDIT, SHOW ME THE OPTIONS,
  FIRST PRINCIPLES, WHY DOES THIS FAIL?, COUNCIL, REBUTTAL, COUNCIL + REBUTTAL,
  FACT CHECK ONLY, or 80/20 — or asks to switch into one of those modes.
---

# AI Commands

Quick prompts that switch how you respond. When the user types a command name
(alone or at the start of a message), adopt that mode for the rest of the turn
until they change mode or the task ends.

Type the command in the message to switch modes.

## CONTROL

### QUESTIONS FIRST
Ask the useful questions and stop before answering. Use when the user wants to
supply context before you analyze anything. Do not produce the substantive
answer yet.

### EXECUTE / JUST DO IT
Skip questions and the assumptions/questions note and perform the task
immediately. Use when the user already gave enough information and wants action.
Counterpoint still runs.

### KEEP SIMPLE
Answer briefly and naturally. Skip questions and extra frameworks or caveats
unless essential. Counterpoint still applies.

## ANALYZE

### ASSUMPTION AUDIT
Expose what must be true for the conclusion to hold. Use when an answer feels
convincing but may rest on shaky assumptions.

### SHOW ME THE OPTIONS
Broaden the option space before converging. Use when you may have jumped too
quickly to one path.

### FIRST PRINCIPLES
Strip away convention and inherited assumptions. Use when a problem feels
constrained by how it is normally done.

## STRESS TEST

### WHY DOES THIS FAIL?
Pressure-test the current idea or recommendation. Surface failure modes, weak
assumptions, missing risks, and reasons it could break.

### COUNCIL
Run Contrarian, First Principles, Expansionist, Outsider, and Executor; then
synthesize. Use for a broad strategic stress test.

### REBUTTAL
Attack the recommendation through competitor, internal skeptic, and end user.
Use when you want to see why a good-looking answer may fail in practice.

### COUNCIL + REBUTTAL
Run both frameworks together. Use for the deepest qualitative review of a
strategy, system, hiring decision, or business idea.

## VERIFY

### FACT CHECK ONLY
Verify the factual claims and stop. No strategy or recommendations layered on.

### 80/20
Judge whether a plan, draft, decision, or ruleset is mostly good and surface
only the high-leverage changes.

## Default
- No command: respond normally.
- Multiple commands: apply in order, or ask which wins if they conflict.
- Stay in mode until the user clears it or names another.
