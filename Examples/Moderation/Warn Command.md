# Warning Command

---

## Overview

The **Warning Command** allows staff members to formally issue warnings to users who violate server rules. This system ensures accountability by providing immediate feedback to the moderator and logging the incident in a dedicated channel for long-term record-keeping.

When a warning is issued, the bot generates a professional embed containing all relevant details, including the target user, the reason, and the moderator responsible.

---

# Command Usage
```bash
/warn user:[member] reason:[text]
```

# How to Issue a Warning
1. Type /warn in any channel where the bot has permissions.
2. Select the **user** you wish to warn from the member list.
3. Provide a **reason** for the warning (e.g., "test0").
4. Press **Enter** to execute.

Once sent, the bot will display a "Sending command..." status followed by a confirmation embed in the current channel.

---

# What the System Does
- Displays an immediate confirmation embed (CoreX Documentation) in the channel where the command was used.
- Automatically mirrors the warning to a private #moderation-logs channel.
- Provides a persistent record even if the original command message is deleted.
- Updates logs in real-time as soon as the command is executed.

---

# Requirements
Permissions:
- **User:** Must have permission to manage members or messages (Admin/Moderator recommended)
- **Bot:** View Channels, Send Messages, Embed Links, View Audit Log

---

# Notes
- **Reason Field:** Providing a reason is highly recommended for clarity during future appeals.
- **Privacy:** While the warning message may be visible in public channels, the #moderation-logs channel should be restricted to staff only.
- **Visuals:** Each log entry includes the target, reason, moderator, and a timestamp for accurate tracking.
