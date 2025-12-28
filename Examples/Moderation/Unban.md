# Unban Command

---

## Overview

The **Unban System** provides staff members with a way to lift a user's permanent restriction from the server. This allows previously banned individuals to rejoin the community, typically following a successful appeal process.

When an unban is executed, the bot removes the user from the server's blacklist and generates a high-fidelity log entry for the moderation team.

---

# Command Usage

```bash
/unban user:[mention, user ID, or username]
```

# How to Unban a Member
1. Type `/unban` in an active channel.
2. Provide the **user**'s mention, user ID, or username.
3. Press **Enter** to execute.


---

# What the System Does
- **Lifts Restrictions:** Instantly removes the target's ID from the server's ban list.
- **Immediate Feedback:** Displays an "Unbanned" confirmation card in the channel where the command was executed.
- **Automated Logging:** Sends a permanent notification to the private logging channel.
- **Execution Details:** Logs specify the target user, the moderator who performed the action, and the exact timestamp.

---

# Requirements
Permissions:
- **User:** Must have the **Ban Members** permission (Admin/Moderator recommended).
- **Bot:** Ban Members, View Channels, Send Messages, Embed Links.

---

# Notes
- **Rejoining:** Once unbanned, the user must use a new invite link to re-enter the server.
- **Versatility:** The command supports various ways to identify the user (mention, ID, or username), making it easy to find individuals no longer in the member list.
- **Staff Records:** All unbans are tracked in logging channel to ensure accountability across the staff team.
