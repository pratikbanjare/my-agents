---
name: estimation-and-sprint-planning
description: Estimate stories in points and allocate them to sprints respecting capacity and dependencies. Use when building the sprint plan.
---

# Estimation and sprint planning

**Estimate** with Fibonacci points (1,2,3,5,8). Anything above 8 must be split. Estimate relative to a named reference story, include test and review effort, and record a confidence level (H/M/L). Low confidence -> add a spike.

**Capacity**: state assumptions explicitly (team size, sprint length, focus factor, default 0.7). With no velocity history, plan the first sprint conservatively and mark later sprints as forecasts.

**Sequencing**: order by dependency first, then value, then risk (retire risky items early). Foundations (setup, CI, data model) go in Sprint 1.

**Output** per sprint: goal, stories (ID, points, dependencies), total points vs capacity, risks, exit criteria. Add a summary table of sprint -> milestone/release.
