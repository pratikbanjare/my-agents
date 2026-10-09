# my-agents

A virtual agile product team built from GitHub Copilot custom agents (`.github/agents/`).

| Agent | Role |
|---|---|
| `scrum-master` | Orchestrator: runs the team, cross-reviews, produces the plan, gates execution |
| `product-owner` | Epics, stories, acceptance criteria, priorities |
| `architect` | Technical design, NFRs, risks |
| `ux-designer` | Flows, states, accessibility |
| `developer` | Estimates/tasks, then implementation |
| `qa-engineer` | Test strategy, then verification |
| `release-manager` | CI/CD, release & rollback plan |

## Usage
1. Select the **scrum-master** agent and paste your detailed requirement.
2. **Phase 1 – Planning:** agents analyse independently, review each other, and write `docs/plans/<slug>/PLAN.md` (requirements → epics → stories → tasks → sprints → release plan, plus risks and open decisions). No product code is touched.
3. Review the report; ask for revisions or **approve**.
4. **Phase 2 – Execution:** on approval, the team implements sprint by sprint (dev → QA → architect review → release prep) with a review file per sprint. Nothing is deployed without your explicit OK.

## Skills (`.github/skills/`)
Reusable playbooks the agents invoke for their purpose:

| Skill | Used by |
|---|---|
| `requirements-intake`, `plan-template` | scrum-master, product-owner |
| `user-story-writing` | product-owner |
| `estimation-and-sprint-planning` | scrum-master, product-owner, developer |
| `task-breakdown`, `conventional-commits-and-pr` | developer, scrum-master |
| `adr-writing`, `threat-modeling` | architect |
| `test-strategy`, `bug-report` | qa-engineer |
| `accessibility-audit` | ux-designer, qa-engineer |
| `release-checklist`, `changelog-release-notes` | release-manager |
| `risk-register` | scrum-master, architect, release-manager |
| `sprint-review-retro` | scrum-master |
