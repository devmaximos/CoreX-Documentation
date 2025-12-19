# Event Log System

---

## Overview

The **Event Log** system provides detailed server-side logging for important Discord events.  
It helps server administrators monitor activity, detect abuse, and maintain a clear audit trail of actions occurring within the server.

All logs are delivered automatically to configured log channels and persist across bot restarts.

⚠️ **Important Requirement**  
The Event Log system **must be enabled from the config panel** in order to function.

---

## How to Enable Event Log

```bash
/config
```

### Steps
1. Run the `/config` command.
2. Open the **Event Log** section.
3. Enable the Event Log system.
4. Assign log channels for each event category.
5. Save the configuration.

Once enabled, logging begins immediately.

---

## What the Event Log Tracks

Depending on configuration, the system can log:

### Server & Structure
- Channel creation, deletion, and updates
- Role creation, deletion, and permission changes


Each log entry includes:
- The user responsible (via Audit Logs when available)
- The affected target (user, role, channel, etc.)
- The action performed
- Timestamp

---

## Behavior

- Logging operates automatically after setup.
- No manual commands are required once enabled.
- The system works silently without sending public messages.
- Audit Logs are used whenever possible to identify executors.
- All data is stored persistently and survives restarts.

---

## Requirements

### Permissions

User:
- Must have permission to manage server configuration (Admin recommended)

Bot:
- View Audit Log
- Send Messages
- Embed Links
- Administrator (recommended for full coverage)

---

## Notes

- Disabling Event Log immediately stops all logging.
- Missing permissions may result in incomplete logs.
- Configuration changes apply instantly.
- Individual event categories can be enabled or disabled from the config panel.
