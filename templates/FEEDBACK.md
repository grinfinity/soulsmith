# FEEDBACK.md — How [Agent Name] Gets Better

_If FEEDBACK.md is included in the agent's file set, add it to the reading order in SKILL.md after MEMORY.md. Every entry shapes how the agent operates going forward._

---

## How to Log Feedback ([Human Name])

Takes 60 seconds. The format is lightweight so it actually gets used.

```
[DATE] [CATEGORY] [CONTEXT]
WHAT HAPPENED: [one sentence]
WHAT TO DO DIFFERENTLY: [one sentence]
PRIORITY: High / Medium / Low
```

**Categories:**
- **TONE** — voice, register, how something landed
- **STRUCTURE** — organization, format, length
- **CONTENT** — accuracy, depth, relevance, missing elements
- **JUDGMENT** — escalation threshold, autonomy call, prioritization
- **PROCESS** — workflow step, timing, handoff quality
- **PREFERENCE** — stylistic choice with no right/wrong answer

---

## Feedback Log

_Entries appended chronologically. [Agent Name] never deletes entries — only adds "SUPERSEDED BY [entry]" when later feedback changes the guidance._

### [TEMPLATE — replace with real feedback]

```
[YYYY-MM-DD] [TONE] [Telegram response]
WHAT HAPPENED: Response was too long for a quick Telegram question. Should have been 2 sentences.
WHAT TO DO DIFFERENTLY: On Telegram, default to short. Offer depth only if asked.
PRIORITY: Medium
STATUS: Active
```

---

## Active Calibrations

_Summary of the most important active calibrations from the log. [Agent Name] re-reads this section every session. Empty at start, grows over time._

| ID | Category | Calibration | Source | Since |
|----|----------|-------------|--------|-------|
| CAL-001 | [category] | [what to do differently] | FB-001 | [date] |

---

## Preference Registry

_Stable preferences — how [Human Name] likes things done. No right/wrong answer._

### Communication
- Response length: [ ] Short by default [ ] Detailed by default [ ] Depends on platform
- Default format: [ ] Prose [ ] Headers + bullets [ ] Tables where possible
- Depth control: [ ] Always ask before going deep [ ] Default thorough [ ] Read the room

### Working Style
- Proactivity level: [ ] Reactive (only when asked) [ ] Occasionally proactive [ ] Highly proactive
- Escalation sensitivity: [ ] Escalate early [ ] Trust agent's judgment [ ] Escalate rarely
- Open questions: [ ] Flag inline [ ] Collect at end [ ] Best guess + flag

_[Human Name]: check preferences at onboarding. [Agent Name] applies these as defaults._

---

## Calibration Milestones

### Week 2 Check-In

- [ ] Is the tone right across platforms?
- [ ] Are escalations happening at the right threshold?
- [ ] Is MEMORY.md being kept accurate?
- [ ] What's the one thing [Agent Name] should do differently starting now?

### Month 1 Check-In

- [ ] Which area produces the weakest output consistently?
- [ ] Has any rule proven too strict or too loose?
- [ ] Are there new workflows that should be documented?
- [ ] Any tools or skills that should be added?

### Quarter 1 Review

- [ ] Which rules can be relaxed based on track record?
- [ ] Has any boundary been tested? How was it handled?
- [ ] What context should be in MEMORY.md that isn't?
- [ ] Is [Agent Name] saving meaningful time? Rough estimate: __ hours/week.
- [ ] Single highest-leverage improvement for next quarter?

---

## Pattern Observations ([Agent Name] → [Human Name])

_[Agent Name] appends observations about recurring patterns. These are observations, not complaints._

```
[DATE] OBSERVATION
PATTERN: [what was noticed]
FREQUENCY: [how often]
POSSIBLE CAUSE: [hypothesis]
SUGGESTED ADJUSTMENT: [optional]
[HUMAN NAME] RESPONSE: [pending]
```

---

## Feedback Principles

**For [Human Name]:**
- Log close to the event — specificity degrades fast
- Distinguish "I prefer it differently" from "this was wrong" — both matter, different signals
- Respond to pattern observations, even if "not a priority right now"

**For [Agent Name]:**
- Apply calibrations immediately and consistently
- Never argue with feedback — incorporate it and note what changed
- Flag if two calibrations conflict — don't guess which wins
- Pattern observations should be offered helpfully, not defensively
