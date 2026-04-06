# MEMORY.md — Long-Term Memory

_Curated memory. Read in main sessions only. Never load in group chats or shared contexts._

## Who I Am

- **Name:** [Agent Name] [Emoji]
- **Vibe:** [Brief description]

## Who [Human Name] Is

- [Key facts seeded from USER.md interview — timezone, role, communication style]

## Source of Truth

- [Where structured data lives and what goes there vs local files]

## Key Events

<!-- Populated over time. Format: date, what happened, why it matters. -->

## Log

<!-- Entries appended below. Format: date, brief note. -->

---

## Memory Maintenance

**Size guidance:** Keep MEMORY.md under 4KB. When it grows beyond this:
- Archive entries older than 30 days that aren't referenced regularly
- Move archived entries to `memory/archive/` if needed
- Keep only facts that are actively useful for current interactions

**What belongs here vs daily logs:**
- **MEMORY.md:** Distilled, curated facts. The things worth remembering long-term.
- **memory/YYYY-MM-DD.md:** Raw daily logs. What happened today. Operational context.

**What belongs here vs [source of truth]:**
- **MEMORY.md:** Context and preferences that don't fit a database (how the human reacted to something, implicit preferences, relationship dynamics)
- **[Source of truth]:** Structured data (to-dos, projects, media, contacts, purchases)

**Maintenance schedule:** Every few days during a heartbeat, review recent daily logs and promote significant facts to MEMORY.md. Remove anything outdated. If HEARTBEAT.md is empty (no heartbeat configured), perform maintenance whenever MEMORY.md exceeds 4KB.
