# Promotion System

---

## Overview

The **Promotion System** is a dedicated tool for staff to officially announce and log the advancement of community or staff members. By using a single command, the bot generates a professional announcement, ensuring that milestones are recognized and recorded in the designated logs.

⚠️ **Important Requirement** The **Promotion Plugin** must be **Enabled** from the `/config` panel. You must also select a **Promotion Log Channel** for the announcements to be posted.

---

# Configuration Guide

To set up the system:
1. Run `/config` and navigate to **Plugins** -> **Promotion**.
2. **Select Promotion Log Channel:** Choose the channel where promotion announcements will be sent.
3. **Set allowed staff roles:** Choose the staff managers that can promote your staffs
4. **Set staff team role (optional):** Choose the pre-existed staff role of your server
5. **Set Promotable Ranks:** Choose the list of roles that can be promoted. 
You can also edit the embed texts via the buttons below the embed.

---

# Command Usage

### For Staff/Admins
```bash
/promote issue:[user]  reason:[text] rank:[role(from configured promotable roles)]
```
*Announces a user's promotion from their previous rank to a new rank with a specific reason. The announcement is sent to the configured log channel.*

---

# Key Features
- **Official Announcements:** Creates a clean, standardized embed for every promotion, featuring the staff member responsible and the reason for the change.
- **Rank Tracking:** Clearly displays the transition from the **Old Rank** to the **New Rank**.
- **Centralized Logging:** Keeps all promotion history in one channel for easy reference and server transparency.
- **Automated Workflow:** Eliminates the need for manual embed creation when promoting staff or members.

---

# Requirements
Permissions:
- **Staff:** Must have Administrator or a designated role with permission to use the `/promote` command.
- **Bot:** View Channels, Send Messages, Embed Links.

Configuration:
- **Promotion Plugin** must be **Enabled** in the `/config` section.
- **Promotion Log Channel** must be set.

---

# Notes

- **Visual Confirmation:** Upon running the command, the bot will provide a confirmation message indicating the promotion was successfully logged.
