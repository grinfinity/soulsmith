# Quality Rubric — Agent Identity Scoring

Use this rubric in Analyze mode (scoring existing agents) and Upgrade mode (assessing before improving).

## Core Rubric (8 dimensions, always scored)

Score each 1-5. Total: /40.

| # | Dimension | 1 (Weak) | 5 (Strong) |
|---|-----------|----------|------------|
| 1 | **Specificity** | "I have nuanced views" | Specific takes with reasoning, named references |
| 2 | **Predictability** | Can't guess their take on anything | Could predict their take on a new topic from worldview |
| 3 | **Voice** | Sounds like any AI | Distinctive vocabulary, rhythm, tone that couldn't be anyone else |
| 4 | **Opinions** | Everything balanced and reasonable | Actual hot takes with reasoning, bad-advice pushbacks |
| 5 | **Rule Enforcement** | Vague guidelines ("be careful") | Numbered rules R-XX with procedures, incident history, rationale |
| 6 | **Separation** | Everything in one file | Personality (SOUL), voice (STYLE), operations (AGENTS) properly separated |
| 7 | **Calibration** | No examples | 10+ good-output samples, 8+ bad-output anti-patterns with corrections |
| 8 | **Completeness** | Missing files, hollow sections | All expected files substantive and interconnected |

## Extended Rubric (7 dimensions, Analyze mode only)

Adds to core for total /75.

| # | Dimension | 1 (Weak) | 5 (Strong) |
|---|-----------|----------|------------|
| 9 | **Worldview** | No deep beliefs, only surface opinions | Fundamental beliefs specific enough to be wrong |
| 10 | **Influences** | No named references | Specific people, books, frameworks with what was taken from each |
| 11 | **Boundaries** | None stated or too vague | Clear character limits (not just operational rules) with rationale |
| 12 | **Texture** | Abstract descriptions only | Specific anecdotes, references, vocabulary that ground the personality |
| 13 | **Contradictions** | Suspiciously coherent | Captures real tensions in belief/behavior |
| 14 | **Actionability** | Philosophical but not implementable | An LLM could embody this immediately |
| 15 | **Consistency** | Files contradict each other | All files tell coherent story, SKILL.md is canonical reading order |

## Red Flags

Call these out regardless of individual scores:

- Everything sounds reasonable and balanced (real agents have specific takes)
- No specific names, references, or examples (too abstract)
- Could apply to many agents (not distinctive)
- All consistent with no tensions (suspiciously coherent)
- AGENTS.md is generic boilerplate without numbered rules or procedures
- USER.md reads like a form, not a portrait of a person
- TOOLS.md lists technologies without "when to use" guidance
- No STYLE.md (voice rules buried in SOUL.md where they get treated as vibes)
- No examples/ (no calibration material to validate voice)
- No SKILL.md (no reading order, no source priority, agent doesn't know what to read first)
- MEMORY.md contains rules instead of memories (rules masquerading as history)
- Uses phrases like "I believe in balance" or "I consider multiple perspectives" (meaningless)
- Opinions without reasoning ("Open source wins" without why)
- Identity section reads like a resume instead of a personality
- Emotional/frustrated language in rules instead of procedural enforcement

## Scoring Report Template

```markdown
## Agent Analysis: [Name]

### Overall Score: [X/40] (Core) | [X/75] (Extended, if scored)

| # | Dimension | Score | Verdict |
|---|-----------|-------|---------|
| 1 | Specificity | X/5 | [one-line assessment] |
| 2 | Predictability | X/5 | [one-line assessment] |
| 3 | Voice | X/5 | [one-line assessment] |
| 4 | Opinions | X/5 | [one-line assessment] |
| 5 | Rule Enforcement | X/5 | [one-line assessment] |
| 6 | Separation | X/5 | [one-line assessment] |
| 7 | Calibration | X/5 | [one-line assessment] |
| 8 | Completeness | X/5 | [one-line assessment] |

### Structural Issues
- [e.g., "Rules scattered across SOUL.md, AGENTS.md, and MEMORY.md"]
- [e.g., "MEMORY.md is 50% operational rules, not memories"]

### Strengths
- [specific things that work well, with quotes from the files]

### Weaknesses
- [specific things that need work, with examples]

### Red Flags
- [any red flags detected from the list above]

### Recommendations (prioritized)
1. [highest impact improvement]
2. [next]
3. [next]
```
