# Moderation System: Role Command

---

## Overview

The **Role System** provides staff members with an efficient way to manage user permissions and designations by toggling roles directly via commands. The system is dynamic: it detects whether a user already possesses a specific role and either adds or removes it accordingly.

When a role is toggled, the bot provides immediate visual feedback to the moderator and ensures the change is processed instantly.

---

# Command Usage

```bash
/role user:[member] role:[role]
```

# How to Toggle a Role
1. Type `/role` in an active channel.
2. Select the **user** whose roles you wish to manage.
3. Select the **role** you wish to toggle from the list of available server roles.
4. Press **Enter** to execute.



---

# What the System Does
- **Dynamic Toggling:** Automatically adds the role if the user does not have it, or removes the role if they do.
- **Immediate Feedback:** Displays a "Role Update" confirmation card in the current channel specifying exactly which role was added or removed.
- **Visual Clarity:** Uses specific icons (e.g., a green plus or red minus) to indicate the type of change made to the user's profile.
- **Real-time Processing:** Updates the user's permissions and appearance in the member list instantly upon execution.

---

# Requirements
Permissions:
- **User:** Must have the **Manage Roles** permission (Admin/Moderator recommended).
- **Bot:** Manage Roles, View Channels, Send Messages, Embed Links.

---

# Notes
- **Role Hierarchy:** The bot can only toggle roles that are positioned lower than its own highest role in the server settings.
- **Staff Accountability:** Like all moderation actions, role changes are recorded in the server's native Audit Logs for long-term tracking.
- **Single Role Toggle:** This command focuses on toggling one role at a time to ensure precision in permission management.
