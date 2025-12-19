# Lock Command

---

## Overview

The **Lock Command** provides staff members with an immediate way to restrict message permissions in a specific channel. This is typically used during intense situations, raids, or when a channel needs to be temporarily closed for maintenance or staff review.

When a channel is locked, the bot updates the channel permissions and logs the action to ensure a clear administrative trail.

---

# Command Usage
```bash
/lock
```

# How to Lock a Channel
1. Navigate to the channel you wish to secure.
2. Type `/lock` in the message bar.
3. Press **Enter** to execute.


---

# What the System Does
- **Permission Override:** Instantly modifies channel permissions to prevent regular members from sending messages.
- **Visual Confirmation:** Posts a "Channel Locked" embed in the affected channel so users are aware of the restriction.
- **Automated Logging:** Sends a permanent notification to the private logging channel.
- **Execution Details:** Logs specify which channel was locked, the staff member who performed the action, and the exact timestamp.

---

# Requirements
Permissions:
- **User:** Must have permission to manage channels or moderate the server (Admin/Moderator recommended).
- **Bot:** Manage Channels, View Channels, Send Messages, Embed Links.

---

# Notes
- **Channel Specific:** The lock only applies to the channel where the command was executed.
- **Staff Access:** Moderators and Administrators with specific permission overrides may still be able to post in locked channels depending on your server's role hierarchy.
- **Reversing:** To restore public access, the corresponding `/unlock` command must be used.
