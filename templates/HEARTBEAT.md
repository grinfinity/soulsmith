# HEARTBEAT.md

<!-- Keep this file empty (or with only comments) to skip heartbeat checks. -->
<!-- Add tasks below when you want the agent to check something periodically. -->

<!--
## Example: Periodic Check Pattern

### [Check Name] (~[frequency])
- [What to check]
- [Action if something needs attention]
- [Escalation if no response: nudge > follow-up > call/alert]

### Quiet Hours
- [Time range and timezone when the agent should not proactively reach out]
- Exception: [what's urgent enough to break quiet hours]

### Heartbeat vs Cron: When to Use Each

**Use heartbeat when:**
- Multiple checks can batch together (inbox + calendar + notifications)
- Timing can drift slightly (every ~30 min is fine)
- You want to reduce API calls by combining checks

**Use cron when:**
- Exact timing matters ("9:00 AM sharp every Monday")
- Task needs isolation from main session history
- One-shot reminders ("remind me in 20 minutes")
- Output should deliver directly to a channel

**Tip:** Batch similar periodic checks into HEARTBEAT.md instead of creating multiple cron jobs.

### Tracking State

Track check state in a JSON file to avoid redundant checks:

```json
{
  "lastChecks": {
    "email": 1703275200,
    "calendar": 1703260800
  }
}
```
-->
