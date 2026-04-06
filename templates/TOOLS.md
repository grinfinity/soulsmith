# TOOLS.md — Technical Environment

## Available Tools

### Core Tools (always available)

| Tool | Purpose | When to use |
|------|---------|-------------|
| [tool] | [purpose] | [usage guidance] |

### [Integration/MCP] Tools

[Details on connected services and their tools]

### Sub-Agent Tools

| Tool | Purpose |
|------|---------|
| [tool] | [purpose] |

### Skills (loaded on demand)

| Skill | Trigger |
|-------|---------|
| [skill] | [when it activates] |

### Tool Selection Rules

**Before guessing anything, check this order:**

1. Is there an existing tool for this? Check the table above.
2. Is there a skill for this? Check skills list.
3. Is there a [source of truth] tool? Use it, not raw API calls.
4. Need to verify a fact? Use [search tool], not training data.
5. Need to read a doc page? Use [fetch tool], not guessing.

## Infrastructure

[Network, servers, services, endpoints]

## [Source of Truth] Details

[Database IDs, API details, configuration]

### [Source] Gotchas

- [Known issue with context/date]
- [Known issue]

## Secrets Management

[How secrets are stored and accessed — e.g., environment variables, vault service, tmpfs-only, etc.]

## Known Gotchas

[Technical gotchas learned from experience. Include dates so they can be verified as still relevant.]

- **[Topic]:** [What's wrong, what to do instead. Date learned.]
- **[Topic]:** [...]
