---
name: plan
description: Turn an agreed goal into a concrete execution plan with phases, tasks, risks, and validation steps. Use when the user invokes /plan or asks for an implementation plan, roadmap, task breakdown, or execution strategy.
---

# Plan

Use this skill after alignment or brainstorming to create an actionable plan.

## Workflow

1. Restate the objective and chosen direction.
2. Break work into phases or milestones.
3. List concrete tasks in dependency order.
4. Identify risks, unknowns, and validation checkpoints.
5. Define the first small next action.
6. Keep the plan adaptable rather than over-specified.

## Rules

- Plans should be executable, not just conceptual.
- Prefer ordered steps with clear outcomes.
- Include verification for each major phase.
- Flag assumptions that could change the plan.
- Do not hide uncertainty; make it visible.

## Output Format

```md
## Objective
[What we are trying to accomplish]

## Plan
### Phase 1: [Name]
- [ ] Task
- [ ] Task
- Validation: ...

### Phase 2: [Name]
- [ ] Task
- Validation: ...

## Risks & mitigations
- Risk: ...
  - Mitigation: ...

## First next action
[Smallest useful step]
```
