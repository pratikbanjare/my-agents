---
name: conventional-commits-and-pr
description: Commit message and pull request conventions that reference story/task IDs. Use when committing code or opening PRs during execution.
---

# Commits and PRs

Commit: `<type>(<scope>): <summary> [S-1.2]` with type in feat, fix, docs, test, refactor, chore, ci. Imperative mood, summary <= 72 chars, body explains why. One logical change per commit.

Always add the trailer:
`Co-authored-by: Copilot App <223556219+Copilot@users.noreply.github.com>`

PR description: why (motivation), approach (key decisions, not a file list), story IDs covered, test evidence, risks or review hotspots, rollback note. Keep it proportional to the change. Use the repo's PR template if one exists.
