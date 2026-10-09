---
name: adr-writing
description: Record architecture decisions as ADRs with context, options, trade-offs and consequences. Use for any significant technical choice.
---

# ADR writing

Save as `docs/adr/NNNN-<slug>.md` (or inside the plan folder during planning).

```
# NNNN. <Decision title>
Status: Proposed | Accepted | Superseded by NNNN
Context: forces, constraints, requirement IDs
Options considered: A, B, C (each with pros/cons)
Decision: what and why
Consequences: positive, negative, follow-up work, risks
```

Rules: at least two real alternatives; state the reversal cost; prefer the simplest option fitting existing repo conventions; one decision per ADR.
