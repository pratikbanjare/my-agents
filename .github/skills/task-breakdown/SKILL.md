---
name: task-breakdown
description: Decompose user stories into traceable engineering tasks with owners, estimates and dependencies. Use when planning developer work.
---

# Task breakdown

For each story produce tasks of at most ~1 day:

| Task ID | Story | Description | Owner role | Est (h) | Depends on | Files/areas |
|---|---|---|---|---|---|---|

Include for every story: implementation, unit/integration tests, docs, migration or config, and review/QA hand-off. Add explicit tasks for spikes, tooling and CI changes.

Rules: ID scheme `T-<story>.<n>`; no task without a story; flag circular or cross-story dependencies; mark the critical path; if a task is > 8h, split it. Read the codebase first to name real files/modules.
