---
name: requirements-intake
description: Turn a raw requirement into a clarified, bounded brief. Use at the start of planning to find gaps, ask clarifying questions, and log assumptions and out-of-scope items.
---

# Requirements intake

1. Restate the requirement in 3-5 lines: problem, users, desired outcome.
2. Check for gaps: users/personas, success metrics, constraints (tech, budget, deadline, compliance), integrations, data, non-functional needs, existing behaviour to preserve.
3. Ask only blocking questions, one at a time (ask_user, with choices when possible). Everything else becomes an **assumption**.
4. Output:
   - Brief (goal, personas, success metrics)
   - In scope / Out of scope
   - Assumptions table (ID, assumption, risk if wrong)
   - Open questions (ID, question, owner, blocking?)
5. Give each requirement an ID (R1, R2...) so stories and tasks can trace back to it.
