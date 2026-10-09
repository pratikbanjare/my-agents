---
name: bug-report
description: Write reproducible, prioritised defect reports. Use when QA finds a failure during verification.
---

# Bug report

```
ID: BUG-<n>   Story: S-x.y   Severity: Sev1 | Sev2 | Sev3 | Sev4
Title: <what fails, where>
Environment: build/commit, OS, config
Steps to reproduce: 1... 2... 3...
Expected:
Actual:
Evidence: logs, output, screenshots
Suspected cause (optional):
```

Severity: Sev1 data loss/security/outage; Sev2 core flow broken, no workaround; Sev3 degraded with workaround; Sev4 cosmetic. One defect per report; confirm it reproduces before filing.
