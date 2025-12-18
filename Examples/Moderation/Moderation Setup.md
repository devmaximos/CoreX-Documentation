# Moderation Commands Setup Tutorial

---

## Overview

This tutorial explains how to properly set up the moderation commands. Before any moderation command can function correctly, the required systems must be enabled through the configuration panel.

Moderation commands rely on the bot’s internal systems and permissions to enforce actions such as warnings, mutes, kicks, bans and channel management.

⚠️ **Important Requirement**  
The **Moderation commands must be enabled from the config panel** for moderation commands to work correctly.

---

```bash
/config
```

All moderation-related systems are configured through the configuration panel accessed via the `/config` command

---

# How to Set Up Moderation Commands
1. Run the `/config` command to access the configuration panel.
2. Open the **Plugins** section and select **Moderation Commands** from Plugins (A).
3. Press **Configure Plugins** and then select **Moderation**
4. Configure whitelist settings to protect trusted staff and loggin channel.

Once the Moderation Commands is enabled, moderation commands become fully operational.

---

# What Moderation Commands Do
Moderation commands allow staff to:
- Warn Members
- Kick Members
- Ban Members
- Unban Members
- Timeout Members
- Un-timeout Members
- Manage Channels
- And more features...

---

# Whitelist Requirements
To prevent staff members from being affected by protection systems, trusted users or roles must be whitelisted
Whitelist options available in the config panel:
- Whitelist by role
- Whitelist by user ID

Whitelisted users are excluded from automated enforcement.

---

# Requirements
Permissions:
- **User:** Must have permission to manage server configuration (usually Admin)
- **Bot:** Administrator, View Audit Log, Manage Roles
Configuration:
- Moderation Commands enabled via `/config`

--- 

## Notes
- Moderation commands **will** not function if the Moderation Feature is disabled.
- All configuration changes apply instantly.
- Punishments and actions can be reviewed through Discord Audit Logs.
