---
name: accessibility-audit
description: WCAG 2.2 AA checklist for designs and implemented UI. Use in UX planning and QA verification of any user interface.
---

# Accessibility audit

Check:
- Keyboard: all functions reachable, logical focus order, visible focus, no traps
- Semantics: correct headings, landmarks, labels for every input, button vs link, alt text
- Contrast: text 4.5:1, large text and UI components 3:1; no colour-only meaning
- Screen reader: names, roles, states, live regions for dynamic updates, announced errors
- Forms: clear errors with fix guidance, no time limits without extension
- Responsive/zoom to 200%, touch targets >= 24px, respect reduced motion
- Media: captions and transcripts

Output: table of Issue | WCAG criterion | Severity | Location | Fix. Add accessibility acceptance criteria to stories at design time, not after.
