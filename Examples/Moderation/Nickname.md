# Nickname Command

---

## Overview

The **Nickname Command** allows staff members to quickly modify the server-specific name of any member. This is a vital tool for maintaining server organization, enforcing naming conventions, or correcting inappropriate usernames.

When a nickname is changed, the bot instantly updates the user's profile within the server and generates a confirmation of the action.

---

# Command Usage
```bash
/nickname user:[member] nick:[new_name]
```

# How to Change a Nickname
1. Type `/nickname` in an active channel.
2. Select the **user** whose nickname you wish to change.
3. Enter the **new name** you want to assign (e.g., "CoreX best bot").
4. Press **Enter** to execute.


---

# What the System Does
- **Instant Name Update:** Immediately modifies the target user's nickname to the provided text.
- **Execution Feedback:** Provides a brief confirmation that the command was processed successfully.
- **Server Organization:** Helps staff keep the member list uniform and professional.

---

# Requirements
Permissions:
- **User:** Must have the **Manage Nicknames** permission (Admin/Moderator recommended).
- **Bot:** Manage Nicknames, View Channels, Send Messages.

---

# Notes
- **Character Limit:** Ensure the new nickname adheres to Discord's 32-character limit.
- **Role Hierarchy:** The bot cannot change the nickname of users with a role higher than its own.
- **Audit Logs:** While the command provides immediate feedback, the change is also recorded in Discord's native Audit Logs.
