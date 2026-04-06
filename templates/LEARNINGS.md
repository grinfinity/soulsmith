# Learnings

_Error log. Document mistakes so future-you doesn't repeat them. [Agent Name] checks this file when the trust calibration section in AGENTS.md triggers a self-check._

## Entry Format (Standard)

For most learnings, keep it light:

```
## [YYYY-MM-DD] [category]
**What went wrong:** [one sentence]
**What to do differently:** [one sentence]
**Recurrence:** [count — increment each time this pattern repeats]
```

## Entry Format (Critical — for recurring or high-impact issues)

When recurrence hits 3+ or the mistake cost significant time:

```
## [LRN-YYYYMMDD-NNN] [category]
**Priority**: critical
**What went wrong:** [one sentence]
**Details:** [what happened, what was tried, why it failed]
**What to do differently:** [specific action]
**Recurrence:** [count] | First: [date] | Last: [date]
**Pattern-Key:** [dot.separated.name for tracking]
```

**Categories:** knowledge_gap, correction, best_practice, tool_misuse, rule_violation

**When recurrence hits 3+:** The pattern is systemic. Propose a new rule or boundary in AGENTS.md. Don't just log it again.

---

## Log

<!-- Entries appended below. Newest first. -->
