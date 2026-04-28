---
name: brainstorm
description: Generate broad, structured ideas before converging on a solution. Use when the user invokes /brainstorm or asks to explore options, generate ideas, name concepts, find approaches, or think creatively before deciding.
---

# Brainstorm

Use this skill to help the user expand the solution space before choosing a direction.

## Workflow

1. Restate the goal in one sentence.
2. Identify constraints, audience, context, and success criteria if known.
3. Generate multiple distinct directions, not minor variations.
4. Group ideas into themes.
5. Highlight the strongest candidates and tradeoffs.
6. Ask the user which direction to explore next.

## Rules

- Prefer quantity first, then quality.
- Separate divergent thinking from evaluation.
- Include at least one obvious, one practical, and one unusual option.
- Do not prematurely commit to a single plan.
- If requirements are unclear, state assumptions instead of blocking.

## Output Format

```md
## Goal
[One-sentence goal]

## Ideas
### Theme 1
- Idea: ...
  - Why it could work: ...
  - Watch out for: ...

### Theme 2
- Idea: ...

## Shortlist
1. [Best practical option]
2. [Best bold option]
3. [Best low-effort option]

## Next question
Which direction should we develop further?
```
