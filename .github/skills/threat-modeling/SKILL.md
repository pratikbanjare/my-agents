---
name: threat-modeling
description: Lightweight STRIDE threat model for a proposed design. Use when a feature handles auth, user data, external input, or new integrations.
---

# Threat modeling (STRIDE-lite)

1. List assets (data, credentials), actors, entry points and trust boundaries.
2. For each boundary/component, check: **S**poofing, **T**ampering, **R**epudiation, **I**nformation disclosure, **D**enial of service, **E**levation of privilege.
3. Output a table: ID, threat, component, likelihood, impact, mitigation, story/task that implements it.
4. Always cover: input validation, authn/authz, secrets handling, logging without sensitive data, dependency risk, rate limiting.
5. Turn mitigations into acceptance criteria or tasks; unmitigated high risks go to the risk register and open decisions.
