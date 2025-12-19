# Anti-Ping Protection System

---

## Overview

The **Anti-Ping Protection** system allows server administrators to protect specific roles from being mentioned. When a protected role is pinged, the system can automatically respond, delete the offending message, and notify the user via DM.

⚠️ **Important Requirement** The Anti-Ping system **must be enabled from the config panel** in order to function.

---

# Command Usage

/config

# How to Enable Anti-Ping
1. Run the `/config` command.
2. Navigate to **Plugins** and then the **Anti-Ping** section.
3. Click on **Configure Plugins** and select **Anti-Ping**.
4. Use the **Toggle Feature** button to enable the system.

---

# Configuration Options

The system offers a clean, user-friendly editor within the `/config` menu to customize protection behavior:

### Protection Settings
- **Set Protected Roles:** Choose which roles cannot be mentioned.
- **Set Bypass Roles:** Choose roles that are allowed to ping protected roles.
- **Set Bypass Members:** Grant specific members permission to ping protected roles.

### Response Actions
- **Toggle Delete Message:** Automatically remove the message that contained the unauthorized ping.
- **Toggle DM User:** Send a private message to the user explaining why their ping was restricted.
- **Set Log Channel:** Select an optional channel to log all ping violations.

---

# What the System Does
- **Monitors Mentions:** Scans messages for pings directed at protected roles.
- **Role-Based Security:** Applies restrictions based on the user's role and the target's role.
- **Automated Moderation:** Instantly reacts to violations based on your "Delete" and "DM" preferences.
- **Audit Logging:** Keeps a record of violations in your configured log channel for staff review.

---

# Requirements
Permissions:
- **User:** Must have permission to manage server configuration (Admin recommended).
- **Bot:** Manage Messages (to delete pings), View Channels, Send Messages.

---

# Notes
- **Live Updates:** Changes made in the editor apply instantly.
- **Bypass Priority:** Bypass roles and members will never trigger the anti-ping response, even when mentioning a protected role.
- **Clean Editor:** All settings can be managed through buttons and dropdowns without needing manual command strings.
