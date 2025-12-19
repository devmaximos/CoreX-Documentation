# Untimeout Command

---

## Overview

The **Untimeout Command** allows staff members to prematurely remove a timeout from a user. This is used when a penalty is rescinded or if a user has successfully appealed their restriction before the original duration has expired.

When a timeout is removed, the bot restores the user's interaction permissions and logs the action for server records.

---

# Command Usage
```bash
/untimeout user:[member] reason:[text]
```

# How to Remove a Timeout
1. Type `/untimeout` in an active channel.
2. Select the **user** whose restriction you want to lift.
3. Provide a **reason** for removing the timeout (e.g., "He said sorry").
4. Press **Enter** to execute.


---

# What the System Does
- **Restores Permissions:** Immediately removes the Discord timeout restriction from the target user.
- **Immediate Feedback:** Displays an "Untimeout" embed in the current channel showing the target and the moderator responsible.
- **Automated Logging:** Sends a detailed log to the private logging channel.
- **Audit Tracking:** Log entries include the target's mention, the reason provided, the moderator who executed the command, and the timestamp.

---

# Requirements
Permissions:
- **User:** Must have permission to moderate members (Admin/Moderator recommended).
- **Bot:** Moderate Members, View Channels, Send Messages, Embed Links.

---

# Notes
- **Reason Field:** It is recommended to document why a timeout was removed to maintain a clear audit trail.
- **Instant Effect:** The user will be able to send messages and react immediately after the command is processed.
