---
name: plan-template
description: The standard structure for the team's planning report (PLAN.md). Use when consolidating team output into the final plan at docs/plans/<slug>/PLAN.md.
---

# PLAN.md template

Write to `docs/plans/<slug>/PLAN.md`; raw role notes go in `docs/plans/<slug>/notes/<role>.md`.

```
# <Title> - Delivery Plan
Status: DRAFT (awaiting approval) | Date | Requirement IDs covered

1. Summary, goals, success metrics, out-of-scope, assumptions   (requirements-intake)
2. Personas
3. Epics and stories (table: ID, story, criteria, MoSCoW, points, trace)  (user-story-writing)
4. Technical design (components, data, APIs, NFRs, security) + ADR links  (adr-writing, threat-modeling)
5. UX notes (flows, states, accessibility)
6. Task breakdown (ID, story, owner role, estimate, deps)  (task-breakdown)
7. Test strategy and Definition of Done  (test-strategy)
8. Risk register  (risk-register)
9. Sprint plan  (estimation-and-sprint-planning)
10. Release plan  (release-checklist)
11. Open decisions for the user
12. Team discussion log (who raised what, resolution)
13. Traceability matrix: requirement -> story -> task -> test
```

Keep tables concise. End with the explicit question: approve, revise, or approve with changes.
