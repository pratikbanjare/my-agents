---
name: test-strategy
description: Define the test strategy, test cases, edge cases and Definition of Done for a plan. Use during planning and when verifying stories.
---

# Test strategy

1. **Levels**: unit, integration, end-to-end, plus performance, security, accessibility and regression as relevant. Follow the test pyramid; state what is automated vs manual.
2. **Per story**: map each acceptance criterion to at least one test case (ID, preconditions, steps, expected). Table: Story | Criterion | Test ID | Level | Automated?
3. **Edge-case heuristics**: boundaries, empty/null, max sizes, invalid types, duplicates, concurrency, permissions, time zones, failure of dependencies, retries/idempotency.
4. **Environment and data needs**; tooling already used in the repo takes precedence.
5. **Definition of Done**: criteria met, tests pass, no open Sev1/Sev2 defects, code reviewed, docs updated, no new lint/security warnings, accessibility checked where UI exists.
6. **Exit criteria** per release and the quality risks.
