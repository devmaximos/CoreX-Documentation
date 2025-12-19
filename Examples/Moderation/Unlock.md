# Moderation System: Unlock Command

---

## Overview

The **Unlock Command** allows staff members to restore message permissions in a previously locked channel. This command re-enables interaction for regular members once a situation has been resolved or maintenance is complete.

When a channel is unlocked, the bot updates the channel permissions and logs the action in the moderation logs to maintain a complete history of channel status changes.

---

# Command Usage
```bash
/unlock
```

# How to Unlock a Channel
1. Navigate to the locked channel you wish to open.
2. Type `/unlock` in the message bar.
3. Press **Enter** to execute.


---

# What the System Does
- **Restores Permissions:** Resets channel permissions to allow members to send messages again.
- **Public Confirmation:** Posts a "Channel Unlocked" embed in the active channel to notify users that it is open for discussion.
- **Automated Logging:** Sends a permanent log entry to the private logging channel.
- **Detailed Reporting:** Logs include the specific channel name, the staff member who performed the action, and the exact timestamp.

---

# Requirements
Permissions:
- **User:** Must have permission to manage channels or moderate the server (Admin/Moderator recommended).
- **Bot:** Manage Channels, View Channels, Send Messages, Embed Links.

---

# Notes
- **Channel Specific:** The unlock command only affects the specific channel where it is run.
- **Instant Effect:** Public access is restored immediately upon the successful execution of the command.
