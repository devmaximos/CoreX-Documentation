# Ban Command

---

## Overview

The **Ban System** is the ultimate disciplinary tool for server administrators, allowing for the immediate and permanent removal of a user from the server. This command not only evicts the user but prevents them from rejoining, ensuring long-term security and order.

When a ban is issued, the bot processes the action instantly and generates a high-fidelity log entry for the moderation team.

---

# Command Usage

```bash
/ban user:[member] reason:[text]
```

# How to Ban a Member
1. Type `/ban` in the message bar of a moderation channel.
2. Select the **user** you wish to ban from the member list.
3. Provide a clear **reason** for the ban (e.g., "test").
4. Press **Enter** to execute.


---

# What the System Does
- **Permanent Removal:** Instantly removes the user and adds them to the server's ban list.
- **Immediate Feedback:** Displays a "Banned" confirmation card in the channel where the command was executed, featuring the target's avatar.
- **Automated Logging:** Sends a permanent record of the ban to the private logging channel.
- **Audit Details:** Logs include the target's mention/ID, the reason provided, the moderator who performed the action, and a precise timestamp.

---

# Requirements
Permissions:
- **User:** Must have the **Ban Members** permission (Admin/Moderator recommended).
- **Bot:** Ban Members, View Channels, Send Messages, Embed Links.

---

# Notes
- **Persistence:** Unlike a kick, a banned user cannot rejoin the server via a standard invite link.
- **Role Hierarchy:** The bot is unable to ban users who have a role equal to or higher than its own in the server hierarchy.
- **Reversing:** To allow a user back into the server, a staff member must manually unban them or use a corresponding `/unban` command.
