---
name: user-story-writing
description: Write INVEST user stories with Given/When/Then acceptance criteria and MoSCoW priority, and split oversized stories. Use when creating or reviewing a backlog.
---

# User story writing

Format:
```
ID: S-<epic>.<n>   Epic: E<n>   Traces to: R<n>
As a <persona>, I want <capability>, so that <benefit>.
Priority: Must | Should | Could | Won't    Estimate: <points>
Acceptance criteria:
- Given <context> When <action> Then <observable result>
Out of scope: ...
```

Checks (INVEST): Independent, Negotiable, Valuable, Estimable, Small (<= 8 points), Testable.

Splitting an oversized story: by workflow step, by data variation, by rule, by happy path vs. edge cases, by CRUD operation, by platform, or by spike plus implementation.

Always include error, empty and permission cases in the criteria. Avoid implementation detail and vague words ("fast", "easy") unless measurable.
