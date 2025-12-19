# Purge Command

---

## Overview

The **Purge System** allows staff members to quickly delete a specified number of recent messages in a channel. This is essential for cleaning up spam, removing off-topic discussions, or clearing accidental message bursts. 

When messages are purged, the bot provides a temporary confirmation in the current channel and logs the action permanently in the moderation logs.

---

# Command Usage

/purge amount:[number]

# How to Purge Messages
1. Type `/purge` in the channel you wish to clean.
2. Enter the **amount** of messages to delete.
3. Press **Enter** to execute.



---

# What the System Does
- **Bulk Deletion:** Removes up to 1000 messages at once from the current channel.
- **Immediate Feedback:** Displays a confirmation embed in the active channel stating exactly how many messages were removed.
- **Automated Logging:** Sends a detailed log to the logging channel.
- **Audit Trail:** The log entry includes the total messages purged, the channel where it occurred, the executor, and a timestamp.

---

# Requirements
Permissions:
- **User:** Must have permission to manage messages (Admin/Moderator recommended).
- **Bot:** Manage Messages, View Channels, Send Messages, Embed Links.

---

# Notes
- **Log Permanence:** While the "Purged" message in the public channel is temporary, the entry in the logging channel provides a permanent record of the moderator's action.
- **Limit:** The system supports purging a maximum of 1000 messages per command.
