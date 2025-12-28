# Softban Command

---

## Overview

The **Softban System** is a specialized moderation tool designed to quickly remove a user and clear their recent message history. This action effectively "kicks" the user by banning them to delete their messages and then immediately lifting the ban so they may rejoin the server if they have an invite.

This is an ideal solution for handling users who have flooded channels with spam or inappropriate content but do not require a permanent ban.

---

# Command Usage

```bash
/softban user:[member] days:[0-7] reason:[text]
```


# How to Softban a Member
1. Type `/softban` in an active moderation or logs channel.
2. Select the **user** you wish to softban.
3. Specify the number of **days** of message history to delete (up to 7 days).
4. Provide a **reason** for the action (e.g., "test").
5. Press **Enter** to execute.


---

# What the System Does
- **Automated Ban/Unban:** Simultaneously bans the user to purge messages and then unbans them immediately.
- **Message Cleanup:** Deletes the user's message history for the specified number of days (up to 7 days).
- **Immediate Feedback:** Displays a "Softbanned" confirmation card in the channel where the command was executed.
- **Detailed Logging:** Sends a permanent record to the logging channel, including the target, reason, number of days of messages deleted, the moderator responsible, and a timestamp.

---

# Requirements
Permissions:
- **User:** Must have the **Ban Members** and **Manage Messages** permissions (Admin/Moderator recommended).
- **Bot:** Ban Members, Manage Messages, View Channels, Send Messages, Embed Links.

---

# Notes
- **Rejoining:** Because the ban is immediately lifted, the user is free to rejoin the server as soon as they have a valid invite link.
- **Role Hierarchy:** The bot cannot softban users whose highest role is equal to or higher than its own.
- **Message Recovery:** Note that once messages are deleted via a softban, they cannot be recovered.
