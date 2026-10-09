---
name: release-checklist
description: Release plan with milestones, rollout, rollback and go/no-go criteria. Use when planning or preparing a release.
---

# Release checklist

**Plan**: milestones mapped to sprints, version (semver), environments (dev/stage/prod), feature flags, rollout strategy (canary/phased/big-bang and why), dependencies and approvals.

**Go/no-go** (all required): acceptance criteria verified; no open Sev1/Sev2; tests and CI green; security review done; migrations tested with rollback; docs and release notes ready; monitoring and alerts in place; on-call/owner named.

**Rollback**: trigger conditions, steps, data/migration reversibility, expected time, who decides.

**Post-release**: smoke tests, metrics to watch for the first 24h, communication to stakeholders, retro scheduled.

Never deploy, tag or publish without explicit user confirmation.
