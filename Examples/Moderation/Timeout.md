# Moderation System: Timeout Command

---

## Overview

The **Timeout System** allows staff members to temporarily restrict a user's ability to interact within the server. This is an effective middle-ground between a warning and a kick, used to de-escalate situations or penalize rule-breaking for a specific duration.

When a timeout is issued, the bot restricts the user and logs the action with high visibility for the moderation team.

---

# Command Usage
```bash
/timeout user:[member] minutes:[number] reason:[text]
```

# How to Issue a Timeout
1. Type `/timeout` in a channel where the bot is active.
2. Select the **user** you wish to restrict.
3. Enter the duration in **minutes** (e.g., 10).
4. Provide a **reason** for the timeout (e.g., "He/She spammed").
5. Press **Enter** to execute.


---

# What the System Does
- **Temporary Restriction:** Automatically applies a Discord timeout to the target user for the specified duration.
- **Immediate Confirmation:** Displays a "Timeout" embed in the current channel showing the duration and target.
- **Automated Logging:** Sends a detailed log to the private logging channel.
- **Detailed Audit Trail:** Logs include the target's mention, the duration (e.g., 10m), the reason, the moderator responsible, and a timestamp.

---

# Requirements
Permissions:
- **User:** Must have permission to timeout members (Admin/Moderator recommended).
- **Bot:** Moderate Members, View Channels, Send Messages, Embed Links.

---

# Notes
- **Duration:** The timeout period is entered in minutes; ensure the value is appropriate for the offense.
- **Persistence:** Timeouts are managed by Discord's native system, ensuring the user remains restricted even if they leave and rejoin.
- **Staff Logs:** The private log entry allows the team to see exactly when a timeout was issued and by whom.
