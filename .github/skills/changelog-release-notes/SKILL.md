---
name: changelog-release-notes
description: Generate semver-based changelog entries and user-facing release notes from completed stories and commits. Use when preparing a release.
---

# Changelog and release notes

1. Pick the version: breaking change -> major, new feature -> minor, fix only -> patch.
2. Collect completed stories and commits since the last release.
3. CHANGELOG.md (Keep a Changelog): `## [x.y.z] - YYYY-MM-DD` with Added, Changed, Deprecated, Removed, Fixed, Security. One line per change, with story ID.
4. Release notes: user-facing highlights in plain language, breaking changes with migration steps, known issues, upgrade instructions.
5. Do not tag or publish; hand the draft to the user.
